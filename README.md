# db
$this->database->createDatabase($this->input->post('ehealth'));

 public function createDatabase($ehealth){
    if ($this->dbforge->create_database($ehaelth))
    {
       return true;
    }
}


<nav class="navbar navbar-dark bg-dark">
  <!-- Navbar content -->
 <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">login</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">signup</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Doctor
        </a>
        <div class="dropdown-menu" doctor="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">create patient record</a>
          <a class="dropdown-item" href="#">update record</a>
          <a class="dropdown-item" href="#">logout</a>
        </div>
      </li>
    </ul>
  </div>
</nav>
</nav>



