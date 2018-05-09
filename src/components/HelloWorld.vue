<template>
 <div>

     <div class="bgtint"></div>
     <section class="bussinesscard">
     		<div class="flip">
     			<div class="front">
     				<div class="top">
                        <div class="logo">
                            Dexter
                        </div>
     				</div>
     				<div class="nametroduction">
     					<div class="name">Signin</div>
     					<div class="introduction">A career is born in public-talent in privacy.</div>
     				</div>
     				<div class="contact">
     					 <div class="website">
     						 <i class="fa fa-user-secret icon"></i>
     					          <a  data-toggle="modal" href="#Model-1">Teacher
                                </a>
     					</div>
     					<div class="twitter">
                            <i class="fa fa-users icon"></i>
     						<a data-toggle="modal" href="#Model-1">Parent</a>
     					</div>
     					<div class="phone">
     						<i class="fa fa-mortar-board icon"></i>
     						<a data-toggle="modal" href="#Model-1">Student</a>
     					</div>
     				</div>
     			</div>
     			<div class="back"></div> <!--FIXES FONT RENDERING -->
     		</div>
     	</section>
     	<section class="tooltip">
     	</section>
        <div class="modal fade" id="Model-1" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
          <h5 class="modal-title" id="exampleModalLongTitle">
              <h4 style="color:red;">
                        <span class="glyphicon glyphicon-lock">
                        </span>
                        Login
                    </h4>
                </h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
          <form role="form">
            <div class="form-group">
              <label for="usrname">
                  <span class="glyphicon glyphicon-user">
                  </span>
                   Username
               </label>
              <input type="text" class="form-control" id="usrname" placeholder="Enter email">
            </div>
            <div class="form-group">
              <label for="psw">
                  <span class="glyphicon glyphicon-eye-open">
                  </span>
                  Password
              </label>
              <input type="text" class="form-control" id="psw" placeholder="Enter password">
            </div>
            <div class="checkbox">
              <label>
                  <input type="checkbox" value="" checked>
                  Remember me
              </label>
            </div>
            <button type="submit" class="btn btn-default btn-success btn-block">
                <span class="glyphicon glyphicon-off">
                </span>
                 Login
             </button>
          </form>
      </div>
      <div class="modal-footer">
          <h5>New User?<i class="fa fa-hand-o-right" style="font-size:36px"></i></h5>
        <!-- <button type="button" class="btn btn-secondary" data-toggle="modal" data-target="#Model-3" data-dismiss="modal">Prev</button> -->
        <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#Model-2"data-dismiss="modal" >Next</button>
      </div>
    </div>
  </div>
</div>

<!-- Model-2 -->
<div class="modal fade w3-animate-zoom" id="Model-2" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true" >
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLongTitle">Second</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-toggle="modal" data-target="#Model-1" data-dismiss="modal">Prev</button>
        <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#Model-3" data-dismiss="modal">Next</button>
      </div>
    </div>
  </div>
</div>

<!-- Model-3 -->
<div class="modal fade" id="Model-3" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">

        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-toggle="modal" data-target="#Model-2" data-dismiss="modal">Prev</button>
        <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#Model-1" data-dismiss="modal">Next</button>
      </div>
    </div>
  </div>
</div>
    <!-- <div class="modal fade" id="myModal" role="dialog">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h4 style="color:red;">
              <span class="glyphicon glyphicon-lock">
              </span>
              Login
          </h4>
           <button type="button" class="close" data-dismiss="modal">
               &times;
           </button>
        </div>
        <div class="modal-body">
          <form role="form">
            <div class="form-group">
              <label for="usrname">
                  <span class="glyphicon glyphicon-user">
                  </span>
                   Username
               </label>
              <input type="text" class="form-control" id="usrname" placeholder="Enter email">
            </div>
            <div class="form-group">
              <label for="psw">
                  <span class="glyphicon glyphicon-eye-open">
                  </span>
                  Password
              </label>
              <input type="text" class="form-control" id="psw" placeholder="Enter password">
            </div>
            <div class="checkbox">
              <label>
                  <input type="checkbox" value="" checked>
                  Remember me
              </label>
            </div>
            <button type="submit" class="btn btn-default btn-success btn-block">
                <span class="glyphicon glyphicon-off">
                </span>
                 Login
             </button>
          </form>
        </div>
        <div class="modal-footer">
          <button type="submit" class="btn btn-default btn-default pull-left" data-dismiss="modal">
              <span class="glyphicon glyphicon-remove">
              </span>
               Cancel
           </button>
          <p>
              Not a member?
              <a href="#">
                  Sign Up
              </a>
          </p>
          <p>Forgot
              <a href="#">
                  Password?
              </a>
          </p>
          <hr>
           <p id="ab-body-text"></p>
           <div id="ab-modal-visual"></div>
             <a href="#" class="button" id="ab-modal-next">Next</a>
        </div>
      </div>
    </div>
  </div>
