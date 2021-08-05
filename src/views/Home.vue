<template>
  <div class="home">
    <div class="title-one">Matthew Brignola's</div>
    <div class="title">Sample Web Development Portfolio</div>
    <div class="title">
      My Github:
      <a
        id="blue"
        href="https://github.com/PrismaticDevelopmentStudios"
        target="_blank"
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
          This site was built with the Vue.js framework and utilizes the
          scripting capabilities I used to build a basic reaction timer which
          displays different output based on JavaScript timing functions.
        </td>
      </tr>
      <tr>
        <td @click="calendar">
          <h1>
            <a href="https://prismatic-calendar.netlify.app" target="_blank"
              >Calendar</a
            >
          </h1>
          This is a simple example of JavaScript's date and time functions.
        </td>
      </tr>
      <tr>
        <td @click="animals">
          <h1>
            <a href="https://cute-animals.netlify.app" target="_blank"
              >Cute Animals</a
            >
          </h1>
          This site is an example of using anchor tags with hrefs to create
          links within webpages.
        </td>
      </tr>
      <tr>
        <td @click="media">
          <h1>
            <a href="https://checkmate-media.netlify.app" target="_blank"
              >Media Site</a
            >
          </h1>
          This site is a mock media company's website, with booking links.
        </td>
      </tr>
      <tr>
        <td @click="tic">
          <h1>
            <a href="https://primatic-tic-tac-toe.netlify.app/" target="_blank"
              >Tic-Tac-Toe</a
            >
          </h1>
          This site is an example of Vue.js functional methods and web design.
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
table {
  width: 50%;
  margin-left: auto;
  margin-right: auto;
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
  box-shadow: 1px 2px 3px rgb(0, 0, 0, 0.5);
}
#blue:hover {
  color: blue;
}
.title-one {
  font-size: 2.5em;
  font-family: "Courier New", Courier, monospace;
  font-weight: 600;
}
</style>
