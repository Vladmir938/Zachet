<template>
  <div class="container-fluid">
     <nav class="navbar navbar-expand-lg bg-white">
        <span class="border border-white container-fluid">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarText">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li>
                <div class="dropdown">
                  <button class="btn btn btn-outline-secondary dropdown-toggle" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Капитализация
                  </button>
                  <div class="dropdown-menu" aria-labelledby="dropdownMenu2">
                    <button class="dropdown-item" type="button">Action</button>
                    <button class="dropdown-item" type="button">Another action</button>
                    <button class="dropdown-item" type="button">Something else here</button>
                  </div>
                </div>
              </li>
            </ul>
            <span class="navbar-text">
              <div class="form-check">
                <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
                <label class="form-check-label" for="flexCheckDefault">
                  Скрывать заполненные строки
                </label>
              </div>
            </span>
            <span class="navbar-text">
              <a class="nav-link " aria-current="page" href="#">
                <button type="button" class="btn btn-primary btn-lg">Подтвердить</button>
              </a>
            </span>
          </div>
        </span>
      </nav>
  </div>
  <div class="container-fluid" >
    <table class="table table-striped">
      <thead>
      <tr>
        <th scope="col">#</th>
        <th scope="col">First</th>
        <th scope="col">Last</th>
        <th scope="col">Handle</th>
      </tr>
      </thead>
      <tbody>
      <tr>
        <th scope="row">1</th>
        <td>Mark</td>
        <td>Otto</td>
        <td>@mdo</td>
      </tr>
      <tr>
        <th scope="row">2</th>
        <td>Jacob</td>
        <td>Thornton</td>
        <td>@fat</td>
      </tr>
      <tr>
        <th scope="row">3</th>
        <td>Larry</td>
        <td>the Bird</td>
        <td>@twitter</td>
      </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: "MyTable"
}
</script>

<style scoped>
p {
  font-size: 24px;
  color: black;
  margin-top: 10px;
}

button {
  margin-top: 20px;
  margin-left: 20px;
}
</style>