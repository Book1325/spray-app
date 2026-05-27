<!DOCTYPE html>
<html lang="th" data-theme="dark">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#10B981">
<meta name="mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="default">
<title>🌿 จดคิวพ่นยา</title>
<style>
/* ══════════════════════════════════════════════════════════
   THEME TOKENS — 4 themes (ห้ามเปลี่ยน structure เดิม)
   ══════════════════════════════════════════════════════════ */
:root, [data-theme="dark"] {
  --bg:#0B0F14;--bg2:#111827;--bg3:#0F172A;--bg4:#1F2937;
  --border:#1F2937;--text:#E5E7EB;--text2:#9CA3AF;--text3:#6B7280;
  --accent:#10B981;--accent2:#22C55E;--accent-d:#0d2e23;
  --red:#EF4444;--red-d:#2d1414;--yellow:#F59E0B;--yellow-d:#2d2006;
  --blue:#3B82F6;--blue-d:#12214a;--teal:#2DD4BF;--teal-d:#0d2e2a;
  --purple:#A78BFA;--shadow:0 8px 32px rgba(0,0,0,.55);--shadow-s:0 2px 10px rgba(0,0,0,.40);
  --r:14px;--r-s:9px;
  --font:"Noto Sans Thai","Sarabun",-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
  --transition-fast:.14s;
  --transition-med:.22s;
}

[data-theme="beige"] {
  --bg:#FAF7F2;--bg2:#FFFFFF;--bg3:#F5EFE6;--bg4:#ECE3D5;--border:#DED2BF;
  --text:#1F2937;--text2:#6B7280;--text3:#9CA3AF;--accent:#B45309;--accent2:#15803D;--accent-d:#fdf0e3;
  --red:#DC2626;--red-d:#fde8e8;--yellow:#D97706;--yellow-d:#fef3c7;
  --blue:#2563EB;--blue-d:#eff6ff;--teal:#0D9488;--teal-d:#f0fdfa;--purple:#7C3AED;
  --shadow:0 8px 32px rgba(0,0,0,.10);--shadow-s:0 2px 8px rgba(0,0,0,.06);
}
[data-theme="glass"] {
  --bg:#EEF7FF;--bg2:#FFFFFF;--bg3:#F8FCFF;--bg4:#E0F2FE;--border:#BAE6FD;
  --text:#0F172A;--text2:#475569;--text3:#94A3B8;--accent:#0284C7;--accent2:#0EA5E9;--accent-d:#e0f2fe;
  --red:#E11D48;--red-d:#fee2e2;--yellow:#D97706;--yellow-d:#fef3c7;
  --blue:#2563EB;--blue-d:#eff6ff;--teal:#0891B2;--teal-d:#ecfeff;--purple:#7C3AED;
  --shadow:0 8px 32px rgba(14,165,233,.15);--shadow-s:0 2px 10px rgba(14,165,233,.10);
}
[data-theme="gray"] {
  --bg:#F5F7FA;--bg2:#FFFFFF;--bg3:#F9FAFB;--bg4:#E5E7EB;--border:#E5E7EB;
  --text:#111827;--text2:#6B7280;--text3:#9CA3AF;--accent:#2563EB;--accent2:#16A34A;--accent-d:#eff6ff;
  --red:#DC2626;--red-d:#fef2f2;--yellow:#D97706;--yellow-d:#fffbeb;
  --blue:#2563EB;--blue-d:#eff6ff;--teal:#0891B2;--teal-d:#ecfeff;--purple:#7C3AED;
  --shadow:0 8px 32px rgba(0,0,0,.08);--shadow-s:0 2px 8px rgba(0,0,0,.05);
}

/* ══════════════════════════════════════════════════════════
   RESET & BASE
   ══════════════════════════════════════════════════════════ */
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{font-size:15px;-webkit-text-size-adjust:100%}
body{
  font-family:var(--font);background:var(--bg);color:var(--text);
  min-height:100vh;line-height:1.6;transition:background .3s,color .3s;
  -webkit-tap-highlight-color:transparent;
  touch-action:manipulation;
  overflow-x:hidden;
}
button{font-family:var(--font);cursor:pointer;-webkit-tap-highlight-color:transparent;touch-action:manipulation}
/* FIX: font-size >= 16px บน mobile ป้องกัน Safari zoom */
input,textarea,select{
  font-family:var(--font);
  font-size:16px; /* Safari จะไม่ zoom ถ้า >= 16px */
}
@media(min-width:600px){
  input,textarea,select{font-size:.85rem}
}

/* ══════════════════════════════════════════════════════════
   HEADER
   ══════════════════════════════════════════════════════════ */
.hdr{position:sticky;top:0;z-index:90;background:var(--bg2);border-bottom:1px solid var(--border);padding:0 16px}
.hdr-in{max-width:1100px;margin:0 auto;display:flex;align-items:center;gap:10px;height:52px}
.logo{font-size:1.05rem;font-weight:600;color:var(--accent);display:flex;align-items:center;gap:7px;white-space:nowrap}
.hdr-r{margin-left:auto;display:flex;align-items:center;gap:6px}

/* connection badge */
.conn{display:inline-flex;align-items:center;gap:5px;padding:4px 10px;border-radius:20px;font-size:.72rem;font-weight:500;border:1px solid var(--border);background:var(--bg3);color:var(--text3);white-space:nowrap;transition:all .25s}
.conn .dot{width:6px;height:6px;border-radius:50%;background:var(--text3);flex-shrink:0}
.conn.online{color:var(--accent);border-color:var(--accent-d)}.conn.online .dot{background:var(--accent)}
.conn.offline{color:var(--red);border-color:var(--red-d)}.conn.offline .dot{background:var(--red)}
.conn.connecting{color:var(--yellow);border-color:var(--yellow-d)}.conn.connecting .dot{background:var(--yellow);animation:pulse 1.2s infinite}
@keyframes pulse{0%,100%{opacity:1;transform:scale(1)}50%{opacity:.4;transform:scale(.75)}}

/* theme picker */
.theme-wrap{position:relative}
.theme-btn{display:inline-flex;align-items:center;gap:6px;height:34px;padding:0 11px;border-radius:var(--r-s);border:1px solid var(--border);background:var(--bg3);color:var(--text2);font-size:.78rem;font-weight:500;cursor:pointer;transition:all .18s;white-space:nowrap}
.theme-btn:hover{background:var(--bg4);color:var(--text);border-color:var(--accent)}
.t-dot{width:9px;height:9px;border-radius:50%;flex-shrink:0;transition:background .25s}
.t-caret{font-size:.58rem;opacity:.55;margin-left:1px}
.theme-dd{position:absolute;right:0;top:calc(100% + 7px);background:var(--bg2);border:1px solid var(--border);border-radius:var(--r);padding:6px;min-width:160px;box-shadow:var(--shadow);display:none;z-index:300;animation:ddIn .15s ease}
.theme-dd.open{display:block}
@keyframes ddIn{from{opacity:0;transform:translateY(-5px)}to{opacity:1;transform:none}}
.t-opt{display:flex;align-items:center;gap:10px;width:100%;text-align:left;padding:8px 12px;border-radius:8px;border:none;background:none;color:var(--text2);font-size:.82rem;cursor:pointer;transition:all .14s}
.t-opt:hover{background:var(--bg3);color:var(--text)}
.t-opt.active{color:var(--accent);background:var(--accent-d);font-weight:500}
.t-swatch{width:13px;height:13px;border-radius:4px;flex-shrink:0;border:1px solid rgba(0,0,0,.08)}
.ico-btn{width:34px;height:34px;border:1px solid var(--border);background:var(--bg3);color:var(--text2);border-radius:var(--r-s);display:flex;align-items:center;justify-content:center;font-size:.95rem;transition:all .2s}
.ico-btn:hover{background:var(--bg4);color:var(--text)}

/* ══════════════════════════════════════════════════════════
   MONTH NAV BAR (ใหม่ — calendar-first)
   ══════════════════════════════════════════════════════════ */
.month-nav{
  background:var(--bg2);border-bottom:1px solid var(--border);
  padding:10px 16px;display:flex;align-items:center;justify-content:space-between;
  gap:10px;position:sticky;top:52px;z-index:80;
}
.month-nav-in{max-width:1100px;margin:0 auto;width:100%;display:flex;align-items:center;justify-content:space-between;gap:10px}
.month-display{font-size:1rem;font-weight:600;color:var(--text);min-width:140px;text-align:center;cursor:pointer;transition:color .15s}
.month-display:hover{color:var(--accent)}
.month-nav-btns{display:flex;align-items:center;gap:5px}
.nav-btn{
  height:32px;min-width:32px;border:1px solid var(--border);background:var(--bg3);
  color:var(--text2);border-radius:8px;display:flex;align-items:center;justify-content:center;
  font-size:.82rem;transition:all .15s;padding:0 10px;white-space:nowrap;
}
.nav-btn:hover{background:var(--bg4);color:var(--accent);border-color:var(--accent)}
.nav-btn.today-btn{color:var(--accent);border-color:var(--accent-d);background:var(--accent-d)}
.nav-btn.today-btn:hover{background:var(--accent);color:var(--bg2)}

/* VIEW SWITCHER */
.view-switcher{display:flex;background:var(--bg3);border:1px solid var(--border);border-radius:8px;padding:3px;gap:2px}
.view-tab{height:26px;padding:0 10px;border-radius:6px;border:none;background:none;color:var(--text3);font-size:.75rem;font-weight:500;cursor:pointer;transition:all .15s;white-space:nowrap}
.view-tab.active{background:var(--bg2);color:var(--accent);box-shadow:var(--shadow-s)}

/* ══════════════════════════════════════════════════════════
   STICKY MINI SUMMARY BAR (ใหม่)
   ══════════════════════════════════════════════════════════ */
.mini-bar{
  background:var(--bg3);border-bottom:1px solid var(--border);
  padding:8px 16px;display:flex;align-items:center;gap:16px;
  overflow-x:auto;-webkit-overflow-scrolling:touch;scrollbar-width:none;
}
.mini-bar::-webkit-scrollbar{display:none}
.mini-bar-in{max-width:1100px;margin:0 auto;width:100%;display:flex;align-items:center;gap:12px;flex-wrap:nowrap;min-width:max-content}
.mini-stat{display:flex;align-items:center;gap:5px;white-space:nowrap;font-size:.75rem}
.mini-stat .ms-label{color:var(--text3)}
.mini-stat .ms-val{font-weight:600}
.mini-stat .ms-val.g{color:var(--accent)}
.mini-stat .ms-val.r{color:var(--red)}
.mini-stat .ms-val.y{color:var(--yellow)}
.mini-stat .ms-val.t{color:var(--teal)}

/* ══════════════════════════════════════════════════════════
   MONTH PICKER MODAL (ใหม่)
   ══════════════════════════════════════════════════════════ */
.month-picker-overlay{position:fixed;inset:0;background:rgba(0,0,0,.45);z-index:250;display:flex;align-items:center;justify-content:center;opacity:0;pointer-events:none;transition:opacity .2s}
.month-picker-overlay.show{opacity:1;pointer-events:all}
.month-picker{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r);padding:18px;width:300px;max-width:92vw;box-shadow:var(--shadow);transform:scale(.96);transition:transform .2s}
.month-picker-overlay.show .month-picker{transform:scale(1)}
.mp-header{display:flex;align-items:center;justify-content:space-between;margin-bottom:14px}
.mp-year{display:flex;align-items:center;gap:8px}
.mp-year-num{font-size:.95rem;font-weight:600;min-width:60px;text-align:center}
.mp-y-btn{width:28px;height:28px;border:1px solid var(--border);background:var(--bg3);border-radius:6px;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:.8rem;color:var(--text2);transition:all .14s}
.mp-y-btn:hover{background:var(--bg4);color:var(--accent)}
.mp-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:6px}
.mp-month-btn{padding:9px 4px;border:1px solid var(--border);background:var(--bg3);border-radius:8px;font-size:.78rem;cursor:pointer;color:var(--text2);transition:all .14s;text-align:center}
.mp-month-btn:hover{background:var(--bg4);color:var(--accent);border-color:var(--accent)}
.mp-month-btn.active{background:var(--accent-d);border-color:var(--accent);color:var(--accent);font-weight:600}
.mp-close{font-size:.8rem;color:var(--text3);background:none;border:none;cursor:pointer;padding:4px 8px;border-radius:6px}
.mp-close:hover{color:var(--red)}

/* ══════════════════════════════════════════════════════════
   FILTER CHIPS (ใหม่)
   ══════════════════════════════════════════════════════════ */
.filter-bar{
  padding:10px 16px;display:flex;gap:7px;overflow-x:auto;
  -webkit-overflow-scrolling:touch;scrollbar-width:none;
  background:var(--bg);
}
.filter-bar::-webkit-scrollbar{display:none}
.filter-bar-in{display:flex;gap:6px;min-width:max-content;align-items:center}
.chip{
  display:inline-flex;align-items:center;gap:4px;padding:5px 12px;border-radius:20px;
  border:1px solid var(--border);background:var(--bg2);color:var(--text2);
  font-size:.75rem;font-weight:500;cursor:pointer;transition:all .15s;white-space:nowrap;
  -webkit-tap-highlight-color:transparent;
}
.chip:hover,.chip.active{background:var(--accent-d);border-color:var(--accent);color:var(--accent)}
.chip.red.active{background:var(--red-d);border-color:var(--red);color:var(--red)}
.chip.blue.active{background:var(--blue-d);border-color:var(--blue);color:var(--blue)}
.chip.yellow.active{background:var(--yellow-d);border-color:var(--yellow);color:var(--yellow)}
.chip-clear{color:var(--text3);font-size:.72rem;padding:5px 8px;background:none;border:none;cursor:pointer;white-space:nowrap}
.chip-clear:hover{color:var(--red)}

/* ══════════════════════════════════════════════════════════
   MAIN WRAP
   ══════════════════════════════════════════════════════════ */
.wrap{max-width:1100px;margin:0 auto;padding:16px}
@media(max-width:600px){.wrap{padding:10px}}

/* ══════════════════════════════════════════════════════════
   STATS SECTION (เดิม — preserve)
   ══════════════════════════════════════════════════════════ */
