<template>
  <div class="h-screen flex flex-col items-center justify-center text-lg">
    <work-in-progress />
  </div>
</template>

<script>
import axios from 'axios';
import Vue from 'vue';
import Layout from '@/Layout/Layout';
import WorkInProgress from '@/Component/WorkInProgress';
import { Themes } from '@/Script/theme/Theme';

export default {
  layout: Layout,
  layoutName: 'default',
  title: 'admin.dashboard',
  components: {
    WorkInProgress,
  },
};
</script>
