<script></script>

<template>
    <footer>
        <img class="logo" src="https://github.com/mariaccarolina/FelizNatal/blob/main/src/assets/logo%20(2).png?raw=true" alt="logomarca">
        <nav>
            <img src="https://github.com/mariaccarolina/FelizNatal/blob/main/src/assets/Frame%202.png?raw=true" alt="redes sociais">
        </nav>
    </footer>
</template>

<style lang="scss">
footer{
    display: flex;
    justify-content: space-between;
    padding: 0 10%;
    background-color: #FFE9E8;
    height: 8vh;
    align-items: center;

    @media (max-width: 900px){
        flex-direction: column;
        align-items: center;
        height: 15vh;
        justify-content: space-around;

        .logo{
            width: 30vw;
        }
    }


}
</style>