<template>
  <div>
    <div class="paragraph" v-if="true">
      <div>
        <p>{{ author }}</p>
        <p>{{ skills }}</p>
      </div>
      <div>
        <ul>
          <li v-for="skill in skills">
            <h1>{{ skill }}</h1>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["author", "skills"],
};
</script>

<style>
.paragraph {
  text-align: center, right, left, justify, start, end;
  font-weight: lighter, 100, normal, 400, bold, 700, bolder, 900;
  text-decoration: wavy, dashed, dotted, double, solid, underline, line-through,
    overline;
  text-decoration: underline red;
  line-height: normal;
  letter-spacing: 2;
  font-size: 20px;
  font-family: "Courier New", Courier, monospace;
}
</style>
