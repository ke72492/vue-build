<script>
import { RouterLink } from 'vue-router';

export default {
    data() {
        return {

        };
    },

    methods: {

    }
};
</script>

<template>
    <article id="8022cf66-40ef-4e68-bfc8-2fd39ac1aa8a" class="page sans">
        <header><img class="page-cover-image"
                src="https://www.notion.so/images/page-cover/met_terracotta_funerary_plaque.jpg"
                style="object-position:center 9.999999999999998%">
            <div class="page-header-icon page-header-icon-with-cover"><span class="icon">🔉</span></div>

            <ol class="breadcrumb my-5">
                <li class="breadcrumb-item"><router-link to="/">首頁</router-link></li>
                <li class="breadcrumb-item"><router-link to="/vue-basic">Vue基礎</router-link></li>
            </ol>

            <div class="col-md-3 col-lg-2 d-md-block bg-light border my-5">
                <ul class="nav flex-column">
                    <div class="nav-item">目錄</div>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none" href="#74200fbd-c3ea-4f78-af29-6e17a985c339">前言</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none" href="#944dafdf-af57-4eb6-861a-4dea1b34f3fa">Vue的使用</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none" href="#c33d2a88-3c9b-47c9-b316-326f084dee02">Vue條件判斷</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none" href="#b5ba5c6e-3e5e-4530-930b-acdce65ff9b6">Vue的for迴圈寫法</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-decoration-none" href="#7bd686d0-4e84-410d-91e1-d7ab2bff1b31">總結</a>
                    </li>
                </ul>
            </div>

            <h1 class="page-title">Vue基礎</h1>
            <p class="page-description"></p>
        </header>
        <div class="page-body">
            <p id="b683dded-b252-4102-8fb0-e991907b4e54" class="">
            </p>
            <h2 id="74200fbd-c3ea-4f78-af29-6e17a985c339" class="">前言</h2>
            <p id="1c6ed0d0-e894-4e37-942b-edebef7ec1e2" class="">
                接下來我們來介紹一些vue的相關應用，由於vue的寫法和原生的js有滿大的差別，大家可能要花一些時間適應vue的寫法~</p>
            <p id="86e10ec5-4974-42d4-8eee-cf39997c1997" class="">
            </p>
            <h2 id="944dafdf-af57-4eb6-861a-4dea1b34f3fa" class="">Vue的使用</h2>
            <p id="1e9f9c82-2dda-465e-b410-e4758caa5ad6" class="">到Vue網站，引用這段</p>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="183ebbfb-8f5e-4f1a-96f3-7bbe4c6bae16" class="code language-javascript"
                tabindex="0"><code class="language-javascript"><span class="token operator">&lt;</span>script src<span class="token operator">=</span><span class="token string">"https://unpkg.com/vue@3/dist/vue.global.js"</span><span class="token operator">&gt;</span><span class="token operator">&lt;</span><span class="token operator">/</span>script<span class="token operator">&gt;</span></code></pre>
            <p id="c581b360-09aa-476e-badd-f9a02cb8653d" class="">html放置Vue的區域</p>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="95abc809-0bca-4ba1-b5ba-ddcef9dcbe11" class="code language-html"
                tabindex="0"><code class="language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>div</span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>app<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>div</span><span class="token punctuation">&gt;</span></span></code></pre>
            <p id="2a076dab-49e6-4653-9b22-b4beaef370d0" class="">JS的寫法，整個是物件，data為宣告變數，透過mount設置在dom元素上</p>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="ddbd1148-1e20-4086-b4eb-1f827ac087fa" class="code language-javascript"
                tabindex="0"><code class="language-javascript"><span class="token keyword">const</span> app <span class="token operator">=</span> Vue<span class="token punctuation">.</span><span class="token function">createApp</span><span class="token punctuation">(</span><span class="token punctuation">{</span>
    <span class="token comment">// 放變數的地方</span>
    <span class="token function">data</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
        <span class="token keyword">return</span><span class="token punctuation">{</span>
            <span class="token literal-property property">message</span><span class="token operator">:</span><span class="token string">'Hello World'</span><span class="token punctuation">,</span>
        <span class="token punctuation">}</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>

app<span class="token punctuation">.</span><span class="token function">mount</span><span class="token punctuation">(</span><span class="token string">'#app'</span><span class="token punctuation">)</span><span class="token punctuation">;</span></code></pre>
            <p id="fc1c4537-7a74-4917-b5c5-e08392924e63" class="">html可以使用兩個大括號呼叫變數</p>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="3b852815-ff83-4524-9ae5-24dc00877999" class="code language-html"
                tabindex="0"><code class="language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>div</span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>app<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>{{ message }}<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>div</span><span class="token punctuation">&gt;</span></span></code></pre>
            <p id="e3d7e9a2-ae28-48d8-93ef-9e15ce8546af" class="">
            </p>
            <p id="127a6561-078e-4906-bbf0-6413510a5eb2" class="">接著是function的寫法</p>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="bb367638-2d69-4771-89c2-b7361b78feed" class="code language-javascript" tabindex="0"><code class="language-javascript"><span class="token literal-property property">methods</span><span class="token operator">:</span><span class="token punctuation">{</span>
    <span class="token comment">// 改變姓名</span>
    <span class="token function">changeName</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
        <span class="token keyword">this</span><span class="token punctuation">.</span>name<span class="token operator">=</span><span class="token string">'Mark'</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token function">changeHobby</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
        <span class="token keyword">this</span><span class="token punctuation">.</span>hobby<span class="token operator">=</span><span class="token string">'健身'</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token function">changeWord</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
        <span class="token keyword">this</span><span class="token punctuation">.</span>word<span class="token operator">=</span><span class="token string">'選擇有興趣的事'</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span><span class="token punctuation">,</span>
<span class="token punctuation">}</span><span class="token punctuation">,</span></code></pre>
            <p id="8eb0e244-e6a3-424d-8d11-6a86a80f97fb" class="">html上面直接寫監聽事件</p>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="70cf4b4b-f660-4a9b-a7e4-efabdaecece6" class="code language-html"
                tabindex="0"><code class="language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>button<span class="token punctuation">"</span></span> <span class="token attr-name"><span class="token namespace">v-on:</span>click</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>changeName()<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>改變名字<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>button<span class="token punctuation">"</span></span> <span class="token attr-name"><span class="token namespace">v-on:</span>click</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>changeHobby()<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>改變興趣<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>button<span class="token punctuation">"</span></span> <span class="token attr-name"><span class="token namespace">v-on:</span>click</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>changeWord()<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>改變座右銘<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span></code></pre>
            <p id="6d0d1458-cb94-43d5-aca6-9550f1765c82" class="">縮寫與其他用法</p>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="9c8a0e25-48f4-4cf0-9490-2fe49be80142" class="code language-html"
                tabindex="0"><code class="language-html"><span class="token comment">&lt;!-- 用{{}}放入變數即可渲染資料至畫面 --&gt;</span>
<span class="token comment">&lt;!-- v-on:用來綁定事件 --&gt;</span>
<span class="token comment">&lt;!-- v-on的縮寫是@ --&gt;</span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>姓名:{{ name }}<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>興趣:{{ hobby }}<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>座右銘:{{ word }}<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>button<span class="token punctuation">"</span></span> <span class="token attr-name">@click</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>changeName<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>改變名字<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>button<span class="token punctuation">"</span></span> <span class="token attr-name">@click</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>changeHobby<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>改變興趣<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>button<span class="token punctuation">"</span></span> <span class="token attr-name">@click</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>changeWord<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>改變座右銘<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>button<span class="token punctuation">"</span></span> <span class="token attr-name">@mouseenter</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>changeWord<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>改變座右銘<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span></code></pre>
            <p id="e679a67f-9e3c-46b9-9d2d-ba1328b319c5" class="">
            </p>
            <h2 id="c33d2a88-3c9b-47c9-b316-326f084dee02" class="">Vue條件判斷</h2>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="cd20ed06-6a81-48e3-9fc7-0c86e04cfb6e" class="code language-html"
                tabindex="0"><code class="language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>div</span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>app<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token comment">&lt;!-- v-show 當為false時會在dom元素上加入&lt;display:none&gt;&lt;/display:none&gt; --&gt;</span>
   <span class="token comment">&lt;!-- v-show 會將傳熱的值轉變成布林值判斷 --&gt;</span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span> <span class="token attr-name">v-show</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>show<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Hello World<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span> <span class="token attr-name">v-show</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>!show<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>How are you?<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>button</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>button<span class="token punctuation">"</span></span> <span class="token attr-name">@click</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>show = !show<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>切換<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>button</span><span class="token punctuation">&gt;</span></span>

  <span class="token comment">&lt;!-- v-if當符合條件才會:"渲染"元素 --&gt;</span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span> <span class="token attr-name">v-if</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>show<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>出門<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span> <span class="token attr-name">v-else</span><span class="token punctuation">&gt;</span></span>不出門<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>

<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>div</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>script</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>https://unpkg.com/vue@3/dist/vue.global.js<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span><span class="token script"></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>script</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>script</span><span class="token punctuation">&gt;</span></span><span class="token script"><span class="token language-javascript">
  <span class="token keyword">const</span> app<span class="token operator">=</span>Vue<span class="token punctuation">.</span><span class="token function">createApp</span><span class="token punctuation">(</span><span class="token punctuation">{</span>
      <span class="token function">data</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
          <span class="token keyword">return</span><span class="token punctuation">{</span>
              <span class="token literal-property property">show</span><span class="token operator">:</span><span class="token boolean">false</span><span class="token punctuation">,</span>
          <span class="token punctuation">}</span><span class="token punctuation">;</span>
      <span class="token punctuation">}</span><span class="token punctuation">,</span>
      <span class="token literal-property property">methods</span><span class="token operator">:</span><span class="token punctuation">{</span>

      <span class="token punctuation">}</span><span class="token punctuation">,</span>
  <span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
  app<span class="token punctuation">.</span><span class="token function">mount</span><span class="token punctuation">(</span><span class="token string">'#app'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>script</span><span class="token punctuation">&gt;</span></span></code></pre>
            <p id="f8e348db-d6a1-4ae7-bb2d-67a5b2959c61" class="">
            </p>
            <p id="6caa9ac5-5317-42b9-86b9-3713fcd7ebfa" class="">v-if和vishow差在效能的不同，v-show比v-if省效能，使用取決於是否常開關</p>
            <p id="339d09c4-73ee-4103-9c9b-7dbb52b4a6c6" class="">
            </p>
            <p id="a80bf96e-ab8b-405e-abd0-9b515fa0d0d3" class="">
                有感覺到vue和原生js的差別了嗎?vue的很多程式會直接寫在dom元素上面，讓程式碼的部分比較簡短，並且他們也提供一些縮寫方式讓程式碼看起來更簡潔!</p>
            <p id="21d03800-7bf0-4691-a07b-b76264b5eabc" class="">
            </p>
            <h2 id="b5ba5c6e-3e5e-4530-930b-acdce65ff9b6" class="">Vue的for迴圈寫法</h2>
            <!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js"
                integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg=="
                crossorigin="anonymous" referrerpolicy="no-referrer"></script> -->
            <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css"
                integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ=="
                crossorigin="anonymous" referrerpolicy="no-referrer">
            <pre id="e0fe5367-5e1c-4ae4-921c-8ef73ff9680c" class="code language-html"
                tabindex="0"><code class="language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>div</span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>app<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>ul</span><span class="token punctuation">&gt;</span></span>
        <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>li</span> <span class="token attr-name">v-for</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>(item,index) in lists<span class="token punctuation">"</span></span> <span class="token attr-name">:key</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>index<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>{{ item }}<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>li</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>ul</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>div</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>script</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>https://unpkg.com/vue@3/dist/vue.global.js<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span><span class="token script"></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>script</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>script</span><span class="token punctuation">&gt;</span></span><span class="token script"><span class="token language-javascript">
    <span class="token keyword">const</span> app<span class="token operator">=</span>Vue<span class="token punctuation">.</span><span class="token function">createApp</span><span class="token punctuation">(</span><span class="token punctuation">{</span>
        <span class="token function">data</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">{</span>
            <span class="token keyword">return</span><span class="token punctuation">{</span>
                <span class="token literal-property property">lists</span><span class="token operator">:</span><span class="token punctuation">[</span><span class="token number">1</span><span class="token punctuation">,</span><span class="token number">2</span><span class="token punctuation">,</span><span class="token number">3</span><span class="token punctuation">]</span><span class="token punctuation">,</span>
            <span class="token punctuation">}</span><span class="token punctuation">;</span>
        <span class="token punctuation">}</span><span class="token punctuation">,</span>
        <span class="token literal-property property">methods</span><span class="token operator">:</span><span class="token punctuation">{</span>

        <span class="token punctuation">}</span><span class="token punctuation">,</span>
    <span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    app<span class="token punctuation">.</span><span class="token function">mount</span><span class="token punctuation">(</span><span class="token string">'#app'</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>script</span><span class="token punctuation">&gt;</span></span></code></pre>
            <p id="fffe2388-3af5-4dea-951a-7759743c9190" class="">
            </p>
            <h2 id="7bd686d0-4e84-410d-91e1-d7ab2bff1b31" class="">總結</h2>
            <p id="7b08fd69-c89a-42e7-881e-bb84bea9c770" class="">
                這篇介紹了一些vue的語法，剛寫到vue的時候會覺得和之前的原生js差很多是正常的，這部分可能就需要花時間熟悉vue的使用，下一篇會介紹更多vue的相關使用方式</p>
        </div>
    </article><span class="sans" style="font-size:14px;padding-top:2em"></span>
</template>

<style scoped>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
/* html {
	-webkit-print-color-adjust: exact;
} */
* {
    box-sizing: border-box;
    /* -webkit-print-color-adjust: exact; */
}

html,
body {
    margin: 0;
    padding: 0;
}

@media only screen {
    body {
        margin: 2em auto;
        max-width: 900px;
        color: rgb(55, 53, 47);
    }
}

body {
    line-height: 1.5;
    white-space: pre-wrap;
}

a,
a.visited {
    color: inherit;
    text-decoration: underline;
}

.pdf-relative-link-path {
    font-size: 80%;
    color: #444;
}

h1,
h2,
h3 {
    letter-spacing: -0.01em;
    line-height: 1.2;
    font-weight: 600;
    margin-bottom: 0;
}

.page-title {
    font-size: 2.5rem;
    font-weight: 700;
    margin-top: 0;
    margin-bottom: 0.75em;
}

h1 {
    font-size: 1.875rem;
    margin-top: 1.875rem;
}

h2 {
    font-size: 1.5rem;
    margin-top: 1.5rem;
}

h3 {
    font-size: 1.25rem;
    margin-top: 1.25rem;
}

.source {
    border: 1px solid #ddd;
    border-radius: 3px;
    padding: 1.5em;
    word-break: break-all;
}

.callout {
    border-radius: 3px;
    padding: 1rem;
}

figure {
    margin: 1.25em 0;
    page-break-inside: avoid;
}

figcaption {
    opacity: 0.5;
    font-size: 85%;
    margin-top: 0.5em;
}

mark {
    background-color: transparent;
}

.indented {
    padding-left: 1.5em;
}

hr {
    background: transparent;
    display: block;
    width: 100%;
    height: 1px;
    visibility: visible;
    border: none;
    border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
    max-width: 100%;
}

@media only print {
    img {
        max-height: 100vh;
        object-fit: contain;
    }
}

@page {
    margin: 1in;
}

.collection-content {
    font-size: 0.875rem;
}

.column-list {
    display: flex;
    justify-content: space-between;
}

.column {
    padding: 0 1em;
}

.column:first-child {
    padding-left: 0;
}

.column:last-child {
    padding-right: 0;
}

.table_of_contents-item {
    display: block;
    font-size: 0.875rem;
    line-height: 1.3;
    padding: 0.125rem;
}

.table_of_contents-indent-1 {
    margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
    margin-left: 3rem;
}

.table_of_contents-indent-3 {
    margin-left: 4.5rem;
}

.table_of_contents-link {
    text-decoration: none;
    opacity: 0.7;
    border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
    border: 1px solid rgba(55, 53, 47, 0.09);
    border-collapse: collapse;
}

table {
    border-left: none;
    border-right: none;
}

th,
td {
    font-weight: normal;
    padding: 0.25em 0.5em;
    line-height: 1.5;
    min-height: 1.5em;
    text-align: left;
}

th {
    color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
    margin: 0;
    margin-block-start: 0.6em;
    margin-block-end: 0.6em;
}

li>ol:first-child,
li>ul:first-child {
    margin-block-start: 0.6em;
}

ul>li {
    list-style: disc;
}

ul.to-do-list {
    padding-inline-start: 0;
}

ul.to-do-list>li {
    list-style: none;
}

.to-do-children-checked {
    text-decoration: line-through;
    opacity: 0.375;
}

ul.toggle>li {
    list-style: none;
}

ul {
    padding-inline-start: 1.7em;
}

ul>li {
    padding-left: 0.1em;
}

ol {
    padding-inline-start: 1.6em;
}

ol>li {
    padding-left: 0.2em;
}

.mono ol {
    padding-inline-start: 2em;
}

.mono ol>li {
    text-indent: -0.4em;
}

.toggle {
    padding-inline-start: 0em;
    list-style-type: none;
}

/* Indent toggle children */
.toggle>li>details {
    padding-left: 1.7em;
}

.toggle>li>details>summary {
    margin-left: -1.1em;
}

.selected-value {
    display: inline-block;
    padding: 0 0.5em;
    background: rgba(206, 205, 202, 0.5);
    border-radius: 3px;
    margin-right: 0.5em;
    margin-top: 0.3em;
    margin-bottom: 0.3em;
    white-space: nowrap;
}

.collection-title {
    display: inline-block;
    margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
    margin-top: 1em;
    font-size: 0.875rem;
    empty-cells: show;
}

.simple-table td {
    height: 29px;
    min-width: 120px;
}

.simple-table th {
    height: 29px;
    min-width: 120px;
}

.simple-table-header-color {
    background: rgb(247, 246, 243);
    color: black;
}

.simple-table-header {
    font-weight: 500;
}

time {
    opacity: 0.5;
}

.icon {
    display: inline-block;
    max-width: 1.2em;
    max-height: 1.2em;
    text-decoration: none;
    vertical-align: text-bottom;
    margin-right: 0.5em;
}

img.icon {
    border-radius: 3px;
}

.user-icon {
    width: 1.5em;
    height: 1.5em;
    border-radius: 100%;
    margin-right: 0.5rem;
}

.user-icon-inner {
    font-size: 0.8em;
}

.text-icon {
    border: 1px solid #000;
    text-align: center;
}

.page-cover-image {
    display: block;
    object-fit: cover;
    width: 100%;
    max-height: 30vh;
}

.page-header-icon {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.page-header-icon-with-cover {
    margin-top: -0.72em;
    margin-left: 0.07em;
}

.page-header-icon img {
    border-radius: 3px;
}

.link-to-page {
    margin: 1em 0;
    padding: 0;
    border: none;
    font-weight: 500;
}

p>.user {
    opacity: 0.5;
}

td>.user,
td>time {
    white-space: nowrap;
}

input[type="checkbox"] {
    transform: scale(1.5);
    margin-right: 0.6em;
    vertical-align: middle;
}

p {
    margin-top: 0.5em;
    margin-bottom: 0.5em;
}

.image {
    border: none;
    margin: 1.5em 0;
    padding: 0;
    border-radius: 0;
    text-align: center;
}

.code,
code {
    background: rgba(135, 131, 120, 0.15);
    border-radius: 3px;
    padding: 0.2em 0.4em;
    border-radius: 3px;
    font-size: 85%;
    tab-size: 2;
}

code {
    color: #eb5757;
}

.code {
    padding: 1.5em 1em;
}

.code-wrap {
    white-space: pre-wrap;
    word-break: break-all;
}

.code>code {
    background: none;
    padding: 0;
    font-size: 100%;
    color: inherit;
}

blockquote {
    font-size: 1.25em;
    margin: 1em 0;
    padding-left: 1em;
    border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
    text-decoration: none;
    max-height: 8em;
    padding: 0;
    display: flex;
    width: 100%;
    align-items: stretch;
}

.bookmark-title {
    font-size: 0.85em;
    overflow: hidden;
    text-overflow: ellipsis;
    height: 1.75em;
    white-space: nowrap;
}

.bookmark-text {
    display: flex;
    flex-direction: column;
}

.bookmark-info {
    flex: 4 1 180px;
    padding: 12px 14px 14px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.bookmark-image {
    width: 33%;
    flex: 1 1 180px;
    display: block;
    position: relative;
    object-fit: cover;
    border-radius: 1px;
}

.bookmark-description {
    color: rgba(55, 53, 47, 0.6);
    font-size: 0.75em;
    overflow: hidden;
    max-height: 4.5em;
    word-break: break-word;
}

.bookmark-href {
    font-size: 0.75em;
    margin-top: 0.25em;
}

.sans {
    font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol";
}

.code {
    font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace;
}

.serif {
    font-family: Lyon-Text, Georgia, ui-serif, serif;
}

.mono {
    font-family: iawriter-mono, Nitti, Menlo, Courier, monospace;
}

.pdf .sans {
    font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP';
}

.pdf:lang(zh-CN) .sans {
    font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC';
}

.pdf:lang(zh-TW) .sans {
    font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC';
}

.pdf:lang(ko-KR) .sans {
    font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR';
}

.pdf .code {
    font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP';
}

.pdf:lang(zh-CN) .code {
    font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC';
}

.pdf:lang(zh-TW) .code {
    font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC';
}

.pdf:lang(ko-KR) .code {
    font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR';
}

.pdf .serif {
    font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP';
}

.pdf:lang(zh-CN) .serif {
    font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC';
}

.pdf:lang(zh-TW) .serif {
    font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC';
}

.pdf:lang(ko-KR) .serif {
    font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR';
}

.pdf .mono {
    font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP';
}

.pdf:lang(zh-CN) .mono {
    font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC';
}

.pdf:lang(zh-TW) .mono {
    font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC';
}

.pdf:lang(ko-KR) .mono {
    font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR';
}

.highlight-default {
    color: rgba(55, 53, 47, 1);
}

.highlight-gray {
    color: rgba(120, 119, 116, 1);
    fill: rgba(120, 119, 116, 1);
}

.highlight-brown {
    color: rgba(159, 107, 83, 1);
    fill: rgba(159, 107, 83, 1);
}

.highlight-orange {
    color: rgba(217, 115, 13, 1);
    fill: rgba(217, 115, 13, 1);
}

.highlight-yellow {
    color: rgba(203, 145, 47, 1);
    fill: rgba(203, 145, 47, 1);
}

.highlight-teal {
    color: rgba(68, 131, 97, 1);
    fill: rgba(68, 131, 97, 1);
}

.highlight-blue {
    color: rgba(51, 126, 169, 1);
    fill: rgba(51, 126, 169, 1);
}

.highlight-purple {
    color: rgba(144, 101, 176, 1);
    fill: rgba(144, 101, 176, 1);
}

.highlight-pink {
    color: rgba(193, 76, 138, 1);
    fill: rgba(193, 76, 138, 1);
}

.highlight-red {
    color: rgba(212, 76, 71, 1);
    fill: rgba(212, 76, 71, 1);
}

.highlight-default_background {
    color: rgba(55, 53, 47, 1);
}

.highlight-gray_background {
    background: rgba(241, 241, 239, 1);
}

.highlight-brown_background {
    background: rgba(244, 238, 238, 1);
}

.highlight-orange_background {
    background: rgba(251, 236, 221, 1);
}

.highlight-yellow_background {
    background: rgba(251, 237, 214, 1);
}

.highlight-teal_background {
    background: rgba(237, 243, 236, 1);
}

.highlight-blue_background {
    background: rgba(231, 243, 248, 1);
}

.highlight-purple_background {
    background: rgba(244, 240, 247, 0.8);
}

.highlight-pink_background {
    background: rgba(249, 238, 243, 0.8);
}

.highlight-red_background {
    background: rgba(253, 235, 236, 1);
}

.block-color-default {
    color: inherit;
    fill: inherit;
}

.block-color-gray {
    color: rgba(120, 119, 116, 1);
    fill: rgba(120, 119, 116, 1);
}

.block-color-brown {
    color: rgba(159, 107, 83, 1);
    fill: rgba(159, 107, 83, 1);
}

.block-color-orange {
    color: rgba(217, 115, 13, 1);
    fill: rgba(217, 115, 13, 1);
}

.block-color-yellow {
    color: rgba(203, 145, 47, 1);
    fill: rgba(203, 145, 47, 1);
}

.block-color-teal {
    color: rgba(68, 131, 97, 1);
    fill: rgba(68, 131, 97, 1);
}

.block-color-blue {
    color: rgba(51, 126, 169, 1);
    fill: rgba(51, 126, 169, 1);
}

.block-color-purple {
    color: rgba(144, 101, 176, 1);
    fill: rgba(144, 101, 176, 1);
}

.block-color-pink {
    color: rgba(193, 76, 138, 1);
    fill: rgba(193, 76, 138, 1);
}

.block-color-red {
    color: rgba(212, 76, 71, 1);
    fill: rgba(212, 76, 71, 1);
}

.block-color-default_background {
    color: inherit;
    fill: inherit;
}

.block-color-gray_background {
    background: rgba(241, 241, 239, 1);
}

.block-color-brown_background {
    background: rgba(244, 238, 238, 1);
}

.block-color-orange_background {
    background: rgba(251, 236, 221, 1);
}

.block-color-yellow_background {
    background: rgba(251, 237, 214, 1);
}

.block-color-teal_background {
    background: rgba(237, 243, 236, 1);
}

.block-color-blue_background {
    background: rgba(231, 243, 248, 1);
}

.block-color-purple_background {
    background: rgba(244, 240, 247, 0.8);
}

.block-color-pink_background {
    background: rgba(249, 238, 243, 0.8);
}

.block-color-red_background {
    background: rgba(253, 235, 236, 1);
}

.select-value-color-uiBlue {
    background-color: rgba(35, 131, 226, .07);
}

.select-value-color-pink {
    background-color: rgba(245, 224, 233, 1);
}

.select-value-color-purple {
    background-color: rgba(232, 222, 238, 1);
}

.select-value-color-green {
    background-color: rgba(219, 237, 219, 1);
}

.select-value-color-gray {
    background-color: rgba(227, 226, 224, 1);
}

.select-value-color-transparentGray {
    background-color: rgba(227, 226, 224, 0);
}

.select-value-color-translucentGray {
    background-color: rgba(0, 0, 0, 0.06);
}

.select-value-color-orange {
    background-color: rgba(250, 222, 201, 1);
}

.select-value-color-brown {
    background-color: rgba(238, 224, 218, 1);
}

.select-value-color-red {
    background-color: rgba(255, 226, 221, 1);
}

.select-value-color-yellow {
    background-color: rgba(249, 228, 188, 1);
}

.select-value-color-blue {
    background-color: rgba(211, 229, 239, 1);
}

.select-value-color-pageGlass {
    background-color: undefined;
}

.select-value-color-washGlass {
    background-color: undefined;
}

.checkbox {
    display: inline-flex;
    vertical-align: text-bottom;
    width: 16;
    height: 16;
    background-size: 16px;
    margin-left: 2px;
    margin-right: 5px;
}

.checkbox-on {
    background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
    background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
</style>