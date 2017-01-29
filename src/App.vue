<template>
  <div id="app">
    <grid-flex></grid-flex>
    <!--<grid-css></grid-css>-->
    <!--<statistics></statistics>-->
    <spells></spells>
  </div>
</template>



<script>
import GridCss from './components/Grid-css';
import GridFlex from './components/Grid-flex';
import Statistics from './components/Statistics';
import Spells from './components/Spells';

export default {
  name: 'app',
  components: {
    GridCss,
    GridFlex,
    Statistics,
    Spells,
  },
};
</script>



<style>

  :root {
    --global-font-size: 10px;
    --global-line-height: 16px;
    --global-transition: all 300ms ease-in-out;

    --white: #fff;
    --grey: #bbb;
    --grey-light: #eee;
    --grey-dark: #555;
    --black: #262626;

    --spacing-tiny:   5px;
    --spacing-small: 10px;
    --spacing:       15px;
    --spacing-large: 20px;
    --spacing-huge:  30px;

    --font-size-h1: 32px;
    --font-size-h2: 24px;
    --font-size-h3: 20px;
    --font-size-h4: 16px;
    --font-size-h5: 14px;
    --font-size-h6: 12px;

    --chamfer-size-s: 4px;
    --chamfer-size-l: 5px;
  }

  body {
    font-family: 'Roboto', sans-serif;
    font-size: var(--global-font-size);
    line-height: var(--global-line-height);
    color: var(--black);
  }

  body, h1, h2, h3, h4, h5, h6, p {
    margin:  0;
    padding: 0;
    font-weight: normal;
  }

  h1, h2, h3, h4, h5, h6, p {
    margin-bottom: var(--spacing-small);
  }

  h1 {
    font-size: var(--font-size-h1);
    line-height: var(--spacing-huge);
  }

  h2 {
    font-size: var(--font-size-h2);
    line-height: var(--spacing-huge);
  }

  h3 {
    font-size: var(--font-size-h3);
    line-height: var(--spacing-huge);
  }

  h4 {
    font-size: var(--font-size-h4);
    line-height: var(--spacing-huge);
  }

  h5 {
    font-size: var(--font-size-h5);
    line-height: var(--spacing);
  }

  h6 {
    font-size: var(--font-size-h6);
    line-height: var(--spacing);
  }

  small {
    display: block;
    font-size: .5rem;
    line-height: 12px;
  }

  @page {
    size: A4;
    margin: 0;
  }

  .page {
    width: 210mm;
    min-height: 297mm;
    padding: 20mm;
    margin: 10mm auto;
    border: 1px #D3D3D3 solid;
    background: white;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
  }

  @media print {

    html, body {
      width: 210mm;
      height: 297mm;
    }

  }

  #app {

  }

  .p1 {
    padding: var(--spacing-tiny) !important;
  }

  .pt1 {
    padding-top: var(--spacing-tiny) !important;
  }

  .pr1 {
    padding-right: var(--spacing-tiny) !important;
  }  

  .pb1 {
    padding-bottom: var(--spacing-tiny) !important;
  }

  .pb2 {
    padding-bottom: var(--spacing-small) !important;
  }

  .pb3 {
    padding-bottom: var(--spacing) !important;
  }

  .pb4 {
    padding-bottom: var(--spacing-large) !important;
  }

  .pb5 {
    padding-bottom: var(--spacing-huge) !important;
  }

  .pl1 {
    padding-left: var(--spacing-tiny) !important;
  }

  .ph1 {
    padding-left: var(--spacing-tiny) !important;
    padding-right: var(--spacing-tiny) !important;
  }

  .pv1 {
    padding-top: var(--spacing-tiny) !important;
    padding-bottom: var(--spacing-tiny) !important;
  }

  .p2 {
    padding: var(--spacing-small) !important;
  }

  .pt2 {
    padding-top: var(--spacing-small) !important;
  }

  .pr0 {
    padding-right: 0 !important;
  }

  .pr2 {
    padding-right: var(--spacing-small) !important;
  }  

  .pb2 {
    padding-bottom: var(--spacing-small) !important;
  }

  .pl2 {
    padding-left: var(--spacing-small) !important;
  }

  .ph0 {
    padding-left: 0 !important;
    padding-right: 0 !important;
  }

  .ph2 {
    padding-left: var(--spacing-small) !important;
    padding-right: var(--spacing-small) !important;
  }

  .pv2 {
    padding-top: var(--spacing-small) !important;
    padding-bottom: var(--spacing-small) !important;
  }

  .m1 {
    margin: var(--spacing-tiny) !important;
  }

  .mb0 {
    margin-bottom: 0 !important;
  }

  .mb1 {
    margin-bottom: var(--spacing-tiny) !important;
  }

  .mb2 {
    margin-bottom: var(--spacing-small) !important;
  }

  .mb3 {
    margin-bottom: var(--spacing) !important;
  }

  .mb4 {
    margin-bottom: var(--spacing-large) !important;
  }

  .mb5 {
    margin-bottom: var(--spacing-huge) !important;
  }

  .ta-c {
    text-align: center !important;
  }

  .ta-r {
    text-align: right !important;
  }

  .tt-u {
    text-transform: uppercase !important;
  }

  .td-u {
    text-decoration: underline !important;
  }

</style>
