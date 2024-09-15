<script></script>

<template>
    <section class="terceiraSessao">
    <img class="maos" src="https://github.com/mariaccarolina/FelizNatal/blob/main/src/assets/illustration%20(1).png?raw=true" alt="enfeite da arvore de natal">
    <div>
        <h2>Conectando generosidade
ao redor do mundos</h2>
        <p>Celebre a magia do Natal de uma maneira especial! Descubra a plataforma que permite a doação de presentes significativos para aqueles que mais precisam. Faça parte do movimento e compartilhe o verdadeiro espírito da generosidade.</p>
        <button>Fazer uma doação</button>
    </div>
    </section>
</template>

<style lang="scss">
.terceiraSessao{
    background-color: white;
    margin: 6rem 0;

     @media (max-width: 900px){
        flex-direction: column;
        height: 70vh;
    }

    .maos{
        @media (max-width: 550px){
      width: 60vw;
    }
    }
}
</style>