<script>
  import "../app.css";
  import Header from "../component/Nav.svelte";
  import Footer from "../component/Footer.svelte";
  let { children } = $props();
</script>

<div class="min-h-screen flex flex-col" style="background-color: var(--neo-bg);">
  <Header />
  <main class="mx-auto flex w-full max-w-6xl flex-1 items-start justify-center px-4 py-6 sm:px-6">
    {@render children()}
  </main>
  <Footer />
</div>
