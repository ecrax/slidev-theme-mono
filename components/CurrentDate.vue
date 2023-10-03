<template>
  {{
    new Date().toLocaleDateString("de-de", {
      month: "2-digit",
      day: "2-digit",
      year: "numeric",
    })
  }}
</template>
