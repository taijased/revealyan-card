<template>
    <div class="animation">
        <div class="container">
            <div class="element2"></div>
            <div class="element3"></div>
            <div class="element4"></div>
            <div class="element5"></div>
        </div>
        <div class="container">
            <div class="element2"></div>
            <div class="element3"></div>
            <div class="element4"></div>
            <div class="element5"></div>
            <div class="element6"></div>
        </div>
        <div class="container">
            <div class="element3"></div>
            <div class="element4"></div>
            <div class="element5"></div>
            <div class="element6"></div>
            <div class="element7"></div>
        </div>
        <div class="container">
            <div class="element4"></div>
            <div class="element5"></div>
            <div class="element6"></div>
            <div class="element7"></div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'animation'
}
</script>

<style lang="less" scoped>
@desktop:   ~"only screen and (min-width: 960px) and (max-width: 1199px)";
@tablet:    ~"only screen and (min-width: 720px) and (max-width: 959px)";
@mobile:    ~"only screen and (min-width: 575px) and (max-width: 719px)";

.element1 {
  height: 120px;
  width: 120px;
  margin: 0 auto;
  animation-name: stretch;
  animation-duration: 1s;
  animation-timing-function: ease-in-out;
  animation-delay: 0;
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-fill-mode: none;
  animation-play-state: running;
}

.element2 {
  height: 120px;
  width: 120px;
  margin: 0 auto;
  animation-name: stretch;
  animation-duration: 1s;
  animation-timing-function: ease-in-out;
  animation-delay: 0.25s;
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-fill-mode: none;
  animation-play-state: running;
}

.element3 {
  height: 120px;
  width: 120px;
  margin: 0 auto;
  animation-name: stretch;
  animation-duration: 1s;
  animation-timing-function: ease-in-out;
  animation-delay: 0.5s;
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-fill-mode: none;
  animation-play-state: running;
}

.element4 {
  height: 120px;
  width: 120px;
  margin: 0 auto;
  animation-name: stretch;
  animation-duration: 1s;
  animation-timing-function: ease-in-out;
  animation-delay: 0.75s;
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-fill-mode: none;
  animation-play-state: running;
}

.element5 {
  height: 120px;
  width: 120px;
  margin: 0 auto;
  animation-name: stretch;
  animation-duration: 1s;
  animation-timing-function: ease-in-out;
  animation-delay: 1.0s;
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-fill-mode: none;
  animation-play-state: running;
}

.element6 {
  height: 120px;
  width: 120px;
  margin: 0 auto;
  animation-name: stretch;
  animation-duration: 1s;
  animation-timing-function: ease-in-out;
  animation-delay: 1.25s;
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-fill-mode: none;
  animation-play-state: running;
}

.element7 {
  height: 120px;
  width: 120px;
  margin: 0 auto;
  animation-name: stretch;
  animation-duration: 1s;
  animation-timing-function: ease-in-out;
  animation-delay: 1.5s;
  animation-direction: alternate;
  animation-iteration-count: infinite;
  animation-fill-mode: none;
  animation-play-state: running;
}

@keyframes stretch {
  0% {
    transform: scale(0.9);
    background-color:#050B75;
    border-radius: 20%;
  }
  
  100% {
    transform: scale(1.1);
    background-color: white;
    border-radius: 20%;
  }
}

.container {
  margin: auto;
  text-align: center;
  // @media @tablet {
  //   width: 30vw;
  // }
  // @media @mobile {
  //   width: 10vw;
  // }
}

.element1, .element2, .element3, .element4, .element5, .element6, .element7 {
  display: inline-block;
  width: 120px;
  height: 120px;
}
</style>
