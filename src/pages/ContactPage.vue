<template>
  <q-page>
    <div class="container gt-xs">
      <q-img src="~assets/back.png">
        <div class="absolute-center uper bg-transparent">
          <div class="text-weight-bold text-h3">Contact Us</div>
          <div class="text-center q-mt-md">
            <q-btn flat label="Home" to="/" />
            --
            <q-btn flat label="PortFolio" to="/portfolio" />
          </div>
        </div>
      </q-img>
      <div style="margin-top: 100px">
        <div class="row">
          <div class="col-8">
            <q-input class="q-mb-md" rounded filled v-model="text" type="textarea" placeholder="Enter Your Message" />
            <div class="row q-mb-md q-col-gutter-md">
              <div class="col-6">
                <q-input rounded filled outlined v-model="text" type="text" placeholder="Enter your Name" />
              </div>
              <div class="col-6">
                <q-input rounded filled v-model="text" type="email" placeholder="Enter your Email" />
              </div>
            </div>
            <q-input rounded filled v-model="text" type="text" placeholder="Enter Your Subject" />
            <div class="q-my-md">
              <q-btn unelevated class="q-px-xl q-mt-md btn2 text-subtitle1 text-weight-bold q-py-sm" label="Send" />
            </div>
          </div>
          <div class="col-4">
            <q-list v-for="item in add" :key="item">
              <q-item>
                <q-item-section avatar>
                  <q-icon class="bg-info q-pa-md" color="white" :name="item.icon" style="border-radius: 10px;" />
                </q-item-section>
                <q-item-section>
                  <q-item-label class="text-h6 text-weight-bold"
                    :class="$q.dark.isActive ? 'text-secondary' : 'text-black'">{{item.title}}</q-item-label>
                  <q-item-label class="text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'text-grey-8'">
                    {{item.name}}</q-item-label>
                </q-item-section>
              </q-item>
            </q-list>
          </div>
        </div>
      </div>
    </div>
    <div class="container lt-sm">
      <q-img src="~assets/back.png">
        <div class="absolute-center uper q-mt-xs bg-transparent">
          <div class="text-weight-bold text-h5">Contact <br /></div>
          <div class="text-center text-weight-bold text-h5">US</div>
        </div>
      </q-img>
      <div style="margin-top: 40px">
        <div class="row">
          <div class="col-md-8 col-sm-12 col-xs-12">
            <q-input class="q-mb-md" rounded filled v-model="text" type="textarea" placeholder="Enter Your Message" />
            <div class="row q-mb-md q-col-gutter-md">
              <div class="col-6">
                <q-input rounded filled outlined v-model="text" type="text" placeholder="Enter your Name" />
              </div>
              <div class="col-6">
                <q-input rounded filled v-model="text" type="email" placeholder="Enter your Email" />
              </div>
            </div>
            <q-input rounded filled v-model="text" type="text" placeholder="Enter Your Subject" />
            <div class="q-my-md">
              <q-btn unelevated class="q-px-xl q-mt-md btn2 text-subtitle1 text-weight-bold q-py-sm" label="Send" />
            </div>
          </div>
          <div class="col-md-4 col-sm-12 col-xs-12">
            <q-list v-for="item in add" :key="item">
              <q-item>
                <q-item-section avatar>
                  <q-icon class="bg-info q-pa-md" color="white" :name="item.icon" style="border-radius: 10px;" />
                </q-item-section>
                <q-item-section>
                  <q-item-label class="text-subtitle1 text-weight-bold"
                    :class="$q.dark.isActive ? 'text-secondary' : 'text-black'">{{item.title}}</q-item-label>
                  <q-item-label class="text-weight-light" :class="$q.dark.isActive ? 'text-white' : 'text-grey-8'">
                    {{item.name}}</q-item-label>
                </q-item-section>
              </q-item>
            </q-list>
          </div>
        </div>
      </div>
    </div>
    <FooterComponent />
  </q-page>
</template>
<script>
import FooterComponent from 'src/components/FooterComponent.vue';
const add = [
  {
    icon: "eva-home-outline",
    title: "Muridke, Pakistan",
    name: "Near Hassan Marriage Hall",
  },
  {
    icon: "eva-phone-outline",
    title: "+923 04-5883005",
    name: "Mon to Fri 9am to 6pm",
  },
  {
    icon: "eva-email-outline",
    title: "hassanali4u2003@gmail.com",
    name: "Send us your query anytime!",
  },
]
export default {
  setup() {
    return {
      add,
    };
  },
  components: { FooterComponent }
}
</script>
<style lang="">

</style>
