<template>
  <div class="main">
    <div class="hero-top is-fullwidth">
      <div class="inner">
        <div class="top_bar">
          <img src="/assets/img/logo.jpg" alt="everwill logo" />
          <h3>Call Us Now <strong>(888) 888-8888</strong></h3>
        </div>
        <div class="left-side-content">
          <h1>Attorney-Crafted Wills & Trusts from the Comfort of Your Home</h1>
          <h2>No hourly billing. Unlimited revisions for life.</h2>
          <form class="form">
            <div class="input_button_wrap">
              <input class="input is-small" placeholder="Name"/>
              <input class="input is-small" placeholder="Phone" />
              <button class="button is-small is-danger">Learn More</button>
            </div>
          </form>
        </div>
      </div>
    </div>
    <div class="who-we-are inner has-text-left">
      <h2 class="second">Who we are</h2>
      <h3>Duo nemore assentior definitionem ut, id appetere verterem mea. Duo aeque iustro elitr cu, duo te diam iriure copiosae.</h3>

      <div class="profile_wrap">
        <div class="columns">
          <div class="column is-6">
            <div class="word_wrap">
              <h2>Jeff Sydney</h2>
              <h3>Senior Associate</h3>
              <p>Estate Planning is a relationship, not a transaction, and that's what Janice values most about her work... <a>Read More</a></p>
            </div>
          </div>
          <div class="column is-3">
            <div class="word_wrap">
              <h2>Peng Li</h2>
              <h3>Senior Associate</h3>
              <p>Estate Planning is a relationship, not a transaction, and that's what Janice values most about her work... <a>Read More</a></p>
            </div>
          </div>
          <div class="column is-3">
            <div class="word_wrap">
              <h2>Janice Shen</h2>
              <h3>Senior Associate</h3>
              <p>Estate Planning is a relationship, not a transaction, and that's what Janice values most about her work... <a>Read More</a></p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="reason inner has-text-left">
      <h2 class="second">3 More Reasons to Choose Everwill</h2>

      <div class="wrap">
        <div class="columns">
          <div class="column is-3">
            <div class="reason_wrap">
              <img src="/assets/img/safe.jpg" alt="safe" />
              <h2><strong>Never lose your will</strong></h2>
              <h3></h3>
              <p>We store it for you in a bank-grade vault</p>
            </div>
          </div>
          <div class="column is-3">
            <div class="reason_wrap">
              <img src="/assets/img/contract.jpg" alt="safe" />
              <h2><strong>Allow doctors' emergency access to your end-of-life wishes</strong></h2>
              <h3></h3>
              <p>Carry your Everwill identification Card in your wallet</p>
            </div>
          </div>
          <div class="column is-3">
            <div class="reason_wrap">
              <img src="/assets/img/contract_shield.jpg" alt="safe" />
              <h2><strong>Prevent unauthorized access to your will</strong></h2>
              <h3></h3>
              <p>Manage who gets access and when from our online portal</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="footer_call has-text-left">
      <div class="call_now inner">
        <h2 class="second">Get started now!</h2>
        <h2 class="second light-grey">Call us at 888-383-7945</h2>
        <button class="button is-medium is-danger">Contact Us Today</button>
      </div>
      <div class="bottom_bar ">
        <div class="links inner">
          <span><small>2017 Everwill. All rights reserved</small></span>
          <a>Privacy Policy</a>
          <a>Terms of Use</a>
          <a>Attorney Advertising</a>
          <img src="/" alt="logo" />
        </div>
      </div>
    </div>


  </div>
</template>
<script type="text/ecmascript-6">

  export default {
    data() {
      return {
        data: {

        }
      }
    }
  }
</script>
<style lang="scss" rel="stylesheet/scss" scoped>


  h1 {
    font-size: 32px;
    font-weight: 500;
  }
  h2 {
    font-size: 12px;
    &.second {
      font-size: 22px;
      font-weight: 500;
    }
  }
  h3 {
    font-size: 10px;
  }
  p {
    font-size: 8px;
  }


  .main {
    max-width: 1200px;
    margin: 0 auto;
    .inner {
      max-width: 790px;
      margin: 0 auto;
    }
  }

  .hero-top {
    background-image: url('/assets/img/background_family.jpg');
    background-repeat: no-repeat;
    background-position: top right;
    padding-top: 2rem;
    padding-bottom: 150px;
  }


//TOP BAR STYLING
  .top_bar {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
//HERO FORM
  .left-side-content {
    width: 50%;
    text-align: left;
    margin-top: 100px;
    h2 {
      margin-top: 1rem;
      font-weight: 500;
    }
    .form {
      margin-top: 1rem;
      .input_button_wrap {
        display: flex;
        align-items: center;
        justify-content: space-between;

      }
    }
  }
//Who We Are
  .who-we-are {
    padding-top: 3rem;
    padding-bottom: 3rem;
    h3 {
      margin-top: 0.5rem;
      max-width: 275px;
    }
  }

//Reasons for Everwill
  .reason {
    padding-top: 3rem;
    padding-bottom: 3rem;
    .wrap {
      padding-top: 5rem;
      padding-left: 2rem;
      padding-right: 2rem;
      .columns {
        justify-content: space-between;
      }
      .reason_wrap {
        max-width: 230px;
      }
    }
  }
//Footer Call Now
  .footer_call {
    background-image: url('/assets/img/background_bigfamily.jpg');
    background-repeat: no-repeat;
    background-position: bottom right;
    padding-top: 10rem;
    .bottom_bar {
      margin-top: 10rem;
      background-color: rgba(22, 67, 73, 0.85);
    }
  }
  .bottom_bar {
    padding-top: 0.5rem;
    padding-bottom: 0.5rem;
    .links {
      display: flex;
      justify-content: center;
      align-items: center;
      span {
        font-size: 9px;
      }
      a {
        padding-left: 2rem;
        padding-right: 2rem;
        font-size: 9px;
      }
    }
  }


</style>