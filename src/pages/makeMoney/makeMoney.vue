<template>
  <div class="container">
    <money-header title="赚钱"></money-header>
    <money-subtitle></money-subtitle>
    <money-slider></money-slider>
    <money-list></money-list>
    <money-vslider></money-vslider>
    <money-blank></money-blank>
    <money-insurance></money-insurance>
    <money-strip></money-strip>
    <money-copyright></money-copyright>
    <money-footer></money-footer>
  </div>
</template>

<script>
import moneyHeader from '../public/header'
import moneySubtitle from '../public/subtitle'
import moneySlider from '../home/components/slider'
import moneyList from './components/list'
import moneyVslider from './components/vSlider'
import moneyBlank from './components/blank'
import moneyInsurance from './components/insurance'
import moneyStrip from './components/strip'
import moneyCopyright from './components/copyright'
import moneyFooter from '../public/footer'
export default{
  name: 'makeMoney',
  components: {
    moneyHeader,
    moneySubtitle,
    moneySlider,
    moneyList,
    moneyVslider,
    moneyBlank,
    moneyInsurance,
    moneyStrip,
    moneyCopyright,
    moneyFooter
  }
}
</script>

<style lang="scss">
.container{
  background-color:#eee;
}
</style>
