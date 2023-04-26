<script> // script para importar el archivo Header.svelte que es la cabecera del sitio
    import Header from './components/Header.svelte'; 
    import Footer from './components/Footer.svelte';
</script>

<Header /> <!-- importa la cabecera por medio del script -->

<main>
    <p>MAIN</p>
</main>

<style>
    main{
        max-width: 960px;
        margin: 40px auto;
    }
</style>

<Footer /> <!-- importa el footer por medio del script -->