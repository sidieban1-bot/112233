<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>效能报表｜低空巡检工单台账平台</title>
<link rel="stylesheet" href="assets/style.css" />

</head>
<body>

<header class="topbar">
  <div class="wrapper nav">
    <a class="logo" href="index.html"><span class="logo-mark">低</span><span>低空巡检工单台账平台</span></a>
    <nav class="navlinks"><a class="" href="index.html">产品首页</a><a class="" href="dashboard.html">运营总览</a><a class="" href="tasks.html">任务台账</a><a class="" href="hazards.html">隐患工单</a><a class="" href="resources.html">资源池</a><a class="" href="data.html">数据档案</a><a class="active" href="reports.html">效能报表</a><a class="" href="pricing.html">试点与定价</a></nav>
    <a class="btn primary" href="dashboard.html">进入演示系统</a>
  </div>
</header>


<main class="wrapper">
  <section class="page-title"><div class="kicker">PERFORMANCE REPORT</div><h1>效能报表</h1><p>把“治理成效全靠人工汇报”变成“自动生成、可追溯、可对比”的量化运营报告。</p></section>
  <div class="layout">
    <aside class="sidebar"><a class="side-link " href="dashboard.html"><span>📊</span>运营总览</a><a class="side-link " href="tasks.html"><span>🧾</span>巡检任务台账</a><a class="side-link " href="hazards.html"><span>⚠️</span>隐患工单管理</a><a class="side-link " href="resources.html"><span>🚁</span>资源池管理</a><a class="side-link " href="data.html"><span>🗂️</span>数据档案库</a><a class="side-link active" href="reports.html"><span>📈</span>效能报表</a><a class="side-link " href="pricing.html"><span>💼</span>试点与定价</a></aside>
    <section class="main-panel">
      <div class="kpi-row">
        <div class="kpi"><small>任务完成率</small><div class="value">96%</div><small>本月 128/133</small></div>
        <div class="kpi"><small>整改闭环率</small><div class="value">94%</div><small>超期率下降</small></div>
        <div class="kpi"><small>平均处置时长</small><div class="value">2.8天</div><small>较传统模式缩短</small></div>
        <div class="kpi"><small>设备利用率</small><div class="value">76%</div><small>闲置率可追踪</small></div>
      </div>
      <div class="split">
        <div class="card"><h3>隐患类型分布</h3><div class="chart"><div class="bar" style="height:80%"><span>市容</span></div><div class="bar" style="height:55%"><span>河道</span></div><div class="bar" style="height:65%"><span>园区</span></div><div class="bar" style="height:38%"><span>工地</span></div><div class="bar" style="height:28%"><span>应急</span></div></div></div>
        <div class="card"><h3>月度报告内容</h3>
          <p>系统可自动生成《月度低空巡检运营报告》，包括任务完成情况、隐患闭环情况、资源利用情况、超期工单清单、重点风险点分布和下月优化建议。</p>
          <button class="btn primary" onclick="exportReport()">导出月度报告</button>
        </div>
      </div>
      <div class="table-card">
        <div class="table-head"><h3>考核指标库</h3><span class="tag">可配置权重</span></div>
        <table><thead><tr><th>维度</th><th>指标</th><th>计算口径</th><th>用途</th></tr></thead>
        <tbody>
          <tr><td>作业质量</td><td>隐患发现率 / 复查通过率</td><td>按任务与工单关联统计</td><td>衡量治理效果</td></tr>
          <tr><td>运营效率</td><td>平均处置时长 / 超期率</td><td>按工单生命周期统计</td><td>识别流程堵点</td></tr>
          <tr><td>资源利用</td><td>设备利用率 / 飞手负荷</td><td>按资源池任务占用统计</td><td>减少重复采购和闲置</td></tr>
          <tr><td>汇报支撑</td><td>月报导出 / 重点风险点</td><td>按归档数据自动生成</td><td>支撑预算、绩效和复盘</td></tr>
        </tbody></table>
      </div>
    </section>
  </div>
</main>

<footer class="footer">
  <div class="wrapper footer-grid">
    <div>
      <div class="logo"><span class="logo-mark">低</span><span>低空巡检工单台账平台</span></div>
      <p style="margin-top:12px">把“飞行行为”变成“治理流程”，把“现场照片”变成“隐患工单”。</p>
    </div>
    <div>演示日期：<span data-date></span><br/>适用场景：区县城管 / 河道巡检 / 园区运维 / 第三方巡检服务商</div>
  </div>
</footer>
<script src="assets/app.js"></script>
</body>
</html>