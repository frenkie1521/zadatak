<template>
  <div class="q-pa-md q-gutter-sm">
    <q-banner inline-actions class="text-white bg-red">
      You have lost connection to the internet. This app is offline.
      <template v-slot:action>
        <q-btn flat color="white" label="Turn ON Wifi" />
      </template>
    </q-banner>
  </div>
</template>



<script>
export default {
  // name: 'PageName',
}
</script>
