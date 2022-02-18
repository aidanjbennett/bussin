<template>
  <div class="credits">
    <h2>Credits to</h2>
    <ul>
      <li>
        <a href="https://twitch.tv/ManniMoki">
          Credits to ManniMoki for redeeming the bussin reward for 21k channel
          points</a
        >
      </li>
      <li>
        <a href="https://twitch.tv/tg_khalil">
          Credits to tg_khalil for getting the first clip of it</a
        >
      </li>
      <li>
        <a href="https://twitch.tv/SekeiDesign">
          Credits to Sekei Design for actually doing it and for eating the
          butter and mayo
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'CreditsSection',
  props: {},
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.credits {
  color: #ffff;
}
.credits ul li a {
  color: #ffff;
  text-decoration: none;
  font-size: 24px;
}

.credits ul li a:hover {
  color: orange;
}
.credits ul li {
  margin-bottom: 15px;
  margin-top: 15px;
}
.credits ul {
  list-style: none;
}
</style>
