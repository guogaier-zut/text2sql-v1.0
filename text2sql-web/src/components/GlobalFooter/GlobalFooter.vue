<template>
  <div class="footer">
    <div class="links">
      <a href="https://github.com/pdxjie" target="_blank"><a-icon type="user" /> 站长：IT 派同学</a>
      <a-tooltip placement="top">
        <template slot="title">
          <img src="~@/assets/wechat.jpg" alt="connect" style="width: 120px;height: 120px">
        </template>
        <a href="#"><a-icon type="mail" /> 联系作者</a>
      </a-tooltip>
      <a target="_blank" href="https://github.com/pdxjie/text2sql-issue/issues/1"><a-icon type="safety" /> 建设反馈</a>
    </div>
    <div class="copyright">
      Copyright
      <a-icon type="copyright" /> 2024 <span>Text2SQL</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GlobalFooter',
  data () {
    return {}
  }
}
</script>

<style lang="less" scoped>
.footer {
  padding: 0 16px;
  margin: 48px 0 24px;
  text-align: center;

  .links {
    margin-bottom: 8px;

    a {
      color: rgba(0, 0, 0, 0.45);

      &:hover {
        color: rgba(0, 0, 0, 0.65);
      }

      &:not(:last-child) {
        margin-right: 40px;
      }
    }
  }

  .copyright {
    color: rgba(0, 0, 0, 0.45);
    font-size: 14px;
  }
}
</style>
