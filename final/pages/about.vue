<template>
<div>
        <AboutHeader />
<div>

<p>Fusce aliquet pede non pede. Suspendisse dapibus lorem pellentesque magna. Integer nulla. Donec blandit feugiat ligula. Donec hendrerit, felis et imperdiet euismod, purus ipsum pretium metus, in lacinia nulla nisl eget sapien.</p>
<p>Fusce aliquet pede non pede. Suspendisse dapibus lorem pellentesque magna. Integer nulla. Donec blandit feugiat ligula. Donec hendrerit, felis et imperdiet euismod, purus ipsum pretium metus, in lacinia nulla nisl eget sapien.</p>
<p>Fusce aliquet pede non pede. Suspendisse dapibus lorem pellentesque magna. Integer nulla. Donec blandit feugiat ligula. Donec hendrerit, felis et imperdiet euismod, purus ipsum pretium metus, in lacinia nulla nisl eget sapien.</p>

</div>

</div>
</template>

<script>
import Nav from '../components/Nav'
import AboutHeader from '../components/AboutHeader'

export default {
    components: {
        Nav,
        AboutHeader
    },
         head () {
    return {
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        { hid: 'description', name: 'About Us', content: 'lorem About Us page' }
      ]
    }
  }
}

</script>