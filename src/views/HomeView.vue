<template>
  <section id="hero" class="bg-[url('/src/assets/images/hero.png')] bg-cover w-full h-screen bg-no-repeat">
    <div class="pt-4"></div>
    <nav id="navigation" class="fixed inset-x-0 py-4 px-4 font-medium text-right flex items-center justify-between flex-wrap text-right bg-white rounded-md uppercase text-sm mx-10">
       <div class="pt-4">
        <img src="../assets/images/logo.png" alt="">
       </div>

      <router-link to="/">solutions</router-link> 
      <router-link to="/contact">leadership</router-link>
      <router-link to="/contact">investor relations</router-link>
      |
      <router-link to="/contact"><span class="bg-neutral-900 text-white lowercase p-1 rounded-md">Subsidiaries</span></router-link>
    </nav>

      
  </section>

  <section id="services" class="container mx-auto my-4">
    <div class="text-center text-neutral-400 text-sm w-full mb-10">
      <h3 class="font-semibold text-2xl text-gray-900 font-inter-regular mb-2">What we do</h3>

      <p>Kweli Capital is inspired by the power of data as point of connection. We not only connect people, businesses and industries, we also inspire informed strategic decisions that power the future. We enable governments and the private sector to make better decisions via our data driven solutions.</p>
    </div>

    <div class="flex items-center justify-between font-bold text-black border-b border-gray-200">
      <div>
        <a> <img class="mx-auto pb-2" src="../assets/images/bomayangu.png" alt=""><span class="border-b-2 border-neutral-900">Bomayangu Portal</span></a>
      </div>

      <div>
        <a> <img class="mx-auto pb-2" src="../assets/images/tenant.png" alt=""><span>Tenant Purchase Platform</span></a>
      </div>

      <div>
        <a> <img class="mx-auto pb-2" src="../assets/images/amaka.png" alt=""><span>Amaka Fund</span></a>
      </div>

    </div>

    <div class="container mx-auto py-16 px-2 flex">
      <div class="w-1/4 mr-8">
        <img class="h-full" src="../assets/images/whatwedo.png"   alt="banner_image">
      </div>
      <div class="flex flex-col justify-center w-3/4">
        <div class="pr-6">
          <h3 class="text-neutral-900 font-bold text-2xl font-medium">Build anything,<br> anytime!</h3>
          <p class="text-stone-400 text-sm">
            We offer support and continuous development for the State Department of Housing and Urban Development - Kenya, for the government's affordable housing portal.
          </p>

          <div class="border-b-2 border-gray-100 mt-6 pb-3"></div>
        </div>
      </div>
      
    </div>
    
  </section>

  <section id="milestones" class="bg-[url('/src/assets/images/milestones.png')] h-64 bg-no-repeat">
      <div class="container mx-auto flex items-center justify-center gap-10">
        <div class="flex items-center justify-between w-3/4  text-gray-300">
          <div>
            <h3 class="font-bold pt-10 text-2xl">Milestones</h3>
            <img class="my-9" src="../assets/images/rocket.png" alt="">
          </div>
          
          <div> 
            <h3 class="text-gray-300 font-bold text-xl">KSHS. 1.51B</h3>

            <p class="w-80">
              Saved by citizens through Affordable Housing Programs Current Mortgages in Kenya - 21,000 Over 33,000 active savers on the BomaYangu platform in under 3 years. 
            </p>
          </div>
        </div>

        <div class="w-1/4">
          <h3 class="text-gray-300 font-bold text-xl">KSHS 50B</h3>

          <p class="text-zinc-400 text-sm pt-2">
            Committed by banks toward Affordable Housing Programs
          </p>
        </div>
        
      </div>
  </section>

  <section id="cards" class="container mx-auto my-4">
    <h3 class="font-semibold text-xl text-left text-neutral-800">Leadership</h3>
    <div class="grid place-items-center md:grid-cols-3 space-y-2">
      <div class="rounded-md">
        <img src="../assets/images/board/chris.png" alt=""  class="hover:-translate-y-2 cursor-pointer duration-700">
        
        <div class="py-2">
          <div class="font-bold text-xl mb-2">Kris Senanu</div>
          <p class="text-gray-700 text-base">
            Board Member
          </p>
        </div>
      </div>
      
      <div class="rounded-md">
        <img src="../assets/images/board/calvin.png" alt="" class="hover:-translate-y-2 cursor-pointer duration-700">
      
        <div class="py-2">
            <div class="font-bold text-xl mb-2">Calvin Nyachoti</div>
            <p class="text-gray-700 text-base">
              Board Member
            </p>
        </div>
      </div>
      <div class="rounded-md">
        <img src="../assets/images/board/hilda.png" alt="" class="hover:-translate-y-2 cursor-pointer duration-700">
        
        <div class="py-2">
              <div class="font-bold text-xl mb-2">Hilda Moraa</div>
              <p class="text-gray-700 text-base">
                Board Member
              </p>
        </div>
      </div>
      <!-- <div class="justify-start"></div> -->
    </div>
    <div class="grid place-items-center md:grid-cols-2 space-y-2">
      <div class="rounded-md">
        <img src="../assets/images/board/ken.png" alt="" class="hover:-translate-y-2 cursor-pointer duration-700">
      
        <div class="py-2">
              <div class="font-bold text-xl mb-2">Kennedy Kipng'etich</div>
              <p class="text-gray-700 text-base">
                Board Member
              </p>
        </div>
      </div>
      <div class="rounded-md">
        <img src="../assets/images/board/phillipa.png" alt="" class="hover:-translate-y-2 cursor-pointer duration-700">
        
        <div class="py-2">
              <div class="font-bold text-xl mb-2">Phillipa Mbonye</div>
              <p class="text-gray-700 text-base">
                Board Member
              </p>
        </div>
      </div>
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

  <section id="footer" class="bg-[url('/src/assets/images/footerimg.png')] bg-black bg-no-repeat py-4">
    <div class="container mx-auto text-xs text-gray-500 font-normal ">
      <p>&copy; Copyright KWELI CAPITAL. All Rights Reserved</p>
    
      <div class="flex">

      </div>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
// import NavBar from '@/components/NavBar.vue'

export default {
  name: 'HomeView',
  components: {
  }
}
</script>
