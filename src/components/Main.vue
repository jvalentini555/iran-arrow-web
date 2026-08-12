<script setup lang="ts">
const accordionItems = [
  {
    value: 'item-1',
    title: 'Synopsis',
    content: 'From the spring of 1967, when it first rolled off the assembly line in the outskirts of Tehran, Paykan was continuously produced for 38 years and played a fundamental role in Iranian society.\n\nThe film features people who share a common interest for the country\'s emblematic car, from pure passion to a complex love-hate connection.\n\nIran\'s Arrow uses rare archival footage and imagery to document the history of Paykan and how it has been perceived throughout the years and examines its links with Iran\'s major historical and sociological landmarks such as the White Revolution, the industrialization, the rise of the middle class, the Islamic Revolution, the Iran-Iraq war, and the post-war era.\n\nThe film also documents the decline of Paykan, and how it is still very much alive in the culture and memory of the country.',
  }
]
</script>

<template>
  <img src="../assets/poster.png">
  <main>
    <template  
      v-for="item in accordionItems"
      :key="item.value">Short Synopsis</template>
    <p>
Iran's Arrow is a 78 minute film about a rather ordinary British car introduced to Iran in 1967, which during its lengthy production period of 38 years became the national car in its new homeland.<br>
    </p>
    <p>
      Although dwindling in numbers, the Paykan can still be seen in the streets of Iran today. This film explores the impact the Paykan had on Iranian society, and the impact the Iranian society had on this car.
    </p>
    <p>Produced in Tehran 2014 - 2017</p>
    <p><i>Written, Directed and Produced by:</i></p>
    <p><b>Shahin Armin and Sohrab Daryabandari</b></p>
    <img src="../assets/award.png">
  </main>
</template>
