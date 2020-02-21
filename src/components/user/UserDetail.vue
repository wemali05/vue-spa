<template>
    <div>
      <h3>Some User Details</h3>
      <p>Loaded user has Id: {{ $route.params.id }}</p>
      <router-link 
        tag="button"
        :to="'/user/' + $route.params.id + '/edit'"
        class="btn btn-primary"
        >Edit User</router-link>
    </div>
</template>