<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>


<template>
  <div>
    <!--HEADER-->
    <header class="hero_header">
        <div class="padd_m flex_bet">
            <div class="">
                <router-link to="/logo"><span class="logo">MAGOBOLLA</span></router-link>
            </div> 
            <div class=""> 
                <ul class="ms_flex ms_menu">
                    <li class="padd_left"><router-link to="/spettacoli">SPETTACOLI</router-link></li>
                    <li class="padd_left"><router-link to="/blog">BLOG</router-link></li>
                    <li class="padd_left"><router-link to="/curriculum">CV</router-link></li>
                    <li class="padd_left"><a href="#">CONTATTI</a></li>
                </ul>
            </div>
        </div>
  </header>

  <main>
    <RouterView />
  </main>

  <!--Css => "style" è da rimuovere; è usato solo ai fini di template testing-->
  <footer class="indigo">  
        <div class="test-border0 test-footer">
            <div class="test-border1 container" style="padding: 0.3%; padding-top: 25px;"><div class="row s-12"><div class="col s-12 center"><h3>Logo</h3></div></div></div> 
            <div class="test-border1 container" style="margin-right: 2%; padding: 1px;"> 
                <div class="row s-12 test-flex0 test-border2 test-flex-dir0" style="padding: 2%; padding: 1px; padding-right: 25px; display: flex;"> 
                    <div class="col s-4 test-border3" style="padding: 1px; margin: 1%; text-align: center;"><router-link to="/" style="color: black;">Link</router-link></div>
                    <div class="col s-4 test-border3" style="padding: 1px; margin: 1%; text-align: center;"><router-link to="/" style="color: black;">Link</router-link></div>
                    <div class="col s-4 test-border3" style="padding: 1px; margin: 1%; text-align: center;"><router-link to="/" style="color: black;">Link</router-link></div>
                    <div class="col s-4 test-border3" style="padding: 1px; margin: 1%; text-align: center;"><router-link to="/" style="color: black;">Link</router-link></div>
                </div>
            </div>
        </div>
    </footer>    

  </div>
</template>