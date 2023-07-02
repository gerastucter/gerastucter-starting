<svelte:head>
  <meta name="description"
    content="Come and discover tools to help your language lerning. That's the resources page, so here you can find everything that Gerastucter offers and even more it's all free.">
  <meta name="keywords" content="LANGUAGE, LEARNING, RESOURCES">
  <meta name="author" content="Gerastucter">
  <title>RESOURCES</title>
</svelte:head>

<script>
  import { CheckCircleIcon } from 'svelte-feather-icons'
</script>

<div class="container mx-auto max-w-screen-lg p-5">
  <div class="grid grid-cols-1 md:grid-cols-12">
    
    <div class="space-y-4 md:col-span-6 p-4">
      <h1 class="text-3xl md:text-3xl font-bold">
        Our <span class="text-success-50-900-token drop-shadow-lg">BLOG</span> has a wide range of interesting content
      </h1>
      <p class="max-w-xl opacity-60">
        Get to know our blog by clicking on the "go" button
      </p>
      <ul class="list-items">
        <li>
          <span>
            <CheckCircleIcon size="22" />
          </span>
          <span>
            <b>Reliable information</b> – All the information contained in our blog is highly reliable, as we have done
            a lot of research to obtain the best result, in addition to using reliable and standardized sources such as
            language academies and/or language institutions
          </span>
        </li>
        <li>
          <span>
            <CheckCircleIcon size="22" />
          </span>
          <span>
            <b>Plain language</b> – We always try to use the language as simple as possible, to facilitate accessibility
            to users with some type of disability
          </span>
        </li>
        <li>
          <span>
            <CheckCircleIcon size="22" />
          </span>
          <span>
            <b>Diversified content</b> – Highly diverse content, so we can bring from grammar tips, to time management.
            You may also notice that we always seek to balance and seek standards to facilitate access to our content
            since it is very diverse
          </span>
        </li>
      </ul>
      <div class="flex flex-wrap gap-4">
        <a
          href="/resources/blog"
          class="py-3 px-4 inline-flex justify-center items-center gap-2 rounded-md variant-filled-tertiary border border-transparent font-semibold text-secondary-900-50-token hover:text-success-50-900-token hover:font-bold focus:outline-none focus:ring-2 ring-offset-white focus:ring-tertiary-500 focus:ring-offset-2 transition-all text-sm px-4 w-full">
          GO
        </a>
      </div>
    </div>
    <div class="space-y-4 mt-10 md:mt-0 md:col-span-6 p-4">
      <h1 class="text-3xl md:text-3xl font-bold">
        Our <span class="text-success-50-900-token drop-shadow-lg">TUTORING</span> will tutor you to learn a new language from scratch
      </h1>
      <p class="max-w-xl opacity-60">
        Get to know our tutoring by clicking on the "go" button
      </p>
      <ul class="list-items">
        <li>
          <span>
            <CheckCircleIcon size="22" />
          </span>
          <span>
            <b>Various paths</b> – We assign multiple paths and you choose one to follow. We recommend that you follow
            the step by step of the chosen path, always modifying it according to your reality
          </span>
        </li>
        <li>
          <span>
            <CheckCircleIcon size="22" />
          </span>
          <span>
            <b>Recommendations</b> – We recommend you the most efficient apps, courses, and trails in the world today,
            if you speak English natively you will have a great advantage when it comes to these recommendations.
          </span>
        </li>
        <li>
          <span>
            <CheckCircleIcon size="22" />
          </span>
          <span>
            <b>Freedom of choice</b> – We do not limit you to choose any path, you are free to study what you want, but
            it should be noted that when you choose a path you have to go through it without procrastinating or giving
            up if you really want to evolve
          </span>
        </li>
      </ul>
      <div class="flex flex-wrap gap-4">
        <a
          href="/resources/tutoring"
          class="py-3 px-4 inline-flex justify-center items-center gap-2 rounded-md variant-filled-tertiary border border-transparent font-semibold text-secondary-900-50-token hover:text-success-50-900-token hover:font-bold focus:outline-none focus:ring-2 ring-offset-white focus:ring-tertiary-500 focus:ring-offset-2 transition-all text-sm px-4 w-full">
          GO
        </a>
      </div>
    </div>
  </div>
</div>

<style>
  .list-items li {
    display: flex;
    gap: 16px;
    padding: 12px 0px;
  }
</style>