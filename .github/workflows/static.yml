<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>StarVision - Minecraft专业定制开发团队</title>
<script>eval(function(p,a,c,k,e,d){e=function(c){return c.toString(36)};if(!''.replace(/^/,String)){while(c--)d[e(c)]=k[c]||e(c);k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('8 7="3";6 5=4.2(\'1\');5.0=\'9: 10 11 12 13\';',14,14,'textContent document createElement script type StarVision源码已加密，禁止盗用复制'.split('|'),0,{})</script>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:"Segoe UI",Inter,sans-serif;transition: background 0.3s ease, color 0.3s ease, border-color 0.3s ease;}
:root{
    --bg-main:#07080c;
    --bg-card:rgba(15,17,26,0.7);
    --primary:#4c7bff;
    --secondary:#9d4edd;
    --glow:0 0 22px rgba(76,123,255,0.45);
    --text:#e6edf7;
    --text-dim:#99a3b8;
    --border:1px solid rgba(76,123,255,0.18);
    --nav-bg:rgba(9,11,18,0.72);
}
html.light{
    --bg-main:#f4f7ff;
    --bg-card:rgba(255,255,255,0.8);
    --primary:#3668e3;
    --secondary:#8036d1;
    --glow:0 0 20px rgba(76,123,255,0.3);
    --text:#0e1422;
    --text-dim:#555c70;
    --border:1px solid rgba(76,123,255,0.25);
    --nav-bg:rgba(255,255,255,0.75);
}
body{
    background:var(--bg-main);
    color:var(--text);
    overflow-x:hidden;
    position:relative;
    min-height:100vh;
}
#starCanvas{
    position:fixed;
    top:0;
    left:0;
    width:100vw;
    height:100vh;
    z-index:-1;
    pointer-events:none;
}
.scroll-box{
    opacity:0;
    transform:translateY(60px);
    transition:opacity 0.7s ease, transform 0.7s ease;
}
.scroll-box.active{
    opacity:1;
    transform:translateY(0);
}
nav{
    backdrop-filter:blur(12px);
    background:var(--nav-bg);
    border-bottom:var(--border);
    padding:1.2rem 6%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:999;
}
.nav-left{
    display:flex;
    align-items:center;
    gap:1.5rem;
}
.logo{
    font-size:1.6rem;
    font-weight:700;
    background:linear-gradient(90deg,var(--primary),var(--secondary));
    -webkit-background-clip:text;
    background-clip:text;
    color:transparent;
}
.tool-group{
    display:flex;
    gap:0.8rem;
    align-items:center;
}
.theme-btn, .lang-select{
    padding:0.4rem 0.8rem;
    border-radius:5px;
    border:var(--border);
    background:var(--bg-card);
    color:var(--text);
    cursor:pointer;
    font-size:0.9rem;
    backdrop-filter:blur(4px);
}
.theme-btn:hover, .lang-select:hover{
    border-color:var(--primary);
}
.nav-group{display:flex;gap:2.5rem;align-items:center;}
.nav-link{color:var(--text-dim);text-decoration:none;transition:0.3s;}
.nav-link:hover{color:var(--primary);text-shadow:var(--glow);}
.btn{
    padding:0.7rem 1.6rem;
    border-radius:6px;
    border:none;
    cursor:pointer;
    font-weight:600;
    transition:0.3s all;
    text-decoration:none;
}
.btn-primary{
    background:linear-gradient(90deg,var(--primary),#3461e8);
    color:#fff;
    box-shadow:var(--glow);
}
.btn-primary:hover{transform:translateY(-2px);box-shadow:0 0 30px rgba(76,123,255,0.6);}
.hero{
    padding:7rem 6%;
    text-align:center;
}
.hero h1{
    font-size:3.2rem;
    margin-bottom:1.4rem;
    line-height:1.2;
}
.hero h1 span{
    background:linear-gradient(90deg,var(--primary),var(--secondary));
    -webkit-background-clip:text;
    background-clip:text;
    color:transparent;
}
.hero p{
    max-width:720px;
    margin:0 auto 2.5rem;
    color:var(--text-dim);
    font-size:1.1rem;
    line-height:1.7;
}
.section{padding:5rem 6%;}
.section-title{
    text-align:center;
    font-size:2.2rem;
    margin-bottom:4rem;
}
.section-title span{
    background:linear-gradient(90deg,var(--primary),var(--secondary));
    -webkit-background-clip:text;
    background-clip:text;
    color:transparent;
}
.service-wrap{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:2rem;
    margin-bottom:5rem;
}
.card{
    background:var(--bg-card);
    border:var(--border);
    border-radius:10px;
    padding:2rem;
    transition:0.3s;
    backdrop-filter:blur(6px);
}
.card:hover{
    border-color:rgba(76,123,255,0.4);
    transform:translateY(-6px);
    box-shadow:var(--glow);
}
.card h3{margin-bottom:1rem;font-size:1.3rem;color:var(--text);}
.card p{color:var(--text-dim);line-height:1.6;}
.adv-wrap{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
    gap:2rem;
}
.mid-btn-box{
    text-align:center;
    margin:4rem 0;
}
footer{
    border-top:var(--border);
    background:var(--nav-bg);
    padding:4rem 6% 2rem;
    margin-top:3rem;
}
.footer-top{
    display:flex;
    justify-content:space-between;
    flex-wrap:wrap;
    gap:3rem;
    margin-bottom:3rem;
}
.footer-col h4{margin-bottom:1.2rem;font-size:1.2rem;}
.footer-col p{color:var(--text-dim);max-width:340px;line-height:1.7;}
.footer-bottom{
    text-align:center;
    padding-top:2rem;
    border-top:1px solid rgba(120,140,180,0.12);
    color:var(--text-dim);
    font-size:0.9rem;
}
.record{margin-top:0.6rem;color:var(--text-dim);}
/* 点赞按钮样式 */
.like-box{
    margin:2rem 0;
    text-align:center;
}
.like-btn{
    padding:0.6rem 2rem;
    border-radius:8px;
    border:var(--border);
    background:var(--bg-card);
    color:var(--text);
    font-size:1rem;
    cursor:pointer;
    transition:0.2s;
}
.like-btn:hover{
    border-color:var(--primary);
    box-shadow:var(--glow);
}
.like-btn:active{
    transform:scale(0.96);
}
.like-count{
    margin-left:0.8rem;
    color:var(--primary);
    font-weight:bold;
}
@media(max-width:768px){
    .nav-left{flex-direction:column;align-items:flex-start;gap:0.8rem;}
    .nav-group{gap:1.2rem;flex-wrap:wrap;justify-content:center;margin-top:1rem;}
    .hero h1{font-size:2.2rem;}
    nav{flex-direction:column;gap:1.2rem;padding:1rem 4%;}
}
</style>
</head>
<body>
<canvas id="starCanvas"></canvas>
<nav>
    <div class="nav-left">
        <div class="logo">StarVision MC</div>
        <div class="tool-group">
            <button class="theme-btn" id="themeToggle">🌓 明暗模式</button>
            <select class="lang-select" id="langSelect">
                <option value="zh">中文 CN</option>
                <option value="en">English EN</option>
            </select>
        </div>
    </div>
    <div class="nav-group">
        <a href="#service" class="nav-link" data-i18n="navService">业务范围</a>
        <a href="#advantage" class="nav-link" data-i18n="navAdv">我们优势</a>
        <a href="#about" class="nav-link" data-i18n="navAbout">团队介绍</a>
        <a href="https://qm.qq.com/q/CcfwemLSA8" target="_blank" class="btn btn-primary" data-i18n="btnContact">联系我们</a>
    </div>
</nav>

<div class="hero scroll-box">
    <h1 data-i18n="heroTitle">专业Minecraft全方案定制 <span>StarVision团队</span></h1>
    <p data-i18n="heroDesc">专注我的世界客户端、服务端、插件、模组整合、材质定制、服务器运维一站式开发，多年MC开发经验，稳定高效，拒绝劣质半成品，满足个人/工作室/商用服务器全部需求</p>
    <a href="https://qm.qq.com/q/CcfwemLSA8" target="_blank" class="btn btn-primary" data-i18n="heroBtn">立即咨询定制方案</a>
</div>

<section id="service" class="section scroll-box">
    <h2 class="section-title" data-i18n="serviceTitle">我们提供 <span>全部MC定制业务</span></h2>
    <div class="service-wrap">
        <div class="card scroll-box">
            <h3 data-i18n="s1Title">定制客户端</h3>
            <p data-i18n="s1Desc">私人/商用整合包、启动器美化、模组优化、光影适配、UI界面定制、防崩溃调优、专属LOGO与加载动画制作</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="s2Title">定制服务端</h3>
            <p data-i18n="s2Desc">Spigot/Paper/Fabric/Forge各类服务端搭建、性能优化、千人服稳定调参、跨版本兼容、防卡防崩底层优化</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="s3Title">原创插件开发</h3>
            <p data-i18n="s3Desc">付费功能、副本、宠物、RPG、经济、领地、菜单、礼包等定制插件，支持按需编写源码，可二次修改维护</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="s4Title">配套增值服务</h3>
            <p data-i18n="s4Desc">模组整合汉化、材质包绘制、服务器宣传图、网站配套搭建、长期运维售后、BUG终身修复</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="s5Title">全程直播制作</h3>
            <p data-i18n="s5Desc">支持全流程直播开发，实时同步进度，随时沟通修改需求；客户端/服务端/插件开发全程可视化，透明无暗箱，有任何问题当场调整，交付同步录制完整工程回放视频</p>
        </div>
    </div>

    <div class="mid-btn-box scroll-box">
        <a href="https://qm.qq.com/q/CcfwemLSA8" target="_blank" class="btn btn-primary" data-i18n="midBtn">获取专属报价与方案</a>
    </div>
</section>

<section id="advantage" class="section scroll-box">
    <h2 class="section-title" data-i18n="advTitle">为什么选择 <span>StarVision？</span></h2>
    <div class="adv-wrap">
        <div class="card scroll-box">
            <h3 data-i18n="a1Title">资深开发团队</h3>
            <p data-i18n="a1Desc">团队全员拥有3年以上MC底层开发经验，精通Java、前端、服务端调优，熟悉主流模组与插件框架，技术扎实不外包转手</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="a2Title">一对一专属定制</h3>
            <p data-i18n="a2Desc">不套用模板流水线制作，根据你的玩法、受众、预算单独设计方案，每一份成品都是独一无二，完全贴合你的需求</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="a3Title">极致性能优化</h3>
            <p data-i18n="a3Desc">针对卡顿、内存溢出、延迟高、模组冲突深度优化，同配置下流畅度远超市面普通定制，支持高人数服务器稳定运行</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="a4Title">完善售后保障</h3>
            <p data-i18n="a4Desc">交付后免费修复BUG，提供使用教程，长期技术答疑，后期新增功能可享受优惠续改，拒绝一次性交易</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="a5Title">透明无隐形收费</h3>
            <p data-i18n="a5Desc">前期沟通列出完整报价清单，无中途加价，需求变更提前说明差价，全程沟通记录留存，消费清晰透明</p>
        </div>
        <div class="card scroll-box">
            <h3 data-i18n="a6Title">交付速度快</h3>
            <p data-i18n="a6Desc">成熟开发流程，简单需求当日出初稿，大型项目分阶段交付预览，随时查看进度，不拖延工期</p>
        </div>
    </div>
</section>

<section id="about" class="section scroll-box">
    <h2 class="section-title" data-i18n="aboutTitle">关于 <span>StarVision</span></h2>
    <div class="card scroll-box" style="max-width:900px;margin:0 auto;">
        <h3 data-i18n="aboutCardTitle">专注我的世界技术定制工作室</h3>
        <p data-i18n="aboutCardDesc" style="margin-top:1rem;">StarVision 是一支深耕Minecraft生态的专业开发团队，专注为MC爱好者、商用服务器、私人玩家提供全套技术定制服务。我们拒绝粗制滥造的流水线成品，坚持以技术为本，兼顾美观、性能与实用性。<br><br>无论是小型单机整合客户端，还是千人在线大型RPG服务端、原创付费插件，我们都能给出专业落地解决方案，已有上百份成熟定制案例，收获大量客户长期复购与推荐。</p>
    </div>
</section>

<footer class="scroll-box">
    <div class="footer-top">
        <div class="footer-col">
            <h4 data-i18n="footLogo">StarVision MC定制</h4>
            <p data-i18n="footDesc">一站式Minecraft技术定制开发团队，客户端/服务端/插件/模组全业务覆盖，专业、稳定、靠谱。</p>
        </div>
        <div class="footer-col">
            <h4 data-i18n="footQuick">快速通道</h4>
            <p><a href="#service" class="nav-link" data-i18n="navService">业务范围</a></p>
            <p><a href="#advantage" class="nav-link" data-i18n="navAdv">团队优势</a></p>
            <p><a href="https://qm.qq.com/q/CcfwemLSA8" target="_blank" class="nav-link" data-i18n="btnContact">联系咨询</a></p>
            <p><a href="https://qm.qq.com/q/CcfwemLSA8" target="_blank" class="nav-link" data-i18n="coopServer">合作开服</a></p>
        </div>
    </div>

    <!-- 新增点赞区域 -->
    <div class="like-box">
        <button class="like-btn" id="likeBtn" data-i18n="likeText">👍 给我们点赞</button>
        <span data-i18n="likePrefix">已有</span>
        <span class="like-count" id="likeNum">0</span>
        <span data-i18n="likeSuffix">位客户认可</span>
    </div>

    <div class="footer-bottom">
        <p data-i18n="copyright">© 2026 StarVision MC All Rights Reserved. 保留所有权利</p>
    </div>
</footer>

<script>
const i18nData = {
    zh:{
        navService:"业务范围",navAdv:"我们优势",navAbout:"团队介绍",btnContact:"联系我们",coopServer:"合作开服",
        heroTitle:"专业Minecraft全方案定制 <span>StarVision团队</span>",
        heroDesc:"专注我的世界客户端、服务端、插件、模组整合、材质定制、服务器运维一站式开发，多年MC开发经验，稳定高效，拒绝劣质半成品，满足个人/工作室/商用服务器全部需求",
        heroBtn:"立即咨询定制方案",serviceTitle:"我们提供 <span>全部MC定制业务</span>",
        s1Title:"定制客户端",s1Desc:"私人/商用整合包、启动器美化、模组优化、光影适配、UI界面定制、防崩溃调优、专属LOGO与加载动画制作",
        s2Title:"定制服务端",s2Desc:"Spigot/Paper/Fabric/Forge各类服务端搭建、性能优化、千人服稳定调参、跨版本兼容、防卡防崩底层优化",
        s3Title:"原创插件开发",s3Desc:"付费功能、副本、宠物、RPG、经济、领地、菜单、礼包等定制插件，支持按需编写源码，可二次修改维护",
        s4Title:"配套增值服务",s4Desc:"模组整合汉化、材质包绘制、服务器宣传图、网站配套搭建、长期运维售后、BUG终身修复",
        s5Title:"全程直播制作",
        s5Desc:"支持全流程直播开发，实时同步进度，随时沟通修改需求；客户端/服务端/插件开发全程可视化，透明无暗箱，有任何问题当场调整，交付同步录制完整工程回放视频",
        midBtn:"获取专属报价与方案",advTitle:"为什么选择 <span>StarVision？</span>",
        a1Title:"资深开发团队",a1Desc:"团队全员拥有3年以上MC底层开发经验，精通Java、前端、服务端调优，熟悉主流模组与插件框架，技术扎实不外包转手",
        a2Title:"一对一专属定制",a2Desc:"不套用模板流水线制作，根据你的玩法、受众、预算单独设计方案，每一份成品都是独一无二，完全贴合你的需求",
        a3Title:"极致性能优化",a3Desc:"针对卡顿、内存溢出、延迟高、模组冲突深度优化，同配置下流畅度远超市面普通定制，支持高人数服务器稳定运行",
        a4Title:"完善售后保障",a4Desc:"交付后免费修复BUG，提供使用教程，长期技术答疑，后期新增功能可享受优惠续改，拒绝一次性交易",
        a5Title:"透明无隐形收费",a5Desc:"前期沟通列出完整报价清单，无中途加价，需求变更提前说明差价，全程沟通记录留存，消费清晰透明",
        a6Title:"交付速度快",a6Desc:"成熟开发流程，简单需求当日出初稿，大型项目分阶段交付预览，随时查看进度，不拖延工期",
        aboutTitle:"关于 <span>StarVision</span>",aboutCardTitle:"专注我的世界技术定制工作室",
        aboutCardDesc:"StarVision 是一支深耕Minecraft生态的专业开发团队，专注为MC爱好者、商用服务器、私人玩家提供全套技术定制服务。我们拒绝粗制滥造的流水线成品，坚持以技术为本，兼顾美观、性能与实用性。<br><br>无论是小型单机整合客户端，还是千人在线大型RPG服务端、原创付费插件，我们都能给出专业落地解决方案，已有上百份成熟定制案例，收获大量客户长期复购与推荐。",
        footLogo:"StarVision MC定制",footDesc:"一站式Minecraft技术定制开发团队，客户端/服务端/插件/模组全业务覆盖，专业、稳定、靠谱。",
        footQuick:"快速通道",copyright:"© 2026 StarVision MC All Rights Reserved. 保留所有权利",
        icpText:"ICP备案号：___________（在此填写你的备案编号）",
        likeText:"👍 给我们点赞",likePrefix:"已有",likeSuffix:"位客户认可"
    },
    en:{
        navService:"Services",navAdv:"Advantages",navAbout:"About Us",btnContact:"Contact Us",coopServer:"Server Cooperation",
        heroTitle:"Professional Minecraft Customization <span>StarVision Team</span>",
        heroDesc:"One-stop development for custom clients, servers, plugins, modpacks & texture packs. Years of Minecraft development experience, stable & high-quality solutions for individuals, studios & commercial servers.",
        heroBtn:"Get Custom Quote Now",serviceTitle:"Our <span>Full MC Services</span>",
        s1Title:"Custom Client",s1Desc:"Private & commercial modpacks, launcher design, mod optimization, shader adaptation, custom UI, crash fixes, exclusive logo & loading animations",
        s2Title:"Custom Server",s2Desc:"Spigot/Paper/Fabric/Forge setup, performance tuning, stable support for thousands players, cross-version compatibility & lag reduction",
        s3Title:"Custom Plugins",s3Desc:"Custom RPG, economy, pets, dungeons, land protection, menus & shop plugins. Original source code with editable & maintainable structure",
        s4Title:"Extra Services",s4Desc:"Mod localization, texture drawing, server promotional art, website build, long-term after-sales & free bug fixes",
        s5Title:"Live Full Production Stream",
        s5Desc:"Whole-process live development, real-time progress sync, instant demand communication. Visible development for clients, servers and plugins, fully transparent workflow. Adjust issues live on stream, full recorded project playback video delivered after completion",
        midBtn:"Request Exclusive Plan & Price",advTitle:"Why Choose <span>StarVision</span>?",
        a1Title:"Experienced Developers",a1Desc:"All team members have 3+ years Minecraft backend experience, proficient in Java & server optimization, no third-party outsourcing",
        a2Title:"1-on-1 Custom Design",a2Desc:"No template mass production. Unique plans tailored to your gameplay, audience & budget",
        a3Title:"Extreme Performance Optimization",a3Desc:"Deep fixes for lag, memory leak & mod conflicts. Smoother experience than generic custom works",
        a4Title:"Complete After-Sales Support",a4Desc:"Free bug repair after delivery, guides & long-term technical support, discount for future feature updates",
        a5Title:"Transparent Pricing",a5Desc:"Full price list provided upfront, no hidden extra fees, all changes discussed before price adjustment",
        a6Title:"Fast Delivery",a6Desc:"Efficient workflow, draft available same-day for simple requests, stage-by-stage preview for large projects",
        aboutTitle:"About <span>StarVision</span>",aboutCardTitle:"Minecraft Professional Custom Studio",
        aboutCardDesc:"StarVision is a professional development team focusing on Minecraft ecosystem. We provide full technical solutions for players and commercial servers. We refuse low-quality template works, focusing on performance, visuals and practicality.<br><br>We deliver single-player modpacks, large RPG servers and original paid plugins. Hundreds of finished projects with long-term customer referrals.",
        footLogo:"StarVision MC Custom",footDesc:"All-in-one Minecraft development: Clients / Servers / Plugins / Mods. Professional & Reliable.",
        footQuick:"Quick Links",copyright:"© 2026 StarVision MC All Rights Reserved",
        likeText:"👍 Like Us",likePrefix:"",likeSuffix:"customers recognized us"
    }
};
function setLang(lang){
    localStorage.setItem("siteLang",lang);
    document.documentElement.lang = lang;
    const list = document.querySelectorAll("[data-i18n]");
    list.forEach(el=>{
        const key = el.getAttribute("data-i18n");
        el.innerHTML = i18nData[lang][key];
    })
}
document.getElementById("langSelect").addEventListener("change",e=>{
    setLang(e.target.value);
});
const savedLang = localStorage.getItem("siteLang") || "zh";
document.getElementById("langSelect").value = savedLang;
setLang(savedLang);

const htmlDom = document.documentElement;
const themeBtn = document.getElementById("themeToggle");
function setTheme(mode){
    localStorage.setItem("siteTheme",mode);
    if(mode === "light") htmlDom.classList.add("light");
    else htmlDom.classList.remove("light");
    themeBtn.innerText = mode === "light" ? "🌙 深色模式" : "🌓 明暗模式";
}
themeBtn.addEventListener("click",()=>{
    const now = localStorage.getItem("siteTheme") || "dark";
    setTheme(now === "dark" ? "light" : "dark");
});
const saveTheme = localStorage.getItem("siteTheme") || "dark";
setTheme(saveTheme);

const canvas = document.getElementById('starCanvas');
const ctx = canvas.getContext('2d');
let stars = [];
function resizeCanvas(){
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
    createStars();
}
function createStars(){
    stars = [];
    let count = Math.floor((canvas.width*canvas.height)/3000);
    for(let i=0;i<count;i++){
        stars.push({
            x:Math.random()*canvas.width,
            y:Math.random()*canvas.height,
            r:Math.random()*1.3+0.2,
            speed:Math.random()*0.6+0.1,
            opacity:Math.random()
        })
    }
}
function drawStars(){
    ctx.clearRect(0,0,canvas.width,canvas.height);
    stars.forEach(s=>{
        ctx.beginPath();
        ctx.arc(s.x,s.y,s.r,0,Math.PI*2);
        ctx.fillStyle = `rgba(180,210,255,${s.opacity})`;
        ctx.fill();
        s.y += s.speed;
        if(s.y>canvas.height){
            s.y = -5;
            s.x = Math.random()*canvas.width;
        }
    })
    requestAnimationFrame(drawStars);
}
window.addEventListener('resize',resizeCanvas);
resizeCanvas();
drawStars();

const scrollBoxes = document.querySelectorAll('.scroll-box');
function checkScroll(){
    const trigger = window.innerHeight * 0.82;
    scrollBoxes.forEach(el=>{
        const boxTop = el.getBoundingClientRect().top;
        if(boxTop < trigger){
            el.classList.add('active');
        }
    })
}
window.addEventListener('scroll',checkScroll);
window.addEventListener('load',checkScroll);

// 点赞计数逻辑
const likeBtn = document.getElementById('likeBtn');
const likeNum = document.getElementById('likeNum');
// 读取本地存储点赞数
let totalLike = Number(localStorage.getItem('starvisionLike')) || 128;
likeNum.innerText = totalLike;
// 判断当前设备是否已点赞
let hasLiked = localStorage.getItem('hasLiked') === 'true';
if(hasLiked){
    likeBtn.disabled = true;
    likeBtn.innerText = "✅ 已点赞";
}
likeBtn.addEventListener('click',()=>{
    if(hasLiked) return;
    totalLike += 1;
    likeNum.innerText = totalLike;
    localStorage.setItem('starvisionLike',totalLike);
    localStorage.setItem('hasLiked','true');
    hasLiked = true;
    likeBtn.disabled = true;
    likeBtn.style.opacity = "0.6";
});

// 防查看源码
document.addEventListener('contextmenu',e=>e.preventDefault());
document.onkeydown=function(e){
    if(e.ctrlKey&&(e.keyCode===83||e.keyCode===85||e.keyCode===73))return false;
};
!function(){function e(e,t,n){this.e=e,this.t=t,this.n=n}e.prototype.toString=function(){return this.e+this.t+this.n};window.StarCodeLock=new e("加密","源码","保护")}();
</script>
</body>
</html>
