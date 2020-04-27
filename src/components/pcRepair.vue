<template>
  <div class="container">
    <link rel="stylesheet"  href="https://use.fontawesome.com/releases/v5.2.0/css/all.css">
    <div class="card shadow mt-3 wrapper">
        <h3 class="p-1 pl-3">A Clean PC makes a Fast PC</h3>

        <div class="pt-3">

          <div class="row">
              <div class="col-md-3">
                  <img class="pl-3 pt-2 windows" src="../assets/windows10.png" alt="windows">
              </div>
              <div class="col-md-6">
                <div class="sysInfo">
                  <div class="text-left">System Information:</div>
                  <div>Your are currently running: Windows 10</div>
                  <div>Your operating system is supported by SafeSoft Driver Manager </div>
                </div>
              </div>
          </div>
        
          <div class="row pl-4 pt-5">
           
             <transition  name="wiggle"> 
                <div  @mouseover="mouseOver()" v-show="active"  class="col-md-3">
                  <div class="shake shadow sff">
                     <a class="text-uppercase scan" >Scan for Free</a> 
                  </div>
                </div>
             </transition>
              <!-- <div v-show="hover" class="col-md-3">
                  <div class="shadow dl">
                     <a class="scan"> Download Now <span class="ml-3"><i class="fas fa-download fa-2x fa-sm text-white-50"></i></span></a> 
                  </div>
                </div> -->

            <div class="col-md-8">
                <div class="info"><span>Download Time:</span> <span>Under 2 minutes</span></div>
                <div class="info"><span>Made by:</span> <span>Blacktail Technology</span></div>
                <div class="info"><span>Compatible with:</span> <span>Windows XP, Windows Vista, Windows 7, Windows 8, and Windows 10</span></div>
            </div>
          </div>
          
          <div class="pt-5">
            <div class="pl-4 pr-4">Are you dealing with a slow computer? Let SafeSoft Driver Manager help you determine your PC’s outdated and incompatible drivers with its powerful yet lightweight technology. When you activate SafeSoft Driver Manager today, it can help you:</div>
          </div>

         <div class="container">
              <div class=" pl-5 pt-5">
                <div class="row">
                  <div class="col-md-4">
                      <ul class="list-unstyled">
                        <li><span><i class="fas fa-check-circle"></i></span> <span class="pl-1">Find the most compatible drivers for your computer.</span></li>
                        <li><span><i class="fas fa-check-circle"></i></span> <span class="pl-1">Avoid slow system, lags, and freezes.</span></li>
                      </ul>
                  </div>
                  <div class="col-md-4">
                      <ul class="list-unstyled">
                        <li><span><i class="fas fa-check-circle"></i></span> <span class="pl-1">Back-up all of your drivers easily.</span></li>
                        <li><span><i class="fas fa-check-circle"></i></span> <span class="pl-1">Ensure that your hardware and peripherals are working properly.</span></li>
                      </ul>
                  </div>
                  <div class="col-md-4 text-center">
                    <img class="" src="../assets/stars.png" alt="windows">
                    <div>"5-star features"</div>
                  </div>
                </div>
            </div>
         </div>

         <div class="container pt-5">
           <div class="row">

             <div class="col-md-4">
                <div class="card bg-light mb-3 shadow" style="max-width: 18rem;">
                  <div class="card-header  text-white bg-info text-center">Step One</div>
                    <div class="card-body" style="max-height: 18rem;">
                      <h5 class="card-title text-center"><i class="fas fa-download fa-3x"></i></h5>
                      <p class="card-text text-center pt-2">Download SafeSoft Driver Manager Free Version</p>
                    </div>
                 </div>
             </div>
             
             <div class="col-md-4">
                <div class="card bg-light mb-3 shadow" style="max-width: 18rem;">
                  <div class="card-header text-white bg-info text-center">Step Two</div>
                    <div class="card-body"  style="height: 167px;">
                      <h5 class="card-title text-center"><i class="fas fa-cogs fa-3x"></i></h5>
                      <p class="card-text text-center pt-2">Install</p>
                    </div>
                 </div>
             </div>

             <div class="col-md-4" >
               <div class="card bg-light mb-3 shadow" style="max-width: 18rem;">
                  <div class="card-header  text-white bg-info text-center">Step Three </div>
                    <div class="card-body" style="max-height: 18rem;">
                      <h5 class="card-title text-center" id="search"><i class="fas fa-search  fa-3x"></i></h5>
                      <p class="card-text  text-center pt-2">Scan and Diagnose your PC’s drivers</p>
                    </div>
                 </div>
             </div>
           </div>
         </div>
         
         <div class="container pt-5">
           <div class="row">
              <div class="col-md-5">
                <h4 class="pl-4 modal-title">It only takes ONE click to optimize your PC</h4>
                <ul class="pt-1">
                  <li>Get a comprehensive diagnosis of drivers based on your PC’s model</li>
                  <li>Fast download of latest drivers</li>
                  <li>Get access to a regularly updated database of more than 600,000 drivers</li>
                  <li>Detects drivers for devices including network, audio and sound, printer, graphics and video card, and other peripherals</li>
                  <li>Backup and restore your configurations</li>
                  <li>Automatically detect and resolve driver problems</li>
                </ul>
              </div>
              <div class="col-md-7">
                  <div class="bg-info shadow rounded text-white pt-2 pb-2">

                    <div class="pl-5 text-left">
                        <span class="f-search"><i class="fas fa-search fa-2x"></i></span>  <span class="pl-2 whp">Work Hard, Play Hard</span>
                        <div class="pl-4">Have your computer scanned and fixed to experience a better performance.</div>
                    </div>

                    <div class="pl-5 pt-4 pr-2 text-left">
                        <span class="f-tachometer"><i class="fas fa-tachometer-alt fa-2x"></i></span> <span class="pl-2 whp">A Clean PC makes a Fast PC</span>
                        <div class="pl-4">Only a clean PC that’s controlled by the most compatible drivers can operate at its finest. Get this tool to give you a hassle-free way of maintaining your system.</div>
                    </div>
                    <div class="pl-5 pt-4 pr-2 text-left">
                        <span class="f-phone"><i class="fa fa-phone fa-2x"></i></span> <span class="pl-2 whp">Support</span>
                        <div class="pl-4">Need help with SafeSoft Driver Manager? Send us an email at <a class="text-white" href="support@safesoftpro.com">support@safesoftpro.com</a></div>
                    </div>
                  </div>
              </div>
           </div>
         </div>

          <div class="row pt-2">
              <div class="col-md-3">
                  <img class="pl-3 pt-2 windows" src="../assets/windows10.png" alt="windows">
              </div>
              <div class="col-md-6">
                <div class="sysInfo">
                  <div class="text-left">System Information:</div>
                  <div>Your are currently running: Windows 10</div>
                  <div>Your operating system is supported by SafeSoft Driver Manager</div>
                </div>
              </div>
          </div>

            <div class="row pl-5 pt-5">
               <transition name="wiggle"> 
                  <div @mouseover="mouseOver()" v-show="active"  class="col-md-3">
                      <div class="shake shadow sff">
                      <a class="scan" >Scan for Free</a> 
                    </div>
                  </div>
             </transition>
             <!-- <div v-show="hover" class="col-md-3">
                  <div class="shadow dl">
                     <a class="text-uppercase scan"> Download Now <span class="ml-3"><i class="fas fa-download fa-2x fa-sm text-white-50"></i></span></a> 
                  </div>
                </div> -->
            <div class="col-md-8">
                <div class="info"><span>Download Time:</span> <span>Under 2 minutes</span></div>
                <div class="info"><span>Made by:</span> <span>Blacktail Technology</span></div>
                <div class="info"><span>Compatible with:</span> <span>Windows XP, Windows Vista, Windows 7, Windows 8, and Windows 10</span></div>
            </div>
        </div>

        <footer class="footer-distributed">
          <div class="conatiner text-white"> <span>Uninstall Guide</span> | <span>License Agreement</span> | <span>Tems and Conditions</span> | <span>Contact</span></div>
          <hr>
          <div class="footer-left">
             <p>Blacktail Technology &copy; 2020</p>
          </div>

		</footer>
         
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'pcRepair',
  data() {
    return {
        systemInfo: '',
        active: true,
        hover: false
    }
  },
  mounted() {
    // this.active = true
  },
  methods: {
    mouseOver() {
      this.active = true;
      this.hover = true;
      console.log('hover')
    }
  }

 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style  scoped>
