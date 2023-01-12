<!-- <template>
    <Bar
      id="my-chart-id"
      :options="chartOptions"
      :data="chartData"
    />
</template>
<script>
import { Bar } from 'vue-chart-3'
import { Chart as ChartJS, Title, Tooltip, Legend, BarElement, CategoryScale, LinearScale } from 'chart.js'

ChartJS.register(Title, Tooltip, Legend, BarElement, CategoryScale, LinearScale)

export default {
  name: 'BarChart',
  components: { Bar },
  data() {
    return {
      chartData: {
        labels: [ 'January', 'February', 'March' ],
        datasets: [ { data: [40, 20, 12] } ]
      },
      chartOptions: {
        responsive: true
      }
    }
  }
}
</script> -->

<template>
  <h1>hff</h1>
</template>
<script>
export default{
  name:'Home'
}
</script>