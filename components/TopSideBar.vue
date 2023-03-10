<template>
  <div>
    <b-navbar toggleable="md" type="dark" variant="light" class="shadow">
      <b-icon v-b-toggle.sidebar-1 class="h2" icon="text-center" style="color: #7952b3;"></b-icon>
      <b-navbar-brand class="ml-4 h2 text-primary">Nuxt LaRa People</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
            <b-button size="sm" class="my-2 my-sm-0 text-" type="submit">Search</b-button>
          </b-nav-form>
          <b-nav-item-dropdown right>
            <!-- Using 'button-content' slot -->
            <template #button-content>
              <h6 class="text-primary mt-3">User</h6>
            </template>
            <b-dropdown-item href="#">Profile</b-dropdown-item>
            <b-dropdown-item href="#">Sign Out</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
