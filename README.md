<!--- div classes--->
<div class="welcome">
    HELLO AND WELCOME TO MY GITHUB! 👋
</div>

<div class="text">
    
    A little bit about me 💻

   -   I like to keep learning 🎓
   -   I am interested in the cloud ☁️ 
   -   Love Linux 🐧
   -   Highly adaptable 🚀

</div>

<!--styling-->
<style>
    .welcome {
        text-shadow: 2px 2px deepskyblue;
        font-weight: 900;
        font-size: 30px;
        position: relative;
        white-space: nowrap;
        animation: scroll-left 20s linear infinite;
        color: wheat
    }

    @keyframes scroll-left {
            from {
        left: 100%;
        width: 500%; 
        }
            to {
        left: -100%;
        width: 500%;
        }
    }

</style>

<!--scripting-->
<script>
function scrollleft() {
    document.getElementById("scrolling-text").style.left = '100%';
    setTimeout(scrollleft, 25);
  }
   scrollleft();

</script>