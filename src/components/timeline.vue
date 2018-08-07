<template>
  <div id="timeline">

    <div class="grid">
        <div class="date">
            
        </div>

        <div class="date">
            <p @mouseover="activeTwo = true" @mouseleave="activeTwo = false">Date, Event, </br>
            Place</p>
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
            <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
        </div>

        <div class="date">
            
        </div>

        <div class="date">
            
        </div>

        <div class="date">
            
        </div>

        <div class="date">
            <p @mouseover="activeSix = true" @mouseleave="activeSix = false" >Date, Event, </br>
            Place</p>
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
            <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
        </div>

        <div class="date">
            
        </div>

        <div class="date">
            
        </div>

        <div class="date">
            <p @mouseover="activeNine = true" @mouseleave="activeNine = false">Date, Event, </br>
            Place</p>
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
            <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
        </div>

        <div class="date">
            
        </div>

        <div class="date">
            
        </div>

        <div class="date under">
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
                <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
            <p @mouseover="activeOne = true" @mouseleave="activeOne = false" >Date, Event, </br>
            Place</p>
        </div>

        <div class="date">
            
        </div>

        <div class="date under">
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
                <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
            <p @mouseover="activeThree = true" @mouseleave="activeThree = false" >Date, Event, </br>
            Place</p>
        </div>

        <div class="date">
            
        </div>

        <div class="date under">
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
                <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
            <p @mouseover="activeFive = true" @mouseleave="activeFive = false" >Date, Event, </br>
            Place</p>
        </div>

        <div class="date">
            
        </div>

        <div class="date under">
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
                <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
            <p @mouseover="activeSeven = true" @mouseleave="activeSeven = false" >Date, Event, </br>
            Place</p>
        </div>

        <div class="date">
            
        </div>

        <div class="date">
            
        </div>

        <div class="date under">
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
                <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
            <p @mouseover="activeTen = true" @mouseleave="activeTen = false" >Date, Event, </br>
            Place</p>
        </div>

        <div class="date under">
            <svg version="1.1" id="Layer_1" class="line" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
            viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
                <line id="XMLID_163_" class="st000" x1="7.1" y1="7" x2="494.7" y2="7"/>
            </svg>
            <!--<svg version="1.1" id="ball" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                viewBox="0 0 3.1 3.1" style="enable-background:new 0 0 3.1 3.1;" xml:space="preserve">
                    <circle id="XMLID_229_" class="sstt0" :class="{active:activeFour}" cx="1.6" cy="1.6" r="1.6"/>
            </svg>-->
            <p @mouseover="activeEleven = true" @mouseleave="activeEleven = false" >Date, Event, </br>
            Place</p>
        </div>


    </div>

    <svg version="1.1" id="Layer_1" class="timeline" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
        viewBox="0 0 501 15" style="enable-background:new 0 0 501 15;" xml:space="preserve">
        <g id="XMLID_137_">
            <linearGradient id="XMLID_138_" gradientUnits="userSpaceOnUse" x1="6.103519e-007" y1="550" x2="374" y2="550">
              <stop  offset="0" style="stop-color:#D04999"/>
              <stop  offset="0.5" style="stop-color:#1B2152"/>
              <stop  offset="1" style="stop-color:#02B7E8"/>
            </linearGradient>
            <line id="XMLID_163_" class="st0" x1="7.1" y1="7" x2="494.7" y2="7"/>
        </g>
    </svg>

  </div>
</template>

<script>
export default {
  name: 'timeline',
  data () {
    return {
        activeOne: false,
        activeTwo: false,
        activeThree: false,
        activeFour: false,
        activeFive: false,
        activeSix: false,
        activeSeven: false,
        activeEight: false,
        activeNine: false,
        activeTen: false,
        activeEleven: false
    }
    },
    methods: {
        mouseOver: function(){
            this.active = !this.active
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
    .sstt0 {
        fill:#FFFFFF;
    }

    #timeline {
        position: relative;
        width: 70%;
        margin: auto;
        margin-top: 15em;
    }

    .timeline {
        position: absolute;
        right: 0;
        left: 0;
        top: 7em;
        width: 92.2%;
    }

    .grid {
        padding-left: 1.2em;
        display: grid;
        grid-template-columns: repeat(11, 1fr);
        grid-template-rows: repeat(2, 8.5em);
    }

    .date {
        //position: absolute;
        background-color: rgba(0, 255, 255, 0);
        width: 8em;
        top: 0em;
        grid-column: span 1;
        margin-left: -4em;
        p {
            font-size: 1em;
            text-indent: 0px;
            text-align: center;
            color: rgb(146, 52, 52);
            width: 6em;
            margin: 1em;
            cursor: pointer;
            transition: .4s;
            &:hover {
                transform: scale(1.2);
                color: rgb(190, 115, 110);
            }
        }
        &.under {
            font-size: .7em;
            opacity: .4;
            p {
                color: rgb(0, 217, 255);
                &:hover {
                    color: rgb(167, 242, 255);
                }
            }
        }
    }

    .active {
        color: rgb(148, 19, 19);
    }

    .line {
        width: 3.5em;
        margin-top: 1em;
        margin-bottom: 1em;
        transform: rotate(90deg);
        stroke-width: 15;
        fill: white;
        z-index: 1;
    }
</style>
