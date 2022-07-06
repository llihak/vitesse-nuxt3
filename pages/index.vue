<template>
  <div>
    <Logos mb-6 />
    <Suspense>
      <PageView />
      <template #fallback>
        <div
          op50
          italic
        >
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>

    <div class="links grid">
      <nuxt-link to="/homepage">homepage</nuxt-link>
      <nuxt-link to="/powertools">powertools</nuxt-link>
      <nuxt-link to="/pugpage">pugpage</nuxt-link>
    </div>
    <!-- <InputEntry /> -->
  </div>
</template>
