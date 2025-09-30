<template>
  <div class="flex w-100% min-h-300px justify-center items-center gap-8px">
    <a href="/test/" class="underline">/test</a>
    <a href="/test/test" class="underline">/test/test</a>
    <a href="/test/test/test" class="underline">/test/test/test</a>
    <a href="/tag/123" class="underline">没有嵌套default布局</a>
  </div>
</template>

<route lang="yaml">
meta:
  layout: empty
</route>
