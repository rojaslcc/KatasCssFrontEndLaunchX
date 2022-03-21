<template>
  <div>
    <div class="w-50 mt-5 float-end">
        <h1>Preparations Before Vaccine</h1>
        <p class="page-description pt-4">
        The success of vaccines is strongly influenced by the strength of the
        body's immune system. Therefore, there are several things that can be
        tried to make the COVID-19 vaccine work:
        </p>
    </div>
    <div class="d-flex flex-row w-100 py-5">
      <div class="box-gradient bg-gradient-blue d-flex flex-column justify-content-center align-items-center">
        <div class="w-75 d-flex flex-column">
          <img src="https://www.cdc.gov/coronavirus/2019-ncov/images/vaccines/VaccineCard.jpg" class="img-fluid" alt="..." />
        </div>
      </div>
      <div class="w-50 d-flex flex-column justify-content-center align-items-center">
        <div class="box-reasons">
          <div>
            <PreparationCard
              icon="fa-solid fa-shield icon-blue p-3"
              title="Avoid alcoholic beverages"
            />
            <PreparationCard
              icon="fa-solid fa-close icon-blue p-3"
              title="Avoid stress"
            />
            <PreparationCard
              icon="fa-solid fa-chart-simple icon-blue p-3"
              title="Eat healthy food"
            />
            <PreparationCard
              icon="fa-solid fa-check icon-blue p-3"
              title="Get enough sleep"
            />
            <PreparationCard
              icon="fa-solid fa-heart icon-blue p-3"
              title="Exercise or physical activity"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import PreparationCard from "./PreparationCard.vue";

export default {
  name: "Preparations",
  components: { PreparationCard },
};
</script>

<style>
.box-gradient {
    width: 40%
}
.box-reasons {
    width: 60%
}
</style>
