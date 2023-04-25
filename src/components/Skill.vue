<template>
    <div id="skill">
      <div id="todo-card">
        <div class="container-fluid">
          <div class="alert alert-dark">
            <h1>{{ msg3 }}</h1>
          </div>
          <h5>{{ training }}</h5>
          <h5>{{ seminars }}</h5>
          <h5>{{ technologies }}</h5>
          <h5>{{ proglang }}</h5>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'skill',
    data() {
      return {
        msg3: 'This is the Skill Component',
        training: 'Training: w3schools',
        seminars: "Seminars: 'Into Coding 2023', 'Understanding Web Server'",
        technologies: 'Technologies: N/A',
        proglang: 'Programming Language: Java, Python, HTML, Dart, Flutter',
      };
    },
  };
  </script>
  