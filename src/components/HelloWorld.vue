<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Welcome to Nano Playground
        </h1>
        <p>My playground created just for myself</p>
      </v-col>


      <v-timeline
      :dense="$vuetify.breakpoint.smAndDown"
      id="timeline"
      >
    <v-timeline-item
      color="purple lighten-2"
      fill-dot
      right

    >
      <v-card>
        <v-card-title class="purple lighten-2">
          <v-icon
            dark
            size="42"
            class="mr-4"
          >
            mdi-magnify
          </v-icon>
          <h2 class="display-1 white--text font-weight-light">生まれ</h2>
        </v-card-title>
        <v-container>
          <v-row>
            <v-col cols="12" md="10">
              千葉県で生まれたが両親が中国人で生後数カ月で中国に左遷されました（楽しかったです）。強いて言うならもう少し中国にいて中国語ちゃんと喋れたかったなぁ。
            </v-col>
            <v-col
              class="hidden-sm-and-down text-right"
              md="2"
            >
              <v-icon size="64">mdi-calendar-text</v-icon>
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </v-timeline-item>

    <v-timeline-item
      color="amber lighten-1"
      fill-dot
      left
      small
    >
      <v-card>
        <v-card-title class="amber lighten-1 justify-end">
          <h2 class="display-1 mr-4 white--text font-weight-light">学生①</h2>
          <v-icon
            dark
            size="42"
          >mdi-home-outline</v-icon>
        </v-card-title>
        <v-container>
          <v-row>
            <v-col cols="12" md="10">
              日本に帰り2~3年で埼玉へ引っ越す、それからはずっと埼玉です。小・中学校は地元の公立学校でのほほんと生活しました。色々あって中学で内向的だったのが外向的になりました。
            </v-col><v-col
              class="hidden-sm-and-down text-right"
              md="2"
            >
              <v-icon size="64">mdi-call-split</v-icon>
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </v-timeline-item>

    <v-timeline-item
      color="cyan lighten-1"
      fill-dot
      right
    >
      <v-card>
        <v-card-title class="cyan lighten-1">
          <v-icon
            class="mr-4"
            dark
            size="42"
          >
            mdi-school-outline
          </v-icon>
          <h2 class="display-1 white--text font-weight-light">学生②</h2>
        </v-card-title>
        <v-container>
          <v-row>
            <v-col
              cols="12"
              md="12"
            >
              中学の成績がよく僕は幸いにも県でも有数の男子校に入れました。ここでは自分の人生を刺激する出会いが沢山あってその分思い出も自分の人生哲学のルートも、いろんなものを与えられた場所になりました。
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </v-timeline-item>

    <v-timeline-item
      color="red lighten-1"
      fill-dot
      left
      small
    >
      <v-card>
        <v-card-title class="red lighten-1 justify-end">
          <h2 class="display-1 mr-4 white--text font-weight-light">学生③</h2>
          <v-icon
            dark
            size="42"
          >
            mdi-pill
          </v-icon>
        </v-card-title>
        <v-container>
          <v-row>
            <v-col class="hidden-sm-and-down" md="2">
              <v-icon size="64">mdi-doctor</v-icon>
            </v-col>
            <v-col cols="12" md="10">
              だいぶ苦労の末ですが高校の成績も幸い良かったため医学部に入学することができました。大学一年生は受験の疲れからか突然始めた一人暮らしのせいかずっと友達と一緒にいろんなことしてました。学年が上がるに連れて自分の行く先が少しずつ現実味を帯びてきました。
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </v-timeline-item>

    <v-timeline-item
      color="green lighten-1"
      fill-dot
      right
    >
      <v-card>
        <v-card-title class="green lighten-1">
          <v-icon
            class="mr-4"
            dark
            size="42"
          >
            mdi-brain
          </v-icon>
          <h2 class="display-1 white--text font-weight-light">学生④</h2>
        </v-card-title>
        <v-container>
          <v-row>
            <v-col>
              医学の勉強は確かに楽しいですが、自分の一生を捧げる気にはなりません、自分にできる面白いことを探そうと少しプログラミングの勉強を始めてみます
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </v-timeline-item>
    <v-timeline-item
    color="lime dark-1"
    fill-dot
    left
    small
    >
    <v-card>
      <v-card-title class="lime dark-1">
        <v-icon
            class="mr-4"
            dark
            size="42"
          >
            mdi-road-variant
        </v-icon>
        <h2 class="display-1 white--text font-weight-light">Yet to be explored</h2>
      </v-card-title>
      <v-container>
        <v-row>
          <v-col>

          </v-col>
        </v-row>
      </v-container>
    </v-card>
    </v-timeline-item>
  </v-timeline>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
    }),
  }
</script>
