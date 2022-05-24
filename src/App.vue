<template>
  <MyHeader />
  <MyEmployer />
  <MyTable />
</template>

<script>
import MyHeader from "@/components/MyHeader";
import MyEmployer from "@/components/MyEmployer";
import MyTable from "@/components/MyTable";

export default {
  name: 'App',
  components: {
    MyHeader,
    MyEmployer,
    MyTable
  }
}
</script>

<style>
#app {

}
</style>
