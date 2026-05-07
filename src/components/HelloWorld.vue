<script setup>
</script>

<template>
  <!-- Navbar Section -->
  <div class="contact-aria flex items-center justify-center lg:gap-7 gap-3 bg-red-100 py-3 flex-wrap">
    <div class="contact flex items-center">
      <span><i class="fa-solid fa-phone text-[#28B463]"></i></span>
      <p class="ml-3 text-[14px] text-[#333] font-medium">Phone:+01784400984</p>
    </div>
    <div class="contact flex items-center">
      <span><i class="fa-solid fa-envelope text-[#28B463]"></i></span>
      <p class="ml-3 text-[14px] text-[#333] font-medium">Email: info@example.com</p>
    </div>
    <div class="contact flex items-center">
      <span><i class="fa-solid fa-location-dot text-[#28B463]"></i></span>
      <p class="ml-3 text-[14px] text-[#333] font-medium">Location: 28/A Street, The king city, USA</p>
    </div>
  </div>
  <nav class="bg-white shadow py-5">
    <div class="container px-2 lg:px-0 mx-auto">
      <div class="nav-menu flex items-center justify-between">
        <div class="brand-name">
          <img class="w-full h-10" src="/public/images/brand-logo.webp" alt="Brand-Name">
        </div>
        <ul class="lg:flex hidden items-center justify-between gap-8 text-[#555555] font-medium">
          <li><a class="text-[#28B463]" href="#">Home</a></li>
          <li><a
              class="relative inline-block hover:text-[#28B463] after:content-[''] after:absolute after:left-0 'after:-top-0' after:w-0 after:h-0.5 after:bg-[#28B463] after:transition-all after:duration-300 hover:after:w-7"
              href="#">Services</a></li>
          <li><a
              class="relative inline-block hover:text-[#28B463] after:content-[''] after:absolute after:left-0 'after:-top-0' after:w-0 after:h-0.5 after:bg-[#28B463] after:transition-all after:duration-300 hover:after:w-7"
              href="#">Portfolio</a></li>
          <li><a
              class="relative inline-block hover:text-[#28B463] after:content-[''] after:absolute after:left-0 'after:-top-0' after:w-0 after:h-0.5 after:bg-[#28B463] after:transition-all after:duration-300 hover:after:w-7"
              href="#">Blogs</a></li>
          <li><a
              class="relative inline-block hover:text-[#28B463] after:content-[''] after:absolute after:left-0 'after:-top-0' after:w-0 after:h-0.5 after:bg-[#28B463] after:transition-all after:duration-300 hover:after:w-7"
              href="#">Pages</a></li>
          <li><a
              class="relative inline-block hover:text-[#28B463] after:content-[''] after:absolute after:left-0 'after:-top-0' after:w-0 after:h-0.5 after:bg-[#28B463] after:transition-all after:duration-300 hover:after:w-7"
              href="#">Contact</a></li>
          <button
            class="bg-[#28B463] p-3 px-4 text-white rounded hover:bg-white border transition-all border-[#28B463] hover:text-[#28B463]">
            Get A Quote</button>
        </ul>
        <!-- Mobile-Menu-icons -->
        <div class="lg:hidden text-2xl"><i class="fa-solid fa-bars"></i></div>
      </div>
    </div>
  </nav>
  <!-- Navbar End -->
</template>
