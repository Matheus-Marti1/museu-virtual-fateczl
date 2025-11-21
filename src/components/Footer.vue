<script setup>
const currentYear = new Date().getFullYear();
</script>

<template>
  <footer class="w-full bg-black/40 backdrop-blur-xl border-t border-white/10 mt-auto z-40">
    <div class="container mx-auto px-6 py-12">
      <div class="flex flex-col md:flex-row justify-between items-center md:items-start gap-8 text-center md:text-left">
        <div class="space-y-4 max-w-md">
          <div class="flex items-center justify-center md:justify-start gap-3">
            <img src="/images/logo_fatec.png" alt="Logo Fatec" class="h-10 w-auto opacity-90" />
            <h3 class="text-xl font-bold text-white tracking-wide">Museu do Hardware</h3>
          </div>
          <p class="text-gray-400 text-sm leading-relaxed">
            Uma jornada interativa pela história da computação. Explore a evolução do hardware através de nossa linha do tempo e acervo digital.
          </p>
        </div>

        <div class="space-y-4 md:text-right">
          <h4 class="text-lg font-semibold text-white">Sobre</h4>
          <p class="text-gray-400 text-sm leading-relaxed">
            Projeto desenvolvido por alunos da Fatec Zona Leste.
          </p>
          <div class="pt-2 flex justify-center md:justify-end">
            <a href="https://fateczl.cps.sp.gov.br/" target="_blank" rel="noopener noreferrer" 
               class="inline-flex items-center gap-2 px-4 py-2 rounded-lg bg-white/5 hover:bg-white/10 border border-white/10 hover:border-white/20 transition-all duration-300 text-sm text-gray-300 hover:text-white">
              <span>Visitar site da Fatec</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14" />
              </svg>
            </a>
          </div>
        </div>
      </div>
      <div class="mt-12 pt-8 border-t border-white/10 flex justify-center">
        <p class="text-gray-500 text-xs">
          &copy; {{ currentYear }} Museu Virtual do Hardware. Todos os direitos reservados.
        </p>
      </div>
    </div>
  </footer>
</template>
