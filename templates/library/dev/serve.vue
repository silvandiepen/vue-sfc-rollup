<script<% if (ts) { %> lang="ts"<% } %>>
import Vue from 'vue';
import { <%-componentNamePascal%>Sample } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    <%-componentNamePascal%>Sample,
  }
});
</script>

<template>
  <div id="app">
    <<%-componentName%>-sample />
  </div>
</template>
