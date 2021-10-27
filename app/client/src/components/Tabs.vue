<template>
  <div>
    <q-tabs v-model="tab" class="bg-primary text-white shadow-5">
      <q-route-tab name="tasks" icon="task" label="Задания" to="/"></q-route-tab>
      <q-route-tab name="lists" icon="list" label="Списки рассылки" to="/lists"></q-route-tab>
    </q-tabs>
  </div>
</template>

<script>
export default {
  // name: 'ComponentName',
  setup() {
    return {
    };
  },
};
</script>
