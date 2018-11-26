<template>
    <div>
        <my-header></my-header>
        <my-list></my-list>
        <my-footer></my-footer>
    </div>
</template>

<script>
import myHeader from './component/index-header'
import myFooter from './component/index-footer'
import myList from './component/index-list'
export default {
  name: 'index',
  components: {
    myHeader,
    myFooter,
    myList
  }
}
</script>

<style scoped>

</style>
