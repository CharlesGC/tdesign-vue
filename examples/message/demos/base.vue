<template>
  <div class="t-demo-message">
    <t-message theme="info">用于表示普通操作信息提示</t-message>
    <t-message theme="success">用于表示操作顺利达成</t-message>
    <t-message theme="warning">用于表示操作引起一定后果</t-message>
    <t-message theme="error">用于表示操作引起严重的后果</t-message>
    <t-message theme="question">用于帮助用户操作的信息提示</t-message>
  </div>
</template>

<style lang="less" scoped>
.t-demo-message {
  .t-message,
  .t-button {
    margin-bottom: 16px;
  }
}
</style>
