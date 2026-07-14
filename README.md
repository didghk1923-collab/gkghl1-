<!DOCTYPE html>
<html lang="ko"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>연금 제안서 · 하나로H종신보험 (<span data-f="monthly">30만원</span>)</title>
<style>
  body{ -webkit-font-smoothing:antialiased; }
  *{ font-weight:600; font-family:'LIFEPLUS Bold','LIFEPLUSBold','LIFEPLUSBOLD','LIFEPLUS','Hanwha(LIFEPLUS)','HanwhaLIFEPLUS','Hanwha LIFEPLUS','Hanwhalife','Hanwha','한화생명','한화 라이프플러스','한화라이프플러스','Pretendard',-apple-system,'Malgun Gothic',sans-serif !important; margin:0; padding:0; box-sizing:border-box; word-break:keep-all; -webkit-print-color-adjust:exact; print-color-adjust:exact; }
  :root{
    --navy:#2E3033; --navy2:#54585C; --ink:#111111; --muted:#3A3E42;
    --gold:#E56A0F; --gold2:#F79A3E; --gold-line:#F5B87A;
    --orange:#F37321; --orange-deep:#D2540A;
    --paper:#FFFFFF; --line:#C9CCCF;
    --t-navy:#F2F3F4; --t-gold:#FEF1E4; --t-orange:#FDE7D4;
  }
  body{ background:#E4E5E6; color:var(--ink); }
  .page{ position:relative; width:210mm; height:297mm; background:var(--paper); margin:0 auto 16px; padding:16mm 17mm 14mm; overflow:hidden; display:flex; flex-direction:column; }
  @media print{ body{ background:#fff; } .page{ margin:0; box-shadow:none; page-break-after:always; } @page{ size:A4; margin:0; } }
  @media screen{ .page{ box-shadow:0 8px 30px rgba(14,37,64,.16); } }
  .frame{ position:absolute; inset:7mm; border:2.5px solid var(--gold-line); border-radius:20px; pointer-events:none; }
  

  /* editable fields */
  b, strong, .fill, .hi, .hiN, .pct, .core .r .rv, .age .pn, .cost .fbig, .wing .wbig, .card .num, .tile .num, .chl .c .v, .spec .v{ font-weight:800; }
  .head, h1, .cover .pname, .core .ch, .wing .wh, .era .col .eh, .cost .box .ch, .feat .ft2, .bi .bt{ font-weight:800; }
  .fill{ color:var(--orange-deep); border-bottom:1.5px dashed var(--gold-line); padding:0 4px; }

  /* ===== COVER ===== */
  .cvtop{ display:flex; justify-content:space-between; align-items:flex-start; }
  .cvtop .co{ font-size:12.5px; letter-spacing:.03em; color:var(--muted); padding-top:4px; }
  .cvtop .co b{ color:var(--navy); }
  .cvbadges{ display:flex; gap:6px; }
  .bdg{ border:2px solid var(--navy); background:#FFFFFF; border-radius:29px; padding:0 6px; text-align:center; width:100px; height:56px; display:flex; flex-direction:column; align-items:center; justify-content:center; }
  .bdg .t{ font-size:13px; color:var(--gold); line-height:1.2; }
  .bdg .s{ font-size:12.5px; color:var(--navy); margin-top:3px; line-height:1.2; }
  
  

  .cover{ flex:1; display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; }
  .cover h1{ font-size:62px; line-height:1.18; color:var(--navy); letter-spacing:-.025em; margin:0; }
  .cover h1 .o{ color:var(--orange); } .cover h1 .g{ color:var(--gold); }
  .cover .hr{ width:70px; height:2px; background:var(--gold2); margin:26px auto 24px; }
  .cover .pname{ font-size:64px; line-height:1.15; color:var(--navy); letter-spacing:-.03em; }
  .cover .pmeta{ font-size:23px; color:var(--muted); margin-top:12px; }
  .cover .tag{ display:inline-block; margin-top:22px; background:var(--t-orange); color:var(--orange-deep); font-size:17px; padding:10px 24px; border-radius:24px; }
  .cover .cfor{ font-size:27px; color:var(--navy); margin-top:30px; line-height:1.6; }
  .cover .cfor .fill{ font-size:34px; padding:0 10px; }
  .cover .by{ margin-top:30px; padding-top:0; font-size:15px; color:var(--muted); display:flex; gap:26px; justify-content:center; }
  .cover .by .srow{ display:flex; align-items:baseline; gap:8px; }
  .cover .by .sfill{ display:inline-block; width:100px; height:17px; border-bottom:1.5px dashed var(--gold-line); }
  .cover .by .lab{ color:var(--gold); font-size:13px; letter-spacing:.06em; margin-right:9px; }

  /* cover highlights */
  .chl{ width:100%; display:grid; grid-template-columns:1fr 1fr 1fr; gap:0; margin-top:30px; border-top:1px solid var(--gold-line); border-bottom:1px solid var(--gold-line); }
  .chl .c{ padding:26px 14px; text-align:center; border-right:1px solid var(--gold-line); }
  .chl .c:last-child{ border-right:none; }
  .chl .c .k{ font-size:16px; letter-spacing:.03em; color:var(--gold); margin-bottom:12px; }
  .chl .c .v{ font-size:38px; line-height:1.12; color:var(--navy); }
  .chl .c .v .u{ font-size:18px; color:var(--muted); }
  .chl .c.hot .v{ color:var(--orange); }
  .chl .c .d{ font-size:15.5px; color:var(--muted); margin-top:12px; line-height:1.5; }
  .cnote{ margin-top:22px; font-size:16.5px; line-height:1.7; color:var(--muted); }
  .cnote b{ color:var(--orange-deep); }

  /* ==== 강조 앵커: 네이비 블록 ==== */
  .anchor{ border:3px solid var(--gold2); background:linear-gradient(135deg,#F37321,#E56A0F 55%,#D2540A); border-radius:16px; padding:30px 34px; margin-top:26px; color:#fff; text-align:center; }
  .anchor .pn{ font-size:60px; line-height:1.12; letter-spacing:-.03em; }
  .anchor .pm{ font-size:21px; color:#FFF3E8; margin-top:10px; }
  .anchor .pt{ display:inline-block; margin-top:16px; background:#FFFFFF; color:var(--orange-deep); font-size:17px; padding:9px 22px; border-radius:22px; }

  /* 섹션 넘버 마커 */
  .snum{ display:flex; align-items:center; gap:12px; margin-bottom:10px; }
  .snum .n{ width:38px; height:38px; border-radius:16px; background:var(--navy); color:#fff; font-size:18px; display:flex; align-items:center; justify-content:center; flex:0 0 auto; }
  .snum .t{ font-size:15px; color:var(--gold); letter-spacing:.04em; }

  /* 핵심 숫자 하이라이트 (형광펜) */
  .hi{ background:linear-gradient(transparent 55%, #FFD9B5 55%); padding:0 2px; color:var(--orange-deep); }
  .hiN{ background:linear-gradient(transparent 55%, #F0E2D6 55%); padding:0 2px; color:var(--navy); }

  /* 양날개 (안아파도/아파도) */
  .wings{ display:grid; grid-template-columns:1fr 1fr; gap:14px; margin-top:20px; }
  .wing{ border:2px solid var(--line); border-radius:16px; padding:18px 20px; }
  .wing.calm{ background:var(--t-navy); border:2px solid var(--navy); }
  .wing.boom{ background:var(--t-orange); border:2px solid var(--orange); }
  .wing .wt{ font-size:16px; letter-spacing:.04em; margin-bottom:9px; }
  .wing.calm .wt{ color:var(--navy2); } .wing.boom .wt{ color:var(--orange-deep); }
  .wing .wh{ font-size:26px; line-height:1.32; margin-bottom:16px; }
  .wing.calm .wh{ color:var(--navy); } .wing.boom .wh{ color:var(--orange-deep); }
  .wing .wl{ font-size:16.5px; line-height:2.0; color:var(--muted); }
  .wing .wl b{ color:var(--navy); }
  .wing.boom .wl b{ color:var(--orange-deep); }
  .wing .wbig{ font-size:36px; line-height:1.1; margin-top:18px; }
  .wing.calm .wbig{ color:var(--navy); } .wing.boom .wbig{ color:var(--orange); }
  .wing .wsub{ font-size:14.5px; color:var(--muted); margin-top:8px; }

  /* <span data-f="monthly">30만원</span>의 가치 */
  .cost{ display:grid; grid-template-columns:1fr 38px 1fr; align-items:stretch; margin-top:20px; }
  .cost .box{ border:2px solid var(--line); border-radius:16px; padding:16px 18px; }
  .cost .box.now{ background:#EAE8E2; border:2px solid #93A3B0; }
  .cost .box.fut{ background:var(--t-orange); border:2px solid var(--orange); }
  .cost .box .ct{ font-size:13px; letter-spacing:.03em; margin-bottom:7px; }
  .cost .box.now .ct{ color:#333A42; } .cost .box.fut .ct{ color:var(--orange-deep); }
  .cost .box .ch{ font-size:19px; line-height:1.3; margin-bottom:11px; }
  .cost .box.now .ch{ color:#1F2937; } .cost .box.fut .ch{ color:var(--orange-deep); }
  .cost .cr{ display:flex; justify-content:space-between; gap:8px; font-size:13px; padding:5px 0; border-bottom:1px dashed #9E9A90; }
  .cost .cr:last-child{ border-bottom:none; }
  .cost .cn{ color:#1F2937; } .cost .cv{ color:#333A42; text-align:right; }
  .cost .mid{ display:flex; align-items:center; justify-content:center; font-size:22px; color:var(--gold2); }
  .cost .fbig{ font-size:38px; color:var(--orange); line-height:1.1; margin-top:10px; }
  .cost .fsub{ font-size:13.5px; color:var(--muted); margin-top:11px; line-height:1.55; }

  /* 덤 개념 */
  .bonus{ margin-top:15px; border:2px solid var(--gold-line); background:var(--t-gold); border-radius:16px; padding:15px 24px; }
  .bonus .bl{ font-size:14px; letter-spacing:.05em; color:var(--gold); margin-bottom:9px; }
  .bonus p{ font-size:19px; line-height:1.75; color:#4A3C0A; margin:0; }
  .bonus p b{ color:var(--orange-deep); }

  /* 옛날 vs 요즘 종신 */
  .era{ display:grid; grid-template-columns:1fr 44px 1fr; align-items:stretch; gap:0; margin-top:14px; }
  .era .col{ border:2px solid var(--line); border-radius:16px; padding:12px 17px; }
  .era .col.old{ background:#EAE8E2; border:2px solid #93A3B0; }
  .era .col.new{ background:var(--t-orange); border:2px solid var(--orange); }
  .era .col .et{ font-size:14px; letter-spacing:.04em; margin-bottom:8px; }
  .era .col.old .et{ color:#333A42; } .era .col.new .et{ color:var(--orange-deep); }
  .era .col .eh{ font-size:22px; line-height:1.3; margin-bottom:11px; }
  .era .col.old .eh{ color:#1F2937; } .era .col.new .eh{ color:var(--orange-deep); }
  .era .col .el{ font-size:14.5px; line-height:1.7; }
  .era .col.old .el{ color:#333A42; } .era .col.new .el{ color:var(--navy); }
  .era .col.new .el b{ color:var(--orange-deep); }
  .era .mid{ display:flex; align-items:center; justify-content:center; font-size:24px; color:var(--gold2); }

  .b5-title{ margin-top:13px; margin-bottom:8px; font-size:17.5px; color:var(--navy); padding-left:2px; }
  .b5-title b{ color:var(--orange-deep); }

  /* 5 benefits */
  .b5{ display:flex; flex-direction:column; gap:9px; margin-top:0; }
  .bi{ display:grid; grid-template-columns:40px 1fr; gap:14px; align-items:center; border:2px solid var(--navy); border-radius:16px; background:#fff; padding:10px 18px; }
  .bi .no{ width:34px; height:34px; border-radius:50%; background:var(--navy); color:#fff; font-size:17px; display:flex; align-items:center; justify-content:center; }
  .bi .bt{ font-size:17.5px; color:var(--navy); line-height:1.3; margin-bottom:4px; }
  .bi .bd{ font-size:14px; line-height:1.5; color:#2C3742; }
  .bi .bd b{ color:var(--orange-deep); }

  /* ===== CONTENT ===== */
  .wrap{ flex:1; display:flex; flex-direction:column; justify-content:center; padding:4px 0; }
  .kick{ font-size:15px; color:var(--gold); margin-bottom:12px; } .kick:before{ content:'— '; color:var(--gold2); }
  .head{ font-size:41px; line-height:1.24; color:var(--navy); letter-spacing:-.015em; margin:0 0 8px; }
  .head .o{ color:var(--orange); } .head .g{ color:var(--gold); }
  .hr2{ width:56px; height:4px; border-radius:2px; background:var(--orange); margin:0 0 22px; }
  .lede{ font-size:22px; line-height:1.9; color:var(--ink); } .lede b{ color:var(--orange-deep); } .lede .big{ font-size:29px; color:var(--orange); } .lede .navy{ color:var(--navy); }
  .strong{ font-size:25px; line-height:1.55; color:var(--navy); margin:0 0 18px; } .strong b{ color:var(--orange-deep); }
  .ft{ display:flex; justify-content:space-between; align-items:center; font-size:11px; letter-spacing:.04em; color:var(--muted); border-top:1px solid var(--line); padding-top:8px; margin-top:auto; }
  .ft em{ color:var(--gold2); font-style:normal; }

  .tiles{ display:grid; grid-template-columns:1fr 1fr 1fr; gap:0; margin-top:22px; border:2px solid var(--line); border-radius:14px; overflow:hidden; }
  .tile{ padding:20px 18px; border-right:1px solid var(--line); position:relative; background:#fff; }
  .tile:last-child{ border-right:none; }
  .tile:before{ content:''; position:absolute; left:0; top:0; width:100%; height:3px; }
  .tile.a:before{ background:var(--navy); } .tile.b:before{ background:var(--orange); } .tile.c:before{ background:var(--gold2); }
  .tile.a{ background:var(--t-navy); } .tile.b{ background:var(--t-orange); } .tile.c{ background:var(--t-gold); }
  .tile .ci{ font-size:12.5px; color:var(--gold); }
  .tile .lab{ font-size:14px; color:var(--muted); margin:5px 0 10px; }
  .tile .num{ font-size:39px; line-height:1; } .tile .num .u{ font-size:17px; color:var(--muted); }
  .tile.a .num{ color:var(--navy); } .tile.b .num{ color:var(--orange); } .tile.c .num{ color:var(--navy); font-size:26px; }
  .tile .sm{ font-size:13.5px; line-height:1.5; color:var(--muted); margin-top:10px; }
  .band{ margin-top:22px; background:var(--t-gold); border:2px solid var(--gold-line); padding:18px 24px; font-size:22px; line-height:1.6; color:#4A3C0A; }
  .band b{ color:var(--orange-deep); }

  .flow{ margin-top:24px; border:2px solid var(--line); background:var(--t-navy); border-radius:14px; padding:26px 26px 22px; }
  .flow .grid{ display:grid; grid-template-columns:1fr 34px 1fr 34px 1fr; align-items:center; }
  .flow .st{ text-align:center; } .flow .st .k{ font-size:14px; color:var(--gold); margin-bottom:12px; }
  .flow .st .v{ font-size:33px; line-height:1.05; color:var(--navy); } .flow .st .v .u{ font-size:15px; color:var(--muted); }
  .flow .ar{ text-align:center; font-size:26px; color:var(--gold2); }
  .flow .k2{ text-align:center; font-size:23px; line-height:1.6; margin-top:22px; padding-top:20px; border-top:1px solid var(--gold-line); color:var(--navy); } .flow .k2 b{ color:var(--orange-deep); }

  table{ width:100%; border-collapse:collapse; margin-top:4px; border-radius:16px; overflow:hidden; }
  thead th{ text-align:center; font-size:15px; color:#fff; background:var(--navy); font-weight:normal; padding:14px 12px; border-bottom:none; }
  thead th:first-child{ text-align:left; padding-left:20px; } thead th.win{ background:var(--orange); color:#fff; }
  tbody td{ padding:14px 12px; text-align:center; font-size:19px; border-bottom:1.5px solid #D5DFE7; }
  tbody td.rk{ text-align:left; padding-left:20px; color:var(--navy); }
  tbody tr:nth-child(even){ background:#F6F4ED; }
  tbody tr.hot td{ background:var(--t-orange); color:var(--orange-deep); font-size:21px; box-shadow:inset 3px 0 0 var(--orange); }
  tbody tr.base td{ color:var(--muted); }
  .pct{ font-size:24px; color:var(--orange); } tr.hot .pct{ font-size:31px; } tr.base .pct{ color:var(--muted); }
  .vs td.k{ text-align:left; padding-left:20px; color:var(--navy); font-size:15px; }
  .vs td.lose{ color:#5A6570; }
  .vs td.win{ background:var(--t-orange); color:#A8430A; box-shadow:inset 3px 0 0 var(--orange); }

  .note{ margin-top:13px; border:2px solid var(--navy2); background:var(--t-navy); border-radius:14px; padding:15px 22px; }
  .note .lab{ font-size:13.5px; letter-spacing:.05em; color:var(--gold); margin-bottom:11px; }
  .note p{ font-size:16.2px; line-height:1.66; color:var(--ink); margin:0; } .note p .o{ color:var(--orange-deep); } .note p .n{ color:var(--navy); }

  .ages{ display:grid; grid-template-columns:1fr 1fr 1fr; gap:18px; margin-top:26px; }
  .age{ border:2.5px solid var(--gold-line); background:var(--t-navy); border-radius:26px; padding:54px 18px; text-align:center; }
  .age.hot{ border-top-color:var(--orange); background:var(--t-orange); }
  .age .ag{ font-size:21px; color:var(--gold); margin-bottom:18px; } .age.hot .ag{ color:var(--orange-deep); }
  .age .pn{ font-size:76px; line-height:1.1; color:var(--navy); } .age.hot .pn{ color:var(--orange); }
  .age .de{ font-size:20px; color:var(--muted); margin-top:20px; line-height:1.6; }

  .stat{ border:2px solid var(--orange); background:var(--t-orange); border-radius:14px; padding:13px 24px; display:flex; align-items:center; justify-content:space-between; margin:12px 0 10px; }
  .stat .t{ font-size:15px; color:var(--navy); line-height:1.45; }
  .stat .n{ font-size:38px; color:var(--orange); line-height:1; white-space:nowrap; } .stat .n .u{ font-size:17px; color:var(--muted); }

  /* closing script */
  .script{ flex:1; background:var(--t-navy); border:2px solid var(--navy2); border-radius:14px; padding:16px 28px 16px 34px; position:relative; display:flex; align-items:center; }
  .script .qm{ position:absolute; left:16px; top:12px; font-size:50px; color:var(--gold-line); line-height:1; }
  .script p{ font-size:15.4px; line-height:1.62; color:var(--ink); margin:0; }
  .script p .o{ color:var(--orange-deep); } .script p .n{ color:var(--navy); } .script p .big{ font-size:20px; color:var(--orange); }

  /* spec sheet */
  .spec{ border:2px solid var(--line); border-radius:14px; overflow:hidden; margin-bottom:15px; }
  .spec .row{ display:grid; grid-template-columns:170px 1fr; border-bottom:1px solid var(--line); }
  .spec .row:last-child{ border-bottom:none; }
  .spec .k{ background:var(--t-navy); color:var(--navy); font-size:15px; padding:6px 16px; display:flex; align-items:center; }
  .spec-note-line{ font-size:12.5px; color:var(--muted); margin:-8px 0 12px 2px; font-weight:600; }
  .spec .v{ padding:6px 16px; font-size:18px; color:var(--ink); display:flex; align-items:center; }
  .spec .v.hl{ color:var(--orange-deep); }
  .spec .v .u{ font-size:15px; color:var(--muted); margin-left:6px; }

  .hl-y{ color:#FFD84D !important; }
  /* 3색 강조 체계 */
  .r{ color:#C42B1C !important; }                                        /* 빨강 = 위험·손실 */
  .bl{ color:#1B5FA8 !important; }                                       /* 파랑 = 확정·보증 */
  .yl{ color:#FFD84D !important; }                                       /* 노랑 = 진한배경 위 핵심 */
  .hi-r{ background:linear-gradient(transparent 55%, #FFC9C2 55%); padding:0 3px; color:#A81F12; }   /* 빨강 형광 */
  .hi-b{ background:linear-gradient(transparent 55%, #BFDCF5 55%); padding:0 3px; color:#134C87; }   /* 파랑 형광 */

  /* 핵심 배너 */
  .core{ border:3px solid var(--gold2); background:linear-gradient(135deg,#F37321,#E56A0F 55%,#D2540A); border-radius:16px; padding:17px 26px; margin-bottom:11px; display:grid; grid-template-columns:1fr auto; gap:22px; align-items:center; }
  .core .l{ color:#fff; }
  .core .cl{ font-size:14px; letter-spacing:.06em; color:#FFE3C7; margin-bottom:10px; }
  .core .ch{ font-size:27px; line-height:1.35; }
  .core .ch b{ color:#FFFFFF; }
  .core .cd{ font-size:15px; line-height:1.6; color:#FFF3E8; margin-top:10px; }
  .core .r{ text-align:center; border-left:1px solid rgba(255,255,255,.2); padding-left:22px; }
  .core .r .rk{ font-size:14px; color:#FFE3C7; margin-bottom:8px; }
  .core .r .rv{ font-size:44px; color:#fff; line-height:1; white-space:nowrap; }
  .core .r .rv .u{ font-size:16px; color:#FFF3E8; }
  .core .r .rs{ font-size:13.5px; color:#FFF3E8; margin-top:9px; }

  /* feature 3 */
  .feats{ display:grid; grid-template-columns:1fr 1fr 1fr; gap:12px; margin-bottom:15px; }
  .feat{ border:2px solid var(--gold-line); border-radius:14px; background:#fff; padding:12px 14px; }
  .feat .fn{ font-size:13px; letter-spacing:.06em; color:var(--gold); margin-bottom:10px; }
  .feat .ft2{ font-size:19px; color:var(--navy); line-height:1.35; margin-bottom:8px; }
  .feat .fd{ font-size:12.9px; line-height:1.48; color:var(--muted); }
  .feat.hot{ border-top-color:var(--orange); background:var(--t-orange); }
  .feat.hot .fn{ color:var(--orange-deep); } .feat.hot .fd{ color:#8a4a25; }

  /* trust bar */
  .trust{ border:2px solid var(--gold-line); background:var(--t-gold); border-radius:14px; padding:14px 22px; display:flex; align-items:center; gap:16px; }
  .trust .ic{ width:40px; height:40px; border-radius:50%; border:1.5px solid var(--gold2); color:var(--gold); font-size:16px; display:flex; align-items:center; justify-content:center; flex:0 0 auto; }
  .trust .tx{ font-size:18px; line-height:1.6; color:#4A3C0A; } .trust .tx b{ color:var(--orange-deep); }

  .hanja{ font-family:'Malgun Gothic','맑은 고딕','Apple SD Gothic Neo','Noto Sans KR','Nanum Gothic',sans-serif !important; }

  /* 납입면제 기준 */
  .crit{ margin:11px 0 8px; border:2px solid var(--gold-line); background:var(--t-gold); border-radius:14px; padding:11px 18px; display:flex; align-items:center; gap:14px; }
  .crit .ci{ width:34px; height:34px; border-radius:50%; border:1.5px solid var(--gold2); color:var(--gold); font-size:15px; display:flex; align-items:center; justify-content:center; flex:0 0 auto; }
  .crit .ct{ font-size:15px; line-height:1.4; color:#4A3C0A; white-space:nowrap; }
  .crit .ct b{ color:var(--orange-deep); }
  .crit .ct .sm{ display:block; font-size:14px; color:var(--muted); margin-top:3px; }

  /* 3줄 요약 */
  .sum3{ margin-top:11px; border:2px solid var(--gold-line); background:var(--t-gold); border-radius:14px; padding:13px 22px; }
  .sum3 .sl{ font-size:13px; letter-spacing:.05em; color:var(--gold); margin-bottom:9px; }
  .sum3 .r{ display:grid; grid-template-columns:24px 1fr; gap:9px; align-items:baseline; font-size:16.2px; line-height:1.5; color:var(--navy); padding:2px 0; }
  .sum3 .r .no{ color:var(--orange); }
  .sum3 .r b{ color:var(--orange-deep); }

  /* sign-off */
  .sign{ margin-top:10px; margin-bottom:3px; border-top:1px solid var(--gold-line); padding-top:10px; display:flex; justify-content:space-between; align-items:flex-end; }
  .sign .msg{ font-size:15px; color:var(--muted); line-height:1.6; }
  .sign .who{ text-align:right; font-size:14.5px; color:var(--muted); line-height:1.9; }
  .sign .srow{ display:flex; align-items:baseline; justify-content:flex-end; gap:8px; }
  .sign .sfill{ display:inline-block; width:120px; height:17px; border-bottom:1.5px dashed var(--gold-line); }
  .sval{ color:var(--navy); white-space:nowrap; }
  .sign .who .lab{ color:var(--gold); font-size:13px; letter-spacing:.06em; margin-right:8px; }

  /* ==== 입력 패널 (인쇄 시 숨김) ==== */
  #fillPanel{ width:210mm; margin:16px auto; background:#fff; border:3px solid var(--orange); border-radius:16px; padding:20px 24px; font-family:inherit; }
  #fillPanel .fp-title{ font-size:17px; color:var(--orange-deep); margin-bottom:14px; }
  #fillPanel .fp-sub{ font-size:13px; color:var(--muted); }
  #fillPanel .fp-grid{ display:grid; grid-template-columns:1fr 1fr 1fr; gap:11px; }
  #fillPanel label{ display:flex; flex-direction:column; gap:5px; font-size:13px; color:var(--navy); }
  #fillPanel input{ padding:9px 11px; border:2px solid var(--line); border-radius:9px; font-size:15px; font-family:inherit; font-weight:700; color:var(--ink); }
  #fillPanel input:focus{ outline:none; border-color:var(--orange); }
  #fillPanel .fp-btns{ display:flex; gap:10px; margin-top:15px; }
  #fillPanel button{ flex:1; padding:12px; border:none; border-radius:10px; background:var(--orange); color:#fff; font-size:16px; font-family:inherit; font-weight:800; cursor:pointer; }
  #fillPanel button:last-child{ background:var(--navy); }
  @media print{ #fillPanel{ display:none !important; } }
</style></head><body>

<div id="fillPanel">
  <div class="fp-title">✎ 여기에 입력하면 제안서가 자동으로 완성됩니다 <span class="fp-sub">(인쇄하면 이 입력창은 나오지 않습니다)</span></div>
  <div class="fp-grid">
    <label>고객 성함<input id="i_cust" placeholder="예: 홍길동"></label>
    <label>담당 FP<input id="i_fp" placeholder="예: 심현우 FP"></label>
    <label>연락처<input id="i_phone" placeholder="예: 010-0000-0000"></label>
    <label>월납보험료 (만원)<input id="i_monthly" type="number" value="30"></label>
    <label>연금확정액 (만원)<input id="i_pension" type="number" placeholder="예: 8403"></label>
    <label>10년 환급률 (%)<input id="i_rpct" placeholder="예: 106.6"></label>
    <label>10년 환급금 (만원)<input id="i_ramt" type="number" placeholder="예: 3839"></label>
    <label>사망보장 최저 (만원)<input id="i_dlo" type="number" placeholder="예: 2315"></label>
    <label>사망보장 최고 (만원)<input id="i_dhi" type="number" placeholder="예: 8403"></label>
  </div>
  <div class="fp-btns">
    <button onclick="applyAll()">적용하기</button>
    <button onclick="window.print()">인쇄 / PDF 저장</button>
  </div>
</div>


<!-- COVER -->
<div class="page">
  <div class="frame"></div>
  <div class="cvtop">
    <div class="co">한화생명금융서비스 <b>하회지점</b></div>
    <div class="cvbadges">
      <div class="bdg"><div class="t">10년 시점</div><div class="s"><span id="badgeRefund">99.3</span>% 확정환급</div></div>
      <div class="bdg hot"><div class="t">비과세 &amp; 건보료</div><div class="s">ZERO</div></div>
      <div class="bdg"><div class="t">예금자보호</div><div class="s">1억원</div></div>
      <div class="bdg hot"><div class="t">7만명 이상</div><div class="s">선택한 상품</div></div>
      <div class="bdg hot"><div class="t">100억 이상</div><div class="s">판매된 상품</div></div>
    </div>
  </div>

  <div class="cover">
    <h1 style="font-size:52px; line-height:1.28;"><span class="o">살아서</span> 받고, <span class="o">아파서</span> 멈추고<br><span class="g">떠나서</span> 남기는 보험</h1>
    <div class="anchor">
      <div class="pn">하나로H종신보험</div>
      <div class="pm">월 <span data-f="monthly">30만원</span> · 15년납</div>
      <div class="pt">나를 위한, 가족을 위한 최고의 선물입니다</div>
    </div>

    <div class="cfor"><span class="fill" data-f="cust">　고객명　</span> 님께<br>준비했습니다</div>

    <div class="chl">
      <div class="c">
        <div class="k">확정 연금</div>
        <div class="v"><span data-f="pensionNum">9,646</span><span class="u" data-u="pension"> 만원</span></div>
        <div class="d">가입하는 순간<br>확정됩니다</div>
      </div>
      <div class="c hot">
        <div class="k">10년 시점</div>
        <div class="v" style="font-size:26px;">목돈 활용</div>
        <div class="d">필요할 때<br>꺼내 쓰실 수 있어요</div>
      </div>
      <div class="c">
        <div class="k">스마트전환</div>
        <div class="v" style="font-size:27px;">전액 인출해도<br>사망보장 유지</div>
        <div class="d">그 보장자산을<br>자녀에게 물려주실 수도 있습니다</div>
      </div>
    </div>

    <div class="by">
      <div class="srow"><span class="lab">담당 FP</span><span class="sval" data-f="fp">　　　　　</span></div>
      <div class="srow"><span class="lab">연락처</span><span class="sval" data-f="phone">　　　　　　</span></div>
      <div class="srow"><span class="lab">소속</span><span class="sval">한화생명금융서비스 하회지점</span></div>
    </div>
  </div>
</div>

<!-- 1 -->


<div class="page">
  <div class="frame"></div>
  <div class="wrap">
    <div class="snum"><div class="n">01</div><div class="t">제안 상품 요약</div></div>
    <div class="head">고객님께 제안드리는 <span class="o">설계 내용</span></div><div class="hr2"></div>

    <div class="spec">
      <div class="row"><div class="k">상품이름</div><div class="v">하나로H종신보험</div></div>
      <div class="row"><div class="k">월납보험료</div><div class="v"><span data-f="monthly">30만원</span><span class="u">/ 월</span></div></div>
      <div class="row"><div class="k">납입기간</div><div class="v">15년납<span class="u">· 총 <span data-f="wanap">5,400만원</span></span></div></div>
      <div class="row"><div class="k">10년 시점 환급률</div><div class="v hl"><span id="refundCell">99.3<span class="u">％ · 3,600만원</span></span></div></div>
      <div class="row"><div class="k">사망보장자산</div><div class="v hl"><span id="deathCell">2,315만원 ~ 8,403만원</span></div></div>
      <div class="row"><div class="k">연금확정액</div><div class="v hl"><span data-f="pension">9,646만원</span><span class="u">· 가입 시 확정</span></div></div>
    </div>
    <div id="specNote" class="spec-note-line">※ 15년납이지만 10년 시점에 100% 이상의 환급률이 보장됩니다.</div>

    <div class="core">
      <div class="l">
        <div class="cl">이 상품의 핵심</div>
        <div class="ch">납입면제를 받으셔도<br><b class="hl-y">확정된 연금은 언제든 그대로</b> 받으십니다</div>
        <div class="cd">암·뇌졸중·심장질환 진단을 받으시면 보험료 납입은 그날로 끝. 그런데 연금 <span data-f="pension">9,646만원</span>은 <b style="color:#fff">한 푼도 줄지 않고</b> 예정대로 나옵니다.</div>
      </div>
      <div class="r">
        <div class="rk">1년차 진단 시</div>
        <div class="rv yl"><span data-f="pct1Num">2,679</span><span class="u">%</span></div>
        <div class="rs"><span data-f="y1">360만원</span> 내고<br><span data-f="pension">9,646만원</span> 수령</div>
      </div>
    </div>

    <div class="feats">
      <div class="feat hot">
        <div class="fn">특징 01</div>
        <div class="ft2">12대 질병 진단 시<br>즉시 납입면제</div>
        <div class="fd">보험료는 그날로 끝나요. 그런데 연금 <span data-f="pension">9,646만원</span>은 그대로. 일찍 진단받으실수록 납부하신 보험료 대비 받으시는 금액이 훨씬 커져요.</div>
      </div>
      <div class="feat">
        <div class="fn">특징 02</div>
        <div class="ft2">10년 시점부터<br>환급률이 크게 올라갑니다</div>
        <div class="fd">15년납이지만 10년만 지키시면 목돈으로 활용하실 수 있습니다.</div>
      </div>
      <div class="feat">
        <div class="fn">특징 03</div>
        <div class="ft2">스마트전환<br>전액 인출해도 사망보장</div>
        <div class="fd">10년 시점부터 낸 보험료를 전액 인출하셔도, 사망보장은 가입 보장자산 이상으로 남아요.</div>
      </div>
    </div>

    <div class="trust">
      <div class="ic">✓</div>
      <div class="tx">보장 · 연금 · 절세를 <b>한 번에 준비</b>하실 수 있어<br><b>가장 많은 고객님이 선택하고 계신 보험상품</b>입니다.</div>
    </div>
  </div>
</div>

<!-- 6 CLOSING -->


<div class="page">
  <div class="frame"></div>
  <div class="wrap">
    <div class="snum"><div class="n">02</div><div class="t">예전 종신과 무엇이 다른가</div></div>
    <div class="head">예전 종신보험과 <span class="o">완전히 다릅니다</span></div><div class="hr2"></div>

    <div class="era">
      <div class="col old">
        <div class="et">예전 종신보험</div>
        <div class="eh">죽어야 나오는 보험</div>
        <div class="el">
          · 사망보장만 덩그러니<br>
          · 길게, 오래 내야 하고<br>
          · 중간에 해지하면 손해<br>
          · <b>살아생전 받는 게 없음</b>
        </div>
      </div>
      <div class="mid">→</div>
      <div class="col new">
        <div class="et">지금의 하나로H종신</div>
        <div class="eh">살아서 다 받는 보험</div>
        <div class="el">
          · 10년 시점 <b>환급률 대폭 상승</b><br>
          · <b>확정 연금</b>으로 노후까지<br>
          · <b>비과세 · 건보료 ZERO</b><br>
          · 사망보장은 <b>그대로 유지</b><br>
          · 암·뇌·심 진단 시 <b>보험료는 거기서 끝</b>
        </div>
      </div>
    </div>

    <div class="b5-title">그래서 <b>하나로H종신</b>은, 이런 것들을 드립니다</div>
    <div class="b5">
      <div class="bi">
        <div class="no">1</div>
        <div>
          <div class="bt">15년납인데, 10년 시점부터 목돈 활용 가능</div>
          <div class="bd">10년만 채우시면 <b>목돈</b>으로 꺼내 쓰실 수 있습니다.</div>
        </div>
      </div>
      <div class="bi">
        <div class="no">2</div>
        <div>
          <div class="bt">스마트전환 — 낸 돈 전액 빼도, 사망보장은 그대로</div>
          <div class="bd"><b>낸 보험료를 전액 인출</b>하셔도 사망보장은 <b>그대로 남습니다.</b></div>
        </div>
      </div>
      <div class="bi">
        <div class="no">3</div>
        <div>
          <div class="bt">연금액은 가입하는 순간 확정</div>
          <div class="bd">시장이 어떻든 <b>받으실 연금 <span data-f="pension">9,646만원</span>은 고정</b>입니다.</div>
        </div>
      </div>
      <div class="bi">
        <div class="no">4</div>
        <div>
          <div class="bt">비과세 &amp; 건강보험료 ZERO</div>
          <div class="bd">연금을 받으셔도 <b>세금도 건강보험료도 늘지 않습니다.</b></div>
        </div>
      </div>
      <div class="bi">
        <div class="no">5</div>
        <div>
          <div class="bt">연금 준비하는 동안 사망보장까지</div>
          <div class="bd">가입기간 내내 <b>가족을 지키는 사망보장</b>이 함께 따라갑니다.</div>
        </div>
      </div>
      <div class="bi">
        <div class="no">6</div>
        <div>
          <div class="bt">연금 받다 사망해도, 남은 연금 전액 지급</div>
          <div class="bd">보통은 적립금만 나오지만, <b>남은 연금 전부를 유족께</b> 드립니다.</div>
        </div>
      </div>
    </div>

    <div class="band" style="margin-top:11px; font-size:17px; padding:11px 20px;">여기까지가 <b>아프지 않으셔도 받으시는 것</b>예요. 그런데 만약 아프시게 되면? 다음 장에서 이어서 말씀드릴게요.</div>
  </div>
</div>

<!-- 2 -->


<div class="page">
  <div class="frame"></div>
  <div class="wrap">
    <div class="snum"><div class="n">03</div><div class="t">아프시면 · 체증 구조</div></div>
    <div class="head">낸 돈, <span class="o">이렇게 불어납니다</span></div><div class="hr2"></div>
    <div class="strong">건강하든 아프시든 <b>연금액은 확정</b>되어 있습니다.<br>또한 조기에 아프시다면 <b>더욱 더 큰 힘</b>이 되어드립니다.</div>

    <div class="crit">
      <div class="ci">✓</div>
      <div class="ct">
        <b>"아프시면"</b> 기준 — <b>암 · 뇌졸중 · 특정허혈심장질환 포함 12대 질병 진단 시</b>, 그날부터 납입 면제
      </div>
    </div>
    <table>
      <thead><tr><th>납입면제 시점</th><th>납부하신 보험료</th><th>받으시는 연금</th><th>납부액 대비</th></tr></thead>
      <tbody id="growTable">
          <tr class="hot"><td class="rk">1년차 면제</td><td><span data-f="y1">360만원</span></td><td><span data-f="pension">9,646만원</span></td><td class="pct"><span data-f="pct1">2,679%</span></td></tr>
          <tr><td class="rk">2년차 면제</td><td><span data-f="p2">720만원</span></td><td><span data-f="pension">9,646만원</span></td><td class="pct">1,340%</td></tr>
          <tr><td class="rk">3년차 면제</td><td><span data-f="p3">1,080만원</span></td><td><span data-f="pension">9,646만원</span></td><td class="pct">893%</td></tr>
          <tr><td class="rk">5년차 면제</td><td><span data-f="p5">1,800만원</span></td><td><span data-f="pension">9,646만원</span></td><td class="pct">536%</td></tr>
          <tr><td class="rk">10년차 면제</td><td><span data-f="p10">3,600만원</span></td><td><span data-f="pension">9,646만원</span></td><td class="pct">268%</td></tr>
          <tr class="base"><td class="rk">15년 완납</td><td><span data-f="wanap">5,400만원</span></td><td><span data-f="pension">9,646만원</span></td><td class="pct">179%</td></tr>
          </tbody>
    </table>
    <div class="flow">
      <div class="grid">
        <div class="st"><div class="k">1년 납입 시</div><div class="v"><span data-f="y1Num">360</span><span class="u" data-u="y1"> 만원</span></div></div>
        <div class="ar">→</div>
        <div class="st"><div class="k">암·뇌·심 진단 시</div><div class="v">납입 끝</div></div>
        <div class="ar">→</div>
        <div class="st"><div class="k">연금 개시 시</div><div class="v" style="color:var(--gold)"><span data-f="pensionNum">9,646</span><span class="u" data-u="pension"> 만원</span></div></div>
      </div>
      <div class="k2">가장 어려운 순간, <b>최고의 동반자가 되어드립니다.</b></div>
    </div>
  </div>
</div>

<!-- 3 -->


<div class="page">
  <div class="frame"></div>
  <div class="wrap">
    <div class="snum"><div class="n">04</div><div class="t">남의 일이 아닙니다</div></div>
    <div class="head">이런 혜택, <span class="o">나는 아닐 거라고요?</span></div><div class="hr2"></div>
    <div class="lede">대한민국 3대 질병은 <b>암 · 뇌졸중 · 심장질환</b>입니다.<br>나이가 들수록 이 3가지는 <b>급격히 늘어납니다.</b></div>
    <div class="ages">
      <div class="age"><div class="ag">30대 가입</div><div class="pn">6명 <span class="hanja" style="color:var(--gold);">中</span><br>1명</div><div class="de">암·뇌·심<br>진단받습니다</div></div>
      <div class="age"><div class="ag">40대 가입</div><div class="pn">4명 <span class="hanja" style="color:var(--gold);">中</span><br>1명</div><div class="de">암·뇌·심<br>진단받습니다</div></div>
      <div class="age hot"><div class="ag">50대 가입</div><div class="pn">3명 <span class="hanja" style="color:var(--gold);">中</span><br>1명</div><div class="de">암·뇌·심<br>진단받습니다</div></div>
    </div>
    <div class="note">
      <div class="lab">고객님께 드리는 말씀</div>
      <p>대한민국 사람 <span class="n">2명 <span class="hanja">中</span> 1명</span>이 평생 한 번은 암에 걸립니다. 여기에 뇌졸중과 심장질환까지 더하면, 살면서 이 <span class="o">3대 질병을 피해 가시는 분이 오히려 드물어요.</span> 30대에 가입하셔도 6명 <span class="hanja">中</span> 한 분, 50대면 3명 <span class="hanja">中</span> 한 분이 납입기간 안에 진단을 받으세요. 그 순간 이 보험이 <span class="o">보험료를 멈춰주고, 낸 돈을 최대 <span data-f="pct1">2,679%</span>로 불려</span> 연금으로 돌려드려요. 그러니 <span class="n">건강하고 젊은 지금</span>이, 이 혜택을 제일 크게 누리실 수 있는 때예요.</p>
    </div>
  </div>
</div>

<!-- 4 -->


<div class="page">
  <div class="frame"></div>
  <div class="wrap vs">
    <div class="snum"><div class="n">05</div><div class="t">이 돈, 어떻게 쓰시겠어요?</div></div>
    <div class="head">같은 <span data-f="monthly">30만원</span>, <span class="o">목돈도 되고 연금도 됩니다</span></div><div class="hr2"></div>
    <div class="cost">
      <div class="box now">
        <div class="ct">한 달 <span data-f="monthly">30만원</span>, 어디서 나오나</div>
        <div class="ch" id="costHead">외식 한 번 줄이고, 카페 두 번 아끼면<br>충분히 만들 수 있는 돈</div>
        <div id="costRows"></div>
      </div>
      <div class="mid">→</div>
      <div class="box fut">
        <div class="ct">그 돈을 여기에 두시면</div>
        <div class="ch">목돈으로도, 연금으로도<br>쓰실 수 있어요</div>
        <div class="cr"><div class="cn">10년 시점</div><div class="cv" style="color:var(--orange-deep);"><b>목돈</b>으로 인출 가능</div></div>
        <div class="cr"><div class="cn">연금 개시</div><div class="cv" style="color:var(--orange-deep);"><b><span data-f="pension">9,646만원</span></b> 확정 수령</div></div>
        <div class="cr"><div class="cn">아프시면</div><div class="cv" style="color:var(--orange-deep);"><b>보험료 끝</b>, 연금은 그대로</div></div>
        <div class="fsub" style="margin-top:12px;">10년만 지나도 낸 돈 이상이 보증되니,<br><b style="color:var(--orange-deep);">필요할 때 목돈으로 꺼내 쓰실 수 있어요.</b></div>
      </div>
    </div>

    <table>
      <thead><tr><th>매달 <span data-f="monthly">30만원</span> · 15년</th><th>그냥 쓰면</th><th class="win">하나로H종신</th></tr></thead>
      <tbody>
        <tr><td class="k">쓴 돈</td><td class="lose"><span data-f="wanap">5,400만원</span></td><td class="win"><span data-f="wanap">5,400만원</span></td></tr>
        <tr><td class="k">10년 뒤 목돈</td><td class="lose">0원</td><td class="win">목돈으로 인출 가능</td></tr>
        <tr><td class="k">15년 뒤 남는 것</td><td class="lose">0원 · 소비로 사라짐</td><td class="win"><span data-f="pension">9,646만원</span> 확정</td></tr>
        <tr><td class="k">아프면</td><td class="lose">치료비까지 부담</td><td class="win">보험료 면제 · 연금 그대로</td></tr>
        <tr><td class="k">먼저 떠나면</td><td class="lose">남는 것 없음</td><td class="win">가족에게 목돈 승계</td></tr>
      </tbody>
    </table>

    <div class="note">
      <div class="lab">고객님께 드리는 말씀</div>
      <p>한 달 <span data-f="monthly">30만원</span>, 사실 쓰다 보면 어디로 갔는지도 모르게 사라지는 돈이잖아요. 그런데 그 돈을 여기에 두시면 <span class="o">10년만 지나도 낸 돈 이상이 보증</span>돼요. 자녀 결혼이든 뭐든 <span class="hi">목돈 필요하실 때 꺼내 쓰실 수 있고</span>, 그냥 두시면 <span class="o"><span data-f="pension">9,646만원</span> 연금</span>이 됩니다. 혹시 그 사이에 큰 병이 오면 <span class="o">보험료는 그날로 끝인데 연금은 그대로</span> 나오고요. <span class="n">쓰고 없어질 돈을, 어떤 미래가 와도 나를 지켜줄 자산으로 바꾸시는 거예요.</span></p>
    </div>
  </div>
</div>

<!-- 5 PRODUCT SUMMARY -->


<div class="page">
  <div class="frame"></div>
  <div class="wrap">
    <div class="snum"><div class="n">06</div><div class="t">이 보험이 특별한 이유</div></div>
    <div class="head" style="font-size:36px; line-height:1.34;">납부하신 <span class="o">소중한 보험료</span>는<br>고객님이 가장 어려운 순간에<br><span class="o">선물로 돌아옵니다.</span></div><div class="hr2"></div>

    <div class="wings" style="margin-top:24px;">
      <div class="wing calm">
        <div class="wt">건강하게 지내셔도</div>
        <div class="wh">이미 좋은 보험</div>
        <div class="wl">
          · 연금 <b><span data-f="pension">9,646만원</span> 확정</b><br>
          · 10년 시점 <b>환급률 대폭 상승</b><br>
          · 연금소득 <b>비과세 · 건보료 ZERO</b><br>
          · 가입기간 내내 <b>사망보장</b><br>
          · 연금 받다 사망해도 <b>잔여 연금 일시지급</b>
        </div>
        <div class="wbig"><span data-f="pensionNum">9,646</span><span style="font-size:17px;" data-u="pension"> 만원</span></div>
        <div class="wsub">완납하셔도 낸 돈보다 훨씬 많이 받으세요</div>
      </div>
      <div class="wing boom">
        <div class="wt">혹시 아프시면</div>
        <div class="wh">보험료는 끝, 연금은 그대로</div>
        <div class="wl">
          · 암·뇌졸중·심장질환 진단 시<br>&nbsp;&nbsp;<b>그날부터 보험료 0원</b><br>
          · 그런데 연금은 <b><span data-f="pension">9,646만원</span> 그대로</b><br>
          · 일찍 진단받으실수록<br>&nbsp;&nbsp;<b>납부하신 보험료 대비<br>&nbsp;&nbsp;받는 금액이 훨씬 커집니다</b>
        </div>
        <div class="wbig"><span data-f="pct1Num">2,679</span><span style="font-size:17px;">%</span></div>
        <div class="wsub">1년차 진단 시 · <span data-f="y1">360만원</span> 내고 <span data-f="pension">9,646만원</span></div>
      </div>
    </div>

    <div class="bonus">
      <div class="bl">여기에 하나 더</div>
      <p>암·뇌졸중·심장질환 진단을 받으시면 <b>그날부터 보험료를 안 내셔도 돼요.</b> 그런데 연금은 그대로 나오니, 사실상 <b>3대 질병 보장을 덤으로 가져가시는 셈</b>입니다.</p>
    </div>

    <div class="band" style="margin-top:13px; font-size:22px; padding:13px 24px;">어느 쪽으로 가도 <b>고객님이 손해 보실 일이 없어요.</b></div>
  </div>
</div>

<!-- 1B: 안 아파도 좋은 이유 -->


<div class="page">
  <div class="frame"></div>
  <div class="wrap">
    <div class="snum"><div class="n">07</div><div class="t">마지막으로 드리고 싶은 이야기</div></div>
    <div class="head"><span class="fill" data-f="cust">고객명</span> 님, <span class="o">이 보험 하나면 됩니다</span></div><div class="hr2"></div>
    <div class="script">
      <div class="qm">“</div>
      <p>
        고객님, 종신보험 하면 <span class="n">"죽어야 나오는 보험"</span> 떠올리시죠. 예전엔 정말 그랬습니다. 사망보장만 덩그러니, 길게 오래 내야 하고, 중간에 깨면 손해였으니까요. 그런데 요즘 그렇게 만들면 <span class="o">고객님들이 안 하십니다.</span> 그래서 지금 종신보험은 <span class="hi">살아계실 때 받아 가시는 걸 극대화</span>해 놨습니다. 이 하나로H종신이 딱 그렇습니다.<br><br>

        먼저, 이 상품은 15년을 내는데 <span class="hi-b">10년 시점부터 환급률이 크게 올라갑니다.</span> 아직 5년이나 더 남았는데 목돈으로 활용하실 수 있다는 뜻이에요.<br><br>

        다만 <span class="r">10년은 채우셔야 합니다.</span> 그 전에 깨시면 낸 돈보다 적게 나오거든요. 그런데 저는 이게 오히려 <span class="o">장점</span>이라고 봅니다. 적금은 급하면 깨게 되잖아요. 이건 <span class="hi">10년만 지나면 확실한 목돈이 보장되니까, 중간에 못 깨게 잡아주는 장치</span>인 셈이에요. <span class="o">강제로 돈이 모이는 구조</span>입니다.<br><br>

        그리고 연금은 <span class="hi-b">가입하시는 순간 <span data-f="pension">9,646만원</span>으로 확정</span>됩니다. 시장이 어떻게 되든 흔들리지 않아요. 받으실 때 <span class="o">세금도 건강보험료도 한 푼 안 붙습니다.</span><br><br>

        여기에, 만약 살다가 암이나 뇌졸중, 심장질환을 만나시면 <span class="hi-r">그날부터 보험료를 안 내십니다.</span> 그런데 연금은 원래대로 다 나와요. 1년만 내고 진단받으셔도 <span class="n"><span data-f="y1">360만원</span></span> 내고 <span class="big"><span data-f="pension">9,646만원</span></span>을 받으시는 겁니다. 사실상 <span class="o">3대 질병 보장을 덤으로 가져가시는 것</span>과 같습니다.<br><br>

        게다가 10년 시점부터는 <span class="o">스마트전환</span>이 됩니다. 목돈 필요하실 때 <span class="hi-b">낸 보험료를 전액 빼 가셔도 사망보장은 그대로 남고</span>, 그 보장자산을 <span class="o">자녀에게 물려주실 수도</span> 있습니다.<br><br>

        마지막으로, 보통 연금보험은 연금 받으시다 돌아가시면 <span class="n">적립금만</span> 나오고 끝입니다. 그런데 이 상품은 <span class="o">남은 연금 전부를 유족께 일시금으로</span> 드립니다. 한 푼도 사라지지 않아요. 그래서 이 상품이 좋다고 말씀드리는 겁니다.
      </p>
    </div>

    <div class="sign">
      <div class="msg">고객님의 가장 어려운 순간에<br>함께하겠습니다.</div>
      <div class="who">
        <div class="srow"><span class="lab">담당 FP</span><span class="sval" data-f="fp">　　　　　</span></div>
        <div class="srow"><span class="lab">연락처</span><span class="sval" data-f="phone">　　　　　　</span></div>
        <div class="srow"><span class="lab">소속</span><span class="sval">한화생명금융서비스 하회지점</span></div>
      </div>
    </div>
  </div>
</div>


<script>
function kr(m){ m=Math.round(m); var e=Math.floor(m/10000), r=m%10000;
  if(e&&r) return e+"억 "+r.toLocaleString()+"만원";
  if(e) return e+"억원";
  return r.toLocaleString()+"만원"; }
/* 단위(만원)가 뒤에 따로 붙는 자리용 — 숫자만 반환 */
function krNum(m){ m=Math.round(m); var e=Math.floor(m/10000), r=m%10000;
  if(e&&r) return e+"억 "+r.toLocaleString();
  if(e) return e+"억";
  return r.toLocaleString(); }

/* 월납 구간별 생활비 비교 문구 */
function costCopy(m){
  if(m<=15) return {
    head:"커피 한 잔 값이면<br>충분히 만들 수 있는 돈",
    rows:[["커피·간식","하루 3~4천원이면 월 10만원"],
          ["배달비","주 1~2번만 줄여도 월 5만원"],
          ["안 쓰는 구독","정리하면 월 3~5만원"]]};
  if(m<=39) return {
    head:"외식 한 번 줄이고, 카페 두 번 아끼면<br>충분히 만들 수 있는 돈",
    rows:[["외식·배달","주 1~2회 줄이면 월 15만원"],
          ["카페·간식","하루 5천원이면 월 15만원"],
          ["안 쓰는 구독·통신","점검하면 월 3~5만원"]]};
  if(m<=69) return {
    head:"새는 지출만 정리해도<br>충분히 만들 수 있는 돈",
    rows:[["외식·모임","주 1~2회 줄이면 월 20만원"],
          ["쇼핑·구독","점검하면 월 15만원"],
          ["여유 자금","매달 15만원만 옮기면"]]};
  return {
    head:"쓰고 사라질 돈을<br>자산으로 옮기는 것뿐입니다",
    rows:[["여유 자금","매달 묶어두시는 돈"],
          ["예·적금","이자만 남고 보장은 없음"],
          ["이 보험","연금 + 보장 + 절세 한 번에"]]};
}
function setF(k,v){ document.querySelectorAll('[data-f="'+k+'"]').forEach(function(e){ e.textContent=v; }); }
/* 딱 떨어지는 억(1억, 2억…)이면 뒤 '만원' 단위를 '원'으로 */
function setU(k,m){ m=Math.round(m);
  var txt = (m>=10000 && m%10000===0) ? "원" : " 만원";
  document.querySelectorAll('[data-u="'+k+'"]').forEach(function(e){ e.textContent=txt; }); }

function applyAll(){
  var cust=document.getElementById('i_cust').value.trim();
  var fp=document.getElementById('i_fp').value.trim();
  var ph=document.getElementById('i_phone').value.trim();
  var m=+document.getElementById('i_monthly').value||30;
  var pen=+document.getElementById('i_pension').value||0;
  var rpct=document.getElementById('i_rpct').value.trim();
  var ramt=+document.getElementById('i_ramt').value||0;
  var dlo=+document.getElementById('i_dlo').value||0;
  var dhi=+document.getElementById('i_dhi').value||0;

  if(cust) setF('cust',cust);
  if(fp) setF('fp',fp);
  if(ph) setF('phone',ph);

  var wanap=m*180, y1=m*12;
  setF('monthly', m+"만원");
  setF('wanap', kr(wanap));
  setF('y1', kr(y1));
  setF('y1Num', krNum(y1));
  setU('y1', y1);
  // 월납 구간별 생활비 문구 자동 전환
  var cc=costCopy(m);
  document.getElementById('costHead').innerHTML=cc.head;
  document.getElementById('costRows').innerHTML=cc.rows.map(function(r){
    return '<div class="cr"><div class="cn">'+r[0]+'</div><div class="cv">'+r[1]+'</div></div>';}).join('');
  setF('p2', kr(m*24)); setF('p3', kr(m*36)); setF('p5', kr(m*60)); setF('p10', kr(m*120));
  var daily=Math.round(m*10000/30/100)*100;
  setF('daily', "하루 "+daily.toLocaleString()+"원");

  if(pen>0){
    setF('pension', kr(pen));
    setF('pensionNum', krNum(pen));
    setU('pension', pen);
    setF('pct1', Math.round(pen/y1*100).toLocaleString()+"%");
    setF('pct1Num', Math.round(pen/y1*100).toLocaleString());
    // 체증표 재생성
    var rows=[[12,'1년차'],[24,'2년차'],[36,'3년차'],[60,'5년차'],[120,'10년차'],[180,'15년 완납']];
    var html='';
    rows.forEach(function(r,i){
      var paid=m*r[0], p=Math.round(pen/paid*100);
      var cls = i===0 ? ' class="hot"' : (r[0]===180 ? ' class="base"' : '');
      var st  = r[0]===180 ? ' style="color:var(--muted)"' : '';
      var rk  = r[1] + (r[0]===180 ? '' : ' 면제');
      html += '<tr'+cls+'><td class="rk">'+rk+'</td><td>'+kr(paid)+'</td><td>'+kr(pen)+'</td><td class="pct"'+st+'>'+p.toLocaleString()+'%</td></tr>';
    });
    document.getElementById('growTable').innerHTML=html;
  }
  if(rpct){
    document.getElementById('badgeRefund').textContent=rpct;
    var amtTxt = ramt>0 ? ("％ · "+kr(ramt)) : "％";
    document.getElementById('refundCell').innerHTML = rpct+'<span class="u">'+amtTxt+'</span>';
    var sn=document.getElementById('specNote');
    if(parseFloat(rpct)>=100){ sn.style.display='block'; sn.textContent='※ 15년납이지만 10년 시점에 '+rpct+'%의 환급률이 보장됩니다.'; }
    else { sn.style.display='none'; }
  }
  if(dlo>0&&dhi>0) document.getElementById('deathCell').textContent = kr(dlo)+" ~ "+kr(dhi);
}
window.addEventListener('load', applyAll);
// 엔터로도 적용
document.addEventListener('keydown', function(e){ if(e.key==='Enter') applyAll(); });
</script>
</body></html>
