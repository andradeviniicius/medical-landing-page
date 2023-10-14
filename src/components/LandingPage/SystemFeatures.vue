<template>
  <div id="features" class="accordion-1">
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <h2 class="h2-heading">Key Medical Service Features</h2>
          <p class="p-heading">
            Our medical service offers a range of essential features to ensure
            your well-being and health. Suspendisse vitae enim arcu. Aliquam
            convallis risus a felis blandit, at mollis nisi bibendum. Aliquam
            nec purus at ex blandit posuere nec a odio. Proin lacinia dolor
            justo.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-5">
          <div class="accordion" id="accordionExample">
            <div class="accordion-item">
              <div class="accordion-icon">
                <span class="fas fa-tv"></span>
              </div>
              <div class="accordion-header" id="headingOne">
                <button
                  class="accordion-button"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseOne"
                  aria-expanded="true"
                  aria-controls="collapseOne"
                >
                  Comprehensive Medical Analysis
                </button>
              </div>
              <div
                id="collapseOne"
                class="accordion-collapse collapse show"
                aria-labelledby="headingOne"
                data-bs-parent="#accordionExample"
              >
                <div class="accordion-body">
                  We conduct thorough medical analyses and design personalized
                  healthcare plans tailored to your needs. Mauris ornare libero
                  et pharetra hendrerit. Cura elementum lectus quis tellus
                  pretium, vitae lobortis dui sagittis aliquam et enim vel semon
                  anticus.
                </div>
              </div>
            </div>

            <div class="accordion-item">
              <div class="accordion-icon blue">
                <span class="fas fa-microphone"></span>
              </div>
              <div class="accordion-header" id="headingTwo">
                <button
                  class="accordion-button"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseTwo"
                  aria-expanded="false"
                  aria-controls="collapseTwo"
                >
                  Identifying Health Opportunities
                </button>
              </div>
              <div
                id="collapseTwo"
                class="accordion-collapse collapse"
                aria-labelledby="headingTwo"
                data-bs-parent="#accordionExample"
              >
                <div class="accordion-body">
                  We help you discover potential health opportunities and
                  provide guidance on how to address them. Mauris ornare libero
                  et pharetra hendrerit. Cura elementum lectus quis tellus
                  pretium, vitae lobortis dui sagittis aliquam et enim vel semon
                  anticus.
                </div>
              </div>
            </div>

            <div class="accordion-item">
              <div class="accordion-icon purple">
                <span class="fas fa-video"></span>
              </div>
              <div class="accordion-header" id="headingThree">
                <button
                  class="accordion-button"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseThree"
                  aria-expanded="false"
                  aria-controls="collapseThree"
                >
                  Productive Health Campaigns
                </button>
              </div>
              <div
                id="collapseThree"
                class="accordion-collapse collapse"
                aria-labelledby="headingThree"
                data-bs-parent="#accordionExample"
              >
                <div class="accordion-body">
                  We work on preparing effective health campaigns to promote
                  your overall well-being. Mauris ornare libero et pharetra
                  hendrerit. Cura elementum lectus quis tellus pretium, vitae
                  lobortis dui sagittis aliquam et enim vel semon anticus.
                </div>
              </div>
            </div>

            <div class="accordion-item">
              <div class="accordion-icon orange">
                <span class="fas fa-tools"></span>
              </div>
              <div class="accordion-header" id="headingFour">
                <button
                  class="accordion-button"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseFour"
                  aria-expanded="false"
                  aria-controls="collapseFour"
                >
                  Continuous Monitoring and Adjustment
                </button>
              </div>
              <div
                id="collapseFour"
                class="accordion-collapse collapse"
                aria-labelledby="headingFour"
                data-bs-parent="#accordionExample"
              >
                <div class="accordion-body">
                  We continuously evaluate your health campaign's progress and
                  make adjustments to ensure the best outcomes. Mauris ornare
                  libero et pharetra hendrerit. Cura elementum lectus quis
                  tellus pretium, vitae lobortis dui sagittis aliquam et enim
                  vel semon anticus.
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-7">
          <div class="image-container">
            <img
              class="img-fluid"
              src="assets/images/features-dashboard.png"
              alt="alternative"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>
