<template>
  <div>
    <div class="main">
      <div class="hero-top is-fullwidth">
        <div class="inner">
          <div class="top_bar">
            <img src="/img/logo.jpg" alt="everwill logo" />
            <h3 class="is-hidden-mobile">Call Us Now <strong>(888) 888-8888</strong></h3>
          </div>
          <div class="left-side-content">
            <h1>Attorney-Crafted Wills & Trusts from the Comfort of Your Home</h1>
            <h2>No hourly billing. Unlimited revisions for life.</h2>
            <form class="form has-text-left">
              <div class="input_button_wrap">
                <input class="input " placeholder="Name"/>
                <input class="input " placeholder="Phone" />
                <button class="button  is-danger">Learn More</button>
                <h2 class="is-hidden-tablet callus">Call Us Now <strong>(888) 888-8888</strong></h2>
              </div>
            </form>
          </div>
        </div>
      </div>
      <div class="who-we-are inner">
        <h2 class="second">Who we are</h2>
        <h3>Duo nemore assentior definitionem ut, id appetere verterem mea. Duo aeque iustro elitr cu, duo te diam iriure copiosae.</h3>

        <div class="profile_wrap has-text-left">
          <div class="columns">
            <div class="column is-6">
              <div class="content_wrap">
                <img src="/img/mobile-jeff-sydney.jpg" alt="Jeff Sydney" />
                <div class="word_wrap jeff">
                  <h2>Jeff Sydney</h2>
                  <h3>Senior Associate</h3>
                  <p class="is-hidden-mobile">Estate Planning is a relationship, not a transaction, and that's what Janice values most
                    about her work... <a @click="handleModal(true)">Read More</a></p>
                </div>
              </div>
            </div>
            <div class="column is-3">
              <div class="content_wrap">
                <img src="/img/mobile-peng-li.jpg" alt="Peng Li" />
                <div class="word_wrap peng">
                  <h2>Peng Li</h2>
                  <h3>Senior Associate</h3>
                  <p class="is-hidden-mobile">Estate Planning is a relationship, not a transaction...<a @click="handleModal(true)">Read More</a></p>
                </div>
              </div>
            </div>
            <div class="column is-3">
              <div class="content_wrap">
                <img src="/img/mobile-janice-shen.jpg" alt="Janice Shen" />
                <div class="word_wrap janice">
                  <h2>Janice Shen</h2>
                  <h3>Senior Associate</h3>
                  <p class="is-hidden-mobile">Estate Planning is a relationship, not a transaction... <a @click="handleModal(true)">Read More</a></p>
                </div>
              </div>

            </div>
          </div>
        </div>
      </div>

      <div class="reason inner">
        <h2 class="second">3 More Reasons to Choose Everwill</h2>

        <div class="wrap">
          <div class="columns is-centered">
            <div class="column is-3">
              <div class="reason_wrap">
                <img src="/img/safe_new.jpg" alt="safe" />
                <h2 class="second"><strong>Never lose your will</strong></h2>
                <h3></h3>
                <p>We store it for you in a bank-grade vault</p>
              </div>
            </div>
            <div class="column is-4">
              <div class="reason_wrap larger">
                <img src="/img/contract.jpg" alt="safe" />
                <h2 class="second"><strong>Allow doctors' emergency access to your end-of-life wishes</strong></h2>
                <h3></h3>
                <p>Carry your Everwill identification Card in your wallet</p>
              </div>
            </div>
            <div class="column is-3">
              <div class="reason_wrap">
                <img src="/img/contract.jpg" alt="safe" />
                <h2 class="second"><strong>Prevent unauthorized access to your will</strong></h2>
                <h3></h3>
                <p>Manage who gets access and when from our online portal</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="footer_call">
        <div class="call_now inner">
          <h2 class="second">Get started now!</h2>
          <h2 class="second light-grey">Call us at 888-383-7945</h2>
          <button class="button is-medium is-danger">Contact Us Today</button>
        </div>
      </div>
      <div class="profile_modal shadow_layer" v-if="modalToggle == true">
        <img class="close_button" src="/img/icon-x.svg" alt="close button" @click="handleModal(false)"/>
        <div class="inner modal_content">
          <img class="profile_pic" src="/img/profile_pic_jeff.jpg" alt="face pic" />
          <h1>Jeff Syndney</h1>
          <span>Senior Associate</span>
          <div class="main_content">
            <p>Every family has their own story to tell.  The trick is listening for it,
              and that's how Janice's speciality.</p>

            <div class="quote_wrap">
              <div class="vertical_line">&nbsp;</div>
              <h2>"Once I understand what is most important to my clients and what keeps
                them up at night, I can create the best plan for their family," Janice
                explains.</h2>
            </div>

            <p>
              Estate planning is a relationship, not a transaction, and that's what Janice
              values most about her work: the human connections she forges with her clients.
              She'll guide you through the decision-making process with compassion and
              expertise, and tailor a plan to suit your wishes.  She's available whenever
              you have a question or need to update your plans, and she'll gently steer
              your family through the necessary steps when the time comes to implement the
              plan you've created.  Janice's clients also appreciate her ability to simplify
              complex legal matters and provide a clear understanding of what will happen to
              their estate after death.
            </p>

            <p>
              As mother to a young son herself, Janice understands firsthand how critical it
              is to plan for your death - and how emotional it can be.  Like all of us, she's
              uneasy about dying, but she finds purpose in delivering peace of mind to her
              clients, who can rest easier knowing they've taken care of their loved ones.
            </p>
          </div>

          <div class="education">
            <h2>Education</h2>
            <ul class="dashed">
              <li>
                Juris Doctorate degree from Western State College of Law in Orange County, Calforina, 2012
              </li>
              <li>
                Bachelor of Arts degree in History from the University of California, Los Angeles, 2005
              </li>
              <li>
                Professional Experience
                <br>
                [<a href="/">pull from resume</a>]
              </li>
            </ul>
          </div>

          <div class="awards">
            <h2>Awards</h2>
          </div>
        </div>

      </div>
    </div>
    <div class="bottom_bar ">
      <div class="links inner">
        <span class="is-hidden-mobile"><small>2017 Everwill. All rights reserved</small></span>
        <a>Privacy Policy</a>
        <a>Terms of Use</a>
        <a>Attorney Advertising</a>
        <p><span class="is-hidden-tablet"><small>2017 Everwill. All rights reserved</small></span></p>
        <img src="/img/mobile-bbb-logo.jpg" alt="logo" />

      </div>
    </div>

  </div>

