<svelte:head>
  <title>Kontak - Pemerintah Desa Seberida</title>
  <meta name="description" content="Hubungi Pemerintah Desa Seberida - alamat kantor, telepon, email, dan peta lokasi" />
</svelte:head>

<div class="w-full space-y-4 sm:space-y-6">
  <!-- Header -->
  <section class="neo-card p-5 sm:p-8 lg:p-10">
    <div class="mb-4 sm:mb-6">
      <span class="gov-badge">Hubungi Kami</span>
    </div>
    <h1 class="gov-heading mb-3 text-2xl sm:mb-4 sm:text-3xl lg:text-4xl">
      Kontak Pemerintah Desa Seberida
    </h1>
    <p class="text-sm leading-relaxed text-slate-600 sm:text-base">
      Kami siap melayani Anda. Silakan hubungi kami melalui saluran resmi yang tersedia di bawah ini.
    </p>
  </section>

  <!-- Contact Grid -->
  <div class="grid gap-4 sm:gap-6 lg:grid-cols-2">
    <!-- Alamat Kantor -->
    <div class="neo-card p-5 sm:p-6">
      <div class="mb-3 flex items-center gap-3 sm:mb-4">
        <div class="rounded-lg bg-blue-100 p-3">
          <svg class="h-6 w-6" style="color: var(--gov-primary);" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
          </svg>
        </div>
        <h2 class="gov-heading text-lg">Alamat Kantor</h2>
      </div>
      <div class="neo-inset p-4">
        <p class="text-sm font-medium text-slate-700">Kantor Desa Seberida</p>
        <p class="mt-2 text-sm text-slate-600">
          Jl. Raya Seberida<br />
          Desa Seberida, Kec. Batang Gansal<br />
          Kabupaten Indragiri Hulu<br />
          Provinsi Riau 29352<br />
          Indonesia
        </p>
      </div>
    </div>

    <!-- Jam Layanan -->
    <div class="neo-card p-6">
      <div class="mb-4 flex items-center gap-3">
        <div class="rounded-lg bg-blue-100 p-3">
          <svg class="h-6 w-6" style="color: var(--gov-primary);" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>
        </div>
        <h2 class="gov-heading text-lg">Jam Layanan</h2>
      </div>
      <div class="neo-inset p-4">
        <div class="space-y-3 text-sm">
          <div class="flex justify-between">
            <span class="text-slate-600">Senin - Kamis</span>
            <span class="font-medium text-slate-700">08:00 - 16:00 WIB</span>
          </div>
          <div class="flex justify-between">
            <span class="text-slate-600">Jumat</span>
            <span class="font-medium text-slate-700">08:00 - 16:00 WIB</span>
          </div>
          <div class="flex justify-between border-t border-slate-200 pt-3">
            <span class="text-slate-600">Sabtu - Minggu</span>
            <span class="font-medium text-red-600">Libur</span>
          </div>
        </div>
        <p class="mt-3 text-xs text-slate-500">
          * Tutup pada hari libur nasional dan cuti bersama
        </p>
      </div>
    </div>

    <!-- Telepon -->
    <div class="neo-card p-6">
      <div class="mb-4 flex items-center gap-3">
        <div class="rounded-lg bg-blue-100 p-3">
          <svg class="h-6 w-6" style="color: var(--gov-primary);" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
          </svg>
        </div>
        <h2 class="gov-heading text-lg">Telepon</h2>
      </div>
      <div class="neo-inset p-4">
        <p class="text-sm text-slate-600">Hubungi kami melalui:</p>
        <p class="mt-2 text-lg font-medium text-slate-700">(0768) 123-4567</p>
        <p class="mt-1 text-xs text-slate-500">Senin - Jumat, 08:00 - 16:00 WIB</p>
      </div>
    </div>

    <!-- Email -->
    <div class="neo-card p-6">
      <div class="mb-4 flex items-center gap-3">
        <div class="rounded-lg bg-blue-100 p-3">
          <svg class="h-6 w-6" style="color: var(--gov-primary);" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
          </svg>
        </div>
        <h2 class="gov-heading text-lg">Email</h2>
      </div>
      <div class="neo-inset p-4">
        <p class="text-sm text-slate-600">Kirim surat elektronik ke:</p>
        <a 
          href="mailto:desa.seberida@outlook.co.id" 
          class="mt-2 inline-block text-base font-medium underline"
          style="color: var(--gov-primary);"
        >
          desa.seberida@outlook.co.id
        </a>
        <p class="mt-2 text-xs text-slate-500">Respon dalam 1-2 hari kerja</p>
      </div>
    </div>
  </div>

  <!-- Peta Lokasi -->
  <section class="neo-card overflow-hidden p-6">
    <div class="mb-4">
      <h2 class="gov-heading mb-2 flex items-center gap-2 text-xl">
        <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
        </svg>
        Peta Lokasi
      </h2>
      <p class="text-sm text-slate-600">Temukan kami di peta untuk kunjungan langsung</p>
    </div>
    <div class="neo-inset overflow-hidden">
      <iframe
        class="h-80 w-full border-0"
        title="Peta Lokasi Desa Seberida"
        style="filter: grayscale(20%);"
        allowfullscreen
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3989.507570962715!2d102.50738091003568!3d-0.7151036992749193!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e290d23a913b8fd%3A0x32716bddf6e74693!2sKantor%20Desa%20Seberida!5e0!3m2!1sid!2ssg!4v1696593800995!5m2!1sid!2ssg"
      ></iframe>
    </div>
  </section>

  <!-- Pengaduan -->
  <section class="neo-card p-8">
    <div class="mb-6">
      <h2 class="gov-heading mb-2 flex items-center gap-2 text-xl">
        <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z" />
        </svg>
        Layanan Pengaduan dan Aspirasi
      </h2>
      <p class="text-sm text-slate-600">
        Masyarakat dapat menyampaikan pengaduan, kritik, saran, atau aspirasi terkait pelayanan publik dan pembangunan desa.
      </p>
    </div>
    <div class="neo-inset p-4">
      <p class="text-sm text-slate-600">
        Pengaduan dapat disampaikan secara langsung ke kantor desa pada jam kerja atau melalui email resmi. Setiap pengaduan akan ditindaklanjuti sesuai prosedur yang berlaku dengan prinsip transparansi dan akuntabilitas.
      </p>
    </div>
  </section>
</div>
