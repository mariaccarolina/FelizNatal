<script>
// Inserindo a lógica
</script>

<template>
  <section>
    <div>
      <img
        src="https://github.com/mariaccarolina/FelizNatal/blob/main/src/assets/logo%20(2).png?raw=true"
        alt="Logo marca Feliz Natal"
      />
      <h1>Uma <span> plataforma de doação </span> para espalhar alegria</h1>
      <p>
        Nessas festas de fim de ano mande um presente para a pessoa amada e
        compartilhe a alegria do Natal.
      </p>
      <button>Fazer uma doação</button>
    </div>
    <figure>
        <img class="meninoNeve" src="https://github.com/mariaccarolina/FelizNatal/blob/main/src/assets/imagem.png?raw=true" alt="Menino olhando presentes">
    </figure>
  </section>
</template>

<style lang="scss">
$cor-button: #CD3C32;
$font-titulos: "Archivo", sans-serif;
$font-texto:"Roboto", sans-serif;

@mixin flex{
     display: flex;
     align-items: center;
     justify-content: space-around;
}

@mixin btn{
    background-color: $cor-button;
    padding: 10px 20px;
    color: white;
    border: none;

}

section{
    @include flex();
    height: 50vh;
    background-color: #FFE9E8;
    span{
        color: #CD3C32;
    }
    @media (max-width: 800px){
        flex-direction: column;
        height: 90vh;
    }
    div{
        width: 30vw;
        height: 35vh;
        @include flex();
        flex-direction: column;
        align-items: flex-start;

        @media (max-width: 900px){
        height: 30vh;
        align-items: center;
        text-align: center;
        width: 60vw;
    }

    @media (max-width: 450px){
        width: 90vw;
        height: 50vh;
    }
    }

    p{
        font-family: $font-titulos;
        font-weight: 400;
    }
}

h1{
    font-family: $font-titulos;
    font-size: 32px;
    font-style: 600;
    @media (max-width: 900px){
      font-size: 24px;
    }
}

button{
    @include btn();
    font-family: $font-texto;
    font-weight: 700;
    border-radius: 5px;

      @media (max-width: 450px){
        width: 90vw;
    }
}

.meninoNeve{
    width: 30vw;
     @media (max-width: 800px){
        width: 60vw;
    }
    @media (max-width: 450px){
        width: 90vw;
    }
}
</style>
