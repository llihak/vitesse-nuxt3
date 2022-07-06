<template>
  <section>
    <div class="container mx-4 p-4 sm:mx-auto space-y-4">
      <h1 class="text-3xl">MetaStock Overview</h1>
      <MediaObject>
        <template v-slot:primary>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus odio tempora molestias et magnam
            ducimus earum! Et esse dolor sequi. Eum quas necessitatibus excepturi reprehenderit sequi, assumenda iste ut
            earum.</p>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus odio tempora molestias et magnam
            ducimus earum! Et esse dolor sequi. Eum quas necessitatibus excepturi reprehenderit sequi, assumenda iste ut
            earum.</p>
        </template>
        <template v-slot:secondary>
          <img
            src="https://www.metastock.com/images/w/MS-Montor-417px.png"
            alt=""
          >
        </template>

        <!-- <article slot="primary">
      </article> -->
      </MediaObject>
      <!-- <div class="Overview md:flex md:justify-between">
        <div class="blurb md:max-w-3/5 flex-1">blurb</div>
        <div class="media md:max-w-2/5">media</div>
      </div> -->
    </div>
  </section>
</template>

<script>
export default {
  name: 'Overview'
}
</script>

<style>
</style>