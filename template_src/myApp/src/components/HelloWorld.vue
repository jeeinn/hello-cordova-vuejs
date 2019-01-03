<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li>
        <a
          href="https://cordova.apache.org/"
          target="_blank"
        >
          Cordova
        </a>
      </li>
      <li>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Vue
        </a>
      </li>
      <li>
        <a
          href="https://github.com/jeeinn"
          target="_blank"
        >
          Github
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Cordova & Vue.js App'
    }
  },
  mounted: function () {
    // test for cordova ready
    var app = {
      // Application Constructor
      initialize: function () {
        document.addEventListener('deviceready', this.onDeviceReady.bind(this), false)
      },

      // deviceready Event Handler
      //
      // Bind any cordova events here. Common events are:
      // 'pause', 'resume', etc.
      onDeviceReady: function () {
        this.receivedEvent('deviceready')
      },

      // Update DOM on a Received Event
      receivedEvent: function (id) {
        console.log('Received Event: ' + id)
      }
    }
    app.initialize()

    setTimeout(function () { console.log('hello vue.') }, 5000)
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
