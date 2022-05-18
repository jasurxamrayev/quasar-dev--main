<template>
  <div>
    <div>
      <q-img  class="q-img" src="	https://xtrm.foxthemes.me/wp-content/uploads/2018/12/Group-1.png">
      <div class="  q-div row  justify-around items-start content-center">
        <br><br><br>
        <div>
          <div class="text-h6 text-weight-light">ABOUT US</div><br>
         <div style="font-size:75px" class=" text-weight-regular">Why You Should</div><br>
         <div  class="text-weight-bolder bg-black choose" >Choose Us</div>
        </div>
      </div>



     </q-img>
    </div>
    <div style="margin-top:500px"></div>
    <div class="row  justify-around  items-center content-center">
    <!-- card1 -->
      <q-card  class=" card-contianer my-card card-hover"><br>
        <div class="text-h2 text-weight-medium" style="margin-left:100px ">01.</div>
      <q-card-section>
        <div class="text-h6">We're Super Talented Team</div><br>
        <div class="text-subtitle1 text-center text-weight-light">Nam porttitor blandit <br> accumsan. Ut vel dictum sem, <br> a pretium dui. In malesuada.</div><br>
      </q-card-section><br>
    </q-card>
        <!-- card2 -->
      <q-card  class=" card-contianer my-card card-hover border"><br>
        <div class="text-h2 text-weight-medium" style="margin-left:100px ">02.</div>
      <q-card-section>
        <div class="text-h6">We Have Best Equipment</div><br>
        <div class="text-subtitle1 text-center text-weight-light">In hac habitasse platea <br> dictumst. Vivamus adipiscing <br>fermentum quam volutpat.</div><br>
      </q-card-section><br>
    </q-card>
        <!-- card1 -->
      <q-card  class=" card-contianer my-card card-hover"><br>
        <div class="text-h2 text-weight-medium" style="margin-left:100px ">03.</div>
      <q-card-section>
        <div class="text-h6">We’re The Best Company</div><br>

        <div class="text-subtitle1 text-center text-weight-light">Cras quis nulla commodo, <br>aliquam lectus sed, blandit<br> augue. Cras ullamcorper.</div><br>
      </q-card-section><br>
    </q-card>
        <!-- card1 -->
      <q-card class=" card-contianer my-card card-hover"><br>
        <div class="text-h2 text-weight-medium" style="margin-left:100px ">04.</div>
      <q-card-section>
        <div class="text-h6">We Have Coffee and Cookies</div><br>
        <div class="text-subtitle1 text-center text-weight-light">We Have Coffee and Cookies <br> fringilla rutrum. Aenean <br> sollicitudin, erat a elem.</div><br>
      </q-card-section><br>
    </q-card>
    </div>
    <div style="margin-top: 100px;"></div>
    <div class="fit row wrap justify-around items-center content-center">
        <img style="width:600px;" src="https://xtrm.foxthemes.me/wp-content/uploads/2018/12/bitmap.png" />
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

              <q-btn color="grey" round flat dens :icon="expanded2 ? 'keyboard_arrow_up' : 'keyboard_arrow_down'" @click="expanded2 = !expanded2"/>
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

              <q-btn color="grey" round flat dens :icon="expanded2 ? 'keyboard_arrow_up' : 'keyboard_arrow_down'" @click="expanded2 = !expanded2" />
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

              <q-btn color="grey"  round flat dense :icon="expanded3 ? 'keyboard_arrow_up' : 'keyboard_arrow_down'" @click="expanded3 = !expanded3" />
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
    </div><br>
    <div class="q-ml-xl q-mt-xl">
       <div class="text-subtitle2">BEST PRICING</div><br>
       <div class="text-h4 ">Why Pay <span style="color: white;background: black;" >More?</span></div>
    </div>

  <div style="margin-top:100px" class="fit row wrap justify-evenly items-start content-start">
    <q-card   class=" card-border my-card"><br>
      <div  class="row justify-between items-center content-center">
        <div style="margin-left:10px" class="text-h3">80$</div>
        <div class=" monthly text-h6">Manthly</div>
      </div>

        <q-card-section >
          <div class="text-h6">Basic Plan</div>
        </q-card-section>
        <div class="chiziq"></div><br>
        <q-card-section class="q-pt-none">
          <div class="row items-center content-center">
            <q-icon name="done" class="yellow-icon"></q-icon>
            <div class="icon">Unlimited Lift</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done" class="text" ></q-icon>
            <div class="icon">Instructor’s Help</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done" class="text"></q-icon>
            <div class="icon">Free Hugs</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done" class="text"></q-icon>
            <div class="icon">Coffee & Cookies</div>
          </div><br>
        </q-card-section>
        <q-btn class="hover-btn btn" >ORDER NEW</q-btn><br><br><br>
     </q-card>
         <!-- ikkinchi card -->
         <q-card  class=" border-color my-card">

         <br>

      <div  class="row justify-between items-center content-center">
        <div style="margin-left:10px" class="text-h3">100$</div>
        <div  class=" mantly text-h6">Manthly</div>
      </div>

        <q-card-section >
          <div class="text-h6">Stadard Plan</div>
        </q-card-section>
        <div class="chiziq"></div><br>
        <q-card-section class="q-pt-none">
          <div class="row items-center content-center">
            <q-icon name="done" class="yellow-icon"></q-icon>
            <div class="icon">Unlimited Lift</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done"  class="icon-color"></q-icon>
            <div class="icon">Instructor’s Help</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done"  class="yellow-icon"></q-icon>
            <div class="icon">Free Hugs</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done" class="text"></q-icon>
            <div class="icon">Coffee & Cookies</div>
          </div><br>
        </q-card-section>
        <q-btn class="hover-btn" style="width:170px;height:50px;margin-left: 30px;background:#f56923">ORDER NEW</q-btn><br><br><br>
     </q-card>


     <!-- uchinchi card -->
         <q-card class="my-card card-border"><br>
      <div  class="row justify-between items-center content-center">
        <div style="margin-left:10px" class="text-h3">120$</div>
        <div class="text-h6 manthly">Manthly</div>
      </div>

        <q-card-section >
          <div class="text-h6">Premium Plan</div>
        </q-card-section>
        <div class="chiziq"></div><br>
        <q-card-section class="q-pt-none">
          <div class="row items-center content-center">
            <q-icon name="done" class="yellow-icon"></q-icon>
            <div class="icon">Unlimited Lift</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done" class="icon-color"></q-icon>
            <div class="text">Instructor’s Help</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done"  class="icon-color"></q-icon>
            <div class="icon">Free Hugs</div>
          </div><br>
          <div class="row items-center content-center">
            <q-icon name="done" class="icon-color"></q-icon>
            <div class="icon">Coffee & Cookies</div>
          </div><br>
        </q-card-section>
        <q-btn class="hover-btn btn">ORDER NEW</q-btn><br><br><br>
     </q-card>
    </div>
    <div class="contianer">
      <div class="q-ml-xl q-mt-xl m" >
          <div class="text-h5" style="color:white" >newsletter</div><br>
        <div class="text-subtitle1" style="color: #444;">A well-executed brand strategy affects all aspects of a business and is <br> connected to consumer needs & emotions.</div><br>
        <div style="width:400px;">
          <q-input style="background:white;"  type="text" placeholder="Your-emil" name="Send" />
        </div><br><br>
      <div class="text-subtitle1 white">© XTRM. <span class="mini-text text-subtitle1">All Right Reserved 2019.</span></div>
      </div>
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
.q-img{
  position:absolute;
   top:0%;
   height:500px;
}
.q-div{
 width:50%;
 height:100%;
 background: #f569238d;
}
.choose{
  font-size:60px;
  width:310px;
  padding-left:5px
}
.card-contianer{
width: 23%;
height: 290px;
}
.card-border{
  width:25%;
  border:3px solid rgba(169, 163, 163, 0.174);
}
.chiziq{
  height: 0.5px;
   background:#999;
   width:85%;
   margin-left:5%;
   margin-bottom:2px
}
.yellow-icon{
  color:#f56923;
  font-size:18px;
  font-weight: 900;
}
.card-hover{
  transition: 0.3s;
}
.monthly{
  margin-right:17px;
  background:#ebebeb;
}
.icon{
  font-size:18px;
  margin-left: 10px;
}
.text{
  font-size:18px;
  font-weight: 900;
}
.btn{
  width:170px;
  height:50px;
  margin-left: 30px;
}
.border-color{
  width:25%;
   border: 5px solid #f56923;
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
.hover-btn{
  transition: 0.5s;
}
.hover-btn:hover{
  color: #fff;
  background: black;
  transition: 0.5s;
}
.contianer{
  width: 100%;
  height: 53vh;
  background: #222;
  margin-top:100px;
}

.m{
  padding-left: 50px;
padding-top: 40px;
}

.white{
  color:white;
}
.zor{
  color:#fff;
  background: #222;
}
.mini-text{
  color: #444;
}

.icon-color{
  color: #f56923;
  font-size:18px;
  font-weight: 900
}
</style>

