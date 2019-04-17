<template>
  <div id="div">
    <AppHeader></AppHeader>
    <Appconterne></Appconterne>
    <AppBeijing></AppBeijing>
    <AppFooter></AppFooter>
    <AppBeijing2></AppBeijing2>

  </div>
</template>
<script>
import AppHeader from "@/components/AppHeader"
import Appconterne from "@/components/Appconterne"
import AppBeijing from "@/components/AppBeijing"
import AppFooter from "@/components/AppFooter"
import AppBeijing2 from "@/components/AppBeijing2"

export default {
    components:{ AppHeader,Appconterne,AppBeijing,AppFooter,AppBeijing2}
}
</script>
