<template>
  <div>
    <q-img style="position:absolute; top:0%; height:500px;" src="	https://xtrm.foxthemes.me/wp-content/uploads/2018/12/Group-1.png">
      <div style="width:50%;height:100%;background: #f569238d; " class="  row  justify-around items-start content-center">
        <br><br><br>
        <div>
          <div class="text-h6 text-weight-light">ABOUT US</div><br>
         <div style="font-size:75px" class=" text-weight-regular">Why You Should</div><br>
         <div  class="text-weight-bolder bg-black" style=" font-size:60px;width:310px;padding-left:5px">Choose Us</div>
        </div>
      </div>



    </q-img>
    <div style="margin-top:500px"></div>
    <div class="row  justify-around  items-center content-center">
    <!-- card1 -->
      <q-card style="width: 23%" class="my-card card-hover"><br>
        <div class="text-h2 text-weight-medium" style="margin-left:100px ">01.</div>
      <q-card-section>
        <div class="text-h6">We're Super Talented Team</div><br>
        <div class="text-subtitle1 text-center text-weight-light">Nam porttitor blandit <br> accumsan. Ut vel dictum sem, <br> a pretium dui. In malesuada.</div><br>
      </q-card-section><br>
    </q-card>
        <!-- card2 -->
      <q-card style="width: 23%" class="my-card card-hover border"><br>
        <div class="text-h2 text-weight-medium" style="margin-left:100px ">02.</div>
      <q-card-section>
        <div class="text-h6">We Have Best Equipment</div><br>
        <div class="text-subtitle1 text-center text-weight-light">In hac habitasse platea <br> dictumst. Vivamus adipiscing <br>fermentum quam volutpat.</div><br>
      </q-card-section><br>
    </q-card>
        <!-- card1 -->
      <q-card style="width: 23%" class="my-card card-hover"><br>
        <div class="text-h2 text-weight-medium" style="margin-left:100px ">03.</div>
      <q-card-section>
        <div class="text-h6">We’re The Best Company</div><br>

        <div class="text-subtitle1 text-center text-weight-light">Cras quis nulla commodo, <br>aliquam lectus sed, blandit<br> augue. Cras ullamcorper.</div><br>
      </q-card-section><br>
    </q-card>
        <!-- card1 -->
      <q-card style="width: 23%;height: 290px;" class="my-card card-hover"><br>
        <div class="text-h2 text-weight-medium" style="margin-left:100px ">04.</div>
      <q-card-section>
        <div class="text-h6">We Have Coffee and Cookies</div><br>
        <div class="text-subtitle1 text-center text-weight-light">We Have Coffee and Cookies <br> fringilla rutrum. Aenean <br> sollicitudin, erat a elem.</div><br>
      </q-card-section><br>
    </q-card>
    </div>
    <div style="margin-top:100px;"></div>
    <div class="fit row wrap justify-around items-center content-center">
      <q-img style="width:600px" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/12/bitmap.png"></q-img>
      <div>
        <div style="margin-left: 10px">
          <div class="text-subtitle1 text-weight-light">ABOUT US</div>
          <div class="text-h4 text-bolder">You Won’t Get Bored <span style="color:#fff;background: #222;"> With Us</span> </div>
        </div><br>
<!-- ochiluvchi card 1 -->
         <q-card style="width:610px" class="my-card open-card" flat bordered>
            <q-card-actions>
              <q-btn class="text-subtitle1 text-bolder" flat color="dark" label="Myspace Layouts The Missing Element" />


              <q-space />

              <q-btn
                color="grey"
                round
                flat
                dense
                :icon="expanded ? 'keyboard_arrow_up' : 'keyboard_arrow_down'"
                @click="expanded = !expanded"
              />
            </q-card-actions>

            <q-slide-transition>
              <div v-show="expanded">
                <q-separator />
                <q-card-section class="text-subitle2">
                  {{ lorem }}
                </q-card-section>
              </div>
            </q-slide-transition>
          </q-card>
