<template>
    <div id="education">
      <div id="todo-card">
        <div class="container-xxl">
          <h1>{{ msg2 }}</h1>
          <h5>{{ elem }}</h5>
          <h5>{{ jhs }}</h5>
          <h5>{{ shs }}</h5>
          <h5>{{ college }}</h5>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'education',
    data() {
      return {
        msg2: 'This is the Education Component',
        elem: "Nursery - Grade 6: L'Altra Montessori School Inc.",
        jhs: "Grade 7 - Grade 10: L'Altra Montessori School Inc.",
        shs: 'Grade 11 - Grade 12: Angeles University Foundation Integrated-School',
        college: 'College: Holy Angel University',
      };
    },
  };
  </script>
  