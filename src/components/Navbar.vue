<template>
  <nav class="navbar">
    <div class="navbar-brand">
      <a class="navbar-item" href="#">Dzaki Portofolio</a>
      <button class="navbar-burger burger" @click="toggleNavbar" :class="{ 'is-active': isActive }" aria-label="menu" aria-expanded="false" data-target="navbarMenu">
        <span></span>
        <span></span>
        <span></span>
      </button>
    </div>
    <div class="navbar-menu" :class="{ 'is-active': isActive }" id="navbarMenu">
      <div class="hidden w-full md:block md:w-auto">
          <ul
            class="flex flex-col mt-4 rounded-lg text-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-transparent dark:bg-gray-800 md:dark:bg-transparent dark:border-gray-700">
            <li id="beranda">
              <router-link
                to="/"
        class="font-general-medium block text-left text-lg font-medium text-primary-dark dark:text-ternary-light hover:text-black-600 dark:hover:text-black-300  sm:mx-4 mb-2 sm:py-2 border-t-2 pt-3 sm:pt-2 sm:border-t-0 border-primary-light dark:border-secondary-dark"
        aria-label="Home"
        >Beranda
              </router-link>
            </li>
            <li id="kontak">
              <router-link
              to="/contact"
        class="font-general-medium block text-left text-lg font-medium text-primary-dark dark:text-ternary-light hover:text-black-600 dark:hover:text-black-300  sm:mx-4 mb-2 sm:py-2 border-t-2 pt-3 sm:pt-2 sm:border-t-0 border-primary-light dark:border-secondary-dark"
        aria-label="Kontak"
        >Kontak
              </router-link>
            </li>
            <li id="tentang">
              <router-link
              to="/about"
        class="font-general-medium block text-left text-lg font-medium text-primary-dark dark:text-ternary-light hover:text-black-600 dark:hover:text-black-300  sm:mx-4 mb-2 sm:py-2 border-t-2 pt-3 sm:pt-2 sm:border-t-0 border-primary-light dark:border-secondary-dark"
        aria-label="About Me"
        >Tentang
              </router-link>
            </li>
            
  
            <li></li>
            <li></li>
  
          </ul>
        </div>
    </div>
  </nav>

</template>


<script>
export default {
  data() {
    return {
      isActive: false,
    };
  },
  methods: {
    toggleNavbar() {
      this.isActive = !this.isActive;
    },
  },
};
</script>


<style>

#beranda{
  color: white;
}

#kontak{
  color: white;
}

#tentang{
  color: white;
}

.navbar {
  background-color: #3B3B3B;
}

.navbar-burger {
  color: #fff;
}

.navbar-burger:hover {
  color: #fff;
}

.navbar-menu {
  background-color: #3B3B3B;
  position: absolute;
  top: 100%;
  left: 0;
  right: 0;
  z-index: 1;
  padding: 1em;
  display: none;
}

.navbar-menu.is-active {
  display: block;
}

.navbar-item {
  color: #fff;
  padding: 0.5em;
  border-bottom: 1px solid #fff;
}

@media screen and (min-width: 768px) {
  .navbar-menu {
    position: relative;
    top: auto;
    left: auto;
    right: auto;
    padding: 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
  }

  .navbar-start {
    display: flex;
    align-items: center;
  }

  .navbar-item {
    border-bottom: none;
    margin-left: 1em;
    margin-right: 1em;
  }
}
</style>
