<template>
<div >
  <div >
    <b-row class="main">

      <!--First Column-->

      <b-col class="image-section">
        <b-row>
          <b-col>
            image
          </b-col>
          <b-col sm="6" >
            <div class="yellow-text pb-3">
            Check your <br> luck and <br> intelligence!
            </div>
            <hr class="hr-item">
           <b-row >
            <b-col>
              <div class="features">
              <p>Customer Support</p>
              </div>
            </b-col>
            <b-col>
              <div class="features">
              <p>Big Prize</p>
              </div>
            </b-col>
            <b-col>
              <div class="features">
              <p>Quick <br> Withdrawls</p>
              </div>
            </b-col>
          </b-row>
          </b-col>
        </b-row>
      </b-col>
      <!-- Second Column-->
      <b-col sm="5" class="pt-5 sign-up">
        <div class="mt-2 mb-5">
        <p>Sign and get up to <br> 
         <span class="inr">INR</span> <span class="yellow">8000</span> bonus
        </p>
        </div>
        <div class="form-input mx-auto pt-5">
         <b-form-input v-model="text" placeholder="Email" class="input "></b-form-input>
        </div>
        <div>
          <b-form-checkbox id="checkbox-1" v-model="status" name="checkbox-1" value="accepted" 
          unchecked-value="not_accepted" class="checkbox mx-auto pt-4"
           >
          I am over 18 years old and I accept the <a class="link" href="https://docs.google.com/document/d/16tAxnbr5gFWT78KkjlbnE6A7FjaDfQRX1im9sciDzzs/edit">
           agreement with offer contract for the chosen currency</a>
          </b-form-checkbox>
        </div>
        <div class="pt-10">
          <b-button  class="btn">SIGN UP</b-button>
        </div>
      </b-col>
    </b-row>
    <b-row class="d-flex footer">
      <b-col>
        Join for free <br> Sign up to play free.
      </b-col>
      <b-col>
        Get the bonus <br> Upto INR 8000.
      </b-col>
      <b-col>
        Win the prizes  
      </b-col>
    </b-row>
  </div>
</div>
</template>

<script>
export default {}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&display=swap');


.main{
  height: calc(100vh - 95px);
}
.image-section{
  background-color: rgb(56, 148, 3);
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
  background-color: rgb(49, 3, 2);
  color: #fff;
  text-align: center;
  font-size:26px;
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
  font-size: 12px;
  padding: 25px 24px 25px 24px;
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
  background-color: yellow;
  color: #000;
  font-size: 16px;
  font-weight: 700;
  border: 1px solid transparent;
  padding: 10px 60px 10px 60px;
}
.pt-10{
  padding-top: 7rem;
}
.footer{
  padding: 10px ;
  text-align: center;
  background-color: #fff;
}
</style>