.card.shadow.mt-3.wrapper {
    width: 80%;
    margin: 0 auto;
    height: auto;
}
.windows {
  width: 60px;
  position: relative;
  left: 21px;
}
.window {
  width: 60px;
}
.sysInfo {
    position: relative;
    right: 109px;
    font-size: 15px;
}
.sff {
    border: 1px solid;
    width: 113%;
    padding: 22px 0 28px 13px;
    background: #2992b8;
    color: #fff;
    margin-top: -6px;
    border-radius: 5px;
}
.dl {
  border: 1px solid;
  width: 113%;
  padding: 5px 0 25px 13px;
  background: #2992b8;
  color: #fff;
  margin-top: -6px;
  border-radius: 5px;
}
.scan {
  color: #fff;
  font-size: 19px;
  text-align: center;
  position: relative;
  top: 4px;
  cursor: pointer;
  left: 17px;
  text-transform: uppercase;
}
.info {
  font-size: 13px;
}
.modal-title {
    margin-bottom: 0;
    line-height: 1.5;
    font-size: 21px;
}
i.fas.fa-search.fa-2x {
    position: absolute;
    top: 32px;
     left: 35px;
}
span.pl-2.whp {
    font-size: 23px;
    font-weight: 600;
    position: relative;
    left: 14px;
}
span.f-tachometer {
    position: absolute;
    top: 144px;
    left: 35px;
}
span.f-phone {
    position: absolute;
    left: 35px;
    top: 264px;
}
.footer-distributed {
  background-color: #2992b8;
  box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
  box-sizing: border-box;
  width: 100%;
  text-align: left;
  font: normal 16px sans-serif;
   padding: 32px 32px;
  margin-top: 66px;
}

