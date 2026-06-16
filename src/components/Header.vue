<script setup></script>

<template>
  <header class="sticky top-0 z-50 bg-bg-surface border-b border-border-default">
    <div class="max-w-7xl mx-auto px-6 h-[60px] bg-bg-brand flex items-center justify-between">
      <!-- Logo -->
      <a href="/" class="flex items-baseline gap-2 no-underline">
        <span
          class="text-[1.05rem] font-extrabold tracking-tight text-text-brand [text-shadow:0_0_18px_rgba(0,240,255,0.5)]"
        >
          Nexus Anime
        </span>
        <span
          class="text-[0.7rem] font-medium uppercase tracking-widest text-text-muted border-b border-border-brand pb-px"
        >
          Anime
        </span>
      </a>

      <!-- Actions -->
      <div class="flex items-center gap-2">
        <button
          class="flex items-center justify-center w-9 h-9 rounded-lg text-text-muted hover:text-text-default hover:bg-bg-container transition-colors"
        >
          <!-- icono layout/grid -->
          <svg
            width="18"
            height="18"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <rect x="3" y="3" width="7" height="7" />
            <rect x="14" y="3" width="7" height="7" />
            <rect x="3" y="14" width="7" height="7" />
            <rect x="14" y="14" width="7" height="7" />
          </svg>
        </button>

        <button
          class="w-[34px] h-[34px] rounded-full border border-border-default hover:border-border-brand bg-bg-container overflow-hidden transition-colors"
        >
          <img
            src="https://api.dicebear.com/7.x/avataaars/svg?seed=nexus"
            alt="Avatar"
            class="w-full h-full object-cover"
          />
        </button>
      </div>
    </div>
  </header>
</template>

<style scoped>
/* Para usar Tailwind con @apply aqui. Cambia la dirección en otras carpetas! */
@reference "../assets/main.css";
</style>
