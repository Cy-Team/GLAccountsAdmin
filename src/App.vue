<template>
  <div id="app">
    <header>
      <nav class="navbar navbar-default navigation-clean">
        <div class="container">
          <div class="navbar-header">
            <a href="#" class="navbar-brand navbar-link">Company Name</a>
            <button data-toggle="collapse" data-target="#navcol-1" class="navbar-toggle collapsed">
              <span class="sr-only">Toggle navigation</span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
            </button>
          </div>
          <div class="collapse navbar-collapse" id="navcol-1">
            <ul class="nav navbar-nav navbar-right">
              <li role="presentation" class="active">
                <a href="#">
                  <i class="glyphicon glyphicon-user"></i>First Item</a>
              </li>
              <li role="presentation">
                <a href="#">
                  <i class="glyphicon glyphicon-envelope"></i>Second Item</a>
              </li>
              <li role="presentation">
                <a href="#">Third Item</a>
              </li>
              <li class="dropdown">
                <a data-toggle="dropdown" aria-expanded="false" href="#" class="dropdown-toggle">Dropdown
                  <span class="caret"></span>
                </a>
                <ul role="menu" class="dropdown-menu">
                  <li role="presentation">
                    <a href="#">First Item</a>
                  </li>
                  <li role="presentation">
                    <a href="#">Second Item</a>
                  </li>
                  <li role="presentation">
                    <a href="#">Third Item</a>
                  </li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>

</style>
