

<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-dark ">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Gestion de eventos</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Inicio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Enlace</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              Dropdown
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><Router-link class="dropdown-item" to="/">Home</Router-link></li>
              <li><Router-link class="dropdown-item" to="/new">New user</Router-link></li>
              <li><Router-link class="dropdown-item" to="/list">List user</Router-link></li>
              <li><Router-link class="dropdown-item" to="/registro">Sing Up</Router-link></li>
            </ul>
          </li>

        </ul>

      </div>
    </div>
  </nav>
  <div class="container-fluid">
    <RouterView />
  </div>
</template>

