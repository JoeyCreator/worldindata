<template>
  <div>
    <div class="w-full text-center">
      <h1 class="text-white uppercase">Welcome To The World In Data</h1>
    </div>
    <div class="alert alert-dismissible alert-warning">
      <button type="button" class="close" data-dismiss="alert">&times;</button>
      <h4 class="alert-heading">Warning!</h4>
      <p class="mb-0">
        For the most up to date information regarding COVID-19 in Canada, please consult Deptartment of Health. This site should not be used for life saving information - instead, rather, a source for numbers and statistics.
        <a
          href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019"
          class="alert-link"
        >More About Covid-19</a>.
      </p>
    </div>
    <iframe
      src="https://ourworldindata.org/grapher/full-list-cumulative-total-tests-per-thousand"
      style="width: 100%; height: 600px; border: 0px none;"
    ></iframe>
    <iframe
      src="https://experience.arcgis.com/experience/4ab8757241cc4d3fab81c8f86a501ce9"
      height="550"
      width="100%"
    ></iframe>
    <div class="pb-4">
      <h4 class="text-xs">
        Developed by Joey Cadieux &middot;
        <a
          class="text-blue-600"
          href="mailto:joey@tech-center.com"
        >Contact Me</a> &middot;
        <a class="text-blue-600" href="https://forms.gle/oef32kh8biei9h8W6">Found an issue?</a>
      </h4>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>

<style scoped>
main {
  padding: 100px;
}
</style>