<script>
  import { onMount } from "svelte";

  const releaseDate = new Date("2027-02-02T00:00:00.000Z");

  let daysRemaining = $state(0);
  let hoursRemaining = $state(0);
  let minutesRemaining = $state(0);
  let secondsRemaining = $state(0);

  onMount(() => {
    const updateCountdown = () => {
      const now = new Date();
      const timeRemaining = releaseDate - now;

      daysRemaining = Math.floor(timeRemaining / (1000 * 60 * 60 * 24));
      hoursRemaining = Math.floor(
        (timeRemaining % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60)
      );
      minutesRemaining = Math.floor(
        (timeRemaining % (1000 * 60 * 60)) / (1000 * 60)
      );
      secondsRemaining = Math.floor((timeRemaining % (1000 * 60)) / 1000);
    };

    updateCountdown();

    const intervalId = setInterval(updateCountdown, 1000);

    return () => {
      clearInterval(intervalId);
    };
  });
</script>

<svelte:head>
  <title>Portal Resmi Pemerintah Desa Seberida</title>
  <meta name="description" content="Situs web resmi Pemerintah Desa Seberida, Kecamatan Batang Gansal, Kabupaten Indragiri Hulu, Provinsi Riau" />
</svelte:head>

<div class="w-full space-y-4 sm:space-y-6">
  <!-- Hero Section -->
  <section class="neo-card w-full p-5 sm:p-8 lg:p-10">
    <div class="mb-4 flex items-center gap-3 sm:mb-6 sm:gap-4">
      <div class="gov-badge">
        <svg class="h-4 w-4" fill="currentColor" viewBox="0 0 20 20">
          <path fill-rule="evenodd" d="M6 6V5a3 3 0 013-3h2a3 3 0 013 3v1h2a2 2 0 012 2v3.57A22.952 22.952 0 0110 13a22.95 22.95 0 01-8-1.43V8a2 2 0 012-2h2zm2-1a1 1 0 011-1h2a1 1 0 011 1v1H8V5zm1 5a1 1 0 011-1h.01a1 1 0 110 2H10a1 1 0 01-1-1z" clip-rule="evenodd" />
          <path d="M2 13.692V16a2 2 0 002 2h12a2 2 0 002-2v-2.308A24.974 24.974 0 0110 15c-2.796 0-5.487-.46-8-1.308z" />
        </svg>
        <span class="hidden sm:inline">Portal Resmi Pemerintah Desa</span>
        <span class="sm:hidden">Portal Resmi</span>
      </div>
    </div>
    
    <h1 class="gov-heading mb-3 text-2xl sm:mb-4 sm:text-4xl lg:text-5xl">
      Desa Seberida
    </h1>
    <p class="mb-4 text-sm leading-relaxed text-slate-600 sm:mb-6 sm:text-base lg:text-lg">
      Selamat datang di Portal Resmi Pemerintah Desa Seberida. Kami sedang mempersiapkan situs web yang lebih baik untuk melayani masyarakat dengan informasi publik yang transparan dan akuntabel.
    </p>

    <div class="mb-4 grid gap-3 sm:mb-6 sm:grid-cols-3 sm:gap-4">
      <div class="neo-inset p-3 sm:p-4">
        <div class="text-2xl font-bold sm:text-3xl" style="color: var(--gov-primary);">1918</div>
        <div class="mt-1 text-xs font-medium uppercase tracking-wide text-slate-600">Tahun Berdiri</div>
      </div>
      <div class="neo-inset p-3 sm:p-4">
        <div class="text-2xl font-bold sm:text-3xl" style="color: var(--gov-primary);">~8.500</div>
        <div class="mt-1 text-xs font-medium uppercase tracking-wide text-slate-600">Jiwa Penduduk</div>
      </div>
      <div class="neo-inset p-3 sm:col-span-1 sm:p-4">
        <div class="text-2xl font-bold sm:text-3xl" style="color: var(--gov-primary);">154 km²</div>
        <div class="mt-1 text-xs font-medium uppercase tracking-wide text-slate-600">Luas Wilayah</div>
      </div>
    </div>

    <div class="rounded-xl bg-blue-50 p-3 sm:p-4">
      <h3 class="gov-heading mb-2 text-xs sm:mb-3 sm:text-sm">Peluncuran Website dalam:</h3>
      <div class="grid grid-cols-4 gap-2 sm:gap-3">
        <div class="neo-inset p-2 text-center sm:p-3">
          <div class="text-xl font-bold tabular-nums sm:text-2xl" style="color: var(--gov-primary);">
            {daysRemaining}
          </div>
          <div class="mt-1 text-xs font-medium uppercase tracking-wide text-slate-600">
            Hari
          </div>
        </div>
        <div class="neo-inset p-2 text-center sm:p-3">
          <div class="text-xl font-bold tabular-nums sm:text-2xl" style="color: var(--gov-primary);">
            {hoursRemaining}
          </div>
          <div class="mt-1 text-xs font-medium uppercase tracking-wide text-slate-600">
            Jam
          </div>
        </div>
        <div class="neo-inset p-2 text-center sm:p-3">
          <div class="text-xl font-bold tabular-nums sm:text-2xl" style="color: var(--gov-primary);">
            {minutesRemaining}
          </div>
          <div class="mt-1 text-xs font-medium uppercase tracking-wide text-slate-600">
            Menit
          </div>
        </div>
        <div class="neo-inset p-2 text-center sm:p-3">
          <div class="text-xl font-bold tabular-nums sm:text-2xl" style="color: var(--gov-primary);">
            {secondsRemaining}
          </div>
          <div class="mt-1 text-xs font-medium uppercase tracking-wide text-slate-600">
            Detik
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Quick Info -->
  <div class="grid gap-4 sm:grid-cols-2 sm:gap-6">
    <section class="neo-card p-5 sm:p-6">
      <div class="mb-3 flex items-center gap-2">
        <svg class="h-5 w-5 sm:h-6 sm:w-6" style="color: var(--gov-primary);" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
        </svg>
        <h2 class="gov-heading text-base sm:text-lg">Lokasi</h2>
      </div>
      <p class="text-xs leading-relaxed text-slate-600 sm:text-sm">
        Desa Seberida terletak di Kecamatan Batang Gansal, Kabupaten Indragiri Hulu, Provinsi Riau. Berada di kawasan strategis dengan akses jalan yang baik menghubungkan ke pusat kabupaten.
      </p>
    </section>

    <section class="neo-card p-5 sm:p-6">
      <div class="mb-3 flex items-center gap-2">
        <svg class="h-5 w-5 sm:h-6 sm:w-6" style="color: var(--gov-primary);" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z" />
        </svg>
        <h2 class="gov-heading text-base sm:text-lg">Demografi</h2>
      </div>
      <p class="text-xs leading-relaxed text-slate-600 sm:text-sm">
        Masyarakat multikultural dengan keberagaman etnis Melayu, Jawa, Sunda, Batak, dan suku lainnya yang hidup harmonis dalam bingkai Bhinneka Tunggal Ika.
      </p>
    </section>
  </div>
</div>
