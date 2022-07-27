<template>
  <!-- <Navbar /> -->
  <body>
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
    <!-- Hero -->
    <div class="container">
      <div class="hero-grid">
        <div class="content">
          <div class="hero-logo">
            <img
              class="logo"
              src="../assets/hero.jpeg"
              style="width: 100%; background url('..assets/wave.svg'); background-size: auto"
            />
          </div>
          <div class="wave">
            <img class="wave1" src="../assets/wave.svg" />
            <img class="wave2" src="../assets/wave (1).svg" />
          </div>

          <h1 class="title">
            Discover <br />
            Your Wonder
          </h1>
          <h4 class="sub-title">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam.
          </h4>
        </div>
      </div>
    </div>

    <!-- Who We Are -->
    <section class="who-we-are">
      <h1 class="title-who">Who we are</h1>
      <h3 class="sub-title-who">Technology Company</h3>
      <h4 class="text-who">
        Sed ut perspiciatis unde omnis iste natus sit voluptatem accusantium
        doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo
        inventore veritatis et quasi architecto beatae vitae dicta sunt
        explicabo.
      </h4>
      <div class="button-grid">
        <button>b</button>
        <button>a</button>
      </div>
    </section>

    <!-- Our Core Values -->
    <section class="our-core-values">
      <div class="our-core">
        <h1 class="title-our">Our Core Values</h1>
        <h4 class="text-our">
          Ridiculus laoreet libero pretium et, sit vel elementum convallis
          fames. Sit suspendisse etiam eget egestas. Aliquet odio et lectus
          etiam sit.
          <br />
          <br />
          In mauris rutrum ac ut volutpat, ornare nibh diam. Montes, vitae, nec
          amet enim.
        </h4>
        <div class="ul-our">
          <div class="flex-our-row">
            <div class="content-flex">
              <div class="strip">&#10134;</div>
              <div class="text">
                <h2 class="ul-our-title">Dedication</h2>
                <p class="ul-our-text">
                  Nam libero tempore, cum soluta nobis est eligendi optio cumque
                  nihil impedit quo minus id quod maxime placeat.
                </p>
              </div>
            </div>
            <div class="content-flex">
              <div class="strip">&#10134;</div>
              <div class="text">
                <h2 class="ul-our-title">Intelectual Honesty</h2>
                <p class="ul-our-text">
                  Nam libero tempore, cum soluta nobis est eligendi optio cumque
                  nihil impedit quo minus id quod maxime placeat.
                </p>
              </div>
            </div>
            <div class="content-flex">
              <div class="strip">&#10134;</div>
              <div class="text">
                <h2 class="ul-our-title">Curiosity</h2>
                <p class="ul-our-text">
                  Nam libero tempore, cum soluta nobis est eligendi optio cumque
                  nihil impedit quo minus id quod maxime placeat.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="section-bottom-right-img">
          <img src="../assets/person.png" />
        </div>
      </div>
    </section>

    <!-- Our Speciality -->
    <section class="our-speciality">
      <div class="border-box-wrap">
        <div class="border-box-speciality">
          <h1 class="title-specialty">Our Specialty</h1>
          <h4 class="sub-title-specialty">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis
            euismod libero vel leo auctor, in venenatis nulla consequat. Sed
            commodo nunc sit amet congue aliquam.
          </h4>
          <div id="default-carousel" class="relative" data-carousel="static">
            <!-- Carousel wrapper -->
            <div class="overflow-hidden relative h-56 rounded-lg md:h-96">
              <!-- Item 1 -->
              <div class="hidden duration-700 ease-in-out" data-carousel-item>
                <span
                  class="absolute top-1/2 left-1/2 text-2xl font-semibold text-white -translate-x-1/2 -translate-y-1/2 sm:text-3xl dark:text-gray-800"
                  >First Slide</span
                >
                <img
                  src="../assets/speed.png"
                  class="block absolute top-1/2 left-1/2 w-full -translate-x-1/2 -translate-y-1/2"
                  alt="..."
                />
              </div>
              <!-- Item 2 -->
              <div class="hidden duration-700 ease-in-out" data-carousel-item>
                <img
                  src="../assets/exhaust.png"
                  class="block absolute top-1/2 left-1/2 w-full -translate-x-1/2 -translate-y-1/2"
                  alt="..."
                />
              </div>
              <!-- Item 3 -->
              <div class="hidden duration-700 ease-in-out" data-carousel-item>
                <img
                  src="../assets/accesories.png"
                  class="block absolute top-1/2 left-1/2 w-full -translate-x-1/2 -translate-y-1/2"
                  alt="..."
                />
              </div>
            </div>
            <!-- Slider indicators -->
            <div
              class="flex absolute bottom-5 left-1/2 z-30 space-x-3 -translate-x-1/2"
            >
              <button
                type="button"
                class="w-3 h-3 rounded-full"
                aria-current="false"
                aria-label="Slide 1"
                data-carousel-slide-to="0"
              ></button>
              <button
                type="button"
                class="w-3 h-3 rounded-full"
                aria-current="false"
                aria-label="Slide 2"
                data-carousel-slide-to="1"
              ></button>
              <button
                type="button"
                class="w-3 h-3 rounded-full"
                aria-current="false"
                aria-label="Slide 3"
                data-carousel-slide-to="2"
              ></button>
            </div>
            <!-- Slider controls -->
            <button
              type="button"
              class="flex absolute top-0 left-0 z-30 justify-center items-center px-4 h-full cursor-pointer group focus:outline-none"
              data-carousel-prev
            >
              <span
                class="inline-flex justify-center items-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none"
              >
                <svg
                  aria-hidden="true"
                  class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M15 19l-7-7 7-7"
                  ></path>
                </svg>
                <span class="sr-only">Previous</span>
              </span>
            </button>
            <button
              type="button"
              class="flex absolute top-0 right-0 z-30 justify-center items-center px-4 h-full cursor-pointer group focus:outline-none"
              data-carousel-next
            >
              <span
                class="inline-flex justify-center items-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none"
              >
                <svg
                  aria-hidden="true"
                  class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9 5l7 7-7 7"
                  ></path>
                </svg>
                <span class="sr-only">Next</span>
              </span>
            </button>
          </div>
          <div class="carousel-wrapper">
            <div v-swiper:mySwiper="options">
              <div class="swiper-wrapper">
                <div v-for="i in 5" :key="i" class="img-warpper swiper-slide">
                  <img :src="`https://picsum.photos/200/100?random=${i}`" />
                </div>
              </div>
              <div class="swiper-pagination swiper-pagination-bullets"></div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Footer -->
    <section class="footer">
      <div class="footer-wrap">
        <div class="footer-content"></div>
      </div>
    </section>
  </body>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      options: {
        slidesPerView: 3,
        loop: true,
        pagination: {
          el: ".swiper-pagination",
        },
      },
    };
  },
};
</script>

