<template>
  <section class="section is-large">
    <div class="container has-text-left">
      <h1 class="title">Hi, I'm 
        <a href="/about" class="name-link">
          Kaelan
        </a> 
      </h1>
      
      <h2 class="subtitle need-padding">a Software Developer based in Detroit, Michigan.</h2>
    </div>
    <projecttile></projecttile>
  </section>
</template>

<script>
import ProjectTile from '../components/ProjectTile'

export default {
  components: {
    ProjectTile
  }
}
</script>

<style>
.name-link {
    color: #555555;
    display: inline;
    border-bottom: 4px dashed #999999;
    text-decoration: none;
    transition: ease 0.5s;

}
.need-padding {
  padding: 10px;
}
</style>