.stats-section{margin-bottom:16px}
.stats-label{font-size:.72rem;font-weight:500;color:var(--text3);letter-spacing:.06em;text-transform:uppercase;margin-bottom:8px}
.stat-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px}
@media(max-width:900px){.stat-grid{grid-template-columns:repeat(2,1fr)}}
.stat-card{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r);padding:14px 16px;transition:transform .18s,box-shadow .18s}
.stat-card:hover{transform:translateY(-1px);box-shadow:var(--shadow-s)}
.sc-label{font-size:.71rem;color:var(--text3);margin-bottom:4px;font-weight:500}
.sc-val{font-size:1.25rem;font-weight:700;line-height:1.2}
.sc-val.g{color:var(--accent)}.sc-val.r{color:var(--red)}.sc-val.y{color:var(--yellow)}
.sc-val.t{color:var(--teal)}.sc-val.b{color:var(--blue)}.sc-val.p{color:var(--purple)}
.sc-sub{font-size:.7rem;color:var(--text3);margin-top:3px}

/* ══════════════════════════════════════════════════════════
   TOOLBAR
   ══════════════════════════════════════════════════════════ */
.toolbar{display:flex;flex-wrap:wrap;gap:7px;align-items:center;margin-bottom:14px}
.btn{display:inline-flex;align-items:center;gap:5px;padding:8px 14px;border-radius:var(--r-s);border:1px solid var(--border);background:var(--bg3);color:var(--text);font-size:.82rem;transition:all .18s;white-space:nowrap;-webkit-tap-highlight-color:transparent}
.btn:hover{background:var(--bg4);border-color:var(--accent);color:var(--accent)}
.btn.pri{background:var(--accent-d);border-color:var(--accent);color:var(--accent)}
.btn.pri:hover{background:var(--accent);color:var(--bg2)}
.btn.danger{color:var(--red);border-color:var(--red-d)}
.btn.danger:hover{background:var(--red-d);border-color:var(--red)}
.btn.sm{padding:6px 11px;font-size:.77rem}
.srch-wrap{margin-left:auto;position:relative}
.srch{background:var(--bg3);border:1px solid var(--border);border-radius:var(--r-s);padding:7px 12px 7px 32px;color:var(--text);width:190px;transition:all .2s;font-size:16px}
@media(min-width:600px){.srch{font-size:.82rem}}
.srch:focus{outline:none;border-color:var(--accent);background:var(--bg2);width:230px}
.srch::placeholder{color:var(--text3)}
.srch-ico{position:absolute;left:9px;top:50%;transform:translateY(-50%);color:var(--text3);font-size:.9rem;pointer-events:none}

/* ══════════════════════════════════════════════════════════
   TABLE (desktop)
   ══════════════════════════════════════════════════════════ */
.tbl-wrap{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r);overflow:hidden}
.tbl-scroll{overflow-x:auto;-webkit-overflow-scrolling:touch}
table{width:100%;border-collapse:collapse;min-width:700px}
thead th{background:var(--bg3);padding:9px 13px;text-align:left;font-size:.72rem;font-weight:500;color:var(--text3);letter-spacing:.04em;border-bottom:1px solid var(--border);white-space:nowrap;user-select:none}
thead th.sort-col{cursor:pointer}
thead th.sort-col:hover{color:var(--text2)}
tbody tr{border-bottom:1px solid var(--border);transition:background .1s}
tbody tr:last-child{border-bottom:none}
tbody tr:hover{background:var(--bg3)}
tbody tr.today{background:var(--accent-d);border-left:2px solid var(--accent)}
tbody tr.virtual-empty{opacity:.45}
td{padding:9px 13px;font-size:.83rem;vertical-align:middle}
td.num{color:var(--text3);font-size:.74rem;text-align:center;width:34px}
td.date-c{white-space:nowrap;min-width:100px}
td.work-c{min-width:110px;max-width:170px}
td.money-c{min-width:80px;font-weight:500}
td.profit-c{min-width:80px;text-align:right;font-weight:600}
td.status-c{min-width:100px}
td.act-c{min-width:90px;white-space:nowrap}

.cell-date{background:transparent;border:1px solid transparent;border-radius:6px;padding:3px 5px;color:var(--text);font-size:16px;width:100%;cursor:pointer;transition:all .18s}
@media(min-width:600px){.cell-date{font-size:.8rem}}
.cell-date:hover,.cell-date:focus{background:var(--bg3);border-color:var(--border);outline:none}
.cell-ta{background:transparent;border:1px solid transparent;border-radius:6px;padding:3px 5px;color:var(--text);font-size:16px;width:100%;resize:none;min-height:34px;transition:all .18s;line-height:1.5}
@media(min-width:600px){.cell-ta{font-size:.8rem}}
.cell-ta:hover,.cell-ta:focus{background:var(--bg3);border-color:var(--border);outline:none}

.day-tag{display:inline-flex;align-items:center;padding:1px 8px;border-radius:20px;font-size:.72rem;background:var(--bg4);color:var(--text3)}
.date-fmt{font-size:.72rem;color:var(--text3);margin-top:2px}
.money-g{color:var(--accent)}.money-r{color:var(--red)}
.profit-pos{color:var(--accent)}.profit-neg{color:var(--red)}.profit-zero{color:var(--text3)}

.sbadge{display:inline-flex;align-items:center;padding:2px 7px;border-radius:20px;font-size:.68rem;font-weight:500;white-space:nowrap}
.sb-wait{background:var(--bg4);color:var(--text3)}
.sb-part{background:var(--yellow-d);color:var(--yellow)}
.sb-done{background:var(--accent-d);color:var(--accent)}
.sb-paid{background:var(--blue-d);color:var(--blue)}

.act-btns{display:flex;gap:4px}
.btn-sm-ico{width:28px;height:28px;border:1px solid var(--border);background:var(--bg3);border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:.8rem;color:var(--text2);transition:all .15s}
.btn-sm-ico:hover{background:var(--bg4);color:var(--text)}
.btn-sm-ico.del:hover{background:var(--red-d);color:var(--red);border-color:var(--red)}
.btn-sm-ico.edit:hover{background:var(--accent-d);color:var(--accent);border-color:var(--accent)}
.btn-sm-ico.dup:hover{background:var(--blue-d);color:var(--blue);border-color:var(--blue)}
.btn-sm-ico.add-day:hover{background:var(--accent-d);color:var(--accent);border-color:var(--accent)}

/* ══════════════════════════════════════════════════════════
   CARD LIST (mobile)
   ══════════════════════════════════════════════════════════ */
.card-list{display:none;flex-direction:column;gap:9px}
.day-card{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r);padding:14px;transition:box-shadow .15s}
.day-card.today{border-left:3px solid var(--accent)}
.day-card.virtual-empty{opacity:.5}
.day-card.virtual-empty .dc-footer{display:none}
.dc-top{display:flex;align-items:flex-start;justify-content:space-between;gap:8px;margin-bottom:8px}
.dc-date{font-size:.88rem;font-weight:500}
.dc-day{font-size:.73rem;color:var(--text3);margin-top:2px}
.dc-nums{display:grid;grid-template-columns:repeat(2,1fr);gap:7px;margin-bottom:9px}
.dc-num{background:var(--bg3);border-radius:8px;padding:7px 9px}
.dc-num-label{font-size:.67rem;color:var(--text3);margin-bottom:2px}
.dc-num-val{font-size:.95rem;font-weight:600}
.dc-works{font-size:.78rem;color:var(--text2);line-height:1.5;margin-bottom:9px}
.dc-footer{display:flex;align-items:center;justify-content:space-between;gap:7px}

/* empty day card tap-to-add */
.dc-tap-add{
  width:100%;padding:9px;border:1px dashed var(--border);background:transparent;
  color:var(--text3);border-radius:8px;font-size:.8rem;cursor:pointer;transition:all .15s;
  display:flex;align-items:center;justify-content:center;gap:5px;
}
.dc-tap-add:hover,.dc-tap-add:active{border-color:var(--accent);color:var(--accent);background:var(--accent-d)}

/* ══════════════════════════════════════════════════════════
   CALENDAR VIEW (ใหม่)
   ══════════════════════════════════════════════════════════ */
.cal-view{display:none}
.cal-view.active{display:block}
.cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:3px;margin-bottom:10px}
.cal-dow{text-align:center;font-size:.67rem;font-weight:600;color:var(--text3);padding:6px 0;text-transform:uppercase;letter-spacing:.05em}
.cal-dow:first-child,.cal-dow:last-child{color:var(--red)}
.cal-cell{
  background:var(--bg2);border:1px solid var(--border);border-radius:10px;
  min-height:72px;padding:6px 7px;cursor:pointer;transition:all .15s;position:relative;
  display:flex;flex-direction:column;gap:2px;
}
.cal-cell:hover{border-color:var(--accent);box-shadow:var(--shadow-s)}
.cal-cell.empty-cell{background:transparent;border-color:transparent;cursor:default}
.cal-cell.empty-cell:hover{border-color:transparent;box-shadow:none}
.cal-cell.cal-today{border-color:var(--accent);background:var(--accent-d)}
.cal-cell.cal-today .cal-dn{color:var(--accent);font-weight:700}
.cal-cell.has-data{border-color:var(--border)}
/* Calendar color system: green=done, yellow=partial, blue=paid, red=no work but has items, gray=empty */
.cal-cell.st-done{border-color:var(--accent)!important;background:var(--accent-d)}
.cal-cell.st-done .cal-dn{color:var(--accent)}
.cal-cell.st-part{border-color:var(--yellow)!important;background:var(--yellow-d)}
.cal-cell.st-part .cal-dn{color:var(--yellow)}
.cal-cell.st-paid{border-color:var(--blue)!important;background:var(--blue-d)}
.cal-cell.st-paid .cal-dn{color:var(--blue)}
.cal-cell.st-wait{border-color:var(--red)!important;background:var(--red-d)!important}
.cal-cell.st-wait .cal-dn{color:var(--red)}
.cal-dn{font-size:.78rem;font-weight:600;color:var(--text);line-height:1}
.cal-badge{
  display:inline-flex;align-items:center;padding:1px 5px;border-radius:4px;
  font-size:.6rem;font-weight:600;margin-top:2px;line-height:1.3;
}
.cal-badge.cb-wait{background:var(--bg4);color:var(--text3)}
.cal-badge.cb-part{background:var(--yellow-d);color:var(--yellow)}
.cal-badge.cb-done{background:var(--accent-d);color:var(--accent)}
.cal-badge.cb-paid{background:var(--blue-d);color:var(--blue)}
.cal-info{font-size:.6rem;color:var(--text3);line-height:1.3;margin-top:1px}
.cal-rai{font-size:.6rem;color:var(--teal)}
.cal-dot-row{display:flex;gap:2px;flex-wrap:wrap;margin-top:2px}
.cal-dot{width:5px;height:5px;border-radius:50%;flex-shrink:0}

/* calendar on mobile: compact */
@media(max-width:600px){
  .cal-cell{min-height:56px;padding:4px 5px;border-radius:8px}
  .cal-dn{font-size:.72rem}
  .cal-badge{font-size:.52rem;padding:1px 4px}
  .cal-info,.cal-rai{font-size:.55rem}
}

/* ══════════════════════════════════════════════════════════
   CALENDAR LEGEND (ใหม่)
   ══════════════════════════════════════════════════════════ */
.cal-legend{display:flex;gap:10px;flex-wrap:wrap;padding:0 0 10px;font-size:.7rem;color:var(--text3)}
.cl-item{display:flex;align-items:center;gap:4px}
.cl-dot{width:9px;height:9px;border-radius:3px;flex-shrink:0}
.cl-dot.g{background:var(--accent)}.cl-dot.y{background:var(--yellow)}
.cl-dot.b{background:var(--blue)}.cl-dot.r{background:var(--red)}
   ══════════════════════════════════════════════════════════ */
.fab{
  position:fixed;bottom:24px;right:20px;z-index:150;
  width:52px;height:52px;border-radius:50%;
  background:var(--accent);color:var(--bg);border:none;
  font-size:1.4rem;display:flex;align-items:center;justify-content:center;
  box-shadow:0 4px 20px rgba(16,185,129,.45);transition:all .2s;
  -webkit-tap-highlight-color:transparent;
}
.fab:hover,.fab:active{transform:scale(1.08);box-shadow:0 6px 28px rgba(16,185,129,.6)}
@media(min-width:769px){.fab{display:none}}

/* ══════════════════════════════════════════════════════════
   QUICK ADD PANEL (ใหม่)
   ══════════════════════════════════════════════════════════ */
.quick-add{
  background:var(--bg2);border:1px solid var(--accent);border-radius:var(--r);
  padding:14px 16px;margin-bottom:14px;display:none;
  animation:slideDown .2s ease;
}
.quick-add.open{display:block}
@keyframes slideDown{from{opacity:0;transform:translateY(-8px)}to{opacity:1;transform:none}}
.qa-row{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
.qa-label{font-size:.75rem;color:var(--accent);font-weight:600;white-space:nowrap}
.qa-input{
  background:var(--bg3);border:1px solid var(--border);border-radius:8px;
  padding:8px 11px;color:var(--text);font-size:16px;flex:1;min-width:120px;
  transition:border-color .15s;
}
@media(min-width:600px){.qa-input{font-size:.85rem}}
.qa-input:focus{outline:none;border-color:var(--accent)}
.qa-date{max-width:150px;flex:none}
.qa-btns{display:flex;gap:6px;margin-top:8px}

/* ══════════════════════════════════════════════════════════
   OVERLAYS — preserve เดิม
   ══════════════════════════════════════════════════════════ */
.overlay{position:fixed;inset:0;background:rgba(0,0,0,.55);z-index:200;display:flex;align-items:flex-end;justify-content:center;opacity:0;pointer-events:none;transition:opacity .22s;overflow:hidden;overscroll-behavior:contain}
.overlay.show{opacity:1;pointer-events:all}
@media(min-width:600px){.overlay{align-items:center}}

.detail-modal{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r) var(--r) 0 0;width:100%;max-width:820px;max-height:92vh;overflow-y:auto;overflow-x:hidden;box-shadow:var(--shadow);transform:translateY(20px);transition:transform .22s}
@media(min-width:600px){.detail-modal{border-radius:var(--r);max-height:88vh;transform:scale(.97)}}
.overlay.show .detail-modal{transform:none}
@media(min-width:600px){.overlay.show .detail-modal{transform:scale(1)}}

