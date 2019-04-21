<template>
  <div id="app">
    <Header/>
    <Blog/>
    <Parallax/>
    <Activities/>
    <Parallax/>
    <Tabs/>
    <Parallax/>
    <Form/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/layout/Header";
import Blog from "./components/Blog-post";
import Parallax from './components/Parallax'
import Form from "./components/Form";
import Tabs from "./components/Tabs";
import Footer from "./components/layout/Footer";
import Activities from "./components/Activities";

export default {
  name: 'app',
  components: {
    Header,
    Blog,
    Parallax,
    Form,
    Tabs,
    Footer,
    Activities
  }
}
</script>
