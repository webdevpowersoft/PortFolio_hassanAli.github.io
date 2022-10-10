<template>
  <q-page>
    <div class="row gt-xs">
      <div class="col-md-6 col-sm-12 col-xs-12 q-mt-md flex flex-center q-pl-xl">
        <div class="font-header q-pl-xl uper">
          <div class="row">
            <div class="col-4">
              <div class="text-h3">Hello</div>
            </div>
            <div class="col-6 q-pt-sm">
              <div class="borderblog q-pt-lg" :class="$q.dark.isActive ? 'text-white' : 'text-black'"></div>
            </div>
          </div>
          <div class="text-h2 q-py-md">i am <span class="text-secondary"
              style="font-weight:1000; letter-spacing:6px">hassan ali</span></div>
          <div class="text-h5">Front-End DEVELOPER</div>
          <div class="q-mt-xl q-gutter-lg">
            <q-btn unelevated class="q-px-xl q-py-sm btn1 text-subtitle1 text-weight-bold" to="/contact"
              label="Hire Me" />
            <q-btn unelevated class="q-px-xl q-py-sm btn2 text-subtitle1 text-weight-bold" label="Get CV" />
          </div>
        </div>
      </div>
      <div class="col-md-6 col-sm-12 col-xs-12">
        <q-img src="~assets/has.jpg" />
      </div>
    </div>
    <div class="row lt-sm">
      <div class="col-md-6 col-sm-12 col-xs-12 q-mt-md flex flex-center q-pl-xl">
        <div class="font-header q-pl-md uper">
          <div class="row">
            <div class="col-4">
              <div class="text-h4 q-mr-md">Hello</div>
            </div>
            <div class="col-6 q-pt-sm">
              <div class="borderblogmobile q-pt-lg" :class="$q.dark.isActive ? 'text-white' : 'text-black'"></div>
            </div>
          </div>
          <div class="text-h3 text-weight-light q-py-md">i am <span class="text-secondary"
              style="font-weight:1000; letter-spacing:6px">hassan ali</span></div>
          <div class="text-h5">Front-End DEVELOPER</div>
          <div class="q-mt-xl q-mb-md q-gutter-lg">
            <q-btn unelevated class="q-px-lg q-py-sm btn1 text-subtitle1 text-weight-bold" to="/contact"
              label="Hire Me" />
            <q-btn unelevated class="q-px-lg q-py-sm btn2 text-subtitle1 text-weight-bold" label="Get CV" />
          </div>
        </div>
      </div>
      <div class="col-md-6 col-sm-12 col-xs-12">
        <q-img src="~assets/has.jpg" />
      </div>
    </div>
    <div class="row q-mb-xl gt-xs">
      <div class="col-md-6 col-sm-12 col-xs-12">
        <q-img src="~assets/hassan.jpg" />
      </div>
      <div class="col-md-6 col-sm-12 col-xs-12 q-mt-xl" :class="$q.dark.isActive ? 'text-white' : 'text-black'">
        <div class="font-header q-mt-xl q-pl-xl uper">
          <div class="text-h3 text-weight-bold space">let's</div>
          <div class="text-h3 q-py-md text-weight-bold space">Introduce about</div>
          <div class="text-h3 text-weight-bold space">myself</div>
        </div>
        <div class="q-pl-xl q-mt-lg text-subtitle1 font-text" :class="$q.dark.isActive ? 'text-white' : 'text-grey-8'">
          <div>Since beginning my journey as a freelance designer & Junior developer, I've done<br />
            consulted and collaborated with talented people to create<br /> digital products for both business and
            consumer
            use.</div>
          <div class="q-mt-lg">
            I'm quietly confident & working on improving myself one step at a time. I always follow<br /> the best
            practices
            to
            build real world applications.
          </div>
          <q-btn unelevated class="q-px-xl q-mt-md btn2 text-subtitle1 text-weight-bold q-py-sm" label="Download CV" />
        </div>
      </div>
    </div>
    <div class="row q-mb-xl lt-sm">
      <div class="col-md-6 col-sm-12 col-xs-12 q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'text-black'">
        <div class="font-header q-mt-xl q-pl-xl uper">
          <div class="text-h4 text-weight-bold space">let's</div>
          <div class="text-h4 q-py-md text-weight-bold space">Introduce about</div>
          <div class="text-h4 text-weight-bold space">myself</div>
        </div>
        <div class="q-pl-xl q-mt-lg text-subtitle1 font-text" :class="$q.dark.isActive ? 'text-white' : 'text-grey-8'">
          <div>Since beginning my journey as a freelance designer & Junior developer, I've done<br />
            consulted and collaborated with talented people to create<br /> digital products for both business and
            consumer
            use.</div>
          <div class="q-mt-lg">
            I'm quietly confident & working on improving myself one step at a time. I always follow<br /> the best
            practices
            to
            build real world applications.
          </div>
          <q-btn unelevated class="q-px-md q-mt-md btn2 text-subtitle1 text-weight-bold q-py-sm" label="Download CV" />
        </div>
      </div>
      <div class="col-md-6 col-sm-12 col-xs-12 q-mt-md">
        <q-img src="~assets/hassan.jpg" />
      </div>
    </div>
    <div class="row container q-my-xl bg-transparent">
      <div class="col-md-8 col-sm-12 col-xs-12 q-mt-xl">
        <div class="row">
          <div class="col-md-3 col-sm-4 col-xs-4 q-ma-md border q-py-md" :class="$q.dark.isActive ? 'text-white' : ''"
            style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <div class="text-subtitle1 text-weight-bold text-center">Weather App</div>
          </div>
          <div class="col-md-3 col-sm-4 col-xs-4 text-center border1 q-ma-md q-py-md border"
            :class="$q.dark.isActive ? '' : ''" style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <q-img width="100px" src="~assets/power.png" />
          </div>
          <div class="col-md-3 col-sm-4 col-xs-4 q-ma-md border1 border q-py-md"
            :class="$q.dark.isActive ? 'text-whtie' : ''" style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <div class="text-subtitle1 text-weight-bold text-center">Horror</div>
          </div>
          <div class="col-md-3 col-sm-4 col-xs-4 text-center border1 q-ma-md border q-py-md"
            :class="$q.dark.isActive ? '' : ''" style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <q-img width="100px" src="~assets/izpay.png" />
          </div>
          <div class="col-md-3 col-sm-4 col-xs-4 q-ma-md border1 border text-center q-py-md"
            :class="$q.dark.isActive ? 'text-whtie' : ''" style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <div class="text-h6 q-pt-sm text-weight-bold q-pl-sm">THE LUXURY</div>
            <div class="text-subtitle2 text-weight-bold q-pl-sm">Premium Theme</div>
          </div>
          <div class="col-md-3 col-sm-4 col-xs-4 q-ma-md border1 text-center border q-py-md"
            :class="$q.dark.isActive ? '' : ''" style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <div class="text-h6 text-weight-bold text-center q-pt-md">ZACSON</div>
          </div>
          <div class="col-md-3 col-sm-4 col-xs-4 text-center border1 q-ma-md border q-py-md"
            :class="$q.dark.isActive ? '' : ''" style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <q-img width="100px" src="~assets/advoza.png" />
          </div>
          <div class="col-md-3 col-sm-4 col-xs-4 q-ma-md border1 text-center border q-py-md"
            :class="$q.dark.isActive ? '' : ''" style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <q-img width="100px" src="~assets/digibit.png" />
          </div>
          <div class="col-md-3 col-sm-4 col-xs-4 text-center border1 q-ma-md border q-py-md"
            :class="$q.dark.isActive ? '' : ''" style="border-radius: 30% 70% 70% 30% / 30% 44% 56% 70%">
            <q-img width="100px" src="~assets/download.png" />
          </div>
        </div>
      </div>
      <div class="col-md-4 col-sm-12 col-xs-12 q-mt-xl">
        <div class="q-pl-sm shadow-7"
          style="border: 1px solid white; width: 300px; height:250px; background-color:#FAF8FF; padding-top:20px; border-radius: 20px; margin-top:30px;">
          <div class="client-info text-h1 text-weight-bolder text-secondary bg-transparent" style="z-index: 1">
            <div>02 <span class="text-caption">Years Experience Working</span></div>
            <div class="text-h6 q-pt-xl text-center text-weight-light">Call Us Now</div>
            <div class="text-h6 text-center q-pt-sm text-weight-bolder">
              <q-icon class="q-pr-sm" name="eva-phone-outline" />+923 04-5883005
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="text-center q-mt-xl bg-transparent">
      <div class="text-h4 uper font-header text-weight-bold" :class="$q.dark.isActive ? 'text-white' : 'text-black'">
        Service
        Offers</div>
    </div>
    <div class="row container q-col-gutter-md q-my-xl bg-transparent">
      <div class="col-md-3 col-sm-6 col-xs-12" v-for="item in card" :key="item">
        <q-card class="my-card q-pt-md full-height" :class="$q.dark.isActive ? 'bg-info text-white' : 'text-black'"
          style="border-radius:20px">
          <div class="text-center">
            <q-img width="80px" :src="item.src" />
          </div>
          <q-card-section>
            <div class="text-h6 text-center ">{{item.title}}</div>
            <div class="q-mt-md zoom font-text">
              <q-icon class="q-mr-md" size="sm" name="eva-award-outline" /> {{item.name1}}
            </div>
            <div class="q-mt-md zoom">
              <q-icon class="q-mr-md" size="sm" name="eva-award-outline" /> {{item.name2}}
            </div>
            <div class="q-mt-md zoom">
              <q-icon class="q-mr-md" size="sm" name="eva-award-outline" /> {{item.name3}}
            </div>
            <div class="q-mt-md zoom">
              <q-icon class="q-mr-md" size="sm" name="eva-award-outline" /> {{item.name4}}
            </div>
            <div class="q-mt-md zoom">
              <q-icon class="q-mr-md" size="sm" name="eva-award-outline" /> {{item.name5}}
            </div>
          </q-card-section>
        </q-card>
      </div>
    </div>
    <div class="text-center q-my-xl bg-transparent">
      <div class="text-h4 uper q-mt-xl text-weight-bold" :class="$q.dark.isActive ? 'text-white' : 'text-black'">My
        Recent Work
      </div>
    </div>
    <!-- ------------------------------------------------- -->
    <div class="container">
      <div class="row q-mt-md q-col-gutter-xl">

        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/advozap.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">Advoza
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">We're proud that our law firm offers top-notch
            legal services for nationwide affordable pricing! With us you'll never feel like the lawyers are just
            robbers in suits, besides, we win 98% of all cases</div>
          <div class="text-subtitle2 text-weight-light q-mt-sm" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://advoza.netlify.app/#/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl gt-xs">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">
            MultiKart
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">Provided a customer services portal for MultiKart
            where they manage direct deals, accounts, users, finance etc.</div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://multicart.netlify.app/#/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/multikartp.png" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl lt-sm">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/multikartp.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">
            MultiKart
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">Provided a customer services portal for MultiKart
            where they manage direct deals, accounts, users, finance etc.</div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://multicart.netlify.app/#/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/weatherp.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">Weather
            App</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">This application provide the current Weather
            information for all country's and city. If you can type any unknow city or country name then app cannot find
            the country or city weather.</div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Weather
            Api</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://quasarweather.netlify.app/#/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
      </div>
    </div>
    <!-- ------------------------------------------------- -->
    <FooterComponent />
  </q-page>
