<template>
  <div>
    <div class="c-toolbar u-mb-0">
      <div class="l-container">
        <ol class="c-breadcrumb">
          <li class="c-breadcrumb__item">
              <a href="#" class="c-breadcrumb__link">Home</a>
          </li>
          <li class="c-breadcrumb__item">
            <router-link to="/" class="c-breadcrumb__link">Dashboard</router-link>
          </li>
        </ol>
      </div>
    </div>
    <main class="l-app__main" role="main">
      <div class="l-container">     
        <alert>Your are in dashboard.</alert>
      </div>
    </main>
  </div>
</template>

<script>
  export default {
    name: 'DashBoardView'
  }
</script>
