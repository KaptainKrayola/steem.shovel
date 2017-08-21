<template>
  <div id="search-header">
    <form action="#" class="form-inline">
        <div class="form-group">
            <div class="form-control has-iconRight">
                <i class="icon-search form-iconRight u-mr-5"></i>
                <input type="text" class="form-input" name="searchFilter" v-model="searchFilter">
            </div>
        </div>
    </form>
  </div>
</template>

<script>
  export default {
    name: 'searchHeader'
  }
</script>
