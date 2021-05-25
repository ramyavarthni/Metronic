<template>
  <div class=" bg-contain bg-fixed bg-no-repeat bg-left-bottom" style="background-image: url(https://preview.keenthemes.com/metronic8/demo1/assets/media/illustrations/progress-hd.png);">
      <div class="flex flex-col h-screen overflow-auto">
        <div class="sec flex-1 my-8">
          <img class="mb-3 mx-auto" style="height: 45px;" src="https://preview.keenthemes.com/metronic8/demo1/assets/media/logos/logo-2-dark.svg" alt="">
          </div>
    <!-- Auth Card Container -->
    <div class="grid place-items-center mx-2 my-20 sm:my-auto">
      <!-- Auth Card -->
      <div class="w-full p-12 sm:w-8/12 md:w-6/12 lg:w-5/12 2xl:w-4/12 
          px-6 py-10 sm:px-10 sm:py-6 border border-opacity-10 drop-shadow-md
          bg-white rounded-lg shadow-md lg:shadow-lg">
    
          <!-- Card Title -->
          <h2 class="text-center font-semibold text-1xl lg:text-2xl text-gray-800">
            Sign In to Metronic
          </h2>
          <div class="text-gray-400 text-center mt-3 font-black font-medium">New Here?
            <a href="signup.html" class="link-primary text-blue-400 font-black font-medium">Create an Account</a>
            <!--end::Link-->
          </div>
    
    
          <div class = "my-8">
            <label class="block text-dark font-black">Email </label>
            <input type="email" name="email" id=""  class="w-full px-4 py-3 rounded-lg  bg-blue-50 text-gray-700 font-semibold mt-2 focus:outline-none" autofocus autocomplete required >
          </div>
    
    
          <div class="mt-4">
            <div class="flex justify-between mb-2">
              <label for="password" class="text-sm  text-dark font-black ">Password</label>
              <a href="#!" class="text-sm text-blue-400  font-black ">Forgot password?</a>
          </div>
            <input type="password" name="" id=""  minlength="6" class="w-full px-4 py-3 rounded-lg bg-blue-50 mt-2 
                 focus:outline-none" required>
          </div>
          
    
     
          <div>
            
            <button type="submit" class="w-full block mt-10 bg-blue-500  text-white font-semibold rounded-lg
                px-4 py-3 mt-6 focus:outline-none">continue</button>
        </div>

          <div class="text-center fw-bold font-black my-3 text-gray-400 mt-5">OR</div>
       

          <div class="p-2">
            <button type="button" class="transition duration-200 bg-blue-50 hover:bg-gray-200 focus:bg-gray-200 focus:shadow-sm  text-white py-2.5 rounded-lg text-sm font-semibold text-center w-full inline-block focus:outline-none">
              <div class="flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" class="w-6 h-6" viewBox="0 0 48 48"><defs><path id="a" d="M44.5 20H24v8.5h11.8C34.7 33.9 30.1 37 24 37c-7.2 0-13-5.8-13-13s5.8-13 13-13c3.1 0 5.9 1.1 8.1 2.9l6.4-6.4C34.6 4.1 29.6 2 24 2 11.8 2 2 11.8 2 24s9.8 22 22 22c11 0 21-8 21-22 0-1.3-.2-2.7-.5-4z"/></defs><clipPath id="b"><use xlink:href="#a" overflow="visible"/></clipPath><path clip-path="url(#b)" fill="#FBBC05" d="M0 37V11l17 13z"/><path clip-path="url(#b)" fill="#EA4335" d="M0 11l17 13 7-6.1L48 14V0H0z"/><path clip-path="url(#b)" fill="#34A853" d="M0 37l30-23 7.9 1L48 0v48H0z"/><path clip-path="url(#b)" fill="#4285F4" d="M48 48L17 24l-4-3 35-10z"/></svg>
              <span class="ml-4 text-gray-600">
              continue
              with
              Google</span>
              </div>
            </button>
          </div>
              
        
        
    
          <div class="p-2">
            <button type="button" class="transition duration-200 bg-blue-50 hover:bg-gray-200 focus:bg-gray-200 focus:shadow-sm  text-white py-2.5 rounded-lg text-sm font-semibold text-center w-full inline-block focus:outline-none">
              <div class="flex items-center justify-center">
                <img alt="Logo" src="https://preview.keenthemes.com/metronic8/demo1/assets/media/svg/brand-logos/facebook-4.svg" class="h-20px me-3" />
              <span class="ml-4 text-gray-600">
              continue
              with
              Facebook</span>
              </div>
            </button>
          </div>
      
          
            
      <div class="p-2">
        <button type="button" class="transition duration-200 bg-blue-50 hover:bg-gray-200 focus:bg-gray-200 focus:shadow-sm  text-white py-2.5 rounded-lg text-sm font-semibold text-center w-full inline-block focus:outline-none">
          <div class="flex items-center justify-center">
            <img alt="Logo" width="19" height="19" src="https://preview.keenthemes.com/metronic8/demo1/assets/media/svg/brand-logos/apple-black.svg"  />
          <span class="ml-4 text-gray-600">
          continue
          with
          Apple</span>
          </div>
        </button>
      </div>
    
    
 
    
      </div>
    </div>
    
    
    
    <div class="d-flex flex-center flex-column-auto mt-20 p-10">
    <!--begin::Links-->
    <div class="d-flex text-center align-items-center font-semibold fs-6 text-gray-400  ">
      <a href="https://keenthemes.com/faqs" class="text-muted text-hover-primary px-2">About</a>
      <a href="mailto:support@keenthemes.com" class="text-muted text-hover-primary px-2">Contact</a>
      <a href="https://1.envato.market/EA4JP" class="text-muted text-hover-primary px-2">Contact Us</a>
    </div>
    
    </div>
    
    <!--end::Links-->
    
    </div>
    </div>
    
</template>

<script setup>
import { defineProps, reactive } from 'vue'

</script>


