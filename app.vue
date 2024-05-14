<template>
  <div>
    <!-- This component requires some changes to the config and CSS file's to work properly. 👇 -->
    <!-- 

-->

    <!-- You also need to include the following css code in your CSS file -->
    <!-- 

 -->

    <div class="bg-gradient fixed inset-0 font-sans">
      <div
        class="fixed left-[50%] top-[50%] max-h-full w-full translate-x-[-50%] translate-y-[-50%] overflow-y-auto p-5 text-center sm:max-w-2xl"
      >
        <h1
          class="font-unbounded mb-6 text-4xl font-bold text-white md:text-6xl"
        >
          Join the revolutionary Reverse Job Board For Rust Engineers!
        </h1>
        <!-- <p class="mb-10 text-sm text-gray-300 md:text-sm">
          Be the first to know when our AI-based app launches and revolutionizes
          the way you work. Our app uses cutting-edge AI technology to automate
          tedious tasks and free up your time for the work that really matters.
          Sign up for our waitlist now and stay ahead of the curve.
        </p> -->
        <form class="grid">
          <!-- <input
            class="mb-3 h-12 rounded-lg border border-[#28272c] bg-[#28272c] px-4 text-sm leading-tight text-gray-700 placeholder-gray-300 focus:border-purple-500 focus:outline-none"
            placeholder="Your name"
          />
          <input
            class="mb-3 h-12 rounded-lg border border-[#28272c] bg-[#28272c] px-4 text-sm leading-tight text-gray-700 placeholder-gray-300 focus:border-purple-500 focus:outline-none"
            placeholder="Your email"
          /> -->

          <button
            class="mb-3 h-12 rounded-md bg-[#623df6] px-4 text-sm leading-tight text-white shadow-sm transition duration-300 hover:cursor-pointer hover:opacity-70 active:scale-95"
            data-tally-open="meBjpo"
            data-tally-layout="modal"
            data-tally-align-left="1"
            data-tally-hide-title="1"
            data-tally-emoji-text="👋"
            data-tally-emoji-animation="wave"
            data-tally-auto-close="0"
          >
            Join the waitlist
          </button>

          <!-- <button
          >
            Join the waitlist
          </button> -->
        </form>

        <footer class="mt-5 text-xs text-gray-400">
          &copy; {{ new Date().getFullYear() }}
          <a href="https://masteringbackend.com?ref=getrustjobs">
            Masteringbackend</a
          >
          inc. All rights reserved
        </footer>
      </div>
    </div>
  </div>
</template>
