<template>
  <div id="footerComponent">
    <div class="footer">
      <router-link to="/">Contact</router-link>
      <router-link to="/events">Job Opportunities</router-link>
      <router-link to="/about">Staff</router-link>
      <p>Made by Samuel M. Bednarz</p>
    </div>
  </div>
</template>

<script>
export default {
    name: 'footerComponent',
    data () {
        return {
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
    .footer {
        padding-top: 3em;
        padding-bottom: 1em;
        text-align: center;
        width: 70%;
        margin: auto;
        p {
            width: 12.9em;
            font-size: .8em;
            opacity: .5;
            text-indent: 0px;
            margin: auto;
        }
        a {
            color: rgba(255, 255, 255, 0.418);
            text-decoration: none;
            margin-right: 20px;
            &:nth-of-type(3) {
                margin-right: 0px;
            }
        }
    }
</style>
