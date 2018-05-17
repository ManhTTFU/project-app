<template>
  <div>
    <navbar-app />
    <app-header />
    <app-hot />
    <product-app />
    <footer-app />
  </div>
</template>

<script>
import AppHeader from '~/components/AppHeader';
import AppHot from '~/components/AppHot';
import ProductApp from '~/components/ProductApp';
import NavbarApp from '~/components/NavbarApp';
import FooterApp from '~/components/FooterApp';

export default {
  components: {
    AppHeader,
    AppHot,
    ProductApp,
    NavbarApp,
    FooterApp,
  },
};
</script>

<style>
</style>
