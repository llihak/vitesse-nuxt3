<template>
  <section>
    <div class="container mx-4 sm:mx-auto">
      <header class="mb-8 pt-8 text-center ">
        <h1 class="text-2xl font-bold">Metastock Power Tools</h1>
        <p class="text-xl">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Possimus repellendus tempora quam
          ut unde. Inventore, veritatis eos officia velit voluptatibus facilis est itaque commodi veniam expedita
          dolorem fugiat fugit ex?</p>
      </header>
      <div class="PowerTools grid gap-4 md:grid-cols-2">
        <div class="powertool
                  | gap-4 sm:flex md:flex-col lg:flex-row
                  | px-4 pb-8 mb-8
                  | shadow-md
                  | text-base">
          <div class="media self-center">
            <img
              src="https://www.metastock.com/images/i/TRADER-EOD.png"
              alt=""
              class="sm:max-w-[150px]"
            />
          </div>
          <div class="powertool-blurb
                    | flex flex-col sm:flex-1 justify-between
                    | space-y-4
                    | font-base 
                    ">
            <h2 class="self-center text-xl">about this powertool</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat natus sapiente voluptatibus porro sit
              eveniet facere officia dignissimos,sapiente voluptatibus porro sit eveniet facere officia dignissimos,
              doloremque, ea dolore a adipisci neque incidunt! Odio perspiciatis aut
              eum tenetur!</p>
            <button class="button bg-blue-500  ">Watch the video</button>
          </div>
        </div>
        <div class="powertool
                  | gap-4 sm:flex md:flex-col lg:flex-row
                  | px-4 pb-8 mb-8
                  | shadow-md
                  | text-base">
          <div class="media self-center">
            <img
              src="https://www.metastock.com/images/i/TRADER-EOD.png"
              alt=""
              class="sm:max-w-[150px] "
            />
          </div>
          <div class="powertool-blurb
                    | flex flex-col sm:flex-1 justify-between
                    | space-y-4
                    | font-base 
                    ">
            <h2 class="self-center text-xl">about this powertool</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat natus sapiente voluptatibus porro sit
              eveniet facere officia dignissimos, doloremque, ea dolore a adipisci neque incidunt! Odio perspiciatis aut
              eum tenetur!</p>
            <button class="button bg-blue-500  ">Watch the video</button>
          </div>
        </div>
        <div class="powertool
                  | gap-4 sm:flex md:flex-col lg:flex-row
                  | px-4 pb-8 mb-8
                  | shadow-md
                  | text-base">
          <div class="media self-center">
            <img
              src="https://www.metastock.com/images/i/TRADER-EOD.png"
              alt=""
              class="sm:max-w-[150px]"
            />
          </div>
          <div class="powertool-blurb
                    | flex flex-col sm:flex-1 justify-between
                    | space-y-4
                    | font-base 
                    ">
            <h2 class="self-center text-xl">about this powertool</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat natus sapiente voluptatibus porro sit
              eveniet facere officia dignissimos, doloremque, ea dolore a adipisci neque incidunt! Odio perspiciatis aut
              eum tenetur!</p>
            <button class="button bg-blue-500  ">Watch the video</button>
          </div>
        </div>
        <div class="powertool
                  | gap-4 sm:flex md:flex-col lg:flex-row
                  | px-4 pb-8 mb-8
                  | shadow-md
                  | text-base">
          <div class="media self-center">
            <img
              src="https://www.metastock.com/images/i/TRADER-EOD.png"
              alt=""
              class="sm:max-w-[150px]"
            />
          </div>
          <div class="powertool-blurb
                    | flex flex-col sm:flex-1 justify-between
                    | space-y-4
                    | font-base 
                    ">
            <h2 class="self-center text-xl">about this powertool</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat natus sapiente voluptatibus porro sit
              eveniet facere officia dignissimos, doloremque, ea dolore a adipisci neque incidunt! Odio perspiciatis aut
              eum tenetur!</p>
            <button class="button bg-blue-500  ">Watch the video</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  definePageMeta({
    layout: 'mylayout'
  })
export default {
  name: 'PowerToolsPage'
}
</script>
<style>
 
  .button  {
    @apply  mx-auto text-white text-center px-4 py-1 rouned-md shadow-lg;
  }

</style>