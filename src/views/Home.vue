<template>
  <div class="home">
    <Navbar />
    <section class="hero">
      <div class="container">
        <div class="row">
          <div>
            <div class="hero-headings">
              <h6>PLAN YOUR LIFE</h6>
              <h1>
                Increase your <span class="h1-side"> <b>productivity</b> </span>
              </h1>
              <p>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an, insolens gubergren similique est cu. Et vel
                modus congue vituperata.
              </p>
              <div>
                <img class="play-btnn" src="../assets/play button.svg" alt="" />
              </div>
            </div>
            <div>
              <img class="stats" src="../assets/one of stats.svg" alt="" />
            </div>
            <img class="img1" src="../assets/clouds.svg" alt="" />
            <img class="img2" src="../assets/chart.svg" alt="" />
          </div>
        </div>
      </div>
    </section>
    <section class="one">
      <div>
        <img class="logos" src="../assets/bitbucket.svg" alt="" />
      </div>
      <div>
        <img class="logos" src="../assets/apple-watch.svg" alt="" />
      </div>
      <div>
        <img class="logos" src="../assets/facebook.svg" alt="" />
      </div>
      <div>
        <img class="logos" src="../assets/atlassian.svg" alt="" />
      </div>
      <div>
        <img class="logos" src="../assets/audi.svg" alt="" />
      </div>
    </section>
    <!-- Section 2  -->
    <section class="section-two">
      <div class="section-two-main">
        <div class="left-div">
          <h6>DESKTOP AND MOBILE APP</h6>
          <h1>Plan <span class="span-text">and</span> manage</h1>
          <p>
            Brute laoreet efficiendi id his, ea illum nonumes luptatum pro. Usu
            atqui laudem an, insolens gubergren similique est cu. Et vel modus
            congue vituperata. Solum patrioque no sea. Mea ex malis mollis
            oporteat. Eum an expetenda consequat.
          </p>
          <div class="">
            <p>
              <button class="btn1">
                View video <img src="../assets/Polygon.svg" alt="" />
              </button>
              <span><button class="btn2">See features</button></span>
            </p>
          </div>
        </div>
        <div class="right-div">
          <img src="../assets/illustration.png" alt="" />
        </div>
      </div>
    </section>
    <!-- Section 3  -->
    <section class="section-three">
      <section class="section-three">
        <div class="">
          <img src="../assets/clouds-left.svg" class="" alt="" />
        </div>
        <div class="section-three-body">
          <h6 class="section-three-head">ABOUT US</h6>
          <h3>Read about our app</h3>
          <div class="about-us">
            <div class="col-sm-2">
              <div class="circle">
                <div><img src="../assets/house.svg" alt="" /></div>
              </div>
              <h6>Overview</h6>
              <p>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
              </p>
            </div>
            <div class="col-sm-2">
              <div class="circle">
                <div><img src="../assets/files.svg" alt="" /></div>
              </div>
              <h6>Files</h6>
              <p>
                No vim nulla vitae intellegat. Ei enim error ius, solet atomorum
                conceptam ex has.
              </p>
            </div>
            <div class="col-sm-2">
              <div class="circle">
                <div><img src="../assets/message.svg" alt="" /></div>
              </div>
              <h6>Meeting chats</h6>
              <p>Vim ne tacimates neglegentur. Erat diceret omittam at est.</p>
            </div>
            <div class="col-sm-2">
              <div class="circle">
                <div><img src="../assets/save.svg" alt="" /></div>
              </div>
              <h6>Save events</h6>
              <p>Nisl idque mel ea, nominati voluptatum.</p>
            </div>
          </div>
          <div class="section-three-btn-div">
            <p>
              <button class="red-btn">Read more</button> <span>OR</span>
              <span><button class="btn">Get Started</button></span>
            </p>
          </div>
        </div>
        <div>
          <img src="../assets/clouds-right.svg" alt="" />
        </div>
      </section>
    </section>
    <!-- Section 4 -->
    <section class="section-four">
      <div class="div-one">
        <div class="col-sm-5">
          <div class="icon-card">
            <img src="../assets/timer.svg" alt="" />
          </div>
          <p class="number-card">89%</p>
          <p class="text-card">
            Customers who have increased their productivity
          </p>
        </div>
      </div>
      <div class="div-two">
        <div class="col-sm-5">
          <div><img src="../assets/people.svg" alt="" /></div>
          <p class="number-card2">3123</p>
          <p class="text-card2">Users who have used our application</p>
        </div>
      </div>
    </section>
    <!-- Section 5 -->
    <section class="section-five">
      <h6>OUR RESOURCES</h6>
      <h3>Start reading our blog</h3>
      <div class="blog-post-div">
        <div class="blog-image-div">
          <img src="../assets/laptop.png" alt="" class="blog-image" />
        </div>

        <div class="blog-content">
          <h4>How to start planning</h4>
          <p class="blog-text">
            Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu usu
            vidit tractatos, vero tractatos ius an, in mel diceret persecuti.
            Natum petentium principes mei ea. Tota everti periculis vis ei, quas
            tibique pro at, eos ut decore ...
          </p>
          <p>
            <button class="readnow-btn">Read now</button>
            <span class="bookmark">Add to your bookmarks</span>
          </p>
        </div>
      </div>
    </section>
    <!-- Section 6 -->
    <section class="slider-one">
      <div class="slider-one-sub">
        <carousel
          :per-page="1"
          :navigate-to="someLocalProperty"
          :mouse-drag="false"
        >
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
          <slide class="linear">
            <div class="slide-titles">
              <h1>
                TESTIMONIALS
              </h1>
              <h2>Customers's quotes</h2>
              <h3>
                Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
                Usu atqui laudem an.
              </h3>
            </div>
            <div class="mini-square">
              <p>
                Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
                usu vidit tractatos, vero tractatos ius an, in mel diceret
                persecuti.
              </p>
              <img src="../assets/man.png" alt="" />
            </div>
            <div class="slide-last">
              <div>
                <p>
                  Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam.
                  Eu usu vidit tractatos, vero tractatos ius an, in mel diceret
                  persecuti.
                </p>
              </div>
            </div>
          </slide>
        </carousel>
      </div>
    </section>
    <!-- Section 7 -->
    <section class="section-seven">
      <div class="section-seven-main">
        <h6>CUSTOMER HELP</h6>
        <h3>Frequently asked questions</h3>
        <div>
          <p>
            <span><img src="../assets/angle-down.svg" alt=""/></span> Reque
            insolens in vel?
          </p>
          <div class="line"></div>
        </div>
        <div>
          <p>
            <span><img src="../assets/angle-down.svg" alt=""/></span> Vis rebum
            error graecis ea, id sit postea accusamus?
          </p>
          <div class="line"></div>
        </div>
        <div>
          <p>
            <span><img src="../assets/angle-up.svg" alt=""/></span> Lorem
            repudiandae ne nec?
          </p>
          <div class="faq-drop-down">
            <p>
              Quidam vocibus eum ne, erat consectetuer voluptatibus ut nam. Eu
              usu vidit tractatos, vero tractatos ius an, in mel diceret
              persecuti.
              <span><button class="FAQ-btn">Go to documentation</button></span>
            </p>
          </div>
          <div class="line"></div>
        </div>
        <div>
          <p>
            <span><img src="../assets/angle-down.svg" alt=""/></span> Ad dicit
            numquam vel. Et eos iudico feugait percipitur?
          </p>
          <div class="line"></div>
        </div>
        <div>
          <p>
            <span><img src="../assets/angle-down.svg" alt=""/></span> Sea no
            dico percipitur. Fierent constituam definitiones id eum?
          </p>
          <div class="line"></div>
        </div>
      </div>
    </section>
    <!-- Section 8 -->
    <section class="section-eight">
      <div class="plan-your-life">
        <div class="left-blue-clouds">
          <img src="../assets/get_clouds_left.svg" alt="" />
        </div>
        <div class="central_blue_area">
          <div class="blue-headings">
            <h6>PLAN YOUR LIFE</h6>
            <h1>Get <span class="started"> Started</span> now</h1>
            <p>
              Brute laoreet efficiendi id his, ea illum nonumes luptatum pro.
              Usu atqui laudem an, insolens gubergren similique est cu. Et vel
              modus congue vituperata.
            </p>
            <div class="plan-life-btns">
              <button class="plan-life-btn1">views Pricing</button
              ><span class="plan-life-btn2"> Read documentation</span>
            </div>
          </div>
        </div>
        <div class="right-blue-clouds">
          <img src="../assets/get_clouds_right.svg" alt="" />
        </div>
      </div>
    </section>
    <!-- Section 9 -->
    <section class="newsletter">
      <div class="newsletter-sub">
        <div class="news-headings">
          <h1>Sign up for newsletter</h1>
          <p>
            Cu qui soleat partiendo urbanitas. Eum aperiri indoctum eu, homero
            alterum.
          </p>
        </div>
        <div class="news-btns">
          <input type="text" placeholder="Email address" />
          <button>Save me</button>
        </div>
      </div>
    </section>

    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Footer,
  },
};
</script>
<style scoped>
.hero {
  width: 100%;
  height: 570px;
  background: linear-gradient(180deg, #f4f7ff 0%, #f1f5ff 100%);
}
.play-btnn {
  margin-top: -40px;
}
.hero-headings h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  /* identical to box height */
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #3d4f9f;
}
.hero-headings h1 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 300;
  font-size: 48px;
  line-height: 60px;
  /* identical to box height */
  text-align: center;
  color: #3d4f9f;
  padding-bottom: 15px;
}
.hero-headings p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 29px;
  text-align: center;
  letter-spacing: 0.03em;
  color: #8d96bd;
  width: 502px;
  margin-left: 140px;
}
.img1 {
  width: 100%;
  height: 570px;
  position: relative;
  top: -50px;
  right: 230px;
}
.img2 {
  width: 100%;
  height: 570px;
  position: absolute;
  top: 120px;
  left: 0px;
}
.hero-headings {
  position: absolute;
  width: 50%;
  left: 370px;
  margin-top: 90px;
  text-align: center;
}
.stats {
  position: absolute;
  top: 470px;
  left: 390px;
}
.one {
  width: 100%;
  height: 146px;
  display: flex;
  align-items: center;
  justify-content: space-around;
  padding: 0px 90px 0px 90px;
}
/* Section Two start */
.section-two {
  background: #f5f8ff;
  width: 100%;
  height: 750px;
}
.section-two-main {
  display: flex;
  width: 100%;
}
.left-div {
  width: 50%;
  margin-top: 12rem;
  padding-left: 10rem;
}
.right-div {
  width: 50%;
  margin-top: 8rem;
}
.left-div h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
}
.left-div h1 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 45px;
  color: #3d4f9f;
}
.left-div p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 13px;
  line-height: 25px;
  letter-spacing: 0.03em;
  color: #8d96bd;
}
.span-text {
  color: #5f77e2;
}
.right-div {
  align-items: center;
  width: 100%;
  display: flex;
  justify-items: center;
}
.btn1 {
  width: 30%;
  height: 43px;
  background: #4c85ff;
  box-shadow: 0px 5px 15px rgba(188, 199, 255, 0.75);
  border-radius: 2px;
  color: #ffffff;
  border: 0.1px solid #4c85ff;
}
.btn2 {
  width: 30%;
  height: 43px;
  background: #f5f8ff;
  box-shadow: 0px 5px 15px rgba(188, 199, 255, 0.75);
  border-radius: 2px;
  color: #bec0c5;
  border: 1px solid #d1d1e4;
}
/* Section Three */
.section-three-body {
  margin-top: 4rem;
}
.section-three {
  width: 100%;
  height: 750px;
  background: #ffffff;
  display: flex;
}