<style>
/* Hero */
.title {
  text-align: start;
  font-family: "Rubik";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 34px;
  margin-left: 10%;
}
.sub-title {
  text-align: start;
  font-family: "Rubik";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.01em;
  margin-left: 10%;
  margin-right: 10%;
  margin-top: 5%;
}

/* Who we are */
.who-we-are {
  margin: 10%;
  height: 245px;
}
.title-who {
  font-family: "Rubik";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 30px;
  color: #029fe4;
}
.sub-title-who {
  font-family: "Rubik";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 38px;
  margin-top: 2%;
  margin-left: 1%;
}
.text-who {
  font-family: "Rubik";
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.01em;
  color: #777777;
}
.button-grid {
  display: flex;
  justify-content: space-between;
}

/* Our core values */
.our-core-values {
  background-color: #f8f8f8;
}
.our-core {
  padding: 10%;
}
.title-our {
  text-align: center;
  font-family: "Rubik";
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 30px;
  color: #029fe4;
}
.text-our {
  margin-top: 4%;
  font-family: "Rubik";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.01em;
  color: #777777;
}
/* .flex-our-row {
  display: flex;
  flex-wrap: flex;
  flex-direction: column;
} */
.content-flex {
  margin-top: 25px;
  display: flex;
  flex-wrap: flex;
  flex-direction: row;
}
.strip {
  width: 200px;
}
.ul-our-title {
  font-family: "Rubik";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 38px;
}
.ul-our-text {
  font-family: "Rubik";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  color: #777777;
}
.section-bottom-right-img {
  width: 360px;
  display: flex;
  justify-content: flex-end;
  align-items: flex-end;
  align-content: flex-end;
}

/* Our speciality */
.border-box-wrap {
  background-color: #509fdd;
  padding-top: 7%;
  padding-bottom: 7%;
  padding-left: 3%;
  padding-right: 3%;
}

.border-box-speciality {
  padding: 7%;
  background-color: white;
  border: 0.1px solid white;
  justify-items: center;
  text-align: left;
}

.title-specialty {
  font-family: "Rubik";
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
  text-transform: uppercase;
  margin-bottom: 12px;

  color: #029fe4;
}
.sub-title-specialty {
  font-family: "Rubik";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 24px;
  color: #303030;
}
.carousel-wrapper {
  padding: 40px;
  height: 300px;
  width: 100%;
}
.swiper-slide {
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
}
.img-warpper img {
  margin: auto;
  width: 200px;
  height: 100px;
  background-image: linear-gradient(gray 100%, transparent 0);
}
::v-deep.swiper-pagination-bullet-active {
  background-color: black;
}
/* Footer */
.footer-wrap {
  background: #07477a;
}
</style>
