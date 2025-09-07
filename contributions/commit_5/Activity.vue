<template>
  <div class="contribution">
    <h3>Contribution Record</h3>
    <p>Date: {{ date }}</p>
    <p>Commit: {{ commitNumber }} / {{ totalCommits }}</p>
  </div>
</template>

<script>
export default {
  name: 'ContributionRecord',
  data() {
    return {
      date: '2025-09-07',
      commitNumber: 5,
      totalCommits: 20
    }
  }
}
</script>

<style scoped>
.contribution {
  border: 1px solid #ddd;
  padding: 1rem;
  margin: 1rem;
  border-radius: 4px;
}
</style>
