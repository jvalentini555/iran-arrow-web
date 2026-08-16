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
      The film also documents the decline of Paykan, and how it is still very much alive in the culture and memory of the country.<br>
    </Accordion>
    <Accordion title="Featured Experts" value="item-2">
      <div>
        <center><img class="expert-pic" src="../assets/talking-head-amir-tehrani.png"></center>
        <b>Amir Tehrani</b> is a PhD candidate in sociology at Tarbiat Modarres University. He received his master's degree from London 
          School of Economics and his main areas of interest include urbanization, urban mobility and urban transportation.<br><br>
        <center><img class="expert-pic" src="../assets/talking-head-gholam-khoshsafar.png"></center>
        <b>Gholam Khoshsafar</b> is one of the most experienced Paykan mechanics still working in Tehran.<br><br>
        <center><img class="expert-pic" src="../assets/talking-head-davoud-mirkhani-rashti.png"></center>
        <b>Davoud Mirkhani Rashti</b> the CEO of Iran Khodro (Paykan manufacturer) from 1983 to 1989 and was
          tasked with maintaining Paykan production during the Iran-Iraq war.<br><br>
        <center><img class="expert-pic" src="../assets/talking-head-afshin-ghaderpanah.png"></center>
        <b>Afshin Ghaderpanah</b> is a fine art photographer and avid car enthusiast.<br><br>
        <center><img class="expert-pic" src="../assets/talking-head-raana-farnoud.png"></center>
        <b>Raana Farnoud</b> graduated from Tehran University of Fine Arts, and is a well known Iranian painter.
          She discusses how Paykan gave mobility to women in Iran.<br><br>
        <center><img class="expert-pic" src="../assets/talking-head-kamran-shirdel.png"></center>
        <b>Kamran Shirdel</b> is a prominent Iranian filmmaker who studied at Centro Sperimentale di Cinematografia of Rome. 
          His 'Paykan Industrial Film' and the iconic 'Happy Birthday Paykan' advertisement were among the most memorable
          cultural works of the 70s in Iran.<br>
      </div>
    </Accordion>
    <Accordion title="Directors" value="item-3">
      <div>
        <center><img class="director-pic" src="../assets/director-shahin-armin.png"></center>
        <b>Shahin Armin</b> is an automotive design-engineer and a Paykan fanatic. Born in Tehran and a car enthusiast 
          before he could even talk or walk, he moved to the US in his twenties and worked in the US car industry for 13 years 
          (Chrysler, Michigan and Honda America, Ohio).<br><br>
          Although he worked on modern and sophisticated cars, he could never get the Paykan out
          of his mind. In 2009 he started the PaykanHunter.com blog, thus initiating an extensive
          research into Iran's emblematic car. Upon returning to Tehran in 2012, he co-curated two
          Paykan themed art exhibitions along with prominent Iranian artists.<br><br>
          Iran's Arrow is a result of Shahin's extensive research into the history of Paykan, interactions
          with fellow Paykan enthusiasts, and comprehensive understanding of Paykan's impact on
          Iranian society.<br><br>
        <center><img class="director-pic" src="../assets/director-sohrab-daryabandari.png"></center>
        <b>Sohrab Daryabandari</b> is a Tehran based professional photographer and filmmaker whose
          25 year-long career has been stretching between many areas of expertise in analog and
          digital photography. His work has ranged from journalistic, commercial, and artistic to
          architectural and industrial photography, which later lead him to editing and documentary
          filmmaking.<br><br>
          His photographic work, which was regularly exhibited and published in Iran and Europe, has
          influenced his filmmaking, notably in Dammam (Iran, 2003) and Sharveh (Iran, 2005), his
          two documentaries on ethnic Iranian music.<br>
      </div>
    </Accordion>
    <Accordion title="Gallery" value="item-4">
      <img class="gallery" src="../assets/car-exterior-0.png">
      <img class="gallery" src="../assets/car-exterior-1.png">
      <img class="gallery" src="../assets/painting.png">
      <u><b>Screen Shots</b></u>
      <img class="gallery" src="../assets/car-orange-0.png">
      <center>Paykan Taxi in iconic orange</center>
      <img class="gallery" src="../assets/car-lineup.png">
      <center>Paykan gathering in Tehran</center>
      <img class="gallery" src="../assets/car-fruit.png">
      <center>Fruit sellers in Paykan pick-up</center>
      <img class="gallery" src="../assets/car-interior-0.png">
      <center>Paykan interior</center>
      <img class="gallery" src="../assets/car-white.png">
      <center>Paykan Javanan (GT)</center>
      <img class="gallery" src="../assets/car-junked.png">
      <center>Junked Paykan</center>
      <img class="gallery" src="../assets/car-statue.png">
      <center>Paykan sculpture</center>
      <img class="gallery" src="../assets/car-art-exhibit.png">
      <center>Paykan art exhibition</center>

    </Accordion>
  </AccordionRoot>
  <img class="gallery" src="../assets/blueprint.png">
  <span class="footer">Email: <a href="mailto:email@example.com">Shahin@PaykanHunter.com</a> | 2026 ©</span>
</template>

