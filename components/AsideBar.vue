<template>
  <div>
    <b-sidebar id="sidebar-1" title="People" bg-variant="light" shadow>
      <hr class="bg-primary">
      <div class="px-3 py-2">
        <nav class="mb-3">
          <b-nav vertical>
            <b-nav-item><NuxtLink to="dashbaord">Dashboard</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/people">People</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/service">Service</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/management">Management</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/partner">Partner</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/order">Order</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/sale">Sale</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/group">Group</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/account">Account</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/device">Device</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/shareholder">ShareHoler</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/team">Team</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/importexport">Import & Export</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/setting">Setting</NuxtLink></b-nav-item>
            <b-nav-item><NuxtLink to="/about">About us</NuxtLink></b-nav-item>
          </b-nav>
        </nav>
      </div>
    </b-sidebar>
  </div>
</template>
