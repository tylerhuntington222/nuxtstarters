<template>
  <div>
    <h1 class="tracking-tight text-5xl">
      <ContentSlot :use="$slots.default" unwrap="h1" />
    </h1>
    <p class="max-w-lg text-md leading-8">
      <ContentSlot :use="$slots.description" />
    </p>
  </div>
</template>