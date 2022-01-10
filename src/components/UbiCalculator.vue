<template>
  <div class="ubicalculator">
    <h1>{{ msg }}</h1>
    <p>
      A simple calculator to estimate the impact a Universal Basic Income (UBI) would have on your after tax income
    </p>
    <p>How much should the UBI be? <br>enter the value in AUD $24,000 </p>
    <p>What should it replace?<br>Tick boxes: Everything(if not everything we can't make admin neglible, but we will still assume it is)</p>
    <p>
      Welfare (does this include public healthcare?) expenditure in 2018-2019 was apprximately $171.62 billion. <a href="https://www.aihw.gov.au/reports/australias-welfare/welfare-expenditure">Source</a>
      <br> This year's budget was selected to minimize the impact made by COVID-19. 
      <br> There are an estimated 17.6 million Australians who are eligible to vote. I am assuming this is the number of Australians that would be eligible for the UBI. <a href="https://aec.gov.au/Enrolling_to_vote/Enrolment_stats/">Source</a>
      <br> This would result in a welfare expenditure of [calculated] $422 billion 
    </p>
    <p>
      This expenditure makes up % of the current budget. Currently taxes make up % of government income.
      We will assume that the proportion of government income remains consistent, that is, if the amount of taxes required increases, this will be mitigated by an equal rising in the amount of other government income. This could be a check box?
    </p>
    <p>
    This means tax revenue would have to increase by an absolute of: 
    </p>

  </div>
</template>

<script>
export default {
  name: 'UbiCalculator',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
