<script lang="tsx">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from './components/HelloWorld.vue';

@Component({
  components: {
    HelloWorld,
  }
})
export default class App extends Vue {
  render() {
    return (
      <div id="app">
        <img alt="Vue logo" src={require('./assets/logo.png')}/>
        <HelloWorld msg={'Welcome to Your Vue.js + TypeScript App'}/>
      </div>
    )
  }
}
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
