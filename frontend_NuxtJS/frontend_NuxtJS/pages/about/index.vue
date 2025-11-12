<template>
  <div class="flex flex-col">
    <header class="banner_single mb-10">
      <div class="flex justify-center absolute items-center w-full flex-col">
        <h2 class="text-white text-3xl font-semibold">
          Về chúng tôi
        </h2>
        <span class="text-orange text-lg">
          <nuxt-link tag="span" class="text-white text-lg cursor-pointer" to="/">
            Trang chủ
          </nuxt-link>
          / Về chúng tôi
        </span>
      </div>
    </header>
    <div class="my-20 grid sm:grid-cols-2 grid-cols-1 sm:px-14 px-8 gap-6">
      <div>
        <img src="@/static/imgAbout.jpg" alt="photo">
      </div>
      <div class="space-y-2">
        <h2 class="text-3xl text-black font-medium">
          ANDSHOP STORE
        </h2>
        <p class="text-2xl text-black font-normal">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequa.
        </p>
        <p class="text-lg  font-normal">
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>
        <p class="text-lg  font-normal">
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
        </p>
      </div>
    </div>

    <div class="bg-[#f6f6f6] flex flex-col mb-20 pt-20 pb-20 sm:px-14 px-8">
      <div class="flex justify-center flex-col w-full items-center space-y-2">
        <h2 class="text-3xl text-black font-medium">
          EXPERT TEAM
        </h2>
        <p class="text-lg  font-normal">
          Mauris luctus nisi sapien tristique dignissim ornare
        </p>
      </div>
      <div class="flex mt-5 justify-center mx-auto sm:space-x-8  space-x-4">
        <div class="w-36 flex justify-end">
          <img src="htts://scontent.fhan2-1.fna.fbcdn.net/v/t1.6435-9/52591436_720237038377890_7401268411050754048_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=QIeqF_zGBz4AX90yvQR&_nc_ht=scontent.fhan2-1.fna&oh=00_AfBCkIvM3eMBJXR0-_mt91k2OIW-nfa1-Ghmkv04QYnLvg&oe=63860FED" alt="photo">
        </div>
        <div class="flex flex-col space-y-2">
          <p class="text-2xl text-black font-medium">
            Admin
          </p>
          <p class="text-lg">
            Be the first to establish a company
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

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
