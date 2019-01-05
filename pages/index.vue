<template>
<div class="home-page">
  <section class="intro">
    <h1>Get the lasted updates</h1>

  </section>
  <section class="featured-posts">
    <postPreview 
      id="1" title="The revolution" 
      thumbnail="https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2011/06/Computer-Code.jpg"
      previewText="Lorem the way we do have to develop the knowledge as per mega watts"/>

    <postPreview 
      id="2" title="Napolitaner" 
      thumbnail="https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2011/06/Computer-Code.jpg"
      previewText="Lorem the way we do have to develop the knowledge as per mega watts"/>

    <postPreview 
      id="3" title="Time Machine" 
      thumbnail="https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2011/06/Computer-Code.jpg"
      previewText="Lorem the way we do have to develop the knowledge as per mega watts"/>

  </section>

</div>
</template>
<script>
import postPreview from '~/components/posts/postPreview'
export default {
  components:{
    postPreview
  }
}
</script>


<style scoped>
.intro {
  height: 300px;
  position: relative;
  padding: 30px;
  box-sizing: border-box;
  background-image: url('~assets/images/background1.jpg');
  background-position: center;
  background-size: cover;
}

.intro h1 {
  position: absolute;
  top: 10%;
  left: 5%;
  width: 90%;
  font-size: 1.5rem;
  color: black;
  background-color: rgb(211, 211, 211);
  text-align: center;
  padding: 10px;
  border-radius: 10px;
  box-shadow: 3px 3px 3px black;
  box-sizing: border-box;
  border: 1px solid black;
}

@media (min-width: 768px) {
  .intro h1 {
    font-size: 2rem;
  }
}

.featured-posts {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>