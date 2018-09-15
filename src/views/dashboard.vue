<template lang="html">
  <section class="dashboard">
    <div class="row">
      <div class="col-xl-4 col-lg-4 col-md-4 col-sm-6 grid-margin stretch-card">
        <div class="card card-statistics">
          <div class="card-body">
            <div class="clearfix">
              <div class="float-left">
                <i class="mdi mdi-cube text-danger icon-lg"></i>
              </div>
              <div class="float-right">
                <p class="card-text text-right">Projects</p>
                <div class="fluid-container">
                  <h3 class="card-title font-weight-bold text-right mb-0">40</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-xl-4 col-lg-4 col-md-4 col-sm-6 grid-margin stretch-card">
        <div class="card card-statistics">
          <div class="card-body">
            <div class="clearfix">
              <div class="float-left">
                <i class="mdi mdi-receipt text-warning icon-lg"></i>
              </div>
              <div class="float-right">
                <p class="card-text text-right">Primary Sites</p>
                <div class="fluid-container">
                  <h3 class="card-title font-weight-bold text-right mb-0">61</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-xl-4 col-lg-4 col-md-4 col-sm-6 grid-margin stretch-card">
        <div class="card card-statistics">
          <div class="card-body">
            <div class="clearfix">
              <div class="float-left">
                <i class="mdi mdi-poll-box text-teal icon-lg"></i>
              </div>
              <div class="float-right">
                <p class="card-text text-right">Cases</p>
                <div class="fluid-container">
                  <h3 class="card-title font-weight-bold text-right mb-0">32,555</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-xl-4 col-lg-4 col-md-4 col-sm-6 grid-margin stretch-card">
        <div class="card card-statistics">
          <div class="card-body">
            <div class="clearfix">
              <div class="float-left">
                <i class="mdi mdi-buffer text-dark icon-lg"></i>
              </div>
              <div class="float-right">
                <p class="card-text text-right">Files</p>
                <div class="fluid-container">
                  <h3 class="card-title font-weight-bold text-right mb-0">356,381</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-xl-4 col-lg-4 col-md-4 col-sm-6 grid-margin stretch-card">
        <div class="card card-statistics">
          <div class="card-body">
            <div class="clearfix">
              <div class="float-left">
                <i class="mdi mdi-source-merge text-primary icon-lg"></i>
              </div>
              <div class="float-right">
                <p class="card-text text-right">Genes</p>
                <div class="fluid-container">
                  <h3 class="card-title font-weight-bold text-right mb-0">22,147</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-xl-4 col-lg-4 col-md-4 col-sm-6 grid-margin stretch-card">
        <div class="card card-statistics">
          <div class="card-body">
            <div class="clearfix">
              <div class="float-left">
                <i class="mdi mdi-vector-triangle text-info icon-lg"></i>
              </div>
              <div class="float-right">
                <p class="card-text text-right">Mutations</p>
                <div class="fluid-container">
                  <h3 class="card-title font-weight-bold text-right mb-0">3,142,246</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
          <div class="col-md-6 grid-margin stretch-card">
            <div class="card">
              <div class="card-body">
                <h4 class="card-title">Graph1</h4>
              </div>
            </div>
          </div>
          <div class="col-md-6 grid-margin stretch-card">
            <div class="card">
              <div class="card-body">
                <h4 class="card-title">Graph2</h4>
              </div>
            </div>
          </div>
    </div>
    <div class="row">
      <div class="col-md-12 grid-margin stretch-card">
        <div class="card">
          <div class="card-body">
            <h4 class="card-title">Case by Major Primary Site</h4>
            <div class="template-demo">
              <div class="d-flex justify-content-between">
                <small>Adrenal Gland</small>
              </div>
              <b-progress :value="50" height="1rem" show-progress></b-progress>
              <div class="d-flex justify-content-between mt-2">
                <small>Blandder</small>
              </div>
              <b-progress :value="10" height="1rem" show-progress variant="success"></b-progress>
              <div class="d-flex justify-content-between mt-2">
                <small>Blandder</small>
              </div>
              <b-progress :value="13" height="1rem" show-progress variant="danger"></b-progress>
              <div class="d-flex justify-content-between mt-2">
                <small>Blandder</small>
              </div>
              <b-progress :value="33" height="1rem" show-progress variant="info"></b-progress>
              <div class="d-flex justify-content-between mt-2">
                <small>Blandder</small>
              </div>
              <b-progress :value="66" height="1rem" show-progress variant="right"></b-progress>
              <div class="d-flex justify-content-between mt-2">
                <small>Blandder</small>
              </div>
              <b-progress :value="12" height="1rem" show-progress variant="success"></b-progress>
              <div class="d-flex justify-content-between mt-2">
                <small>Blandder</small>
              </div>
              <b-progress :value="87" height="1rem" show-progress variant="dark"></b-progress>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="js">
export default {
  name: 'dashboard'
}
</script>

<style scoped lang="scss">
</style>
