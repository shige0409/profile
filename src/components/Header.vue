<template>
	<header>
    <nav>
      <ul class="flex-box right-align header-lists">
        <li><a href="">PORTFOLIO</a></li>
        <li><a href="#profile">profile</a></li>
        <li><a href="#trend">mytrend</a></li>
        <li id="portfolio-drop">
          <a href="#portfolio">portfolio</a>
          <ul id="portfolios">
            <li><a href="">test1</a></li>
            <li><a href="">test2</a></li>
            <li><a href="">test3</a></li>
          </ul>
        </li>
        <li><a href="#contact">contact</a></li>
      </ul>
    </nav>
</header>
</template>


<script>
export default {
	
}
</script>

<style lang="scss" scoped>
	.header-lists {
    padding: 15px;
    margin-bottom: 100px;
    > li:first-child {
      margin-right: auto;
      font-size: 1.5em;
      font-family: 'Bangers', cursive;
    }
    > li {
      font-size: 1.2em;
      margin-left: 20px;
      padding: 20px;
      position: relative;
      > a {
        letter-spacing: 0.2em;
        padding: 15px;
        transition: 0.6s;
      }
      &:hover > a {
        background-color: #fff;
        color: #00c;
        border-radius: 20px;
      }
      #portfolios {
        position: absolute;
        z-index: 5;
        top: 100%;
        left: -50%;
        width: 200%;
        li {
            transition: 0.6s;
            overflow: hidden;
            max-height: 0;
            a {
                padding: 10px;
            }
            &:hover a {
                background-color: #fff;
                color: #00c;
                border-radius: 10px;
            }
        } 
      }
    }
    #portfolio-drop{
        &:hover > ul > li{
            max-height: 40px;
            margin: 10px;
        }
    }
  }
</style>
