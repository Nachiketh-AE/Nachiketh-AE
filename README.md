<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Nachiketh Sudhindra Kadkol | Analytics Engineer</title>
<meta name="description" content="Analytics Engineer specializing in SQL transformations, data modeling, ETL/ELT pipelines, reporting automation and data quality.">
<meta property="og:title" content="Nachiketh Sudhindra Kadkol | Analytics Engineer">
<meta property="og:description" content="From raw data to trusted insights: pipelines, reusable analytical models and automated reporting.">
<meta property="og:type" content="website">
<meta name="twitter:card" content="summary">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Geist:wght@400;500;600;700&family=Geist+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{--bg:#0e1116;--bg2:#151a22;--line:#262d38;--tx:#e8edf3;--mu:#9aa6b5;--ac:#38bdf8;--ok:#2dd4bf;--warn:#fbbf24;--bad:#f87171;
--sans:"Geist",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;--mono:"Geist Mono",ui-monospace,Menlo,Consolas,monospace}
:root[data-theme="light"]{--bg:#f6f8fb;--bg2:#fff;--line:#d9e0ea;--tx:#101722;--mu:#4a5668;--ac:#0369a1;--ok:#0f766e;--warn:#b45309;--bad:#b91c1c}
@media (prefers-color-scheme:light){:root:not([data-theme="dark"]){--bg:#f6f8fb;--bg2:#fff;--line:#d9e0ea;--tx:#101722;--mu:#4a5668;--ac:#0369a1;--ok:#0f766e;--warn:#b45309;--bad:#b91c1c}}
*{box-sizing:border-box}
:root{padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-behavior:smooth;scroll-padding-top:calc(72px + env(safe-area-inset-top,0px))}
body{margin:0;background:var(--bg);color:var(--tx);font:16px/1.65 var(--sans);-webkit-font-smoothing:antialiased}
a{color:var(--ac)}
:focus-visible{outline:2px solid var(--ac);outline-offset:3px;border-radius:4px}
.w{max-width:1120px;margin:0 auto;padding:0 24px}
section{padding:96px 0;border-top:1px solid var(--line)}
h1,h2,h3{line-height:1.12;letter-spacing:-.02em;margin:0}
h2{font-size:clamp(28px,4vw,40px);margin-bottom:12px}
h3{font-size:19px;letter-spacing:-.01em}
p{margin:0 0 12px}
.lead{color:var(--mu);max-width:62ch;margin-bottom:40px}
.mono{font-family:var(--mono);font-size:13px}
.mu{color:var(--mu)}
header.nav{position:sticky;top:0;z-index:20;background:color-mix(in srgb,var(--bg) 92%,transparent);border-bottom:1px solid var(--line);backdrop-filter:blur(8px);padding-top:env(safe-area-inset-top,0px)}
.nav .w{display:flex;align-items:center;justify-content:space-between;height:60px;gap:16px}
.nav nav{display:flex;gap:20px;overflow-x:auto;scrollbar-width:none}
.nav nav a{color:var(--mu);text-decoration:none;font-size:14px;white-space:nowrap}
.nav nav a:hover{color:var(--tx)}
.brand{font-weight:600;color:var(--tx);text-decoration:none;white-space:nowrap}
.btn{display:inline-block;padding:12px 22px;border-radius:8px;font-weight:500;text-decoration:none;border:1px solid var(--line);color:var(--tx);background:none;cursor:pointer;font:500 15px var(--sans)}
.btn.p{background:var(--ac);border-color:var(--ac);color:#04121c}
.btn:hover{border-color:var(--ac)}
.hero{padding:72px 0 80px;border:0}
.eyebrow{font:500 12px var(--mono);letter-spacing:.14em;color:var(--ac);margin-bottom:20px}
.hero h1{font-size:clamp(40px,7vw,76px);max-width:14ch;margin-bottom:24px}
.hero .lead{font-size:18px;margin-bottom:28px}
.row{display:flex;flex-wrap:wrap;gap:12px;align-items:center}
.links a{font-size:14px;color:var(--mu)}
.pipe{margin-top:56px;border:1px solid var(--line);border-radius:12px;background:var(--bg2);padding:20px}
.pipe svg{width:100%;height:auto;display:block}
.stages{display:grid;grid-template-columns:repeat(6,1fr);gap:8px;margin-top:8px}
.stg{background:none;border:1px solid var(--line);color:var(--mu);border-radius:8px;padding:10px 8px;font:500 13px var(--sans);cursor:pointer;text-align:left}
.stg[aria-pressed=true],.stg:hover{border-color:var(--ac);color:var(--tx)}
.stg[data-q=true][aria-pressed=true]{border-color:var(--ok)}
.pdesc{margin-top:14px;min-height:56px;color:var(--tx)}
.pdesc b{color:var(--ac)}
.pill{fill:var(--bg);stroke:var(--line);stroke-width:1.5}
.pn.on .pill{stroke:var(--ac);fill:color-mix(in srgb,var(--ac) 18%,var(--bg))}
.pn.q.on .pill{stroke:var(--ok);fill:color-mix(in srgb,var(--ok) 18%,var(--bg))}
.flow{stroke:var(--ac);stroke-width:1.5;fill:none;stroke-dasharray:6 6;opacity:.7}
.draw{stroke-dasharray:1200;stroke-dashoffset:1200;animation:dr 1.6s .2s ease forwards}
@keyframes dr{to{stroke-dashoffset:0}}
.grid4{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.card{border:1px solid var(--line);border-radius:10px;background:var(--bg2);padding:24px}
.pil dl{margin:16px 0 0}.pil dt{font:500 12px var(--mono);color:var(--ac);margin-top:12px}.pil dd{margin:2px 0 0;color:var(--mu);font-size:15px}
.pil svg{width:100%;height:56px;margin-bottom:12px}
.mets{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1px;background:var(--line);border:1px solid var(--line);border-radius:10px;overflow:hidden}
.met{background:var(--bg2);padding:24px}
.met .n{font-size:40px;font-weight:600;letter-spacing:-.03em;font-variant-numeric:tabular-nums}
.met .n i{font-style:normal;color:var(--mu);font-weight:400;margin:0 6px}
.met p{color:var(--mu);font-size:14px;margin:4px 0 10px}
.tag{font:500 11px var(--mono);color:var(--ok);border:1px solid color-mix(in srgb,var(--ok) 40%,transparent);border-radius:99px;padding:2px 9px;display:inline-block}
.note{font-size:13px;color:var(--mu);margin-top:16px}
.tabs{display:flex;gap:8px;margin-bottom:24px;flex-wrap:wrap}
.tab{padding:10px 18px;border-radius:8px;border:1px solid var(--line);background:none;color:var(--mu);font:500 15px var(--sans);cursor:pointer}
.tab[aria-selected=true]{color:var(--tx);border-color:var(--ac)}
.case{display:none}.case.on{display:block;animation:fi .4s ease}
@keyframes fi{from{opacity:0}to{opacity:1}}
.facts{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px;margin:24px 0}
.facts h4{margin:0 0 6px;font:500 12px var(--mono);color:var(--ac)}
.facts p,.facts li{color:var(--mu);font-size:15px}.facts ul{margin:0;padding-left:18px}
.arch{display:flex;flex-wrap:wrap;gap:8px;align-items:center;margin:20px 0}
.arch span{border:1px solid var(--line);border-radius:6px;padding:8px 12px;font:500 13px var(--mono);background:var(--bg2)}
.arch span.q{border-color:var(--ok);color:var(--ok)}
.arch em{color:var(--ac);font-style:normal}
.two{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
.scroll{overflow-x:auto}
table{border-collapse:collapse;width:100%;font:13px var(--mono)}
td,th{padding:8px 10px;border-bottom:1px solid var(--line);text-align:left;white-space:nowrap}
th{color:var(--mu);font-weight:500}
.chk{list-style:none;padding:0;margin:16px 0}
.chk li{display:flex;justify-content:space-between;gap:12px;padding:10px 0;border-bottom:1px solid var(--line);font-size:14px;color:var(--mu)}
.chk li .st{font:500 12px var(--mono)}
.chk li.ok{color:var(--tx)}.chk li.ok .st{color:var(--ok)}.chk li.bad{color:var(--tx)}.chk li.bad .st{color:var(--bad)}
.tl{position:relative;margin-left:8px;border-left:1px solid var(--line);padding-left:28px}
.tl-prog{position:absolute;left:-1px;top:0;width:2px;background:var(--ac);height:0}
.job{position:relative;margin-bottom:20px}
.job::before{content:"";position:absolute;left:-35px;top:8px;width:13px;height:13px;border-radius:50%;background:var(--bg);border:2px solid var(--ac)}
.job summary{cursor:pointer;list-style:none;display:flex;justify-content:space-between;flex-wrap:wrap;gap:4px 16px;padding:4px 0}
.job summary::-webkit-details-marker{display:none}
.job summary h3 span{color:var(--mu);font-weight:400}
.job ul{margin:10px 0 0;padding-left:18px;color:var(--mu);font-size:15px;max-width:72ch}
.job li{margin-bottom:6px}
.stack{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:20px}
.stack h3{font-size:16px;margin-bottom:12px}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chip{font-size:14px;border:1px solid var(--line);border-radius:6px;padding:4px 10px;color:var(--mu);transition:border-color .2s,color .2s}
.chip:hover{border-color:var(--ac);color:var(--tx)}
.pr{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:20px}
.pr h3{font-size:17px;margin-bottom:6px}.pr p{color:var(--mu);font-size:15px}
.edu{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}
footer{border-top:1px solid var(--line);padding:48px 0;color:var(--mu);font-size:14px}
.rv{opacity:0;transform:translateY(10px);transition:opacity .6s,transform .6s}.rv.in{opacity:1;transform:none}
@media (max-width:760px){.stages{grid-template-columns:repeat(2,1fr)}section{padding:64px 0}.nav nav{gap:14px}}
@media (prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}.draw{stroke-dashoffset:0}.rv{opacity:1;transform:none}html{scroll-behavior:auto}}
</style>
</head>
<body>
<header class="nav"><div class="w"><a class="brand" href="#top">Nachiketh Kadkol</a>
<nav aria-label="Primary"><a href="#capabilities">Capabilities</a><a href="#impact">Impact</a><a href="#work">Case studies</a><a href="#experience">Experience</a><a href="#stack">Stack</a><a href="#contact">Contact</a></nav></div></header>
<main id="top">
<section class="hero"><div class="w">
<p class="eyebrow">ANALYTICS ENGINEERING · DATA MODELING · AUTOMATION</p>
<h1>From raw data to trusted insights.</h1>
<p class="lead">I build reliable data pipelines, reusable analytical models, and automated reporting workflows that transform fragmented data into consistent, decision-ready analytics.</p>
<div class="row"><a class="btn p" href="#work">Explore My Work</a><a class="btn" id="resumeBtn" href="#experience">View Resume</a><span class="links row" id="social"></span></div>
<p class="mu mono" style="margin-top:20px">Amherst, Massachusetts · Open to relocation</p>
<div class="pipe" role="group" aria-label="Analytics engineering pipeline, six stages">
<svg viewBox="0 0 960 110" aria-hidden="true" id="pipeSvg"></svg>
<div class="stages" id="stages"></div>
<p class="pdesc" id="pdesc" aria-live="polite"></p>
</div>
</div></section>

<section id="capabilities"><div class="w">
<h2>Engineering principles in practice</h2>
<p class="lead">Four capabilities that turn separate sources into datasets people can rely on.</p>
<div class="grid4" id="pillars"></div>
</div></section>

<section id="impact"><div class="w">
<h2>Impact, with context</h2>
<p class="lead">Each figure comes from my resume and is tied to the role or project where it happened. These are self-reported and have not been independently audited.</p>
<div class="mets" id="mets"></div>
</div></section>

<section id="work"><div class="w">
<h2>Featured case studies</h2>
<p class="lead">Selected projects described in my resume. They are presented as technical case studies; source code is not public unless a repository link appears.</p>
<div class="tabs" role="tablist" aria-label="Case studies">
<button class="tab" role="tab" id="t0" aria-controls="c0" aria-selected="true">Sales &amp; Revenue Analytics</button>
<button class="tab" role="tab" id="t1" aria-controls="c1" aria-selected="false">BI Automation &amp; Data Quality</button></div>

<div class="case on" id="c0" role="tabpanel" aria-labelledby="t0">
<p class="mono mu">Snowflake · SQL · Alteryx Designer · Tableau</p>
<div class="arch" aria-label="Data flow"><span>Source systems</span><em>→</em><span>Snowflake</span><em>→</em><span>SQL transformations</span><em>→</em><span>Analytical models</span><em>→</em><span class="q">Data validation</span><em>→</em><span>Tableau reporting</span></div>
<div class="facts">
<div><h4>Problem</h4><p>Sales, finance and operational data lived in 3+ separate systems and fed roughly 10 manual reports.</p></div>
<div><h4>Approach</h4><p>Consolidated the sources in Snowflake and built reusable SQL transformations and analytical models for revenue, sales and customer reporting.</p></div>
<div><h4>Validation</h4><p>Alteryx Designer automated data preparation and pre-reporting validation.</p></div>
<div><h4>Outcome</h4><p>Interactive Tableau dashboards replaced approximately 10 manual reports, centralizing revenue, regional sales, customer performance and executive KPIs.</p></div></div>
<div class="card"><h3>Dashboard layout preview</h3>
<svg viewBox="0 0 640 250" role="img" aria-label="Illustrative dashboard layout with KPI tiles, a revenue trend line, and regional bars" style="width:100%;height:auto;margin-top:12px">
<g font-family="Geist,system-ui,sans-serif" font-size="11" fill="var(--mu)">
<g id="kp"></g>
<rect x="10" y="80" width="380" height="160" rx="8" fill="none" stroke="var(--line)"/><text x="22" y="100">Revenue trend (sample)</text>
<path class="draw" d="M24 215 L84 195 L144 200 L204 165 L264 170 L324 135 L376 120" fill="none" stroke="var(--ac)" stroke-width="2.5"/>
<rect x="400" y="80" width="230" height="160" rx="8" fill="none" stroke="var(--line)"/><text x="412" y="100">Regional performance (sample)</text>
<g fill="var(--ok)"><rect x="412" y="115" width="170" height="14" rx="3"/><rect x="412" y="145" width="130" height="14" rx="3"/><rect x="412" y="175" width="100" height="14" rx="3"/><rect x="412" y="205" width="60" height="14" rx="3"/></g>
</g></svg>
<p class="note">Illustrative sample layout with placeholder shapes. No values here are real business results.</p></div>
</div>

<div class="case" id="c1" role="tabpanel" aria-labelledby="t1" hidden>
<p class="mono mu">SQL · ETL/ELT · Data Modeling</p>
<div class="facts">
<div><h4>Problem</h4><p>Recurring reports were prepared by hand, with logic duplicated across outputs.</p></div>
<div><h4>Approach</h4><p>Automated and restructured 10+ recurring SQL reporting workflows into reusable ETL/ELT datasets supporting 15+ reports and KPI outputs.</p></div>
<div><h4>Validation</h4><p>Validation and reconciliation checks identify inconsistencies before dashboard delivery.</p></div>
<div><h4>Outcome</h4><p>Less manual preparation, simpler maintenance, and KPI views with standardized reporting logic.</p></div></div>
<div class="card"><h3>Data-quality demonstration</h3>
<p class="note" style="margin-top:4px"><b>Synthetic demo.</b> The records and counts below are invented to show the method, not a production dataset.</p>
<div class="two" style="margin-top:16px">
<div class="scroll"><table aria-label="Synthetic source records"><thead><tr><th>order_id</th><th>region</th><th>amount</th></tr></thead><tbody id="rows"></tbody></table></div>
<div><ul class="chk" id="chk" aria-live="polite"></ul>
<label class="mu" style="font-size:14px"><input type="checkbox" id="defect"> Inject a defect upstream</label>
<div class="row" style="margin-top:12px"><button class="btn p" id="run">Run pipeline</button><button class="btn" id="reset">Reset</button></div></div></div></div>
</div>
</div></section>

<section id="experience"><div class="w">
<h2>Experience</h2>
<p class="lead">Select a role to expand its details.</p>
<div class="tl" id="tl"><div class="tl-prog" id="prog"></div></div>
</div></section>

<section id="stack"><div class="w">
<h2>Technical stack, grouped by purpose</h2>
<p class="lead">Only tools and methods from my resume. No proficiency scores.</p>
<div class="stack" id="stk"></div>
</div></section>

<section id="principles"><div class="w">
<h2>How I approach analytical systems</h2>
<p class="lead">Working principles, not claims about any specific production system.</p>
<div class="pr" id="prs"></div>
</div></section>

<section id="education"><div class="w">
<h2>Education</h2>
<div class="edu">
<div class="card"><h3>University of Massachusetts Amherst</h3><p class="mu">M.S., Data Analytics and Computational Social Science<br>Aug 2024 – May 2026</p></div>
<div class="card"><h3>Mumbai University</h3><p class="mu">B.E., Information Technology<br>Aug 2019 – May 2023</p></div></div>
</div></section>
</main>
<footer id="contact"><div class="w">
<h2 style="font-size:28px">Let's talk about your data.</h2>
<p class="row" id="foot"></p>
<p class="note">Built as a single static page. Sample data is labeled wherever it appears.</p></div></footer>

<script>
/* ===== Editable content ===== */
const CONFIG={email:"nachikethkadkol61@gmail.com",github:"",linkedin:"",resume:""}; // add URLs here; empty ones are hidden
const STAGES=[
["Data sources","Business systems, research data, sales data and operational data."],
["Ingestion","Data extraction and integration through scheduled pipelines."],
["Transformation","SQL transformations, cleaning, standardization and business logic."],
["Data modeling","Reusable analytical datasets, modeled tables and consistent KPI definitions."],
["Data quality","Validation, reconciliation and consistency checks before anything is reported.",1],
["Analytics delivery","Reporting datasets, dashboards, KPI reporting and stakeholder insights."]];
const PILLARS=[
["Data integration","Sources are siloed and inconsistent.","Bring business and research sources into scheduled pipelines and shared analytical datasets.","Dependable datasets for recurring reporting.","M4 28h16M4 12h16M20 12l8 8-8 8M20 28l8-8"],
["SQL transformations and modeling","Raw data cannot be reported on directly.","Structure sources with SQL into reusable models that carry consistent reporting logic.","One modeled layer serving many outputs.","M6 8h28v8H6zM6 24h12v8H6zM22 24h12v8H22zM20 16v4M12 24v-4h16v4"],
["Data quality and reliability","Inconsistencies surface after reports ship.","Apply validation and reconciliation checks before delivery.","Issues caught before stakeholders see them.","M6 20l8 8 20-20M6 8h10M6 32h10"],
["Analytics automation","Repetitive preparation slows reporting.","Replace manual steps with reusable workflows.","Shorter reporting turnaround.","M8 20a12 12 0 0 1 22-6M32 8v8h-8M32 20a12 12 0 0 1-22 6M8 32v-8h8"]];
const METS=[
[[4],"+","business and research data sources integrated","SAGO · Analytics Engineer"],
[[6,2]," h","manual consolidation per cycle (approx.)","SAGO · Analytics Engineer"],
[[4,1.5]," h","statistical reporting turnaround per cycle (approx.)","SAGO · Analytics Engineer"],
[[25],"%","reduction in typical ETL/ELT refresh times (approx.)","Diacto · BI Analyst"],
[[9],"+","ETL/ELT workflows built and maintained","Diacto · BI Analyst"],
[[11],"+","analytical datasets with standardized reporting logic","Diacto · BI Analyst"],
[[14],"+","recurring reports consolidated","Diacto · BI Analyst"],
[[10]," h/wk","reporting preparation saved (approx.)","Diacto · BI Analyst"],
[[13],"+","enterprise engagements supported","Diacto · BI Analyst"]];
const JOBS=[
["Analytics Engineer","SAGO","Jun 2026 – Present",["Integrated 4+ business and research data sources through scheduled daily and weekly pipelines into an AWS-based lakehouse and Dremio Cloud.","Reduced manual consolidation from approximately 6 to 2 hours per cycle.","Automated recurring statistical reporting, from approximately 4 to 1.5 hours per cycle.","Built dashboards, analytical workflows, applications and proofs of concept using Hex and Superset.","Coordinated a six-member team across research workflows, data structures, visualization and analytics architecture."]],
["Analytics Intern","SAGO","Jan 2026 – May 2026",["Supported extraction, integration and preparation of business and research data.","Helped consolidate siloed sources into datasets for recurring reporting.","Assisted with dashboard development and automation of recurring research and reporting tasks."]],
["BI Analyst","Diacto Technologies","Jan 2023 – Aug 2024",["Built and maintained 9+ ETL/ELT workflows.","Optimized SQL queries and transformation logic, reducing typical refresh times by approximately 25%.","Standardized reporting logic across 11+ analytical datasets, with validation and reconciliation checks before dashboard delivery.","Developed and optimized 9+ dashboards and KPI scorecards.","Consolidated 14+ recurring reports, saving approximately 10 hours of preparation per week.","Delivered solutions across 13+ enterprise engagements, leading requirements workshops.","Mentored junior analysts in SQL, data workflows, data modeling and BI development."]],
["Intern","Diacto Technologies","Sep 2022 – Dec 2022",["Supported SQL-based data preparation and ETL workflows.","Assisted with dashboard development, validation and reconciliation."]]];
const STACK=[
["SQL and transformations",["SQL","SQL transformations","Transformation logic"]],
["Data platforms",["Snowflake","Dremio Cloud","AWS"]],
["Integration and workflow",["ETL/ELT","Data integration","Alteryx Designer","Reporting automation"]],
["Analytics and visualization",["Tableau","Hex","Apache Superset","KPI reporting"]],
["Modeling and quality",["Reusable analytical datasets","Data modeling","Validation","Reconciliation","Standardized reporting logic"]],
["Delivery",["Requirements gathering","Stakeholder collaboration","Solution design","Deployment","Production support"]]];
const PRIN=[["Reusability","Datasets and transformations that support multiple reporting needs."],["Consistency","Standardized business logic and KPI definitions."],["Reliability","Data validated and results reconciled before delivery."],["Efficiency","Less repeated manual preparation and unnecessary processing."],["Maintainability","Workflows organized for understandable, repeatable delivery."]];

/* ===== Helpers ===== */
const $=s=>document.querySelector(s),NS="http://www.w3.org/2000/svg";
const RM=matchMedia("(prefers-reduced-motion:reduce)").matches;
const esc=t=>String(t).replace(/[&<>]/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;"}[c]));

/* links */
const soc=[];if(CONFIG.github)soc.push(`<a href="${CONFIG.github}" rel="noopener">GitHub</a>`);if(CONFIG.linkedin)soc.push(`<a href="${CONFIG.linkedin}" rel="noopener">LinkedIn</a>`);
$("#social").innerHTML=soc.join("");
if(CONFIG.resume){$("#resumeBtn").href=CONFIG.resume;$("#resumeBtn").target="_blank"}
$("#foot").innerHTML=[`<a href="mailto:${CONFIG.email}">${CONFIG.email}</a>`,...soc].join(" · ");

/* hero pipeline */
const svg=$("#pipeSvg"),xs=STAGES.map((_,i)=>80+i*160);let pd="M"+xs[0]+" 45";
xs.slice(1).forEach(x=>pd+=" L"+x+" 45");
svg.innerHTML=`<path id="mp" class="flow draw" d="${pd}"/>`+STAGES.map((s,i)=>`<g class="pn${s[2]?" q":""}" data-i="${i}"><rect class="pill" x="${xs[i]-36}" y="25" width="72" height="40" rx="8"/><text x="${xs[i]}" y="50" text-anchor="middle" font-size="12" fill="var(--tx)" font-family="Geist Mono,monospace">${i<2?["src","ingest"][i]:["sql","model","check","serve"][i-2]}</text></g>`).join("")
+(RM?"":[0,1,2,3,4].map(k=>`<circle r="3.5" fill="var(--ac)"><animateMotion dur="7s" begin="${k*1.4}s" repeatCount="indefinite"><mpath href="#mp"/></animateMotion></circle>`).join(""))
+`<text x="${xs[0]}" y="100" font-size="11" fill="var(--mu)" font-family="Geist,sans-serif">raw and fragmented</text><text x="${xs[5]}" y="100" font-size="11" text-anchor="end" fill="var(--mu)" font-family="Geist,sans-serif">consistent and decision-ready</text>`;
const stg=$("#stages");
STAGES.forEach((s,i)=>{const b=document.createElement("button");b.className="stg";b.textContent=s[0];if(s[2])b.dataset.q="true";b.setAttribute("aria-pressed","false");
 const on=()=>{stg.querySelectorAll(".stg").forEach((x,j)=>x.setAttribute("aria-pressed",j==i));svg.querySelectorAll(".pn").forEach((g,j)=>g.classList.toggle("on",j==i));$("#pdesc").innerHTML=`<b>${s[0]}.</b> ${s[1]}`};
 b.onclick=on;b.onmouseenter=on;b.onfocus=on;stg.append(b);if(i==0)b._on=on});
stg.firstChild._on();

/* pillars */
$("#pillars").innerHTML=PILLARS.map(p=>`<article class="card pil"><svg viewBox="0 0 40 40" aria-hidden="true" style="width:40px;height:40px"><path d="${p[4]}" fill="none" stroke="var(--ac)" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg><h3>${p[0]}</h3><dl><dt>Problem</dt><dd>${p[1]}</dd><dt>Approach</dt><dd>${p[2]}</dd><dt>Value</dt><dd>${p[3]}</dd></dl></article>`).join("");

/* metrics */
$("#mets").innerHTML=METS.map(m=>`<div class="met"><div class="n">${m[0].map(v=>`<span data-n="${v}">${v}</span>`).join("<i>to</i>")}${m[1]}</div><p>${m[2]}</p><span class="tag">${m[3]}</span></div>`).join("");
const count=el=>{const to=+el.dataset.n,dec=String(to).includes(".")?1:0,t0=performance.now();const f=t=>{const k=Math.min((t-t0)/1100,1);el.textContent=(to*(1-Math.pow(1-k,3))).toFixed(dec);if(k<1)requestAnimationFrame(f)};requestAnimationFrame(f)};
const mo=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){if(!RM)e.target.querySelectorAll("[data-n]").forEach(count);mo.unobserve(e.target)}}),{threshold:.4});
document.querySelectorAll(".met").forEach(m=>mo.observe(m));

/* dashboard kpi tiles (placeholders only) */
$("#kp").innerHTML=[0,1,2,3].map(i=>`<rect x="${10+i*160}" y="8" width="150" height="62" rx="8" fill="none" stroke="var(--line)"/><text x="${22+i*160}" y="30">${["Revenue","Orders","Customers","Margin"][i]} (sample)</text><rect x="${22+i*160}" y="42" width="${60+i*10}" height="12" rx="3" fill="var(--line)"/>`).join("");

/* tabs */
const tabs=[...document.querySelectorAll(".tab")];
tabs.forEach((t,i)=>{t.onclick=()=>{tabs.forEach((x,j)=>{x.setAttribute("aria-selected",j==i);const c=$("#c"+j);c.classList.toggle("on",j==i);c.hidden=j!=i})}});

/* data-quality demo (synthetic) */
const SRC=[["A-101","North",120],["A-102","South",80],["A-102","South",80],["A-103","East",null],["A-104","West",200],["A-105","North",150]];
const rows=$("#rows"),chk=$("#chk");
const draw=(d,cls)=>rows.innerHTML=d.map(r=>`<tr${cls&&cls(r)?` style="color:var(--bad)"`:""}><td>${r[0]}</td><td>${r[1]}</td><td>${r[2]??"NULL"}</td></tr>`).join("");
const reset=()=>{draw(SRC);chk.innerHTML=`<li class="ok"><span>Source row count</span><span class="st">${SRC.length} rows</span></li>`;$("#run").disabled=false};
$("#reset").onclick=reset;
$("#run").onclick=function(){this.disabled=true;reset();$("#run").disabled=true;
 const seen=new Set(),dup=SRC.filter(r=>seen.has(r[0])?true:(seen.add(r[0]),false)),nul=SRC.filter(r=>r[2]==null);
 const clean=SRC.filter((r,i)=>SRC.findIndex(x=>x[0]==r[0])==i&&r[2]!=null),def=$("#defect").checked;
 const srcSum=clean.reduce((a,r)=>a+r[2],0),tgt=def?srcSum-50:srcSum;
 const steps=[
 ()=>{draw(SRC,r=>dup.includes(r));return["Duplicate check",`${dup.length} found`,"bad"]},
 ()=>{draw(SRC,r=>nul.includes(r));return["Null check",`${nul.length} found`,"bad"]},
 ()=>{draw(clean);return["Transformation: dedupe, drop nulls",`${clean.length} rows kept`,"ok"]},
 ()=>def?["Reconciliation: source vs model total",`mismatch (${srcSum} vs ${tgt})`,"bad"]:["Reconciliation: source vs model total",`match (${srcSum})`,"ok"],
 ()=>def?["Final dataset","held back until fixed","bad"]:["Final modeled dataset",`published, ${clean.length} rows`,"ok"]];
 steps.forEach((s,i)=>setTimeout(()=>{const r=s();chk.insertAdjacentHTML("beforeend",`<li class="${r[2]}"><span>${r[0]}</span><span class="st">${r[1]}</span></li>`);if(i==steps.length-1)$("#run").disabled=false},RM?0:(i+1)*650)) };
reset();

/* timeline */
$("#tl").insertAdjacentHTML("beforeend",JOBS.map((j,i)=>`<details class="job"${i==0?" open":""}><summary><h3>${j[0]} <span>· ${j[1]}</span></h3><span class="mono mu">${j[2]}</span></summary><ul>${j[3].map(x=>`<li>${x}</li>`).join("")}</ul></details>`).join(""));
const tl=$("#tl"),prog=$("#prog"),upd=()=>{const r=tl.getBoundingClientRect(),h=r.height,p=Math.max(0,Math.min(h,innerHeight*.6-r.top));prog.style.height=p+"px"};
addEventListener("scroll",upd,{passive:true});addEventListener("resize",upd);upd();

/* stack, principles */
$("#stk").innerHTML=STACK.map(g=>`<div class="card"><h3>${g[0]}</h3><div class="chips">${g[1].map(c=>`<span class="chip">${c}</span>`).join("")}</div></div>`).join("");
$("#prs").innerHTML=PRIN.map(p=>`<div><h3>${p[0]}</h3><p>${p[1]}</p></div>`).join("");

/* reveal */
document.querySelectorAll(".card,.pr>div,.edu>div").forEach(e=>e.classList.add("rv"));
const ro=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("in");ro.unobserve(e.target)}}),{threshold:.1});
document.querySelectorAll(".rv").forEach(e=>ro.observe(e));
</script>
</body>
</html>
