<template>
    <div>
        <h1>第1回 HTML/CSS/vue.jsについて</h1>
        <h2>実習1-1 Node.jsの動作検証</h2>
        <h3>目的</h3>
        <p>Node.jsによる開発用サーバーの開始方法を知るとともに、デバイスに正しくNode.jsがインストールされたことを確認する。</p>
        <h3>手順</h3>
        <ol>
            <li><a href="https://github.com/klef-project/lec-html_css">READMEファイルを参照し、本リポジトリをクローンせよ。</a></li>
            <li><p><code>yarn dev</code>を実行し、localhostにアクセスすると、トップページが表示されることを確認せよ。</p></li>
            <li><p>トップページ内のリンクが正しく機能していることを確認せよ。</p></li>
        </ol>
        <h2>実習1-2 VSCodeでファイル変更</h2>
        <h3>目的</h3>
        <p>htmlおよびvueの構造を理解し、変更するときちんと反映されることを確認する。</p>
        <h3>手順</h3>
        <ol>
            <li>本リポジトリのルートでVSCodeを起動せよ。</li>
            <li>ページを構成するファイルが"pages"ディレクトリにあることを確認せよ。</li>
            <li>vueファイルの<code>template</code>タグ内はすべて何らかのタグで囲まれていることを確認せよ。</li>
            <li>"pages/1-about/work.vue"に文字を追加し、ファイルを保存せよ。</li>
            <li>ブラウザを起動し、先の手順で行った変更が反映されていることを確認せよ。</li>
        </ol>
        <h2>実習1-3 特別なファイル名</h2>
        <h3>目的</h3>
        <p>"index"などの特殊な名称のファイルの役割を理解する。</p>
        <h3>手順</h3>
        <ol>
            <li>本ディレクトリのルートでVSCodeまたはファイルマネージャーを起動せよ。</li>
            <li>"pages/index.vue"を"pages/main.vue"に変更し、トップページを開くと404 Not Foundエラーが返されることを確認せよ。</li>
            <li>ファイル名を戻すと、エラーが治り、トップページが表示されることを確認せよ。</li>
        </ol>
    </div>
</template>