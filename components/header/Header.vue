<template lang="pug">
  header.header
    .wrapper(@click='toggleNav(true)' role="banner")
      nuxt-link.logo(to="/")
        span.visually-hidden Vue mastery
        .vue-mastery-logo

        svg(viewbox='0 0 480 84')
          style(type='text/css').
            .st{fill:#36495E;}
            .st0{fill:#36495E;}
            .st1{fill:url(#SVGID_1_);}
            .st2{fill:url(#SVGID_2_);}
            .st3{fill:url(#SVGID_3_);}
            .st4{fill:url(#SVGID_4_);}
            .st5{fill:url(#SVGID_5_);}
          g
            g
              g
                polygon.st(points='36.5,83.1 47.5,64.1 58.5,83.1 76,83.1 47.5,33.8 19,83.1')
                lineargradient#SVGID_1_(gradientunits='userSpaceOnUse' x1='61.7617' y1='83.1439' x2='61.7617' y2='33.7712')
                  stop(offset='0' style='stop-color:#36495E')
                  stop(offset='1' style='stop-color:#0A1C33')
                polygon.st1(points='47.5,33.8 47.5,64.1 58.5,83.1 76,83.1')
                g
                  lineargradient#SVGID_2_(gradientunits='userSpaceOnUse' x1='94.9561' y1='83.1439' x2='94.9561' y2='83.1324')
                    stop(offset='0' style='stop-color:#88C96E')
                    stop(offset='1' style='stop-color:#86D859')
                  polygon.st2(points='95,83.1 95,83.1 94.9,83.1')
              g
                polygon.st(points='115.5,83.1 104.5,64.1 93.5,83.1 76,83.1 104.5,33.8 133,83.1')
                g
                  lineargradient#SVGID_3_(gradientunits='userSpaceOnUse' x1='151.9669' y1='83.1439' x2='151.9669' y2='83.1324')
                    stop(offset='0' style='stop-color:#88C96E')
                    stop(offset='1' style='stop-color:#86D859')
                  polygon.st3(points='152,83.1 152,83.1 151.9,83.1')
                lineargradient#SVGID_4_(gradientunits='userSpaceOnUse' x1='3870.532' y1='83.1439' x2='3870.532' y2='33.7712' gradienttransform='matrix(-1 0 0 1 3960.7991 0)')
                  stop(offset='0' style='stop-color:#36495E')
                  stop(offset='1' style='stop-color:#0A1C33')
                polygon.st4(points='104.5,33.8 104.5,64.1 93.5,83.1 76,83.1')
              lineargradient#SVGID_5_(gradientunits='userSpaceOnUse' x1='76.0144' y1='83.1439' x2='76.0144' y2='0.8561')
                stop(offset='0.2' style='stop-color:#41B782')
                stop(offset='1' style='stop-color:#86D169')
              polygon.st5(points='104.5,0.9 76,50.2 76,50.2 76,50.2 47.5,0.9 0,83.1 19,83.1 47.5,33.8 76,83.1 76,83.1 76,83.1 \
              104.5,33.8 133,83.1 152,83.1')
            g
              path.st0(d='M178.9,35.6h10.8L178,71.2h-11.3l-11.6-35.6h10.8l4.8,18c1,4,1.6,6.8,1.7,8.4c0.1-1.1,0.3-2.6,0.7-4.3\
              c0.3-1.7,0.6-3,0.9-4L178.9,35.6z')
              path.st0(d='M212.6,71.2l-1.2-3.4h-0.6c-0.8,1.3-1.9,2.2-3.3,2.9c-1.4,0.7-3.1,1-5,1c-3,0-5.4-0.9-7.1-2.6\
              c-1.7-1.8-2.5-4.2-2.5-7.5v-18h9.5v15.1c0,1.8,0.3,3.2,0.8,4.1c0.5,0.9,1.3,1.4,2.5,1.4c1.6,0,2.8-0.6,3.5-1.9\
              c0.7-1.3,1-3.5,1-6.5V43.6h9.5v27.6H212.6z')
              path.st0(d='M239.6,71.7c-4.6,0-8.2-1.2-10.7-3.7c-2.5-2.4-3.8-5.9-3.8-10.4c0-4.7,1.2-8.2,3.5-10.7\
              c2.4-2.5,5.7-3.7,10.1-3.7c4.2,0,7.4,1.1,9.6,3.2c2.3,2.2,3.4,5.3,3.4,9.4V60h-17c0.1,1.5,0.6,2.7,1.7,3.6\
              c1.1,0.9,2.5,1.3,4.3,1.3c1.7,0,3.2-0.2,4.6-0.5s2.9-0.9,4.6-1.6v6.8c-1.5,0.8-3,1.3-4.6,1.6C243.7,71.5,241.8,71.7,239.6,71.7z\
              M239.1,49.6c-1.1,0-2.1,0.4-2.8,1.1c-0.8,0.7-1.2,1.8-1.3,3.3h8.2c0-1.3-0.4-2.4-1.1-3.2S240.3,49.6,239.1,49.6z')
              path.st0(d='M286.1,71.2l-7.3-25.6h-0.2c0.3,4.4,0.5,7.8,0.5,10.2v15.4h-8.5V35.6h12.8l7.4,25.2h0.2l7.3-25.2h12.8v35.6\
              h-8.8V55.6c0-0.8,0-1.7,0-2.7c0-1,0.1-3.4,0.3-7.3h-0.2l-7.2,25.6H286.1z')
              path.st0(d='M336.2,71.2l-1.8-3.6h-0.2c-1.3,1.6-2.6,2.7-3.9,3.3c-1.3,0.6-3,0.9-5.2,0.9c-2.6,0-4.6-0.8-6.1-2.3\
              c-1.5-1.6-2.2-3.7-2.2-6.6c0-2.9,1-5.1,3.1-6.6c2-1.4,5-2.2,8.9-2.4l4.6-0.1v-0.4c0-2.3-1.1-3.4-3.4-3.4c-2,0-4.6,0.7-7.7,2\
              l-2.7-6.3c3.2-1.7,7.3-2.5,12.2-2.5c3.5,0,6.3,0.9,8.2,2.6c1.9,1.8,2.9,4.2,2.9,7.3v18.1H336.2z M329.1,64.9c1.2,0,2.1-0.4,3-1.1\
              s1.2-1.7,1.2-2.8v-2.1l-2.2,0.1c-3.1,0.1-4.7,1.3-4.7,3.5C326.4,64.1,327.3,64.9,329.1,64.9z')
              path.st0(d='M370.5,62.7c0,3-1,5.2-3,6.7c-2,1.5-4.9,2.3-8.7,2.3c-2,0-3.8-0.1-5.3-0.3s-3-0.6-4.6-1.2v-7.6\
              c1.5,0.6,3.1,1.2,4.9,1.6c1.8,0.4,3.3,0.6,4.7,0.6c2.1,0,3.1-0.5,3.1-1.4c0-0.5-0.3-0.9-0.9-1.3c-0.6-0.4-2.2-1.1-5-2.2\
              c-2.5-1-4.3-2.2-5.3-3.5s-1.5-3-1.5-5c0-2.6,1-4.6,3-6s4.8-2.1,8.4-2.1c1.8,0,3.5,0.2,5.1,0.6c1.6,0.4,3.3,1,5,1.7l-2.6,6.1\
              c-1.3-0.6-2.6-1-4-1.4c-1.4-0.4-2.6-0.6-3.5-0.6c-1.6,0-2.3,0.4-2.3,1.1c0,0.5,0.3,0.9,0.8,1.2s2.1,1,4.7,2\
              c1.9,0.8,3.4,1.6,4.3,2.3s1.6,1.7,2.1,2.7S370.5,61.2,370.5,62.7z')
              path.st0(d='M389.3,64.1c1.3,0,2.8-0.3,4.6-0.9v6.9c-1.3,0.6-2.5,0.9-3.7,1.2c-1.2,0.2-2.5,0.4-4.1,0.4\
              c-3.2,0-5.5-0.8-6.9-2.3c-1.4-1.6-2.1-4-2.1-7.2V50.7h-3.3v-3.9l4.2-3l2.5-5.8h6.2v5.5h6.8v7.1h-6.8v10.7\
              C386.7,63.3,387.6,64.1,389.3,64.1z')
              path.st0(d='M412,71.7c-4.6,0-8.2-1.2-10.7-3.7c-2.5-2.4-3.8-5.9-3.8-10.4c0-4.7,1.2-8.2,3.5-10.7\
              c2.4-2.5,5.7-3.7,10.1-3.7c4.2,0,7.4,1.1,9.6,3.2c2.3,2.2,3.4,5.3,3.4,9.4V60h-17c0.1,1.5,0.6,2.7,1.7,3.6\
              c1.1,0.9,2.5,1.3,4.3,1.3c1.7,0,3.2-0.2,4.6-0.5c1.4-0.3,2.9-0.9,4.6-1.6v6.8c-1.5,0.8-3,1.3-4.6,1.6\
              C416.1,71.5,414.2,71.7,412,71.7z M411.5,49.6c-1.1,0-2.1,0.4-2.8,1.1c-0.8,0.7-1.2,1.8-1.3,3.3h8.2c0-1.3-0.4-2.4-1.1-3.2\
              S412.7,49.6,411.5,49.6z')
              path.st0(d='M446.2,43.1c0.8,0,1.6,0.1,2.4,0.2l0.5,0.1l-0.9,9c-0.8-0.2-1.9-0.3-3.2-0.3c-2.1,0-3.6,0.5-4.5,1.4\
              c-0.9,0.9-1.4,2.3-1.4,4.1v13.5h-9.5V43.6h7.1l1.5,4.4h0.5c0.8-1.5,1.9-2.6,3.3-3.5C443.3,43.6,444.7,43.1,446.2,43.1z')
              path.st0(d='M449.6,43.6h10l4.7,15.8c0.2,0.8,0.4,1.8,0.5,3h0.2c0.1-1.1,0.3-2.1,0.6-2.9l4.8-15.9h9.7l-10.9,29.3\
              c-1.4,3.7-3.1,6.4-5.1,7.9s-4.7,2.3-8,2.3c-1.3,0-2.6-0.1-3.9-0.4v-7.5c0.9,0.2,1.8,0.3,2.9,0.3c0.8,0,1.6-0.2,2.2-0.5\
              c0.6-0.3,1.2-0.8,1.7-1.4s1-1.6,1.5-2.9L449.6,43.6z')

      Navigation(:account='account' @closeNav='toggleNav(true)')
    Hambuger(@toggleNav='toggleNav()')
</template>

<script>
import { mapState, mapActions } from 'vuex'
import Navigation from './Navigation'
import Hambuger from './Hamburger'

export default {
  name: 'page-header',
  components: {
    Navigation,
    Hambuger
  },
  computed: {
    ...mapState({
      account: result => result.account.account
    })
  },
  methods: {
    ...mapActions(['toggleNav'])
  }
}
</script>

<style lang="stylus">
.open-nav
  .logo
    transform: translateX(-50%)
    margin-left: 50%
  .index
    .st0
      fill: #36495E !important

  .hamburger:before, .hamburger:after
    background-color: #222 !important
</style>

<style lang="stylus" scoped>
.header
  position relative
  width: 100%
  top 0
  z-index 4

  .wrapper
    height $header-height
    display flex
    flex-wrap wrap
    align-items center

.logo
  display block
  max-width 200px
  margin-top -5px
  position: relative
  z-index: 1
  transition: all ease-in .2s

  img
    display block
    width 100%

  +laptop-up()
    transform: none
    max-width 240px
    min-width 200px
    margin: -10px 90px 0 0

.index
  position: absolute;
  width: 100%;

  +laptop-up()
    ::v-deep .navbar-item
      color: #fff

  .hamburger:before, .hamburger:after
    background-color: #fff

  .st0
    fill: white

svg
  width: 200px
  height: 49.34px

  +laptop-up()
    width: 282px
</style>
