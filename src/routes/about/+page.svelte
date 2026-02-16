<svelte:head>
  <title>Profil Desa - Pemerintah Desa Seberida</title>
  <meta name="description" content="Profil lengkap Desa Seberida meliputi geografi, demografi, ekonomi, dan pemerintahan" />
</svelte:head>

<div class="w-full space-y-4 sm:space-y-6">
  <section class="neo-card p-5 sm:p-8 lg:p-10">
    <div class="mb-4 sm:mb-6">
      <span class="gov-badge">Profil Desa</span>
    </div>
    <h1 class="gov-heading mb-4 text-2xl sm:mb-6 sm:text-3xl lg:text-4xl">
      Tentang Desa Seberida
    </h1>

    <div class="space-y-4 sm:space-y-6">
      <!-- Gambaran Umum -->
      <div>
        <h2 class="gov-heading mb-2 text-lg sm:mb-3 sm:text-xl">Gambaran Umum</h2>
        <p class="mb-3 text-sm leading-relaxed text-slate-600 sm:mb-4 sm:text-base">
          Desa Seberida adalah sebuah desa di Kecamatan Batang Gansal, Kabupaten Indragiri Hulu, Provinsi Riau. Sebagai Desa Asli yang didirikan sekitar tahun 1918 Masehi, Seberida memiliki sejarah panjang dan kaya akan budaya serta kearifan lokal.
        </p>
        <p class="text-sm leading-relaxed text-slate-600 sm:text-base">
          Nama "Seberida" berasal dari kata "belida", sejenis ikan yang melimpah di Sungai Seberida. Dari masa ke masa, nama ini mengalami transformasi linguistik hingga menjadi identitas khas desa yang melambangkan kelimpahan dan kehidupan berkelanjutan.
        </p>
      </div>

      <!-- Geografi -->
      <div class="neo-inset p-4 sm:p-6">
        <h3 class="gov-heading mb-2 flex items-center gap-2 text-base sm:mb-3 sm:text-lg">
          <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>
          Kondisi Geografis
        </h3>
        <div class="grid gap-3 sm:grid-cols-2 sm:gap-4">
          <div>
            <dt class="mb-1 text-xs font-medium sm:text-sm" style="color: var(--gov-primary);">Luas Wilayah</dt>
            <dd class="text-xs text-slate-600 sm:text-sm">Sekitar 154 km²</dd>
          </div>
          <div>
            <dt class="mb-1 text-xs font-medium sm:text-sm" style="color: var(--gov-primary);">Ketinggian</dt>
            <dd class="text-xs text-slate-600 sm:text-sm">25-50 mdpl</dd>
          </div>
          <div>
            <dt class="mb-1 text-xs font-medium sm:text-sm" style="color: var(--gov-primary);">Topografi</dt>
            <dd class="text-xs text-slate-600 sm:text-sm">Dataran rendah dengan perbukitan</dd>
          </div>
          <div>
            <dt class="mb-1 text-xs font-medium sm:text-sm" style="color: var(--gov-primary);">Iklim</dt>
            <dd class="text-xs text-slate-600 sm:text-sm">Tropis dengan curah hujan tinggi</dd>
          </div>
        </div>
      </div>

      <!-- Demografi -->
      <div>
        <h3 class="gov-heading mb-3 flex items-center gap-2 text-lg">
          <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" />
          </svg>
          Kependudukan
        </h3>
        <div class="space-y-3">
          <p class="text-sm text-slate-600">
            Desa Seberida dihuni oleh sekitar <strong>8.500 jiwa</strong> yang terdiri dari berbagai suku dan etnis, menciptakan harmoni dalam keberagaman.
          </p>
          <div class="grid gap-3 sm:grid-cols-3">
            <div class="rounded-lg bg-blue-50 p-3">
              <div class="text-2xl font-bold" style="color: var(--gov-primary);">2.100+</div>
              <div class="text-xs text-slate-600">Kepala Keluarga</div>
            </div>
            <div class="rounded-lg bg-blue-50 p-3">
              <div class="text-2xl font-bold" style="color: var(--gov-primary);">51%</div>
              <div class="text-xs text-slate-600">Laki-laki</div>
            </div>
            <div class="rounded-lg bg-blue-50 p-3">
              <div class="text-2xl font-bold" style="color: var(--gov-primary);">49%</div>
              <div class="text-xs text-slate-600">Perempuan</div>
            </div>
          </div>
        </div>
      </div>

      <!-- Ekonomi -->
      <div class="neo-inset p-6">
        <h3 class="gov-heading mb-3 flex items-center gap-2 text-lg">
          <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>
          Perekonomian
        </h3>
        <p class="mb-3 text-sm text-slate-600">
          Perekonomian desa bertumpu pada sektor:
        </p>
        <ul class="space-y-2 text-sm text-slate-600">
          <li class="flex items-start gap-2">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0" style="color: var(--gov-primary);" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
            </svg>
            <span><strong>Pertanian dan Perkebunan:</strong> Kelapa sawit, karet, padi, dan hortikultura</span>
          </li>
          <li class="flex items-start gap-2">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0" style="color: var(--gov-primary);" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
            </svg>
            <span><strong>Perikanan:</strong> Perikanan air tawar di sungai dan kolam</span>
          </li>
          <li class="flex items-start gap-2">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0" style="color: var(--gov-primary);" fill="currentColor" viewBox="0 0 20 20">
              <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
            </svg>
            <span><strong>UMKM:</strong> Perdagangan, jasa, dan industri rumah tangga</span>
          </li>
        </ul>
      </div>

      <!-- Infrastruktur -->
      <div>
        <h3 class="gov-heading mb-3 flex items-center gap-2 text-lg">
          <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
          </svg>
          Fasilitas Publik
        </h3>
        <div class="grid gap-3 sm:grid-cols-2">
          <div class="rounded-lg border-l-4 border-blue-900 bg-blue-50 p-3">
            <div class="text-sm font-medium" style="color: var(--gov-primary);">Pendidikan</div>
            <div class="mt-1 text-xs text-slate-600">3 SD/MI, 2 SMP/MTs, 1 SMA, PAUD</div>
          </div>
          <div class="rounded-lg border-l-4 border-blue-900 bg-blue-50 p-3">
            <div class="text-sm font-medium" style="color: var(--gov-primary);">Kesehatan</div>
            <div class="mt-1 text-xs text-slate-600">1 Puskesmas, 3 Posyandu, Polindes</div>
          </div>
          <div class="rounded-lg border-l-4 border-blue-900 bg-blue-50 p-3">
            <div class="text-sm font-medium" style="color: var(--gov-primary);">Ibadah</div>
            <div class="mt-1 text-xs text-slate-600">5 Masjid, 8 Musholla, 2 Gereja</div>
          </div>
          <div class="rounded-lg border-l-4 border-blue-900 bg-blue-50 p-3">
            <div class="text-sm font-medium" style="color: var(--gov-primary);">Infrastruktur</div>
            <div class="mt-1 text-xs text-slate-600">Jalan aspal, listrik PLN, air bersih</div>
          </div>
        </div>
      </div>

      <!-- Pemerintahan -->
      <div class="neo-inset p-6">
        <h3 class="gov-heading mb-3 flex items-center gap-2 text-lg">
          <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
          </svg>
          Struktur Pemerintahan
        </h3>
        <div class="space-y-3">
          <div>
            <div class="text-sm font-medium" style="color: var(--gov-primary);">Kepala Desa</div>
            <div class="text-sm text-slate-600">Ria Saprina</div>
          </div>
          <div class="text-sm text-slate-600">
            Pemerintahan desa didukung oleh perangkat desa yang terdiri dari Sekretaris Desa, Kaur (Kepala Urusan), dan Kepala Dusun yang bekerja melayani masyarakat dengan penuh dedikasi.
          </div>
        </div>
      </div>
    </div>
  </section>
</div>
