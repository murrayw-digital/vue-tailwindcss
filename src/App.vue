<template>
  <div class="antialiased text-gray-800">
    <header
      :style="{'background-image': 'url(' + require('./assets/img/airbnb-home.jpg') + ')'}"
      class="bg-smoke-light z-50 relative bg-no-repeat bg-cover lg:bg-center p-6 bg-top-right"
    >
      <a href="/">
        <h1>
          <span class="sr-only">Airbnb</span>
          <svg
            viewBox="0 0 1000 1000"
            role="img"
            aria-label="Home"
            focusable="false"
            class="w-8 h-8 fill-current text-white"
          >
            <path
              d="m499.3 736.7c-51-64-81-120.1-91-168.1-10-39-6-70 11-93 18-27 45-40 80-40s62 13 80 40c17 23 21 54 11 93-11 49-41 105-91 168.1zm362.2 43c-7 47-39 86-83 105-85 37-169.1-22-241.1-102 119.1-149.1 141.1-265.1 90-340.2-30-43-73-64-128.1-64-111 0-172.1 94-148.1 203.1 14 59 51 126.1 110 201.1-37 41-72 70-103 88-24 13-47 21-69 23-101 15-180.1-83-144.1-184.1 5-13 15-37 32-74l1-2c55-120.1 122.1-256.1 199.1-407.2l2-5 22-42c17-31 24-45 51-62 13-8 29-12 47-12 36 0 64 21 76 38 6 9 13 21 22 36l21 41 3 6c77 151.1 144.1 287.1 199.1 407.2l1 1 20 46 12 29c9.2 23.1 11.2 46.1 8.2 70.1zm46-90.1c-7-22-19-48-34-79v-1c-71-151.1-137.1-287.1-200.1-409.2l-4-6c-45-92-77-147.1-170.1-147.1-92 0-131.1 64-171.1 147.1l-3 6c-63 122.1-129.1 258.1-200.1 409.2v2l-21 46c-8 19-12 29-13 32-51 140.1 54 263.1 181.1 263.1 1 0 5 0 10-1h14c66-8 134.1-50 203.1-125.1 69 75 137.1 117.1 203.1 125.1h14c5 1 9 1 10 1 127.1.1 232.1-123 181.1-263.1z"
            />
          </svg>
        </h1>
      </a>

      <div class="max-w-5xl mx-auto lg:py-32 py-2">
        <h2
          class="lg:text-5xl text-4xl font-semibold text-white leading-none mb-4"
        >Book a trip. Host travels. All on Airbnb</h2>
        <div class="flex items-center flex-wrap justify-start max-w-2xl lg:mx-0 mx-auto">
          <div class="lg:pr-5 w-full lg:w-1/2 mb-4 lg:mb-0">
            <p class="text-white mb-2 tracking-wide">Find places to stay and things to do.</p>
            <a
              href="#"
              class="transition bg-white px-10 py-3 rounded font-bold hover:bg-gray-300 block w-full text-center border-2 border-white"
            >Explore</a>
          </div>
          <div class="lg:pr-5 w-full lg:w-1/2 mb-4 lg:mb-0">
            <p class="text-white mb-2 tracking-wide">Earn money from your extra space.</p>
            <a
              href="#"
              class="transition bg-transparent text-white px-10 py-3 rounded font-bold hover:bg-gray-800 block w-full text-center border-2 border-white"
            >Host</a>
          </div>
        </div>
      </div>
    </header>

    <div class="max-w-5xl mx-auto lg:py-16 py-12 lg:px-0 px-4">
      <h3 class="font-bold text-2xl mb-4 leading-none">Book unique homes and experiences</h3>
      <form class="lg:mb-16 mb-10">
        <div class="flex items-start justify-start flex-wrap">
          <div class="lg:w-1/3 w-full lg:pr-2 mb-4 lg:mb-0">
            <label for="where" class="label">Where</label>
            <input type="text" class="input" id="where" placeholder="Anywhere" />
          </div>
          <div class="lg:w-1/3 w-full lg:px-2 mb-4 lg:mb-0">
            <label for="checkin_checkout" class="label">Check-in - Checkout</label>
            <input
              type="text"
              class="input"
              id="checkin_checkout"
              placeholder="mm/dd/yyy - mm/dd/yyyy"
            />
          </div>
          <div class="lg:w-1/3 w-full lg:pl-2">
            <label for="guests" class="label">Guests</label>
            <div class="relative">
              <select id="guests" class="input select">
                <option value="1">1 guest</option>
                <option value="2">2 guests</option>
                <option value="3">3 guests</option>
              </select>
              <div
                class="pointer-events-none absolute inset-y-0 right-0 flex items-center px-2 text-gray-700"
              >
                <svg
                  class="fill-current w-4 h-4"
                  viewBox="0 0 18 18"
                  role="presentation"
                  aria-hidden="true"
                  focusable="false"
                >
                  <path
                    d="m16.29 4.3a1 1 0 1 1 1.41 1.42l-8 8a1 1 0 0 1 -1.41 0l-8-8a1 1 0 1 1 1.41-1.42l7.29 7.29z"
                    fill-rule="evenodd"
                  />
                </svg>
              </div>
            </div>
          </div>
        </div>
      </form>

      <h3
        class="font-bold text-2xl mb-4 lg:mb-2 leading-none"
      >What guests are saying about homes in Cape Town</h3>

      <div class="flex lg:items-center items-center">
        <svg
          class="w-4 h-4 flex-shrink-0"
          viewBox="0 0 24 24"
          role="presentation"
          aria-hidden="true"
          focusable="false"
          style="height:24px;width:24px;fill:#FFB400"
        >
          <path
            d="m21.95 9.48a.84.84 0 0 0 -.87-.48h-4.62a.5.5 0 0 0 0 1l4.14.01-4.81 4.17a.5.5 0 0 0 -.14.57l2.65 6.38-6.07-3.72a.5.5 0 0 0 -.52 0l-6.08 3.72 2.65-6.37a.5.5 0 0 0 -.13-.57l-4.75-4.18h5.75a.5.5 0 0 0 .46-.3l2.37-5.37 1.58 3.57a.5.5 0 0 0 .91-.41l-1.72-3.88a.8.8 0 0 0 -1.56-.01l-2.38 5.39h-5.9a.83.83 0 0 0 -.87.48.85.85 0 0 0 .32.96l4.85 4.25-2.78 6.67a.81.81 0 0 0 .16.98.66.66 0 0 0 .43.15 1.1 1.1 0 0 0 .56-.18l6.37-3.91 6.38 3.92a.81.81 0 0 0 .99.03c.15-.12.37-.41.15-1l-2.77-6.66 4.92-4.26a.84.84 0 0 0 .31-.95zm-.78.53h-.01"
            fill="#484848"
          />
          <path
            d="m11 21.5a.5.5 0 1 1 -.5-.5.5.5 0 0 1 .5.5zm-3.5-15.5a.5.5 0 1 0 .5.5.5.5 0 0 0 -.5-.5zm15 10h-.5v-.5a.5.5 0 0 0 -1 0v .5h-.5a.5.5 0 0 0 0 1h .5v.5a.5.5 0 0 0 1 0v-.5h.5a.5.5 0 0 0 0-1zm-15-13h-.5v-.5a.5.5 0 0 0 -1 0v .5h-.5a.5.5 0 0 0 0 1h .5v.5a.5.5 0 0 0 1 0v-.5h.5a.5.5 0 0 0 0-1zm10.22 7.54a.84.84 0 0 0 -.17-.02q-.28-.01-3.19 0a .6.6 0 0 1 -.55-.35l-1.5-3.23a.42.42 0 0 0 -.75 0l-1.81 4.14a2.92 2.92 0 0 0 4.12 3.72l.46-.26 3.49-2.99.16-.18a.5.5 0 0 0 -.26-.82z"
          />
        </svg>
        <p class="pl-2">
          United States homes were
          <strong>rated 4.8 out of 5 stars</strong> with
          <strong>42,500,000+ reviews</strong>
        </p>
      </div>

      <section class="flex items-start flex-wrap justify-between lg:my-10 my-6">
        <!-- Card 1 -->
        <article class="lg:w-1/3 w-full lg:pr-4 lg:mb-0 mb-6">
          <img src="@/assets/img/card1.jpg" class="object-cover rounded w-full" alt />
          <div class="my-3 flex justify-start items-center">
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
          </div>
          <p
            class="text-gray-700 font-light text-sm leading-snug"
          >Perfect location, hiking trails starting at the frontdoor and only a couple of minutes away from the great restaurants in Boulder. We felt...</p>
          <div class="flex items-center justify-start my-4">
            <img src="@/assets/img/katie.jpg" class="w-12 h-12 rounded-full flex-shrink-0" alt />
            <div class="flex-1 pl-4 text-sm">
              <p class="font-semibold leading-none">Katie</p>
              <p>Belgium</p>
            </div>
          </div>
        </article>

        <!-- Card 2 -->
        <article class="lg:w-1/3 w-full lg:px-2 lg:mb-0 mb-6">
          <img src="@/assets/img/card2.jpg" class="object-cover rounded w-full" alt />
          <div class="my-3 flex justify-start items-center">
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
          </div>
          <p
            class="text-gray-700 font-light text-sm leading-snug"
          >My boyfriend and I had an incredible experience in this cabin. We had everything we needed to enjoy our stay there and everything...</p>
          <div class="flex items-center justify-start my-4">
            <img src="@/assets/img/jen.jpg" class="w-12 h-12 rounded-full flex-shrink-0" alt />
            <div class="flex-1 pl-4 text-sm">
              <p class="font-semibold leading-none">Jen</p>
              <p>United States</p>
            </div>
          </div>
        </article>

        <!-- Card 3 -->
        <article class="lg:w-1/3 w-full lg:pl-4 lg:mb-0 mb-6">
          <img src="@/assets/img/card3.jpg" class="object-cover rounded w-full" alt />
          <div class="my-3 flex justify-start items-center">
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
            <svg
              class="fill-current w-4 h-4 text-cyan mr-1"
              viewBox="0 0 1000 1000"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M972 380c9 28 2 50-20 67L725 619l87 280c11 39-18 75-54 75-12 0-23-4-33-12L499 790 273 962a58 58 0 0 1-78-12 50 50 0 0 1-8-51l86-278L46 447c-21-17-28-39-19-67 8-24 29-40 52-40h280l87-279c7-23 28-39 52-39 25 0 47 17 54 41l87 277h280c24 0 45 16 53 40z"
              />
            </svg>
          </div>
          <p
            class="text-gray-700 font-light text-sm leading-snug"
          >Bob and Karen gave us a detailed description of the neighborhood and made my first airbnb experience a pleasant one. The place was also...</p>
          <div class="flex items-center justify-start my-4">
            <img src="@/assets/img/miles.jpg" class="w-12 h-12 rounded-full flex-shrink-0" alt />
            <div class="flex-1 pl-4 text-sm">
              <p class="font-semibold leading-none">Miles</p>
              <p>United States</p>
            </div>
          </div>
        </article>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {}
};
</script>

<style>
</style>