.dm-header{padding:14px 18px 12px;border-bottom:1px solid var(--border);display:flex;align-items:center;gap:10px;background:var(--bg2);position:sticky;top:0;z-index:2}
.dm-title{font-size:.95rem;font-weight:600;flex:1;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.dm-close{width:30px;height:30px;border:none;background:transparent;color:var(--text3);font-size:1.25rem;display:flex;align-items:center;justify-content:center;border-radius:6px;transition:all .15s;flex-shrink:0}
.dm-close:hover{background:var(--bg3);color:var(--text)}
.dm-body{padding:16px 18px;display:flex;flex-direction:column;gap:16px;overflow-x:hidden;width:100%;box-sizing:border-box}
.dm-section{display:flex;flex-direction:column;gap:9px}
.dm-sec-title{font-size:.7rem;font-weight:500;color:var(--text3);letter-spacing:.06em;text-transform:uppercase;padding-bottom:6px;border-bottom:1px solid var(--border)}
.field-group{display:grid;grid-template-columns:1fr 1fr;gap:9px}
.field{display:flex;flex-direction:column;gap:4px}
.field.full{grid-column:1/-1}
.field label{font-size:.72rem;color:var(--text3)}
.field input,.field textarea,.field select{
  background:var(--bg3);border:1px solid var(--border);border-radius:var(--r-s);
  padding:8px 10px;color:var(--text);font-size:16px;transition:all .18s;width:100%;box-sizing:border-box;
}
@media(min-width:600px){.field input,.field textarea,.field select{font-size:.85rem}}
.field input:focus,.field textarea:focus,.field select:focus{outline:none;border-color:var(--accent);background:var(--bg2)}
.field textarea{resize:vertical;min-height:58px;line-height:1.5}

/* item cards (preserve) */
.item-cards-wrap{display:grid;grid-template-columns:1fr;gap:9px;width:100%}
.item-card{background:var(--bg3);border:1px solid var(--border);border-radius:var(--r-s);padding:14px;display:flex;flex-direction:column;gap:10px;width:100%;box-sizing:border-box}
.item-field{display:flex;flex-direction:column;gap:5px;width:100%}
.item-field label{font-size:.71rem;color:var(--text3);font-weight:500}
.item-field input,.item-field select{
  background:var(--bg2);border:1px solid var(--border);border-radius:8px;
  padding:10px 12px;color:var(--text);font-size:16px;width:100%;min-height:44px;
  transition:all .15s;-webkit-appearance:none;appearance:none;box-sizing:border-box;
}
@media(min-width:600px){.item-field input,.item-field select{font-size:.9rem}}
.item-field input:focus,.item-field select:focus{outline:none;border-color:var(--accent)}
.item-field input.inc-rai{color:var(--teal)}
.item-field input.inc-amt{color:var(--accent)}
.item-field input.exp-amt{color:var(--red)}
.item-del-btn{width:100%;padding:10px;border:1px solid var(--red-d);background:transparent;color:var(--red);border-radius:8px;font-size:.82rem;font-weight:500;min-height:44px;transition:all .15s;display:flex;align-items:center;justify-content:center;gap:5px;margin-top:2px;box-sizing:border-box}
.item-del-btn:hover,.item-del-btn:active{background:var(--red-d)}
.items-empty{font-size:.8rem;color:var(--text3);padding:10px 0;text-align:center}
.items-summary{font-size:.78rem;color:var(--text2);padding:8px 0;border-top:1px solid var(--border);margin-top:4px;font-weight:500}

/* ══════════════════════════════════════════════════════════
   CALENDAR FILTER INDICATOR (ใหม่)
   ══════════════════════════════════════════════════════════ */
.cal-cell.filtered-out{opacity:.25;pointer-events:none}

/* ══════════════════════════════════════════════════════════
   TODAY HIGHLIGHT pulse (subtle)
   ══════════════════════════════════════════════════════════ */
.cal-cell.cal-today::after{content:'';position:absolute;inset:-1px;border-radius:11px;border:2px solid var(--accent);pointer-events:none;animation:todayPulse 2.5s ease-in-out infinite}
@keyframes todayPulse{0%,100%{opacity:.8}50%{opacity:.3}}

.check-list{display:flex;flex-direction:column;gap:8px}
.chk-label{display:flex;align-items:center;gap:8px;font-size:.83rem;color:var(--text2);cursor:pointer;user-select:none;min-height:36px}
.chk-label input[type=checkbox]{accent-color:var(--accent);width:15px;height:15px;cursor:pointer;flex-shrink:0}

.dm-footer{padding:12px 18px;border-top:1px solid var(--border);display:flex;gap:7px;justify-content:flex-end;background:var(--bg2);position:sticky;bottom:0;padding-bottom:max(12px,env(safe-area-inset-bottom))}

.confirm-modal{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r);padding:22px;max-width:360px;width:90%;box-shadow:var(--shadow);transform:scale(.96);transition:transform .22s}
.overlay.show .confirm-modal{transform:scale(1)}
.confirm-modal h3{font-size:.92rem;font-weight:600;margin-bottom:7px}
.confirm-modal p{font-size:.82rem;color:var(--text2);margin-bottom:16px;line-height:1.6}
.confirm-btns{display:flex;gap:7px;justify-content:flex-end}

/* ══════════════════════════════════════════════════════════
   TOAST
   ══════════════════════════════════════════════════════════ */
.toast-c{position:fixed;bottom:24px;left:50%;transform:translateX(-50%);z-index:400;display:flex;flex-direction:column;gap:5px;pointer-events:none;align-items:center}
@media(min-width:769px){.toast-c{left:auto;right:20px;transform:none;align-items:flex-end}}
.toast{background:var(--bg2);border:1px solid var(--border);border-radius:var(--r-s);padding:8px 13px;font-size:.8rem;color:var(--text);box-shadow:var(--shadow-s);display:flex;align-items:center;gap:6px;animation:toastIn .22s ease,toastOut .22s ease 2.7s forwards;white-space:nowrap}
.toast.ok{border-left:3px solid var(--accent)}.toast.err{border-left:3px solid var(--red)}.toast.info{border-left:3px solid var(--blue)}
@keyframes toastIn{from{opacity:0;transform:translateY(8px)}to{opacity:1;transform:none}}
@keyframes toastOut{to{opacity:0}}

/* ══════════════════════════════════════════════════════════
   EMPTY STATE
   ══════════════════════════════════════════════════════════ */
.empty{padding:48px 20px;text-align:center;color:var(--text3)}
.empty .ico{font-size:2.6rem;margin-bottom:10px}
.empty h3{font-size:.95rem;color:var(--text2);margin-bottom:5px;font-weight:500}
.empty p{font-size:.81rem}

/* ══════════════════════════════════════════════════════════
   PRINT
   ══════════════════════════════════════════════════════════ */
