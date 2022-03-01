<script>
    import Nav from "../components/nav.svelte";
</script>


<header>

    <Nav/>
</header>

<main>
    <!-- page content -->
    <div class="container-fluid py-5">
        <slot></slot>
    </div>
</main>

<footer>

</footer>

<style>

</style>