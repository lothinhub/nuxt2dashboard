<template>
  <div>
    <b-sidebar id="sidebar-1" title="People" bg-variant="light" shadow>
      <hr class="bg-primary">
      <div class="px-3 py-2">
        <nav class="mb-3">
          <b-nav vertical>
            <b-nav-item NuxtLink to="/dashboard"><b-icon icon="house-fill" variant="warning"></b-icon>&nbsp; Dashboard</b-nav-item>
            <b-nav-item NuxtLink to="/people"><b-icon icon="people-fill" variant="warning"></b-icon>&nbsp; People</b-nav-item>
            <b-nav-item NuxtLink to="/service"><b-icon icon="arrow-repeat" variant="warning"></b-icon>&nbsp; Service</b-nav-item>
            <b-nav-item NuxtLink to="/management"><b-icon icon="arrows-move" variant="warning"></b-icon>&nbsp; Management</b-nav-item>
            <b-nav-item NuxtLink to="/partner"><b-icon icon="handbag-fill" variant="warning"></b-icon>&nbsp; Partner</b-nav-item>
            <b-nav-item NuxtLink to="/order"><b-icon icon="cart-check-fill" variant="warning"></b-icon>&nbsp; Order</b-nav-item>
            <b-nav-item NuxtLink to="/sale"><b-icon icon="layer-forward" variant="warning"></b-icon>&nbsp; Sale</b-nav-item>
            <b-nav-item NuxtLink to="/group"><b-icon icon="layout-wtf" variant="warning"></b-icon>&nbsp; Group</b-nav-item>
            <b-nav-item NuxtLink to="/account"><b-icon icon="layers-fill" variant="warning"></b-icon>&nbsp; Account</b-nav-item>
            <b-nav-item NuxtLink to="/device"><b-icon icon="layer-backward" variant="warning"></b-icon>&nbsp; Device</b-nav-item>
            <b-nav-item NuxtLink to="/shareholder"><b-icon icon="percent" variant="warning"></b-icon>&nbsp; ShareHoler</b-nav-item>
            <b-nav-item NuxtLink to="/team"><b-icon icon="person-bounding-box" variant="warning"></b-icon>&nbsp; Team</b-nav-item>
            <b-nav-item NuxtLink to="/importexport"><b-icon icon="card-checklist" variant="warning"></b-icon>&nbsp; Import & Export</b-nav-item>
            <b-nav-item NuxtLink to="/setting"><b-icon icon="sliders" variant="warning"></b-icon>&nbsp; Setting</b-nav-item>
            <b-nav-item NuxtLink to="/About"><b-icon icon="cloud" variant="warning"></b-icon>&nbsp; About us</b-nav-item>
          </b-nav>
        </nav>
      </div>
    </b-sidebar>
  </div>
</template>
