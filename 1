<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>跨境供应链智能系统 · 增强版 | HS图谱 & 风险预测</title>
    <!-- Font Awesome 6 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <!-- Google Font Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,500;14..32,600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: #f1f5f9;
            color: #1e293b;
            height: 100vh;
            display: flex;
            overflow: hidden;
        }

        /* ========== 左侧导航 ========== */
        .sidebar {
            width: 280px;
            background: #0f172a;
            color: #e2e8f0;
            display: flex;
            flex-direction: column;
            box-shadow: 4px 0 12px rgba(0,0,0,0.1);
            overflow-y: auto;
        }

        .sidebar-header {
            padding: 24px 20px;
            border-bottom: 1px solid #334155;
        }

        .sidebar-header h2 {
            font-weight: 600;
            font-size: 1.3rem;
            color: white;
            line-height: 1.3;
        }

        .sidebar-header span {
            font-size: 0.85rem;
            color: #94a3b8;
            display: block;
            margin-top: 4px;
        }

        .nav-menu {
            flex: 1;
            padding: 20px 8px;
        }

        .nav-item {
            display: flex;
            align-items: center;
            gap: 14px;
            padding: 12px 16px;
            margin: 4px 0;
            border-radius: 12px;
            font-weight: 500;
            font-size: 0.95rem;
            color: #cbd5e1;
            transition: all 0.2s;
            cursor: pointer;
        }

        .nav-item i {
            width: 24px;
            font-size: 1.2rem;
            color: #64748b;
        }

        .nav-item.active {
            background: #1e293b;
            color: white;
        }

        .nav-item.active i {
            color: #38bdf8;
        }

        .nav-item:hover:not(.active) {
            background: #1e2a3a;
            color: #f1f5f9;
        }

        .nav-item:hover i {
            color: #94a3b8;
        }

        /* ========== 右侧主内容 ========== */
        .main {
            flex: 1;
            background: #f8fafc;
            overflow-y: auto;
            padding: 24px 32px;
        }

        .top-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 28px;
        }

        .page-title {
            font-size: 1.8rem;
            font-weight: 600;
            color: #0f172a;
        }

        .user-profile {
            display: flex;
            align-items: center;
            gap: 16px;
            background: white;
            padding: 8px 20px 8px 16px;
            border-radius: 40px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.03);
            border: 1px solid #e2e8f0;
        }

        .user-profile i {
            font-size: 1.4rem;
            color: #475569;
        }

        .user-profile span {
            font-weight: 500;
        }

        /* 内容区块 — 所有页面面板 */
        .page-panel {
            display: none;
            animation: fade 0.2s ease;
        }

        .page-panel.active-panel {
            display: block;
        }

        @keyframes fade {
            from { opacity: 0.5; transform: translateY(5px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* 卡片样式 */
        .card {
            background: white;
            border-radius: 20px;
            padding: 20px 24px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.03);
            border: 1px solid #e9edf2;
            margin-bottom: 24px;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 16px;
            margin: 20px 0;
        }

        .stat-card {
            background: white;
            border-radius: 18px;
            padding: 20px 18px;
            border: 1px solid #e2e8f0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.02);
        }

        .stat-title {
            font-size: 0.9rem;
            color: #64748b;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .stat-number {
            font-size: 2.2rem;
            font-weight: 600;
            color: #0f172a;
        }

        /* 简易图表模拟 */
        .chart-row {
            display: flex;
            align-items: flex-end;
            gap: 12px;
            margin-top: 25px;
            height: 160px;
        }

        .bar-container {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 6px;
        }

        .bar {
            width: 40px;
            background: #3b82f6;
            border-radius: 12px 12px 4px 4px;
            height: 100px;
            transition: 0.2s;
        }

        .bar.small { height: 60px; background: #60a5fa; }
        .bar.medium { height: 90px; }
        .bar.large { height: 130px; }
        .bar.xlarge { height: 150px; }

        .label {
            font-size: 0.8rem;
            color: #475569;
        }

        .timing-chart {
            display: flex;
            gap: 16px;
            margin: 20px 0;
            flex-wrap: wrap;
        }

        .timing-item {
            flex: 1;
            min-width: 100px;
        }

        .timing-bar-bg {
            background: #e2e8f0;
            height: 12px;
            border-radius: 20px;
            margin-top: 8px;
        }

        .timing-fill {
            height: 12px;
            border-radius: 20px;
            background: #f97316;
            width: 65%;
        }

        /* 表格样式 */
        .filter-bar {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            margin-bottom: 20px;
            align-items: center;
        }

        .filter-input {
            background: #f1f4f9;
            border: 1px solid #dde3ea;
            border-radius: 30px;
            padding: 10px 18px;
            font-size: 0.9rem;
            min-width: 160px;
            color: #1e293b;
        }

        .filter-input:focus {
            outline: 2px solid #94a3b8;
            background: white;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.85rem;
        }

        th {
            text-align: left;
            padding: 16px 8px;
            color: #475569;
            font-weight: 500;
            border-bottom: 2px solid #e2e8f0;
        }

        td {
            padding: 14px 8px;
            border-bottom: 1px solid #edf2f7;
        }

        .badge {
            background: #e2f0ff;
            color: #1e4a7a;
            padding: 4px 12px;
            border-radius: 30px;
            font-size: 0.75rem;
            font-weight: 500;
            display: inline-block;
        }

        .badge.warning { background: #fff3cd; color: #856404; }
        .badge.success { background: #d1fae5; color: #0b5e42; }
        .badge.high { background: #fee2e2; color: #991b1b; }
        .badge.medium { background: #ffedd5; color: #9a3412; }
        .badge.low { background: #dcfce7; color: #166534; }

        .action-btn {
            background: none;
            border: 1px solid #cfd9e6;
            padding: 5px 12px;
            border-radius: 30px;
            font-size: 0.75rem;
            color: #334155;
            cursor: pointer;
            transition: 0.2s;
            margin-right: 4px;
        }

        .action-btn:hover {
            background: #1e293b;
            color: white;
            border-color: #1e293b;
        }

        .action-btn i {
            font-size: 0.7rem;
            margin-right: 4px;
        }

        .form-row {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .form-group {
            flex: 1 1 200px;
        }

        .form-group label {
            display: block;
            font-size: 0.8rem;
            color: #64748b;
            margin-bottom: 5px;
        }

        .form-control {
            width: 100%;
            padding: 12px 18px;
            border-radius: 30px;
            border: 1px solid #d4dfea;
            background: white;
        }

        hr {
            border: none;
            border-top: 2px dashed #d9e2ef;
            margin: 30px 0 20px;
        }

        .small-note {
            color: #94a3b8;
            font-size: 0.8rem;
            margin-left: 8px;
        }

        /* 智能报关专用样式 */
        .graph-preview {
            background: #f0f4fe;
            border-radius: 28px;
            padding: 16px 22px;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            border: 1px solid #cbd5e1;
        }

        .graph-nodes {
            display: flex;
            align-items: center;
            gap: 8px;
            flex-wrap: wrap;
        }

        .hs-node {
            background: white;
            border: 2px solid #3b82f6;
            border-radius: 40px;
            padding: 8px 18px;
            font-weight: 600;
            font-size: 0.9rem;
            color: #1e4a7a;
            box-shadow: 0 2px 6px rgba(59,130,246,0.2);
        }

        .hs-node.small {
            padding: 5px 14px;
            border-color: #f97316;
        }

        .graph-arrow {
            font-size: 1.4rem;
            color: #64748b;
        }

        .risk-summary {
            background: white;
            border-radius: 26px;
            padding: 14px 28px;
            border: 1px solid #f1c4a3;
            display: inline-flex;
            gap: 30px;
            align-items: center;
        }

        .risk-level {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .risk-dot {
            width: 14px;
            height: 14px;
            border-radius: 14px;
            margin-bottom: 4px;
        }
        .risk-dot.high { background: #dc2626; }
        .risk-dot.medium { background: #f97316; }
        .risk-dot.low { background: #16a34a; }
    </style>
</head>
<body>
    <!-- 侧边导航栏 (与手册模块一致) -->
    <div class="sidebar">
        <div class="sidebar-header">
            <h2>跨境供应链 <br>智能决策与管理</h2>
            <span>V1.0 · 增强版</span>
        </div>
        <div class="nav-menu">
            <div class="nav-item active" data-page="home"><i class="fas fa-home"></i> 首页</div>
            <div class="nav-item" data-page="order"><i class="fas fa-clipboard-list"></i> 订单处理</div>
            <div class="nav-item" data-page="warehouse"><i class="fas fa-warehouse"></i> 仓储作业</div>
            <div class="nav-item" data-page="transport"><i class="fas fa-truck"></i> 运输监控</div>
            <div class="nav-item" data-page="customs"><i class="fas fa-file-invoice"></i> 报关作业</div>
            <div class="nav-item" data-page="finance"><i class="fas fa-coins"></i> 财务结算</div>
            <div class="nav-item" data-page="decision"><i class="fas fa-chart-pie"></i> 决策分析</div>
            <div class="nav-item" data-page="service"><i class="fas fa-headset"></i> 客户服务</div>
        </div>
    </div>

    <!-- 主内容区，动态切换页面 -->
    <div class="main">
        <div class="top-bar">
            <div class="page-title" id="current-page-label">首页</div>
            <div class="user-profile">
                <i class="fas fa-user-circle"></i>
                <span>运营中心 · 王经理</span>
                <i class="fas fa-chevron-down" style="font-size: 0.8rem;"></i>
            </div>
        </div>

        <!-- 首页面板 (不变) -->
        <div id="home" class="page-panel active-panel">
            <div class="card">
                <div style="display: flex; gap: 12px; flex-wrap: wrap;">
                    <input class="filter-input" placeholder="订单号 / 客户名称 / 货品编号" style="flex:2;">
                    <button class="action-btn" style="background:#1e293b; color:white; border:none;"><i class="fas fa-search"></i> 检索</button>
                </div>
            </div>
            <div class="stats-grid">
                <div class="stat-card"><div class="stat-title"><i class="fas fa-hourglass-half"></i> 待处理订单</div><div class="stat-number">24</div></div>
                <div class="stat-card"><div class="stat-title"><i class="fas fa-shipping-fast"></i> 在途运输</div><div class="stat-number">18</div></div>
                <div class="stat-card"><div class="stat-title"><i class="fas fa-file-contract"></i> 待报关货物</div><div class="stat-number">9</div></div>
                <div class="stat-card"><div class="stat-title"><i class="fas fa-hand-holding-usd"></i> 待结算账款</div><div class="stat-number">₿ 1.2M</div></div>
            </div>

            <div style="display: flex; gap: 24px; flex-wrap: wrap;">
                <div class="card" style="flex: 1.4;">
                    <h4>📈 上半年订单趋势</h4>
                    <div class="chart-row">
                        <div class="bar-container"><div class="bar small"></div><span class="label">1月</span></div>
                        <div class="bar-container"><div class="bar medium"></div><span class="label">2月</span></div>
                        <div class="bar-container"><div class="bar large"></div><span class="label">3月</span></div>
                        <div class="bar-container"><div class="bar xlarge"></div><span class="label">4月</span></div>
                        <div class="bar-container"><div class="bar large"></div><span class="label">5月</span></div>
                        <div class="bar-container"><div class="bar medium"></div><span class="label">6月</span></div>
                    </div>
                    <div style="display: flex; gap: 30px; justify-content: center; margin-top: 5px;">
                        <span><span style="background:#3b82f6; display:inline-block; width:12px; height:12px; border-radius:4px;"></span> 国内订单</span>
                        <span><span style="background:#f97316; display:inline-block; width:12px; height:12px; border-radius:4px;"></span> 跨境订单</span>
                    </div>
                </div>
                <div class="card" style="flex: 1;">
                    <h4>⏱️ 各环节平均时效</h4>
                    <div class="timing-chart">
                        <div class="timing-item"><span>仓储</span><div class="timing-bar-bg"><div class="timing-fill" style="width:40%"></div></div>2.4h</div>
                        <div class="timing-item"><span>运输</span><div class="timing-bar-bg"><div class="timing-fill" style="width:75%"></div></div>6.2h</div>
                        <div class="timing-item"><span>报关</span><div class="timing-bar-bg"><div class="timing-fill" style="width:55%"></div></div>3.8h</div>
                        <div class="timing-item"><span>配送</span><div class="timing-bar-bg"><div class="timing-fill" style="width:30%"></div></div>1.9h</div>
                    </div>
                </div>
            </div>

            <div class="card">
                <h4>➕ 新增订单登记</h4>
                <div class="form-row">
                    <div class="form-group"><label>订单编号</label><input class="form-control" placeholder="ORD-20250225"></div>
                    <div class="form-group"><label>客户信息</label><input class="form-control" placeholder="名称/ID"></div>
                    <div class="form-group"><label>货品类型</label><select class="form-control"><option>电子产品</option><option>服装</option></select></div>
                    <div class="form-group"><label>运输方式</label><select class="form-control"><option>海运</option><option>空运</option></select></div>
                </div>
                <button class="action-btn" style="margin-top:20px; background:#0f172a; color:white;">提交登记</button>
            </div>
        </div>

        <!-- 订单处理 (2.3) 不变 -->
        <div id="order" class="page-panel">
            <div class="card">
                <div class="filter-bar">
                    <input class="filter-input" placeholder="订单编号"><input class="filter-input" placeholder="客户名称"><input class="filter-input" type="date" value="2025-02-01"><input class="filter-input" placeholder="货品类型"><select class="filter-input"><option>全部状态</option><option>待处理</option></select>
                    <button class="action-btn"><i class="fas fa-search"></i> 筛选</button>
                </div>
                <table>
                    <tr><th>订单编号</th><th>客户名称</th><th>下单日期</th><th>货品类型</th><th>金额</th><th>联系电话</th><th>状态</th><th>操作</th></tr>
                    <tr><td>PO10086</td><td>亚马逊物流</td><td>2025-02-20</td><td>3C电子</td><td>$12,450</td><td>+1 206***</td><td><span class="badge">已发货</span></td><td><button class="action-btn" onclick="alert('订单详情弹窗\n包含完整处理历史')">详情</button><button class="action-btn" onclick="alert('修改订单信息弹窗')">修改</button></td></tr>
                    <tr><td>PO10092</td><td>Zara Home</td><td>2025-02-21</td><td>家居</td><td>$8,220</td><td>+34 91***</td><td><span class="badge warning">待处理</span></td><td><button class="action-btn" onclick="alert('订单详情')">详情</button><button class="action-btn" onclick="alert('取消原因填写')">取消</button></td></tr>
                </table>
            </div>
        </div>

        <!-- 仓储作业 (2.4) 不变 -->
        <div id="warehouse" class="page-panel">
            <div class="card">
                <div class="filter-bar">
                    <input class="filter-input" placeholder="货品编号"><input class="filter-input" placeholder="仓库位置"><input class="filter-input" placeholder="作业类型"><input class="filter-input" type="date"><button class="action-btn">筛选</button>
                </div>
                <table>
                    <tr><th>作业编号</th><th>货品名称</th><th>仓库位置</th><th>当前库存</th><th>作业类型</th><th>作业日期</th><th>操作员</th><th>操作</th></tr>
                    <tr><td>WH2304</td><td>iPhone 15</td><td>深圳-3C区</td><td>5,220</td><td>出库</td><td>02-24</td><td>张丽</td><td><button class="action-btn" onclick="alert('库存详情')">详情</button><button class="action-btn" onclick="alert('出库处理')">出库</button></td></tr>
                    <tr><td>WH2309</td><td>羊毛大衣</td><td>宁波-服装A</td><td>1,050</td><td>盘点</td><td>02-23</td><td>王海</td><td><button class="action-btn" onclick="alert('盘点记录')">盘点</button></td></tr>
                </table>
            </div>
        </div>

        <!-- 运输监控 (2.5) 不变 -->
        <div id="transport" class="page-panel">
            <div class="card">
                <div class="filter-bar">
                    <input class="filter-input" placeholder="运输单号"><input class="filter-input" placeholder="起运地"><input class="filter-input" placeholder="目的地"><select class="filter-input"><option>全部状态</option></select>
                </div>
                <table>
                    <tr><th>运单号</th><th>客户</th><th>起运地</th><th>目的地</th><th>运输方式</th><th>承运商</th><th>状态</th><th>操作</th></tr>
                    <tr><td>SF10923</td><td>联想</td><td>深圳</td><td>洛杉矶</td><td>空运</td><td>顺丰国际</td><td><span class="badge">飞途中</span></td><td><button class="action-btn" onclick="alert('位置更新')">位置</button><button class="action-btn" onclick="alert('延误报告')">延误</button></td></tr>
                    <tr><td>MSK8802</td><td>宜家</td><td>上海</td><td>汉堡</td><td>海运</td><td>马士基</td><td><span class="badge warning">清关中</span></td><td><button class="action-btn" onclick="alert('异常处理')">异常</button></td></tr>
                </table>
            </div>
        </div>

        <!-- ========== 报关作业 (2.6) 智能增强版 ========== -->
        <div id="customs" class="page-panel">
            <!-- 智能报关卡片：HS编码图谱 + 合规风险预测 -->
            <div class="card" style="background: linear-gradient(145deg, #f9fcff, #eef4ff);">
                <div style="display: flex; align-items: center; gap: 16px; margin-bottom: 16px;">
                    <i class="fas fa-microchip" style="font-size: 2rem; color:#2563eb;"></i>
                    <h3 style="font-weight: 600;">🧠 智能报关中枢 · HS编码图谱 & 合规风险预测</h3>
                </div>
                <div class="graph-preview">
                    <div class="graph-nodes">
                        <span class="hs-node">📱 智能手机</span>
                        <i class="fas fa-code-branch graph-arrow"></i>
                        <span class="hs-node" style="background:#fff7ed;">8517.12</span>
                        <i class="fas fa-long-arrow-alt-right graph-arrow"></i>
                        <span class="hs-node small">🔌 充电器</span>
                        <i class="fas fa-code-branch graph-arrow"></i>
                        <span class="hs-node" style="border-color:#f97316;">8504.40</span>
                        <i class="fas fa-long-arrow-alt-left graph-arrow"></i>
                        <span class="hs-node">💻 笔记本电脑</span>
                        <i class="fas fa-code-branch graph-arrow"></i>
                        <span class="hs-node">8471.30</span>
                    </div>
                    <div class="risk-summary">
                        <div class="risk-level"><span class="risk-dot high"></span> <span>高 2</span></div>
                        <div class="risk-level"><span class="risk-dot medium"></span> <span>中 4</span></div>
                        <div class="risk-level"><span class="risk-dot low"></span> <span>低 13</span></div>
                        <i class="fas fa-chart-line" style="color:#2563eb; font-size: 1.4rem;"></i>
                        <span style="font-weight:500;">风险指数 50%</span>
                    </div>
                </div>
                <div style="display: flex; gap: 10px; margin-top: 18px; flex-wrap: wrap;">
                    <button class="action-btn" onclick="alert('📊 HS编码知识图谱：展示同族商品、归类关联、历史归类记录')"><i class="fas fa-project-diagram"></i> 浏览完整图谱</button>
                    <button class="action-btn" onclick="alert('🔍 合规风险预测：基于原产地、税率、监管条件，当前批次建议重点关注8517项下商品')"><i class="fas fa-shield-alt"></i> 运行全面风险预测</button>
                    <span class="small-note">今日智能推荐HS编码 6次，规避潜在退单2笔</span>
                </div>
            </div>

            <!-- 报关作业表格 (增加HS编码推荐列 + 风险等级) -->
            <div class="card">
                <div class="filter-bar">
                    <input class="filter-input" placeholder="报关单号"><input class="filter-input" placeholder="货品名称"><select class="filter-input"><option>报关状态</option></select>
                    <button class="action-btn"><i class="fas fa-search"></i> 筛选</button>
                    <button class="action-btn" style="background: #dbeafe;" onclick="alert('启动智能HS匹配引擎')"><i class="fas fa-magic"></i> 智能匹配HS</button>
                </div>
                <table>
                    <tr>
                        <th>报关单号</th><th>货品名称</th><th>HS编码(智能推荐)</th><th>风险等级</th><th>报关口岸</th><th>状态</th><th>申报日期</th><th>操作</th>
                    </tr>
                    <tr>
                        <td>BG240215</td><td>智能手机</td>
                        <td><span style="font-weight:600;">8517.12 <i class="fas fa-bolt" style="color:#fbbf24;" title="AI推荐"></i></span></td>
                        <td><span class="badge high"><i class="fas fa-exclamation-triangle"></i> 高</span></td>
                        <td>上海洋山</td><td><span class="badge success">放行</span></td><td>02-15</td>
                        <td>
                            <button class="action-btn" onclick="alert('报关详情+智能归类图谱')"><i class="fas fa-info-circle"></i></button>
                            <button class="action-btn" onclick="alert('单证管理弹窗')"><i class="fas fa-file"></i></button>
                            <button class="action-btn" onclick="alert('⚡风险详情：原产地规则变更，建议补充原产地证')"><i class="fas fa-shield-virus"></i></button>
                        </td>
                    </tr>
                    <tr>
                        <td>BG240218</td><td>锂离子电池</td>
                        <td><span style="font-weight:600;">8507.60 <i class="fas fa-bolt" style="color:#fbbf24;"></i></span></td>
                        <td><span class="badge medium">中</span></td>
                        <td>广州南沙</td><td><span class="badge warning">查验</span></td><td>02-18</td>
                        <td>
                            <button class="action-btn" onclick="alert('报关详情')"><i class="fas fa-info-circle"></i></button>
                            <button class="action-btn" onclick="alert('申报信息填写')"><i class="fas fa-edit"></i></button>
                            <button class="action-btn" onclick="alert('风险：危包证缺失，建议立即上传')"><i class="fas fa-shield-virus"></i></button>
                        </td>
                    </tr>
                    <tr>
                        <td>BG240221</td><td>电动剃须刀</td>
                        <td><span style="font-weight:600;">8510.10 <i class="fas fa-bolt" style="color:#fbbf24;"></i></span></td>
                        <td><span class="badge low">低</span></td>
                        <td>深圳盐田</td><td><span class="badge success">放行</span></td><td>02-21</td>
                        <td>
                            <button class="action-btn" onclick="alert('详情')"><i class="fas fa-info-circle"></i></button>
                            <button class="action-btn" onclick="alert('单证管理')"><i class="fas fa-file"></i></button>
                            <button class="action-btn" onclick="alert('低风险，无预警')"><i class="fas fa-check-circle"></i></button>
                        </td>
                    </tr>
                </table>
                <div style="margin-top: 16px; background:#f0f7ff; border-radius: 30px; padding: 12px 20px; font-size:0.9rem;">
                    <i class="fas fa-robot" style="color:#2563eb;"></i> 智能报关引擎：根据商品描述“智能手机”推荐HS 8517.12 (置信度97%)； 锂电池归入8507.60，请注意危险品申报。
                </div>
            </div>
        </div>

        <!-- 财务结算 (2.7) 不变 -->
        <div id="finance" class="page-panel">
            <div class="card">
                <div class="filter-bar">
                    <input class="filter-input" placeholder="结算单号"><input class="filter-input" placeholder="客户名称"><select class="filter-input"><option>结算状态</option></select>
                </div>
                <table>
                    <tr><th>结算单号</th><th>客户</th><th>金额</th><th>状态</th><th>结算日期</th><th>结算方式</th><th>操作</th></tr>
                    <tr><td>SET0212</td><td>DHL供应链</td><td>$54,200</td><td><span class="badge">已支付</span></td><td>02-20</td><td>T/T</td><td><button class="action-btn" onclick="alert('结算详情')">详情</button><button class="action-btn" onclick="alert('发票管理')">发票</button></td></tr>
                </table>
            </div>
        </div>

        <!-- 决策分析 (2.8) 增加智能风险预测条目 -->
        <div id="decision" class="page-panel">
            <div class="card">
                <div class="filter-bar">
                    <input class="filter-input" placeholder="分析编号"><select class="filter-input"><option>成本分析</option><option>风险评估</option></select>
                </div>
                <table>
                    <tr><th>分析编号</th><th>主题</th><th>类型</th><th>分析师</th><th>日期</th><th>状态</th><th>操作</th></tr>
                    <tr><td>DA2401</td><td>Q1运输成本优化</td><td>成本分析</td><td>赵岩</td><td>02-18</td><td><span class="badge success">已完成</span></td><td><button class="action-btn" onclick="alert('成本分析报告')">报告</button></td></tr>
                    <tr><td>DA2402</td><td>HS编码合规风险深度预测</td><td>智能风控</td><td>AI引擎</td><td>02-22</td><td><span class="badge">进行中</span></td><td><button class="action-btn" onclick="alert('📊 图谱：高 likelihood 商品为8517、8507，建议开展内部核查')">风险图谱</button><button class="action-btn" onclick="alert('优化建议：根据原产地规则，建议申请预裁定')">建议</button></td></tr>
                </table>
            </div>
        </div>

        <!-- 客户服务 (2.9) 不变 -->
        <div id="service" class="page-panel">
            <div class="card">
                <div class="filter-bar">
                    <input class="filter-input" placeholder="服务单号"><input class="filter-input" placeholder="客户名称"><select class="filter-input"><option>投诉</option></select><select class="filter-input"><option>优先级</option></select>
                </div>
                <table>
                    <tr><th>服务单号</th><th>客户</th><th>服务类型</th><th>问题描述</th><th>创建时间</th><th>状态</th><th>优先级</th><th>操作</th></tr>
                    <tr><td>SR0223</td><td>安克创新</td><td>投诉</td><td>运输延误</td><td>02-23</td><td><span class="badge warning">处理中</span></td><td>高</td><td><button class="action-btn" onclick="alert('投诉处理')">处理</button><button class="action-btn" onclick="alert('满意度评价')">评价</button></td></tr>
                </table>
            </div>
        </div>
    </div>

    <!-- 切换脚本 -->
    <script>
        (function() {
            const navItems = document.querySelectorAll('.nav-item');
            const panels = {
                home: document.getElementById('home'),
                order: document.getElementById('order'),
                warehouse: document.getElementById('warehouse'),
                transport: document.getElementById('transport'),
                customs: document.getElementById('customs'),
                finance: document.getElementById('finance'),
                decision: document.getElementById('decision'),
                service: document.getElementById('service')
            };
            const pageLabel = document.getElementById('current-page-label');

            function setActive(pageId) {
                navItems.forEach(item => item.classList.remove('active'));
                Object.values(panels).forEach(p => p.classList.remove('active-panel'));

                const activeNav = Array.from(navItems).find(n => n.dataset.page === pageId);
                if (activeNav) activeNav.classList.add('active');
                if (panels[pageId]) panels[pageId].classList.add('active-panel');

                const names = { home:'首页', order:'订单处理', warehouse:'仓储作业', transport:'运输监控', customs:'报关作业', finance:'财务结算', decision:'决策分析', service:'客户服务' };
                pageLabel.innerText = names[pageId] || '首页';
            }

            navItems.forEach(item => {
                item.addEventListener('click', (e) => {
                    e.preventDefault();
                    const page = item.dataset.page;
                    if (page) setActive(page);
                });
            });
        })();
    </script>
    <!-- 浮动提示 -->
    <div style="position: fixed; bottom: 16px; right: 20px; background: #0f172a; color: #facc15; padding: 6px 16px; border-radius: 40px; font-size: 0.8rem; box-shadow: 0 4px 12px black; z-index: 999;">
        ⚡ 智能报关增强 · HS图谱 & 合规风险预测
    </div>
</body>
</html>
