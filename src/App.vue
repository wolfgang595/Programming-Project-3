<script>
export default {
  mounted() {
    const plugin = document.createElement("script");
    plugin.setAttribute(
      "src",
      "D:\School\Fall 2024\Advanced Web Design\CITP4316\programming-project-3\src\main.js"
    );
    plugin.async = true;
    document.head.appendChild(plugin);
  }
};
</script>
<template>
 <h1>Stopwatch</h1>


 <div id="timeContainer"> <!-- create box container for stopwatch  -->

<div id="timeDisplay">00:00:00</div>" <!-- display stopwatch zeros -->

<button id="startButton" class="timerButton">Start</button> <!--  create a start button -->
<button id="pauseButton" class="timerButton">Pause</button> <!--  create a Pause button -->
<button id="resetButton" class="timerButton">Reset</button> <!--  create a Reset button -->









<!--   -->
</div>
</template>


