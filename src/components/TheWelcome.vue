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
    <template #heading>PENDIDIKAN</template>
    PENDIDIKAN YANG DITEMPUH<br> SD (Mutiara)<br> SMP (SMPN 4 MANDAU)<br> SMA (SMAN 2 MANDAU)
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>OTOMOTIF</template>
    Ketertarikan dengan modification<br> mobil dan motor
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>GAMES</template>
    Games Favorite untuk saat ini,<br> 1.Mobile legends<br> 2.Ball 8 Pool<br> 3.PUBG
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>MEDIA SOSIAL</template>
    -Instagram : @frl.qshyi<br> -Tiktok : @frlqshyi<br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>DATA DIRI</template>
    1.NAMA : Farell Qushoyi<br> 2.UMUR : 20<br> 3.KULIAH : Universitas Islam Riau<br> 4.JENIS KELAMIN : LAKI-LAKI
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>
  </WelcomeItem>
</template>
