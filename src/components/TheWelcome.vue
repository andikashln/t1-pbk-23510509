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
    <template #heading>Latar Pendidikan</template>

    Saya merupakan mahasiswa Universitas Islam Riau, sebelumnya saya pernah bersekolah di SMA 14 Pekanbaru, MTsN 3 Pekanbaru, dan SD 21 Pekanbaru.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pengalaman dan Keahlian</template>

    Bermain futsal dan bermain game 
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Karya</template>

    Pada sosial media saya menjadi streaming game, dari situ saya bisa berjual untuk memancing viewers yang nonton untuk belanja di toko yang saya sediakan
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sertifikasi</template>

    Saya pernah mengambil beberapa sertifikasi pada PT tertentu
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Kontak</template>

   Hubungi saya melalui:<br>
   <li>Email: andikashalihin@gmail.com</li>
   <li>Instagram: @andikashln</li>
  </WelcomeItem>
</template>
