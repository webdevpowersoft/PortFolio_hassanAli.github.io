<template>
  <q-page>
    <div class="container">
      <q-img class="gt-xs" src="~assets/back.png">
        <div class="absolute-center uper bg-transparent">
          <div class="text-weight-bold text-h3">PortFolio</div>
        </div>
      </q-img>
      <q-img class="lt-sm" src="~assets/back.png">
        <div class="absolute-center uper bg-transparent">
          <div class="text-weight-bold text-h5">PortFolio</div>
        </div>
      </q-img>
      <div class="font-header q-my-xl uper gt-xs">
        <div class="text-h3 text-weight-bold space">QUALITY <span
            :class="$q.dark.isActive ? 'text-secondary' : ''">WORK</span></div>
        <div class="text-h3 q-py-md text-weight-bold space">RECENTLY DONE <span
            :class="$q.dark.isActive ? 'text-secondary' : ''">PROJECT</span></div>
      </div>
      <div class="font-header q-my-md uper lt-sm">
        <div class="text-h5 text-weight-bold space">QUALITY <span
            :class="$q.dark.isActive ? 'text-secondary' : ''">WORK</span></div>
        <div class="text-h5 q-pt-md text-weight-bold space">RECENTLY DONE <span
            :class="$q.dark.isActive ? 'text-secondary' : ''">PROJECT</span></div>
      </div>

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

      <div class="row q-mt-md q-col-gutter-xl gt-xs">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div class="text-h5 text-weight-bold font-header" :class="$q.dark.isActive ? 'text-secondary' : ''"
            style="text-decoration: underline;">Zacson
            Gym
          </div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">
            This Website can provide different workout plan to manage user weight and fitness. This website can offer's
            Body Building, Muscle Gain and weight loss.
          </div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://zacson.netlify.app/#/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/zacsonp.png" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl lt-sm">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/zacsonp.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div class="text-h5 text-weight-bold font-header" :class="$q.dark.isActive ? 'text-secondary' : ''"
            style="text-decoration: underline;">Zacson
            Gym
          </div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'"> This Website can provide different workout plan
            to manage user weight and fitness. This website can offer's
            Body Building, Muscle Gain and weight loss.</div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://zacson.netlify.app/#/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/powersoftp.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">
            PowerSoft
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">Powersoft is a provider of IT-based solutions and
            services that enable organizations to achieve operational effectiveness, increase revenues, and improve
            stakeholder relations. By understanding our customers at critical business processes; we design, develop and
            deliver solutions that create competitive advantage through increased efficiency, speed to market, and
            improved quality.</div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://hassan-powersoft.netlify.app/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl gt-xs">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">Izpay
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">This website can provide the easiest facility of
            payment method in your hand. Izpay provide Simple and user friendly UI business tracking and credit & debit
            card. </div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://izpay.netlify.app/" target="_blank" icon="eva-external-link-outline" label="Visit Website" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/izpayp.png" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl lt-sm">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/izpayp.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">Izpay
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">This website can provide the easiest facility of
            payment method in your hand. Izpay provide Simple and user friendly UI business tracking and credit & debit
            card. </div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://izpay.netlify.app/" target="_blank" icon="eva-external-link-outline" label="Visit Website" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/digibitp.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">Digibit
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">Digibit can provide the currency exchange. if you
            want to buy bitcoin so you can easy buying a bitcoin in this website. </div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Vuejs 3</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">Quasar
            Framework</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://digibit.netlify.app/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl gt-xs">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">OnePage
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">Lorem ipsum dolor sit amet consectetur
            adipisicing
            elit.
            Voluptates<br /> aut architecto praesentium est pariatur sed perspiciatis molestiae<br /> cupiditate,
            tenetur beatae,
            atque quis, eum quae harum. Numquam<br /> eos culpa provident dignissimos!</div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Bootstrap 4</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Animation (AOS)</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://onepage404.netlify.app/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/onepagep.png" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl lt-sm">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/onepagep.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">OnePage
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">Lorem ipsum dolor sit amet consectetur
            adipisicing
            elit.
            Voluptates<br /> aut architecto praesentium est pariatur sed perspiciatis molestiae<br /> cupiditate,
            tenetur beatae,
            atque quis, eum quae harum. Numquam<br /> eos culpa provident dignissimos!</div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Bootstrap 4</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Animation (AOS)</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://onepage404.netlify.app/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
      </div>

      <div class="row q-mt-md q-col-gutter-xl">
        <div class="col-md-6 col-sm-12 col-xs-12">
          <q-img class="borderimg shadow-5" src="~assets/horrorp.png" />
        </div>
        <div class="col-md-6 col-sm-12 col-xs-12">
          <div style="text-decoration: underline;" class="text-h5 text-weight-bold font-header"
            :class="$q.dark.isActive ? 'text-secondary' : ''">Horror
            Template</div>
          <div class="text-subtitle1 q-mt-sm text-weight-light font-text"
            :class="$q.dark.isActive ? 'text-grey-4' : 'text-grey-6'">Lorem ipsum dolor sit amet consectetur
            adipisicing
            elit.
            Voluptates<br /> aut architecto praesentium est pariatur sed perspiciatis molestiae<br /> cupiditate,
            tenetur beatae,
            atque quis, eum quae harum. Numquam<br /> eos culpa provident dignissimos!</div>
          <div class="text-subtitle2 text-weight-light q-mt-md" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Tailwind CSS</div>
          <div class="text-subtitle2 text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'textgrey-9'">
            Animation (AOS)</div>
          <q-btn unelevated no-caps class="q-px-md q-py-sm q-mt-md btn2 text-subtitle1 text-weight-light"
            href="https://webhorror.netlify.app/" target="_blank" icon="eva-external-link-outline"
            label="Visit Website" />
        </div>
      </div>

    </div>
    <FooterComponent />
  </q-page>
</template>
<script>
import FooterComponent from 'src/components/FooterComponent.vue';
export default {
  components: { FooterComponent }
}
</script>
<style lang="scss">
.borderimg {
  border-radius: 5px;
}
</style>
