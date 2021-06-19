<template>
  <div class="home">
    <div class="container">
      <div class="row header mb-5 p-3">
        <div class="col-lg-12">
          <h2>What i do Today?</h2>
        </div>
      </div>

      <div class="row content">
        <div class="col-lg-12">
          <div class="home-work">
            <div v-for="task in tasks" v-bind:key="task.id" class="mb-3 task">
              <div class="form-check">
                <TaskItem v-bind:task="task" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import TaskItem from "@/components/TaskItem.vue";

export default {
  name: "home",
  components: {
    TaskItem,
  },
  data: function () {
    return {
      tasks: [
        {
          id: 1,
          name: "Membersihkan toilet",
          isDone: false,
        },
        {
          id: 2,
          name: "Tugas akhir",
          isDone: false,
        },
        {
          id: 3,
          name: "Main game",
          isDone: false,
        },
      ],
    };
  },
};
</script>

<style>
.header {
  background: #1abc9c;
}

.header h2 {
  margin: 0;
}

.item-completed {
  color: #1abc9c;
}
</style>