</div> -->
    </div>
</template>

<script>
$('.container').on('click', function () {
  $('.card').toggleClass('flipped');
});
</script>
<style>
/* @import url(https://fonts.googleapis.com/css?family=Old+Standard+TT:400,400italic,700);
@import url(https://fonts.googleapis.com/css?family=Raleway:400,100,200,300,500,600,700,800,900);
@import url(https://code.ionicframework.com/ionicons/1.5.2/css/ionicons.min.css); */
::selection {
  color: #fff;
  background: #2a2b39;
}

::-moz-selection {
  color: #fff;
  background: #2a2b39;
}
.modal-backdrop {
  background-color:navy;
}
.modal-backdrop.show, .modal-backdrop.fade  {
  opacity:0.5;
}
/* .modal.fade .modal-dialog {
  transform:translate(-100%,0);
}
.modal.show .modal-dialog {
  transform:translate(0%,0%);
} */
.modal.fade .modal-dialog{
  transform:translate(0%,0%);
  transition-property:none;
}
.modal.fade .modal-dialog{
  animation:in ease-in 0.2s;
}
.out{
  animation:out ease-out 0.2s;
}
.modal.fade{
  opacity:1;
}.modal-backdrop {
  background-color:#10E6Bc;
}
.modal-backdrop.show, .modal-backdrop.fade  {
  opacity:0.5;
}
/* .modal.fade .modal-dialog {
  transform:translate(-100%,0);
}
.modal.show .modal-dialog {
  transform:translate(0%,0%);
} */
.modal.fade .modal-dialog{
  transform:translate(0%,0%);
  transition-property:none;
}
.modal.fade .modal-dialog{
  animation:in ease-in 0.2s;
}
.out{
  animation:out ease-out 0.2s;
}
.modal.fade{
  opacity:1;
}

