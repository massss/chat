<template lang="pug">
  div
    h1.title.text-blue ChatVert
    .container-wrap
      router-view.container
    .footer
      | by
      a(href="https://github.com/massss")  @massss
    //- a.post-button(@click="")
    //-   i.fas.fa-pencil-alt

</template>
<script>
export default {
  components: {
  },
  methods: {
  }
}
</script>

<style lang="sass" scoped>
  .title
    text-align: center;
    padding-top: 1em;
    font-size: 3em;
    padding-bottom: 1em;
    font-weight: normal;
    margin: 0;
  .container-wrap
    max-width: 800px;
    margin: 0 auto;
    margin-bottom: 50px;
  .container
    margin-left: 10px;
    margin-right: 10px;
    // background: #fff;
    border-radius: 5px;
  .footer
    text-align: center;
    font-size: 14px;
    padding-top: 4em;
    padding-bottom: 4em;
    background: #17425a;
    color: #58b69a;
    a
      text-decoration: none;
      color: #d33943;
      &:hover
        opacity: 0.8;
  .post-button
    position: fixed
    bottom: 20px
    right: 20px
    border-radius: 50%
    width: 80px
    height: 80px
    background: #17425a
    color: #fff
    box-shadow: 0 1px 3px 1px rgba(0, 0, 0, 0.3)
    cursor: pointer
    i
      position: absolute
      top: 0
      left: 30px
      line-height: 75px
      font-size: 25px
</style>