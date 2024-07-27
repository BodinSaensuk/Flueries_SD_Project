<template>
    <footer class=" bg-white text-pink-800 py-8">
      <div class="container px-4">
        <div class="flex flex-wrap justify-between">
          <div class="w-full md:w-1/4 mb-6 md:mb-0">
            <h3 class="text-lg font-semibold mb-2">Company Name</h3>
            <p class="text-sm">A brief description of your company or website.</p>
          </div>
          <div class="w-full md:w-1/4 mb-6 md:mb-0">
            <h3 class="text-lg font-semibold mb-2">Quick Links</h3>
            <ul class="text-sm">
              <li class="mb-1"><a href="#" class="hover:text-gray-300">Home</a></li>
              <li class="mb-1"><a href="#" class="hover:text-gray-300">About</a></li>
              <li class="mb-1"><a href="#" class="hover:text-gray-300">Services</a></li>
              <li class="mb-1"><a href="#" class="hover:text-gray-300">Contact</a></li>
            </ul>
          </div>
          <div class="w-full md:w-1/4 mb-6 md:mb-0">
            <h3 class="text-lg font-semibold mb-2">Contact Us</h3>
            <p class="text-sm mb-1">123 Main St, City, Country</p>
            <p class="text-sm mb-1">Phone: (123) 456-7890</p>
            <p class="text-sm">Email: info@example.com</p>
          </div>
          <div class="w-full md:w-1/4">
            <h3 class="text-lg font-semibold mb-2">Follow Us</h3>
            <div class="flex space-x-4">
              <a href="#" class="text-white hover:text-gray-300">
                <i class="fab fa-facebook-f"></i>
              </a>
              <a href="#" class="text-white hover:text-gray-300">
                <i class="fab fa-twitter"></i>
              </a>
              <a href="#" class="text-white hover:text-gray-300">
                <i class="fab fa-instagram"></i>
              </a>
              <a href="#" class="text-white hover:text-gray-300">
                <i class="fab fa-linkedin-in"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="mt-8 text-center text-sm">
          <p>&copy; {{ new Date().getFullYear() }} Company Name. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer'
  }
  </script>