@keyframes in {
  from {transform:translate(100%,0);}
  to {transform:translate(0%,0%);}
}
@keyframes out {
  from {transform:translate(0%,0);}
  to {transform:translate(-100%,0%);}
}
body{
  font-family: 'Raleway', sans-serif;
  background: url(https://unsplash.imgix.net/uploads/141310026617203b5980d/c86b8baa?q=75&fm=jpg&s=be8d1e8254844f53e56583bd49cf5e77);
  -webkit-background-size: cover;
  -moz-background-size: cover;
  background-size: cover;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  overflow: hidden;
  z-index: 9;
}

.bgtint {
  position: absolute;
  height: 100%;
  width: 100%;
  background: rgba(42, 43, 57, 0.7);
}

p {
  padding: 0;
  margin: 0;
  display: inline-block;
}
.icon{
    color:#9ec649;
}
a {
  color: #315356;
  text-decoration: none;
  -moz-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  -webkit-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
}
a:hover {
  color:#000000;
}

.bussinesscard {
  height: 350px;
  width: 450px;
  overflow: hidden;
  box-shadow: 0px 0px 43px -10px black;
  position: absolute;
  left: 50%;
  top: 50%;
  -moz-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}
.bussinesscard .flip {
  -moz-transition: all 0.5s ease;
  -o-transition: all 0.5s ease;
  -webkit-transition: all 0.5s ease;
  transition: all 0.5s ease;
}
.bussinesscard .front {
  z-index: 11;
  width: 100%;
  position: absolute;
  height: 100%;
  background: #fff;
  box-shadow: 0px 0px 33px -1px rgba(0, 0, 0, 0.45);
  -moz-transform: scale(1, 1);
  -ms-transform: scale(1, 1);
  -webkit-transform: scale(1, 1);
  transform: scale(1, 1);
  -moz-transition: all 0.6s ease;
  -o-transition: all 0.6s ease;
  -webkit-transition: all 0.6s ease;
  transition: all 0.6s ease;
}
.bussinesscard .front .top {
  height: 50%;
  background: #2a2b39;
}
.bussinesscard .front .top:after {
  position: absolute;
  content: '';
  pointer-events: none;
}
.bussinesscard .front .top:after {
  left: 50%;
  width: 2em;
  height: 2em;
  -moz-transform: translateX(-50%) rotate(45deg);
  -ms-transform: translateX(-50%) rotate(45deg);
  -webkit-transform: translateX(-50%) rotate(45deg);
  transform: translateX(-50%) rotate(45deg);
  bottom: 9em;
  z-index: 10;
  background: inherit;
}
.bussinesscard .front .top .logo {
  display: inline-block;
  background: #6acd79;
  color: #fff;
  z-index: 11;
  padding: .16em;
  border: 8px solid #fff;
  position: relative;
  pointer-events: none;
  -moz-transform: translateX(-50%);
  -ms-transform: translateX(-50%);
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  left: 50%;
  margin-top: .4em;
  font-size: 4em;
}
.bussinesscard .front .top .logo .fat {
  font-weight: 800;
}
.bussinesscard .front .top .logo .skinny {
  font-weight: 100;
}
.bussinesscard .front .nametroduction {
  margin-top: 2.4em;
  -moz-transform: translateY(0);
  -ms-transform: translateY(0);
  -webkit-transform: translateY(0);
  transform: translateY(0);
  z-index: 8;
}
.bussinesscard .front .name {
  color: #2a2b39;
  font-weight: 400;
  font-size: 3.2em;
  text-align: center;
  position: relative;
  margin-bottom: .35em;
}
.bussinesscard .front .name:after {
  content: '';
  position: absolute;
  top: 1.3em;
  width: 20%;
  left: 40%;
  right: 40%;
  height: 1px;
  background: #2a2b39;
}
.bussinesscard .front .introduction {
  text-align: center;
  color: #2a2b39;
  font-family: 'Old Standard TT', serif;
  font-style: italic;
}
.bussinesscard .front .contact {
  color: #2a2b39;
  margin-left:4em;
  font-weight: 300;
  font-size:2.3em;
  -moz-transform: translateY(400%);
  -ms-transform: translateY(400%);
  -webkit-transform: translateY(400%);
  transform: translateY(400%);
}
.bussinesscard .front .contact span {
  color: #2D3244;
  font-size: 1.7em;
  width: 1.3em;
  display: inline-block;
}
.bussinesscard .front .contact a {
  position: relative;
  bottom: .24em;
}
.bussinesscard .back {
  width: 100%;
  height: 100%;
  background: #fff;
  backface-visibility: hidden;
  position: absolute;
}

.tooltip {
  position: absolute;
  left: 1em;
  bottom: 1em;
  color: #fff;
  font-weight: 300;
  padding: .4em;
  background: #6acd79;
}

/* HOVER ANIMATIONS */
.front .top .logo, .front .top, .front .top:after, .front .nametroduction, .front .contact {
  -moz-transition: all 0.7s ease-in-out;
  -o-transition: all 0.7s ease-in-out;
  -webkit-transition: all 0.7s ease-in-out;
  transition: all 0.7s ease-in-out;
}

.flip:hover .front .top .logo {
  margin-top: .28em;
  font-size: 1.3em;
  border: 3px solid #fff;
  margin-left: .15em;
  -moz-transform: translateX(0);
  -ms-transform: translateX(0);
  -webkit-transform: translateX(0);
  transform: translateX(0);
  left: 0;
}

.flip:hover .front .top {
  height: 15%;
}
.flip:hover .front .top:after {
  width: 1.5em;
  height: 1.5em;
  bottom: 16.3em;
}

.flip:hover .front .nametroduction {
  -moz-transform: translateY(400%);
  -ms-transform: translateY(400%);
  -webkit-transform: translateY(400%);
  transform: translateY(400%);
}

.flip:hover .front .contact {
  -moz-transform: translateY(-52%);
  -ms-transform: translateY(-52%);
  -webkit-transform: translateY(-52%);
  transform: translateY(-52%);
}

</style>
