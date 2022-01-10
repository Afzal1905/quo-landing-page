<template>
  <div>
    <div>
    <header>
      <v-container 
      class="container">
      <v-layout xs12 row class="row">
        <v-flex  md2 class=" quo quo1">
          <h1 class="logo--text">Quo.</h1>
        </v-flex>
        <v-flex md3 class="quo quo2">

        </v-flex>
        <v-flex md5 class="quo quo3">
          <ul class="ull"> <!--// v-for="ul in menu" :key="ul.id"
            <li>{{ul.title}}</li> -->
            <li>Money Transfer</li>
            <li>Multi Currency</li>
            <li>How it works</li>
            <li>Business</li>
            <li>Help</li>
          </ul>
          <select id="menu" class="ul--menu">
            <option value="Money Transfer">Money Transfer</option>
            <option value="Multi Currency">Multi Currency</option>
            <option value="How it works">How it works</option>
            <option value="Business">Business</option>
            <option value="Help">Help</option>
          </select>
  
        </v-flex>
        <v-flex md2 class="quo quo3 loginnn">
          <ul>
            <li>Log In</li>
            <label>
              <input type="checkbox">
              <span class="check"></span>
            </label>
          </ul>
        </v-flex>
      </v-layout>
    </v-container>
    </header>
    <section class="section__play">
      <v-container class="play__container">
        <h1 class="play--section--text">Experience the easier way <br> for transaction</h1>
        <p>Quo is the most easier way for transaction with your friends and family, now matter where are you. <br>
                    An exceptional way for make your life one step easier</p>
        <button class="play--section--button">
          <!-- <p> <img width="80%" src="" alt=""></p> -->
          <p id="play--section--text">See how we works</p>
        </button>
      </v-container>
    </section>
    <section class="section__table">
      <v-container class="table__container" container>
        <v-layout xs12 row class="table__row">
          <v-flex  md5 class="flexbox">
            <div class="balance--table balance--1">
              <p>Balance stats</p>
              <h3>$45,450.00</h3>
              <img class="table--img" src="../assets/Group 5.png" alt="">
            </div>
            <div class="small-table small-table--1">
              <img src="../assets/Group2.png" alt="">
            </div>
          </v-flex>
          <v-flex  xl12 md2 class="bg--col">
          </v-flex>
          <v-flex  md5 class="flexbox">
            <div class="balance--table balance--2">
              <p>Spendings</p>
              <img class="table--img" src="../assets/Group.png" alt="">
            </div>
            <div class="small-table small-table--2">
              <img src="../assets/Group3.png" alt="">
            </div>
          </v-flex>
        </v-layout>
      </v-container>
    </section>
    <section class="section__trusted">
      <v-container class="trusted__container">
        <h1 class="trusted--text" style="text-align:center;">Trusted  By</h1>
        <v-layout class="trusted__row" xs12 row style="text-align:center; justifity-content:space-between;">
          <v-flex  md1></v-flex>
          <v-flex  md2 class="logos">
            <img src="../assets/google-logo.png" alt="">
          </v-flex>
          <v-flex  md2 class="logos">
            <img src="../assets/5cb480b85f1b6d3fbadece78 1.png" alt="" style="height:60px;">
          </v-flex>
          <v-flex md2 class="logos">
            <img src="../assets/amazon-logo.png" alt="" style="height:80px;">
          </v-flex>
          <v-flex md2 class="logos">
            <img src="../assets/Dropbox_logo 1.png" alt="" style="height:50px;">
          </v-flex>
          <v-flex md2 class="logos">
            <img src="../assets/Microsoft-Logo-PNG 1.png" alt="" style="height:60px;">
          </v-flex>
          <v-flex md1></v-flex>
        </v-layout>
      </v-container>
    </section>
    <section class="section__real realll">
      <v-container class="real__container">
        <v-layout xs12 row class="real__row">
          <v-flex  md6 class="col--real">
            <h1>Real time currency check   <br>
              and easier tracking system</h1>
              <p>Quo is the most easier way for transaction with your friends and family, 
                  No matter where are you. An exceptional way for make your life one step easier.
                  Quo is the most easier way for transaction with your friends and family, </p>
              <button class="button--real">Explore Now &rarr;</button>
          </v-flex>
          <v-flex md6 class="col--real--2">
            <div class="flag--1"><img src="../assets/9hscw2oc-900 1.png" alt=""></div>
            <div class="flag--2">
              <div>
                <v-flex class="money--ul money--ul--1">
                <span>Send money</span>
              </v-flex>
              <v-flex class="money--ul money--ul--2">
                <span>Track Money</span>
              </v-flex>
              </div>
              <div class="you--send">
                <p>You send</p>
              </div>
              <div class="send--row">
                <div class="send">
                  <p>100</p>
                </div>
                <div class="send send--2">
                    <img src="../assets/1280px-Flag_of_the_United_States 1.png" alt="">
                    <span>USD</span>
                </div>
              </div>
              <div class="you--send">
                <p>Reciver will get</p>
              </div>
              <div class="send--row">
                <div class="send">
                  <p>74.58</p>
                </div>
                <div class="send send--2">
                    <img src="../assets/640px-Flag_of_the_United_Kingdom 1.png" alt="">
                    <span>GBP</span>
                </div>
              </div>
              <img class="emoji--hand" src="../assets/emoji-hands1.png" alt="">
            </div>
          </v-flex>
        </v-layout>
      </v-container>
    </section>
    <section class="section__works">
          <h1 class="trusted--text" 
          style="
          text-align:center; 
          margin-bottom:16px ">
            How Quo works?</h1>
          <p 
          style="text-align:center; 
          color:#0A021380;  
          margin-bottom:160px ">
            Quo is the most easier way for 
            transaction with your friends and family,  <br>
            No matter where are you.
            An exceptional way for make
            your life one step easier</p>
      <v-container 
      class="works__container" 
      style="
      justifity-content:space-between;">
        <v-layout class="works__row" row xs12>
          <v-flex class="cards"  md3 style="justifity-content:space-between; text-align:center;">
            <div  class="card--image" style="width:42%; padding: 16px; ">
              <img width="60%" src="../assets/cards--image.png" alt="">
            </div>
              <h2>Create accont</h2>
              <p>Create free account for your transaction. 
                It’s pretty much easier and don’t worry we care 
                about your safety</p>
          </v-flex>
          <v-flex class="cards"  md3 style="justifity-content:space-between; text-align:center;">
            <div  class="card--image" style="width:42%; padding: 16px; ">
              <img width="60%" src="../assets/cardimage2.png" alt="">
            </div>
              <h2>Enter Recipent Info</h2>
              <p>Create free account for your transaction. 
                It’s pretty much easier and don’t worry we care 
                about your safety</p>
          </v-flex>
          <v-flex class="cards"  md3 style="justifity-content:space-between; text-align:center;">
            <div  class="card--image" style="width:42%; padding: 16px; ">
              <img width="60%" src="../assets/cardimage3.png" alt="">
            </div>
              <h2>Send money</h2>
              <p>Create free account for your transaction. 
                It’s pretty much easier and don’t worry we care 
                about your safety</p>
          </v-flex>
        </v-layout>
      </v-container>
    </section>
    <section class="section__features  section__real">
      <v-container class="features__container  real__container" style="margin-top:50px">
        <h1 style="text-align:center;font-size: 40px; font-weight: 700;">Worthy features that you will love</h1>
        <v-layout class="features__row real__row" style="margin-top:50px" xs12>
          <v-flex md6 class="col--real">
            <h1>Capable for taking  <br>
              multiple cards at one place</h1>
              <p>Quo is the most easier way for transaction with your friends and family, 
                  No matter where are you. An exceptional way for make your life one step easier.
                  Quo is the most easier way for transaction with your friends and family, </p>
              <button class="button--real">Learn How &rarr;</button>
          </v-flex>
          <v-flex md6 class="col--real--2">
            <img src="../assets/Group 16.png" class="images--feature"  id="feature--image" alt="">
            <img class="images--feature images--feature--2" src="../assets/Group 15.png" alt="">
          </v-flex>
        </v-layout>
      </v-container>
    </section>
    <section class="section__map">
      <v-container  class="map__container">
        <h1 style="color:white; font-size :48px; font-weight:700; text-align:center;">Widely covering these countries</h1>
        <p style="color:white; text-align:center;">Quo is the most easier way for transaction with your friends and family, No matter where are you. <br>
        An exceptional way for make your life one step easier.Quo is the most easier way for transaction with your friends and family, </p>
        <v-layout class="map__row" row xs12>
          <div class="place place--1">
            <div class="location"><img src="../assets/Ellipse 23.png" alt=""></div>
            <div class="location location--2">
              <img src="../assets/1280px-Flag_of_the_United_States 2.png" alt="">
              <span>UK</span>
            </div>
          </div>
          <div class="place place--2">
            <div class="location"><img src="../assets/Ellipse 23.png" alt=""></div>
            <div class="location location--2">
              <img src="../assets/1280px-Flag_of_the_chili 2.png" alt="">
              <span>Chile</span>
            </div>
          </div>
          <div class="place place--3">
            <div class="location"><img src="../assets/Ellipse 23.png" alt=""></div>
            <div class="location location--2">
              <img src="../assets/1280px-Flag_of_the_kanada2.png" alt="">
              <span>Kanada</span>
            </div>
          </div>
          <div class="place place--4">
            <div class="location"><img src="../assets/Ellipse 23.png" alt=""></div>
            <div class="location location--2">
              <img src="../assets/1280px-Flag_of_the_Usa.png" alt="">
              <span>USA</span>
            </div>
          </div>
          <div class="place place--5">
            <div class="location"><img src="../assets/Ellipse 23.png" alt=""></div>
            <div class="location location--2">
              <img src="../assets/1280px-Flag_of_the_sveden 2.png" alt="">
              <span>Sweden</span>
            </div>
          </div>
          <div class="place place--6">
            <div class="location"><img src="../assets/Ellipse 23.png" alt=""></div>
            <div class="location location--2">
              <img src="../assets/1280px-Flag_of_the_Thaialnd.png" alt="">
              <span>Thailand</span>
            </div>
          </div>
          <div class="place place--7">
            <div class="location"><img src="../assets/Ellipse 23.png" alt=""></div>
            <div class="location location--2">
              <img src="../assets/1280px-Flag_of_the_Colombia.png" alt="">
              <span>Colombia</span>
            </div>
          </div>
          <div class="place place--8">
            <div class="location"><img src="../assets/Ellipse 23.png" alt=""></div>
            <div class="location location--2">
              <img src="../assets/1280px-Flag_of_theRussia.png" alt="">
              <span>Russia</span>
            </div>
          </div>
        </v-layout>
      </v-container>
    </section>
    <section class="section__phone">
      <v-container class="phone__container">
        <v-layout class="phone__row" row xs12>
          <v-flex class="flexboard--1" md 6>
            <img class="flexboard--img--1" src="../assets/rfdbx632-900 1.png" alt="">
            <img class="flexboard--img--2" src="../assets/giphy_s 1.png" alt="">
          </v-flex>
          <v-flex class="flexboard" md 6>
            <h1 style="font-size: 40px; font-weight: 600; margin-bottom: 30px">Satisfied peoples saying <br>
              about Quo!</h1>
            <p style="font-size:16px; color:#0A0213; font-weight: 300; margin-bottom: 30px;">
              Quo is the most easier way for transaction with your friends and family,  <br><br>
              No matter where are you. An exceptional way for make your life one step easier.<br><br>
              Quo is the most easier way for transaction with your friends and family, 
            </p>
            <p style="font-size: 20px; margin-bottom:20px">Amanda Smith</p>
            <p style="font-size: 16px; margin-bottom:20px; color: #0000004D;">CEO, Amazon </p>
            <div class="icons">
              <img src="../assets/Vector1.png" alt="">
              <img src="../assets/Vector2.png" alt="">
            </div>
          </v-flex>
        </v-layout>
      </v-container>
    </section>
    <section class="section__email">
      <v-container class="email__container">
          <h1>Get connect with Quo <br>
            and enjoy a new Experience</h1>
             <input class="input" type="text" id="email" name="email" placeholder="Enter your mail here">
              <input class="subscribe--input" type="submit" value="Subscribe">
      </v-container>
    </section>
    <footer class="footer">
      <v-container class="footer__container">
        <v-layout class="footer__row" row xs12>
          <v-flex class="footer--flex" md3>
            <h1 style="color:#6C60FE; font-size:40px; font-weight:500; margin-bottom: 16px"> Quo.</h1>
            <p style="color:#0A021380;margin-bottom: 16px">Quo is the most easier way for transaction 
            with your friends and family, No matter where are you. 
            An exceptional way for make your life one step easier.</p>
            <img src="../assets/Path.png" alt="">
            <img src="../assets/Path2.png" alt="">
            <img src="../assets/004-instagram.png" alt="">
          </v-flex>
          <v-flex class="footer--flex" md3>
            <p>Company</p>
            <p style="color:#0A021380;">About Us</p>
            <p style="color:#0A021380;">Contact Us</p>
            <p style="color:#0A021380;">Support</p>
            <p style="color:#0A021380;">News/Blog</p>
          </v-flex>
          <v-flex class="footer--flex" md3>
            <p>Terms</p>
            <p style="color:#0A021380;">Privacy Policy</p>
            <p style="color:#0A021380;">Terms of Usage</p>
            <p style="color:#0A021380;">Areas of coverage</p>
          </v-flex>
          <v-flex class="footer--flex" md3>
            <p>Contact</p>
            <p style="color:#0A021380;">84/E/2  West Jafrabad, <br> Liverpool, Uk</p>
            <p style="color:#0A021380;">+8801757410907</p>
          </v-flex>
        </v-layout>
      </v-container>
    </footer>
    <section class="footer--2">
      <p>@ - 2020 . Made with. by Antor Paul</p>
    </section>
      </div>
    </div>
  
