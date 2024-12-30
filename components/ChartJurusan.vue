<script setup lang="ts">
import Chart from 'chart.js/auto';

const data = {
  labels: [
    'TBSM',
    'PPLG',
    'DKV',
    'TOI',
    'TJKT'
  ],
  datasets: [{
    label: 'Jumlah Siswa',
    data: [432, 432, 216, 108, 432,],
    backgroundColor: [
      'rgb(255, 0, 0)',
      'rgb(75, 192, 192)',
      'rgb(255, 98, 0)',
      'rgb(201, 203, 207)',
      'rgb(54, 162, 235)'
    ]
  }]
};

  const config = {
  type: 'polarArea',
  data: data,
  options: {}
};

onMounted(() => {
    const myChart = new Chart(
    document.getElementById('myChart'),
    config
  );
})
</script>

<template>
    <div class="p-4">
        <canvas id="myChart"></canvas>
      </div>
      
</template>