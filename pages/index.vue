<template>
  <div class="container">
    <div class="row">
      <h1 class="display-2 justify-center">Compare Mercedes</h1>
    </div>
    <div class="row">
      <p class="lead">メルセデス車比較用サイト</p>
    </div>
    <div class="row">
      <p class="text-muted">工事中。メルセデス車の諸元比較用サイトを作成予定</p>
    </div>
    <div class="row">
      <div class="col-6">
        <b-dropdown id="dropdown-1" text="車を選択">
          <b-dropdown-item>Aクラス</b-dropdown-item>
          <b-dropdown-item>Bクラス</b-dropdown-item>
          <b-dropdown-item>Cクラス</b-dropdown-item>
          <b-dropdown-item>Eクラス</b-dropdown-item>
          <b-dropdown-item>Sクラス</b-dropdown-item>
        </b-dropdown>
      </div>
      <div class="col-6">
        <b-dropdown id="dropdown-2" text="車を選択">
          <b-dropdown-item>Aクラス</b-dropdown-item>
          <b-dropdown-item>Bクラス</b-dropdown-item>
          <b-dropdown-item>Cクラス</b-dropdown-item>
          <b-dropdown-item>Eクラス</b-dropdown-item>
          <b-dropdown-item>Sクラス</b-dropdown-item>
        </b-dropdown>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