<!-- ochiluvchi card2 -->

         <q-card style="width:610px" class="my-card open-card" flat bordered>
            <q-card-actions>
              <q-btn class="text-subtitle1 text-bolder" flat color="dark" label="Choosing The Best Audio Player Software For Your Computer" />


              <q-space />

              <q-btn
                color="grey"
                round
                flat
                dense
                :icon="expanded2 ? 'keyboard_arrow_up' : 'keyboard_arrow_down'"
                @click="expanded2 = !expanded2"
              />
            </q-card-actions>

            <q-slide-transition>
              <div v-show="expanded2">
                <q-separator />
                <q-card-section class="text-subitle2">
                  {{ lorem2 }}
                </q-card-section>
              </div>
            </q-slide-transition>
          </q-card>
          <!-- ochiluvchi card 3 -->

         <q-card style="width:610px" class="my-card open-card " flat bordered>
            <q-card-actions>
              <q-btn class="text-subtitle1 text-bolder" flat color="dark" label="How To Build A Pc" />


              <q-space />

              <q-btn
                color="grey"
                round
                flat
                dense
                :icon="expanded3 ? 'keyboard_arrow_up' : 'keyboard_arrow_down'"
                @click="expanded3 = !expanded3"
              />
            </q-card-actions>

            <q-slide-transition>
              <div v-show="expanded3">
                <q-separator />
                <q-card-section class="text-subitle2">
                  {{ lorem3 }}
                </q-card-section>
              </div>
            </q-slide-transition>
          </q-card>
      </div>
    </div>
    <div class="pej4">
    <q-card style="width:25%;" class="my-card">
      <div>
        <div>80$</div>
        <div>Manthly</div>
      </div>

        <q-card-section>
          <div class="text-h6">Basic Plan</div>
        </q-card-section>

        <q-card-section class="q-pt-none">
          <div class="fit row wrap">
            <q-icon name="done"></q-icon>
            <div>Unlimited Lift</div>
          </div>
          <div class="fit row wrap">
            <q-icon name="done"></q-icon>
            <div>Unlimited Lift</div>
          </div>
          <div class="fit row wrap">
            <q-icon name="done"></q-icon>
            <div>Unlimited Lift</div>
          </div>
          <div class="fit row wrap">
            <q-icon name="done"></q-icon>
            <div>Unlimited Lift</div>
          </div>
        </q-card-section>
    </q-card>
    </div>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  setup () {
    return {
      expanded: ref(false),
      lorem: 'Nam porttitor blandit accumsan. Ut vel dictum sem, a pretium dui. In malesuada enim in dolor euismod, id commodo mi consectetur. Curabitur at vestibulum nisi. Nullam vehicula nisi velit. Mauris turpis nisl, molestie ut ipsum et, suscipit vehicula odio. Vestibulum interdum vestibulum felis ac molestie. Praesent aliquet quam et libero dictum, vitae dignissim leo eleifend. In in turpis turpis. Quisque justo turpis, vestibulum non enim nec, tempor mollis mi. Sed vel tristique quam.',
      expanded2: ref(false),
     lorem2: 'Nam porttitor blandit accumsan. Ut vel dictum sem, a pretium dui. In malesuada enim in dolor euismod, id commodo mi consectetur. Curabitur at vestibulum nisi. Nullam vehicula nisi velit. Mauris turpis nisl, molestie ut ipsum et, suscipit vehicula odio. Vestibulum interdum vestibulum felis ac molestie. Praesent aliquet quam et libero dictum, vitae dignissim leo eleifend. In in turpis turpis. Quisque justo turpis, vestibulum non enim nec, tempor mollis mi. Sed vel tristique quam.',

     expanded3: ref(false),
     lorem3: 'Nam porttitor blandit accumsan. Ut vel dictum sem, a pretium dui. In malesuada enim in dolor euismod, id commodo mi consectetur. Curabitur at vestibulum nisi. Nullam vehicula nisi velit. Mauris turpis nisl, molestie ut ipsum et, suscipit vehicula odio. Vestibulum interdum vestibulum felis ac molestie. Praesent aliquet quam et libero dictum, vitae dignissim leo eleifend. In in turpis turpis. Quisque justo turpis, vestibulum non enim nec, tempor mollis mi. Sed vel tristique quam.'

    }
  }
}
</script>

<style scoped>
.card-hover{
  transition: 0.3s;
}
.card-hover:hover{
  background: #f56923;
  color: #fff;
  transition: 0.3s;
}
.border{
  border: 10px solid #f56923;
}
.open-card{
  margin-top: 25px;
  border-left: none;
  border-top: none;
  border-right: none;
}
</style>

