# db
$this->database->createDatabase($this->input->post('ehealth'));

 public function createDatabase($ehealth){
    if ($this->dbforge->create_database($ehaelth))
    {
       return true;
    }
}


NAV bar. under viws-users and admin
<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="#">Ehealth</a>
    </div>
    <ul class="nav navbar-nav">
      <li class="active"><a href="#">Home</a></li>
      <li class="dropdown">
        <a class="dropdown-toggle" data-toggle="dropdown" href="#">Page 1
        <span class="caret"></span></a>
        <ul class="dropdown-menu">
          <li><a href="#">login</a></li>
          <li><a href="#">signup</a></li>
          <li><a href="#">logout</a></li>
        </ul>
      </li>
      <li><a href="#">create patients details</a></li>
      <li><a href="#">update details</a></li>
    </ul>
  </div>
</nav>
