<template>
  <nav class="navbar navbar-expand-lg navbar-light  navigation">
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav align-items-center">
        <li class="active">
          <a class="active" href="#">HOME</a>
        </li>
        <li class="">
          <a class="" href="#">ABOUT US</a>
        </li>
        <li class="">
          <a class="" href="#">CONTACT</a>
        </li>
        <button class="mr-4 log_in">LOG IN</button>
        <button class="sign_up">SIGN UP</button>
      </ul>
    </div>
  </nav>
</template>
<style>
.navigation {
  position: absolute;
  z-index: 1;
  margin-left: 40%;
  margin-top: 31px;
}
button {
  width: 152px;
  height: 50px;
  border-radius: 25px;
  border: solid 1px #111111;
}
ul li a {
  margin-right: 25px;
  list-style: none;
  width: 127px;
  height: 50.2px;
  font-family: Montserrat;
  font-size: 20px;
  color: #302e2f !important;
}
ul li a.active,
ul li a:hover {
  text-decoration: none;
  border-bottom: 2px solid black;
}
.log_in {
  background-color: transparent;
  outline: none;
}
.sign_up {
  background-color: black;
  font-size: 20px;
  font-weight: 900;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.9;
  letter-spacing: normal;
  text-align: center;
  color: #edcb50;
}
</style>
