<template>
  <div class="bg-blue-200">
      <nav class="">
          <div class="bg-yellow-50 flex justify-between">
              <NuxtLink class="bg-pink-50 p-3" to="/">YuasysChannel</NuxtLink>
             
              <div class="bg-green-50" id="navbarNavAltMarkup">
                  <div class="p-3" >
                      <NuxtLink class="bg-slate-200 pr-3" activeClass="active" aria-current="page" to="/">Home</NuxtLink>
                      <NuxtLink class="bg-slate-200 pr-3" activeClass="active" to="/secondpage">Secondpage</NuxtLink>
                      <NuxtLink class="bg-slate-200" activeClass="active" to="/fishdata">FishData</NuxtLink>
                  </div>
              </div>
          </div>
      </nav>
  </div>
</template>