</template>
<script type="text/ecmascript-6">

  module.exports = {
    data() {
      return {
        modalToggle: false
      }
    },
    methods: {
      handleModal(state) {
        this.modalToggle = state;
      }
    }
  }
</script>
<style lang="scss" rel="stylesheet/scss" scoped>
  @import '~assets/css/variables.scss';


  h1 {
    font-size: 58px;
    line-height: 1.21;
    color: $black;
    font-family: Vollkorn;
  }
  h2 {
    font-size: 24px;
    opacity: 0.8;
    font-family: "Source Sans Pro";
    line-height: 1.71;
    color: $black;
    &.second {
      opacity: 1;
      font-family: Vollkorn;
      font-size: 40px;
      font-weight: 500;
      color: $black;
    }
  }
  h3 {
    font-family: "Source Sans Pro";
    font-size: 19px;
    color: $black;
    line-height: 1.47;
    opacity: 0.6;
  }
  p {
    font-size: 12px;
  }


  .main {
    max-width: 1690px;
    margin: 0 auto;
    .inner {
      max-width: 1176px;
      margin: 0 auto;
      @media screen and (max-width: 800px) {
        padding-left: 2rem;
        padding-right: 2rem;
      }


    }
  }

  .hero-top {
    background-image: url('/img/background_family_new.jpg');
    background-repeat: no-repeat;
    background-position: right;
    background-position-y: 72px;
    background-size: 800px 763px;
    padding-top: 2rem;
    padding-bottom: 232px;
    @media screen and (max-width: 768px) {
      background-image: url('/img/background_family_new.jpg');
      background-position: bottom right;
      background-size: contain;
      padding-bottom: 760px;
    }
    @media screen and (max-width: 700px) {
      padding-bottom: 660px;
    }
    @media screen and (max-width: 600px) {
      padding-bottom: 550px;
    }
    @media screen and (max-width: 600px) {
      padding-bottom: 400px;
    }
  }

