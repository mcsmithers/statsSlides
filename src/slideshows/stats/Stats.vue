<template lang='pug'>
#Stats
  .eg-slideshow
    slide
      h1 Trending Pictures
      h4 Lorem ipsum galaxy constellation voyager supernova curiosity jupiter orbit

    slide(enter='bounceInRight' leave='fadeOut')
      h3 Top Pictures
      p.
        Lorem ipsum apollo nebula pulsar pluto cassini eclipse nasa wormhole comet

    slide(enter='fadeIn')
      h3 Trending Headlines
      p.
        Lorem ipsum mercury orion meteor falcon transit moon andromeda planet astroid

    slide(enter='fadeIn')
      h3 Top Headlines
      p.
        Lorem ipsum sun quasar saturn rover trajectory hubble lightspeed cosmos star

    slide(enter='fadeIn')
      h3 Clicks, Conversions, and Impressions
      p.
        Lorem ipsum venus ranger neptune columbia earth pluto iss rocket interstellar
</template>

<script>
import eagle from 'eagle.js'
export default {
  mixins: [ eagle.slideshow ],
  infos: {
    // These infos appear on the home page, below the slideshow's thumbnail
    title: 'Tapstone',
    description: 'This shows awesome trends that we have going on',
    path: 'stats'
  }
}
</script>

<style lang='scss'>
@import url(https://fonts.googleapis.com/css?family=Raleway);
#Stats{
  .eg-slideshow{
    font-family: 'Raleway';
    background-color: #eef;
    .eg-slide{
      .eg-slide-content{
        width: 25em;
        max-width: 80%;
        margin: 0 auto;
      }
    }
  }
  .eg-slide-content{
    width: 25em;
    max-width: 80%;
    margin: 0 auto;
  }
}
</style>
