<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
  </div>
  <InputPage></InputPage>
  <FunctionPage></FunctionPage>
</template>


<script>
import InputPage from './InputPage.vue';
import FunctionPage from 'src/pages/FunctionPage.vue';

export default {
    name: 'HtmlComponent',
    component: {
        InputPage,
        FunctionPage
    },
    data() {
        return {
            title: 'สรวิชญ์ บุญเสรฐ',
        };
    },
    components: { InputPage , FunctionPage}
}
</script>

<style scoped></style>
