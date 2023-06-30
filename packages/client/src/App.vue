<template>
  <div bg-red bg-green>
    Set className as attribute at last not working
  </div>

  <!-- Set className as attribute at last, by without end tag works -->
  <div bg-gray />

  <!-- eslint-disable-next-line -->
  <div bg-red bg-blue         >
    Set className as attribute at last, add space between `attribute` and `>` works
  </div>

  <div bg-yellow>
    Set className as attribute at last, className is used in other place, it works
  </div>
  <div text-white bg-yellow rounded>
    2
  </div>

  <div class="bg-teal">
    Set className in class attribute, it works
  </div>
</template>
