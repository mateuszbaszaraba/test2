<template>
    <nav class="navbar navbar-default">
  <div class="container-fluid">
    <div class="navbar-header">
      <router-link class="navbar-brand" to="/">Stock Trader</router-link>
    </div>

    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <router-link to="/portfolio" tag="li" activeClass="active"><a>Portfolio</a></router-link>
        <router-link to="/stocks" tag="li" activeClass="active"><a>Stocks</a></router-link>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#">End Day</a></li>
        <li class="dropdown">
          <a 
            href="#" 
            class="dropdown-toggle" 
            data-toggle="dropdown" 
            role="button" 
            aria-haspopup="true" 
            aria-expanded="false">Save & Load <span class="caret"></span></a>
          <ul class="dropdown-menu">
            <li><a href="#">Save Data</a></li>
            <li><a href="#">Load Data</a></li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>