<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illum sequi sed
      veniam dolorum laborum ut, saepe fugiat quod, cum est temporibus facilis
      libero rerum velit molestias doloribus delectus pariatur eligendi?
    </p>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad, voluptatem?
      Architecto atque temporibus earum! Consequatur, nemo sequi nisi illum
      voluptate assumenda qui, quos mollitia obcaecati odit optio ut a
      distinctio.
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
// const { data } = await useFetch(`/api/ninja?name=mario`);

// const { data } = await useFetch(`/api/ninja?name=mario`, {
//   method: "POST",
//   body: { age: 30 },
// });

const { data } = await useFetch(`/api/currency/GBP`);
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
