<template>
  <div>
    <sgds-button>
      <span class="testing">Hello</span>
    </sgds-button>
    <sgds-accordion>
      <sgds-accordion-item>
        <div slot="accordion-header">This is an accordion</div>
        <span slot="accordion-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores soluta eaque fugit fuga distinctio?
          Eum.</span>
      </sgds-accordion-item>
      <sgds-accordion-item>
        <div slot="accordion-header">Accordion 1</div>
        <span slot="accordion-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores soluta eaque fugit fuga distinctio?
          Eum.</span>
      </sgds-accordion-item>
      <sgds-accordion-item>
        <div slot="accordion-header">Accordion 2</div>
        <span slot="accordion-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores soluta eaque fugit fuga distinctio?
          Eum.</span>
      </sgds-accordion-item>
      <sgds-accordion-item>
        <div slot="accordion-header">Accordion 3</div>
        <span slot="accordion-content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores soluta eaque fugit fuga distinctio?
          Eum.</span>
      </sgds-accordion-item>
    </sgds-accordion>

    <div class="test"> test</div>
  </div>
</template>

<script lang="ts" setup>
import "@govtechsg/sgds-web-component/components/Button/index.js"
import "@govtechsg/sgds-web-component/components/Accordion/index.js"
// import "@govtechsg/sgds-web-component/components/ActionCard/index.js"
// import "@govtechsg/sgds-web-component/themes/day.css";
</script>
<style>

/* sgds-button:not(:defined)> template[shadowrootmode] ~ * {
    display:none;
} */
</style>