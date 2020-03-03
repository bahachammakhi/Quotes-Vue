<template>
  <div class="col-sm-6 col-md-4 col-lg-3">
    <div class="card card-default">
      <div class="card-body quote">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script></script>

<style>
.panel-body {
  font-family: fantasy;
  font-size: 24px;
  color: #6e6e6e;
}
.quote {
  cursor: pointer;
}
.quote:hover {
  background-color: #ffe2e2;
}
</style>
