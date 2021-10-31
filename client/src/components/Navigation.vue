<template>
<div class="container">
  <div id="nav-top">
    <router-link id="amazon-logo" to="/">
    </router-link>
    <span id="delivery-to" class="generic-text">
      <p class="smol-text">Deliver to</p>
      <p><strong>Czech Republic</strong></p>
    </span>
    <span id="search-bar-nav" :class="{ 'search-border': isFocused }">
      <button id="category">All</button>
      <input type="text" id="text-input" @focus="changeFocus()" @blur="changeFocus()"/>
      <button id="lookup"></button>
    </span>
    <router-link id="country" to="/select-lang">
    </router-link>
    <router-link class="generic-text" to="/sign-in">
      <span class="smol-text"><p>Hello, Sign in</p></span>
      <p><strong>Account & Lists</strong></p>
    </router-link>
    <router-link class="generic-text" to="/returns-orders">
      <span class="smol-text"><p>Returns</p></span>
      <p><strong>& Orders</strong></p>
    </router-link>
    <router-link id="cart" class="generic-text" to="/cart">
      <span id="cart-number"><strong>0</strong></span>
      <span id="cart-text"><strong>Cart</strong></span>
    </router-link>
  </div>
  <div id="nav-bottom">
    <span id="burger">
      <strong>All</strong>
    </span>
    <router-link class="generic-text" to="/deals">Today's Deals</router-link>
    <router-link class="generic-text" to="/customer-service">Customer Service</router-link>
    <router-link class="generic-text" to="/registry">Registry</router-link>
    <router-link class="generic-text" to="/gift-cards">Gift Cards</router-link>
    <router-link class="generic-text" to="/sell">Sell</router-link>

    <span id="covid-19">
      <p class="generic-text"><strong><router-link to="/covid-19">Amazon's response to COVID-19</router-link></strong></p>
    </span>
  </div>
</div>
</template>

<script>
export default {
  name: 'Navigation',
  data() {
    return {
      isFocused: false
    }
  },
  methods: {
    navFocus() {
      window.scrollTo(0, 0);
    },
    changeFocus() {
      this.isFocused = !this.isFocused;
    }
  }
}
</script>

<style lang="scss" scoped>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
  $nav-lookup: #febd69;
  $nav-dark-blue: #131921;
  $nav-blue: #232f3e;
  $nav-grey: #f3f3f3;
	$nav-input: #ffffff;
  $nav-hover: #dddcdc;

  .container {
    color: white;
    font-family: 'Roboto', sans-serif;
  }

  #nav-top {
    height: 3.75em;
    max-height: 3.75em;
    background-color: $nav-dark-blue;
    display: flex;
    gap: 10px;
    justify-content: space-between;

    #amazon-logo {
      margin: 5px 0 5px 12px;
      padding: 8px 5px 0 6px;
      width: 100px;
      background-image: url("../assets/Logo.png");
      background-repeat: no-repeat;
      background-size: 98px;
      background-position: 6px 11px;
      border: 1px solid transparent;
      border-radius: 3px;
      &:hover {
        border: 1px solid white;
      }
    }

    #delivery-to {
      .smol-text {
        color: #d1cfcf;
      }
      color: $nav-grey;
      padding: 5px 5px 0 25px;
      background-image: url("../assets/Map-Pointer.png");
      background-repeat: no-repeat;
      background-size: 12%;
      background-position: 5px 12px;
      border: 1px solid transparent;
      border-radius: 3px;
      &:hover {
        border: 1px solid white;
    }
    }

    #search-bar-nav {
      display: flex;
      flex-direction: row;
      margin: 10px 0;
      // box-shadow: 0 0 10px black;

      #category {
        cursor: pointer;
        background-color: $nav-grey;
        padding: 0 20px;
        border: none;
        border-right: 1px solid #c9c9c9;
        border-radius: 5px 0 0 5px;
        &:focus {
          position: relative;
          box-shadow: 0 0 1px 3px rgb(236, 120, 37);
        }
        &:hover {
          background-color: $nav-hover;
        }
      }

      #text-input {
        &[type=text] {
          padding-left: 10px;
          font-size: 1em;
        }

        border: none; 
        width: calc(100vw - 830px);
        &:focus {
          outline: none;
        }
      }

      #lookup {
        cursor: pointer;
        background-color: $nav-lookup;
        background-image: url("../assets/Lookup.png");
        background-repeat: no-repeat;
        background-size: 50%;
        background-position: 10px 9px;
        width: 45px;
        border-radius: 0 5px 5px 0;
        border: none;
        &:focus {
          position: relative;
          box-shadow: 0 0 1px 3px rgb(236, 120, 37);
        }
      }
    }

    #country {
      cursor: pointer;
      background-image: url("../assets/USA-Flag.png");
      background-repeat: no-repeat;
      background-size: 25px;
      width: 25px;
      background-position: 9.5px 17.5px;
      border: 1px solid transparent;
      border-radius: 3px;
      padding: 0 10px 0 10px;
      margin: 7.5px 0 7.5px 0;
      &:hover {
        border: 1px solid white;
      }
    }

    #cart {
      padding-left: 21px;
      margin-left: 5px;
      margin-right: 10px;
      width: 55px;
      background-image: url("../assets/Cart.png");
      background-repeat: no-repeat;
      background-size: 47.5px;
      background-position: 2.75px 5px;

      #cart-number {
        margin-left: 3.75px;
        color: rgb(236, 120, 37);
      }

      #cart-text {
        position: absolute;
        margin-top: 14px;
        padding-left: 15px;
        text-align: right;
      }
    }

    .generic-text {
      color: white;
      text-decoration: none;
      cursor: pointer;
      font-size: 1em;
      margin-top: 8px;
      margin-bottom: 5px;
      padding: 5px 10px 0 10px;
      border: 1px solid transparent;
      border-radius: 3px;
      &:hover {
        border: 1px solid white;
      }
    }

    .smol-text {
      font-size: .7em;
    }

    .search-border {
      position: relative;
      box-shadow: 0 0 1px 3px rgb(236, 120, 37);
      border-radius: 5px;
    }
  }

  #nav-bottom {
    height: 2.35em;
    max-height: 2.35em;
    background-color: $nav-blue;
    display: flex;

    * {
      color: white;
      text-decoration: none;
    }
    .generic-text {
      font-size: .90em;
      margin: 5px 0 5px 0; //outside
      padding: 3.5px 8px 5px 6px; //inside
      border: 1px solid transparent;
      border-radius: 3px;
      &:hover {
        border: 1px solid white;
      }
    }

    #burger {
      font-size: .90em;
      cursor: pointer;
      padding-left: 50px;
      background-image: url("../assets/Burger.png");
      background-repeat: no-repeat;
      background-size: 20px;
      background-position: 6px 4px;
      margin: 5px 0 5px 20px; //outside
      padding: 3.5px 8px 5px 31px; //inside
      border: 1px solid transparent;
      border-radius: 3px;
      &:hover {
        border: 1px solid white;
      }
    }

    #covid-19 {
      padding-right: 15px;
      margin-left: auto;
      text-align: left;
    }
  }
</style>
