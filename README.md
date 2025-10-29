<!doctype html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>个人主页 — RP 社区 | 联系 QQ</title>
  <meta name="description" content="面向 RP 社区成员与潜在加入者的专业主页 — 简介、规则、加入方式与联系方式（QQ）" />
  <!-- 如果你希望使用自定义 Google Font，请在下方替换或添加 -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#f5f7fa;
      --card:#ffffff;
      --accent:#1f6feb;
      --muted:#6b7280;
      --glass: rgba(255,255,255,0.6);
      --radius:12px;
      font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      color-scheme: light;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background: linear-gradient(180deg, #f8fbff 0%, var(--bg) 100%);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      color:#0f1724;
      line-height:1.5;
      padding:32px;
      display:flex;
      justify-content:center;
    }
    .container{
      width:100%;
      max-width:980px;
    }

    header{
      display:flex;
      gap:20px;
      align-items:center;
      margin-bottom:20px;
    }
    .brand {
      display:flex;
      gap:14px;
      align-items:center;
    }
    .logo {
      width:64px;height:64px;border-radius:12px;
      background:linear-gradient(135deg,var(--accent),#4bc0ff);
      display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:20px;
      box-shadow:0 6px 18px rgba(31,111,235,0.15);
    }
    h1{font-size:20px;margin:0}
    .subtitle{color:var(--muted);font-size:13px;margin-top:4px}

    main{
      display:grid;
      grid-template-columns: 1fr 320px;
      gap:20px;
      align-items:start;
    }

    /* 左侧主卡片 */
    .card{
      background:var(--card);
      border-radius:var(--radius);
      padding:22px;
      box-shadow:0 6px 24px rgba(15,23,36,0.06);
    }

    .profile{
      display:flex;
      gap:18px;
      align-items:center;
    }
    .avatar{
      width:96px;height:96px;border-radius:8px;flex-shrink:0;
      background:linear-gradient(180deg,#ffffff,#eef6ff);
      display:flex;align-items:center;justify-content:center;border:1px solid rgba(15,23,36,0.04);
    }
    .avatar svg{width:72px;height:72px;opacity:0.9}
    .meta h2{margin:0;font-size:18px}
    .meta p{margin:6px 0 0;color:var(--muted);font-size:13px}

    section + section{margin-top:18px}

    .section-title{
      display:flex;align-items:center;justify-content:space-between;margin-bottom:10px;
    }
    .section-title h3{margin:0;font-size:15px}
    .text-muted{color:var(--muted);font-size:14px}

    /* 规则列表 */
    .rules{display:flex;flex-direction:column;gap:8px}
    .rule{
      background:linear-gradient(180deg, rgba(31,111,235,0.04), rgba(31,111,235,0.01));
      padding:10px;border-radius:10px;border:1px solid rgba(31,111,235,0.06);
      font-size:14px;
    }

    /* 右侧侧栏 */
    aside .card{position:sticky;top:28px}
    .contact-list{display:flex;flex-direction:column;gap:10px}
    .contact-item{display:flex;gap:10px;align-items:center}
    .contact-item .tag{
      min-width:40px;height:40px;border-radius:8px;display:flex;align-items:center;justify-content:center;
      background:var(--glass);border:1px solid rgba(15,23,36,0.04);
      font-weight:600;color:var(--accent)
    }
    .contact-item .value{font-weight:600}

    .btn{
      display:inline-flex;gap:10px;align-items:center;padding:10px 14px;border-radius:10px;border:0;
      background:var(--accent);color:white;font-weight:600;cursor:pointer;text-decoration:none;
      box-shadow:0 10px 24px rgba(31,111,235,0.12);
    }
    .btn.secondary{
      background:transparent;color:var(--accent);border:1px solid rgba(31,111,235,0.12);box-shadow:none;font-weight:600;
    }

    footer{margin-top:18px;color:var(--muted);font-size:13px;text-align:center}

    /* Responsiveness */
    @media (max-width:900px){
      main{grid-template-columns:1fr; padding-bottom:40px}
      aside .card{position:static}
    }

    /* small util */
    .muted{color:var(--muted);font-size:13px}
    .pill{display:inline-block;padding:6px 10px;border-radius:999px;background:#f1f5f9;font-weight:600;font-size:13px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden="true">RP</div>
        <div>
          <h1>你的 RP 社区 — 社区负责人</h1>
          <div class="subtitle">面向现有成员与想加入的玩家 · 专业 / 企业风展示页</div>
        </div>
      </div>
    </header>

    <main>
      <!-- 左侧主内容 -->
      <div class="card">
        <div class="profile">
          <div class="avatar" aria-hidden="true">
            <!-- 简易 SVG 头像占位 -->
            <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="avatar">
              <defs>
                <linearGradient id="g" x1="0" x2="1" y1="0" y2="1">
                  <stop offset="0" stop-color="#60a5fa"/>
                  <stop offset="1" stop-color="#4bc0ff"/>
                </linearGradient>
              </defs>
              <rect x="0" y="0" width="100" height="100" rx="12" fill="url(#g)"/>
              <g fill="#fff" transform="translate(15,12)">
                <circle cx="35" cy="24" r="12"/>
                <rect x="6" y="48" width="58" height="30" rx="8"/>
              </g>
            </svg>
          </div>
          <div class="meta">
            <h2 id="displayName">社区负责人名称</h2>
            <p id="tagline">让我的 RP 社区更安全、更专业、更好玩</p>
            <div style="margin-top:8px">
              <span class="pill">RP 社区 • 加入 / 招新</span>
            </div>
          </div>
        </div>

        <section id="about" style="margin-top:16px">
          <div class="section-title"><h3>关于我 / 社区</h3></div>
          <p class="text-muted" id="aboutText">
            这是一个为角色扮演玩家提供的专业社区，聚焦高质量剧情、稳定的管理团队以及友好的交流环境。欢迎现有成员与有兴趣加入的玩家查看规则、活动与加入方式。
          </p>
        </section>

        <section id="rules">
          <div class="section-title"><h3>核心规则（示例）</h3></div>
          <div class="rules">
            <div class="rule"><strong>1.</strong> 尊重其他玩家，禁止人身攻击与侮辱。</div>
            <div class="rule"><strong>2.</strong> 按服务器规则进行角色扮演，禁止破坏 RP 体验的行为。</div>
            <div class="rule"><strong>3.</strong> 管理有最终决定权，请配合审批与仲裁流程。</div>
          </div>
        </section>

        <section id="howtojoin">
          <div class="section-title"><h3>如何加入 / 招新流程</h3></div>
          <ol class="text-muted" style="padding-left:18px;margin:0">
            <li>添加 QQ 联系（页面右侧或下方）。</li>
            <li>提交入群申请：姓名 / 角色设定 / 过去 RP 经验。</li>
            <li>通过面试或小测，加入预备成员，观测期表现合格后转正。</li>
          </ol>
        </section>

        <section id="events">
          <div class="section-title"><h3>近期活动</h3></div>
          <ul class="text-muted" style="padding-left:18px;margin:0">
            <li>每周剧情联机 — 周五 20:00（示例，具体时间线上通知）。</li>
            <li>新手托管 & 指导 — 每周日 19:00。</li>
          </ul>
        </section>

        <footer>
          <div>页面由社区负责人维护 · 如需修改信息请通过 QQ 联系</div>
        </footer>
      </div>

      <!-- 右侧侧栏 -->
      <aside>
        <div class="card">
          <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:12px">
            <div>
              <h3 style="margin:0">联系方式</h3>
              <div class="muted" style="margin-top:6px;font-size:13px">直接添加或点击聊天</div>
            </div>
            <div style="text-align:right">
              <div class="muted" style="font-size:12px">状态：在线</div>
            </div>
          </div>

          <div class="contact-list" id="contactList">
            <!-- 联系项将由 JS 填充 -->
            <div class="contact-item">
              <div class="tag">QQ</div>
              <div>
                <div class="value" id="qqDisplay">正在加载…</div>
                <div class="muted" style="font-size:12px">添加时请注明来自本站</div>
              </div>
            </div>

            <div class="contact-item">
              <div class="tag">群</div>
              <div>
                <div class="text-muted">服务器/群：询问管理员获取最新群号</div>
              </div>
            </div>
          </div>

          <div style="display:flex;gap:10px;margin-top:12px">
            <a id="qqChatBtn" class="btn" href="#" target="_blank" rel="noopener">发起 QQ 聊天</a>
            <button class="btn secondary" id="copyBtn" title="复制联系方式">复制 QQ</button>
          </div>

          <hr style="margin:14px 0;border:none;border-top:1px solid rgba(15,23,36,0.04)">

          <div>
            <h4 style="margin:0 0 8px 0">快速简介</h4>
            <div class="muted" style="font-size:13px">
              专业管理团队 · 安全审核 · 定期活动 · 新人友好
            </div>
          </div>
        </div>

        <div style="height:12px"></div>

        <div class="card">
          <h3 style="margin-top:0">加入表单（示例）</h3>
          <p class="muted" style="margin-bottom:8px">填写后请发送截图给 QQ 管理员以便快速处理</p>
          <div style="display:flex;flex-direction:column;gap:8px">
            <input id="inpName" placeholder="你的游戏名 / 真实名（选填）" style="padding:10px;border-radius:8px;border:1px solid #e6eefc">
            <input id="inpRole" placeholder="主要角色设定（例：侦探/市民）" style="padding:10px;border-radius:8px;border:1px solid #e6eefc">
            <textarea id="inpMsg" rows="4" placeholder="简述你的 RP 经验与擅长方向" style="padding:10px;border-radius:8px;border:1px solid #e6eefc"></textarea>
            <button id="applyBtn" class="btn">生成申请卡（复制）</button>
          </div>
        </div>

      </aside>
    </main>
  </div>

  <script>
    /***********************************************
     IMPORTANT:
     把下面的 QQ_NUMBER 替换成你的真实 QQ 号（纯数字，不要加空格）。
     例如： const QQ_NUMBER = "12345678";
     ***********************************************/
    const QQ_NUMBER = "QQ_NUMBER"; // <-- 把这里替换成你的 QQ（例如 "12345678"）

    // 页面元素
    const qqDisplay = document.getElementById("qqDisplay");
    const qqChatBtn = document.getElementById("qqChatBtn");
    const copyBtn = document.getElementById("copyBtn");
    const applyBtn = document.getElementById("applyBtn");

    function initContact(){
      if(!QQ_NUMBER || QQ_NUMBER === "QQ_NUMBER"){
        qqDisplay.textContent = "请在 HTML 中将 QQ_NUMBER 替换为真实 QQ 号";
        qqChatBtn.href = "#";
        qqChatBtn.classList.add("secondary");
        qqChatBtn.textContent = "聊天链接未设置";
      } else {
        // 显示 QQ（部分隐藏以保护隐私，如需完整显示可移除）
        const masked = maskQQ(QQ_NUMBER);
        qqDisplay.textContent = masked;

        // QQ web 聊天链接（网页跳转到 QQ 客服页 / 在线聊天）
        // 兼容常见的 QQ 外链格式
        const webLink = "https://wpa.qq.com/msgrd?v=3&uin=" + encodeURIComponent(QQ_NUMBER) + "&site=qq&menu=yes";
        qqChatBtn.href = webLink;
        qqChatBtn.classList.remove("secondary");
        qqChatBtn.textContent = "发起 QQ 聊天";
      }
    }

    function maskQQ(q){
      // 如果很短则直接显示，否则部分掩码
      if(q.length <= 5) return q;
      return q.slice(0,3) + "•••" + q.slice(-2);
    }

    copyBtn.addEventListener("click", function(){
      if(!QQ_NUMBER || QQ_NUMBER === "QQ_NUMBER"){
        alert("请先在 HTML 中将 QQ_NUMBER 替换为你的真实 QQ 号。");
        return;
      }
      navigator.clipboard.writeText(QQ_NUMBER).then(() => {
        copyBtn.textContent = "已复制";
        setTimeout(()=> copyBtn.textContent = "复制 QQ",1500);
      }, ()=>{
        alert("复制失败，请手动复制：" + QQ_NUMBER);
      });
    });

    // 简易申请卡复制功能
    applyBtn.addEventListener("click", function(){
      const n = document.getElementById("inpName").value.trim() || "——";
      const r = document.getElementById("inpRole").value.trim() || "——";
      const m = document.getElementById("inpMsg").value.trim() || "无";
      const text = `申请人：${n}\n角色：${r}\n简介：${m}\n联系方式：QQ ${QQ_NUMBER === "QQ_NUMBER" ? "(请在页面替换 QQ)" : QQ_NUMBER }`;
      navigator.clipboard.writeText(text).then(()=>{
        applyBtn.textContent = "已复制申请卡";
        setTimeout(()=> applyBtn.textContent = "生成申请卡（复制）",1500);
        alert("申请卡已复制，请将其发送给 QQ 管理员以加速处理。");
      }, ()=>{
        alert("无法复制，请手动复制下面文本：\n\n" + text);
      });
    });

    // 初始化
    initContact();

    // 允许外部自定义显示名/简介（可在保存前编辑）
    // 如需直接在 HTML 中写入自定义名称，修改下方变量即可
    const CUSTOM_NAME = "社区负责人名称"; // 修改为你的显示名
    const CUSTOM_TAGLINE = "让我的 RP 社区更安全、更专业、更好玩";
    const CUSTOM_ABOUT = "这是一个为角色扮演玩家提供的专业社区，聚焦高质量剧情、稳定的管理团队以及友好的交流环境。欢迎现有成员与有兴趣加入的玩家查看规则、活动与加入方式。";

    document.getElementById("displayName").textContent = CUSTOM_NAME;
    document.getElementById("tagline").textContent = CUSTOM_TAGLINE;
    document.getElementById("aboutText").textContent = CUSTOM_ABOUT;

    // 小贴士：你可以在这里直接把 QQ 写成常量（替换 QQ_NUMBER），页面所有位置会自动更新。
  </script>
</body>
</html>
