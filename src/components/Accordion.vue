<script setup lang="ts">
import { Icon } from '@iconify/vue'
import { AccordionContent, AccordionHeader, AccordionItem, AccordionTrigger } from 'reka-ui'
import '../style.css'
const props = defineProps({'title': String, 'value': String})
</script>

<template>
  <AccordionItem 
    class="AccordionItem"
    value={{value}}>
    <AccordionHeader class="AccordionHeader">
      <AccordionTrigger class="AccordionTrigger">
        <span>{{title}}</span>
        <Icon
          icon="radix-icons:chevron-down"
          class="AccordionChevron"
        />
      </AccordionTrigger>
    </AccordionHeader>
    <AccordionContent class="AccordionContent">
      <slot></slot>
    </AccordionContent>
  </AccordionItem>
</template>

<style>
.AccordionItem {
  background-color: #00000000;
  border-color:#00000000;
}
.AccordionTrigger {
  background-color: #00000000;
  border-color:#00000000;
  box-sizing:border-box;
  width: 100%;
  display: flex;
  font-size: 28px;
  text-align: left;
  align-items: center;
  color: #16171d;
}
.AccordionHeader {
  border-bottom: 2px solid gainsboro;
}
.AccordionContent {
  margin: 0;
  font-size: 16px;
  text-align: left;
  padding-left: 15px;
  padding-right: 15px;
}
.AccordionChevron {
  transition: transform 300ms;
}
.AccordionTrigger[data-state="open"] > .AccordionChevron {
  transform: rotate(180deg);
}
</style>