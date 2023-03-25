<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>


<template>
  <!--Css => "style" è da rimuovere; è usato solo ai fini di template testing-->
  <header class="teal accent-3">
        <div class="test-border0 test-header">
            <div class="test-border1 test-flex0" style="margin-left: 0.5%; padding: 0.3%;"><router-link to="/">Logo</router-link></div> 
            <div class="test-border1 test-flex0" style="margin-right: 1%; padding: 1px;"> 
                <div class="test-flex0 test-border2" style="padding: 2%; padding: 1px; padding-right: 35px;">
                    <div class="test-border3" style="padding: 2%; margin: 1%;"><router-link to="/spettacoli">Spettacoli</router-link></div>
                    <div class="test-border3" style="padding: 2%; margin: 1%;"><router-link to="/curriculum">Curriculum</router-link></div>
                    <div class="test-border3" style="padding: 2%; margin: 1%;"><router-link to="/blog">Blog</router-link></div>
                </div>
            </div>
        </div>
  </header>

  <main>
    <RouterView />
  </main>

  <!--Css => "style" è da rimuovere; è usato solo ai fini di template testing-->
  <footer class="indigo">  
        <div class="test-border0 test-footer">
            <div class="test-border1 test-flex0" style="padding: 0.3%; padding-top: 25px;">Logo</div> 
            <div class="test-border1 test-flex0" style="margin-right: 2%; padding: 1px;"> 
                <div class="test-flex0 test-border2 test-flex-dir0" style="padding: 2%; padding: 1px; padding-right: 25px; display: flex; justify-content: center;"> 
                    <div class="test-border3" style="padding: 2%; padding-right: 10px; margin: 1%;">Spettacoli</div>
                    <div class="test-border3" style="padding: 2%; padding-right: 10px; margin: 1%;">CV</div>
                    <div class="test-border3" style="padding: 2%; padding-right: 10px; margin: 1%;">Blog</div>
                </div>
            </div>
        </div>
    </footer>    
  
</template>