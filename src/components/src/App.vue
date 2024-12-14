<template>
  <div id="app">
    <header>
      <h1>החזון שלי</h1>
    </header>
    <main>
      <VisionCard
        title="פיתוח חוויות משתמש מתקדמות"
        description="אני שואפת ליצור ממשקים חדשניים שיגרמו למשתמשים להרגיש בבית."
      />
      <VisionCard
        title="הנגשת טכנולוגיה לכולם"
        description="חזון שמטרתו להפוך את הטכנולוגיה לפשוטה ונגישה לכלל האוכלוסייה."
      />
    </main>
  </div>
</template>

<script>
import VisionCard from './components/VisionCard.vue';

export default {
  components: {
    VisionCard
  }
};
</script>

<style>
header {
  background-color: #4caf50;
  color: white;
  padding: 1rem;
  text-align: center;
}
main {
  padding: 2rem;
}
</style>
