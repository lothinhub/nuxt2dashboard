<template>
  <div>
   <div>
    <b-button v-b-modal.modal-xl variant="primary">Create</b-button>
    <b-modal id="modal-xl" size="xl" title="Humen Resource">
      <b-card shadow>
        <b-card-text>
          People Information
        </b-card-text>
        <b-container class="bv-example-row">
          <b-row>
            <b-col>
              <b-form-input type="text" placeholder="Enter your first name"></b-form-input>
            </b-col>
            <b-col>
              <b-form-input text="text" placeholder="Enter your last name"></b-form-input>
            </b-col>
            <div class="w-100 pt-4"></div>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <div class="w-100 pt-4"></div>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <div class="w-100 pt-4"></div>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <div class="w-100 pt-4"></div>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <div class="w-100 pt-4"></div>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
            <b-col>
              <b-form-input placeholder="Enter your name"></b-form-input>
            </b-col>
          </b-row>
      </b-container>
      </b-card>
    </b-modal>
  </div>
  <b-pagination class="pt-2" v-model="currentPage" :total-rows="rows"></b-pagination>
  </div>
</template>

<script>
export default {
  data() {
    return {
      rows: 100,
      currentPage: 1
    }
  }
}
</script>

<style>

</style>
