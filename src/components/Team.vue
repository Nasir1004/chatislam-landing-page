<template>
  <div class="tw-mt-12 sm:tw-mt-24">
    <div>
      <div class="title tw-text-2xl sm:tw-text-3xl tw-text-center">
        Scholars
      </div>
      <div class="row tw-justify-center tw-mt-8">
        <div
          class="tw-w-64 tw-h-56 card tw-border-2 tw-mx-2 tw-border-primary-bg-color tw-rounded-2xl tw-mt-4 sm:tw-mt-0"
        >
          <div class="row tw-justify-center">
            <q-img
              src="~assets/img/nasir.png"
              class="tw-w-24 tw-h-24 tw-rounded-full tw-mt-10"
            />
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Nasir Ibrahim Abba
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Co-Founder Eduvacity & Founder ChatIslam
          </div>
        </div>
        <div
          class="tw-w-64 tw-h-56 card tw-border-2 tw-mx-2 tw-border-primary-bg-color tw-rounded-2xl tw-mt-4 sm:tw-mt-0"
        >
          <div class="row tw-justify-center">
            <q-img
              src="~assets/img/bashir.png"
              class="tw-w-24 tw-h-24 tw-rounded-full tw-mt-10"
            />
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Bashir Isah Dodo PhD
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Co-Founder ChatIslam & Ai Resercher
          </div>
        </div>
        <div
          class="tw-w-64 tw-h-56 card tw-border-2 tw-mx-2 tw-border-primary-bg-color tw-rounded-2xl tw-mt-4 sm:tw-mt-0"
        >
          <div class="row tw-justify-center">
            <q-img
              src="~assets/img/hajarah.jpg"
              class="tw-w-24 tw-h-24 tw-rounded-full tw-mt-10"
            />
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Hajar Mousannif
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Associate Professor | AI, ML & TinyML Advocate
          </div>
        </div>
        <div
          class="tw-w-64 tw-h-56 card tw-border-2 tw-mx-2 tw-border-primary-bg-color tw-rounded-2xl tw-mt-4 sm:tw-mt-0"
        >
          <div class="row tw-justify-center">
            <q-img
              src="~assets/img/najib.jpg"
              class="tw-w-24 tw-h-24 tw-rounded-full tw-mt-10"
            />
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Najeeb G. Abdulhamid PhD
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Resercher @Microsoft
          </div>
        </div>
      </div>
      <div class="row tw-justify-center sm:tw-mt-8">
        <div
          class="tw-w-64 tw-h-56 card tw-border-2 tw-mx-2 tw-border-primary-bg-color tw-rounded-2xl tw-mt-4 sm:tw-mt-0"
        >
          <div class="row tw-justify-center">
            <q-img
              src="~assets/img/yusuf.jpg"
              class="tw-w-24 tw-h-24 tw-rounded-full tw-mt-10"
            />
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Yusuf Abubakar PhD
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Ai Resercher Ahmadu Bello University
          </div>
        </div>
        <div
          class="tw-w-64 tw-h-56 card tw-border-2 tw-mx-2 tw-border-primary-bg-color tw-rounded-2xl tw-mt-4 sm:tw-mt-0"
        >
          <div class="row tw-justify-center">
            <q-img
              src="~assets/img/mustapha.jpg"
              class="tw-w-24 tw-h-24 tw-rounded-full tw-mt-10"
            />
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Mustapha Jimoh
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Ai Resercher & machine learning engineer
          </div>
        </div>
        <div
          class="tw-w-64 tw-h-56 card tw-border-2 tw-mx-2 tw-border-primary-bg-color tw-rounded-2xl tw-mt-4 sm:tw-mt-0"
        >
          <div class="row tw-justify-center">
            <q-img
              src="~assets/img/nasir.png"
              class="tw-w-24 tw-h-24 tw-rounded-full tw-mt-10"
            />
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Dahir Muhammad Dahir
          </div>
        </div>
        <div
          class="tw-w-64 tw-h-56 card tw-border-2 tw-mx-2 tw-border-primary-bg-color tw-rounded-2xl tw-mt-4 sm:tw-mt-0"
        >
          <div class="row tw-justify-center">
            <q-img
              src="~assets/img/nasir.png"
              class="tw-w-24 tw-h-24 tw-rounded-full tw-mt-10"
            />
          </div>
          <div class="tw-text-center tw-font-medium tw-text-base tw-pt-2">
            Nasir Ibrahim Abba
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  setup() {},
});
</script>

<style scoped>
.title {
  background: linear-gradient(to right, #fd8a45 0%, #0b1e4f 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
.card:hover {
  transform: translateY(-5%);
}
.card {
  transition: all ease 900ms;
}
</style>
