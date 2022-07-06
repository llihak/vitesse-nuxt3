<template>
  <section>
    <div class="container mx-4 p-4 sm:mx-auto">
      <div class="Products grid gap-4 md:grid-cols-2">
        <div class="Data
                  | md:col-span-2 flex gap-4 flex-col md:flex-row
                  | pb-8 pr-4
                  | bg-blue-100
                  | shadow-md">
          <MediaObject reverse>
            <template v-slot:primary>
              <h3>Market Data and News</h3>
              <p>
                XENITH Real-Time Market Data and News gathers the essential news, data, analytics, commentary and
                insights
                you need in one place, so you can act quickly and confidently.
              </p>

              <p>
                Refinitiv DataLink is the daily market data feed that has been powering MetaStock D/C for decades. It
                provides clean, accurate market data you can count on.
              </p>

              <p>Both packages are provided by Refinitiv, a world leader in financial data and news.</p>
            </template>
            <template v-slot:secondary>
              <iframe
                class="aspect-video"
                width="auto"
                height="auto"
                src="https://www.youtube.com/embed/3dD3NEoiC2o"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              ></iframe>
            </template>

            <!-- <article slot="primary">
      </article> -->
          </MediaObject>
        </div>
        <div class="RT">
          <h3>Real-Time Traders</h3>
          <p>
            Specifically designed for day traders, MetaStock R/T powered by XENITH is among the world's more powerful
            private trader platforms. Highly customizable, MetaStock R/T contains powerful analysis tools to help you
            make
            informed decisions about what to buy and sell and when to execute to be as profitable as possible.
          </p>
        </div>
        <div class="DC">
          <h3>Position & Swing Traders</h3>
          <p>
            MetaStock D/C powered by Refinitiv DataLink is designed specifically for swing and position traders.
            Regardless of your trading experience, MetaStock D/C gives you professional level analysis tools that answer
            the questions: "What should I trade?" "How can I test my trading system?" and "When should I get in and out
            of
            a trade?"
          </p>
        </div>
      </div>

      <!--  -->
    </div>
  </section>


</template>

<script>
export default {

}
</script>

<style lang="postcss">
h3 {
  @apply text-xl font-bold
}


</style>