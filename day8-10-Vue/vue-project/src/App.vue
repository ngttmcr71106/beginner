<script setup>
import Inner from '@/components/inner.vue'
import SectionHeading from '@/components/SectionHeading.vue'
</script>

<template>
<header class="p-3 md:p-4 fixed top-0 left-0 border-b border-solid border-[#f1eee4]/25 w-full text-center">
  <div class="max-w-[1080px] px-10 my-0 mx-auto block md:flex justify-between">
    <h1 class="w-50 my-0 mx-auto md:mx-0"><img src="./images/logo.svg" alt="ロゴ"></h1>
    <nav class="mt-2.5">
      <ul class="flex justify-center gap-6 md:gap-10 text-white">
        <li><a href="#about">About</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#shop">Shop</a></li>
      </ul>
    </nav>
  </div>
</header>

<div class="">
  <picture>
    <source media="(min-width: 768px)" srcset="./images/fv.png">
    <img src="./images/sp/fv.png" alt="">
  </picture>
</div>

<section id="about" class="py-10 bg-[#f1eee4]">
  <Inner>
    <SectionHeading main="About" sub="ー 当店について ー" />
    <div class="">
      <img src="./images/about.png" alt="">
      <div class="mt-5">
        <p class="text-sm leading-loose">当店では、素材の持つ美味しさや風味を最大限に生かし、シンプルでありながらも、素材の良さを引き出すこだわりのスイーツを提供しています。</p>
        <p class="text-sm leading-loose mt-4">自然な味わいを大切にし、素材を感じさせるスイーツで、心に残るひとときをお過ごしください。</p>
      </div>
    </div>
  </Inner>
</section>

<section id="menu" class="py-20 bg-[#f1eee4]">
  <Inner>
    <SectionHeading main="Menu" sub="ー メニュー ー" />
    <div class="">
      <ul>
        <li>
          <div class="">
            <img src="./images/menu1.png" alt="">
          </div>
          <div class="text-center py-4 px-2.5">
            <h3>
              <span class="text-lg block">ストロベリーケーキ</span>
              <span class="text-[#a98c5f] text-[12px] block mt-2">- Strawberry cake -</span>
            </h3>
            <p class="text-sm text-[#a98c5f] mt-4"># 旬のあまおうトッピング</p>
          </div>
        </li>
        <li class="mt-16">
          <div class="">
            <img src="./images/menu2.png" alt="">
          </div>
          <div class="text-center py-4 px-2.5">
            <h3>
              <span class="text-lg block">ブルーベリーチーズケーキ</span>
              <span class="text-[#a98c5f] text-[12px] block mt-2">- Blueberry cheesecake -</span>
            </h3>
            <p class="text-sm text-[#a98c5f] mt-4"># フランス産チーズをブレンド</p>
          </div>
        </li>
        <li class="mt-16">
          <div class="">
            <img src="./images/menu3.png" alt="">
          </div>
          <div class="text-center py-4 px-2.5">
            <h3>
              <span class="text-lg block">チョコレートケーキ</span>
              <span class="text-[#a98c5f] text-[12px] block mt-2">- Chocolate cake -</span>
            </h3>
            <p class="text-sm text-[#a98c5f] mt-4"># ベルギー産チョコレート使用</p>
          </div>
        </li>
      </ul>
    </div>
  </Inner>
</section>

<section id="shop" class="bg-[url(/images/sp/bg-shop.png)] bg-cover bg-center py-20">
  <div class="px-5">
    <SectionHeading main="Shop" sub="ー ショップ情報 ー" class="text-white" />
    <div class="">
      <p class="text-white text-center text-sm ">
        ただいま、オンラインストアを準備中です。
        <br>
        最新情報は以下より送信いただいた
        <br>
        メールアドレスへご案内いたします。
      </p>
      <form action="#" class="mt-10">
        <input type="email" placeholder="sample@sample.com" class="w-full rounded-[4px] bg-white/70 border-none p-3.5">
        <button type="submit" class="rounded-[4px] border-none block mt-2.5 mx-auto w-[120px] py-3 px-2.5 text-white bg-[#a98c5f]">SEND</button>
      </form>
    </div>
  </div>
</section>

<footer class="bg-[#3c301e] text-center pt-12 text-white block">
  <div class="w-[200px] my-0 mx-auto">
    <img src="./images/logo.svg" alt="">
  </div>
  <p class="text-[12px]">ー 各SNS更新中 ー</p>
  <ul class="mt-10 flex justify-center gap-6 py-0 px-5">
    <li>
      <a href="https://google.com" target="_blank" class="flex flex-col items-center">
        <img src="./images/icon-instagram.png" alt="" class="!w-[56px]">
        <p class="text-[12px] mt-3">メニューご案内</p>
      </a>
    </li>
    <li>
      <a href="https://google.com" target="_blank" class="flex flex-col items-center">
        <img src="./images/icon-youtube.png" alt="" class="!w-[56px]">
        <p class="text-[12px] mt-3">メニューご案内</p>
      </a>
    </li>
    <li>
      <a href="https://google.com" target="_blank" class="flex flex-col items-center">
        <img src="./images/icon-twitter.png" alt="" class="!w-[56px]">
        <p class="text-[12px] mt-3">メニューご案内</p>
      </a>
    </li>
  </ul>
  <div class="border-t border-solid border-[#f1eee4]/25 p-3 mt-12">
    <small class="text-[12px]">&copy;2023 Sweet Delight.</small>
  </div>
</footer>

</template>

<style>

</style>