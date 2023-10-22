<template>
  <div class="flex flex-col justify-center items-center w-full h-full">
    <div class="flex flex-1 justify-center items-center">
      <h1 class="text-4xl font-bold">
        <slot name="title" />
      </h1>
    </div>
    <div class="grid grid-cols-3 place-items-center w-full py-16">
      <h3><slot name="subtitle" /></h3>
      <h3><slot name="date" /></h3>
      <h3><slot name="author" /></h3>
    </div>
  </div>
</template>
