<template>
    <div id="profile">
      <div id="todo-card">
        <div class="container">
          <div class="alert alert-primary" role="alert">
            <h1>{{ msg1 }}</h1>
            <h5>{{ objective }}</h5>
            <h5>{{ name }}</h5>
            <h5>{{ course }}</h5>
            <h5>{{ specialization }}</h5>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'profile',
    data() {
      return {
        msg1: 'This is the Profile Component',
        objective: 'Objective: To finish this activity by the end of the day.',
        name: 'Name: April Gomez',
        course: 'Course: Bachelor of Science in Information Technology',
        specialization: 'Specialization: Major in Web Development',
      };
    },
  };
  </script>
  