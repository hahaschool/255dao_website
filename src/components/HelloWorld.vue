<template>
  <div class="hello">
    <h1>{{ msg }}</h1>


    <el-row class="row-bg nes-container with-title is-rounded" justify="center">
      <h2 class="title">Moonbeam Network</h2>
      <el-col :span="24">
        <h3>We are conducting a 2555 GLMR giveaway to our Moonbeam delegators. Please join our <a href="https://t.me/dao255">Telegram community</a> for event details.</h3>
        <p style="word-break: break-word;">
          Collator name: 255 DAO 01 | 🌔✨ <br/>
          Collator address: <a href="https://moonbeam.subscan.io/validator/0xE596665a52D9Bb37865b3a9264fFE038Be08F28d">0xE596665a52D9Bb37865b3a9264fFE038Be08F28d</a>
        </p>
        <p style="word-break: break-word;">
          Collator name: 255 DAO 02 | 🌔✨ <br/>
          Collator address: <a href="https://moonbeam.subscan.io/validator/0x6faf9F07D12D68A3685d34F3262383df40Bd35Cd">0x6faf9F07D12D68A3685d34F3262383df40Bd35Cd</a>
        </p>

      </el-col>
    </el-row>

    <el-row  class="row-bg nes-container with-title is-rounded" justify="center">
      <h2 class="title">Calamari Network</h2>
      <p>255 DAO is proud to be one of the first batch of community collators of Calamari Network. <br>
        Collator address: <a href="https://calamari.subscan.io/validator/dmvvqrfK5AUYH294zTCCiimJRV7CQDDQyC7RAkd5aZgUn9S6f">dmvvqrfK5AUYH294zTCCiimJRV7CQDDQyC7RAkd5aZgUn9S6f</a>
      </p>
    </el-row>

    <el-row type="flex" class="row-bg" justify="center">
      <h2> Join our delegator community</h2>
    </el-row>

  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello {
  margin-bottom: 20px;
}
.row-bg{
  margin-bottom: 20px;
}
</style>
