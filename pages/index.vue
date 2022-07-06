<template>
  <div>
    <Logos mb-6 />
    <Suspense>
      <PageView />
      <template #fallback>
        <div op50 italic>
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>
    <nuxt-link to="/powertools">powertools</nuxt-link>
    <InputEntry />
  </div>
</template>
