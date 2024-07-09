<script setup lang="ts">
import ProfileSkillItem from './ProfileSkillItem.vue'
import FrameworkIcon from '../icons/IconFramework.vue'
import PerformanceIcon from '../icons/IconPerformance.vue'
import AnimationIcon from '../icons/IconAnimation.vue'
import TestIcon from '../icons/IconTest.vue'
</script>

<template>
  <ProfileSkillItem>
    <template #icon>
      <FrameworkIcon />
    </template>
    <template #heading>Frameworks Vue | React</template>

    <p>
      Vue and React are powerful UI frameworks that streamline the creation of interactive web applications. They simplify state management, data handling, and component reusability, while their extensive libraries and plugins boost development efficiency and facilitate the building of complex applications.    </p>
  </ProfileSkillItem>

  <ProfileSkillItem>
    <template #icon>
      <PerformanceIcon />
    </template>
    <template #heading>Performance</template>

    <p>
      Improving frontend application performance is crucial for user experience. Techniques like code splitting, lazy loading, caching, optimizing network requests, and minimizing render-blocking resources enhance speed and efficiency. Regular monitoring with tools like Lighthouse or WebPageTest is essential to identify and fix bottlenecks.    </p>
  </ProfileSkillItem>


  <ProfileSkillItem>
    <template #icon>
      <AnimationIcon />
    </template>
    <template #heading>Animations</template>

    <p>
      GSAP is a popular library for web animations, offering a flexible API for creating smooth, detailed animations including tweens, timelines, and morphs. It enables advanced features like SVG and physics animations, enhancing user experience with its performance and cross-browser compatibility. GSAP's extensive documentation supports its widespread use among developers.
    </p>
  </ProfileSkillItem>

  <ProfileSkillItem>
    <template #icon>
      <TestIcon />
    </template>
    <template #heading>Tests</template>

    <p>
      Testing is crucial in front-end development, encompassing unit tests, component tests, and e2e tests. Unit tests check individual code units, component tests examine component interactions, and e2e tests simulate real user experiences. Utilizing frameworks like Jest, Mocha, Cypress, and tools like Vue Test Utils or React Testing Library ensures application quality, early bug detection, and a seamless user experience.    </p>
  </ProfileSkillItem>
</template>
