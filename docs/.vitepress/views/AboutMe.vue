<template>
  <div class="px-6 pb-24 mt-2 md:pb-32 md:px-12 lg:px-16">
    <div class="flex flex-col items-center justify-center max-w-6xl mx-auto">
      <!-- 头像与徽章 -->
      <div class="relative w-full mx-auto">
        <!-- 头像 -->
        <div class="relative py-2 h-52">
          <div
            class="absolute w-48 h-48 mx-auto rounded-full shadow-[0px_0px_3px#147eae] dark:shadow-[0px_0px_3px#9ba0a9] top-1/2 avatar-ping left-1/2">
          </div>
          <img class="block w-48 h-48 mx-auto rounded-full" src="../../src/public/logo.png" alt="avatar" />
        </div>
        <!-- Right-tags -->
        <p style="top: 32%"
          class="tag-bounce hidden sm:block sm:left-[69%] md:left-[66%] lg:left-[63%] xl:left-[60%] absolute px-3 py-0.5 text-sm font-bold rounded-full shadow-[0px_0px_1px_1px#eee]">
          🎵 网易云 空生酥
        </p>
        <p style="top: 50%"
          class="tag-bounce hidden sm:block sm:left-[69%] md:left-[66%] lg:left-[63%] xl:left-[60%] absolute px-3 py-0.5 text-sm font-bold rounded-full shadow-[0px_0px_1px_1px#eee]">
          🌙 Bilibili 空生酥
        </p>
        <!-- Left-tags -->
        <p style="top: 32%"
          class="tag-bounce hidden sm:block sm:left-[8%] md:left-[13%] lg:left-[21%] xl:left-[27%] absolute px-3 py-0.5 text-sm font-bold rounded-full shadow-[0px_0px_1px_1px#eee]">
          🌟 独立音乐人
        </p>
        <p style="top: 50%"
          class="tag-bounce hidden sm:block sm:left-[8%] md:left-[13%] lg:left-[21%] xl:left-[27%] absolute px-3 py-0.5 text-sm font-bold rounded-full shadow-[0px_0px_1px_1px#eee]">
          ✨Coding with dream
        </p>
      </div>
      <!-- 概述与箴言 -->
      <div class="flex flex-col w-full mt-4">
        <div class="flex flex-col justify-between gap-5 md:gap-0 md:flex-row">
          <!-- 概述 -->
          <div
            class="dark:from-sky-700 dark:to-teal-600 dark:border-slate-900 w-full flex flex-col justify-center rounded-xl border py-4 px-8 text-white md:w-[59%] bg-gradient-to-r from-sky-400 to-teal-400">
            <p class="text-lg text-slate-50">
              你好，我是酥酥，来自成都，很高兴认识你 👋
            </p>
            <h1 class="text-xl font-bold xl:text-3xl lg:break-normal lg:break-words">
              🌟 Dream to be a full-stack developer.
            </h1>
            <p class="text-slate-100">前端开发 / 产品设计 / 音乐制作人 / 虚拟主播 / up主</p>
          </div>
          <!-- 箴言 -->
          <div
            class="bg-stripe dark:border-slate-900 dark:bg-slate-800 md:w-[39%] w-full rounded-xl border p-4 bg-slate-50">
            <p class="text-[12px]">💬 Motto</p>
            <div>
              <h1 class="text-2xl leading-9">
                <span class="hidden font-bold text-teal-400 md:inline-block">💬 A blog is not just a website.&nbsp;
                </span>
                <span class="hidden lg:inline-block">It's a voice, &nbsp;</span>
              </h1>
              <h1 class="font-serif text-3xl tracking-widest md:text-2xl lg:text-3xl">
                <span class="font-bold text-sky-500">a conversation</span> and a
                community.
              </h1>
              <h1 class="text-2xl leading-9 md:text-3xl">
                <span class="inline-block font-bold text-teal-400 md:hidden">Blogs are used to record study and
                  life.&nbsp;
                </span>
                <span class="inline-block lg:hidden">Is Everywhere</span>
              </h1>
            </div>
          </div>
        </div>
      </div>
      <!-- 简介与技术栈 -->
      <div class="flex flex-col justify-between w-full gap-5 mt-4 md:gap-0 md:flex-row">
        <!-- 简介 -->
        <div
          class="bg-stripe w-full md:w-[35%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <p class="text-[12px]">💡 I am a software engineering student.</p>
          <div class="mt-2">
            <h1 class="text-xl">😺Love coding and open source.</h1>
            <h1 class="text-xl">🎂2006.1.26 born in Chengdu.</h1>
            <h1 class="text-xl lg:text-xl md:text-base">🔥🌱</h1>
            <p></p>
          </div>
        </div>
        <!-- 技术栈 -->
        <div class="w-full md:w-[62%] dark:border-slate-900 border dark:bg-slate-800 bg-slate-50 p-4 rounded-xl">
          <p class="text-[12px]">技术栈</p>
          <div class="mt-2 overflow-hidden">
            <!-- TODO:封装ICON组件,抽离背景颜色与svg地址 -->
            <div class="flex gap-4 w-fit icon-scroll">
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-emerald-200">
                <img src="./img/vue.svg" alt="vue.js" />
              </div>
              <div class="flex-shrink-0 w-20 h-20 p-4 bg-red-200 rounded-lg">
                <img src="./img/html.svg" alt="" />
              </div>
              <div class="flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-sky-200">
                <img src="./img/css.svg" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-200">
                <img src="./img/tailwind.svg" alt="" />
              </div>
              <div class="flex justify-center w-20 h-20 p-4 flex-shrink-0 rounded-lg bg-[#f7cb4f]">
                <img class="rounded-lg" src="./img/js.webp" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-red-400 rounded-lg">
                <img class="rounded-lg" src="./img/git.svg" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-200">
                <img class="rounded-lg" src="./img/react.svg" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-rose-200">
                <img class="rounded-lg" src="./img/npm.svg" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-indigo-200 rounded-lg">
                <img class="rounded-lg" src="./img/nest.png" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-emerald-200">
                <img src="./img/vue.svg" alt="vue.js" />
              </div>
              <div class="flex-shrink-0 w-20 h-20 p-4 bg-red-200 rounded-lg">
                <img src="./img/html.svg" alt="" />
              </div>
              <div class="flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-sky-200">
                <img src="./img/css.svg" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-200">
                <img src="./img/tailwind.svg" alt="" />
              </div>
              <div class="flex justify-center w-20 h-20 p-4 flex-shrink-0 rounded-lg bg-[#f7cb4f]">
                <img class="rounded-lg" src="./img/js.webp" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-red-400 rounded-lg">
                <img class="rounded-lg" src="./img/git.svg" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-200">
                <img class="rounded-lg" src="./img/react.svg" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-rose-200">
                <img class="rounded-lg" src="./img/npm.svg" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-indigo-200 rounded-lg">
                <img class="rounded-lg" src="./img/nest.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- 图片与荣誉 -->
      <div class="flex flex-col justify-between w-full gap-5 mt-4 md:gap-0 md:flex-row">
        <!-- 图片 -->
        <div class="w-full md:w-[45%] honer-bg bg-center bg-no-repeat bg-cover rounded-xl h-52 sm:h-auto"></div>
        <!-- 荣誉 -->
        <div
          class="bg-stripe w-full md:w-[50%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <p class="text-[12px]">🏆 Awards</p>
          <h1 class="mt-2 text-4xl font-bold text-indigo-600">追风赶月</h1>
          <div class="mt-4 md:text-base lg:text-xl">
            <p class="py-1 text-blue-500 font-semibold">
              🏅
              <a href="https://github.com/LofiSu/LofiSu/blob/main/My%20Honors%20and%20Awards.md" class="underline">My
                Honors and Awards</a>
            </p>
            <p class="py-1 text-purple-500">
              🌟
              <span class="font-bold">Apache Open Source Contributor</span> in
              Apache Fury.
              <span class="italic">Fury official website builder</span>
            </p>
            <p class="py-1 text-green-500">
              🌟
              <span class="font-bold">Tencent Rhino Bird Open Source Contributor</span>
              in Tencent Omi.
            </p>
            <p class="py-1 text-red-500">
              🏆
              <span class="font-bold">Tencent Rhino Bird Open Source Practical Award</span>
            </p>
            <p class="py-1 text-yellow-500">
              🌟
              <span class="font-bold">Alibaba Open Source Contributor</span> in
              Alibaba Cloud ( Higress --- OpenYurt ).
            </p>
            <p class="py-1 text-orange-500">
              🏅
              <span class="font-bold">Champion of the Alibaba Cloud Tianchi 2024 Cloud Native
                Programming Challenge</span>
            </p>
          </div>
        </div>
      </div>
      <!-- 🎯 Looking for Jobs -->
      <div class="flex flex-col justify-between w-full gap-5 mt-4 md:gap-0 md:flex-row">
        <!-- 工作机会 -->
        <div
          class="bg-stripe w-full md:w-[45%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <p class="text-[12px]">🎯 Looking for Jobs</p>
          <h1 class="mt-2 text-4xl font-bold">工作机会</h1>
          <div class="mt-4 md:text-base lg:text-xl">
            <p class="py-1 text-blue-500">
              💼 Work Experience:
              <a href="https://github.com/LofiSu/LofiSu/blob/main/My%20offer.md" class="underline">myOffer</a>
            </p>
            <p class="py-1 text-green-500">🛠️ Internship:</p>
            <ul>
              <li class="py-1">
                <a href="https://www.bilibili.com/" class="text-pink-500 text-2xl font-bold italic">Bilibili</a>
                <span class="text-purple-500">-- OGV（Occupationally Generated Video）Technical Department
                  + Value-added Front-End Business Group</span>
                <span class="text-green-500 font-mono">`Front-End Engineer`</span>
                <span class="text-red-500">--- `From 2024.7 to Now.`</span>
              </li>
              <li class="py-1">
                <a href="https://www.meituan.com/" class="text-yellow-500 text-2xl font-bold italic">Meituan</a>
                <span class="text-blue-500">-- Takeaway business unit Campus team</span>
                <span class="text-green-500 font-mono">`From 2024.1 to 2024.6.`</span>
              </li>
            </ul>
          </div>
        </div>
        <!-- 🪁 Interests -->
        <div
          class="bg-stripe w-full md:w-[45%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <h2 class="text-2xl font-bold">🪁 Interests</h2>
          <ul class="mt-2 md:text-base lg:text-xl">
            <li>🪄 Traveling</li>
            <li>🎶 Producing Music 🎸 Sing 🎤 My Music: <a href="https://music.163.com/#/artist?id=33710680"
                class="underline">网易云音乐主页</a></li>
            <li>📸 Photography</li>
          </ul>
          <!-- 📫 How to reach me -->
          <h2 class="mt-4 text-2xl font-bold">📫 How to reach me</h2>
          <ul class="mt-2 md:text-base lg:text-xl">
            <li>Email: <a href="mailto:linsu269@gmail.com" class="underline text-blue-500">lofisuchat@gmail.com</a></li>
            <li>GitHub: <a href="https://github.com/LofiSu" class="underline text-blue-500">LofiSu</a></li>
            <li>掘金：<a href="https://juejin.cn/user/2351234356882624" class="underline text-blue-500">LofiSu</a></li>
            <li>Bilibili: <a href="https://space.bilibili.com/489812144?spm_id_from=333.1007.0.0"
                class="underline text-blue-500">空生酥</a></li>
            <li>QQ群号: 953852964</li>
          </ul>
        </div>
      </div>

      <!-- 图片与音乐 -->
      <div class="flex flex-col justify-between w-full gap-5 mt-4 md:gap-0 md:flex-row">
        <!-- 图片 -->
        <div class="w-full md:w-[45%] kawaii-bg bg-center bg-no-repeat bg-cover rounded-xl h-52 sm:h-auto"></div>
        <div
          class="bg-stripe w-full md:w-[50%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <p class="text-[12px]">🎵 Music</p>
          <h1 class="mt-2 text-4xl font-bold text-indigo-600">Future Bass</h1>
          <h1 class="mt-2 text-4xl font-bold text-indigo-600">Pop</h1>
          <h1 class="mt-2 text-4xl font-bold text-indigo-600">Kawaii</h1>
        </div>
      </div>

      <!-- 图片 -->
      <div class="flex flex-col w-full mt-4">
        <img src="../../src/public/hi.jpg" alt="hi" class="w-full rounded-lg" />
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.honer-bg {
  background-image: url("./img/bg.jpg");
}

.music-bg {
  background-image: url("./img/bg.jpg");
  filter: brightness(0.6);
}

.kawaii-bg {
  background-image: url("./img/kawaii.jpg");
}

.avatar-ping {
  animation: avatarPing 2s ease-in infinite;
}

@keyframes avatarPing {

  0%,
  100% {
    transform: translateX(-50%) translateY(-50%) scale(1.05);
  }

  50% {
    transform: translateX(-50%) translateY(-50%) scale(1.1);
  }
}

.tag-bounce {
  animation: tagBounce 1.5s ease-in infinite;
}

@keyframes tagBounce {

  0%,
  100% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-10%);
  }
}

.icon-scroll {
  animation: iconScroll 20s linear infinite;
}

@keyframes iconScroll {
  0% {
    transform: translateX(0);
  }

  100% {
    transform: translateX(-50%);
  }
}
</style>
