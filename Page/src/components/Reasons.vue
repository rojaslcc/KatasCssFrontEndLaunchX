<template>
  <div>
    <div class="d-flex flex-row w-100 my-5">
      <div
        class="d-flex flex-column justify-content-center align-items-center w-50"
      >
        <div class="w-75">
          <h2 class="page-subtitle">Why should I vaccine?</h2>
          <p class="page-description pt-4">
            In order to avoid any doubts about getting the COVID-19 vaccine,
            identify the following 4 benefits of COVID-19 vaccination:
          </p>
        </div>
      </div>
      <div class="w-50"></div>
    </div>
    <div class="w-75 my-5 my-card">
      <div class="d-flex flex-row justify-content-center align-items-center">
        <ReasonCard
          icon="fa-solid fa-sliders icon-blue p-3"
          title="Minimize the spread of viruses"
          description="Vaccine has been proven effective to prevent someone from getting infected with Coronavirus"
        />
        <ReasonCard
          icon="fa-solid fa-shield icon-blue p-3"
          title="Forming antibodies"
          description="COVID-19 vaccine proven to help shape antibody response for immune system"
        />
        <ReasonCard
          icon="fa-solid fa-users icon-blue p-3"
          title="Protecting people nearby"
          description="The benefits of COVID-19 vaccination are the vaccine that we get can also help protect people around us"
        />
        <ReasonCard
          icon="fa-solid fa-chart-line icon-blue p-3"
          title="Creating group immunity"
          description="COVID-19 vaccination is also beneficial for creating group immunity or herd immunity"
        />
      </div>
    </div>
  </div>
</template>

<script>
import ReasonCard from "./ReasonCard.vue";
export default {
  name: "Reasons",
  components: { ReasonCard },
};
</script>

<style>
.background-triangles {
  background-image: url("../assets/img/triangles1.png");
  background-size: contain;
  background-repeat: no-repeat;
}

.my-card {
  margin: auto;
}
</style>
