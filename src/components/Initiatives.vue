<template>
    <div class="intiatives">
      <h2>Sign Up If...
      </h2>
      <div class="intiatives-list">
        <ul>
            <li>You are a black-owned or ally-owned cannabis-business needing tech resources (i.e. website, app) </li>
            <li>You are a creative that has a specific service to offer a cannabis-business (i.e. graphic designer, copywriting)</li>
            <li>You are really interested to see what unfolds in this space</li>
        </ul>
      </div>
    </div>
  </template>
  <script>
  export default {
    name: 'Initiatives'
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  
  .intiatives {
    /* display: flex; */
    justify-items: center;
    max-width: 525px;
    order: 2;
  }
  
.intiatives-list {
    color: red;
}

  h2 {
    text-transform: uppercase;
    color: red;
  }
  
  </style>
  