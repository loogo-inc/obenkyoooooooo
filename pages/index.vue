<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div class="text-center">
        <logo />
        <vuetify-logo />
      </div>
      <h2><a href="/corp.html">企業ページに移動</a></h2>
      <v-card>
        <v-card-title class="headline">
          Vuetify + Nuxt.jsテンプレートへようこそ
        </v-card-title>
        <v-card-text>
          <p>Vuetifyは、Vue.js用のプログレッシブマテリアルデザインコンポーネントフレームワークです。これは、開発者がすばらしいアプリケーションを作成できるようにするために設計されました。</p>
          <p>
            Vuetifyの詳細については、<a
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
            >
              ドキュメントを 
            </a>確認してください。
          </p>
          <p>
            ご不明な点がございましたら、公式の<a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              rel="noopener noreferrer"
              title="chat"
            >
              不和に
            </a>ご参加ください。
          </p>
          <p>
            バグを見つけますか？github<a
              href="https://github.com/vuetifyjs/vuetify/issues"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              発行ボードで 
            </a>報告してください。
          </p>
          <p>Vuetifyで開発していただきありがとうございます。今後、よりエキサイティングな機能を提供できることを楽しみにしています。</p>
          <div class="text-xs-right">
            <em><small>&mdash; ジョン・ライダー</small></em>
          </div>
          <hr class="my-3">
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxtドキュメント
          </a>
          <br>
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            rel="noopener noreferrer"
          >
            NuxtGitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            継続する
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
