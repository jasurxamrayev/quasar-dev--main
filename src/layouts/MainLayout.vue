<template>
  <q-layout view="hhh lpR fFf">

    <q-header style="height:13%" reveal bordered class="bg-transparent text-white" height-hint="98">
      <q-toolbar>
        <q-toolbar-title>
          <div style="margin-top:30px;" class="fit row  justify-around items-center content-center">
            <div>
               <img src="https://xtrm.foxthemes.me/wp-content/uploads/2018/09/white.png">
            </div>
            <div width="70%">
               <q-btn-dropdown unelevated class="bg-transparent mg" label="HOME" />
               <q-btn-dropdown unelevated class="bg-transparent mg" label="PAGES" />
               <q-btn-dropdown unelevated class="bg-transparent mg" label="SHOWCASES" />
               <q-btn-dropdown unelevated class="bg-transparent mg" label="BLOG" />
               <q-btn-dropdown unelevated class="bg-transparent mg" label="SHOP" />
               <q-btn-dropdown unelevated class="bg-transparent mg" label="PRICING" />
               <q-btn-dropdown unelevated class="bg-transparent mg" label="CONTECT US" />

            </div>
          </div>




        </q-toolbar-title>
      </q-toolbar>


    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>



  </q-layout>
</template>
<style scoped>
.mg{
  margin-left: 30px;
}
</style>
