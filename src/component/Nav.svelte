<script>
  import { base } from "$app/paths";
  
  let mobileMenuOpen = $state(false);
  
  function toggleMenu() {
    mobileMenuOpen = !mobileMenuOpen;
  }
  
  function closeMenu() {
    mobileMenuOpen = false;
  }
</script>

<header class="sticky top-0 z-50 neo-card mb-4 sm:mb-6">
  <div class="mx-auto flex w-full max-w-6xl flex-col px-3 py-3 sm:px-6 sm:py-4">
    <div class="flex items-center justify-between">
      <div class="flex items-center gap-2 sm:gap-3">
        <div class="flex h-10 w-10 flex-shrink-0 items-center justify-center rounded-xl bg-gradient-to-br from-blue-900 to-blue-700 text-white shadow-lg sm:h-12 sm:w-12">
          <svg class="h-5 w-5 sm:h-7 sm:w-7" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
          </svg>
        </div>
        <div>
          <a href={`${base}/`} class="gov-heading text-base sm:text-xl lg:text-2xl">Desa Seberida</a>
          <p class="text-xs text-slate-600">Kec. Batang Gansal</p>
        </div>
      </div>
      
      <!-- Desktop Navigation -->
      <nav class="hidden items-center gap-1 md:flex">
        <a href={`${base}/`} class="neo-btn text-sm">Beranda</a>
        <a href={`${base}/about`} class="neo-btn text-sm">Profil</a>
        <a href={`${base}/contact`} class="neo-btn text-sm">Kontak</a>
        <a href={`${base}/history`} class="neo-btn text-sm">Sejarah</a>
      </nav>
      
      <!-- Mobile Menu Button -->
      <button 
        onclick={toggleMenu}
        class="neo-btn p-2 md:hidden"
        aria-label="Menu navigasi"
        aria-expanded={mobileMenuOpen}
      >
        <svg class="h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          {#if mobileMenuOpen}
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
          {:else}
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          {/if}
        </svg>
      </button>
    </div>
    
    <!-- Mobile Navigation Menu -->
    {#if mobileMenuOpen}
      <nav class="mt-3 flex flex-col gap-2 border-t border-slate-200 pt-3 md:hidden">
        <a href={`${base}/`} class="neo-btn w-full justify-center py-3 text-sm" onclick={closeMenu}>Beranda</a>
        <a href={`${base}/about`} class="neo-btn w-full justify-center py-3 text-sm" onclick={closeMenu}>Profil</a>
        <a href={`${base}/contact`} class="neo-btn w-full justify-center py-3 text-sm" onclick={closeMenu}>Kontak</a>
        <a href={`${base}/history`} class="neo-btn w-full justify-center py-3 text-sm" onclick={closeMenu}>Sejarah</a>
      </nav>
    {/if}
  </div>
</header>
