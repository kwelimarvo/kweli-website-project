<template>
  <section id="services" class="container mx-auto my-4">
    <div>
      <h3 class="text-center font-semibold text-xl text-gray-900 font-inter-regular">What we do</h3>
    </div>
  </section>

  <section id="milestones" class="bg-neutral-900">
    <div>
      MILESTONES
    </div>
  </section>

  <section id="cards" class="container mx-auto my-4">
    <h3 class="font-semibold text-xl text-left text-neutral-800">Leadership</h3>
    <div class="grid place-items-center md:grid-cols-3 space-y-2">
      <div class="rounded-md"><img src="../assets/images/board/chris.png" alt=""></div>
      <div class="rounded-md"><img src="../assets/images/board/calvin.png" alt=""></div>
      <div class="rounded-md"><img src="../assets/images/board/hilda.png" alt=""></div>
      <div class="rounded-md"><img src="../assets/images/board/ken.png" alt=""></div>
      <div class="rounded-md"><img src="../assets/images/board/phillipa.png" alt=""></div>
    </div>
  </section>

  <hr class="font-bold">

  <div class="bg-neutral-900 pb-10">

    <div>
      <h1 class="text-white text-xl opacity-100 font-medium text-center py-16">BRAND PARTNERS</h1>
    </div>  

    <div class="flex justify-center space-x-16">
      <span class="text-white my-4 font-bold text-base"><img src="../assets/images/partners/genghis.png" alt="">Fund Manager</span>
      <img src="../assets/images/partners/line.png" alt="">
      <span class="text-white my-4 font-bold text-base"><img src="../assets/images/partners/stanbic.png" alt="">Funds Trustee & Custodian</span>
    </div>
    
  </div>

  <section id="investor">
    <h2 class="h-8 text-neutral-900 text-2xl font-semibold sm:text-left md:text-center mt-20">Investor Relations</h2>
  </section>

  <section id="sustainability" class="bg-neutral-100 mt-3 py-16">
    <h3 class="text-neutral-900 font-semibold text-2xl">Sustainability</h3>
    <span class="uppercase text-xs font-normal">Using innovation for good</span>
    
    <div class="text-left text-sm w-80 mt-6">
      <p>We strongly believe that the success of many private and public initiatives requires strong partnerships with private companies and governments 
        in Africa.
      </p>
      <br>
      <p>
         Our data-driven solutions have allowed us to form strong partnerships in both government & the private sector.
      </p>
    </div>
  </section>

  <section id="mission">
    <div class="text-center mb-10">
      <h3 class="text-black text-2xl font-semibold mt-10">Our Mission</h3>
      <p class="text-zinc-500 italic text-xl font-semibold"><span class="text-9xl text-center font-merriweather z-1">“</span>To provide the public & private sectors with bespoke, data-driven ICT solutions that inform their strategic decisions.<span class="text-9xl text-center font-merriweather z-1">“</span></p>
    </div>

    <div>
      <div></div>
      <div>
        <p class="uppercase text-xl font-bold text-neutral-900">Let's build something great.<br>together.</p>
      </div>
    </div>
  </section>


  <section id="footer" class="bg-[url('/src/assets/images/footerimg.png')]">
    <div>
      <p>&copy; Copyright KWELI CAPITAL. All Rights Reserved</p>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    
  }
}
</script>
