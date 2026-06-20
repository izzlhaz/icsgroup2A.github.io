<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Venture Capitalist's Endeavor — TEQ Technologies Case Study</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@500;600;700&family=Inter:wght@400;500;600;700&family=IBM+Plex+Mono:wght@500;600&display=swap" rel="stylesheet">
<style>
  /* ============ TOKENS ============ */
  :root{
    --bg: #eeede9;
    --paper: #ffffff;
    --ink: #15151a;
    --muted: #6c6f76;
    --faint: #9a9da3;
    --line: #e4e2dd;

    --blue:   #2d5fdb;
    --green:  #1c9d5c;
    --amber:  #d6790f;
    --violet: #8b3dd1;
    --coral:  #e2572b;
    --teal:   #0f8f8a;
    --pink:   #d6336c;
    --slate:  #4b5160;

    --r-lg: 30px;
    --r-md: 20px;
    --r-sm: 12px;
    --shadow: 0 24px 60px -28px rgba(20,20,26,.30), 0 2px 10px -2px rgba(20,20,26,.08);
    --shadow-sm: 0 10px 24px -14px rgba(20,20,26,.22);

    --font-display: 'Space Grotesk', 'Inter', sans-serif;
    --font-body: 'Inter', sans-serif;
    --font-mono: 'IBM Plex Mono', monospace;
  }

  *{ box-sizing: border-box; }
  html{ scroll-behavior: smooth; }
  body{
    margin:0;
    background: var(--bg);
    color: var(--ink);
    font-family: var(--font-body);
    -webkit-font-smoothing: antialiased;
    line-height: 1.55;
    overflow-x:hidden;
  }
  img,svg{ display:block; max-width:100%; }
  ul{ margin:0; padding:0; list-style:none; }
  p{ margin:0; }
  button{ font-family: inherit; }

  @media (prefers-reduced-motion: reduce){
    *{ animation-duration: .001ms !important; animation-iteration-count: 1 !important; transition-duration: .001ms !important; scroll-behavior: auto !important; }
  }

  /* ============ HOLOGRAPHIC BLOB ============ */
  .blob{
    position:absolute;
    border-radius: 41% 59% 63% 37% / 47% 41% 59% 53%;
    background: conic-gradient(from 210deg at 50% 50%,
      #ffd9ec, #d9c8ff, #bfe2ff, #c4f3e2, #fff4c2, #ffd2d2, #ffd9ec);
    filter: blur(1px) saturate(1.25);
    opacity: .8;
    pointer-events:none;
    z-index:0;
  }
  .blob::after{
    content:"";
    position:absolute; inset:0;
    border-radius: inherit;
    background: radial-gradient(circle at 30% 25%, rgba(255,255,255,.85), rgba(255,255,255,0) 55%);
  }
  .blob--hero{
    width: 560px; height: 560px;
    top: -220px; right: -160px;
    animation: drift 26s ease-in-out infinite;
  }
  .blob--footer{
    width: 360px; height: 360px;
    bottom: -180px; left: -120px;
    animation: drift 30s ease-in-out infinite reverse;
  }
  @keyframes drift{
    0%,100%{ transform: rotate(0deg) scale(1); }
    50%{ transform: rotate(14deg) scale(1.04); }
  }

  /* ============ LAYOUT SHELL ============ */
  .wrap{
    width:100%;
    max-width: 1180px;
    margin: 0 auto;
    padding: 0 28px;
  }

  /* ============ HERO ============ */
  .hero{
    position:relative;
    overflow:hidden;
    padding: 40px 0 36px;
    border-bottom: 1px solid var(--line);
    opacity:0;
    animation: rise .7s .05s ease forwards;
  }
  .hero__inner{ position:relative; z-index:1; }
  .brand{ display:flex; align-items:center; gap:14px; margin-bottom:34px; min-width:0; }
  .brand__logo{
    width:46px; height:46px; border-radius:50%;
    background: var(--blue);
    color:#fff;
    display:flex; align-items:center; justify-content:center;
    font-family: var(--font-display); font-weight:700; font-size:13px; letter-spacing:.5px;
    border: 2px solid #fff;
    box-shadow: 0 0 0 1px var(--line);
    flex-shrink:0;
  }
  .brand__text{ min-width:0; }
  .brand__text p{ margin:0; }
  .brand__school{ font-size:12.5px; font-weight:600; color: var(--ink); overflow-wrap:anywhere; }
  .brand__uni{ font-size:12px; color: var(--blue); font-weight:600; margin-top:1px; overflow-wrap:anywhere; }

  .hero__title{
    font-family: var(--font-display);
    font-weight:700;
    font-size: 52px;
    line-height: 1.04;
    letter-spacing: 0;
    margin: 0 0 6px;
    max-width: 16ch;
    overflow-wrap:break-word;
  }
  .hero__subtitle{
    font-family: var(--font-display);
    font-weight:500;
    font-size: 25px;
    color:#3a3c42;
    max-width: 22ch;
    margin-bottom:16px;
  }
  .hero__eyebrow{
    font-family: var(--font-mono);
    font-size: 12.5px;
    text-transform: uppercase;
    letter-spacing: .06em;
    color: var(--muted);
  }
  .hero__eyebrow span{ color: var(--coral); font-weight:600; }

  /* ============ TABS ============ */
  .tabbar{
    position: sticky;
    top:0;
    z-index: 20;
    background: rgba(238,237,233,.92);
    backdrop-filter: blur(10px);
    border-bottom: 1px solid var(--line);
  }
  .tabs{
    display:flex;
    gap:8px;
    padding: 14px 0;
    overflow-x:auto;
    overscroll-behavior-inline: contain;
    -webkit-overflow-scrolling: touch;
    scroll-padding-inline: 28px;
    scroll-snap-type: x proximity;
    scrollbar-width: none;
  }
  .tabs::-webkit-scrollbar{ display:none; }
  .tab{
    --c: var(--blue);
    flex: 0 0 auto;
    display:flex; align-items:center; gap:7px;
    min-height:44px;
    padding: 9px 16px 9px 12px;
    border-radius: 999px;
    border: 1.5px solid var(--line);
    background: #fff;
    color: var(--muted);
    font-size: 13.5px;
    font-weight: 600;
    text-decoration:none;
    cursor:pointer;
    transition: background .2s ease, color .2s ease, border-color .2s ease, transform .15s ease;
    white-space: nowrap;
    scroll-snap-align: start;
  }
  .tab svg{ width:16px; height:16px; flex-shrink:0; opacity:.8; }
  .tab:hover{ transform: translateY(-1px); border-color: var(--c); color: var(--ink); }
  .tab.active{
    background: var(--c);
    border-color: var(--c);
    color: #fff;
  }
  .tab.active svg{ opacity:1; }
  .tab:focus-visible{ outline: 2.5px solid var(--ink); outline-offset:2px; }

  /* ============ CONTENT ============ */
  .content{ position:relative; padding: 48px 0 90px; }

  .panel{
    --accent: var(--blue);
    scroll-margin-top: 86px;
    opacity: 0;
    transform: translateY(22px);
    transition: opacity .65s ease, transform .65s ease;
  }
  .panel.in-view{ opacity:1; transform:none; }
  .panel + .panel{ margin-top: 76px; }
  .panel[data-color="blue"]{ --accent: var(--blue); }
  .panel[data-color="green"]{ --accent: var(--green); }
  .panel[data-color="amber"]{ --accent: var(--amber); }
  .panel[data-color="violet"]{ --accent: var(--violet); }
  .panel[data-color="coral"]{ --accent: var(--coral); }
  .panel[data-color="teal"]{ --accent: var(--teal); }
  .panel[data-color="pink"]{ --accent: var(--pink); }
  .panel[data-color="slate"]{ --accent: var(--slate); }

  .panel-head{ display:flex; align-items:center; gap:14px; margin-bottom: 22px; }
  .panel-head > div:last-child{ min-width:0; }
  .panel-head__index{
    font-family: var(--font-mono);
    font-size: 12px; font-weight:600;
    color: var(--accent);
    border: 1.5px solid var(--accent);
    border-radius: 50%;
    width: 26px; height:26px;
    display:flex; align-items:center; justify-content:center;
    flex-shrink:0;
  }
  .panel-head__icon{
    width:42px; height:42px; border-radius: 13px;
    background: color-mix(in srgb, var(--accent) 14%, white);
    color: var(--accent);
    display:flex; align-items:center; justify-content:center;
    flex-shrink:0;
  }
  .panel-head__icon svg{ width:22px; height:22px; }
  .panel-head h2{
    font-family: var(--font-display);
    font-size: 30px;
    font-weight:700;
    letter-spacing:0;
    color: var(--accent);
    margin:0;
    overflow-wrap:break-word;
  }
  .panel-head p{ font-size:13px; color: var(--muted); margin-top:2px; }

  .card{
    background: var(--paper);
    border-radius: var(--r-lg);
    box-shadow: var(--shadow);
    padding: 34px 36px;
    position: relative;
    overflow:hidden;
  }
  .card + .card{ margin-top: 20px; }
  .card__lede{ font-size:16px; color:#33353b; max-width: 70ch; overflow-wrap:break-word; }

  .subgrid{ display:grid; grid-template-columns: repeat(3,minmax(0,1fr)); gap:22px; margin-top:26px; }
  .sub{ }
  .sub h3{
    font-family: var(--font-display);
    font-size:15px; font-weight:600; color: var(--ink);
    margin:0 0 10px;
    padding-left:12px;
    border-left: 3px solid var(--accent);
  }
  .sub ul li{
    font-size: 14px; color:#45474d;
    padding-left: 16px; position:relative; margin-bottom:8px;
  }
  .sub ul li::before{
    content:""; position:absolute; left:0; top:8px;
    width:5px; height:5px; border-radius:50%;
    background: var(--accent);
  }

  /* timeline (executive summary) */
  .timeline{ display:grid; grid-template-columns: repeat(4,minmax(0,1fr)); gap:18px; margin-top:30px; position:relative; }
  .timeline::before{
    content:""; position:absolute; top:27px; left:8%; right:8%; height:1.5px;
    background: repeating-linear-gradient(90deg, var(--line) 0 8px, transparent 8px 14px);
    z-index:0;
  }
  .tl-step{ position:relative; z-index:1; text-align:center; }
  .tl-step__icon{
    width:54px; height:54px; margin:0 auto 12px;
    border-radius:50%;
    background:#fff;
    border: 1.5px solid var(--line);
    display:flex; align-items:center; justify-content:center;
    color: var(--accent);
    box-shadow: var(--shadow-sm);
  }
  .tl-step__icon svg{ width:24px; height:24px; }
  .tl-step h4{ font-family: var(--font-display); font-size:14.5px; font-weight:700; margin:0 0 4px; }
  .tl-step p{ font-size:12.5px; color: var(--muted); line-height:1.4; }

  /* causes */
  .cause-list{ display:flex; flex-direction:column; gap:24px; margin-top:6px; }
  .cause{ display:flex; gap:18px; }
  .cause__num{
    font-family: var(--font-mono);
    font-size:12px; font-weight:600; color: var(--accent);
    width:30px; height:30px; flex-shrink:0;
    border-radius:50%; border:1.5px solid var(--accent);
    display:flex; align-items:center; justify-content:center;
  }
  .cause__body h3{ font-family: var(--font-display); font-size:16px; font-weight:600; margin:0 0 8px; }
  .cause__body ul li{ font-size:14px; color:#45474d; padding-left:16px; position:relative; margin-bottom:6px; }
  .cause__body ul li::before{ content:""; position:absolute; left:0; top:8px; width:5px; height:5px; border-radius:50%; background:var(--accent); }

  /* options */
  .opts{ display:grid; grid-template-columns: repeat(3,minmax(0,1fr)); gap:18px; margin-top:28px; }
  .opt{
    background:#fbfaf8;
    border:1.5px solid var(--line);
    border-radius: var(--r-md);
    padding:22px;
    transition: transform .2s ease, box-shadow .2s ease;
  }
  .opt:hover{ transform: translateY(-3px); box-shadow: var(--shadow-sm); }
  .opt__tag{ font-family: var(--font-mono); font-size:11px; color:var(--violet); font-weight:600; text-transform:uppercase; letter-spacing:.05em; }
  .opt h3{ font-family: var(--font-display); color: var(--violet); font-size:18px; font-weight:700; margin:6px 0 16px; }
  .opt .pc-label{ font-size:11px; font-weight:700; text-transform:uppercase; letter-spacing:.06em; margin:14px 0 8px; }
  .opt .pc-label.pro{ color: var(--green); }
  .opt .pc-label.con{ color: var(--coral); }
  .opt ul li{ font-size:13px; color:#45474d; padding-left:14px; position:relative; margin-bottom:6px; }
  .opt ul.pro li::before{ content:"+"; position:absolute; left:0; top:0; color:var(--green); font-weight:700; }
  .opt ul.con li::before{ content:"–"; position:absolute; left:0; top:0; color:var(--coral); font-weight:700; }

  /* swot */
  .swot{ display:grid; grid-template-columns: repeat(2,minmax(0,1fr)); gap:16px; margin-top:28px; }
  .swot-box{ border-radius: var(--r-md); padding:20px 22px; }
  .swot-box h3{ font-family: var(--font-display); font-size:15px; font-weight:700; margin:0 0 10px; }
  .swot-box ul li{ font-size:13px; color:#3d3f45; padding-left:14px; position:relative; margin-bottom:6px; }
  .swot-box ul li::before{ content:"›"; position:absolute; left:0; top:0; font-weight:700; }
  .swot-box.strengths{ background: color-mix(in srgb, var(--green) 9%, white); }
  .swot-box.strengths h3{ color: var(--green); }
  .swot-box.strengths li::before{ color: var(--green); }
  .swot-box.weaknesses{ background: color-mix(in srgb, var(--coral) 9%, white); }
  .swot-box.weaknesses h3{ color: var(--coral); }
  .swot-box.weaknesses li::before{ color: var(--coral); }
  .swot-box.opportunities{ background: color-mix(in srgb, var(--blue) 9%, white); }
  .swot-box.opportunities h3{ color: var(--blue); }
  .swot-box.opportunities li::before{ color: var(--blue); }
  .swot-box.threats{ background: color-mix(in srgb, var(--slate) 12%, white); }
  .swot-box.threats h3{ color: var(--slate); }
  .swot-box.threats li::before{ color: var(--slate); }

  /* recommendation */
  .reco-statement{
    font-family: var(--font-display);
    font-size: 27px;
    font-weight:600; line-height:1.35;
    color: var(--ink);
    max-width: 36ch;
  }
  .reco-statement strong{ color: var(--accent); }
  .chips{ display:flex; flex-wrap:wrap; gap:10px; margin-top:26px; }
  .chip{
    font-size:13px; font-weight:600; color: var(--accent);
    background: color-mix(in srgb, var(--accent) 12%, white);
    border-radius:999px; padding:8px 16px;
  }

  /* implementation steps */
  .steps{ display:flex; flex-direction:column; gap:16px; margin-top:26px; }
  .step{ display:flex; gap:16px; align-items:flex-start; }
  .step__n{
    font-family: var(--font-display); font-weight:700; font-size:15px;
    color:#fff; background: var(--accent);
    width:32px; height:32px; border-radius:50%;
    display:flex; align-items:center; justify-content:center; flex-shrink:0;
  }
  .step p{ font-size:14.5px; color:#33353b; padding-top:4px; }

  /* justification stats */
  .stats{ display:grid; grid-template-columns: repeat(3,minmax(0,1fr)); gap:16px; margin-top:8px; margin-bottom:30px; }
  .stat{
    background: color-mix(in srgb, var(--accent) 8%, white);
    border-radius: var(--r-md);
    padding:22px 20px;
    text-align:center;
  }
  .stat__num{ font-family: var(--font-display); font-size: 32px; font-weight:700; color: var(--accent); overflow-wrap:anywhere; }
  .stat__label{ font-size:12px; color: var(--muted); margin-top:4px; }
  .justify-list{ display:flex; flex-direction:column; gap:14px; }
  .justify-list li{ font-size:14.5px; color:#33353b; padding-left:20px; position:relative; }
  .justify-list li::before{ content:"✓"; position:absolute; left:0; top:0; color: var(--accent); font-weight:700; font-size:13px; }

  /* external sources */
  .source-note{
    background: color-mix(in srgb, var(--slate) 8%, white);
    border-radius: var(--r-md);
    padding:18px 22px;
    font-size:13.5px; color:#3d3f45;
    margin-bottom:24px;
    border-left:3px solid var(--slate);
  }
  .source-list{ display:flex; flex-direction:column; gap:14px; }
  .source-item{
    display:flex; gap:14px; align-items:flex-start;
    border:1.5px dashed var(--line); border-radius: var(--r-md);
    padding:16px 18px;
  }
  .source-item__n{ font-family: var(--font-mono); font-size:12px; color: var(--slate); font-weight:600; padding-top:2px; }
  .source-item p{ font-size:13.5px; color:#55575d; }
  .source-item .ph{ color: var(--faint); font-style:italic; }

  /* ============ FOOTER ============ */
  .footer{
    position:relative; overflow:hidden;
    border-top:1px solid var(--line);
    padding: 30px 0 34px;
    text-align:center;
  }
  .footer__label{
    font-family: var(--font-mono); font-size:11px; text-transform:uppercase;
    letter-spacing:.08em; color: var(--muted); margin-bottom:12px; position:relative; z-index:1;
  }
  .footer__members{
    display:flex; flex-wrap:wrap; justify-content:center; gap: 10px 22px;
    position:relative; z-index:1;
  }
  .footer__members li{ font-size:13.5px; color: var(--ink); font-weight:600; }
  .footer__members li span{
    font-family: var(--font-mono); font-weight:500; color: var(--muted);
    font-size:12px; margin-left:5px;
  }

  @keyframes rise{
    from{ opacity:0; transform: translateY(10px); }
    to{ opacity:1; transform: translateY(0); }
  }

  /* ============ RESPONSIVE ============ */
  @media (max-width: 880px){
    .hero__title{ font-size:44px; }
    .hero__subtitle{ font-size:22px; }
    .panel-head h2{ font-size:27px; }
    .reco-statement{ font-size:24px; }
    .stat__num{ font-size:28px; }
    .subgrid{ grid-template-columns: 1fr; }
    .opts{ grid-template-columns: 1fr; }
    .swot{ grid-template-columns: 1fr; }
    .timeline{ grid-template-columns: repeat(2,minmax(0,1fr)); row-gap:30px; }
    .timeline::before{ display:none; }
    .stats{ grid-template-columns: 1fr; }
    .card{ padding: 26px 22px; }
  }
  @media (max-width: 640px){
    .hero{ padding: 30px 0 28px; }
    .content{ padding: 34px 0 64px; }
    .panel + .panel{ margin-top: 52px; }
    .tabs{ padding: 10px 0; gap:6px; scroll-padding-inline:18px; }
    .tab{ font-size:12.5px; padding: 8px 13px 8px 10px; }
    .tab svg{ width:15px; height:15px; }
    .panel-head{ align-items:flex-start; gap:10px; }
    .panel-head__icon{ width:38px; height:38px; border-radius:12px; }
    .panel-head__icon svg{ width:20px; height:20px; }
    .panel-head h2{ font-size:24px; line-height:1.16; }
    .panel-head p{ font-size:12.5px; }
    .card{ border-radius: 18px; padding:22px 18px; }
    .timeline{ grid-template-columns:1fr; gap:18px; }
    .tl-step{ display:grid; grid-template-columns:44px minmax(0,1fr); gap:2px 12px; text-align:left; align-items:center; }
    .tl-step__icon{ width:44px; height:44px; margin:0; grid-row:1 / span 2; }
    .tl-step__icon svg{ width:21px; height:21px; }
    .tl-step p{ font-size:13px; }
    .cause{ gap:12px; }
    .steps{ gap:14px; }
    .step{ gap:12px; }
    .source-item{ gap:10px; padding:14px; }
    .footer__members{ gap:8px 16px; }
  }
  @media (max-width: 540px){
    .wrap{ padding:0 18px; }
    .brand{ align-items:flex-start; margin-bottom:28px; }
    .brand__logo{ width:42px; height:42px; font-size:12px; }
    .hero__title{ font-size:33px; max-width:100%; line-height:1.08; }
    .hero__subtitle{ font-size:19px; max-width:100%; }
    .hero__eyebrow{ font-size:11.5px; line-height:1.5; }
    .blob--hero{ width:320px; height:320px; top:-140px; right:-160px; opacity:.5; }
    .blob--footer{ width:240px; height:240px; bottom:-130px; left:-110px; opacity:.45; }
    .panel-head__index{ width:24px; height:24px; font-size:11px; }
    .card{ padding:20px 16px; border-radius:16px; }
    .subgrid, .opts, .swot{ margin-top:22px; }
    .opt, .swot-box, .stat, .source-note{ border-radius:14px; }
    .opt{ padding:18px; }
    .reco-statement{ font-size:21px; max-width:100%; }
    .chips{ gap:8px; }
    .chip{ font-size:12.5px; padding:8px 12px; }
    .stat__num{ font-size:26px; }
    .footer__members{ flex-direction:column; align-items:center; gap:6px; }
  }
</style>
</head>
<body>

<header class="hero">
  <div class="blob blob--hero" aria-hidden="true"></div>
  <div class="wrap hero__inner">
    <div class="brand">
      <div class="brand__logo">UUM</div>
      <div class="brand__text">
        <p class="brand__school">Pusat Pengajian Perakaunan Tunku Puteri Intan Safinaz</p>
        <p class="brand__uni">Universiti Utara Malaysia</p>
      </div>
    </div>
    <h1 class="hero__title">A Venture Capitalist's Endeavor</h1>
    <p class="hero__subtitle">Valuing TEQ Technologies for Investment</p>
    <p class="hero__eyebrow"><span>Case Study Analysis</span> — Venture Capital &amp; Start-Up Valuation</p>
  </div>
</header>

<div class="tabbar">
  <div class="wrap">
    <nav class="tabs" aria-label="Jump to section" id="tabs"></nav>
  </div>
</div>

<main class="wrap content" id="content"></main>

<footer class="footer">
  <div class="blob blob--footer" aria-hidden="true"></div>
  <p class="footer__label">Project Members</p>
  <ul class="footer__members">
    <li>Dania <span>291296</span></li>
    <li>Izzul <span>294670</span></li>
    <li>A'in <span>296767</span></li>
    <li>Aisyah <span>300670</span></li>
    <li>Syahmi <span>301276</span></li>
  </ul>
</footer>

<script>
/* ---------- ICONS ---------- */
const ICONS = {
  summary: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><rect x="3.5" y="3.5" width="17" height="17" rx="4"/><path d="M7.5 9h9M7.5 13h6"/></svg>`,
  statement: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="9"/><path d="M9.5 9a2.5 2.5 0 1 1 3.5 2.3c-.9.4-1.5 1-1.5 2.1"/><circle cx="12" cy="16.6" r=".4" fill="currentColor"/></svg>`,
  causes: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M12 4v6"/><path d="M12 10c0 4-5 3-5 8"/><path d="M12 10c0 4 5 3 5 8"/><circle cx="12" cy="4" r="2"/></svg>`,
  criteria: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3v18"/><path d="M5 7l-3 6a3.2 3.2 0 0 0 6 0z"/><path d="M19 7l-3 6a3.2 3.2 0 0 0 6 0z"/><path d="M5 7h14"/><path d="M8 21h8"/></svg>`,
  recommend: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="8.5"/><circle cx="12" cy="12" r="4.5"/><path d="M12 12l5.5-5.5"/></svg>`,
  implementation: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="2.6"/><path d="M19.4 13.5a7.6 7.6 0 0 0 0-3l1.8-1.4-1.7-2.9-2.2.6a7.6 7.6 0 0 0-2.6-1.5L14.3 3h-3.4l-.4 2.3a7.6 7.6 0 0 0-2.6 1.5l-2.2-.6-1.7 2.9 1.8 1.4a7.6 7.6 0 0 0 0 3L4 14.9l1.7 2.9 2.2-.6c.75.66 1.63 1.18 2.6 1.5l.4 2.3h3.4l.4-2.3a7.6 7.6 0 0 0 2.6-1.5l2.2.6 1.7-2.9-1.8-1.4z"/></svg>`,
  justification: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3l7 3v6c0 4.5-3 7.5-7 9-4-1.5-7-4.5-7-9V6z"/><path d="M9 12l2 2 4-4.2"/></svg>`,
  sources: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M9.5 14.5l5-5"/><path d="M8 16l-1.8 1.8a3 3 0 0 1-4.2-4.2L4 11.6"/><path d="M16 8l1.8-1.8a3 3 0 0 1 4.2 4.2L20 12.4"/></svg>`,
  rocket: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M12 15c4-1 7-5 7-10 0 0-6-1-10 3-2.5 2.5-3 6-3 6l3 1z"/><path d="M9.5 14.5L5 16l3-4.5"/><path d="M9.5 14.5L8 19l4.5-3"/><circle cx="14.5" cy="7.5" r="1.4"/></svg>`,
  growth: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M3.5 17l5.5-6 4 3.5L20.5 6"/><path d="M15 6h5.5v5.5"/></svg>`,
  globe: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="9"/><path d="M3 12h18"/><path d="M12 3c2.8 2.6 4.2 5.7 4.2 9s-1.4 6.4-4.2 9c-2.8-2.6-4.2-5.7-4.2-9s1.4-6.4 4.2-9z"/></svg>`,
  handshake: `<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7" stroke-linecap="round" stroke-linejoin="round"><path d="M2.5 12l4-3.5 3 2 3-2.5 3 1 3.5-2.5 2.5 3-3 3-2-1.5-3 2.5-3-2-2.5 2-3-1.5z"/><path d="M9.5 10.5l3.5 3"/><path d="M13 8.5l3.5 3.3"/></svg>`
};

/* ---------- DATA ---------- */
const TABS = [
  { id:'summary', label:'Executive Summary', color:'blue', icon:'summary' },
  { id:'statement', label:'Statement of Problem', color:'green', icon:'statement' },
  { id:'causes', label:'Causes of Problem', color:'amber', icon:'causes' },
  { id:'criteria', label:'Criteria & Alternatives', color:'violet', icon:'criteria' },
  { id:'recommend', label:'Recommended Solution', color:'coral', icon:'recommend' },
  { id:'implementation', label:'Implementation', color:'teal', icon:'implementation' },
  { id:'justification', label:'Justification', color:'pink', icon:'justification' },
  { id:'sources', label:'External Sources', color:'slate', icon:'sources' },
];

/* ---------- BUILD NAV ---------- */
const tabsEl = document.getElementById('tabs');
TABS.forEach((t,i)=>{
  const a = document.createElement('a');
  a.className='tab';
  a.id = 'tabbtn-'+t.id;
  a.href = '#'+t.id;
  a.dataset.tab = t.id;
  if(i===0) a.classList.add('active');
  a.style.setProperty('--c', `var(--${t.color})`);
  a.innerHTML = ICONS[t.icon] + `<span>${t.label}</span>`;
  tabsEl.appendChild(a);
});

function setActiveNav(id){
  TABS.forEach(t=>{
    document.getElementById('tabbtn-'+t.id).classList.toggle('active', t.id===id);
  });
  const link = document.getElementById('tabbtn-'+id);
  if(link) link.scrollIntoView({inline:'center', block:'nearest', behavior:'smooth'});
}

/* ---------- PANEL CONTENT ---------- */
const content = document.getElementById('content');

content.innerHTML = `

<section id="summary" class="panel" data-color="blue">
  <div class="panel-head">
    <div class="panel-head__index">01</div>
    <div class="panel-head__icon">${ICONS.summary}</div>
    <div><h2>Executive Summary</h2><p>The investment opportunity at a glance</p></div>
  </div>
  <div class="card">
    <p class="card__lede">TEQ Technologies presents a high-risk, high-growth investment opportunity. Its innovative business model, strong customer retention, and growing market demand offer substantial upside potential — but successful investment depends on accurate valuation, effective execution, and the company's ability to achieve sustainable profitability.</p>
    <div class="timeline">
      <div class="tl-step"><div class="tl-step__icon">${ICONS.rocket}</div><h4>Launch</h4><p>Company Incorporated</p></div>
      <div class="tl-step"><div class="tl-step__icon">${ICONS.growth}</div><h4>Growth</h4><p>Rapid Revenue Generation</p></div>
      <div class="tl-step"><div class="tl-step__icon">${ICONS.globe}</div><h4>Market</h4><p>Building Product &amp; Customer Base</p></div>
      <div class="tl-step"><div class="tl-step__icon">${ICONS.handshake}</div><h4>Funding</h4><p>INR 30 Million Investment</p></div>
    </div>
  </div>
</section>

<section id="statement" class="panel" data-color="green">
  <div class="panel-head">
    <div class="panel-head__index">02</div>
    <div class="panel-head__icon">${ICONS.statement}</div>
    <div><h2>Statement of the Problem</h2><p>What exactly Girish has to resolve</p></div>
  </div>
  <div class="card">
    <div class="subgrid">
      <div class="sub">
        <h3>The Core Investment Dilemma</h3>
        <ul><li>Girish Chhabria must decide whether to invest INR 30 Million into TEQ Technologies for an equity stake.</li></ul>
      </div>
      <div class="sub">
        <h3>Inadequacy of Traditional Metrics</h3>
        <ul>
          <li>TEQ Technologies has only twelve months of operational history.</li>
          <li>Currently generating a 2% operating loss.</li>
        </ul>
      </div>
      <div class="sub">
        <h3>Valuation Methodology Discrepancies</h3>
        <ul>
          <li>Girish's team faces the challenge of reconciling two distinct valuation outcomes.</li>
          <li>The top-down Venture Capitalist Approach applies an industry-average EV/Sales multiple to projected Year T+3 revenues.</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="causes" class="panel" data-color="amber">
  <div class="panel-head">
    <div class="panel-head__index">03</div>
    <div class="panel-head__icon">${ICONS.causes}</div>
    <div><h2>Cause of the Problem</h2><p>Why the decision is genuinely difficult</p></div>
  </div>
  <div class="card">
    <div class="cause-list">
      <div class="cause">
        <div class="cause__num">01</div>
        <div class="cause__body">
          <h3>Financial Constraints &amp; Valuation Uncertainty</h3>
          <ul>
            <li>TEQ Technologies needs a huge amount of capital to grow.</li>
            <li>TEQ has limited financial history, making valuation and future performance assessment more challenging.</li>
          </ul>
        </div>
      </div>
      <div class="cause">
        <div class="cause__num">02</div>
        <div class="cause__body">
          <h3>High Market Risks</h3>
          <ul><li>TEQ Technologies operates in a highly competitive and uncertain market.</li></ul>
        </div>
      </div>
      <div class="cause">
        <div class="cause__num">03</div>
        <div class="cause__body">
          <h3>Scalability &amp; Sustainable Growth Challenges</h3>
          <ul><li>The main concern is whether the business can scale while maintaining profitability and customer satisfaction.</li></ul>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="criteria" class="panel" data-color="violet">
  <div class="panel-head">
    <div class="panel-head__index">04</div>
    <div class="panel-head__icon">${ICONS.criteria}</div>
    <div><h2>Decision Criteria &amp; Alternative Solutions</h2><p>Weighing the paths available to Girish</p></div>
  </div>
  <div class="card">
    <p class="card__lede">Girish should consider investing in TEQ Technologies, but only after agreeing on a fair valuation and equity stake. TEQ's strengths — particularly its recurring revenue model, customer lock-in, scalable business model, and capable founder — appear to outweigh its weaknesses. However, the investment should reflect the substantial risks arising from startup uncertainty, competition, financing needs, and the possibility of failure.</p>

    <div class="opts">
      <div class="opt">
        <p class="opt__tag">Option 1</p>
        <h3>Invest Immediately</h3>
        <p class="pc-label pro">Pros</p>
        <ul class="pro"><li>Capture growth opportunity early</li><li>First-mover investor advantage</li><li>Potentially higher returns</li></ul>
        <p class="pc-label con">Cons</p>
        <ul class="con"><li>Higher financial risk</li><li>Limited operational track record</li><li>Exposure to start-up failure</li></ul>
      </div>
      <div class="opt">
        <p class="opt__tag">Option 2</p>
        <h3>Reject Investment</h3>
        <p class="pc-label pro">Pros</p>
        <ul class="pro"><li>Avoid potential financial losses</li><li>Preserve capital for other opportunities</li></ul>
        <p class="pc-label con">Cons</p>
        <ul class="con"><li>Miss future returns</li><li>Lose opportunity for high returns</li><li>Competitors may benefit instead</li></ul>
      </div>
      <div class="opt">
        <p class="opt__tag">Option 3</p>
        <h3>Invest with Conditions</h3>
        <p class="pc-label pro">Pros</p>
        <ul class="pro"><li>Better risk management</li><li>Performance monitoring</li><li>Milestone-based funding</li></ul>
        <p class="pc-label con">Cons</p>
        <ul class="con"><li>More negotiation required</li><li>Additional monitoring costs</li></ul>
      </div>
    </div>

    <div class="swot">
      <div class="swot-box strengths">
        <h3>Strengths</h3>
        <ul>
          <li>Strong founder (Ajay) with technical + sales expertise</li>
          <li>High customer retention (99–100%)</li>
          <li>Integrated ecosystem (ERP + CRM + Cloud bundling)</li>
          <li>Strong revenue growth (₹300M)</li>
        </ul>
      </div>
      <div class="swot-box weaknesses">
        <h3>Weaknesses</h3>
        <ul>
          <li>Current net loss (2%)</li>
          <li>High expansion expenditure</li>
          <li>Limited operating history</li>
          <li>Cash burn due to scaling</li>
          <li>Still building market presence</li>
          <li>Unstable financial performance</li>
        </ul>
      </div>
      <div class="swot-box opportunities">
        <h3>Opportunities</h3>
        <ul>
          <li>Booming Indian IT sector (cloud + ERP + CRM growth)</li>
          <li>SME digital transformation wave</li>
          <li>High demand for cloud-based services</li>
          <li>Upselling &amp; bundling potential</li>
        </ul>
      </div>
      <div class="swot-box threats">
        <h3>Threats</h3>
        <ul>
          <li>Intense competition from established SaaS providers</li>
          <li>Rapid technological shifts could erode current advantages</li>
          <li>Customer data security and compliance risks</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="recommend" class="panel" data-color="coral">
  <div class="panel-head">
    <div class="panel-head__index">05</div>
    <div class="panel-head__icon">${ICONS.recommend}</div>
    <div><h2>Recommended Solution</h2><p>The call Girish should make</p></div>
  </div>
  <div class="card">
    <p class="reco-statement">Girish Chhabria should <strong>invest INR 30 million</strong> in TEQ Technologies — after negotiating a fair valuation and equity stake.</p>
    <div class="chips">
      <span class="chip">Recurring revenue model</span>
      <span class="chip">Customer lock-in</span>
      <span class="chip">Scalable business model</span>
      <span class="chip">Capable founder — Ajay</span>
    </div>
  </div>
</section>

<section id="implementation" class="panel" data-color="teal">
  <div class="panel-head">
    <div class="panel-head__index">06</div>
    <div class="panel-head__icon">${ICONS.implementation}</div>
    <div><h2>Implementation</h2><p>How the investment should be carried out</p></div>
  </div>
  <div class="card">
    <div class="steps">
      <div class="step"><div class="step__n">1</div><p>Girish should first determine a fair valuation and negotiate an appropriate equity stake before investing the INR 30 million.</p></div>
      <div class="step"><div class="step__n">2</div><p>He should leverage his industry experience and professional network to guide TEQ's growth and support future fundraising activities.</p></div>
      <div class="step"><div class="step__n">3</div><p>This will enable TEQ to strengthen its competitive position and achieve sustainable profitability.</p></div>
    </div>
  </div>
</section>

<section id="justification" class="panel" data-color="pink">
  <div class="panel-head">
    <div class="panel-head__index">07</div>
    <div class="panel-head__icon">${ICONS.justification}</div>
    <div><h2>Justification</h2><p>Why the upside outweighs the risk</p></div>
  </div>
  <div class="card">
    <div class="stats">
      <div class="stat"><div class="stat__num">₹300M</div><div class="stat__label">Revenue in first year</div></div>
      <div class="stat"><div class="stat__num">99%</div><div class="stat__label">Product attachment rate</div></div>
      <div class="stat"><div class="stat__num">100%</div><div class="stat__label">Customer retention</div></div>
    </div>
    <ul class="justify-list">
      <li>TEQ generated INR 300 million in revenue within its first year and achieved a 99% product attachment rate and 100% customer retention.</li>
      <li>This demonstrates strong customer loyalty and stable recurring revenues.</li>
      <li>The rapid growth of India's IT industry and Ajay's proven leadership capabilities enhance the company's long-term prospects.</li>
      <li>The potential rewards outweigh the risks associated with the company's limited operating history and current losses.</li>
    </ul>
  </div>
</section>

<section id="sources" class="panel" data-color="slate">
  <div class="panel-head">
    <div class="panel-head__index">08</div>
    <div class="panel-head__icon">${ICONS.sources}</div>
    <div><h2>External Sources</h2><p>References supporting this analysis</p></div>
  </div>
  <div class="card">
    <div class="source-note">The original poster didn't list a formal reference list — add your case citation, course materials, and any data sources below so the site matches what you'll submit.</div>
    <div class="source-list">
      <div class="source-item"><span class="source-item__n">01</span><p class="ph">Primary case study — e.g. author, title, publisher, year</p></div>
      <div class="source-item"><span class="source-item__n">02</span><p class="ph">Course materials — e.g. course code, instructor, institution</p></div>
      <div class="source-item"><span class="source-item__n">03</span><p class="ph">Supporting industry data — e.g. Indian IT/SaaS market reports</p></div>
      <div class="source-item"><span class="source-item__n">04</span><p class="ph">Valuation methodology references — e.g. VC Method, EV/Sales multiples</p></div>
    </div>
  </div>
</section>

`;

/* ---------- SCROLLSPY + REVEAL ON SCROLL ---------- */
const panels = Array.from(document.querySelectorAll('.panel'));

const revealObserver = new IntersectionObserver((entries)=>{
  entries.forEach(entry=>{
    if(entry.isIntersecting){
      entry.target.classList.add('in-view');
      revealObserver.unobserve(entry.target);
    }
  });
}, { threshold: 0.12 });
panels.forEach(p => revealObserver.observe(p));

const spyObserver = new IntersectionObserver((entries)=>{
  entries.forEach(entry=>{
    if(entry.isIntersecting) setActiveNav(entry.target.id);
  });
}, { rootMargin: '-35% 0px -55% 0px', threshold: 0 });
panels.forEach(p => spyObserver.observe(p));
</script>
</body>
</html>
