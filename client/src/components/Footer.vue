<template>
<div class="container">
  <div id="footer-top" @click="scroll()">
    Back to top
  </div>
  <div id="footer-info">
    <span>
      <strong>Get to Know Us</strong>
      <p>Careers</p>
      <p>Blog</p>
      <p>About Amazon</p>
      <p>Investor Relations</p>
      <p>Amazon Devices</p>
    </span>
    <span>
      <strong>Make Money with Us</strong>
      <p>Sell products on Amazon</p>
      <p>Sell on Amazon Business</p>
      <p>Sell apps on Amazon</p>
      <p>Become an Affiliate</p>
      <p>Advertise Your Products</p>
      <p>Self-Publish with Us</p>
      <p>Host an Amazon Hub</p>
      <p>> See more Make Money with Us</p>
    </span>
    <span>
      <strong>Amazon Payment Products</strong>
      <p>Amazon Business Card</p>
      <p>Shop with Points</p>
      <p>Reload Your Balance</p>
      <p>Amazon Currency Converter</p>
    </span>
    <span>
      <strong>Let us Help You</strong>
      <p>Amazon and COVID-19</p>
      <p>Your Account</p>
      <p>Your Orders</p>
      <p>Shipping Rates & Policies</p>
      <p>Returns & Replacements</p>
      <p>Manage Your Content and Devices</p>
      <p>Amazon Assistant</p>
      <p>Help</p>
    </span>
  </div>
  <div id="footer-settings">
    <button id="footer-language">English</button>
    <button id="footer-currency"><p>$</p> USD - U.S. Dollar</button>
    <button id="footer-country">United States</button>
  </div>
  <div id="footer-services">
    <table id="footer-services-list">
      <tr>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Music</div>
            <div class="smol-text">Sream millions of songs</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Advertising</div>
            <div class="smol-text">Find, attract, and engage customers</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Drive</div>
            <div class="smol-text">Cloud storage from Amazon</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">6pm</div>
            <div class="smol-text">Score deals on fashion brands</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">AbeBooks</div>
            <div class="smol-text">Books, art, & collectibles</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">ACX</div>
            <div class="smol-text">Audiobook Publishing Made Easy</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Alexa</div>
            <div class="smol-text">Actionable Analytics for the Web</div>
          </router-link>
        </td>
      </tr>

      <tr>
        <td>
          <router-link to="/#">
            <div class="services-header">Sell on Amazon</div>
            <div class="smol-text">Start a Selling Account</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Business</div>
            <div class="smol-text">Everything For Your Business</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">AmazonGlobal</div>
            <div class="smol-text">Ship Orders Internationally</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Home Services</div>
            <div class="smol-text">Experienced Pros Happiness Guarantee</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Ignite</div>
            <div class="smol-text">Sell your original Digital Educational Resources</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Web Services</div>
            <div class="smol-text">Scalable Cloud Computing Services</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Audible</div>
            <div class="smol-text">Listen to Books & Original Audio Performances</div>
          </router-link>
        </td>
      </tr>

      <tr>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Music</div>
            <div class="smol-text">Sream millions of songs</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Advertising</div>
            <div class="smol-text">Find, attract, and engage customers</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Drive</div>
            <div class="smol-text">Cloud storage from Amazon</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">6pm</div>
            <div class="smol-text">Score deals on fashion brands</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">AbeBooks</div>
            <div class="smol-text">Books, art, & collectibles</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">ACX</div>
            <div class="smol-text">Audiobook Publishing Made Easy</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Alexa</div>
            <div class="smol-text">Actionable Analytics for the Web</div>
          </router-link>
        </td>
      </tr>

      <tr>
        <td>
          <router-link to="/#">
            <div class="services-header">Sell on Amazon</div>
            <div class="smol-text">Start a Selling Account</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Business</div>
            <div class="smol-text">Everything For Your Business</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">AmazonGlobal</div>
            <div class="smol-text">Ship Orders Internationally</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Home Services</div>
            <div class="smol-text">Experienced Pros Happiness Guarantee</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Ignite</div>
            <div class="smol-text">Sell your original Digital Educational Resources</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Web Services</div>
            <div class="smol-text">Scalable Cloud Computing Services</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Audible</div>
            <div class="smol-text">Listen to Books & Original Audio Performances</div>
          </router-link>
        </td>
      </tr>

      <tr>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Music</div>
            <div class="smol-text">Sream millions of songs</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Advertising</div>
            <div class="smol-text">Find, attract, and engage customers</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Amazon Drive</div>
            <div class="smol-text">Cloud storage from Amazon</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">6pm</div>
            <div class="smol-text">Score deals on fashion brands</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">AbeBooks</div>
            <div class="smol-text">Books, art, & collectibles</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">ACX</div>
            <div class="smol-text">Audiobook Publishing Made Easy</div>
          </router-link>
        </td>
        <td>
          <router-link to="/#">
            <div class="services-header">Alexa</div>
            <div class="smol-text">Actionable Analytics for the Web</div>
          </router-link>
        </td>
      </tr>
    </table>
    <span id="footer-legal">
      <router-link to="conditons-use">
        Conditions of Use
      </router-link>
      <router-link to="privacy">
        Privacy Notice
      </router-link>
      <router-link to="ads">
        Interest-Based Ads
      </router-link>
      <div>
        © 1996-2021, Amazon.com, Inc. or its affiliates
      </div>
    </span>
  </div>