.circle {
  width: 69px;
  height: 69px;
  background: #f1f5ff;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  padding-top: 21px;
  margin: 20px;
  margin-left: 45px;
}
.about-us {
  display: flex;
  justify-content: center;
}
.section-three {
  padding-top: 3rem;
}
.section-three-head {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
  text-align: center;
  padding: 20px;
}
.section-three h3 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 30px;
  text-align: center;
  color: #3d4f9f;
  padding: 20px;
}
.about-us h6 {
  font-family: Open Sans;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 25px;
  text-align: center;
  color: #4074f8;
}
.about-us p {
  font-family: Open Sans;
  font-style: normal;
  font-weight: 500;
  font-size: 11px;
  line-height: 19px;
  text-align: center;
  color: #adb3cb;
}
.btn {
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #3a79ff;
  width: 113px;
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
  margin-left: 30px;
}
.red-btn {
  width: 113px;
  height: 43px;
  background: #ffd7d7;
  border-radius: 2px;
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #d43f3f;
  border: none;
  margin-right: 30px;
}
.section-three-btn-div {
  display: flex;
  justify-content: center;
  margin-top: 8rem;
}
/* Section four */
.section-four {
  display: flex;
}
.text-card {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 23px;
  letter-spacing: 0.03em;
  text-indent: 55px;
}

