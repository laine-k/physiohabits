<script setup lang="ts">
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
    <template #heading>Research</template> Physiohabits will occasionally post the latest research findings from the fields of physiotherapy, behaviour science and psychology.
    <br>
       • <i>Non-adherence to home exercise has been shown to be as high as 50-70% (<a href="https://www.sciencedirect.com/science/article/pii/S1529943013014745?casa_token=3913WKQJ0c8AAAAA:6d9FpoBmL6wA7KMUnvoP1kRorA7X3Yaa4JbHPCaShJo4fD9_nT6q6dUWa_MzRuZcmDbMf-wh" target="_blank" rel="noopener">Low back pain</a> +
      <a href="https://www.researchgate.net/publication/284411604_The_assessment_of_patient_adherence_to_physiotherapy_rehabilitation" target="_blank" rel="noopener">Muskolosceletal conditions</a>).</i>


  </WelcomeItem>
<!--
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling</template>

    This project is served and bundled with
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">Vite</a>. The
    recommended IDE setup is
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">VSCode</a> +
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Volar</a>. If
    you need to test your components and web pages, check out
    <a href="https://www.cypress.io/" target="_blank" rel="noopener">Cypress</a> and
    <a href="https://on.cypress.io/component" target="_blank">Cypress Component Testing</a>.

    <br />

    More instructions are available in <code>README.md</code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>

    Get official tools and libraries for your project:
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Pinia</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Vue Router</a>,
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Vue Test Utils</a>, and
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">Vue Dev Tools</a>. If
    you need more resources, we suggest paying
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome Vue</a>
    a visit.
  </WelcomeItem> -->

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    Are you a health practicioner or a patient? <br>
    Do you have a method or idea that worked for you to stick with the exercise plan? Would you like to share your story and help others?
    <br> Get in touch <a href="https://www.instagram.com/physio_habits/" target="_blank">@physio_habits</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Physiohabits</template>

    As an independent project, Physiohabits relies on community backing for its sustainability.<!-- You can help
    us by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.-->
  </WelcomeItem>

</template>

