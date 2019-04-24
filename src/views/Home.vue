<template>
    <div class="wrap">
        <header class="header">
        <h1 class="header-title">
            <router-link to="/">START BOOTSTRAP</router-link>
        </h1>
            <headernav></headernav>
        </header>
        <div class="container">
            <div class="spot">
                <img src="../assets/profile.png" alt="list logo" >
                <h2 class="spot-title">START BOOTSTRAP</h2>
                <p class="spot-text">Web Developer - Graphic Artist - User Experience Designer</p>
            </div>

            <div class="section section-portfolio">
                <h3 class="section-title-black">PORTFOLIO</h3>
                <list></list>
            </div>

            <div class="section section-about">
                <h3 class="section-title-black">ABOUT</h3>
                <div class="about-text-area">
                    <p class="section-text">Freelancer is a free bootstrap theme created by Start Bootstrap. The download includes the complete source files including HTML, CSS, and JavaScript as well as optional LESS stylesheets for easy customization.</p>
                    <p class="section-text">Whether you're a student looking to showcase your work, a professional looking to attract clients, or a graphic artist looking to share your projects, this template is the perfect starting point!</p>
                </div>
            </div>

            <div class="section">
            
            </div>

            <div class="section">
            
            </div>            
        </div>
        <footer class="footer">
        
        </footer>
    </div>
</template>

<script>
// @ is an alias to /src
import headernav from '@/components/nav.vue'
import list from '@/components/list.vue'

export default {
  name: 'home',
  components: {
    headernav : headernav,
    list : list
  }
}
</script>
