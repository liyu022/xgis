<!--
 * @Description: 头部组件
 * @Author: liyu
 * @Date: 2020-05-06 11:16:41
 -->
<template>
  <div class="header">
    <div class="title">陕西省环保厅GIS数据平台</div>
    <div class="header-menu">
      <a-menu mode="horizontal"  theme="yellow">
        <a-menu-item key="mail"> <a-icon type="mail" />Navigation One </a-menu-item>
        <a-menu-item key="app" disabled> <a-icon type="appstore" />Navigation Two </a-menu-item>
        <a-sub-menu>
          <span slot="title" class="submenu-title-wrapper"><a-icon type="setting" />Navigation Three - Submenu</span>
          <a-menu-item-group title="Item 1">
            <a-menu-item key="setting:1">
              Option 1
            </a-menu-item>
            <a-menu-item key="setting:2">
              Option 2
            </a-menu-item>
          </a-menu-item-group>
          <a-menu-item-group title="Item 2">
            <a-menu-item key="setting:3">
              Option 3
            </a-menu-item>
            <a-menu-item key="setting:4">
              Option 4
            </a-menu-item>
          </a-menu-item-group>
        </a-sub-menu>
        <a-menu-item key="alipay">
          <a href="https://antdv.com" target="_blank" rel="noopener noreferrer">Navigation Four - Link</a>
        </a-menu-item>
      </a-menu>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyHeader",
};
</script>

<style lang="less">

</style>
