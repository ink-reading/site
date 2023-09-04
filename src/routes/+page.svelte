<svelte:head>
  <title>ink</title>
</svelte:head>

<main class="h-screen flex flex-col justify-center items-center text-[#ea6c61] font-mono">
  <div class="grow flex items-center">
    <div class="flex flex-col justify-center items-baseline gap-6 sm:flex-row">
      <div class="text-7xl">ink</div>
      <div class="text-xl">/// UNDER CONSTRUCTION</div>
    </div>
  </div>
  <div class="my-2 text-sm text-gray-400">https://ink-reading.app</div>
  <div class="mb-8 text-sm text-gray-400">https://github.com/ink-reading/ink</div>
</main>

<style>
  main::before {
    content: "";
    width: 100vw;
    height: 100vh;
    position: fixed;
    z-index: -1;
    background: radial-gradient(circle,rgba(2,0,36,0) 0,#fcfcfc 100%);
  }
  main::after {
    content: "";
    width: 100vw;
    height: 100vh;
    position: fixed;
    z-index: -2;
    background-image: url(/grid.svg);
    filter: invert(1);
    opacity: .5;
  }
</style>
