<script setup lang="ts">
import Chart from 'chart.js/auto';

const data = {
  labels: [
    'Angkatan 10',
    'Angkatan 11',
    'Ankatan 12'
  ],
  datasets: [{
    label: 'My First Dataset',
    data: [500, 500, 500],
    backgroundColor: [
      'rgb(255, 99, 132)',
      'rgb(54, 162, 235)',
      'rgb(255, 205, 86)'
    ],
    hoverOffset: 4
  }]
};


  const config = {
  type: 'doughnut',
  data: data,
};

onMounted(() => {
    const myChart = new Chart(
    document.getElementById('Chart'),
    config
  );
})
</script>

<template>
    <div class="p-4">
        <canvas id="Chart"></canvas>
      </div>
      
</template>
<style>
tes{
  color: rgb(152, 152, 152);
}
</style>