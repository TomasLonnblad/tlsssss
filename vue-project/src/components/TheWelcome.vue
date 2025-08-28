<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading></template>

   
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading></template>

   
    <a href="https://vite.dev/guide/features.html" target="_blank" rel="noopener"></a> 
    
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a>
    
    <a href="https://github.com/vuejs/language-tools" target="_blank" rel="noopener"> </a>
    
    <a href="https://vitest.dev/" target="_blank" rel="noopener"></a>
  
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a>
    
    <a href="https://playwright.dev/" target="_blank" rel="noopener"></a>

    <br />

  
    <a href="javascript:void(0)" @click="openReadmeInEditor"><code></code></a
    >
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading></template>


    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a>
    
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"> </a>
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading></template>

  
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      ></a
    >
    <a href="https://bsky.app/profile/vuejs.org" target="_blank" rel="noopener"></a>
  
    <a href="https://x.com/vuejs" target="_blank" rel="noopener"></a>
  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading></template>

    
    
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>
  </WelcomeItem>
</template>
