<template>
  <div class="home">

    <section id="home-1">
      <h1>Hi, My name is MUHAAFIDZ</h1>
      <h2>I am a <span id="role">WEB</span> DEVELOPER</h2>
    </section>

    <section id="home-2">
      <h2 class="section-title">Discover</h2>
      <div class="card-container">
        <a class="card-1" href="https://github.com/muhaafidz" target="_blank" rel="nofollow">
          <h4 class="card-title">LinkedIn</h4>
        </a>
        <a class="card-1" href="https://my.linkedin.com/in/muhaafidz-md-saufi" target="_blank" rel="nofollow">
          <h4 class="card-title">Github</h4>
        </a>
        <a class="card-1" href="https://codepen.io/muhaafidz" target="_blank" rel="nofollow">
          <h4 class="card-title">Code Pen</h4>
        </a>
      </div>
    </section>
    
    <section id="home-3">
      <h2 class="section-title">Skillset</h2>
      <div class="card-container">
        <div class="card-1">
          <h4 class="card-title">Web Development</h4>
        </div>
        <div class="card-1">
          <h4 class="card-title">Video Game Development</h4>
        </div>
        <div class="card-1">
          <h4 class="card-title">Video & Graphics Editing</h4>
        </div>
      </div>
    </section>

    <section id="home-4">
      <h2 class="section-title">My Career Journey</h2>
      <div class="card-container">
        <div class="card-1 card-career">
          <h4 class="card-title">Graphics Designer <span>@Percetakan Berkat Karisma</span></h4>
        </div>
        <div class="card-1 card-career">
          <h4 class="card-title">AR Developer <span>@Karangkraf</span></h4>
        </div>
        <div class="card-1 card-career">
          <h4 class="card-title">Software Developer <span>@Genecare</span></h4>
        </div>
        <div class="card-1 card-career">
          <h4 class="card-title">Web Developer <span>@Pipeline Network</span></h4>
        </div>
        <div class="card-1 card-career">
          <h4 class="card-title">Web Developer Engineer <span>@Doo Group</span></h4>
        </div>
      </div>
    </section>

  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  },
  data () {
    return {
      name: 'hahaha',
      arr: [
        {
          title: 'jojojo',
          description: 'jajaja'
        },
        {
          title: 'rororo',
          description: 'rururu'
        }
      ]
    }
  },
  updated: function () {
    // this.role_loop();
  }
}
</script>

<style lang="scss">
  section {
    margin: 0 50px;
    padding: 50px 0;
  }
  section:not(:last-child) {
    border-bottom: 1px solid #CCCCCC;
  }
  .section-title {
    margin-bottom: 16px;
  }

  .card-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;

    .card-1 {
      cursor: pointer;
      background: #FAFAFA;
      margin: 15px;
      width: 100%;
      max-width: 300px;
      padding: 50px;
      border-radius: 5px;
      box-shadow: 1px 1px 6px 6px #00000011;
      transition: 0.3s;
      text-decoration: none;
      &:hover {
        background:#FFFFFF;
        transition: 0.3s;
        transform: translateY(-10px);
        .card-title {
          color: #b94287;
        }
      }
    }
  }
  .card-career {
    span {
      color: #888888;
    }
  }
</style>