</template>

<script>
  export default {
    name: 'Home',
    data(){
      return{
        color: 'red',
        menu:[
          {id:1, title:'Money Transfer'},
          {id:2, title:'Multi Currency'},
          {id:3, title:'How it works'},
          {id:4, title:'Business'},
          {id:5, title:'Help'},
        ]
      }
    },
    methods:{
      hoverIn(){
        this.color = 'red'
      }
    }
  }
</script>  
<style lang="scss" scoped>

   input[type="checkbox"]{
    -webkit-appearance: none;
    visibility: hidden;
    display: none;
  }
  
  label{
    float: right;
    position: absolute;
  }
  .check{
    position: relative;
    display: block;
    width: 40px;
    height: 20px;
    background: #092c3e;
    cursor: pointer;
    border-radius: 20px;
    overflow: hidden;
    transition: ease-in 0.5s;
  }
  input[type="checkbox"]:checked ~ .check{
    background: #fff;
    box-shadow: 0 0 0 20000px pink;
    z-index: -4;
  }
  .check:before{
    content: '';
    position: absolute;
    top: 2px;
    right: 2px;
    background: white;
    width: 16px;
    height: 16px;
    border-radius: 50%;
    transition: 0.5s;
    transform: translate(0px);
  }
  input[type="checkbox"]:checked ~ .check:before{
    transform: translate(-50px);
  }
  .check:after{
    content: '';
    position: absolute;
    top: 2px;
    right: 2px;
    background: #092c3e;
    width: 16px;
    height: 16px;
    border-radius: 50%;
    transition: 0.5s;
    transform: translate(50px);
  }
  input[type="checkbox"]:checked ~ .check:after{
    transform: translate(0px);
  }
  *{
    padding: .2rem;
  }
  .container .row .quo .logo--text{
    color: #6C60FE;
  }
  
  .container .row .quo3 ul li{
    list-style-type: none;
    display: inline-block;
    margin-right: 12px;
    color: #0A0213;
  }
  .container .row .quo3 .ul--menu{
    display: none;
  }
  .container .row .quo3 ul li:hover{
    color: black;
    border-bottom: 1px slid black;
    cursor: pointer;
  }
  .container .row .quo3 ul  button{
    color: white;
    background-color: #6C60FE;
    justify-content: space-between;
    text-align: center;
    border-radius: 6px;
    width: 80px;
    height: 24px;
  }
  .container .row .quo3 ul  button:hover{
    color: white;
    background-color: darkblue;
    box-shadow: rgba(0, 0, 0, 0.45) 0px 25px 20px -20px!important;
  }
  // 2chi section
  .section__play{
    margin-top: 50px;
  }
  .section__play .play__container {
    border-radius: 30px;
    background-color: #6C60FE0D;
    text-align: center;

  }
  .section__play .play__container  .play--section--text{
    text-align: center!important;
    font-size: 56px!important;
    margin-top: 24px;
    color: #09053F;
    margin-bottom: 16px;
  }
  .section__play .play__container  .play--section--button{
    color: white;
    background-color: #6C60FE;
    justify-content: space-between;
    text-align: center;
    border-radius: 19px;
    margin-top: 20px;
    margin-bottom: 80px;
  }
  .section__play .play__container  .play--section--button:hover{
    color: white;
    background-color: #6C60FE;
    background-color: darkblue;
    box-shadow: rgba(0, 0, 0, 0.45) 0px 25px 20px -20px!important;
  }
  .section__play .play__container  .play--section--button p{
    padding: 10px;
    display: inline-block;
  }
  .section__play .play__container  .play--section--button #play--section--text{
    display: inline-block;
  }
  //3chi section
  .section__table {
    margin-bottom: 350px;
  }
  .section__table .table__container {
    height: 60vh;
    position: relative;
  }
  .section__table .table__container .table__row .flexbox .balance--table{
    width: 50%;
    border-radius: 6px;
    box-shadow: 2px 2px 2px 2px #f1f1f1;
    background-color: white;
  }
  .section__table .table__container .table__row .flexbox .balance--table:hover{
    box-shadow: 2px 2px 2px 2px #777;
    cursor: pointer; 
    background-color: #f1f1f1;
  }
  .section__table .table__container .table__row .flexbox .balance--table .table--img{
    width: 100%;
  }
  .section__table .table__container .table__row .flexbox .balance--1{
    transform: translate(55%, 90%);
  }
  .section__table .table__container .table__row .flexbox .balance--2{
    transform: translate(25%, 120%);
  }
  .section__table .table__container .table__row .flexbox .small-table{
    width: 15%;
    background-color: #EFFFF8;
    border-radius: 4px;
    position: relative;
  }
  .section__table .table__container .table__row .flexbox .small-table:hover{
    box-shadow: 2px 2px 2px 2px #f1f1f1;
    cursor: pointer;
  }
  .section__table .table__container .table__row .flexbox .small-table img{
    width: 100%;
  }
  .section__table .table__container .table__row .flexbox .small-table--1{
    transform: translate(260%, 300%)!important;
    -ms-transform: rotate(20deg)!important; /* IE 9 */
  }
  .section__table .table__container .table__row .flexbox .small-table--2{
    transform: translate(200%, -180%)!important;
    -ms-transform: rotate(20deg)!important; /* IE 9 */
  }
  .section__table .table__container .table__row{
    background-image: url("../assets/opanirasmi.png");
    background-size: 50%;
    height: 100vh;
    background-position-x: 45%;
    margin-bottom: 50px;
  }
  ///3
  .section__trusted{
    position: relative;
    margin-bottom: 20px;
  }
  .section__trusted .trusted__container  .trusted__row{
    margin-top: 20px;
  }
  .section__trusted .trusted__container  .trusted__row .logos img {
    width: 80%;
  }
  //4chi section
  .section__real{
    margin-bottom: 30vh;
  }
  .section__real .real__container .real__row .col--real h1{
    font-size: 48px;
    font-weight: 500;
    margin-bottom: 10px;
  }
  .section__real .real__container .real__row .col--real p{
    font-size: 16px;
    font-weight: 400;
    margin-bottom: 20px;
    color: #0A021380;
  }
  .section__real .real__container .real__row .col--real .button--real{
    background-color: #F6F6F9;
    padding: 10px;
    border-radius: 6px;
  }
  .section__real .real__container .real__row .col--real .button--real:hover{
    background-color: #777;
    color: white;
    box-shadow: 0 2px 2px 2px #7777;
  }
  .section__real .real__container .real__row .col--real--2 .flag--1{
    float: right;
    width: 50%;
    height: 250px;
    border-radius: 8px;
    background-color: #F6F6F9;
  }
  .section__real .real__container .real__row .col--real--2 .flag--1 img{
    width: 40%;
    float: right;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2{
    float: right;
    width: 50%;
    height: 250px;
    border-radius: 8px;
    box-shadow: 0 5px 5px 5px #F6F6F9;
    transform: translate(70%,40%);
    background-color: white;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2:hover{
    box-shadow: 0 5px 5px 5px #777;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2 .money--ul{
    width: 50%;
    text-align: center;
    color: #031B71;
    padding: 16px;
    display: inline-block;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2 .money--ul:hover{
    border-bottom: 3px solid #031B71;
    cursor: pointer;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2 .send--row{
    width: 80%;
    margin: 0 auto;
    background-color: #F8FAFF;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2 .you--send {
    padding: 10px!important;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2 .send--row .send{
    display: inline-block;
    padding: 4px;
    justify-content: space-between;
    // margin-bottom: 16px;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2 .send--row .send--2{
    width: 40%;
    background-color: #3B32A6;
    float: right;
    color: white;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2 .send--row .send--2 img{
    width: 43%;
    height: 100%;
  }
  .section__real .real__container .real__row .col--real--2 .flag--2 .emoji--hand{
    width: 35%;
    transform: translate(-60%,-20%);
  }
  // 6chi section
  .section__works .works__container {
    width: 100%;
    height: 45vh;
    background-color: #F5F5FD80;
  }
  .section__works .works__container .works__row .cards{
    margin-left: 32px;
    padding: 32px;
    justify-content: space-between!important;
    text-align: center;
    width: 80%;
    margin: 0 auto;
    height: 48vh;
    background-color: white;
    position: relative;
    margin-top: -10vh;
    box-shadow: 0px 0px 10px 8px #F5F5FD80 !important;
  }
  .section__works .works__container .works__row .cards .card--image{
    background-color: #F5F5FD80;
    justify-content: space-between;
    border-radius: 100%;
    margin-bottom: 16px;
    margin: 16px auto;
  }
  .section__works .works__container .works__row .cards h2{
    margin-bottom: 16px;
    
  }
  .section__works .works__container .works__row .cards p{
    color: #0A021380;
  }
  ///7chi section
  .section__real .real__container .real__row .col--real--2 .images--feature{
    float: right;
    width: 55%;
  }
  .section__real .real__container .real__row .col--real--2 #feature--image:hover{
    z-index: s4;
  }
  .section__real .real__container .real__row .col--real--2 .images--feature--2{
    position: relative;
    transform: translate(-40%, -50%);
  }
  //8chi section
  .section__map{
    margin-bottom: 100px;
  }
  .section__map{
    height: 130vh;
    background-image: url("../assets/Group 22.png");
    background-color: #2D23A5;
    background-size: 80%;
    background-position-x: 120px;
    background-position-y: 200px;
  }
  .section__map .map__container .map__row .place--1{
    // transform: translate(300%, 200%);
    margin-left: 40%;
    margin-top: 10%;
  }
  .section__map .map__container .map__row .place--2{
    // transform: translate(7%, 440%);
    margin-left: 13%;
    margin-top: 14.5%;
    position: absolute;
  }
  .section__map .map__container .map__row .place--3{
    // transform: translate(80%, 640%);
    margin-left: 30%;
    margin-top: 20%;
    position: absolute;
  }
  .section__map .map__container .map__row .place--4{
    // transform: translate(130%, 540%);
    margin-left: 50%;
    margin-top: 15%;
    position: absolute;
  }
  .section__map .map__container .map__row .place--5{
    // transform: translate(290%, 640%);
    margin-left: 65%;
    margin-top: 18%;
    position: absolute;
  }
  .section__map .map__container .map__row .place--6{
    // transform: translate(-410%, 740%);
    margin-left: 5%;
    margin-top: 23%;
    position: absolute;
  }
  .section__map .map__container .map__row .place--7{
    // transform: translate(-430%, 1040%);
    margin-left: 40%;
    margin-top: 34%;
    position: absolute;
  }
  .section__map .map__container .map__row .place--8{
    // transform: translate(-330%, 1140%);
    margin-left: 55%;
    margin-top: 30%;
    position: absolute;
  }
  .section__map .map__container .map__row .place .location{
    display: inline-block;
  }
  .section__map .map__container .map__row .place .location--2:hover{
    background-color: #f1f1f1;
    cursor: pointer;
    box-shadow: 0 0px 5px 5px #777;
  }
  .section__map .map__container .map__row .place .location--2{
    background-color: white;
    border-radius: 10px;
  }
  .section__map .map__container .map__row .place .location img{
    width: 60%;
  }
  .section__map .map__container .map__row .place .location--2 img{
    width: 40%;
  }
  .section__map .map__container .map__row .place .location--2 span{
    position: absolute;
  }
  //9chi section
  .section__phone{
    position: relative;
  }
  .section__phone .phone__container .phone__row .flexboard--1{
    background-image: url("../assets/good-looking.png");
    background-size: 50%;
    height: 80vh;
    justify-content: space-between;
    background-position-x: 100px;
  }
  .section__phone .phone__container .phone__row .flexboard--1 img{
    width: 25%;
  }
  .section__phone .phone__container .phone__row .flexboard--1 .flexboard--img--1{
    transform: translate(0, 40%);
  }
  .section__phone .phone__container .phone__row .flexboard--1 .flexboard--img--2{
    transform: translate(120%, 220%);
  }
  //10chi
  .section__email{
    margin-bottom: 150px;
  }
  .section__email .email__container{
    width: 80%;
    margin: 0 auto;
    background-color: #5045D2;
    border-radius: 16px;
    padding: 24px;
    text-align: center;
    justify-content: space-between;
  }
  .section__email .email__container h1{
    color:white; 
    text-align: center; 
    font-size:40px; 
    font-weight: 600;
    margin: 0 auto;
    margin-bottom: 30px;
  }
  .section__email .email__container .input{
    background-color: white;
    width: 200px;
    padding: 10px;
    height: 46px;
    border: 1px solid #5045D2;
    border-radius: 3px;
    border: 2px solid white;
    margin-bottom: 16px;
}
.section__email .email__container .subscribe--input{
    background-color: #5045D2;
    color: white;
    height: 46px;
    border-radius: 3px;
    position: absolute;
    border: 2px solid white;
}
.section__email .email__container .subscribe--input:hover{
    background-color: white;
    color: #5045D2;
    height: 46px;
    border-radius: 3px;
    position: absolute;
    border: 2px solid white;
}
//11chi
.footer .footer__container .footer__row .footer--flex p{
  margin-bottom: 16px;
}
.footer .footer__container .footer__row .footer--flex :hover{
  color: black;
  cursor: pointer;
  display: inline-block;
}
.footer--2{
  background-color: #5045D2;
  width: 100%;
  color: white;
  text-align: center;
  padding: 16px;
}
@media only screen and (max-width: 900px){
  .container .row .quo{
    display: inline-block;
  }
  .container .row .quo3{
    float: right;
    width: 70%;
  }
  .section__works{
    margin-top: 100px!important;
    padding: 30px;
  }
  .section__real{
    margin-bottom: 250px;
  }
  .section__works .works__container .works__row .cards{
    width: 30%;
    margin: 0;
    padding: 0;
    height: 55vh;
  }
}
@media only screen and (max-width: 600px){
  .section__map{
    background-size: 80%;
    background-position-x: 70px;
    background-position-y: 200px; 
  }
}
@media only screen and (max-width: 500px){
  .section__table .table__container .table__row .flexbox .balance--1{
    transform: translate(5%, 10%);
    width: 40%;
  }
  .container .row .quo3 .ul--menu{
    display: block;
    margin-top: 14px;
    z-index: 4;
    justify-content: space-between;
  }
  .container .row .quo3 .ull{
    display: none;
  }
  .container .row  .loginnn{
    width: 100px !important;
    float: right;
    margin-top: -38px;
    z-index: -4;
  }
  .container .row  .loginnn ul{
    float: right;
  }
  .section__table .table__container .table__row .flexbox .balance--2{
    transform: translate(180%, -30%);
    width: 35%;
  }
  .section__table .table__container .table__row .flexbox .small-table--1{
    position: absolute;
    margin-top: -30%;
    margin-left: -30%;
  }
  .section__table .table__container .table__row .flexbox .small-table--2{
    position: absolute;
    margin-top: -55%;
    margin-left: 40%;
  }
  .section__map{
    background-size: 80%;
    background-position-x: center;
    background-position-y: 240px; 
    height: 100vh;
  }
  .section__trusted .trusted__container  .trusted__row .logos img {
    width: 70%;
    justify-content: space-between;
  }
  .section__play .play__container  .play--section--text{
    font-size: 40px !important;
  }
  .section__works .works__container .works__row .cards{
    width: 60%;
    display: block;
    margin-bottom: 30px;
    height: 60vh;
  }
  .section__real{
    margin-top: 150vh;
  }
  .realll{
    margin-top: -10vh;
  }
  .section__trusted{
    margin-top: -40vh;
  }
  .section__email .email__container .input{
    margin-left: -50px;
  }
}
@media only screen and (max-width: 375px){
  .section__real .real__container .real__row .col--real h1{
    font-size: 36 px;
  }
  .section__email .email__container .input{
    margin-left: -50px;
    width: 160px;
  }
}
</style>