</div>
</template>

<script>
export default {
  name: 'Footer',
  methods: {
    scroll() {
      window.scrollTo(0, 0);
    }
  }
}
</script>

<style lang="scss" scoped>
  $footer-lightblue: #37475a;
  $footer-blue: #232f3e;
  $footer-darkblue: #131a22;
  $footer-grey: #acacac;
  $footer-lightgrey: #cecece;

  .container {
    color: white;
    font-family: 'Roboto', sans-serif;
  }

  * {
    text-decoration: none;
    color: white;
  }

  #footer-top {
    // height: 50px;
    cursor: pointer;
    padding: 1.35em 0;
    background-color: $footer-lightblue;
    text-align: center;
    font-size: .8em;
  }

  #footer-info {
    display: flex;
    justify-content: center;
    gap: 140px;
    background-color: $footer-blue;
    padding: 40px 7vw 125px 7vw;
    border-bottom: 1px solid #556375;

    span {
      max-width: 155px;
      display: flex;
      flex-direction: column;
      line-height: 25px;
      strong {
        font-size: 1em;
      }
    }

    p {
      font-size: .85em;
      color: $footer-lightgrey;
    }
  }

  #footer-settings {
    background-color: $footer-blue;
    display: flex;
    gap: 25px;
    justify-content: center;
    padding: 40px 0 50px 200px;
    background-image: url("../assets/Logo.png");
    background-repeat: no-repeat;
    background-size: 80px;
    background-position: 32.5vw 48px;
    button {
      font-size: .8em;
      padding-top: 10px;
      padding-bottom: 8px;
      color: $footer-grey;
      background-color: $footer-blue;
      border: 1px solid $footer-grey;
      border-radius: 3px;
    }

    #footer-language {
      background-image: url("../assets/Globe.png");
      background-repeat: no-repeat;
      background-position: 8px 7px;
      background-size: 15px;
      padding: 10px 30px 8px 30px;
    }

    #footer-currency {
      display: flex;
      padding: 10px 25px 8px 15px;
      p {
        color: white;
        padding-right: 10px;
      }
    }

    #footer-country {
      background-image: url("../assets/USA-Flag.png");
      background-repeat: no-repeat;
      background-size: 20px;
      background-position: 6px 9px;
      padding: 10px 25px 8px 35px;
    }
  }

  #footer-services {
    background-color: $footer-darkblue;
    padding-top: 25px;
    #footer-services-list {
      padding-bottom: 30px;
      display: table;
      margin-left: auto;
      margin-right: auto;
      max-width: 75%;
      tr {
      }

      td {
        width: 95px;
        vertical-align: top;
        font-size: .7em;
        padding: 10px 30px 10px 10px;
      }

      .services-header{
        color: white;
      }

      .smol-text {
        color: $footer-grey;
      }
    }

    #footer-legal {
      color: $footer-lightgrey;
      padding-bottom: 30px;
      font-size: .75em;
      gap: 20px;
      display: flex;
      flex-wrap: nowrap;
      justify-content: center;
    }
  }
</style>