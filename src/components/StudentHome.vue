<template>
  <div>
    <p>Successfully logged in as student</p>
    <ApplicantDashboard/>
  </div>
</template>


<script>
import ApplicantDashboard from '@/components/Dashboard/Dashboard.vue'

export default {
  name: "AdminHome",
  components: {ApplicantDashboard},
  computed: {},
  data() {
    return {};
  },
  methods: {},
  async mounted() {}
};
</script>