.text-card2 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 23px;
  letter-spacing: 0.03em;
}
.div-one {
  width: 50%;
  height: 342px;
  background: linear-gradient(229.32deg, #6888ff 12.77%, #5e80ff 73.11%);
  color: #ffffff;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
.div-two {
  width: 50%;
  height: 342px;
  background: linear-gradient(101.48deg, #e9efff 41.56%, #e0e9ff 81.53%);
  color: #5e80ff;
  display: flex;
  align-items: center;
}
.number-card {
  font-family: Quicksand;
  font-style: normal;
  font-weight: normal;
  font-size: 48px;
  line-height: 83px;
  letter-spacing: 0.03em;
  text-align: right;
}
.number-card2 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: normal;
  font-size: 48px;
  line-height: 83px;
  letter-spacing: 0.03em;
}
.icon-card {
  display: flex;
  justify-content: flex-end;
}
/* Section five */
.section-five {
  width: 100%;
  height: 820px;
  background: #f5f8ff;
  padding-top: 8rem;
}
.blog-post-div {
  width: 70%;
  height: 350px;
  background: #ffffff;
  border: 1px solid #d8e3fe;
  box-sizing: border-box;
  box-shadow: 0px 15px 50px #eff4ff;
  display: flex;
  margin: auto;
  justify-content: center;
}
.section-five h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
  padding: 20px;
  text-align: center;
}
.section-five h3 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 30px;
  text-align: center;
  color: #3d4f9f;
  text-align: center;
  padding: 20px;
}
.section-five h4 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: normal;
  font-size: 32px;
  line-height: 40px;
  color: #3d4f9f;
}
.blog-text {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 22px;
  letter-spacing: 0.03em;
  color: #8d96bd;
}
.readnow-btn {
  width: 113px;
  height: 43px;
  background: #d2e1ff;
  border-radius: 2px;
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #3a79ff;
  border: 0.1 px solid #d2e1ff;
}
.bookmark {
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  color: #a6b6da;
  margin-left: 10px;
}
.blog-image-div {
  width: 45%;
}
.blog-content {
  width: 45%;
  margin-top: 3rem;
}
.blog-image {
  width: 100%;
}
/* Section 6 */
.linear {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 100%;
  height: 479px;
  background: linear-gradient(180deg, #eaf0ff 0%, #f6f9ff 100%);
}
.slide-titles {
  margin: 0 0 0 275px;
}
.slide-titles h1 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: #3d4f9f;
  padding: 0 0 20px 0;
}
.slide-titles h2 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 45px;
  color: #3d4f9f;
  padding: 0 0 10px 0;
}
.slide-titles h3 {
  font-family: Open Sans;
  font-style: normal;
  font-weight: 600;
  font-size: 12px;
  line-height: 23px;
  letter-spacing: 0.03em;
  color: #a4abc8;
  width: 323px;
}
.mini-square {
  background: #ffffff;
  border: 1px solid #d8e3fe;
  box-sizing: border-box;
  box-shadow: 0px 5px 50px #f3f5fa;
  width: 25%;
  height: 175.37px;
  align-items: center;
  justify-content: center;
  text-align: center;
  margin: 0 0 0 130px;
}
.mini-square p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 24px;
  letter-spacing: 0.03em;
  color: #676f95;
  width: 283px;
  padding: 0 0 0 100px;
}
.slide-last {
  width: 13%;
  height: 175.37px;
  background: #ffffff;
  border: 1px solid #d8e3fe;
  box-sizing: border-box;
  box-shadow: 0px 5px 50px #f3f5fa;
}
.slide-last p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 27px;
  letter-spacing: 0.03em;
  color: #8d96bd;
  width: 283px;
}

