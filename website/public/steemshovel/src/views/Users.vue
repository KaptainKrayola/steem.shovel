<template>
  <div>
    <div class="c-toolbar u-mb-0">
      <div class="l-container">
        <ol class="c-breadcrumb">
          <li class="c-breadcrumb__item">
              <a href="#" class="c-breadcrumb__link">Home</a>
          </li>
          <li class="c-breadcrumb__item">
            <router-link to="/users" class="c-breadcrumb__link">User</router-link>
          </li>
        </ol>
      </div>
    </div>
    <main class="l-app__main" role="main">
      <div class="l-container"> 
        <alert type="info">Your are in users.</alert>
      </div>
    </main>
  </div>
</template>

<script>
  export default {
    name: 'UsersView'
  }
</script>
