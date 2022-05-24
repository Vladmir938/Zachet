<template>
  <div class="container-fluid">
    <div class="shadow-none p-3  bg-white rounded">
      <nav class="navbar navbar-expand-lg bg-white">
        <span class="border container-fluid">
          <a class="navbar-brand" href="#"><img src="../../img/icon/employer.png" height="40" width="40"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarText">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li>
                <p class="nav-link ">Capacity planning</p>
              </li>
              <li>
                <button type="button" class="btn btn-outline-secondary">руководитель</button>
              </li>
            </ul>
            <span class="navbar-text">
              Окончание периода редактирования отчетов : 27.12.2020
            </span>
            <span class="navbar-text">
              <a class="nav-link " aria-current="page" href="#">Декабрь 2020
              <img src="../../img/icon/info.svg" width="21" height="21">
              </a>
            </span>
          </div>
        </span>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyEmployer"
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