/* Section Seven */
.section-seven {
  width: 100%;
  height: 950px;
  background: #ffffff;
  display: flex;
  justify-content: center;
}
.section-seven-main {
  width: 55%;
  margin: auto;
}
.line {
  border: 1px solid #d8e3fe;
  margin: 20px;
}
.faq-drop-down {
  margin-left: 50px;
}
.section-seven-main h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  letter-spacing: 0.1em;
  color: #3d4f9f;
  text-align: center;
  padding: 10px;
}
.section-seven-main h3 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 30px;
  text-align: center;
  color: #3d4f9f;
  padding: 10px;
}
.section-seven-main p {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 15px;
  line-height: 19px;
  display: flex;
  align-items: center;
  letter-spacing: 0.03em;
  color: #8e96b7;
}
.section-seven-main img {
  padding: 10px;
}
.FAQ-btn {
  width: 195px;
  height: 43px;
  background: #e8ecf4;
  border-radius: 2px;
  margin: 20px;
  border: 0.1px solid #e8ecf4;
}
/* Section 8 */
.plan-your-life {
  width: 100%;
  height: 447px;
  background: linear-gradient(229.32deg, #6888ff 12.77%, #5e80ff 73.11%);
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.central_blue_area {
  text-align: center;
}
.blue-headings h6 {
  font-family: Roboto;
  font-style: normal;
  font-weight: 500;
  font-size: 10px;
  line-height: 12px;
  color: #ffffff;
}
.blue-headings h1 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: 300;
  font-size: 48px;
  line-height: 60px;
  text-align: center;
  color: #ffffff;
}
.blue-headings p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 29px;
  max-width: 712px;
  /* text-align: center; */
  /* letter-spacing: 0.03em; */
  color: #ffffff;
  width: 712px;
  height: 78px;
}
.plan-life-btn1 {
  width: 130.08px;
  height: 43px;
  background: #ffffff;
  box-shadow: 0px 5px 15px #6480e8;
  border-radius: 2px;
  border: 0.3px solid white;
  /* Text */
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  /* identical to box height */
  text-align: center;
  color: #565f82;
}
.plan-life-btn2 {
  width: 155px;
  height: 43px;
  /* border: 1px solid #a0b4ff; */
  box-sizing: border-box;
  border-radius: 2px;
  /* Text */
  font-family: Quicksand;
  font-style: normal;
  font-weight: 500;
  font-size: 13px;
  line-height: 16px;
  /* identical to box height */
  align-items: center;
  text-align: center;
  color: #c7d3ff;
}
.right-blue-clouds {
  position: relative;
  top: 50px;
  right: 140px;
}
.newsletter {
  display: flex;
  align-items: center;
  width: 100%;
  height: 332px;
  justify-content: center;
}
.newsletter-sub {
  width: 60%;
  height: 200px;
  display: flex;
  align-items: center;
}
.news-headings h1 {
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 22px;
  /* text-align: center; */
  color: #3d4f9f;
}
.news-headings {
  width: 50%;
  padding: 20px;
}
.news-btns {
  width: 50%;
}
.news-headings p {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 27px;
  letter-spacing: 0.03em;
  color: #8d96bd;
  width: 330px;
  height: 54px;
}
.news-btns input {
  width: 279px;
  height: 59px;
  left: 686px;
  top: 5698px;
  background: #efeff7;
  border-radius: 5px;
  padding: 15px;
  border: 0.3px solid white;
}
.news-btns button {
  width: 184px;
  height: 59px;
  background: #4d6ce1;
  box-shadow: 0px 5px 15px rgba(116, 104, 255, 0.2);
  border-radius: 5px;
  margin-left: 9px;
  border: 0.1px solid #4d6ce1;
  /* text */
  font-family: Quicksand;
  font-style: normal;
  font-weight: bold;
  font-size: 13px;
  line-height: 16px;
  /* identical to box height */
  color: #ffffff;
}
</style>
