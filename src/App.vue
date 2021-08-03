<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
      <Grid></Grid>
      <VuesaxTheme/>
      <VuesaxButton/>
      <VuesaxButton2/>
      <VuesaxButton3/>
      <VuesaxButtonGradient/>
      <VuesaxButtonRelief/>
      <VuesaxButtonTransparent/>
      <VuesaxButtonShadow/>
      <VuesaxButtonColor/>
      <VuesaxButtonIcon/>
      <VuesaxButtonIconText/>
      <VuesaxButtonAlert/>
      <Input/>
  </div>
</template>

<script>
    import Input from '@/components/Input.vue';
    import VuesaxButtonAlert from '@/components/Alert.vue';
    import VuesaxButtonIconText from '@/components/VuesaxButtonIconText.vue';
    import VuesaxButtonIcon from '@/components/VuesaxButtonIcon.vue';
    import VuesaxButtonColor from '@/components/VuesaxButtonColor.vue';
    import VuesaxButtonShadow from '@/components/VuesaxButtonShadow.vue';
    import VuesaxButtonTransparent from '@/components/VuesaxButtonTransparent.vue';
    import VuesaxButtonRelief from '@/components/VuesaxButtonRelief.vue';
    import VuesaxButtonGradient from '@/components/VuesaxButtonGradient.vue';
    import VuesaxButton3 from '@/components/VuesaxButton3.vue';
    import VuesaxButton2 from '@/components/VuesaxButton2.vue';
    import VuesaxButton from '@/components/VuesaxButton.vue';
    import VuesaxTheme from '@/components/VuesaxTheme.vue';
    import Grid from '@/components/Grid.vue';
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
      Grid,
      VuesaxTheme,
      VuesaxButton,
      VuesaxButton2,
      VuesaxButton3,
      VuesaxButtonGradient,
      VuesaxButtonRelief,
      VuesaxButtonTransparent,
      VuesaxButtonShadow,
      VuesaxButtonColor,
      VuesaxButtonIcon,
      VuesaxButtonIconText,
      VuesaxButtonAlert,
      Input,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
    height: 8000px;
  margin-top: 60px;
    padding-bottom: 50px;
}
</style>
