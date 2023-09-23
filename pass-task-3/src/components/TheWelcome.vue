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
    <template #heading>Education</template>
    2021 - Certificate IV in Cyber Secruity<br/>
    <span class="school">Box Hill Institute.</span><br/>
    <br/>
    2022 - Advanced Diploma in Cyber Security<br/>
    <span class="school">Box Hill Institute</span><br/>
    <br/>
    2023-present - Bachelor of Cyber Security<br/>
    <span class="school">Deakin University</span>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Work</template>
    Combat Engineer - Australian Army<br/>
    Console Operator - Horizon Petrolium<br/>
    IT Clerk - Latrobe Regional Hospital<br/>
    General Labourer - SuperSoil Garden Supplies<br/>
    Help Desk - Web Hosting Company<br/>

    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Code</template>
    Find my code on Github!<br/>
    <a href="https://github.com/brett-a-wiggins/Pass-Task-1" target="_blank">SIT120 Pass Task 1</a><br/>
    <a href="https://github.com/brett-a-wiggins/Pass-Task-2" target="_blank">SIT120 Pass Tast 2</a><br/>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community Work</template>

    2018 - Marine Radio Operator - Australian Volunteer Coast Guard<br/>
    2020 - Volunteer Repsonder - State Emergency Service<br/>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Follow Me</template>


    <a title="Facebook, Public domain, via Wikimedia Commons" href="https://www.facebook.com/bawig.one/" target="_blank"><img width="64" alt="2021 Facebook icon" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/2021_Facebook_icon.svg/128px-2021_Facebook_icon.svg.png"></a>




  </WelcomeItem>
</template>

<style scoped>
.school{
  font-weight: bold;
}
</style>