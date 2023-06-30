<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Praesentium
      nobis ex porro placeat, autem deserunt veritatis impedit aut rem adipisci
      voluptatem dolorem qui dolor totam quibusdam inventore mollitia obcaecati
      distinctio.
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Non reiciendis
      quidem aperiam ab eligendi dolorum perspiciatis blanditiis, exercitationem
      recusandae iure quos ad dolorem amet dignissimos quas distinctio odit quae
      mollitia?
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
const { data } = await useFetch("/api/ninja?name=mario", {
  method: "post",
  body: {
    age: 30,
  },
});
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
