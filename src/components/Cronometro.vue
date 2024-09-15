<script>
</script>

<template>
    <div class="container-cronometro">
        <h3>Tempo limitado</h3>
        <p class="texto">Nessas festas de fim de ano mande um presente para a pessoa amada e compartilhe a alegria do Natal.</p>
        <h2>10d -24h - 01m  - 52s</h2>
        <img src="https://github.com/mariaccarolina/FelizNatal/blob/main/src/assets/illustration.png?raw=true" alt="presentes de natal">
    </div>
</template>

<style lang="scss">
$font-titulos: "Archivo", sans-serif;
$font-texto:"Roboto", sans-serif;

.container-cronometro{
    height: 60vh;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;

    img{
        width: 25vw;
         @media (max-width: 750px){
         width: 60vw;
    }
    }

    h2{
        color: #CD3C32;
        font-weight: 600;
        font-size: 32px;
    }
}

h3{
     font-family:  $font-titulos;
        font-weight: 600;
        font-size: 30px;

         @media (max-width: 450px){
         font-size: 24px;
    }
}

.texto{
    font-family: $font-titulos;
    width: 30vw;
    text-align: center;
    @media (max-width: 450px){
         width: 70vw;
    }
}
</style>