@media print{
  .no-print,.hdr,.month-nav,.mini-bar,.filter-bar,.toolbar,.fab,.quick-add,.act-c,.card-list,.cal-view{display:none!important}
  .tbl-wrap{display:block!important}
  body{background:#fff;color:#000}
  td,th{border:1px solid #ddd!important}
  .print-hdr{display:block!important}
}
.print-hdr{display:none;text-align:center;margin-bottom:14px}
#importFile{display:none}

/* ══════════════════════════════════════════════════════════
   RESPONSIVE
   ══════════════════════════════════════════════════════════ */
@media(max-width:768px){
  .tbl-wrap{display:none}
  .card-list{display:flex}
  .detail-modal{max-width:100vw;max-height:96vh}
  .field-group{grid-template-columns:1fr}
  .field.full{grid-column:unset}
  .dm-body{overflow-x:hidden}
  .toolbar{gap:5px}
  .btn{padding:7px 9px;font-size:.78rem}
  .conn-text{display:none}
  .t-lbl{display:none}
  .srch{width:110px}
  .srch:focus{width:140px}
}

::-webkit-scrollbar{width:5px;height:5px}
::-webkit-scrollbar-track{background:var(--bg)}
::-webkit-scrollbar-thumb{background:var(--border);border-radius:3px}

/* ══════════════════════════════════════════════════════════
   DRAFT RECOVERY BANNER (ใหม่)
   ══════════════════════════════════════════════════════════ */
.draft-banner{
  background:var(--yellow-d);border-bottom:1px solid var(--yellow);
  padding:8px 16px;font-size:.8rem;color:var(--yellow);
  display:flex;align-items:center;justify-content:space-between;gap:10px;
}
.draft-banner.hidden{display:none!important}
.draft-banner-btns{display:flex;gap:6px}
.draft-restore-btn,.draft-discard-btn{
  padding:4px 12px;border-radius:6px;font-size:.76rem;font-weight:500;cursor:pointer;border:1px solid;
  -webkit-tap-highlight-color:transparent;
}
.draft-restore-btn{background:var(--yellow);color:var(--bg);border-color:var(--yellow)}
.draft-discard-btn{background:transparent;color:var(--yellow);border-color:var(--yellow)}

/* ══════════════════════════════════════════════════════════
   IMPROVED CARD HOVER & TOUCH STATES
   ══════════════════════════════════════════════════════════ */
.day-card{transition:box-shadow .15s,transform .12s}
@media(hover:hover){
  .day-card:hover{transform:translateY(-1px);box-shadow:0 4px 18px rgba(0,0,0,.2)}
}
.day-card:active{transform:scale(.99)}

/* ══════════════════════════════════════════════════════════
   SYNC INDICATOR on mini bar
   ══════════════════════════════════════════════════════════ */
.mini-sep{width:1px;height:16px;background:var(--border);flex-shrink:0}

/* ══════════════════════════════════════════════════════════
   IMPROVED EMPTY DAY CARD — better tap target
   ══════════════════════════════════════════════════════════ */
.day-card.virtual-empty{cursor:pointer;transition:all .15s}
@media(hover:hover){.day-card.virtual-empty:hover{opacity:.8;border-color:var(--accent)}}
.day-card.virtual-empty:active{opacity:.7}

/* ══════════════════════════════════════════════════════════
   IMPROVED QUICK ADD — sticky at bottom on mobile  
   ══════════════════════════════════════════════════════════ */
@media(max-width:600px){
  .quick-add{
    position:fixed;bottom:0;left:0;right:0;z-index:140;
    border-radius:var(--r) var(--r) 0 0;border-left:none;border-right:none;border-bottom:none;
    border-top:2px solid var(--accent);
    padding-bottom:max(16px,env(safe-area-inset-bottom));
    margin-bottom:0;
  }
  .quick-add.open{display:block}
}

/* ══════════════════════════════════════════════════════════
   IMPROVED TABLE — row number column better
   ══════════════════════════════════════════════════════════ */
tbody tr.virtual-empty td{background:transparent}

/* ══════════════════════════════════════════════════════════
   BIGGER TAP TARGETS (mobile)
   ══════════════════════════════════════════════════════════ */
@media(max-width:600px){
  .btn{min-height:40px}
  .dc-tap-add{min-height:44px}
  .chip{min-height:36px;padding:6px 14px}
  .chk-label{min-height:44px}
}

/* ══════════════════════════════════════════════════════════
   FAB improved — safe area inset
   ══════════════════════════════════════════════════════════ */
.fab{bottom:max(24px,env(safe-area-inset-bottom,24px));right:20px}

/* ══════════════════════════════════════════════════════════
   MONTH DISPLAY IMPROVED — shows Thai year + full month  
   ══════════════════════════════════════════════════════════ */
.month-display{
  display:flex;flex-direction:column;align-items:center;line-height:1.2;
  font-size:.92rem;
}
.month-display .md-month{font-size:1rem;font-weight:700}
.month-display .md-year{font-size:.7rem;color:var(--text3);font-weight:400;margin-top:1px}

/* ══════════════════════════════════════════════════════════
   IMPROVED STATS — subtle hover  
   ══════════════════════════════════════════════════════════ */
.sc-val{transition:color .2s}

/* ══════════════════════════════════════════════════════════
   SWIPE HINT (subtle) — shows only first time on mobile
   ══════════════════════════════════════════════════════════ */
.swipe-hint{
  display:none;text-align:center;font-size:.7rem;color:var(--text3);
  padding:4px 16px;animation:fadeHint 3s ease 1s forwards;
}
@keyframes fadeHint{0%{opacity:0}10%{opacity:1}80%{opacity:1}100%{opacity:0;display:none}}
@media(max-width:600px){.swipe-hint.show{display:block}}

/* ══════════════════════════════════════════════════════════
   LOADING SKELETON (ใหม่) — for smoother perceived load
   ══════════════════════════════════════════════════════════ */
.skeleton-card{
  background:var(--bg2);border:1px solid var(--border);border-radius:var(--r);
  padding:14px;animation:skelPulse 1.5s ease-in-out infinite;
}
@keyframes skelPulse{0%,100%{opacity:.6}50%{opacity:1}}
.skel-line{height:12px;background:var(--bg4);border-radius:4px;margin-bottom:8px}
.skel-line.short{width:40%}
.skel-line.med{width:65%}
</style>
</head>
<body>

<!-- ══ DRAFT RECOVERY BANNER ══ -->
<div class="draft-banner hidden" id="draftBanner">
  <span>📝 มีข้อมูลร่างที่ยังไม่ได้บันทึก — ต้องการกู้คืนไหม?</span>
  <div class="draft-banner-btns">
    <button class="draft-restore-btn" onclick="window._app.restoreDraft()">กู้คืน</button>
    <button class="draft-discard-btn" onclick="window._app.discardDraft()">ยกเลิก</button>
  </div>
</div>

<!-- ══ HEADER ══ -->
<header class="hdr no-print">
  <div class="hdr-in">
    <div class="logo">🌿 จดคิวพ่นยา</div>
    <div class="conn connecting" id="connBadge">
      <div class="dot"></div>
      <span class="conn-text" id="connText">กำลังเชื่อมต่อ</span>
    </div>
    <div class="hdr-r">
      <div class="theme-wrap" id="themeWrap">
        <button class="theme-btn" onclick="window._app.toggleThemeMenu()" title="เลือกธีม">
          <span class="t-dot" id="tDot"></span>
          <span class="t-lbl">ธีม</span>
          <span class="t-caret">▾</span>
        </button>
        <div class="theme-dd" id="themeDd">
          <button class="t-opt" data-t="beige" onclick="window._app.setTheme('beige')"><span class="t-swatch" style="background:#B45309"></span>Beige</button>
          <button class="t-opt" data-t="glass" onclick="window._app.setTheme('glass')"><span class="t-swatch" style="background:linear-gradient(135deg,#0EA5E9,#8B5CF6)"></span>Glass</button>
          <button class="t-opt" data-t="gray"  onclick="window._app.setTheme('gray')"><span class="t-swatch" style="background:#2563EB"></span>Gray Blue</button>
          <button class="t-opt" data-t="dark"  onclick="window._app.setTheme('dark')"><span class="t-swatch" style="background:#10B981;border-color:#374151"></span>Dark</button>
        </div>
      </div>
      <button class="ico-btn no-print" onclick="window._app.printPage()" title="พิมพ์">🖨️</button>
    </div>
  </div>
</header>
<div class="print-hdr"><h2>🌿 แอปจดคิวพ่นยาผัก</h2><p id="printDate"></p></div>

<!-- ══ MONTH NAV ══ -->
<div class="month-nav no-print">
  <div class="month-nav-in">
    <div class="month-nav-btns">
      <button class="nav-btn" onclick="window._app.goMonthPrev()" title="เดือนก่อนหน้า">‹</button>
      <button class="nav-btn today-btn" onclick="window._app.goToday()">วันนี้</button>
      <button class="nav-btn" onclick="window._app.goMonthNext()" title="เดือนถัดไป">›</button>
    </div>
    <div class="month-display" id="monthDisplay" onclick="window._app.openMonthPicker()">
      <span class="md-month" id="mdMonth">พฤษภาคม</span>
      <span class="md-year" id="mdYear">2568</span>
    </div>
    <div class="view-switcher">
      <button class="view-tab active" id="tabList" onclick="window._app.setView('list')">รายการ</button>
      <button class="view-tab" id="tabCal" onclick="window._app.setView('cal')">ปฏิทิน</button>
    </div>
  </div>
</div>

<!-- SWIPE HINT (mobile only, auto-hides) -->
<div class="swipe-hint" id="swipeHint">← เลื่อนซ้าย/ขวา เพื่อเปลี่ยนเดือน →</div>

<!-- ══ MINI SUMMARY BAR ══ -->
<div class="mini-bar no-print" id="miniBar">
  <div class="mini-bar-in">
    <div class="mini-stat"><span class="ms-label">รายรับ</span><span class="ms-val g" id="msInc">฿0</span></div>
    <div class="mini-sep"></div>
    <div class="mini-stat"><span class="ms-label">รายจ่าย</span><span class="ms-val r" id="msExp">฿0</span></div>
    <div class="mini-sep"></div>
    <div class="mini-stat"><span class="ms-label">กำไร</span><span class="ms-val y" id="msProfit">฿0</span></div>
    <div class="mini-sep"></div>
    <div class="mini-stat"><span class="ms-label">ไร่</span><span class="ms-val t" id="msRai">0</span></div>
    <div class="mini-sep"></div>
    <div class="mini-stat"><span class="ms-label">งาน</span><span class="ms-val" id="msCount">0</span></div>
  </div>
</div>

<!-- ══ FILTER CHIPS ══ -->
<div class="filter-bar no-print">
  <div class="filter-bar-in" id="filterChips">
    <button class="chip active" data-filter="all" onclick="window._app.setFilter('all')">ทั้งหมด</button>
    <button class="chip" data-filter="has_work" onclick="window._app.setFilter('has_work')">มีงาน</button>
    <button class="chip" data-filter="no_work" onclick="window._app.setFilter('no_work')">ยังว่าง</button>
    <button class="chip" data-filter="done" onclick="window._app.setFilter('done')">เสร็จครบ</button>
    <button class="chip yellow" data-filter="partial" onclick="window._app.setFilter('partial')">บางส่วน</button>
    <button class="chip red" data-filter="unpaid" onclick="window._app.setFilter('unpaid')">ยังไม่เก็บเงิน</button>
    <button class="chip blue" data-filter="paid" onclick="window._app.setFilter('paid')">เก็บเงินแล้ว</button>
    <button class="chip" data-filter="profit_pos" onclick="window._app.setFilter('profit_pos')">กำไร</button>
  </div>
</div>

<div class="wrap">

  <!-- QUICK ADD PANEL -->
  <div class="quick-add no-print" id="quickAdd">
    <div class="qa-row">
      <span class="qa-label">⚡ เพิ่มด่วน</span>
      <input type="date" class="qa-input qa-date" id="qaDate">
      <input type="text" class="qa-input" id="qaMorning" placeholder="งานเช้า..." maxlength="100">
      <input type="text" class="qa-input" id="qaEvening" placeholder="งานเย็น..." maxlength="100">
    </div>
    <div class="qa-btns">
      <button class="btn pri sm" onclick="window._app.quickAddSubmit()">✓ บันทึก</button>
      <button class="btn sm" onclick="window._app.toggleQuickAdd(false)">ยกเลิก</button>
    </div>
  </div>

  <!-- TOOLBAR -->
  <div class="toolbar no-print">
    <button class="btn pri" onclick="window._app.addTodayRow()">＋ เพิ่มวันนี้</button>
    <button class="btn" onclick="window._app.toggleQuickAdd()">⚡ เพิ่มด่วน</button>
    <button class="btn" onclick="window._app.sortByDate()">↕ เรียง</button>
    <button class="btn" onclick="window._app.exportJSON()">📤 ส่งออก</button>
    <button class="btn" onclick="document.getElementById('importFile').click()">📥 นำเข้า</button>
    <input type="file" id="importFile" accept=".json" onchange="window._app.importJSON(event)">
    <button class="btn danger" onclick="window._app.confirmClearAll()">🗑 ล้างทั้งหมด</button>
    <div class="srch-wrap">
      <span class="srch-ico">🔍</span>
      <input type="text" class="srch" id="searchInput" placeholder="ค้นหา..." oninput="window._app.filterRows()">
    </div>
  </div>

  <!-- ══ STATS — MONTHLY ══ -->
  <div class="stats-section">
    <div class="stats-label">สรุปรายเดือน</div>
    <div class="stat-grid">
      <div class="stat-card"><div class="sc-label">รายรับ</div><div class="sc-val g" id="mIncome">฿0</div><div class="sc-sub" id="mIncSub">สด ฿0 · โอน ฿0</div></div>
      <div class="stat-card"><div class="sc-label">รายจ่าย</div><div class="sc-val r" id="mExpense">฿0</div><div class="sc-sub" id="mExpSub">สด ฿0 · โอน ฿0</div></div>
      <div class="stat-card"><div class="sc-label">กำไร</div><div class="sc-val y" id="mProfit">฿0</div><div class="sc-sub" id="mCount">0 รายการ</div></div>
      <div class="stat-card"><div class="sc-label">รวมไร่</div><div class="sc-val t" id="mRai">0 ไร่</div></div>
    </div>
  </div>

  <!-- ══ STATS — ALL TIME ══ -->
  <div class="stats-section">
    <div class="stats-label">สรุปรวมทั้งหมด</div>
    <div class="stat-grid">
      <div class="stat-card"><div class="sc-label">รายรับรวม</div><div class="sc-val g" id="statIncome">฿0</div><div class="sc-sub" id="statIncSub">สด ฿0 · โอน ฿0</div></div>
      <div class="stat-card"><div class="sc-label">รายจ่ายรวม</div><div class="sc-val r" id="statExpense">฿0</div><div class="sc-sub" id="statExpSub">สด ฿0 · โอน ฿0</div></div>
      <div class="stat-card"><div class="sc-label">กำไรรวม</div><div class="sc-val y" id="statProfit">฿0</div><div class="sc-sub" id="statJobSub">งาน 0 · เสร็จ 0</div></div>
      <div class="stat-card"><div class="sc-label">รวมไร่ทั้งหมด</div><div class="sc-val t" id="statRai">0 ไร่</div></div>
    </div>
  </div>

  <!-- ══ CALENDAR VIEW ══ -->
  <div class="cal-view" id="calView">
    <div class="cal-legend">
      <div class="cl-item"><div class="cl-dot g"></div>เสร็จครบ</div>
      <div class="cl-item"><div class="cl-dot y"></div>บางส่วน</div>
      <div class="cl-item"><div class="cl-dot b"></div>เก็บเงินแล้ว</div>
      <div class="cl-item"><div class="cl-dot r"></div>รอดำเนินการ</div>
    </div>
    <div class="cal-grid" id="calGrid"><!-- JS generated --></div>
  </div>

  <!-- ══ TABLE (desktop) ══ -->
  <div class="tbl-wrap no-print" id="tblWrap">
    <div class="tbl-scroll">
      <table id="mainTable">
        <thead><tr>
          <th style="width:34px">#</th>
          <th class="sort-col" onclick="window._app.sortByDate()">วันที่ ↕</th>
          <th>วัน</th><th>งานเช้า</th><th>งานเย็น</th>
          <th>รายรับ</th><th>รายจ่าย</th>
          <th style="text-align:right">กำไร</th>
          <th>สถานะ</th>
          <th class="no-print">จัดการ</th>
        </tr></thead>
        <tbody id="tableBody"></tbody>
      </table>
    </div>
    <div id="emptyState" class="empty" style="display:none">
      <div class="ico">🌱</div><h3>ยังไม่มีรายการในเดือนนี้</h3><p>กดปุ่ม "เพิ่มวันนี้" หรือกดวันในปฏิทินเพื่อเพิ่ม</p>
    </div>
  </div>

  <!-- ══ CARD LIST (mobile) ══ -->
  <div class="card-list" id="cardList"></div>
  <div id="cardEmpty" class="empty" style="display:none">
    <div class="ico">🌱</div><h3>ยังไม่มีรายการในเดือนนี้</h3><p>กด ＋ เพื่อเพิ่มรายการ</p>
  </div>

</div><!-- /wrap -->

<!-- FAB -->
<button class="fab no-print" onclick="window._app.fabAction()" title="เพิ่มรายการ">＋</button>

<!-- ══ DETAIL MODAL ══ -->
<div class="overlay" id="detailOverlay">
  <div class="detail-modal">
    <div class="dm-header">
      <div class="dm-title" id="dmTitle">รายละเอียด</div>
      <button class="dm-close" onclick="window._app.closeDetail()">×</button>
    </div>
    <div class="dm-body" id="dmBody"></div>
    <div class="dm-footer">
      <button class="btn danger sm" id="dmDelBtn">🗑 ลบรายการนี้</button>
      <button class="btn sm" onclick="window._app.closeDetail()">ปิด</button>
    </div>
  </div>
</div>

<!-- ══ MONTH PICKER MODAL ══ -->
<div class="month-picker-overlay" id="monthPickerOverlay" onclick="if(event.target===this)window._app.closeMonthPicker()">
  <div class="month-picker">
    <div class="mp-header">
      <div class="mp-year">
        <button class="mp-y-btn" onclick="window._app.mpYearPrev()">‹</button>
        <div class="mp-year-num" id="mpYearNum">2025</div>
        <button class="mp-y-btn" onclick="window._app.mpYearNext()">›</button>
      </div>
      <button class="mp-close" onclick="window._app.closeMonthPicker()">✕ ปิด</button>
    </div>
    <div class="mp-grid" id="mpGrid"></div>
  </div>
</div>

<!-- ══ CONFIRM MODAL ══ -->
<div class="overlay" id="confirmOverlay">
  <div class="confirm-modal">
    <h3 id="cfTitle">ยืนยัน</h3>
    <p id="cfMsg"></p>
    <div class="confirm-btns">
      <button class="btn sm" onclick="window._app.closeConfirm()">ยกเลิก</button>
      <button class="btn danger sm" id="cfOkBtn">ยืนยัน</button>
    </div>
  </div>
</div>

<div class="toast-c" id="toastC"></div>

<script type="module">
import { initializeApp }      from "https://www.gstatic.com/firebasejs/12.12.1/firebase-app.js";
import { getDatabase, ref, set, onValue } from "https://www.gstatic.com/firebasejs/12.12.1/firebase-database.js";

/* ══════════════════════════════════════════════════════════
   FIREBASE CONFIG — ห้ามเปลี่ยน
   ══════════════════════════════════════════════════════════ */
const firebaseConfig = {
  apiKey:            "AIzaSyA-Ma3ZkkPliZ7xFwfwSnM0oUrbI1wnXeQ",
  authDomain:        "spray-app-7b3ed.firebaseapp.com",
  databaseURL:       "https://spray-app-7b3ed-default-rtdb.asia-southeast1.firebasedatabase.app",
  projectId:         "spray-app-7b3ed",
  storageBucket:     "spray-app-7b3ed.firebasestorage.app",
  messagingSenderId: "569965766139",
  appId:             "1:569965766139:web:fd054889fc20fd8e41d75e"
};
const DB_PATH = "spray-app/rows"; // ห้ามเปลี่ยน

/* ══════════════════════════════════════════════════════════
   STATE
   ══════════════════════════════════════════════════════════ */
let rows = [];           // ข้อมูลจริงที่ save ใน Firebase/localStorage
let sortAsc = true;
let searchQuery = '';
let pendingCf = null;
let openRowId = null;

// Firebase state
let db = null, fbReady = false, activeInput = null, pendingSnap = null;
let ignoreSnaps = 0, writeTimer = null;

// Month navigation state
let selMonth = new Date().getMonth() + 1; // 1-12
let selYear  = new Date().getFullYear();

// View state: 'list' | 'cal'
let currentView = 'list';

// Active filter chip
let activeFilter = 'all';

// Quick add open state
let quickAddOpen = false;

/* ══════════════════════════════════════════════════════════
   CONSTANTS
   ══════════════════════════════════════════════════════════ */
const DAYS   = ['อาทิตย์','จันทร์','อังคาร','พุธ','พฤหัสบดี','ศุกร์','เสาร์'];
const MONTHS = ['มกราคม','กุมภาพันธ์','มีนาคม','เมษายน','พฤษภาคม','มิถุนายน',
                'กรกฎาคม','สิงหาคม','กันยายน','ตุลาคม','พฤศจิกายน','ธันวาคม'];
const MONTHS_SHORT = ['ม.ค.','ก.พ.','มี.ค.','เม.ย.','พ.ค.','มิ.ย.',
                      'ก.ค.','ส.ค.','ก.ย.','ต.ค.','พ.ย.','ธ.ค.'];
const isMobile = () => window.innerWidth <= 768;

/* ══════════════════════════════════════════════════════════
   THEME SYSTEM — preserve เดิมทั้งหมด
   ══════════════════════════════════════════════════════════ */
const THEME_META = {
  beige:{ dot:'#B45309' },
  glass:{ dot:'linear-gradient(135deg,#0EA5E9,#8B5CF6)' },
  gray: { dot:'#2563EB' },
  dark: { dot:'#10B981' },
};
function applyThemeUI(t) {
  const dot = document.getElementById('tDot');
  if (dot) dot.style.background = (THEME_META[t]||THEME_META.dark).dot;
  document.querySelectorAll('.t-opt').forEach(el => el.classList.toggle('active', el.dataset.t === t));
}
function setTheme(t) {
  if (!THEME_META[t]) t = 'dark';
  document.documentElement.setAttribute('data-theme', t);
  localStorage.setItem('spray_theme', t);
  applyThemeUI(t);
  closeThemeMenu();
  showToast('เปลี่ยนธีมแล้ว','info');
}
function toggleThemeMenu() { document.getElementById('themeDd').classList.toggle('open'); }
function closeThemeMenu()  { document.getElementById('themeDd')?.classList.remove('open'); }
document.addEventListener('click', e => {
  const w = document.getElementById('themeWrap');
  if (w && !w.contains(e.target)) closeThemeMenu();
});

/* ══════════════════════════════════════════════════════════
   CONNECTION
   ══════════════════════════════════════════════════════════ */
function setConn(s) {
  const b = document.getElementById('connBadge'), t = document.getElementById('connText');
  if (!b||!t) return;
  b.className = 'conn ' + s;
  t.textContent = { connecting:'กำลังเชื่อมต่อ', online:'เชื่อมต่อแล้ว', offline:'ออฟไลน์' }[s] || s;
}

/* ══════════════════════════════════════════════════════════
   LOCAL STORAGE — preserve keys เดิม
   ══════════════════════════════════════════════════════════ */
function loadLocal() {
  try { const s = localStorage.getItem('spray_rows'); return s ? JSON.parse(s) : []; }
  catch { return []; }
}
function saveLocal() {
  try { localStorage.setItem('spray_rows', JSON.stringify(rows)); }
  catch {}
}

/* ══════════════════════════════════════════════════════════
   FIREBASE WRITES — debounced
   ══════════════════════════════════════════════════════════ */
function fbWrite() {
  if (!fbReady||!db) return;
  clearTimeout(writeTimer);
  writeTimer = setTimeout(() => {
    // Save เฉพาะ rows ที่มีข้อมูลจริง — virtual empty days ไม่ save
    const toSave = rows.length ? rows : null;
    ignoreSnaps++;
    set(ref(db, DB_PATH), toSave).catch(e => {
      ignoreSnaps = Math.max(0, ignoreSnaps - 1);
      console.warn(e);
      showToast('บันทึก Cloud ไม่สำเร็จ','err');
    });
  }, 800);
}
function fbWriteNow() {
  if (!fbReady||!db) return;
  clearTimeout(writeTimer);
  ignoreSnaps++;
  set(ref(db, DB_PATH), rows.length ? rows : null).catch(e => {
    ignoreSnaps = Math.max(0, ignoreSnaps - 1);
    console.warn(e);
  });
}
function save()    { saveLocal(); fbWrite(); }
function saveNow() { saveLocal(); fbWriteNow(); }

/* ══════════════════════════════════════════════════════════
   NORMALIZE — backward compatible กับข้อมูลเก่า
   ══════════════════════════════════════════════════════════ */
function norm(row) {
  // Preserve ทุก field เดิม, เพิ่มเฉพาะที่หายไป
  if (!Array.isArray(row.incomeItems))  row.incomeItems = [];
  if (!Array.isArray(row.expenseItems)) row.expenseItems = [];
  row.incomeItems  = row.incomeItems.map(i => ({
    name: i.name||'', amount: i.amount??'', rai: i.rai??0, paymentType: i.paymentType||'เงินสด'
  }));
  row.expenseItems = row.expenseItems.map(i => ({
    name: i.name||'', amount: i.amount??'', paymentType: i.paymentType||'เงินสด'
  }));
  if (!row.status) row.status = { morning:false, evening:false, paid:false };
  // normalize status fields ที่อาจขาด
  if (typeof row.status.morning === 'undefined') row.status.morning = false;
  if (typeof row.status.evening === 'undefined') row.status.evening = false;
  if (typeof row.status.paid    === 'undefined') row.status.paid    = false;
  // preserve optional fields
  if (!row.note) row.note = '';
  return row;
}

/* ══════════════════════════════════════════════════════════
   FIREBASE INIT
   ══════════════════════════════════════════════════════════ */
try {
  const app = initializeApp(firebaseConfig);
  db = getDatabase(app);
  fbReady = true;
  onValue(ref(db, '.info/connected'), s => setConn(s.val() ? 'online' : 'offline'));
  onValue(ref(db, DB_PATH), s => {
    if (ignoreSnaps > 0) { ignoreSnaps--; return; }
    const val = s.val();
    if (activeInput) pendingSnap = val; else applySnap(val);
  }, e => { console.warn(e); setConn('offline'); rows = loadLocal().map(norm); renderAll(); });
} catch(e) {
  console.warn(e); setConn('offline'); rows = loadLocal().map(norm); renderAll();
}

/* Focus tracking เพื่อ avoid snap clobber ตอนกำลังพิมพ์ */
document.addEventListener('focusin',  e => { if (e.target.matches('input,textarea,select')) activeInput = e.target; }, true);
document.addEventListener('focusout', e => {
  setTimeout(() => {
    if (document.activeElement?.matches('input,textarea,select')) { activeInput = document.activeElement; }
    else { activeInput = null; if (pendingSnap !== null) { const v = pendingSnap; pendingSnap = null; applySnap(v); } }
  }, 0);
}, true);

function applySnap(val) {
  if (Array.isArray(val) && val.length)           { rows = val.map(norm); saveLocal(); }
  else if (val && typeof val === 'object')          { rows = Object.values(val).map(norm); saveLocal(); }
  else { const loc = loadLocal(); if (loc.length)  { rows = loc.map(norm); fbWriteNow(); } else rows = []; }
  renderAll();
}

/* ══════════════════════════════════════════════════════════
   UTILITIES
   ══════════════════════════════════════════════════════════ */
function genId()     { return Date.now().toString(36) + Math.random().toString(36).slice(2); }
function todayStr()  { const d = new Date(); return d.getFullYear()+'-'+pad(d.getMonth()+1)+'-'+pad(d.getDate()); }
function pad(n)      { return String(n).padStart(2,'0'); }
function dayName(ds) { if (!ds) return ''; return DAYS[new Date(ds+'T00:00:00').getDay()]; }
function thaiDate(ds){ if (!ds) return ''; const d = new Date(ds+'T00:00:00'); return `${d.getDate()} ${MONTHS[d.getMonth()]} ${d.getFullYear()+543}`; }
function fmt(n)      { if (!isFinite(n)) return '฿0'; return '฿'+n.toLocaleString('th-TH',{minimumFractionDigits:0,maximumFractionDigits:2}); }
function fmtRai(n)   { if (!n||!isFinite(n)) return '0'; return parseFloat(n.toFixed(2)).toString(); }
function esc(s)      { return String(s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;'); }

function safeCalc(x) {
  if (!x && x!==0) return 0;
  const s = String(x).trim(); if (!s) return 0;
  if (!/^[\d\s+\-*/().]+$/.test(s)) return 0;
  try { return evalE(s.replace(/\s+/g,'')); } catch { return 0; }
}
function evalE(s) {
  let p=0;const pk=()=>s[p],eat=()=>s[p++];
  function nm(){let n='';if(pk()==='-')n+=eat();while(p<s.length&&/[\d.]/.test(pk()))n+=eat();return parseFloat(n)||0}
  function fc(){if(pk()==='('){eat();const v=ex();if(pk()===')') eat();return v}return nm()}
  function tm(){let v=fc();while(p<s.length&&(pk()==='*'||pk()==='/')){const o=eat(),r=fc();v=o==='*'?v*r:(r?v/r:0)}return v}
  function ex(){let v=tm();while(p<s.length&&(pk()==='+'||pk()==='-')){v=eat()==='+'?v+tm():v-tm()}return v}
  const r=ex();return isFinite(r)?r:0;
}

/* ══════════════════════════════════════════════════════════
   ROW COMPUTED VALUES — preserve logic เดิม
   ══════════════════════════════════════════════════════════ */
function rowInc(r)         { if (Array.isArray(r.incomeItems)&&r.incomeItems.length) return r.incomeItems.reduce((s,i)=>s+(parseFloat(i.amount)||0),0); return safeCalc(r.income); }
function rowExp(r)         { if (Array.isArray(r.expenseItems)&&r.expenseItems.length) return r.expenseItems.reduce((s,i)=>s+(parseFloat(i.amount)||0),0); return safeCalc(r.expense); }
function rowRai(r)         { if (!Array.isArray(r.incomeItems)) return 0; return r.incomeItems.reduce((s,i)=>s+(parseFloat(i.rai)||0),0); }
function rowIncCash(r)     { if (!Array.isArray(r.incomeItems)) return 0; return r.incomeItems.filter(i=>(i.paymentType||'เงินสด')==='เงินสด').reduce((s,i)=>s+(parseFloat(i.amount)||0),0); }
function rowIncTransfer(r) { if (!Array.isArray(r.incomeItems)) return 0; return r.incomeItems.filter(i=>(i.paymentType||'เงินสด')==='โอน').reduce((s,i)=>s+(parseFloat(i.amount)||0),0); }
function rowExpCash(r)     { if (!Array.isArray(r.expenseItems)) return 0; return r.expenseItems.filter(i=>(i.paymentType||'เงินสด')==='เงินสด').reduce((s,i)=>s+(parseFloat(i.amount)||0),0); }
function rowExpTransfer(r) { if (!Array.isArray(r.expenseItems)) return 0; return r.expenseItems.filter(i=>(i.paymentType||'เงินสด')==='โอน').reduce((s,i)=>s+(parseFloat(i.amount)||0),0); }

/* ══════════════════════════════════════════════════════════
   BADGE / STATUS — preserve เดิม
   ══════════════════════════════════════════════════════════ */
function badge(st) {
  const s = st||{};
  if (s.paid)                   return '<span class="sbadge sb-paid">เก็บเงินแล้ว</span>';
  if (s.morning && s.evening)   return '<span class="sbadge sb-done">เสร็จครบ</span>';
  if (s.morning || s.evening)   return '<span class="sbadge sb-part">เสร็จบางส่วน</span>';
  return '<span class="sbadge sb-wait">รอดำเนินการ</span>';
}

/* ══════════════════════════════════════════════════════════
   MONTH NAVIGATION — ใหม่ (calendar-first)
   ══════════════════════════════════════════════════════════ */
function goToday()      { const n=new Date(); selMonth=n.getMonth()+1; selYear=n.getFullYear(); onMonthChange(); }
function goMonthPrev()  { if(selMonth===1){selMonth=12;selYear--;}else selMonth--; onMonthChange(); }
function goMonthNext()  { if(selMonth===12){selMonth=1;selYear++;}else selMonth++; onMonthChange(); }

function onMonthChange() {
  updateMonthDisplay();
  renderAll();
  // save selected month to localStorage
  try { localStorage.setItem('spray_month', JSON.stringify({m:selMonth,y:selYear})); } catch {}
}

/* ══════════════════════════════════════════════════════════
   MONTH PICKER — tap month display to open
   ══════════════════════════════════════════════════════════ */
let mpYear = new Date().getFullYear();

function openMonthPicker() {
  mpYear = selYear;
  renderMonthPicker();
  document.getElementById('monthPickerOverlay').classList.add('show');
}
function closeMonthPicker() {
  document.getElementById('monthPickerOverlay').classList.remove('show');
}
function mpYearPrev() { mpYear--; renderMonthPicker(); }
function mpYearNext() { mpYear++; renderMonthPicker(); }
function renderMonthPicker() {
  document.getElementById('mpYearNum').textContent = mpYear + 543;
  const grid = document.getElementById('mpGrid');
  if (!grid) return;
  grid.innerHTML = MONTHS_SHORT.map((m,i) => {
    const isActive = (mpYear === selYear && (i+1) === selMonth);
    return `<button class="mp-month-btn ${isActive?'active':''}" onclick="window._app.pickMonth(${i+1})">${m}</button>`;
  }).join('');
}
function pickMonth(m) {
  selMonth = m; selYear = mpYear;
  closeMonthPicker();
  onMonthChange();
}

function updateMonthDisplay() {
  const el = document.getElementById('monthDisplay');
  if (el) el.setAttribute('aria-label', `${MONTHS[selMonth-1]} ${selYear+543}`);
  const mdMonth = document.getElementById('mdMonth');
  const mdYear  = document.getElementById('mdYear');
  if (mdMonth) mdMonth.textContent = MONTHS[selMonth-1];
  if (mdYear)  mdYear.textContent  = selYear + 543;
}

/* ══════════════════════════════════════════════════════════
   VIRTUAL CALENDAR DAYS — UI only, ไม่ save วันว่าง
   สร้าง array ของวันทุกวันในเดือน แต่ merge กับ rows จริง
   ══════════════════════════════════════════════════════════ */
function getVirtualDays() {
  const daysInMonth = new Date(selYear, selMonth, 0).getDate();
  const today = todayStr();
  // build map ของ rows ในเดือนนี้ by date string
  const rowMap = new Map();
  rows.forEach(r => { if (r.date) rowMap.set(r.date, r); });

  const days = [];
  for (let d = 1; d <= daysInMonth; d++) {
    const ds = `${selYear}-${pad(selMonth)}-${pad(d)}`;
    const real = rowMap.get(ds) || null;
    days.push({ ds, d, isToday: ds===today, real });
  }
  return days;
}

/* ══════════════════════════════════════════════════════════
   FILTER — chip filter + search filter
   ══════════════════════════════════════════════════════════ */
function setFilter(f) {
  activeFilter = f;
  document.querySelectorAll('.chip[data-filter]').forEach(el => {
    el.classList.toggle('active', el.dataset.filter === f);
  });
  if (currentView === 'cal') renderCalendar();
  else { renderTable(); renderCards(); }
}

function filterRows() {
  searchQuery = document.getElementById('searchInput').value;
  renderTable(); renderCards();
}

function applyChipFilter(r) {
  if (!r) return false; // virtual empty day
  const st = r.status || {};
  const inc = rowInc(r), exp = rowExp(r);
  const hasWork = r.morning || r.evening || r.incomeItems?.length;
  switch (activeFilter) {
    case 'has_work':   return !!hasWork;
    case 'no_work':    return !hasWork;
    case 'done':       return st.morning && st.evening;
    case 'partial':    return (st.morning||st.evening) && !(st.morning&&st.evening);
    case 'unpaid':     return !st.paid && (st.morning||st.evening||hasWork);
    case 'paid':       return !!st.paid;
    case 'profit_pos': return (inc-exp) > 0;
    default:           return true;
  }
}

function applySearch(r) {
  if (!r) return false;
  const q = searchQuery.toLowerCase();
  if (!q) return true;
  const it = Array.isArray(r.incomeItems) ? r.incomeItems.map(i=>i.name).join(' ') : (r.income||'');
  const et = Array.isArray(r.expenseItems)? r.expenseItems.map(i=>i.name).join(' '): (r.expense||'');
  return (r.date||'').includes(q)||(r.morning||'').toLowerCase().includes(q)||
         (r.evening||'').toLowerCase().includes(q)||(r.note||'').toLowerCase().includes(q)||
         dayName(r.date).includes(q)||it.toLowerCase().includes(q)||et.toLowerCase().includes(q);
}

/* ══════════════════════════════════════════════════════════
   RENDER ALL
   ══════════════════════════════════════════════════════════ */
function renderAll() {
  updateMonthDisplay();
  updateStats();
  updateMonthlySummary();
  updateMiniBar();
  if (currentView === 'cal') renderCalendar();
  else { renderTable(); renderCards(); }
}

/* ══════════════════════════════════════════════════════════
   RENDER TABLE (desktop) — แสดงวันทุกวันในเดือน
   ══════════════════════════════════════════════════════════ */
function renderTable() {
  const tbody  = document.getElementById('tableBody');
  const empty  = document.getElementById('emptyState');
  if (!tbody) return;

  const virtualDays = getVirtualDays();
  const today = todayStr();
  let shownCount = 0;

  const rows_html = virtualDays.map((vd, i) => {
    const row = vd.real;
    // apply filter — skip empty days if filter != 'all' / 'no_work'
    if (!row && activeFilter !== 'all' && activeFilter !== 'no_work') return '';
    if (row && !applyChipFilter(row)) return '';
    if (row && !applySearch(row)) return '';
    // also filter no_work virtual empties vs real
    if (!row && activeFilter === 'has_work') return '';
    shownCount++;

    if (!row) {
      // virtual empty day
      return `<tr class="virtual-empty ${vd.isToday?'today':''}" data-date="${vd.ds}">
        <td class="num"><span style="color:var(--text3)">${vd.d}</span></td>
        <td class="date-c"><div class="date-fmt">${thaiDate(vd.ds)}</div></td>
        <td class="day-c"><span class="day-tag">${dayName(vd.ds)}</span></td>
        <td class="work-c" style="color:var(--text3);font-size:.77rem">—</td>
        <td class="work-c" style="color:var(--text3);font-size:.77rem">—</td>
        <td class="money-c" style="color:var(--text3)">—</td>
        <td class="money-c" style="color:var(--text3)">—</td>
        <td class="profit-c" style="color:var(--text3)">—</td>
        <td class="status-c"><span class="sbadge sb-wait">ยังว่าง</span></td>
        <td class="act-c no-print"><button class="btn-sm-ico add-day" onclick="window._app.addRowDate('${vd.ds}')" title="เพิ่มงานวันนี้">＋</button></td>
      </tr>`;
    }

    const inc=rowInc(row),exp=rowExp(row),pft=inc-exp,pc=pft>0?'pos':pft<0?'neg':'zero';
    return `<tr class="${vd.isToday?'today':''}" data-id="${row.id}">
      <td class="num">${vd.d}</td>
      <td class="date-c"><input class="cell-date" type="date" value="${esc(row.date||'')}" onchange="window._app.upField('${row.id}','date',this.value)"><div class="date-fmt">${thaiDate(row.date)}</div></td>
      <td class="day-c"><span class="day-tag">${dayName(row.date)}</span></td>
      <td class="work-c"><textarea class="cell-ta" rows="2" placeholder="งานเช้า..." oninput="window._app.upSilent('${row.id}','morning',this.value)" onchange="window._app.upField('${row.id}','morning',this.value)">${esc(row.morning||'')}</textarea></td>
      <td class="work-c"><textarea class="cell-ta" rows="2" placeholder="งานเย็น..." oninput="window._app.upSilent('${row.id}','evening',this.value)" onchange="window._app.upField('${row.id}','evening',this.value)">${esc(row.evening||'')}</textarea></td>
      <td class="money-c money-g">${fmt(inc)}</td>
      <td class="money-c money-r">${fmt(exp)}</td>
      <td class="profit-c profit-${pc}">${fmt(pft)}</td>
      <td class="status-c">${badge(row.status)}</td>
      <td class="act-c no-print"><div class="act-btns">
        <button class="btn-sm-ico edit" onclick="window._app.openDetail('${row.id}')" title="รายละเอียด">✏️</button>
        <button class="btn-sm-ico dup"  onclick="window._app.dupRow('${row.id}')" title="คัดลอก">📋</button>
        <button class="btn-sm-ico del"  onclick="window._app.askDelete('${row.id}')" title="ลบ">🗑</button>
      </div></td>
    </tr>`;
  }).join('');

  tbody.innerHTML = rows_html;
  empty.style.display = shownCount ? 'none' : '';
}

/* ══════════════════════════════════════════════════════════
   RENDER CARDS (mobile) — แสดงวันทุกวันในเดือน
   ══════════════════════════════════════════════════════════ */
function renderCards() {
  const list  = document.getElementById('cardList');
  const empty = document.getElementById('cardEmpty');
  if (!list) return;

  const virtualDays = getVirtualDays();
  const today = todayStr();
  let shownCount = 0;

  const html = virtualDays.map(vd => {
    const row = vd.real;
    if (!row && activeFilter !== 'all' && activeFilter !== 'no_work') return '';
    if (row && !applyChipFilter(row)) return '';
    if (row && !applySearch(row)) return '';
    if (!row && activeFilter === 'has_work') return '';
    shownCount++;

    if (!row) {
      return `<div class="day-card virtual-empty ${vd.isToday?'today':''}" data-date="${vd.ds}">
        <div class="dc-top">
          <div><div class="dc-date">${thaiDate(vd.ds)}</div><div class="dc-day">${dayName(vd.ds)}</div></div>
          <span class="sbadge sb-wait">ยังว่าง</span>
        </div>
        <button class="dc-tap-add" onclick="window._app.addRowDate('${vd.ds}')">＋ แตะเพื่อเพิ่มงาน</button>
      </div>`;
    }

    const inc=rowInc(row),exp=rowExp(row),pft=inc-exp,rai=rowRai(row),pc=pft>0?'g':pft<0?'r':'';
    const mor = row.morning ? `<strong>เช้า</strong> ${row.morning.slice(0,30)}${row.morning.length>30?'…':''}` : '';
    const eve = row.evening ? `<strong style="color:var(--text3)">เย็น</strong> ${row.evening.slice(0,30)}${row.evening.length>30?'…':''}` : '';
    return `<div class="day-card ${vd.isToday?'today':''}" data-id="${row.id}">
      <div class="dc-top">
        <div><div class="dc-date">${thaiDate(row.date)||'ไม่มีวันที่'}</div><div class="dc-day">${dayName(row.date)}</div></div>
        ${badge(row.status)}
      </div>
      ${(mor||eve)?`<div class="dc-works">${[mor,eve].filter(Boolean).join(' · ')}</div>`:''}
      <div class="dc-nums">
        <div class="dc-num"><div class="dc-num-label">รายรับ</div><div class="dc-num-val money-g">${fmt(inc)}</div></div>
        <div class="dc-num"><div class="dc-num-label">รายจ่าย</div><div class="dc-num-val money-r">${fmt(exp)}</div></div>
        <div class="dc-num"><div class="dc-num-label">กำไร</div><div class="dc-num-val sc-val ${pc}">${fmt(pft)}</div></div>
        <div class="dc-num"><div class="dc-num-label">รวมไร่</div><div class="dc-num-val" style="color:var(--teal)">${fmtRai(rai)} ไร่</div></div>
      </div>
      <div class="dc-footer">
        <button class="btn sm pri" onclick="window._app.openDetail('${row.id}')">✏️ แก้ไข</button>
        <button class="btn sm danger" onclick="window._app.askDelete('${row.id}')">🗑</button>
      </div>
    </div>`;
  }).join('');

  list.innerHTML = html;
  empty.style.display = shownCount ? 'none' : '';
}

/* ══════════════════════════════════════════════════════════
   RENDER CALENDAR — month grid
   ══════════════════════════════════════════════════════════ */
function renderCalendar() {
  const grid = document.getElementById('calGrid');
  if (!grid) return;

  const firstDay = new Date(selYear, selMonth-1, 1).getDay(); // 0=อาทิตย์
  const daysInMonth = new Date(selYear, selMonth, 0).getDate();
  const today = todayStr();

  // build rowMap
  const rowMap = new Map();
  rows.forEach(r => { if (r.date) rowMap.set(r.date, r); });

  let html = '';
  // day-of-week headers
  ['อา','จ','อ','พ','พฤ','ศ','ส'].forEach(d => {
    html += `<div class="cal-dow">${d}</div>`;
  });

  // empty cells before first day
  for (let i = 0; i < firstDay; i++) {
    html += `<div class="cal-cell empty-cell"></div>`;
  }

  for (let d = 1; d <= daysInMonth; d++) {
    const ds = `${selYear}-${pad(selMonth)}-${pad(d)}`;
    const row = rowMap.get(ds) || null;
    const isToday = ds === today;
    const st = row?.status || {};

    // Determine status class for color coding
    let stClass = '';
    let badgeCls = 'cb-wait';
    let badgeTxt = '';
    if (row) {
      if (st.paid)                        { stClass='st-paid'; badgeCls='cb-paid'; badgeTxt='เก็บเงิน'; }
      else if (st.morning && st.evening)  { stClass='st-done'; badgeCls='cb-done'; badgeTxt='เสร็จ'; }
      else if (st.morning || st.evening)  { stClass='st-part'; badgeCls='cb-part'; badgeTxt='บางส่วน'; }
      else                                { stClass='st-wait'; badgeCls='cb-wait'; badgeTxt='รอ'; }
    }

    // Apply chip filter to calendar cells
    let filteredOut = false;
    if (activeFilter !== 'all') {
      if (!row) {
        filteredOut = (activeFilter !== 'no_work');
      } else {
        filteredOut = !applyChipFilter(row);
      }
    }

    const rai = row ? rowRai(row) : 0;
    const inc = row ? rowInc(row) : 0;

    html += `<div class="cal-cell ${isToday?'cal-today':''} ${row?'has-data '+stClass:''} ${filteredOut?'filtered-out':''}" onclick="window._app.calCellClick('${ds}')">
      <div class="cal-dn">${d}</div>
      ${row ? `<span class="cal-badge ${badgeCls}">${badgeTxt}</span>` : ''}
      ${rai>0 ? `<div class="cal-rai">${fmtRai(rai)}ไร่</div>` : ''}
      ${inc>0 ? `<div class="cal-info">${fmt(inc)}</div>` : ''}
    </div>`;
  }

  grid.innerHTML = html;
}

function calCellClick(ds) {
  const row = rows.find(r => r.date === ds);
  if (row) { openDetail(row.id); }
  else { addRowDate(ds); }
}

/* ══════════════════════════════════════════════════════════
   VIEW SWITCHER
   ══════════════════════════════════════════════════════════ */
function setView(v) {
  currentView = v;
  document.getElementById('tabList').classList.toggle('active', v==='list');
  document.getElementById('tabCal').classList.toggle('active',  v==='cal');
  document.getElementById('calView').classList.toggle('active', v==='cal');
  document.getElementById('tblWrap').style.display = (v==='cal') ? 'none' : '';
  document.getElementById('cardList').style.display = (v==='cal') ? 'none' : '';
  document.getElementById('cardEmpty').style.display = 'none';
  document.getElementById('emptyState').style.display = 'none';
  if (v === 'cal') renderCalendar(); else { renderTable(); renderCards(); }
  try { localStorage.setItem('spray_view', v); } catch {}
}

/* ══════════════════════════════════════════════════════════
   STATS
   ══════════════════════════════════════════════════════════ */
function updateStats() {
  let inc=0,exp=0,rai=0,done=0,ic=0,it=0,ec=0,et=0;
  rows.forEach(r => {
    inc+=rowInc(r);exp+=rowExp(r);rai+=rowRai(r);
    ic+=rowIncCash(r);it+=rowIncTransfer(r);ec+=rowExpCash(r);et+=rowExpTransfer(r);
    const s=r.status||{};if(s.morning&&s.evening)done++;
  });
  const pft=inc-exp;
  const el = id => document.getElementById(id);
  if(el('statIncome'))  el('statIncome').textContent=fmt(inc);
  if(el('statIncSub'))  el('statIncSub').textContent=`สด ${fmt(ic)} · โอน ${fmt(it)}`;
  if(el('statExpense')) el('statExpense').textContent=fmt(exp);
  if(el('statExpSub'))  el('statExpSub').textContent=`สด ${fmt(ec)} · โอน ${fmt(et)}`;
  if(el('statProfit'))  {el('statProfit').textContent=fmt(pft);el('statProfit').className='sc-val '+(pft>=0?'y':'r');}
  if(el('statJobSub'))  el('statJobSub').textContent=`งาน ${rows.length} · เสร็จ ${done}`;
  if(el('statRai'))     el('statRai').textContent=fmtRai(rai)+' ไร่';
}

function updateMonthlySummary() {
  const f = rows.filter(r => {
    if (!r.date) return false;
    const d = new Date(r.date+'T00:00:00');
    return d.getMonth()+1===selMonth && d.getFullYear()===selYear;
  });
  let inc=0,exp=0,rai=0,ic=0,it=0,ec=0,et=0;
  f.forEach(r => { inc+=rowInc(r);exp+=rowExp(r);rai+=rowRai(r);ic+=rowIncCash(r);it+=rowIncTransfer(r);ec+=rowExpCash(r);et+=rowExpTransfer(r); });
  const pft=inc-exp,el=id=>document.getElementById(id);
  if(el('mIncome'))  el('mIncome').textContent=fmt(inc);
  if(el('mIncSub'))  el('mIncSub').textContent=`สด ${fmt(ic)} · โอน ${fmt(it)}`;
  if(el('mExpense')) el('mExpense').textContent=fmt(exp);
  if(el('mExpSub'))  el('mExpSub').textContent=`สด ${fmt(ec)} · โอน ${fmt(et)}`;
  if(el('mProfit'))  {el('mProfit').textContent=fmt(pft);el('mProfit').className='sc-val '+(pft>=0?'y':'r');}
  if(el('mCount'))   el('mCount').textContent=f.length+' รายการ';
  if(el('mRai'))     el('mRai').textContent=fmtRai(rai)+' ไร่';
}

function updateMiniBar() {
  const f = rows.filter(r => {
    if (!r.date) return false;
    const d = new Date(r.date+'T00:00:00');
    return d.getMonth()+1===selMonth && d.getFullYear()===selYear;
  });
  let inc=0,exp=0,rai=0;
  f.forEach(r => { inc+=rowInc(r);exp+=rowExp(r);rai+=rowRai(r); });
  const pft=inc-exp,el=id=>document.getElementById(id);
  if(el('msInc'))    {el('msInc').textContent=fmt(inc);el('msInc').className='ms-val g';}
  if(el('msExp'))    {el('msExp').textContent=fmt(exp);el('msExp').className='ms-val r';}
  if(el('msProfit')) {el('msProfit').textContent=fmt(pft);el('msProfit').className='ms-val '+(pft>=0?'y':'r');}
  if(el('msRai'))    el('msRai').textContent=fmtRai(rai);
  if(el('msCount'))  el('msCount').textContent=f.length;
}

/* ══════════════════════════════════════════════════════════
   ROW CRUD — preserve logic เดิม
   ══════════════════════════════════════════════════════════ */
function addRow() {
  rows.push({id:genId(),date:'',morning:'',evening:'',income:'',expense:'',incomeItems:[],expenseItems:[],status:{morning:false,evening:false,paid:false},note:''});
  save(); renderAll(); showToast('เพิ่มรายการแล้ว','ok');
}

function addTodayRow() {
  // ตรวจสอบว่ามีวันนี้อยู่แล้วหรือยัง
  const today = todayStr();
  const existing = rows.find(r => r.date === today);
  if (existing) { openDetail(existing.id); return; }
  rows.push({id:genId(),date:today,morning:'',evening:'',income:'',expense:'',incomeItems:[],expenseItems:[],status:{morning:false,evening:false,paid:false},note:''});
  save();
  // navigate to this month
  const n = new Date(); selMonth=n.getMonth()+1; selYear=n.getFullYear();
  renderAll(); showToast('เพิ่มรายการวันนี้แล้ว','ok');
}

function addRowDate(ds) {
  // เพิ่ม row สำหรับวันที่ระบุ — ใช้สำหรับกด virtual day หรือ calendar cell
  const existing = rows.find(r => r.date === ds);
  if (existing) { openDetail(existing.id); return; }
  const newRow = {id:genId(),date:ds,morning:'',evening:'',income:'',expense:'',incomeItems:[],expenseItems:[],status:{morning:false,evening:false,paid:false},note:''};
  rows.push(newRow); save(); renderAll();
  // auto-open detail modal
  openDetail(newRow.id);
}

function dupRow(id) {
  const r = rows.find(x => x.id===id); if (!r) return;
  const n = JSON.parse(JSON.stringify(r)); n.id = genId();
  rows.splice(rows.indexOf(r)+1, 0, n); save(); renderAll(); showToast('คัดลอกแล้ว','ok');
}

/* ══════════════════════════════════════════════════════════
   FIELD UPDATES — preserve เดิม
   ══════════════════════════════════════════════════════════ */
function upSilent(id,field,val) { const r=rows.find(x=>x.id===id);if(!r)return;r[field]=val;saveLocal();fbWrite(); }
function upField(id,field,val) {
  const r=rows.find(x=>x.id===id);if(!r)return;r[field]=val;save();
  const tr=document.querySelector(`tr[data-id="${id}"]`);
  if(tr&&field==='date'){const dt=tr.querySelector('.day-tag');if(dt)dt.textContent=dayName(val);const df=tr.querySelector('.date-fmt');if(df)df.textContent=thaiDate(val);tr.classList.toggle('today',val===todayStr());updateMonthlySummary();updateMiniBar();}
}

/* ══════════════════════════════════════════════════════════
   DETAIL MODAL — preserve เดิม
   ══════════════════════════════════════════════════════════ */
function openDetail(id) {
  openRowId = id;
  renderDetailModal();
  document.getElementById('detailOverlay').classList.add('show');
}
function closeDetail() {
  document.getElementById('detailOverlay').classList.remove('show');
  openRowId = null;
  clearDraft(); // draft saved — clear it
  renderAll();
}
document.getElementById('detailOverlay').addEventListener('click', e => {
  if (e.target === document.getElementById('detailOverlay')) closeDetail();
});

function renderDetailModal() {
  const row = rows.find(r => r.id===openRowId); if (!row) return;
  const inc=rowInc(row),exp=rowExp(row),pft=inc-exp,rai=rowRai(row),st=row.status||{};
  document.getElementById('dmTitle').textContent = thaiDate(row.date)||'รายละเอียด';
  document.getElementById('dmDelBtn').onclick = () => { closeDetail(); askDelete(row.id); };
  document.getElementById('dmBody').innerHTML = `
    <div class="dm-section">
      <div class="dm-sec-title">📋 ข้อมูลงาน</div>
      <div class="field-group">
        <div class="field"><label>วันที่</label><input type="date" value="${esc(row.date||'')}" onchange="window._app.dmUpField('date',this.value)"></div>
        <div class="field"><label>วัน</label><input type="text" value="${esc(dayName(row.date))}" readonly style="color:var(--text3)"></div>
        <div class="field full"><label>งานช่วงเช้า</label><textarea rows="2" oninput="window._app.dmUpSilent('morning',this.value)" onchange="window._app.dmUpField('morning',this.value)">${esc(row.morning||'')}</textarea></div>
        <div class="field full"><label>งานช่วงเย็น</label><textarea rows="2" oninput="window._app.dmUpSilent('evening',this.value)" onchange="window._app.dmUpField('evening',this.value)">${esc(row.evening||'')}</textarea></div>
      </div>
    </div>
    <div class="dm-section">
      <div class="dm-sec-title">💰 รายรับ — รวม <span style="color:var(--accent)">${fmt(inc)}</span> · ${fmtRai(rai)} ไร่</div>
      <div class="item-cards-wrap" id="dmIncCards">${buildIncCards(row)}</div>
      <button class="btn sm" style="margin-top:6px" onclick="window._app.dmAddInc()">＋ เพิ่มรายรับ</button>
    </div>
    <div class="dm-section">
      <div class="dm-sec-title">💸 รายจ่าย — รวม <span style="color:var(--red)">${fmt(exp)}</span></div>
      <div class="item-cards-wrap" id="dmExpCards">${buildExpCards(row)}</div>
      <button class="btn sm" style="margin-top:6px" onclick="window._app.dmAddExp()">＋ เพิ่มรายจ่าย</button>
    </div>
    <div class="dm-section">
      <div class="dm-sec-title">✅ สถานะ</div>
      <div class="check-list">
        <label class="chk-label"><input type="checkbox" ${st.morning?'checked':''} onchange="window._app.dmUpStatus('morning',this.checked)"> งานเช้าเสร็จแล้ว</label>
        <label class="chk-label"><input type="checkbox" ${st.evening?'checked':''} onchange="window._app.dmUpStatus('evening',this.checked)"> งานเย็นเสร็จแล้ว</label>
        <label class="chk-label"><input type="checkbox" ${st.paid?'checked':''} onchange="window._app.dmUpStatus('paid',this.checked)"> เก็บเงินแล้ว</label>
      </div>
    </div>
    <div class="dm-section">
      <div class="dm-sec-title">📝 หมายเหตุ</div>
      <div class="field"><textarea rows="3" placeholder="หมายเหตุ..." oninput="window._app.dmUpSilent('note',this.value)" onchange="window._app.dmUpField('note',this.value)">${esc(row.note||'')}</textarea></div>
    </div>
    <div class="dm-section">
      <div class="dm-sec-title">📊 สรุปรายการนี้</div>
      <div class="stat-grid" style="grid-template-columns:repeat(2,1fr);gap:8px" id="dmSummaryGrid">
        <div class="stat-card"><div class="sc-label">รายรับ</div><div class="sc-val g">${fmt(inc)}</div></div>
        <div class="stat-card"><div class="sc-label">รายจ่าย</div><div class="sc-val r">${fmt(exp)}</div></div>
        <div class="stat-card"><div class="sc-label">กำไร</div><div class="sc-val ${pft>=0?'y':'r'}">${fmt(pft)}</div></div>
        <div class="stat-card"><div class="sc-label">รวมไร่</div><div class="sc-val t">${fmtRai(rai)} ไร่</div></div>
      </div>
    </div>`;
}

/* ── item card builders — preserve เดิม ── */
function buildIncCards(row) {
  const arr = row.incomeItems||[];
  if (!arr.length) return '<div class="items-empty">ยังไม่มีรายรับ</div>';
  return arr.map((item,idx) => `
    <div class="item-card">
      <div class="item-field"><label>ชื่อ / งาน</label><input type="text" value="${esc(item.name||'')}" placeholder="ชื่องาน..." oninput="window._app.dmUpInc(${idx},'name',this.value)" onchange="window._app.dmUpInc(${idx},'name',this.value)"></div>
      <div class="item-field"><label>จำนวนไร่</label><input class="inc-rai" type="number" min="0" step="0.25" value="${esc(String(item.rai??''))}" placeholder="0" oninput="window._app.dmUpInc(${idx},'rai',this.value)" onchange="window._app.dmUpInc(${idx},'rai',this.value)"></div>
      <div class="item-field"><label>จำนวนเงิน (บาท)</label><input class="inc-amt" type="number" min="0" step="any" value="${esc(String(item.amount??''))}" placeholder="0" oninput="window._app.dmUpInc(${idx},'amount',this.value)" onchange="window._app.dmUpInc(${idx},'amount',this.value)"></div>
      <div class="item-field"><label>ประเภทเงิน</label><select onchange="window._app.dmUpInc(${idx},'paymentType',this.value)"><option value="เงินสด" ${(item.paymentType||'เงินสด')==='เงินสด'?'selected':''}>💵 เงินสด</option><option value="โอน" ${(item.paymentType||'เงินสด')==='โอน'?'selected':''}>📲 โอน</option></select></div>
      <button class="item-del-btn" onclick="window._app.dmDelInc(${idx})">🗑 ลบรายการนี้</button>
    </div>`).join('') + `<div class="items-summary">รวมรายรับ ${fmt(arr.reduce((s,i)=>s+(parseFloat(i.amount)||0),0))} · ${fmtRai(arr.reduce((s,i)=>s+(parseFloat(i.rai)||0),0))} ไร่</div>`;
}

function buildExpCards(row) {
  const arr = row.expenseItems||[];
  if (!arr.length) return '<div class="items-empty">ยังไม่มีรายจ่าย</div>';
  return arr.map((item,idx) => `
    <div class="item-card">
      <div class="item-field"><label>ชื่อรายการ</label><input type="text" value="${esc(item.name||'')}" placeholder="ชื่อรายจ่าย..." oninput="window._app.dmUpExp(${idx},'name',this.value)" onchange="window._app.dmUpExp(${idx},'name',this.value)"></div>
      <div class="item-field"><label>จำนวนเงิน (บาท)</label><input class="exp-amt" type="number" min="0" step="any" value="${esc(String(item.amount??''))}" placeholder="0" oninput="window._app.dmUpExp(${idx},'amount',this.value)" onchange="window._app.dmUpExp(${idx},'amount',this.value)"></div>
      <div class="item-field"><label>ประเภทเงิน</label><select onchange="window._app.dmUpExp(${idx},'paymentType',this.value)"><option value="เงินสด" ${(item.paymentType||'เงินสด')==='เงินสด'?'selected':''}>💵 เงินสด</option><option value="โอน" ${(item.paymentType||'เงินสด')==='โอน'?'selected':''}>📲 โอน</option></select></div>
      <button class="item-del-btn" onclick="window._app.dmDelExp(${idx})">🗑 ลบรายการนี้</button>
    </div>`).join('') + `<div class="items-summary">รวมรายจ่าย ${fmt(arr.reduce((s,i)=>s+(parseFloat(i.amount)||0),0))}</div>`;
}

/* ── Modal field updaters — preserve เดิม ── */
function dmUpSilent(field,val) { const r=rows.find(x=>x.id===openRowId);if(!r)return;r[field]=val;saveLocal();fbWrite();saveDraft(); }
function dmUpField(field,val) {
  const r=rows.find(x=>x.id===openRowId);if(!r)return;r[field]=val;save();
  if(field==='date'){updateDmSummary(r);updateMonthlySummary();updateMiniBar();}
}
function dmUpStatus(field,val) {
  const r=rows.find(x=>x.id===openRowId);if(!r)return;if(!r.status)r.status={};r.status[field]=val;save();
  updateStats();
}
function dmUpInc(idx,field,val) {
  const r=rows.find(x=>x.id===openRowId);if(!r||!r.incomeItems[idx])return;
  r.incomeItems[idx][field]=(field==='amount'||field==='rai')?(val===''?'':(parseFloat(val)||0)):val;
  saveLocal();fbWrite();updateDmSummary(r);updateStats();updateMonthlySummary();updateMiniBar();saveDraft();
}
function dmUpExp(idx,field,val) {
  const r=rows.find(x=>x.id===openRowId);if(!r||!r.expenseItems[idx])return;
  r.expenseItems[idx][field]=field==='amount'?(val===''?'':(parseFloat(val)||0)):val;
  saveLocal();fbWrite();updateDmSummary(r);updateStats();updateMonthlySummary();updateMiniBar();saveDraft();
}
function dmAddInc() { const r=rows.find(x=>x.id===openRowId);if(!r)return;r.incomeItems.push({name:'',amount:'',rai:0,paymentType:'เงินสด'});saveNow();rebuildDmInc(); }
function dmDelInc(idx) { const r=rows.find(x=>x.id===openRowId);if(!r)return;r.incomeItems.splice(idx,1);saveNow();rebuildDmInc();updateStats();updateMonthlySummary();updateMiniBar(); }
function dmAddExp() { const r=rows.find(x=>x.id===openRowId);if(!r)return;r.expenseItems.push({name:'',amount:'',paymentType:'เงินสด'});saveNow();rebuildDmExp(); }
function dmDelExp(idx) { const r=rows.find(x=>x.id===openRowId);if(!r)return;r.expenseItems.splice(idx,1);saveNow();rebuildDmExp();updateStats();updateMonthlySummary();updateMiniBar(); }

function rebuildDmInc() {
  const el=document.getElementById('dmIncCards');
  const r=rows.find(x=>x.id===openRowId);if(!r)return;
  if(el)el.innerHTML=buildIncCards(r);updateDmSummary(r);
}
function rebuildDmExp() {
  const el=document.getElementById('dmExpCards');
  const r=rows.find(x=>x.id===openRowId);if(!r)return;
  if(el)el.innerHTML=buildExpCards(r);updateDmSummary(r);
}
function updateDmSummary(row) {
  const inc=rowInc(row),exp=rowExp(row),pft=inc-exp,rai=rowRai(row);
  const secs=document.querySelectorAll('#dmBody .dm-sec-title');
  if(secs[1])secs[1].innerHTML=`💰 รายรับ — รวม <span style="color:var(--accent)">${fmt(inc)}</span> · ${fmtRai(rai)} ไร่`;
  if(secs[2])secs[2].innerHTML=`💸 รายจ่าย — รวม <span style="color:var(--red)">${fmt(exp)}</span>`;
  const cards=document.querySelectorAll('#dmSummaryGrid .sc-val');
  if(cards[0])cards[0].textContent=fmt(inc);if(cards[1])cards[1].textContent=fmt(exp);
  if(cards[2]){cards[2].textContent=fmt(pft);cards[2].className='sc-val '+(pft>=0?'y':'r');}
  if(cards[3])cards[3].textContent=fmtRai(rai)+' ไร่';
  const dmT=document.getElementById('dmTitle');if(dmT)dmT.textContent=thaiDate(row.date)||'รายละเอียด';
}

/* ══════════════════════════════════════════════════════════
   QUICK ADD — ใหม่
   ══════════════════════════════════════════════════════════ */
function toggleQuickAdd(force) {
  quickAddOpen = force !== undefined ? force : !quickAddOpen;
  const el = document.getElementById('quickAdd');
  el.classList.toggle('open', quickAddOpen);
  if (quickAddOpen) {
    // set default date = วันนี้
    const qaDate = document.getElementById('qaDate');
    if (qaDate && !qaDate.value) qaDate.value = todayStr();
    setTimeout(() => document.getElementById('qaMorning')?.focus(), 100);
  }
}

function quickAddSubmit() {
  const ds = document.getElementById('qaDate')?.value || todayStr();
  const morning = document.getElementById('qaMorning')?.value.trim()||'';
  const evening = document.getElementById('qaEvening')?.value.trim()||'';
  if (!morning && !evening) { showToast('กรุณาใส่ข้อมูลงาน','err'); return; }

  // check ว่ามี row วันนี้อยู่แล้ว
  const existing = rows.find(r => r.date===ds);
  if (existing) {
    if (morning) existing.morning = existing.morning ? existing.morning+'\n'+morning : morning;
    if (evening) existing.evening = existing.evening ? existing.evening+'\n'+evening : evening;
    save(); renderAll(); showToast('อัปเดตรายการแล้ว','ok');
  } else {
    rows.push({id:genId(),date:ds,morning,evening,income:'',expense:'',incomeItems:[],expenseItems:[],status:{morning:false,evening:false,paid:false},note:''});
    save();
    const d = new Date(ds+'T00:00:00'); selMonth=d.getMonth()+1; selYear=d.getFullYear();
    renderAll(); showToast('เพิ่มรายการด่วนแล้ว','ok');
  }
  // reset form
  document.getElementById('qaMorning').value='';
  document.getElementById('qaEvening').value='';
  toggleQuickAdd(false);
}

/* FAB action — บน mobile toggle quick add */
function fabAction() { toggleQuickAdd(); }

/* ══════════════════════════════════════════════════════════
   DRAFT RECOVERY — lightweight unsaved edit protection
   ══════════════════════════════════════════════════════════ */
const DRAFT_KEY = 'spray_draft_rows';
let draftSaveTimer = null;

function saveDraft() {
  // Only save a draft when we have active edits (detail modal open)
  if (!openRowId) return;
  clearTimeout(draftSaveTimer);
  draftSaveTimer = setTimeout(() => {
    try { localStorage.setItem(DRAFT_KEY, JSON.stringify(rows)); } catch {}
  }, 2000);
}

function clearDraft() {
  try { localStorage.removeItem(DRAFT_KEY); } catch {}
  clearTimeout(draftSaveTimer);
}

function checkForDraft() {
  try {
    const draft = localStorage.getItem(DRAFT_KEY);
    if (!draft) return;
    const draftRows = JSON.parse(draft);
    if (!Array.isArray(draftRows) || !draftRows.length) return;
    // Check if draft differs from current rows
    if (JSON.stringify(draftRows) !== JSON.stringify(rows)) {
      document.getElementById('draftBanner')?.classList.remove('hidden');
    }
  } catch {}
}

function restoreDraft() {
  try {
    const draft = localStorage.getItem(DRAFT_KEY);
    if (!draft) return;
    const draftRows = JSON.parse(draft);
    if (!Array.isArray(draftRows)) return;
    rows = draftRows.map(norm);
    saveNow(); renderAll(); showToast('กู้คืนข้อมูลร่างแล้ว','ok');
  } catch {}
  clearDraft();
  document.getElementById('draftBanner')?.classList.add('hidden');
}

function discardDraft() {
  clearDraft();
  document.getElementById('draftBanner')?.classList.add('hidden');
}


/* ══════════════════════════════════════════════════════════
   SORT / SEARCH
   ══════════════════════════════════════════════════════════ */
function sortByDate() {
  rows.sort((a,b) => {
    if (!a.date&&!b.date) return 0; if (!a.date) return 1; if (!b.date) return -1;
    return sortAsc ? a.date.localeCompare(b.date) : b.date.localeCompare(a.date);
  });
  sortAsc = !sortAsc; save(); renderAll();
}

/* ══════════════════════════════════════════════════════════
   CONFIRM MODAL — preserve เดิม
   ══════════════════════════════════════════════════════════ */
function showConfirm(title,msg,cb,okLabel='ยืนยัน') {
  pendingCf=cb;
  document.getElementById('cfTitle').textContent=title;
  document.getElementById('cfMsg').textContent=msg;
  document.getElementById('cfOkBtn').textContent=okLabel;
  document.getElementById('confirmOverlay').classList.add('show');
}
function closeConfirm() { document.getElementById('confirmOverlay').classList.remove('show'); pendingCf=null; }
document.getElementById('cfOkBtn').addEventListener('click', () => { if(pendingCf)pendingCf(); closeConfirm(); });
document.getElementById('confirmOverlay').addEventListener('click', e => { if(e.target===document.getElementById('confirmOverlay'))closeConfirm(); });

function askDelete(id) {
  showConfirm('ยืนยันการลบ','คุณต้องการลบรายการนี้ใช่ไหม? ไม่สามารถย้อนกลับได้',
    () => { rows=rows.filter(r=>r.id!==id); saveNow(); renderAll(); showToast('ลบรายการแล้ว','ok'); },'ลบ');
}
function confirmClearAll() {
  if (!rows.length) { showToast('ไม่มีรายการให้ล้าง','err'); return; }
  showConfirm('ยืนยันการล้างข้อมูล',`ต้องการล้างรายการทั้งหมด ${rows.length} รายการ? ข้อมูลจะหายถาวร`,
    () => { rows=[]; saveNow(); renderAll(); showToast('ล้างข้อมูลทั้งหมดแล้ว','ok'); },'ล้างทั้งหมด');
}

/* ══════════════════════════════════════════════════════════
   EXPORT / IMPORT
   ══════════════════════════════════════════════════════════ */
function exportJSON() {
  if (!rows.length) { showToast('ไม่มีข้อมูลให้ส่งออก','err'); return; }
  const b = new Blob([JSON.stringify(rows,null,2)],{type:'application/json'});
  const u = URL.createObjectURL(b); const a = document.createElement('a');
  a.href=u; a.download='spray_'+todayStr()+'.json'; a.click(); URL.revokeObjectURL(u);
  showToast('ส่งออกแล้ว','ok');
}
function importJSON(e) {
  const file = e.target.files[0]; if (!file) return;
  showConfirm('ยืนยันการนำเข้า','⚠️ การนำเข้าจะแทนที่ข้อมูลทั้งหมด กรุณาสำรองข้อมูลก่อน',
    () => { const rd=new FileReader(); rd.onload=ev=>{try{const d=JSON.parse(ev.target.result);if(!Array.isArray(d))throw 0;rows=d.map(norm);saveNow();renderAll();showToast(`นำเข้า ${rows.length} รายการแล้ว`,'ok');}catch{showToast('ไฟล์ไม่ถูกต้อง','err');}};rd.readAsText(file);},'นำเข้า');
  e.target.value='';
}

/* ══════════════════════════════════════════════════════════
   PRINT / TOAST
   ══════════════════════════════════════════════════════════ */
function printPage() { document.getElementById('printDate').textContent='พิมพ์วันที่: '+thaiDate(todayStr()); window.print(); }
function showToast(msg,type='ok') {
  const c=document.getElementById('toastC'); if(!c)return;
  const t=document.createElement('div'); t.className='toast '+type;
  t.innerHTML=(type==='ok'?'✅':type==='info'?'🎨':'❌')+' '+msg;
  c.appendChild(t); setTimeout(()=>t.remove(),3000);
}

/* ══════════════════════════════════════════════════════════
   KEYBOARD SHORTCUTS
   ══════════════════════════════════════════════════════════ */
document.addEventListener('keydown', e => {
  if (e.key==='Escape') {
    if(document.getElementById('themeDd').classList.contains('open'))     closeThemeMenu();
    else if(document.getElementById('monthPickerOverlay').classList.contains('show')) closeMonthPicker();
    else if(document.getElementById('detailOverlay').classList.contains('show')) closeDetail();
    else if(document.getElementById('confirmOverlay').classList.contains('show')) closeConfirm();
    else if(quickAddOpen) toggleQuickAdd(false);
  }
  // Arrow key month navigation (when no input is focused)
  if (!activeInput && !document.getElementById('detailOverlay').classList.contains('show')) {
    if (e.key==='ArrowLeft')  { e.preventDefault(); goMonthPrev(); }
    if (e.key==='ArrowRight') { e.preventDefault(); goMonthNext(); }
  }
});

/* ══════════════════════════════════════════════════════════
   SWIPE GESTURE — horizontal swipe for month nav on mobile
   ══════════════════════════════════════════════════════════ */
(function initSwipe() {
  let sx = 0, sy = 0, moving = false;
  const THRESHOLD = 60;
  document.addEventListener('touchstart', e => {
    // Ignore swipes starting in modals / inputs / scrollable horiz containers
    if (e.target.closest('.overlay, .mini-bar, .filter-bar, input, textarea, select')) return;
    sx = e.touches[0].clientX;
    sy = e.touches[0].clientY;
    moving = true;
  }, { passive: true });
  document.addEventListener('touchend', e => {
    if (!moving) return;
    moving = false;
    const dx = e.changedTouches[0].clientX - sx;
    const dy = e.changedTouches[0].clientY - sy;
    if (Math.abs(dx) > THRESHOLD && Math.abs(dx) > Math.abs(dy) * 1.5) {
      if (dx < 0) goMonthNext(); else goMonthPrev();
    }
  }, { passive: true });
})();

/* ══════════════════════════════════════════════════════════
   PUBLIC API — preserve ทั้งหมดของเดิม + เพิ่มใหม่
   ══════════════════════════════════════════════════════════ */
window._app = {
  // preserve เดิม
  addRow, addTodayRow, sortByDate, filterRows, exportJSON, importJSON, confirmClearAll,
  upField, upSilent, askDelete, dupRow, closeDetail, closeConfirm, printPage,
  openDetail,
  dmUpField, dmUpSilent, dmUpStatus, dmUpInc, dmUpExp, dmAddInc, dmDelInc, dmAddExp, dmDelExp,
  setTheme, toggleThemeMenu,
  // backward compat aliases
  setMonthNow: goToday, setMonthPrev: goMonthPrev, updateMonthly: updateMonthlySummary,
  // ใหม่
  goToday, goMonthPrev, goMonthNext,
  setView, setFilter,
  addRowDate, calCellClick,
  toggleQuickAdd, quickAddSubmit, fabAction,
  // month picker
  openMonthPicker, closeMonthPicker, mpYearPrev, mpYearNext, pickMonth,
  // draft recovery
  restoreDraft, discardDraft,
};

/* ══════════════════════════════════════════════════════════
   BOOT
   ══════════════════════════════════════════════════════════ */
(function boot() {
  // restore theme
  const old = localStorage.getItem('theme');
  const saved = localStorage.getItem('spray_theme')||(old==='light'?'gray':old==='dark'?'dark':null)||'dark';
  const t = ['beige','glass','gray','dark'].includes(saved)?saved:'dark';
  document.documentElement.setAttribute('data-theme',t);
  applyThemeUI(t);

  // restore month selection
  try {
    const sm = JSON.parse(localStorage.getItem('spray_month')||'null');
    if (sm?.m && sm?.y) { selMonth=sm.m; selYear=sm.y; }
  } catch {}

  // restore view
  const savedView = localStorage.getItem('spray_view');
  if (savedView === 'cal') {
    currentView = 'cal';
    document.getElementById('tabList').classList.remove('active');
    document.getElementById('tabCal').classList.add('active');
    document.getElementById('calView').classList.add('active');
  }

  // load data
  rows = loadLocal().map(norm);
  updateMonthDisplay();
  if (rows.length) renderAll();
  else { updateMonthlySummary(); updateStats(); updateMiniBar(); if(currentView==='cal')renderCalendar(); else{renderTable();renderCards();} }

  // set quick add date
  const qaDate = document.getElementById('qaDate');
  if (qaDate) qaDate.value = todayStr();

  // show swipe hint on mobile (first 5 visits)
  try {
    const visits = parseInt(localStorage.getItem('spray_visits')||'0');
    if (visits < 5 && window.innerWidth <= 600) {
      document.getElementById('swipeHint')?.classList.add('show');
    }
    localStorage.setItem('spray_visits', visits + 1);
  } catch {}

  // check for draft recovery
  setTimeout(checkForDraft, 500);
})();
</script>
</body>
</html>
