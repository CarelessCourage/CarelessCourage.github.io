<template>
  <div id="app">
    <navigation></navigation>
    <transition name="router" enter-active-class="animated fadeInDown" leave-active-class="animated fadeOutDown" mode="out-in">
      <router-view/>
    </transition>
  </div>
</template>

<script>
import navigation from '@/components/navigation.vue'
export default {
  name: 'home',
  components: {
    navigation
  }

}
</script>


<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #efe6fd;
}
p {
  text-align: left;
  width: 40em;
  font-size: 1.2em;
  text-indent: 50px;
  line-height: 1.7em;
  word-spacing: 0em;
}
html {
  background-color: rgb(16, 0, 19);
  overflow-x: hidden;
}
h2{
  font-family: 'Permanent Marker';
}

.st00{fill:none;stroke:#FFFFFF;stroke-width:0.5;stroke-miterlimit:10;}
.st000{fill:rgba(255, 255, 255, 0.144);stroke:rgba(255, 255, 255, 0.356);stroke-width:25;stroke-miterlimit:10;}
.st01{
  fill:#FFFFFF; 
  cursor: pointer; 
  transition: .4s;
  &.active {
    fill: rgb(148, 19, 19);
  }
}
.st01:hover{fill:rgb(133, 14, 14);}

  .st0{
    fill:none;
    stroke:url(#XMLID_138_);
    stroke-miterlimit:10;
    &.active {
      color: rgb(148, 19, 19);
    }
  }
  .sst0{fill:none;stroke:#FFFFFF;stroke-miterlimit:10;}
        .st1{fill:none;stroke:url(#XMLID_139_);stroke-miterlimit:10;}
        .st2{fill:none;stroke:url(#XMLID_140_);stroke-miterlimit:10;}
        .st3{fill:none;stroke:url(#XMLID_141_);stroke-miterlimit:10;}
        .st4{fill:none;stroke:url(#XMLID_142_);stroke-miterlimit:10;}
        .st5{fill:none;stroke:url(#XMLID_143_);stroke-miterlimit:10;}
        .st6{fill:none;stroke:url(#XMLID_144_);stroke-miterlimit:10;}
        .st7{fill:none;stroke:url(#XMLID_145_);stroke-miterlimit:10;}
        .st8{fill:none;stroke:url(#XMLID_146_);stroke-miterlimit:10;}
        .st9{fill:none;stroke:url(#XMLID_147_);stroke-miterlimit:10;}
        .st10{fill:none;stroke:url(#XMLID_147_);stroke-miterlimit:10;}
        .st11{fill:none;stroke:url(#XMLID_147_);stroke-miterlimit:10;}
        .st12{fill:none;stroke:url(#XMLID_150_);stroke-miterlimit:10;}
        .st13{fill:none;stroke:url(#XMLID_151_);stroke-miterlimit:10;}
        .st14{fill:none;stroke:url(#XMLID_152_);stroke-miterlimit:10;}
        .st15{fill:none;stroke:url(#XMLID_153_);stroke-miterlimit:10;}
        .st16{fill:none;stroke:url(#XMLID_154_);stroke-miterlimit:10;}
        .st17{fill:none;stroke:url(#XMLID_155_);stroke-miterlimit:10;}
        .st18{fill:none;stroke:url(#XMLID_156_);stroke-miterlimit:10;}
        .st19{fill:none;stroke:url(#XMLID_157_);stroke-miterlimit:10;}
        .st20{fill:none;stroke:url(#XMLID_158_);stroke-miterlimit:10;}
        .st21{fill:none;stroke:url(#XMLID_159_);stroke-miterlimit:10;}
        .st22{fill:none;stroke:url(#XMLID_160_);stroke-miterlimit:10;}
        .st23{fill:none;stroke:url(#XMLID_161_);stroke-miterlimit:10;}
        .st24{fill:none;stroke:url(#XMLID_162_);stroke-miterlimit:10;}
        .st25{fill:none;stroke:url(#XMLID_163_);stroke-miterlimit:10;}
        .st26{fill:none;stroke:url(#XMLID_164_);stroke-miterlimit:10;}
        .st27{fill:none;stroke:url(#XMLID_165_);stroke-miterlimit:10;}
        .st28{fill:none;stroke:url(#XMLID_166_);stroke-miterlimit:10;}
        .st29{fill:none;stroke:url(#XMLID_167_);stroke-miterlimit:10;}
        .st30{fill:none;stroke:url(#XMLID_168_);stroke-miterlimit:10;}
        .st31{fill:none;stroke:url(#XMLID_169_);stroke-miterlimit:10;}
        .st32{fill:none;stroke:url(#XMLID_170_);stroke-miterlimit:10;}
        .st33{fill:none;stroke:url(#XMLID_171_);stroke-miterlimit:10;}
        .st34{fill:none;stroke:url(#XMLID_172_);stroke-miterlimit:10;}
        .st35{fill:none;stroke:url(#XMLID_173_);stroke-miterlimit:10;}
        .st36{fill:none;stroke:url(#XMLID_174_);stroke-miterlimit:10;}
        .st37{fill:none;stroke:url(#XMLID_175_);stroke-miterlimit:10;}
        .st38{fill:none;stroke:url(#XMLID_176_);stroke-miterlimit:10;}
        .st39{fill:none;stroke:url(#XMLID_177_);stroke-miterlimit:10;}
        .st40{fill:none;stroke:url(#XMLID_178_);stroke-miterlimit:10;}
        .st41{fill:none;stroke:url(#XMLID_179_);stroke-miterlimit:10;}
        .st42{fill:none;stroke:url(#XMLID_180_);stroke-miterlimit:10;}
        .st43{fill:none;stroke:url(#XMLID_181_);stroke-miterlimit:10;}
        .st44{fill:none;stroke:url(#XMLID_182_);stroke-miterlimit:10;}
        .st45{fill:none;stroke:url(#XMLID_183_);stroke-miterlimit:10;}
        .st46{fill:none;stroke:url(#XMLID_184_);stroke-miterlimit:10;}
        .st47{fill:none;stroke:url(#XMLID_185_);stroke-miterlimit:10;}
        .st48{fill:none;stroke:url(#XMLID_186_);stroke-miterlimit:10;}
        .st49{fill:none;stroke:url(#XMLID_187_);stroke-miterlimit:10;}
        .st50{fill:none;stroke:url(#XMLID_188_);stroke-miterlimit:10;}
        .st51{fill:none;stroke:url(#XMLID_189_);stroke-miterlimit:10;}
        .st52{fill:none;stroke:url(#XMLID_190_);stroke-miterlimit:10;}
        .st53{fill:none;stroke:url(#XMLID_191_);stroke-miterlimit:10;}
        .st54{fill:none;stroke:url(#XMLID_192_);stroke-miterlimit:10;}
        .st55{fill:none;stroke:url(#XMLID_193_);stroke-miterlimit:10;}
        .st56{fill:none;stroke:url(#XMLID_194_);stroke-miterlimit:10;}
        .st57{fill:none;stroke:url(#XMLID_195_);stroke-miterlimit:10;}
        .st58{fill:none;stroke:url(#XMLID_196_);stroke-miterlimit:10;}
        .st59{fill:none;stroke:url(#XMLID_197_);stroke-miterlimit:10;}
        .st60{fill:none;stroke:url(#XMLID_198_);stroke-miterlimit:10;}
</style>