//TOP BAR STYLING
  .top_bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    h3 {
      color: $light-black;
      font-weight: 500;
      strong {
        color: $light-black;
      }
    }
  }
//HERO FORM
  .left-side-content {
    width: 50%;
    text-align: left;
    margin-top: 150px;
    h2 {
      margin-top: 1rem;

    }
    .form {
      margin-top: 1.2rem;
      .input_button_wrap {
        display: flex;
        align-items: center;
        justify-content: space-between;
        .input {
          height: $main-button-height;
          border-radius: 50;
          font-size: 18px;
          line-height:2.28;
        }
        .button {
          display: flex;
          align-self: flex-start;
          background-color: $red;
          padding-left: 3.5rem;
          padding-right: 3.5rem;
          font-size: 18px;
          line-height: 1.5;
          height: $main-button-height;
          border-radius: 5px;
          margin-left: 1rem;
        }
        .input + .input {
          margin-left: 1rem;
        }
        h2 {
          text-align: left;
          width: 100%;
          font-size: 16px;
        }
        @media screen and (max-width: 768px) {
          flex-direction: column;
          max-width: 350px;
          .input, .button {
            height: $mobile-button-height;
            margin-top: 1rem;
          }
          .input + .input {
            margin-left: 0rem;
          }
          .input + button {
            margin-left: 0rem;
          }
          .button {
            width: 75%;
          }
        }
      }
    }
    @media screen and (max-width: 768px) {
      width: 100%;
    }
  }
//Who We Are
  .who-we-are {
    padding-top: 105px;
    padding-bottom: 3rem;
    text-align: left;
    h3 {
      margin-top: 0.5rem;
      max-width: 405px;
    }
    @media screen and (max-width: 768px) {
      padding-top: 7rem;
      text-align: center;
      h3 {
        margin-top: 1rem;
        max-width: none;
      }
    }
    .profile_wrap {
      padding-top: 2rem;
      .columns {
        justify-items: space-between;
      }
      .column {
        overflow-x: hidden;
        .content_wrap {
          position: relative;
          width: 300px;
          .word_wrap {
            position: absolute;
            background-color: $black;
            color: black;
            top: 55%;
            left: 22px;
            max-width: 280px;
            text-align: left;
            h2 {
              font-family: Vollkorn;
              font-size: 24px;
              font-weight: 500;
              color: #ffffff;
            }
            h3 {
              margin-top: 0;
              font-family: "Source Sans Pro";
              font-size: 17px;
              font-weight: 300;
              opacity: 1;
              color: #ffffff;
            }
            p {
              font-family: "Source Sans Pro";
              margin-top: 2rem;
              font-size: 16px;
              line-height: 1.38;
              color: #ffffff;
              a {
                color: $red;
              }
            }
          }
        }
      }
      @media screen and (max-width: 768px) {
        padding-top: 5rem;
        .content_wrap {
          margin: 0 auto;
        }
      }
    }
  }

//Reasons for Everwill
  .reason {
    padding-top: 137px;
    padding-bottom: 3rem;
    text-align: left;
    .wrap {
      padding-left: 2rem;
      padding-right: 2rem;
      .columns {
        justify-content: space-between;
      }
      .reason_wrap {
        padding-top: 56px;
        &.larger {
          padding-left: 1rem;
          @media screen and (max-width: 768px) {
            padding-left: 0;
          }
        }
        img {
          height: 210px;
          width: 184px;
        }
        h2.second {
          font-size: 24px;
          opacity: 0.8;
          color: $light-black;
          margin-top: 1.5rem;
          strong {
            font-weight: 500;
          }
        }
        p {
          font-size: 19px;
          margin-top: 0.5rem;
          line-height: 1.7;
          max-width: 283px;
          color: $black;
          opacity: 0.6;
        }
      }
    }
    @media screen and (max-width: 768px) {
      text-align: center;
      h2 {
        font-size: 32px;
        max-width: 280px;
        margin: 0 auto;
      }
      .wrap {
        .reason_wrap {
          margin: 0 auto;
          padding-top: 56px;
          p {
            max-width: none;
          }
        }
      }
    }
  }
