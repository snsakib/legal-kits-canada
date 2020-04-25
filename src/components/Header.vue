<template>
  <div class="header">
    <div role="navigation" class="navbar navbar-default site-nav">
      <div class="container-fluid dark-ash">
        <div class="row nav-container p-0 m-0">
          <div class="col-lg-3 ">
            <div class="navbar-header site-header ">
              <a href="index.html" class="navbar-brand p-0">
                <img class="img-fluid site-logo" src="../assets/img/logo_web.png" />
              </a>

              <div class="navbar-buttons custom-nav-btn">
                <button
                  type="button"
                  data-toggle="collapse"
                  data-target=".navbar-collapse"
                  class="navbar-toggle navbar-btn"
                >
                  <i class="fa fa-align-justify"></i>
                </button>
              </div>
            </div>
          </div>
          <div class="col-lg-9 pr-0  orange-bottom-border site-nav-content">
            <div id="navigation" class="collapse navbar-collapse">
              <ul class="nav navbar-nav nav-likns site-nav-pages">
                <li class="dropdown">
                  <a href="#" data-toggle="dropdown" class="dropdown-toggle">
                    Relationships <b class="caret"></b
                  ></a>
                  <ul class="dropdown-menu">
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                  </ul>
                </li>

                <li class="dropdown">
                  <a href="#" data-toggle="dropdown" class="dropdown-toggle"
                    >Finances<b class="caret"></b
                  ></a>
                  <ul class="dropdown-menu">
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                  </ul>
                </li>

                <li class="dropdown">
                  <a href="#" data-toggle="dropdown" class="dropdown-toggle"
                    >Death<b class="caret"></b
                  ></a>
                  <ul class="dropdown-menu">
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                  </ul>
                </li>

                <li class="dropdown">
                  <a href="#" data-toggle="dropdown" class="dropdown-toggle"
                    >Money-Back Gaurantee<b class="caret"></b
                  ></a>
                  <ul class="dropdown-menu">
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                    <li><a href="#">...</a></li>
                  </ul>
                </li>
              </ul>

              <ul class="nav navbar-nav site-login-options">
                <li><a href="#">Login</a></li>
                <li><a href="#">Sign Up</a></li>
                <li>
                  <a href="#">
                    <span class="site-login">
                      <img class="img-fluid" src="../assets/img/cart-icon.png" />
                    </span>
                    <span>Cart</span>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style></style>
