<template>
  <Header />
  <TotalPending />
  <Breakdown />
  <div class="container">
    <TaskList />
    <AddTask />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import TotalPending from './components/TotalPending.vue';
import Breakdown from './components/Breakdown.vue';
import TaskList from './components/TaskList.vue';
import AddTask from './components/AddTask.vue';

export default {
  components: {
    Header,
    TotalPending,
    Breakdown,
    TaskList,
    AddTask,
  },
};
</script>