//Footer Call Now
  .footer_call {
    background-image: url('/img/background_bigfamily_new.jpg');
    background-repeat: no-repeat;
    background-position: right;
    background-position-y: -10px;
    background-size: 722px 631px;
    padding-top: 230px;

    display: flex;
    flex-direction: column;
    .call_now {
      width: 100%;
      text-align: left;
      padding-bottom: 210px;
      .light-grey {
        color: $light-black;
        opacity: 0.5;
      }
      h2 {
        font-size: 40px;
        line-height: 1.25;
        @media screen and (max-width: 768px) {
          font-size: 24px;
        }
      }
      button {
        background-color: $red;
        padding-left: 2.5rem;
        padding-right: 2.5rem;
        margin-top: 2rem;
        font-size: 18px;
        line-height: 1.5;
        height: $main-button-height;
        border-radius: 5px;
      }
    }
    @media screen and (max-width: 768px) {
      background-image: url('/img/background_bigfamily_new.jpg');
      background-position: bottom right;
      background-size: contain;
      padding-top: 0rem;
      margin-top: 100px;
      .call_now {
        text-align: center;
        padding-bottom: 30rem;
      }
    }
  }
  .bottom_bar {
    background-color: rgba(22, 67, 73, 0.85);
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    width: 100%;
    .links {
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      img {
        padding-left: 1rem;
        @media screen and (max-width: 768px) {
          position: absolute;
          bottom: 1rem;
          right: 1rem;
          padding-left: 0;
        }

      }
      span {
        font-size: 14px;
        padding-right: 0.5rem;
        color: rgba(255, 255, 255, 0.52);
      }
      a {
        padding-left: 1rem;
        font-size: 14px;
        color: #ffffff;
      }
    }
    @media screen and (max-width: 768px) {
      .links {
        padding-top: 1rem;
        flex-direction: column;
        align-items: flex-start;
        a {
          padding-left: 2rem;
        }
        p {
          margin-top: 0.25rem;
          padding-left: 2rem;
          color: $light-grey;
        }
      }
    }
  }

//Modal Styling
  .profile_modal {
    &.shadow_layer {
      position: fixed;
      top:0;
      left: 0;
      bottom: 0;
      right: 0;
      background-color: #ffffff;
      text-align: center;
      padding-top: 5rem;
      .close_button {
        position: absolute;
        top: 2rem;
        right: 2rem;
        transform: scale(0.7);
        cursor: pointer;
        &:hover{
          opacity: 0.7;
        }
      }

      .inner {
        max-width: 700px;
        h1 {
          margin-bottom: 0.25rem;
          font-size: 40px;
        }
        span {
          font-size: 17px;
        }
      }
      .main_content {
        margin-top: 2rem;
        text-align: left;
        p {
          font-family: 'Source Sans Pro';
          margin-top: 1.5rem;
          font-size: 17px;
          line-height: 30px;
        }
        .quote_wrap {
          margin-top: 1.5rem;
          margin-bottom: 1.5rem;
          padding-right: 2rem;
          padding-left: 1rem;
          position: relative;
          .vertical_line {
            position: absolute;
            top: 10px;
            bottom: 10px;
            left: 0;
            border-left: 1px solid black;
          }
          h2 {
            font-family: Vollkorn;
            font-style: italic;
            font-size: 24px;
            line-height: 1.5;
            color: $quote-color;
            font-weight: 500;
          }
          @media screen and (max-width: 500px) {
            padding-right: 0rem;
            max-width: 380px;
          }
        }
      }
      .education {
        margin-top: 2rem;
        text-align: left;
        h2 {
          font-size: 21px;
          font-family: 'Source Sans Pro';
          line-height: 1.48;
          color: $light-black;
        }
        ul {
          font-family: 'Source Sans Pro';

          margin-top: 1rem;
          li {
            margin-top: 1rem;
            font-size: 17px;
            a {
              color: inherit;
            }
          }
        }
        ul.dashed {
          list-style: none;
          padding-left: 0;
        }

        ul.dashed > li {
          margin-left: 6px;
        }

        /* Prevent nested li's from getting messed up */
        ul.dashed > li::before {
          content: "-";
          margin-left: -6px;
        }
      }
      .awards {
        margin-top: 2rem;
        text-align: left;
        h2 {
          color: $light-black;
        }
      }
    }
  }
  .profile_pic {
    border-radius: 1000px;
    transform: scale(0.75);

  }































</style>