<template>
  <section>
    <base-card>
      <h2>Register As as a Coach</h2>
      <CoachForm />
    </base-card>
  </section>
</template>

<script>
import CoachForm from '../../components/coaches/CoachForm.vue';
import BaseCard from '../../components/ui/BaseCard.vue';
export default {
  components: {
    CoachForm,
    BaseCard
  }
};
</script>
