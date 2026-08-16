<script setup lang="ts">
import Accordion from './Accordion.vue'
import { AccordionRoot } from 'reka-ui'

</script>

<template>
  <img src="../assets/poster.png">
  <main>
    <p>
      Iran's Arrow is a 78 minute film about a rather ordinary British car introduced to Iran in 1967, 
      which during its lengthy production period of 38 years became the national car in its new homeland.<br>
    </p>
    <p>
      Although dwindling in numbers, the Paykan can still be seen in the streets of Iran today. 
      This film explores the impact the Paykan had on Iranian society, and the impact the Iranian society had on this car.
    </p>
    <p>Produced in Tehran 2014 - 2017</p>
    <p><i>Written, Directed and Produced by:</i></p>
    <p><b>Shahin Armin and Sohrab Daryabandari</b></p><br>
    <img src="../assets/award.png">
  </main>
  <AccordionRoot
    type="single"
    :collapsible="true"
  >
    <Accordion title="Synopsis" value="item-1">
      From the spring of 1967, when it first rolled off the assembly line in the outskirts of Tehran, 
      Paykan was continuously produced for 38 years and played a fundamental role in Iranian society.<br><br>
      The film features people who share a common interest for the country's emblematic car, 
      from pure passion to a complex love-hate connection.<br><br>
      Iran's Arrow uses rare archival footage and imagery to document the history of Paykan and 
      how it has been perceived throughout the years and examines its links with Iran's major historical 
      and sociological landmarks such as the White Revolution, the industrialization, the rise of the middle class, 
      the Islamic Revolution, the Iran-Iraq war, and the post-war era.<br><br>
      The film also documents the decline of Paykan, and how it is still very much alive in the culture and memory of the country.<br><br>
    </Accordion>
    <Accordion title="Featured Experts" value="item-2">
      <div>
        <center><img class="expert-pic" src="../assets/talking-head-amir-tehrani.png"></center>
        <p><b>Amir Tehrani</b> is a PhD candidate in sociology at Tarbiat Modarres University. He received his master's degree from London 
          School of Economics and his main areas of interest include urbanization, urban mobility and urban transportation.</p><br>
        <center><img class="expert-pic" src="../assets/talking-head-gholam-khoshsafar.png"></center>
        <p><b>Gholam Khoshsafar</b> is one of the most experienced Paykan mechanics still working in Tehran.</p><br>
        <center><img class="expert-pic" src="../assets/talking-head-davoud-mirkhani-rashti.png"></center>
        <p><b>Davoud Mirkhani Rashti</b> the CEO of Iran Khodro (Paykan manufacturer) from 1983 to 1989 and was
          tasked with maintaining Paykan production during the Iran-Iraq war.</p><br>
        <center><img class="expert-pic" src="../assets/talking-head-afshin-ghaderpanah.png"></center>
        <p><b>Afshin Ghaderpanah</b> is a fine art photographer and avid car enthusiast.</p><br>
        <center><img class="expert-pic" src="../assets/talking-head-raana-farnoud.png"></center>
        <p><b>Raana Farnoud</b> graduated from Tehran University of Fine Arts, and is a well known Iranian painter.
          She discusses how Paykan gave mobility to women in Iran.</p><br>
        <center><img class="expert-pic" src="../assets/talking-head-kamran-shirdel.png"></center>
        <p><b>Kamran Shirdel</b> is a prominent Iranian filmmaker who studied at Centro Sperimentale di Cinematografia of Rome. 
          His 'Paykan Industrial Film' and the iconic 'Happy Birthday Paykan' advertisement were among the most memorable
          cultural works of the 70s in Iran.</p><br>
      </div>
    </Accordion>
  </AccordionRoot>
</template>

