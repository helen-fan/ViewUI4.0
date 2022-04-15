<template>
  <ScrollBar height="400" width="200">
    <section v-for="item in list">
        <div class="city">
            <p>{{ item }}</p>
        </div>
    </section>
  </ScrollBar>
</template>
<script>
export default {
    data () {
        return {
            list: [1,2,3,4,5,6,7,8,9,10]
        };
    }
};
</script>
<style>
    section {
        margin: 20px;
    }
    section > div {
        width: 300px;
        padding: 15px;
        margin: 5px;
        background-color: #ddf;
        border: 1px solid #446;
        border-radius: 5px;
        margin: 0 auto;
    }

</style>
