<div class="box"></div>

<style>
  @keyframes shrink1 {
    0% {transform: matrix(1,0,0,1,0,0);}
    90% {transform: matrix(0.000001,0,0,0.0000001,0,0);}
    100% {transform: matrix(1,0,0,1,0,0);}
  }

  @keyframes shrink2 {
    0% {transform: matrix(1,0,0,1,0,0);}
    45% {transform: matrix(1,0,0,0.5,0,0);}
    90% {transform: matrix(0.000001,0,0,0.0000001,0,0);}
    100% {transform: matrix(1,0,0,1,0,0);}
  }

  @keyframes aniMatrixWindUp {
    from, to {transform: matrix(1,0,0,1,0,0);}
    25% {transform: matrix(0,1,-1,0,0,0);}
    50% {transform: matrix(-1,0,0,-1,0,0);}
    75% {transform: matrix(0,-1,1,0,0,0);}
  } /* Use with default (ease) timing.  5s duration works well */

  @keyframes aniMatrixSkew1 {
    from, to {transform: matrix(1,0,0,1,0,0);}
    90% {transform: matrix(1,1,2,1,0,0);}
  }

  @keyframes aniRotate {
    from {transform: rotate(0deg);}
    to {transform: rotate(360deg);}
  }

  .box {
    height: 100px;
    width: 100px;
    padding: 10px;
    background-color: #697889;
    animation-name: aniMatrixWindUp;
    animation-duration: 5s;
    animation-iteration-count: infinite;
  }
</style>