.footer-distributed .footer-left p {
  color: #fff;
  font-size: 14px;
  margin: 0;
  padding-left: 5px;
}
/* Footer links */
.footer-distributed p.footer-links {
 font-size: 14px;
  font-weight: bold;
  color: #ffffff;
  margin: 0 0 10px;
  padding: 0;
  transition: ease .25s;
}

.footer-distributed p.footer-links a {
  display: inline-block;
  line-height: 1.8;
  text-decoration: none;
  color: inherit;
  transition: ease .25s;
}

.footer-distributed .footer-links a:before {
  content: "";
  font-size: 20px;
  left: 0;
  color: #fff;
  display: inline-block;
  padding-right: 5px;
}

.footer-distributed .footer-links .link-1:before {
  content: none;
}

.footer-distributed .footer-right {
  float: right;
  margin-top: 6px;
  max-width: 180px;
}


.footer-distributed .footer-right a:hover{transform:scale(1.1); -webkit-transform:scale(1.1);}

.footer-distributed p.footer-links a:hover{text-decoration:underline;}

/* Media Queries */

@media (max-width: 600px) {
  .footer-distributed .footer-left, .footer-distributed .footer-right {
    text-align: center;
  }
  .footer-distributed .footer-right {
    float: none;
    margin: 0 auto 20px;
  }
  .footer-distributed .footer-left p.footer-links {
    line-height: 1.8;
  }

}
.text-muted {
    color: #9ea1a3 !important;
    font-size: 12px;
    padding-top: 24px;
}
.fa-windows {
    font-size: 2em;
    position: absolute;
    top: -11px;
    left: 151px;
}

/* .shake {
  animation: shake 2s linear infinite;
}

@keyframes shake {
  0%, 7% {
    transform: rotateZ(0);
  
  }
  15% {
    transform: rotateZ(-15deg);

  }
  20% {
    transform: rotateZ(10deg);

  }
  25% {
    transform: rotateZ(-10deg);
  }
  30% {
    transform: rotateZ(6deg);
  }
  35% {
    transform: rotateZ(-4deg);
  }
  40%, 100% {
    transform: rotateZ(0);
  }
} */

/* #search {
  animation: rotation 2s infinite linear;
}
@keyframes rotation {
    from {
				-webkit-transform: rotate(0deg);
		}
		to {
				-webkit-transform: rotate(359deg);
		}
} */

</style>