<template>
  <div id="nml-tool">
    <heading class="mb-6">{{ __("nml_media_library") }}</heading>

    <nmlAction />

    <nmlSearch />

    <nmlItems />

    <nmlLoader />

    <transition name="fade">
      <Popup v-if="popup" />
    </transition>

  </div>
</template>

<script src="./script.js"></script>
