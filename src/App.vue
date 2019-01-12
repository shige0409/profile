<template>
  <div id="main-bg">
    <Header/>
    <main>
      <Message/>
      <!--
      <Profile/>
      <Trend/>
      <Portfolio/>
      <Contact/>
      -->
    </main>
    <Footer/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Header from './components/Header'
import Message from './components/Message'
import Profile from './components/Profile'
import Trend from './components/Trend'
import Portfolio from './components/Portfolio'
import Contact from './components/Contact'
import Footer from './components/Footer'
export default {
  name: 'App',
  components: {
    Header,
    Message,
    Profile,
    Trend,
    Portfolio,
    Contact,
    Footer
  }
}
</script>

<style lang="scss">
@charset "UTF-8";
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}
/* HTML5 display-role reset for older browsers */
ol, ul {
	list-style: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
a {
	text-decoration: none;
	color: #fff;
}
input, textarea{
	outline: none;
	border-color: transparent;
	background: transparent;
}
body {
	text-align: center;
	color: #fff;
	font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", "Yu Gothic", YuGothic, Verdana, Meiryo, "M+ 1p", sans-serif;
}
.flex-box {
  display: flex; }

.right-align {
  justify-content: flex-end; }

.container {
  margin: 0 auto;
  height: 640px; }

#target {
  font-size: 40px;
  letter-spacing: 3px; }

.info {
  margin-top: 40px; }

.good {
  color: #777; }

.bad {
  color: #222; }

.hide {
  display: none; }

.clearness {
  opacity: 0;
}
.typing {
  width: 100%;
  font-size: 40px;
  text-align: center; }
.btn {
  display: inline-block;
  font-size: 20px;
  margin: 10px auto;
  padding: 15px;
  border-radius: 5px;
}

body {
  font-family: 'Times New Roman', Times, serif;
}
#main-bg {
  background: linear-gradient(to top, rgba(0,0,0,0.5),rgba(0,0,200,0.5)), url('./assets/shige.jpeg');
  background-size: 100% 100%;
  background-attachment: fixed;
}
</style>
