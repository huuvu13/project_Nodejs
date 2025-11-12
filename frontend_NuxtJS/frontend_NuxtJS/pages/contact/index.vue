<template>
  <div class=" flex flex-col">
    <header class="banner_single mb-10">
      <div class="flex justify-center absolute items-center w-full flex-col">
        <h2 class="text-white text-3xl font-semibold">
          Contact Us
        </h2>
        <span class="text-orange text-lg">
          <nuxt-link tag="span" class="text-white text-lg cursor-pointer" to="/">
            Trang chủ
          </nuxt-link>
          / Liên hệ
        </span>
      </div>
    </header>
    <div class="sm:px-14  px-8 mt-16 mb-20 flex flex-col space-y-7">
      <div class="space-y-4">
        <h1 class="text-3xl font-medium">
          Thông tin liên hệ
        </h1>
        <p class="text-[1rem]">
          Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque,
          auctor sit amet aliquam vel, ullamcorper sit amet ligula. Vestibulum ac diam sit amet quam vehicula elementum
          sed sit amet dui. Proin eget tortor risus. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.
          Curabitur non nulla sit amet nisl tempus convallis quis ac lectus. Vivamus magna justo, lacinia eget consectetur sed,
          convallis at tellus. Cras ultricies ligula sed magna dictum porta. Proin eget tortor risus. Curabitur arcu erat,
          accumsan id imperdiet et, porttitor at sem.
        </p>
      </div>
      <div class="grid sm:grid-cols-3 grid-cols-1">
        <div class="col-span-1 flex flex-col space-y-2 text-[1rem] text-black gap-7 sm:mb-0 mb-2">
          <div class="flex items-center">
            <i class="fa-solid fa-location-dot mr-4" />
            <p> 324, Hoàng Quốc Việt, Hà Nội, Việt Nam</p>
          </div>
          <div class="flex  items-center">
            <i class="fa-solid fa-phone mr-4" />
            <div>
              <p>+ 84 359 933 921    </p>
              <p>+ 84 888 686 868    </p>
            </div>
          </div>
          <div class="flex  items-center">
            <i class="fa-solid fa-envelope mr-4" />
            <div>
              <p>tumynet2000@gmail.com  </p>
              <p>Aelgbg@gmail.com</p>
            </div>
          </div>
        </div>
        <div class="col-span-2">
          <contact-form />
        </div>
      </div>
      <div>
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3723.6439090418726!2d105.78291137508137!3d21.046929480606924!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3135abb158a2305d%3A0x5c357d21c785ea3d!2zVHLGsOG7nW5nIMSQ4bqhaSBo4buNYyDEkGnhu4duIEzhu7Fj!5e0!3m2!1svi!2sus!4v1762939688857!5m2!1svi!2sus"
          style="border:0;"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          class="w-full h-[60vh]"
        />
      </div>
    </div>
  </div>
</template>

<script>
import ContactForm from '@/components/contact/ContactForm.vue'
export default {
  components: {
    ContactForm
  }
}
</script>

<style lang="scss">
    .banner_single{
      background-image: url('@/static/banner/banner_single.png');
      position: relative;
      background-repeat: no-repeat;
      background-size: cover cover;
      padding: 100px 0 140px 0;
      width: 100%;
    }
  </style>
