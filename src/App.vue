<template>
  <div id="main-bg">
    <Header/>
    <main>
      <Message/>
      <Profile/>
      <Trend/>
      <Portfolio/>
      <Contact/>
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

<style>
#main-bg {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
