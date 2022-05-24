<template>
  <nav class="navbar navbar-expand-lg bg-white">
    <div class="container-fluid">
      <img src="../../img/logo.png" height="56" width="120"/>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" aria-current="page" href="#">
              <img src="../../img/icon/services.svg" height="16" width="16">
              Сервисы
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" href="#">
              <img src="../../img/icon/find.svg" height="16" width="16">
              Поиск
            </a>
          </li>
        </ul>
      </div>
      <div class="d-flex flex-row justify-content-between">
        <div class="p-2"><img src="../../img/icon/megaphone.svg" height="25" width="25"></div>
        <div class="p-2"><img src="../../img/icon/bell.svg" height="16" width="19"></div>
        <div class="p-2"><img src="../../img/icon/profile.svg" height="40" width="40"></div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "MyHeader"
}
</script>

<style scoped>
a {
  color: black;
}

.d-flex p-2 {
  padding: 10px;
}
</style>