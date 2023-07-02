<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt Dojo</NuxtLink>
        <ul>
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about">About</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/products">Products</NuxtLink>
          </li>
        </ul>
      </nav>
    </header>

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
  </div>
</template>

<script setup></script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
