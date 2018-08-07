<template>
  <div id="header">
    <svg version="1.1" id="logo" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
      viewBox="0 0 117.6 72" style="enable-background:new 0 0 117.6 72;" xml:space="preserve">
      <g id="XMLID_45_">
        <text id="XMLID_148_" transform="matrix(1 0 0 1 0 28.0361)" class="stt0 stt1 stt2">Music</text>
      </g>
      <g id="XMLID_44_">
        <text id="XMLID_149_" transform="matrix(1 0 0 1 8.5234 68.0986)" class="stt3 stt4 stt5">Inc</text>
      </g>
    </svg>
    <div class="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/events">Events</router-link>
      <router-link to="/about">About</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'navigation',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

      .stt0{fill:#F1F1F2;}
      .stt1{font-family:'Monoton';}
      .stt2{font-size:33.5724px;}
      .stt3{fill:#FFFFFF;}
      .stt4{font-family:'Permanent Marker';}
      .stt5{font-size:53.3582px;}

#header {
  padding: 30px;
  .nav {
    float: right;
  }
  a {
    font-weight: bold;
    color: #ffffff;
    text-decoration: none;
    margin-right: 1em;
    &.router-link-exact-active {
      color: #b94242;
    }
  }
  #logo {
    width: 5em;
    height: 5em;
    float: left;
    margin-top: -2em;
  }
}
</style>