</template>

<script>
const card = [
  {
    src: require('assets/dev.png'),
    title: "WEB DEVELOPING",
    name1: "HTML/CSS",
    name2: "BootStrap",
    name3: "Tailwind CSS",
    name4: "Vue-js 3",
    name5: "Quasar FrameWork",
  },
  {
    src: require('assets/webdesign.png'),
    title: "WEB DESIGN",
    name1: "Landing Pages",
    name2: "User Flow",
    name3: "Mobile App Design",
    name4: "Product Design",
    name5: "Contact Design",
  },
  {
    src: require('assets/seo.png'),
    title: "SEO OPTIMIZE",
    name1: "White Hat",
    name2: "Black Hat",
    name3: "Grey Hat",
    name4: "On-Page",
    name5: "Negative",
  },
  {
    src: require('assets/ui.png'),
    title: "PHOTOGRAPHY",
    name1: "Product photography",
    name2: "Wedding photography",
    name3: "Baby photography",
    name4: "Fashion photography",
    name5: "Alnum photography",
  },
]
import { ref } from 'vue'
import FooterComponent from 'src/components/FooterComponent.vue';

export default {
  components: { FooterComponent },
  setup() {
    return {
      card
    };
  },
}
</script>

<style lang="scss">
.border:hover {
  background: linear-gradient(to right, #4458dc 0%, #854fee 100%);
  color: white;
}

.opacit {
  position: absolute;
}

.my-card:hover {
  box-shadow: 4px 4px 5px #854fee;
  transition: 0.5s;
}

.zoom:hover {
  transform: scale(1.1);
  transition: transform .5s ease;
}

.iconhover:hover {
  border: 2px solid #854fee;
  padding: 5px;
}
.borderimg{
  border-radius: 20px;
}
</style>

