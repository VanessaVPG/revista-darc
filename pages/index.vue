<template>
    <main>
        <section class="container d-flex flex-column justify-content-center">
            <div class="logo">
            <b-img src="~/assets/img/logo.svg" alt=""></b-img>
        </div>
        <div class="abra-sua-mente d-flex justify-content-center align-items-center position-absolute">
            <NuxtLink to="/Sections">
                  <h1 class="text-center">ABRA SUA MENTE<span>|</span></h1>  
            </NuxtLink>
            
        </div>
        <div class="abra-sua-mente-sombra2 position-relative"></div>
        <div class="abra-sua-mente-sombra1 position-relative"></div>
        
            
        </section>
        
    </main>
</template>
<style scoped>
@keyframes example {
  0%   {opacity: 100%;}
  25%  {opacity: 50%;}
  50%  {opacity: 25%;}
  100% {opacity: 0%}
}
  
.container{
    width: 1000px;
}
main {
    height: 100vh;
    background: url('~/assets/img/background.png') no-repeat fixed;
    background-size: cover ;   
}

.abra-sua-mente{
    top: 500px;
    text-decoration: none;
    z-index: 1;
    background:#0C0B0D;
    width: 17.238125rem;
    height: 5.086875rem;
    border-radius: 10px;
}
.abra-sua-mente span{
animation-name: example;
animation-duration: 100000000 ;
}
a{
    text-decoration: none;
}
a:hover{
  transform: matrix3d();
}
.abra-sua-mente h1{
    font-size: 1.5rem;
    color: #FED616;

}
.abra-sua-mente-sombra1{
    
    width: 17.238125rem;
    height: 5.086875rem;
    border-radius: 10px;
    bottom:-82px;
    left:7px;
    background: hsla(194, 99%, 65%, 1);


}
.abra-sua-mente-sombra2{
    width: 17.238125rem;
    height: 5.086875rem;
    border-radius: 10px;
    bottom:-170px;
    left:12px;
    background: hsla(326, 98%, 80%, 1);
}


</style>