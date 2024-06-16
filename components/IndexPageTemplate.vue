<template>
    <div>
        <h1>HTML/CSS入門</h1>
        <h2>内容</h2>
        <ul>
            <li><a href="/1-about">第1回 HTML/CSS/vue.jsについて</a></li>
            <li><a href="/2-html">第2回 HTMLのタグとその役割</a></li>
            <li><a href="/3-css_calactor">第3回 HTMLのClassとCSSによる文字装飾</a></li>
            <li><a href="/4-css_layout">第4回 CSSによるレイアウト作成</a></li>
            <li><a href="/5-responsive">第5回 レスポンシブデザイン</a></li>
        </ul>
    </div>
</template>

<style scoped>
    h1{
        border-bottom: 2px solid skyblue;
    }
    h2{
        border-left: 2px solid pink;
    }
    h3{
        :hover{
            border-bottom: 1px darkgreen;
        }
    }
</style>