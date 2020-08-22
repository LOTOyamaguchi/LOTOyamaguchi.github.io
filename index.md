Vue.jsの学習

1日目
idを付ける。appと言う名前が多い

<div id="app">
{{ message }}
</div>
<script src="https://cdn.jsdelivr.net/npm/vue@2.5.16/dist/vue.min.js"></script>
<script>
    new Vue({
        el: '#app',
        data: {
            message: "ハロー"
        }
    });
</script>

基本的な流れ
idを定義
new Vue以下dataまたはmethodsを定義

用語：
ディレクティブ　属性
データバインド　要するにVueで変えたい箇所を指定する方法。{{ }}はHTMLの中でしか使えないため、属性を変えたいときにはデータバインドを使う
v-on　クリックで動かしたい関数を指定。　


学習したもん
https://blog.capilano-fw.com/?p=648
https://www.youtube.com/playlist?list=PLh6V6_7fbbo-SZYHHBVFstU2tp0dDZMAW
                
               
