<template>
  <div  class="container-md">
      <NavManagement/>
      <div class="row">
          <div class="col-12 col-md">
              <TypePanel/>
          </div>
          <div class="col-12 col-md">
              <TypePanel/>
          </div>
      </div>
  </div>
</template>

<script>
// @ is an alias to /src

import NavManagement from "../components/NavManagement";
import TypePanel from  "../components/TypePanel"
export default {
  components: {TypePanel, NavManagement}
}
</script>
