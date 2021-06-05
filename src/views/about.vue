<template>
  <div class="boxed-container">
    <nav class="navbar horizontal-menu navbar-fixed-top">
      <div class="navbar-inner">
        <div class="navbar-brand">
          <router-link to="/" class="logo">
            <img src="../assets/images/logo_dark@2x.png" width="100%" alt="" class="hidden-xs">
            <img src="../assets/images/logo@2x.png" width="100%" alt="" class="visible-xs"></router-link>
        </div>
        <div class="navbar-mobile-clear"></div>
        <a href="https://github.com/zhangsison" target="_blank">
          <img style="position: absolute; top: 0; right: 0; border: 0;" src="https://s3.amazonaws.com/github/ribbons/forkme_right_darkblue_121621.png" alt="Fork me on GitHub"></a>
      </div>
    </nav>
    <div class="header">
      <!--Content before waves-->
      <div class="inner-header flex">
        <h1>工具导航网址</h1></div>
      <!--Waves Container-->
      <div>
        <svg class="waves" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 24 150 28" preserveAspectRatio="none" shape-rendering="auto">
          <defs>
            <path id="gentle-wave" d="M-160 44c30 0 58-18 88-18s 58 18 88 18 58-18 88-18 58 18 88 18 v44h-352z" /></defs>
          <g class="parallax">
            <use xlink:href="#gentle-wave" x="48" y="0" fill="rgba(255,255,255,0.7" />
            <use xlink:href="#gentle-wave" x="48" y="3" fill="rgba(255,255,255,0.5)" />
            <use xlink:href="#gentle-wave" x="48" y="5" fill="rgba(255,255,255,0.3)" />
            <use xlink:href="#gentle-wave" x="48" y="7" fill="#fff" /></g>
        </svg>
      </div>
      <!--Waves end--></div>
    <div class="content flex">2017-2025
      <a href="/">
        <strong>迪拜de天空导航工具</strong></a>design by
      <a href="https://beian.miit.gov.cn/#/Integrated/index" target="_blank">
        <strong>粤ICP备18020498号</strong></a>
    </div>
  </div>
</template>
<script>export
default {
    name:
    'About',
    data() {
      return {
        authorImg: './assets/images/logos/viggoz.png'
      }
    }
  }</script>
<style>
.header { position:relative; text-align:center; background: linear-gradient(60deg, rgba(84,58,183,1) 0%, rgba(0,172,193,1) 100%); color:white; } .inner-header { height:65vh; width:100%; margin: 0; padding: 0; } .flex { /*Flexbox for containers*/ display: flex; justify-content: center; align-items: center; text-align: center; } .waves { position:relative; width: 100%; height:15vh; margin-bottom:-7px; /*Fix for safari gap*/ min-height:100px; max-height:150px; } .content { position:relative; height:20vh; text-align:center; background-color: white; } /* Animation */ .parallax > use { animation: move-forever 25s cubic-bezier(.55,.5,.45,.5) infinite; } .parallax > use:nth-child(1) { animation-delay: -2s; animation-duration: 7s; } .parallax > use:nth-child(2) { animation-delay: -3s; animation-duration: 10s; } .parallax > use:nth-child(3) { animation-delay: -4s; animation-duration: 13s; } .parallax > use:nth-child(4) { animation-delay: -5s; animation-duration: 20s; } @keyframes move-forever { 0% { transform: translate3d(-90px,0,0); } 100% { transform: translate3d(85px,0,0); } } /*Shrinking for mobile*/ @media (max-width: 768px) { .waves { height:40px; min-height:40px; } .content { height:30vh; } h1 { font-size:24px; } }
</style>