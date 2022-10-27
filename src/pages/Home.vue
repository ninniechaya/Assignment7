<template>
  <div>
    <Navbar />
    <section class="home">
      <div class="image">
        <img src="https://scontent.fbkk13-2.fna.fbcdn.net/v/t39.30808-6/288559449_1436527996843444_4328702160863813768_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=8NtD-UlQECYAX8eJzWI&_nc_ht=scontent.fbkk13-2.fna&oh=00_AT_Y10tBUKOQyRostvhKGif6C9O8s3PO7NH1JlJ1XrVGJQ&oe=63461E69" alt="" />
      </div>
      <div class="content">
        <h3>hi, i am {{name}}</h3>
        <span>Belive the Impossible is Possible.</span>
        <p>
          {{motto}}
        </p>
        <p>{{content}}</p>
        <router-link to="/about" class="btn">
          about me <i class="fas fa-user"></i>
        </router-link>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
export default {
  components: { Navbar },
  data() {
    return {
      name: "Chayanin Pinjungern",
      motto:"JUB JUB",
      content:"JUB MUA",
    };
  },
};
</script>

<style>
</style>