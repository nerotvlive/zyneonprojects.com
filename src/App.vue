<script setup lang="ts">
  function showPage(page: string) {
    document.getElementById("dashboard")?.classList.remove("active");
    document.getElementById("discover")?.classList.remove("active");
    document.getElementById("downloads")?.classList.remove("active");
    document.getElementById("library")?.classList.remove("active");
    document.getElementById("search")?.classList.remove("active");
    document.getElementById("settings")?.classList.remove("active");
    document.getElementById("dashboard-button")?.classList.remove("active");
    document.getElementById("discover-button")?.classList.remove("active");
    document.getElementById("downloads-button")?.classList.remove("active");
    document.getElementById("library-button")?.classList.remove("active");
    document.getElementById("search-button")?.classList.remove("active");
    document.getElementById("settings-button")?.classList.remove("active");
    document.getElementById(page)?.classList.add("active");
    document.getElementById(page+"-button")?.classList.add("active");
  }

  document.addEventListener('contextmenu', (e) => {
    e.preventDefault()
  })
</script>

<template>
  <div class="zyneon-projects zyn-background-body select-none align-middle justify-center w-full h-full text-center" id="main">
    <h1 class="text-3xl font-bold">Fehler: Im Aufbau...</h1>
    <h2 class="text-xl font-bold">Die Zyneon Projects Website befindet sich aktuell in der Entwicklung<br>Versuche es später erneut!</h2>
  </div>
</template>

<style scoped>
  .zyneon-projects {
    position: absolute;
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 100%;
  }
</style>
