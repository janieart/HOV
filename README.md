<style>
.grow {
  -webkit-transition:all 0.5s ease-out;
  -moz-transition:all 0.5s ease-out;
  -ms-transition:all 0.5s ease-out;
  -o-transition:all 0.5s ease-out;
  transition:all 0.5s ease-out;
}

.grow:hover {
  -webkit-transform:scale(1.3);
  -moz-transform:scale(1.3);
  -ms-transform:scale(1.3);
  -o-transform:scale(1.3);
  transform:scale(1.3);
}

.zoom-tilt {
  -webkit-transition:all 0.3s ease-out;
  -moz-transition:all 0.3s ease-out;
  -ms-transition:all 0.3s ease-out;
  -o-transition:all 0.3s ease-out;
  transition:all 0.3s ease-out;
}

.zoom-tilt:hover {
  -webkit-transform:rotate(15deg) scale(1.3);
  -moz-transform:rotate(15deg) scale(1.3);
  -ms-transform:rotate(15deg) scale(1.3);
  -o-transform:rotate(15deg) scale(1.3);
  transform:rotate(15deg) scale(1.3);
}

.fade-in {
  -webkit-transition:opacity .5s ease-out;
  -moz-transition:opacity .5s ease-out;
  -ms-transition:opacity .5s ease-out;
  -o-transition:opacity .5s ease-out;
  transition:opacity .5s ease-out;
  opacity:0.2;
}

.fade-in:hover {
  opacity:1;
}

.fade-out {
  -webkit-transition:opacity .5s ease-out;
  -moz-transition:opacity .5s ease-out;
  -ms-transition:opacity .5s ease-out;
  -o-transition:opacity .5s ease-out;
  transition:opacity .5s ease-out;
}

.fade-out:hover {
  opacity:0.2;
}

@-webkit-keyframes wobble {
  16.65% {
    -webkit-transform: translateY(8px);
    transform: translateY(8px);
  }
  33.3% {
    -webkit-transform: translateY(-6px);
    transform: translateY(-6px);
  }
  49.95% {
    -webkit-transform: translateY(4px);
    transform: translateY(4px);
  }
  66.6% {
    -webkit-transform: translateY(-2px);
    transform: translateY(-2px);
  }
  83.25% {
    -webkit-transform: translateY(1px);
    transform: translateY(1px);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}

@keyframes wobble {
  16.65% {
    -webkit-transform: translateY(8px);
    -ms-transform: translateY(8px);
    transform: translateY(8px);
  }
  33.3% {
    -webkit-transform: translateY(-6px);
    -ms-transform: translateY(-6px);
    transform: translateY(-6px);
  }
  49.95% {
    -webkit-transform: translateY(4px);
    -ms-transform: translateY(4px);
    transform: translateY(4px);
  }
  66.6% {
    -webkit-transform: translateY(-2px);
    -ms-transform: translateY(-2px);
    transform: translateY(-2px);
  }
  83.25% {
    -webkit-transform: translateY(1px);
    -ms-transform: translateY(1px);
    transform: translateY(1px);
  }
  100% {
    -webkit-transform: translateY(0);
    -ms-transform: translateY(0);
    transform: translateY(0);
  }
}

.wobble {
  display: inline-block;
  -webkit-transform: translateZ(0);
  -ms-transform: translateZ(0);
  transform: translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
}

.wobble:hover {
  -webkit-animation-name: wobble;
  animation-name: wobble;
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-timing-function: ease-in-out;
  animation-timing-function: ease-in-out;
  -webkit-animation-iteration-count: 1;
  animation-iteration-count: 1;
}

.sink {
  -webkit-transition:all .3s ease-out;
  -moz-transition:all .3s ease-out;
  -ms-transition:all .3s ease-out;
  -o-transition:all .3s ease-out;
  transition:all .3s ease-out;
}

.sink:hover {
  -webkit-transform:translate(0px,10px);
  -moz-transform:translate(0px,10px);
  -ms-transform:translate(0px,10px);
  -o-transform:translate(0px,10px);
  transform:translate(0px,10px);
}

.float {
  -webkit-transition:all .3s ease-out;
  -moz-transition:all .3s ease-out;
  -ms-transition:all .3s ease-out;
  -o-transition:all .3s ease-out;
  transition:all .3s ease-out;
}

.float:hover {
  -webkit-transform:translate(0px,-10px);
  -moz-transform:translate(0px,-10px);
  -ms-transform:translate(0px,-10px);
  -o-transform:translate(0px,-10px);
  transform:translate(0px,-10px);
}

@-webkit-keyframes pulse {
  25% {
    -webkit-transform: scale(1.2);
    transform: scale(1.2);
  }
  75% {
    -webkit-transform: scale(0.8);
    transform: scale(0.8);
  }
}

@keyframes pulse {
  25% {
    -webkit-transform: scale(1.2);
    -ms-transform: scale(1.2);
    transform: scale(1.2);
  }
  75% {
    -webkit-transform: scale(0.8);
    -ms-transform: scale(0.8);
    transform: scale(0.8);
  }
}

.pulse {
  display: inline-block;
  -webkit-transform: translateZ(0);
  -ms-transform: translateZ(0);
  transform: translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
}

.pulse:hover {
  -webkit-animation-name: pulse;
  animation-name: pulse;
  -webkit-animation-duration: 1s;
  animation-duration: 1s;
  -webkit-animation-timing-function: linear;
  animation-timing-function: linear;
  -webkit-animation-iteration-count: infinite;
  animation-iteration-count: infinite;
}

.shrink{
  -webkit-transition:all 0.5s ease-out;
  -moz-transition:all 0.5s ease-out;
  -ms-transition:all 0.5s ease-out;
  -o-transition:all 0.5s ease-out;
  transition:all 0.5s ease-out;
}

.shrink:hover {
  -webkit-transform:scale(.7);
  -moz-transform:scale(.7);
  -ms-transform:scale(.7);
  -o-transform:scale(.7);
  transform:scale(.7);
}

.rotate {
  -webkit-transition:all 0.5s ease-out;
  -moz-transition:all 0.5s ease-out;
  -ms-transition:all 0.5s ease-out;
  -o-transition:all 0.5s ease-out;
  transition:all 0.5s ease-out;
}

.rotate:hover {
  -webkit-transform:rotate(360deg);
  -moz-transform:rotate(360deg);
  -ms-transform:rotate(360deg);
  -o-transform:rotate(360deg);
  transform:rotate(360deg);
}
</style><center>
<div style="display:inline-block; width:90%; float:left;">
<h1>grow</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="grow" src="ex.png" /></a>

<h1>zoom-tilt</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="zoom-tilt" src="ex.png" /></a>

<h1>fade-in</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="fade-in" src="ex.png" /></a>

<h1>fade-out</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="fade-out" src="ex.png" /></a>

<h1>wobble</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="wobble" src="ex.png" /></a>

<h1>sink</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="sink" src="ex.png" /></a>

<h1>float</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="float" src="ex.png" /></a>

<h1>pulse</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="pulse" src="ex.png" /></a>

<h1>shrink</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="shrink" src="ex.png" /></a>

<h1>rotate</h1>
<a alt="alt title here" href="#"><img alt="alt title here" class="rotate" src="ex.png" /></a>
</div></center>
