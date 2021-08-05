<template>
  <div class="home">
    <div class="title">Matthew Brignola</div>
    <div class="title">Sample Web Development Portfolio</div>
    <div class="title">My Github</div>
    <div class="title">
      <a id="blue" href="https://github.com/PrismaticDevelopmentStudios"
        >https://github.com/PrismaticDevelopmentStudios</a
      >
    </div>
    <table>
      <tr>
        <td @click="reaction">
          <h1>
            <a href="https://reaction-timer.netlify.app" target="_blank"
              >Reaction Timer</a
            >
          </h1>
          - This site was built with the Vue.js framework and utilizes the
          scripting capabilities I used to build a basic reaction timer which
          displays different output based on JavaScript timing functions.
        </td>
        <td @click="calendar">
          <h1>
            <a href="https://prismatic-calendar.netlify.app" target="_blank"
              >Calendar</a
            >
          </h1>
          - This is a simple example of JavaScript's date and time functions.
        </td>
        <td @click="animals">
          <h1>
            <a href="https://cute-animals.netlify.app" target="_blank"
              >Cute Animals</a
            >
          </h1>
          - This site is an example of using anchor tags with hrefs to create
          links within webpages.
        </td>
        <td @click="media">
          <h1>
            <a href="https://checkmate-media.netlify.app" target="_blank"
              >Media Site</a
            >
          </h1>
          This site is a mock media companies website, with booking links.
        </td>
        <td @click="tic">
          <h1>
            <a href="https://primatic-tic-tac-toe.netlify.app/" target="_blank"
              >Tic-Tac-Toe</a
            >
          </h1>
          - This site is another example of JavaScript timing functions.
        </td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
  methods: {
    resume() {
      window.open("https://matthew-brignola.netlify.app"), "_blank";
      console.log("resume");
    },
    reaction() {
      window.open("https://reaction-timer.netlify.app", "_blank");
    },
    calendar() {
      window.open("https://prismatic-calendar.netlify.app", "_blank");
    },
    animals() {
      window.open("https://cute-animals.netlify.app");
    },
    media() {
      window.open("https://checkmate-media.netlify.app");
    },
    tic() {
      window.open("https://primatic-tic-tac-toe.netlify.app");
    },
  },
};
</script>

<style scoped>
h1 {
  margin: 0;
}

td:hover {
  background: wheat;
}

td {
  cursor: pointer;
  text-align: left;
  padding: 1%;
}
td:hover {
  border-radius: 15px;
}
#blue:hover {
  color: blue;
}
</style>
