<script type="text/javascript" charset="utf-8">
  import { PlusCircleIcon, TrendingDownIcon } from 'svelte-feather-icons'
</script>

<svelte:head>
  <meta name="description" content="Learn a new language with us. Choose a language and start to learn from it.">
  <meta name="keywords" content="LANGUAGE, LEARNING, STARTINGPOINT">
  <meta name="author" content="Gerastucter">
  <title>Start here</title>
</svelte:head>


<main class="container bg-gradient-to-r from-primary-600 to-tertiary-300 w-full h-full">
  <!-- Masonry Cards -->
  
  
  <!-- Card -->
  <section id="alerts" class="p-5">
    <div class="sticky top-[25px] variant-filled-secondary rounded-md md:py-3 mt-4 p-4" role="alert">
      <div class="flex">
        <div class="flex-shrink-0">
          <svg class="h-4 w-4 text-warning-500 mt-0.5" xmlns="http://www.w3.org/2000/svg" width="16" height="16"
            fill="currentColor" viewBox="0 0 16 16">
            <path
              d="M8.982 1.566a1.13 1.13 0 0 0-1.96 0L.165 13.233c-.457.778.091 1.767.98 1.767h13.713c.889 0 1.438-.99.98-1.767L8.982 1.566zM8 5c.535 0 .954.462.9.995l-.35 3.507a.552.552 0 0 1-1.1 0L7.1 5.995A.905.905 0 0 1 8 5zm.002 6a1 1 0 1 1 0 2 1 1 0 0 1 0-2z" />
          </svg>
        </div>
        <div class="flex-1 md:flex md:justify-between ml-4">
          <p class="text-sm text-warning-500">
            Please if you don't speak english translate this website to your native language.
          </p>
          <p class="text-sm mt-3 md:mt-0 md:ml-6">
            <a href="https://www.google.com/search?q=how+to+translate+a+website+in+google+chrome&oq=how+to+translate+a+website+in+google+chrome&aqs=chrome..69i57j0i22i30l4j0i390i650l3.16237j1j4&client=tablet-android-lge-rev1&sourceid=chrome-mobile&ie=UTF-8"
              class="text-warning-600 hover:text-success-500 font-bold whitespace-nowrap">Details</a>
          </p>
        </div>
      </div>
    </div>
    
    <div class="variant-filled-secondary rounded-md mt-4 p-4" role="alert">
      <div class="flex">
        <div class="flex-shrink-0">
          <svg class="h-4 w-4 text-success-500 mt-0.5" xmlns="http://www.w3.org/2000/svg" width="16" height="16"
            fill="currentColor" viewBox="0 0 16 16">
            <path
              d="M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16zm.93-9.412-1 4.705c-.07.34.029.533.304.533.194 0 .487-.07.686-.246l-.088.416c-.287.346-.92.598-1.465.598-.703 0-1.002-.422-.808-1.319l.738-3.468c.064-.293.006-.399-.287-.47l-.451-.081.082-.381 2.29-.287zM8 5.5a1 1 0 1 1 0-2 1 1 0 0 1 0 2z" />
          </svg>
        </div>
        <div class="flex-1 md:flex md:justify-between ml-4">
          <p class="text-sm text-success-500">
            To access the content, choose one of the languages at the bottom of this page and learn from it.
          </p>
          <p class="text-sm mt-3 md:mt-0 md:ml-6">
            <a href="#languages" class="text-success-600 hover:text-success-500 font-bold whitespace-nowrap">Details</a>
          </p>
        </div>
      </div>
    </div>
  </section>
  <!-- End Card -->
  
  <section style="box-shadow: inset -40px 0 400px black;" id="features" class="bg-primary-900 py-20 bg-fixed shadow-lg rounded-b-xl rounded-t-xl py-20">
    <!-- Features -->
    <div class="max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-14 mx-auto text-tertiary-500">
      <!-- Title -->
      <div  class="mx-auto max-w-2xl mb-8 lg:mb-14 text-center variant-glass-tertiary  p-6 rounded ">
        <h2 class="text-3xl lg:text-4xl font-bold">
          <span class="font-bold ">GERASTUCTER</span> is a powerfull language learning tool for you
        </h2>
        <p class="mt-3">
          Want to discover more? Take a look at the following features then choose one language to be able to access our content and know more about us
        </p>
      </div>
      <!-- End Title -->
      
      <!-- Grid -->
      <div class="mx-auto max-w-3xl grid grid-cols-12 gap-6 lg:gap-8">
        <!-- Icon Block -->
        <div class="col-span-6 sm:col-span-4 text-center">
          <TrendingDownIcon size="40"/>
          <div class="mt-2 sm:mt-6 variant-glass-tertiary  py-3 p-1 rounded-xl">
            <h3 class="text-lg font-semibold">
             #Accessible# <br /> It's the keyword from Gerastucter, keep this word with you when using our application.
            </h3>
          </div>
        </div>
        <!-- End Icon Block -->
        
        <!-- Icon Block -->
        <div class="col-span-6 sm:col-span-4 text-center">
          <TrendingDownIcon size="40"/>
          <div class="mt-2 sm:mt-6 variant-glass-tertiary  py-3 p-1 rounded-xl">
            <h3 class="text-lg font-semibold">
              #Easy to use#<br /> Usability is also a great feature of Gerastucter, since users hardly have difficulty using and accessing the content they want.
            </h3>
          </div>
        </div>
        <!-- End Icon Block -->
        
        <!-- Icon Block -->
        <div class="col-span-6 col-start-4 sm:col-span-4 text-center">
          <TrendingDownIcon size="40"/>
          <div class="mt-2 sm:mt-6 variant-glass-tertiary py-3 p-1 rounded-xl">
            <h3 class="text-lg font-semibold">
              #Modern# <br /> Gerastucter also has o wide of modern and interesting content, all this content is current and optimized.
            </h3>
          </div>
        </div>
        <!-- End Icon Block -->
      </div>
    </div>
    <!-- End Features -->
  </section>
  
  <section id="languages" class="px-5 py-18 sm:px-6 lg:px-8 lg:py-14 my-20">
    <!-- Title -->
    <div id="hero" class="max-w-2xl text-center py-5 rounded-lg mb-10 mt-20 lg:mb-14 mx-auto">
      <h2 class="text-2xl font-bold md:text-4xl text-primary-900-50-token">
        I WANT TO LEARN FROM
      </h2>
    </div>
    <!-- End Title -->
    <!-- Grid -->
    <div class="flex justify-around items-center flex-wrap p-3 pb-4">
      
      <a href="https://en.gerastucter.site" class="flex flex-col items-center justify-center gap-1">
        <img class="rounded-lg w-20 h-20"
          src="https://res.cloudinary.com/djglhdlln/image/upload/v1688331791/Flags/flag-400_2_bifo0y.png"
          alt="English image, the USA flag">
        <br />
        <h3 class="text-2xl p-4 variant-glass-secondary">English</h3>
      </a>
      <!-- End Col -->
      <!-- End Col -->
      
      <!-- End Col -->
      
      <a href="mailto:gerastucter@gmail.com" class="block sm:flex items-center gap-y-3 justify-center">
        <PlusCircleIcon size="40" />
      </a>
      <!-- End Col -->
    </div>
    <!-- End Grid -->
  </section>
  <!-- End Team -->
  <!-- End Masonry Cards -->
</main>



<style type="text/css" media="all">
  /*main {*/
  /*  background-image: url('https://res.cloudinary.com/djglhdlln/image/upload/v1688397374/glass-3389935_640_vqcxig.jpg');*/
  /*  background-position: center;*/
  /*  background-repeat: no-repeat;*/
  /*  background-size: cover;*/
  /*  position: relative;*/
  /*}*/
  #hero {
    background-image: url('https://res.cloudinary.com/djglhdlln/image/upload/v1688325288/milad-fakurian-F93PQmh4krI-unsplash_ier1tm.jpg');
    height: auto;
    width: auto;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
  }
  #features {
    background-image: url('https://res.cloudinary.com/djglhdlln/image/upload/v1688325289/humanabstract-anf0.jpg');
    height: auto;
    width: auto;
    background-position: start;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
  }
</style>