<template>
<div >
  <div >
    <b-row class="main d-flex">

      <!--First Column  -->

      <b-col col="12" class="image-section">
        <!-- <b-img src="~/assets/images/new-bg.jpg" class="big-daddy-image" alt="Responsive image"></b-img> -->
        
        <div class="d-flex justify-content-center flex-wrap pb-3 mx-auto team-logos ">
         <b-img src="~/assets/images/ipl_logo/MI.png" fluid width="150px"></b-img> 
         <b-img src="~/assets/images/ipl_logo/CSK.png" fluid width="150px"></b-img> 
         <b-img src="~/assets/images/ipl_logo/KKR.png" fluid width="150px"></b-img> 
         <b-img src="~/assets/images/ipl_logo/SRH.png" fluid width="150px"></b-img> 
         <b-img src="~/assets/images/ipl_logo/DC.png" fluid width="150px"></b-img> 
         <b-img src="~/assets/images/ipl_logo/KXIP.png" fluid width="150px"></b-img> 
         <b-img src="~/assets/images/ipl_logo/RR.png" fluid width="150px"></b-img> 
         <b-img src="~/assets/images/ipl_logo/RCB.png" fluid width="150px"></b-img> 
        </div>
      </b-col>
      <!-- Second Column-->
      <b-col sm="5" class="pt-5 sign-up ">
        
        <div class="pt-2 pb-4">
        <p>Sign and get up a <span class="inr">100%</span> bonus <br> on first deposit.
        </p>
        </div>
        <div class="form-input mx-auto pt-2">
         <b-form-input v-model="text" placeholder="Email" class="input"></b-form-input>
        </div>
        <div>
          <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted" 
          unchecked-value="not_accepted" class="checkbox mx-auto pt-4"
           >
          I am over 18 years old and I accept the <a class="link" href="https://docs.google.com/document/d/16tAxnbr5gFWT78KkjlbnE6A7FjaDfQRX1im9sciDzzs/edit">
           agreement with offer contract for the chosen currency</a>
          </b-form-checkbox>
        </div>
        <div class="pt-10 pb-10">
          <b-button  class="btn">SIGN UP</b-button>
        </div>
      </b-col>
    </b-row>
    <b-row >
      <b-col>
        <b-row class="d-flex justify-content-center footer ">
      <b-col  >
        <div class="foot-icon">
        <img src="~/assets/images/odds.png" alt="live stream">
       <span class="foot-text text-white pl-3"> Best odds in the market</span> 
        </div> 
      </b-col>
      <b-col>
        <div class="foot-icon">
        <img src="~/assets/images/bonus.png" alt="live stream">
        <span class="foot-text text-white pl-3"> Referral bonus </span> 
        </div>
      </b-col>
      <b-col>
        <div class="foot-icon">
        <img src="~/assets/images/Instant-withdrawals.png" alt="live stream">
        <span class="foot-text text-white pl-3"> Instant payouts </span> 
        </div> 
      </b-col>
    </b-row>
      </b-col>
    </b-row>
    
  </div>
</div>
</template>

<script>
export default {}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&display=swap');


.main{
background-color: #000;
  
}
.image-section{
  
 background-image: url(~/assets/images/new-bg.jpg);
 background-repeat: no-repeat;
 background-size: cover;

}

.image-text{
  font-family: 'Lato';
  font-size: 38px;
  font-weight: 900;
  color: #f36c21; 
  background:linear-gradient(to right,#e9bd2c , orange) ;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height: 1.4;
}

.span-text{
  z-index: 1;
  font-family: 'Lato';
  font-weight: 300;
  font-size: 26px;
}
.date-block{
  font-family: 'Lato';
  font-size: 22px;
  background-image: linear-gradient(to right, #f3b239 , #f36c21);
  width:40%;
   padding: 10px 40px 10px 40px;
   border-radius: 5px;
}
@media (max-width:810px) {
  .date-block{
    width:65%;
  }
}
.yellow-text{
  margin: 0 auto;
  padding-top:10rem;
  font-family: 'Lato';
  font-size:48px;
  font-weight: 700;
  text-align: left;
  color:rgb(255, 255, 107);
  line-height: 1.5;

}
.hr-item{
    width: 100%;
    height: 1px;
    background: #fff;
    border-radius: 10px;
    box-shadow: 0 0 20px #f8ff13;
}
.features{
  padding-top: 50px;
  color: #fff;
  font-family: 'Lato';
  font-size: 14px;
  font-weight: 400;
}
.container {
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.sign-up{
  /* background-color: #9b4a1d;
   */
   background-image: url(~/assets/images/orange-bg.jpg);
   background-size: cover;
  color: #fff;
  text-align: center;
  font-size:29px;
  font-weight: 300;
  font-family:'Lato'; 
}
.yellow{
  font-size: 34px;
  font-weight: 800;
  color: yellow;
}
.inr{
  font-size: 34px;
  font-weight: 800;
}
.form-input{
  width: 75%;
  text-align: center;
  
}
.input{
  background: rgba(255,255,255,.1);
  border:1px solid transparent;
  color: #fff;
  font-size: 14px;
  padding: 25px 24px 25px 24px;
}
.input::placeholder{
  color:#000;
}
.checkbox{
  font-size: 12px;
  font-family:'Lato'; 
  color: #fff;
   width: 75%;
   text-align: left;
}
.link{
  color: #fff;
  text-decoration: underline;
}
.btn{
  background-color: #000;
  color: #fff;
  font-size: 16px;
  font-weight: 700;
  border: 1px solid transparent;
  padding: 10px 60px 10px 60px;
}
.pt-10{
  padding-top: 7rem;
}
.team-logos{
  /* position: absolute;
  bottom : 70px;
  left: 100px; */
  padding-top: 20.6rem;
  width: 75%;
}

.pb-10{
  padding-bottom: 9rem;
}
.footer{
  position:absolute;
  top: -5px;
  left: 0;
  right: 0;
  padding: 20px ;
  text-align: center;
  background-color: #000;
}
.foot-text{
  font-family: 'Lato';
  font-size:18px;
  font-weight:400;
}
</style>
