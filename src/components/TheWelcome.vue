<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>

    Halo! Saya adalah Muhammad Surya Fadilla, seorang penggiat teknologi yang bersemangat untuk menciptakan dampak positif melalui inovasi dan kreativitas.<br><br>
    Cerita perjalanan saya dimulai dari ketertarikan masa kecil saya pada perangkat lunak komputer yang sederhana, yang kemudian berkembang menjadi obsesi untuk memahami teknologi lebih dalam.<br>
Sejak kecil, saya selalu suka dengan teknologi memungkinkan kita untuk berkomunikasi, berkreasi, dan menyelesaikan masalah dengan cara yang belum pernah terpikirkan sebelumnya. Inilah yang mendorong saya untuk mengejar pendidikan dalam bidang teknik komputer, di mana saya belajar tentang pemrograman, desain sistem, dan teknologi informasi secara mendalam.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Latar Belakang Pendidikan</template>

    Saya pernah bersekolah dasar, Sekolah menengah pertama, Sekolah menengah atas hingga Perguruan tinggi di Pekanbaru.<br><br>
    Sekarang ini saya sebagai Mahasiswa di Universitas Islam Riau (UIR)

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobbi</template>

    Saya memiliki hobbi Menggambar, Ketika saya menyentuh pensil ke kertas, saya merasa seolah-olah saya membuka jendela ke dalam pikiran dan perasaan saya sendiri. Setiap garis yang saya gambar menceritakan cerita yang unik, menyampaikan emosi dan pemikiran yang sulit diungkapkan dengan kata-kata.<br><br>
    Melalui hobi saya ini, saya belajar tentang ketekunan, kreativitas, dan rasa menghargai keindahan di sekitar kita. Saya percaya bahwa seni memiliki kekuatan untuk menginspirasi, menghibur, dan menyatukan orang-orang dari berbagai latar belakang.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Komunikasi</template>

    Saya adalah orang yang sulit berinterasi dengan orang lain, tetapi jika sudah mengenal orang maka saya akan lebih terbuka
  </WelcomeItem>

</template>
