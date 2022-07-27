<template>
  <div>
    <!-- Hamburger Navbar -->
    <nav
      class="relative px-1 py-1 flex justify-between items-center"
      style="top: 0px; background-color: white; position: fixed; width: 100%"
    >
      <a class="text-3xl font-bold leading-none" href="/home.html">
        <img src="../assets/logo.jpeg" alt="logo" width="70" />
      </a>
      <div class="lg:hidden">
        <button class="navbar-burger flex items-center text-gray-800 p-3">
          <svg
            class="block h-4 w-4 fill-current"
            viewBox="0 0 20 20"
            xmlns="http://www.w3.org/2000/svg"
          >
            <title>Mobile menu</title>
            <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
          </svg>
        </button>
      </div>
      <ul
        class="hidden absolute top-1/2 left-1/2 transform -translate-y-1/2 -translate-x-1/2 lg:flex lg:mx-auto lg:flex lg:items-center lg:w-auto lg:space-x-2"
      >
        <li>
          <a class="text-sm text-gray-400 hover:text-gray-500" href="/home.html"
            >Who We Are</a
          >
        </li>
        <li class="text-gray-300">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            stroke="currentColor"
            class="w-4 h-4 current-fill"
            viewBox="0 0 24 24"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v0m0 7v0m0 7v0m0-13a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            />
          </svg>
        </li>
        <li>
          <a
            class="text-sm text-gray-400 hover:text-gray-500"
            href="/our-work.html"
            >Our Values</a
          >
        </li>
        <li class="text-gray-300">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            stroke="currentColor"
            class="w-4 h-4 current-fill"
            viewBox="0 0 24 24"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 5v0m0 7v0m0 7v0m0-13a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
            />
          </svg>
        </li>
        <li>
          <a
            class="text-sm text-gray-400 hover:text-gray-500"
            href="/contact.html"
            >The Perks</a
          >
        </li>
        <li class="text-gray-300"></li>
      </ul>
    </nav>
    <div class="navbar-menu relative z-50 hidden">
      <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
      <nav
        class="fixed top-0 left-0 bottom-0 flex flex-col w-5/6 max-w-sm py-6 px-6 bg-white border-r overflow-y-auto"
      >
        <div class="flex items-center mb-8">
          <a class="mr-auto text-3xl font-bold leading-none" href="#">
            <img src="/header-img/logo.png" alt="logo" width="70" />
          </a>
          <button class="navbar-close">
            <svg
              class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M6 18L18 6M6 6l12 12"
              ></path>
            </svg>
          </button>
        </div>
        <div>
          <ul>
            <li class="mb-1">
              <a
                class="block p-4 text-sm font-semibold text-gray-400 hover:bg-gray-300 hover:text-gray-700 rounded"
                href="#"
                >Who We Are</a
              >
            </li>
            <li class="mb-1">
              <a
                class="block p-4 text-sm font-semibold text-gray-400 hover:bg-gray-300 hover:text-gray-700 rounded"
                href="#"
                >Our Values</a
              >
            </li>
            <li class="mb-1">
              <a
                class="block p-4 text-sm font-semibold text-gray-400 hover:bg-gray-300 hover:text-gray-700 rounded"
                href="#"
                >The Perks</a
              >
            </li>
          </ul>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "SaltNavbar",
};
</script>

<style></style>
