<script lang="ts">
  import Button from './Button.svelte';
  
  let isMenuOpen = false;
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-cream/90 backdrop-blur-sm border-b border-gray-200/50">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-20">
      <!-- Logo -->
      <div class="flex-shrink-0 flex items-center">
        <a href="/" class="flex items-center gap-2">
          <!-- NOC/TURNA Logo Icon -->
          <svg width="32" height="32" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-orange-brand">
            <path
              opacity="0.7"
              d="M9.22279 15.2235C12.6595 15.2235 15.4456 12.4375 15.4456 9.00075C15.4456 5.56399 12.6595 2.77795 9.22279 2.77795C5.78604 2.77795 3 5.56399 3 9.00075C3 12.4375 5.78604 15.2235 9.22279 15.2235Z"
              fill="currentColor"
            />
            <path
              opacity="0.7"
              d="M14.5566 20.5574C17.9933 20.5574 20.7794 17.7713 20.7794 14.3346C20.7794 10.8978 17.9933 8.11179 14.5566 8.11179C11.1198 8.11179 8.3338 10.8978 8.3338 14.3346C8.3338 17.7713 11.1198 20.5574 14.5566 20.5574Z"
              fill="currentColor"
            />
          </svg>
          <span class="font-bold text-xl tracking-tight">NOC/TURNA</span>
        </a>
      </div>

      <!-- Desktop Navigation -->
      <div class="hidden md:flex items-center space-x-8">
        <a href="#features" class="text-sm font-medium hover:text-orange-brand transition-colors">Features</a>
        <a href="#how-it-works" class="text-sm font-medium hover:text-orange-brand transition-colors">How It Works</a>
        <a href="#events" class="text-sm font-medium hover:text-orange-brand transition-colors">Events</a>
      </div>

      <!-- Right Side -->
      <div class="hidden md:flex items-center space-x-6">
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">About</a>
        <a href="#" class="text-sm font-medium hover:text-orange-brand transition-colors">Login</a>
        <Button href="#" className="!py-2 !px-4 !text-sm">Download App</Button>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden flex items-center">
        <button on:click={() => isMenuOpen = !isMenuOpen} class="text-gray-600 hover:text-gray-900 focus:outline-none">
          <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
      </div>
    </div>
  </div>
</nav>
