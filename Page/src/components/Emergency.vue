<template>
  <div>
    <div class="w-50 mt-5 px-5">
      <h1>Emergency Contact</h1>
      <p class="page-description">
        Contact one of the contacts below if you or your family feel unwell and
        have similar symptons such as Covid-19, make sure you also take care of
        yourself before reporting to us:
      </p>
    </div>
    <div class="d-flex flex-row w-100 py-5">
      <div class="box-communication-methods d-flex flex-column justify-content-center align-items-center">
        <div>
          <div class="d-flex flex-row align-items-center">
            <div class="d-flex flex-row">
              <CommunicationCard
                method="Call"
                buttonLabel="Call Now"
                icon="fa-solid fa-phone icon-blue p-2"
                buttonClass="button-vac-secondary w-100 p-2"
              />
              <CommunicationCard
                method="Chat"
                buttonLabel="Chat Now"
                icon="fa-solid fa-message icon-blue p-2"
                buttonClass="button-vac w-100 p-2"
              />
            </div>
          </div>
          <div>
            <div class="d-flex flex-row">
              <CommunicationCard
                method="Video Call"
                buttonLabel="Video Call Now"
                icon="fa-solid fa-video icon-blue p-2"
                buttonClass="button-vac-secondary w-100 p-2"
              />
              <CommunicationCard
                method="Message"
                buttonLabel="Message Now"
                icon="fa-solid fa-envelope icon-blue p-2"
                buttonClass="button-vac-secondary w-100 p-2"
              />
            </div>
          </div>
        </div>
      </div>
      <div class="box-gradient bg-gradient-blue d-flex flex-column justify-content-center align-items-center">
        <div class="w-75 d-flex flex-column">
          <img src="https://www.momkidcare.com/img/contact/Contact-Us.png" class="img-fluid" alt="..." />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import CommunicationCard from "./CommunicationCard.vue";

export default {
  name: "Emergency",
  components: { CommunicationCard },
};
</script>

<style>
.box-gradient {
  width: 40%;
}
.box-communication-methods {
  width: 60%;
}
</style>
