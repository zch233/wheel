<template>
  <div class="base">
    <section>
      <h2>📌 Attributes</h2>
      <div class="attr">
        <table>
          <thead>
            <tr>
              <th>参数</th>
              <th class="des">说明</th>
              <th class="type">类型</th>
              <th>可选值</th>
              <th>默认值</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>total-page</td>
              <td class="des">总页数，必填</td>
              <td class="type">Number</td>
              <td>——</td>
              <td>--</td>
            </tr>
            <tr>
              <td>current-page</td>
              <td class="des">当前页数，必填，用 .sync 绑定</td>
              <td class="type">Number</td>
              <td>——</td>
              <td>--</td>
            </tr>
          </tbody>
        </table>
      </div>
    </section>
  </div>
</template>

<style>
.code {
  background-color: rgba(27, 31, 35, 0.05);
  border-radius: 3px;
  font-size: 85%;
  margin: 0;
  padding: 0.2em 0.4em;
}
</style>