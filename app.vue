<template>
  <div>
  
    <div class="profile-header bg-purple-600 text-white text-center py-8">
      <img src="./assets/image.png" alt="Profile Image" class="profile-image w-36 h-36 rounded-full border-4 border-white mx-auto mb-4 hover:scale-110 transition-transform duration-300">
      <h2 class="text-2xl font-bold">Azam Akbar Fadillah</h2>
      <p class="text-lg">Web Developer | Designer | Content Creator | Musisi</p>
      <div class="profile-buttons mt-4 flex justify-center space-x-2">
      </div>
      <div class="social-icons mt-6 flex justify-center">
        <a href="#" class="text-blue-500 mx-2 text-2xl"><i class="fab fa-facebook"></i></a>
        <a href="#" class="text-blue-500 mx-2 text-2xl"><i class="fab fa-instagram"></i></a>
        <a href="#" class="text-blue-500 mx-2 text-2xl"><i class="fab fa-linkedin"></i></a>
      </div>
    </div>

    <div class="container mx-auto profile-info bg-gray-100 rounded-lg mt-8 p-8 shadow-lg">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div>
          <h3 class="text-xl font-semibold mb-4">Tentang Saya</h3>
          <p>Halo! Saya Azam Akbar Fadillah, seorang mahasiswa Universitas Brawijaya yang bersemangat belajar dalam membuat website. Saya senang memecahkan masalah dan mempelajari hal-hal baru setiap hari. Saya juga memiliki hobi bermain alat musik.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-4">Kemampuan</h3>
          <ul class="list-group space-y-2">
            <li class="flex items-center"><i class="fas fa-code mr-2"></i> HTML & CSS</li>
            <li class="flex items-center"><i class="fas fa-code mr-2"></i> JavaScript & React</li>
            <li class="flex items-center"><i class="fas fa-code mr-2"></i> Bootstrap</li>
            <li class="flex items-center"><i class="fas fa-pencil-ruler mr-2"></i> Design</li>
          </ul>
        </div>
      </div>
    </div>

    
    <div class="container mx-auto contact-info bg-gray-100 rounded-lg mt-8 p-8 shadow-lg">
      <h3 class="text-xl font-semibold mb-4">Informasi Kontak</h3>
      <ul class="list-group space-y-4">
        <li class="flex items-center"><i class="fas fa-envelope mr-2"></i> azamakbarfadillah@gmail.com</li>
        <li class="flex items-center"><i class="fas fa-phone mr-2"></i> 08993518880</li>
        <li class="flex items-center"><i class="fas fa-map-marker-alt mr-2"></i> Malang, Jawa Timur</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ProfilePage',
}
</script>

<style>
.profile-header {
  background-color: #9650ed;
}
.profile-image:hover {
  transform: scale(1.1);
}
</style>
