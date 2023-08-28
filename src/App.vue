<script setup lang="ts">
import { OverlayScrollbarsComponent } from 'overlayscrollbars-vue';
const options = {
  className: 'os-theme-dark',
  resize: 'both',
  sizeAutoCapable: true,
  paddingAbsolute: true,
  showNativeOverlaidScrollbars: true,
  scrollbars: {
    clickScrolling: true,
    autohide: 'scroll',
  },
};
</script>

<template>
  <OverlayScrollbarsComponent
    :options="options"
    defer
  >
    <div class="container" data-overlayscrollbars-initialize>
      <ul>
        <li>Lorem ipsum dolor sit.</li>
        <li>Animi odit illo ex?</li>
        <li>Veniam, odio. Natus, nam?</li>
        <li>Consequuntur, libero! Doloribus, beatae?</li>
        <li>Aliquid totam dignissimos possimus.</li>
        <li>Iusto ea repellat quasi.</li>
        <li>Aliquam quos odio nisi!</li>
        <li>Sapiente nisi porro vel?</li>
        <li>Tenetur enim maxime natus.</li>
        <li>Laboriosam optio at asperiores?</li>
        <li>Ex necessitatibus dolore ipsum.</li>
        <li>Totam recusandae assumenda porro.</li>
        <li>Neque quaerat quibusdam reiciendis.</li>
        <li>Qui quam maxime tempora.</li>
        <li>Est architecto asperiores cumque.</li>
        <li>Rem magni delectus itaque.</li>
        <li>Earum minus accusamus quia!</li>
        <li>Voluptatum repellendus rem iste!</li>
        <li>Omnis quisquam maiores veritatis.</li>
        <li>A aliquam facilis commodi!</li>
        <li>Quae consectetur ipsa corrupti?</li>
        <li>Alias inventore recusandae esse?</li>
        <li>Ullam doloribus amet voluptate.</li>
        <li>Nobis quod suscipit quibusdam.</li>
        <li>Totam tempora error porro!</li>
        <li>Exercitationem minima veritatis rem.</li>
        <li>Optio enim dolorum nisi?</li>
        <li>Ad ducimus eius dolore.</li>
        <li>Nulla praesentium libero dolore.</li>
        <li>Ex veritatis omnis aut.</li>
        <li>Voluptate nulla dolorem exercitationem?</li>
        <li>Magnam iusto exercitationem dolorem?</li>
        <li>Molestias nesciunt iure id?</li>
        <li>Culpa molestiae qui asperiores?</li>
        <li>Minus officia id fugiat.</li>
      </ul>
    </div>
  </OverlayScrollbarsComponent>
</template>

<style scoped>
.container {
  height: 200px;
  width: 500px;
  overflow: auto;
}
</style>
