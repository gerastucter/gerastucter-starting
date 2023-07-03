<script>
  // Import theme
  import '../theme.postcss'
  
  
  //Theme system 
  // import { autoModeWatcher } from '@skeletonlabs/skeleton';
  
  // Import components
  import FooterComponent from  '../utilities/components/FooterComponent.svelte'
  // Skeleton imports
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	import '../app.postcss';
	import { AppShell } from '@skeletonlabs/skeleton';
	
	// Errors and more
	import { page } from '$app/stores';
	
	
	
</script>

<svelte:head>
  <!--{@html `<script>${autoModeWatcher.toString()} autoModeWatcher();</script>`}-->
</svelte:head>



<AppShell class="max-w-screen">
  <!-- Router Slot -->
  <slot class="w-full"/>
  <!-- ---- / ---- -->
  <svelte:fragment slot="sidebarRight">
    <nav translate="no"class="h-full w-auto px-2">
      <ul class="flex flex-col items-center justify-around h-full">
        <li class="p-2 textScreen">
          <a class="flex flex-col items-center justify-center" href="#">
            <span>T</span>
            <span>E</span>
            <span>R</span>
            <span>M</span>
            <span>S</span>
          </a>
        </li>
        <li class="p-2 textScreen">
          <a class="flex flex-col items-center justify-center" href="#">
            <span>P</span>
            <span>R</span>
            <span>I</span>
            <span>V</span>
            <span>A</span>
            <span>C</span>
            <span>Y</span>
            <span>-</span>
            <span>P</span>
            <span>O</span>
            <span>L</span>
            <span>I</span>
            <span>C</span>
            <span>Y</span>
          </a>
        </li>
      </ul>
    </nav>
	</svelte:fragment>
  <svelte:fragment slot="pageFooter">
    {#if $page.status != 404}
    <FooterComponent />
    {/if}
  </svelte:fragment>
  <!-- (footer) -->
</AppShell>

<style type="text/css" media="all">

  .textScreen {
    animation: textToAnim 3s ease-in ;
  }

  @keyframes textToAnim {
    from {
      opacity: 0;
      transform: scale(0.3);
    }
    to {
      opacity: 1;
      transform: scale(1);
    }
  }
</style>