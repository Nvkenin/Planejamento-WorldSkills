<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Planejamento — WSC #54</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:ital,wght@0,300;0,400;0,500;0,700;1,400&family=Syne:wght@400;600;800&display=swap');
:root{
  --bg:#09090b;--bg2:#0e0f12;--bg3:#13151a;
  --border:#1c1f26;--border2:#262b36;
  --accent:#00e87a;--blue:#3b9eff;--red:#ff4b6e;
  --amber:#f5a623;--purple:#a78bfa;--cyan:#67e8f9;
  --text:#e2e8f4;--muted:#4a5568;--muted2:#6b7a94;
  --mono:'JetBrains Mono',monospace;--display:'Syne',sans-serif;
}
*{margin:0;padding:0;box-sizing:border-box}
body{background:var(--bg);color:var(--text);font-family:var(--mono);font-size:12.5px;line-height:1.6;min-height:100vh}
body::after{content:'';position:fixed;inset:0;background:repeating-linear-gradient(0deg,transparent,transparent 3px,rgba(0,0,0,.02) 3px,rgba(0,0,0,.02) 4px);pointer-events:none;z-index:9999}
/* SCREENS */
.screen{min-height:100vh;display:none;align-items:center;justify-content:center;padding:20px}
.screen.active{display:flex}
.box{width:380px;background:var(--bg2);border:1px solid var(--border);border-radius:6px;padding:36px}
.box-logo{font-family:var(--display);font-size:22px;font-weight:800;color:var(--accent);margin-bottom:3px;text-shadow:0 0 20px rgba(0,232,122,.2)}
.box-sub{font-size:10px;color:var(--muted);letter-spacing:.15em;text-transform:uppercase;margin-bottom:26px}
.lbl{font-size:10px;color:var(--muted2);letter-spacing:.08em;text-transform:uppercase;margin-bottom:6px;margin-top:14px}
.inp{width:100%;background:var(--bg);border:1px solid var(--border);border-radius:3px;padding:10px 12px;color:var(--text);font-family:var(--mono);font-size:12px;outline:none;transition:border-color .12s}
.inp:focus{border-color:var(--blue)}
.primary-btn{width:100%;margin-top:20px;padding:11px;background:rgba(0,232,122,.1);border:1px solid var(--accent);color:var(--accent);font-family:var(--mono);font-size:12px;border-radius:3px;cursor:pointer;transition:all .12s;letter-spacing:.06em}
.primary-btn:hover:not(:disabled){background:rgba(0,232,122,.2)}
.primary-btn:disabled{opacity:.4;cursor:not-allowed}
.secondary-btn{width:100%;margin-top:8px;padding:10px;background:transparent;border:1px solid var(--border);color:var(--muted2);font-family:var(--mono);font-size:11px;border-radius:3px;cursor:pointer;transition:all .12s}
.secondary-btn:hover{border-color:var(--red);color:var(--red)}
.err-msg{font-size:11px;color:var(--red);margin-top:10px;min-height:18px}
.ok-msg{font-size:11px;color:var(--accent);margin-top:6px;min-height:18px}
.divider{height:1px;background:var(--border);margin:16px 0}
.user-pills{display:flex;flex-direction:column;gap:8px;margin-bottom:20px}
.user-pill{display:flex;align-items:center;gap:10px;padding:10px 12px;background:var(--bg);border:1px solid var(--border);border-radius:3px;cursor:pointer;transition:all .12s}
.user-pill:hover{border-color:var(--border2);background:var(--bg3)}
.user-pill.selected{border-color:var(--accent);background:rgba(0,232,122,.05)}
.uav{width:32px;height:32px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--display);font-size:13px;font-weight:700;flex-shrink:0}
.pw-hint{font-size:10px;color:var(--muted);margin-top:8px;line-height:1.7}
.pw-hint em{color:var(--muted2);font-style:normal}
/* APP */
#app{display:none}
.app{max-width:1200px;margin:0 auto;padding:22px 20px}
header{
  display:flex;align-items:center;justify-content:space-between;
  padding-bottom:18px;border-bottom:1px solid var(--border);margin-bottom:22px;
}
.logo{
  font-family:var(--display);font-size:22px;font-weight:800;
  color:var(--accent);letter-spacing:-.5px;
  text-shadow:0 0 24px rgba(0,232,122,.25);
}
.logo-sub{font-size:10px;color:var(--muted);letter-spacing:.15em;text-transform:uppercase;margin-top:2px}
.hdr-r{display:flex;align-items:center;gap:8px}
.ubadge{
  display:flex;align-items:center;gap:8px;padding:6px 14px;
  background:var(--bg2);border:1px solid var(--border);border-radius:20px;
}
.bdot{width:6px;height:6px;border-radius:50%;animation:blink 1.6s infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.3}}
.hbtn{
  padding:6px 14px;background:transparent;border:1px solid var(--border);
  color:var(--muted2);font-family:var(--mono);font-size:11px;border-radius:20px;
  cursor:pointer;transition:all .15s;
}
.hbtn.red:hover{border-color:var(--red);color:var(--red);background:rgba(255,75,110,.06)}
.hbtn.blue:hover{border-color:var(--blue);color:var(--blue);background:rgba(59,158,255,.06)}
/* TABS */
.tabs{display:flex;gap:0;margin-bottom:22px;border-bottom:1px solid var(--border);overflow-x:auto}
.tab{
  padding:10px 18px;font-size:10px;letter-spacing:.08em;color:var(--muted2);
  cursor:pointer;border-bottom:2px solid transparent;transition:all .15s;
  text-transform:uppercase;white-space:nowrap;flex-shrink:0;
}
.tab:hover{color:var(--text);background:rgba(255,255,255,.02)}
.tab.active{color:var(--accent);border-bottom-color:var(--accent);background:rgba(0,232,122,.02)}
.view{display:none}.view.active{display:block}
/* CARDS */
.card{
  background:var(--bg2);border:1px solid var(--border);border-radius:6px;
  padding:20px;position:relative;overflow:hidden;
  transition:border-color .15s;
}
.card::before{
  content:'';position:absolute;top:0;left:0;right:0;height:1px;
  background:linear-gradient(90deg,transparent,rgba(255,255,255,.04),transparent);
}
.card:hover{border-color:var(--border2)}
.clabel{
  font-size:9px;letter-spacing:.18em;text-transform:uppercase;color:var(--muted);
  margin-bottom:14px;display:flex;align-items:center;gap:7px;
}
.clabel-dot{width:5px;height:5px;border-radius:50%;background:var(--accent);box-shadow:0 0 6px var(--accent)}
/* GRIDS */
.g3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:12px;margin-bottom:12px}
.g2r{display:grid;grid-template-columns:1fr 340px;gap:12px;margin-bottom:12px}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:12px}
/* BIGNUM */
.bignum{font-family:var(--display);font-size:44px;font-weight:800;line-height:1;margin:6px 0 4px}
.bignum.g{color:var(--accent);text-shadow:0 0 30px rgba(0,232,122,.15)}
.bignum.b{color:var(--blue);text-shadow:0 0 30px rgba(59,158,255,.15)}
.bignum.a{color:var(--amber);text-shadow:0 0 30px rgba(245,166,35,.15)}
.slbl{font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em}
/* MODULE BARS */
.mrow{
  display:flex;align-items:center;gap:8px;padding:6px 8px;border-radius:4px;
  cursor:pointer;transition:background .12s;margin-bottom:2px;
}
.mrow:hover:not(.ro){background:rgba(255,255,255,.04)}.mrow.ro{cursor:default}
.mid{font-size:9px;color:var(--blue);width:16px;flex-shrink:0;font-weight:700}
.mnm{font-size:11px;color:var(--muted2);width:130px;flex-shrink:0}
.bt{flex:1;height:4px;background:var(--border);border-radius:2px;overflow:hidden}
.bf{height:100%;border-radius:2px;transition:width .6s cubic-bezier(.23,1,.32,1)}
.bv{font-size:11px;width:30px;text-align:right;flex-shrink:0;font-weight:500}
.bbtn{
  font-size:9px;padding:2px 7px;border:1px solid var(--border2);border-radius:3px;
  color:var(--muted);cursor:pointer;transition:all .12s;flex-shrink:0;
}
.bbtn:hover{border-color:var(--blue);color:var(--blue)}
/* CYCLES */
.cyc-list{display:flex;flex-direction:column;gap:2px;max-height:320px;overflow-y:auto}
.cyc{
  display:flex;align-items:center;gap:8px;padding:7px 10px;border-radius:4px;
  border:1px solid transparent;cursor:pointer;transition:all .12s;
}
.cyc:hover{background:rgba(255,255,255,.03);border-color:var(--border)}
.cyc.active{border-color:var(--accent);background:rgba(0,232,122,.04)}
.cyc.done{opacity:.4}.cyc.locked{opacity:.22;cursor:default;pointer-events:none}
.cn{font-size:9px;color:var(--muted);width:18px;flex-shrink:0;font-weight:500}
.cnm{flex:1;font-size:11px;color:var(--muted2)}.cyc.active .cnm{color:var(--text)}
.tag{font-size:9px;padding:2px 7px;border-radius:3px;text-transform:uppercase;letter-spacing:.04em;flex-shrink:0;font-weight:600}
.tA{background:rgba(0,232,122,.12);color:var(--accent)}.tB{background:rgba(59,158,255,.12);color:var(--blue)}
.tC{background:rgba(255,75,110,.12);color:var(--red)}.tD{background:rgba(245,166,35,.12);color:var(--amber)}
.tE{background:rgba(167,139,250,.12);color:var(--purple)}.tF{background:rgba(103,232,249,.12);color:var(--cyan)}
.tP{background:rgba(255,255,255,.06);color:var(--muted2)}
.cdot{width:6px;height:6px;border-radius:50%;flex-shrink:0}
.don{background:var(--accent);box-shadow:0 0 8px var(--accent);animation:blink 1.5s infinite}
.ddone{background:var(--muted)}.dnext{border:1px solid var(--muted)}.dlock{border:1px solid var(--border)}
/* CYCLE DETAIL */
.det-title{font-family:var(--display);font-size:16px;font-weight:700;margin-bottom:4px}
.det-meta{font-size:10px;color:var(--muted);margin-bottom:14px;display:flex;gap:10px;flex-wrap:wrap}
.ssbl{font-size:9px;letter-spacing:.15em;text-transform:uppercase;color:var(--muted);margin:12px 0 6px}
.goal{font-size:11px;color:var(--muted2);line-height:1.7;border-left:2px solid var(--border2);padding-left:12px}
.exit-box{background:rgba(0,232,122,.04);border:1px solid rgba(0,232,122,.18);border-radius:4px;padding:14px;margin-top:12px}
.exit-lbl{font-size:9px;letter-spacing:.15em;text-transform:uppercase;color:var(--accent);margin-bottom:8px;display:flex;align-items:center;gap:6px}
.exit-item{display:flex;align-items:flex-start;gap:8px;padding:5px 0;font-size:11px;color:var(--muted2);border-bottom:1px solid rgba(0,232,122,.06);cursor:pointer}
.exit-item:last-child{border-bottom:none}.exit-item.ro{cursor:default}
.chk{width:14px;height:14px;border:1px solid rgba(0,232,122,.35);border-radius:3px;flex-shrink:0;margin-top:1px;display:flex;align-items:center;justify-content:center;font-size:9px;transition:all .12s;cursor:pointer}
.chk:hover{border-color:var(--accent)}.chk.done{background:var(--accent);border-color:var(--accent);color:var(--bg)}
.exit-ok{margin-top:10px;font-size:10px;color:var(--accent);display:none;align-items:center;gap:6px}
.exit-ok.show{display:flex}
/* OVERVIEW AVALIADOR */
.ov-grid{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:14px}
.ov-athlete{background:var(--bg2);border:1px solid var(--border);border-radius:6px;overflow:hidden;transition:border-color .15s}
.ov-athlete:hover{border-color:var(--border2)}
.ov-head{padding:16px 18px 14px;border-bottom:1px solid var(--border);display:flex;align-items:center;gap:12px;position:relative}
.ov-av{width:38px;height:38px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--display);font-size:15px;font-weight:800;flex-shrink:0}
.ov-name{font-family:var(--display);font-size:15px;font-weight:700}
.ov-meta{font-size:10px;color:var(--muted2);margin-top:2px}
.ov-pw-warn{display:inline-flex;align-items:center;gap:5px;font-size:9px;color:var(--amber);background:rgba(245,166,35,.08);border:1px solid rgba(245,166,35,.25);border-radius:2px;padding:3px 8px}
.ov-body{padding:16px 18px}
.ov-section{font-size:9px;letter-spacing:.15em;text-transform:uppercase;color:var(--muted);margin:0 0 8px;display:flex;align-items:center;gap:8px}
.ov-section::after{content:'';flex:1;height:1px;background:var(--border)}
.ov-stats-row{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:14px}
.ov-stat{text-align:center;padding:10px 6px;background:var(--bg3);border:1px solid var(--border);border-radius:4px}
.ov-stat-n{font-family:var(--display);font-size:24px;font-weight:800;line-height:1;margin-bottom:3px}
.ov-stat-l{font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.08em}
.ov-compare{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:14px}
.ov-col-lbl{font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin-bottom:8px}
.ov-mini-bar{display:flex;align-items:center;gap:6px;margin-bottom:5px}
.ov-mini-id{font-size:9px;color:var(--muted);width:12px;flex-shrink:0}
.ov-mini-track{flex:1;height:5px;background:var(--border);border-radius:3px;overflow:hidden;position:relative}
.ov-mini-fill{height:100%;border-radius:3px;transition:width .6s cubic-bezier(.23,1,.32,1)}
.ov-mini-val{font-size:10px;width:26px;text-align:right;flex-shrink:0;font-weight:500}
.ov-target-line{position:absolute;top:0;bottom:0;width:1px;background:rgba(255,255,255,.25)}
.ov-actions{display:flex;gap:8px;margin-top:14px;padding-top:12px;border-top:1px solid var(--border)}
.ov-btn{flex:1;padding:7px 4px;font-family:var(--mono);font-size:10px;border-radius:3px;cursor:pointer;transition:all .12s;text-align:center;letter-spacing:.03em}
.ov-summary{background:var(--bg3);border:1px solid var(--border);border-radius:4px;padding:14px 16px;margin-bottom:14px}
/* COACH PANEL melhorado */
.cp-sect{font-size:9px;letter-spacing:.15em;text-transform:uppercase;color:var(--muted);margin:16px 0 8px;display:flex;align-items:center;gap:8px}
.cp-sect::after{content:'';flex:1;height:1px;background:var(--border)}
/* CANAL SIDEBAR */
.ch-item{display:flex;align-items:center;gap:8px;padding:8px 10px;border-radius:4px;cursor:pointer;border:1px solid transparent;transition:all .12s;margin-bottom:3px}
.ch-item:hover{background:rgba(255,255,255,.03);border-color:var(--border)}
.ch-item.active{background:rgba(0,232,122,.05);border-color:var(--accent)}
.ch-dot{width:7px;height:7px;border-radius:50%;flex-shrink:0}
.ch-nm{font-size:11px;color:var(--muted2);flex:1}
.ch-item.active .ch-nm{color:var(--text);font-weight:500}
.ch-badge{font-size:9px;background:var(--accent);color:var(--bg);border-radius:10px;padding:1px 7px;flex-shrink:0;font-weight:700}
/* CHAT */
.chat-wrap{display:flex;flex-direction:column;gap:10px;max-height:420px;overflow-y:auto;padding:4px 0;margin-bottom:12px}
.msg-row{display:flex;gap:10px;align-items:flex-end}
.msg-row.mine{flex-direction:row-reverse}
.msg-av{width:28px;height:28px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--display);font-size:11px;font-weight:700;flex-shrink:0}
.msg-bubble{max-width:72%;padding:9px 14px;border-radius:12px;font-size:11px;line-height:1.6}
.msg-row.mine .msg-bubble{background:rgba(0,232,122,.12);border:1px solid rgba(0,232,122,.25);color:var(--text);border-bottom-right-radius:3px}
.msg-row:not(.mine) .msg-bubble{background:var(--bg3);border:1px solid var(--border2);color:var(--muted2);border-bottom-left-radius:3px}
.msg-meta{font-size:9px;color:var(--muted);margin-top:3px;display:flex;gap:6px}
.msg-row.mine .msg-meta{justify-content:flex-end}
.chat-input-wrap{display:flex;gap:8px}
.chat-inp{flex:1;background:var(--bg3);border:1px solid var(--border2);border-radius:24px;padding:10px 18px;color:var(--text);font-family:var(--mono);font-size:11px;outline:none;transition:border-color .12s}
.chat-inp:focus{border-color:var(--blue)}
.chat-inp::placeholder{color:var(--muted)}
.chat-send{background:rgba(0,232,122,.1);border:1px solid var(--accent);color:var(--accent);font-family:var(--mono);font-size:11px;padding:10px 20px;border-radius:24px;cursor:pointer;transition:all .12s;white-space:nowrap}
.chat-send:hover{background:rgba(0,232,122,.22)}
/* REVIEW */
.rev-q{display:flex;align-items:flex-start;gap:10px;padding:9px 0;border-bottom:1px solid rgba(255,255,255,.03);cursor:pointer;transition:background .1s}
.rev-q:hover{background:rgba(255,255,255,.02);border-radius:3px}
.rev-q:last-child{border-bottom:none}
.qb{width:16px;height:16px;border:1px solid var(--border2);border-radius:50%;flex-shrink:0;margin-top:1px;transition:all .15s;display:flex;align-items:center;justify-content:center;font-size:8px}
.rev-q:hover .qb{border-color:var(--accent)}
.rev-q.on .qb{background:rgba(0,232,122,.18);border-color:var(--accent);color:var(--accent)}
/* AGENDA */
.prova-item{display:flex;align-items:center;gap:12px;padding:12px 14px;background:var(--bg3);border:1px solid var(--border);border-radius:5px;margin-bottom:8px;transition:all .12s}
.prova-item:hover{border-color:var(--border2)}
.prova-date{font-family:var(--display);font-size:22px;font-weight:800;color:var(--accent);min-width:34px;text-align:center;line-height:1}
.prova-month{font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.08em;margin-top:3px;text-align:center}
.prova-info{flex:1}
.prova-nm{font-size:12px;color:var(--text);font-weight:600}
.prova-loc{font-size:10px;color:var(--muted2);margin-top:2px}
.prova-tag{font-size:9px;padding:3px 9px;border-radius:3px;text-transform:uppercase;letter-spacing:.06em;flex-shrink:0;font-weight:600}
.prova-del{font-size:10px;padding:4px 9px;border:1px solid var(--border);border-radius:3px;color:var(--muted);cursor:pointer;transition:all .12s;flex-shrink:0}
.prova-del:hover{border-color:var(--red);color:var(--red)}
/* WEEK */
.wk-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:10px}
.day-card{border-radius:5px;padding:14px;border:1px solid var(--border);transition:border-color .12s}
.day-card:hover{border-color:var(--border2)}
.day-nm{font-size:9px;letter-spacing:.12em;text-transform:uppercase;margin-bottom:8px;font-weight:700}
/* COACH PANEL */
.cg{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.ath-card{background:var(--bg2);border:1px solid var(--border);border-radius:6px;padding:20px;transition:border-color .15s}
.ath-card:hover{border-color:var(--border2)}
.ath-hdr{display:flex;align-items:center;gap:12px;margin-bottom:18px;padding-bottom:14px;border-bottom:1px solid var(--border)}
.ath-av{width:42px;height:42px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--display);font-size:16px;font-weight:700;flex-shrink:0}
.ath-nm{font-family:var(--display);font-size:16px;font-weight:700}
.ath-meta{font-size:10px;color:var(--muted);margin-top:2px}
.ta{width:100%;background:var(--bg);border:1px solid var(--border);border-radius:4px;padding:10px 12px;color:var(--text);font-family:var(--mono);font-size:11px;resize:vertical;min-height:72px;outline:none;transition:border-color .12s;margin-top:8px}
.ta:focus{border-color:var(--blue)}
.abtn{
  margin-top:8px;padding:9px 16px;font-family:var(--mono);font-size:11px;
  border-radius:4px;cursor:pointer;transition:all .15s;width:100%;display:block;
  text-align:center;font-weight:500;letter-spacing:.03em;
}
.btn-g{background:rgba(0,232,122,.08);border:1px solid rgba(0,232,122,.4);color:var(--accent)}
.btn-g:hover{background:rgba(0,232,122,.16);border-color:var(--accent)}
.btn-b{background:rgba(59,158,255,.08);border:1px solid rgba(59,158,255,.4);color:var(--blue)}
.btn-b:hover{background:rgba(59,158,255,.16);border-color:var(--blue)}
.btn-r{background:rgba(255,75,110,.08);border:1px solid rgba(255,75,110,.4);color:var(--red)}
.btn-r:hover{background:rgba(255,75,110,.16);border-color:var(--red)}
.btn-a{background:rgba(245,166,35,.08);border:1px solid rgba(245,166,35,.4);color:var(--amber)}
.btn-a:hover{background:rgba(245,166,35,.16);border-color:var(--amber)}
.btn-pu{background:rgba(167,139,250,.08);border:1px solid rgba(167,139,250,.4);color:var(--purple)}
.btn-pu:hover{background:rgba(167,139,250,.16);border-color:var(--purple)}
.small-ok{font-size:10px;color:var(--accent);height:16px;margin-top:5px}
.warn-badge{font-size:10px;color:var(--amber);background:rgba(245,166,35,.08);border:1px solid rgba(245,166,35,.25);border-radius:4px;padding:6px 10px;margin-bottom:10px}
/* SYNC / JSON BLOCK */
.json-block{background:var(--bg);border:1px solid var(--border);border-radius:4px;padding:12px;font-size:10px;color:var(--muted2);word-break:break-all;max-height:120px;overflow-y:auto;margin-top:8px;position:relative;font-family:var(--mono)}
.copy-btn{position:absolute;top:8px;right:8px;padding:3px 10px;background:var(--bg2);border:1px solid var(--border2);color:var(--muted2);font-family:var(--mono);font-size:10px;border-radius:3px;cursor:pointer;transition:all .12s}
.copy-btn:hover{border-color:var(--accent);color:var(--accent)}
/* MODAL */
.backdrop{position:fixed;inset:0;background:rgba(0,0,0,.75);display:flex;align-items:center;justify-content:center;z-index:100;opacity:0;pointer-events:none;transition:opacity .18s}
.backdrop.open{opacity:1;pointer-events:all}
.modal{background:var(--bg3);border:1px solid var(--border2);border-radius:5px;padding:22px;width:340px;transform:translateY(10px);transition:transform .18s}
.backdrop.open .modal{transform:translateY(0)}
.modal h3{font-family:var(--display);font-size:16px;margin-bottom:3px}
.modal p{font-size:11px;color:var(--muted2);margin-bottom:16px}
.sl-wrap{display:flex;align-items:center;gap:12px;margin-bottom:14px}
.sl-wrap input[type=range]{flex:1;-webkit-appearance:none;height:3px;background:var(--border);border-radius:2px;outline:none}
.sl-wrap input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:14px;height:14px;border-radius:50%;background:var(--accent);cursor:pointer;box-shadow:0 0 8px rgba(0,232,122,.4)}
.sval{font-family:var(--display);font-size:26px;font-weight:800;color:var(--accent);width:32px}
.sdesc{font-size:10px;color:var(--muted);margin-bottom:14px;min-height:28px}
.mbns{display:flex;gap:8px;justify-content:flex-end}
.mbtn{padding:8px 18px;border-radius:3px;font-family:var(--mono);font-size:11px;cursor:pointer;transition:all .12s}
.mbtn-c{background:transparent;border:1px solid var(--border);color:var(--muted2)}
.mbtn-c:hover{border-color:var(--red);color:var(--red)}
.mbtn-s{background:rgba(0,232,122,.1);border:1px solid var(--accent);color:var(--accent)}
.mbtn-s:hover{background:rgba(0,232,122,.2)}
::-webkit-scrollbar{width:3px;height:3px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:var(--border2);border-radius:2px}
footer{margin-top:20px;padding-top:14px;border-top:1px solid var(--border);display:flex;justify-content:space-between;font-size:9px;color:var(--muted);letter-spacing:.06em}
.mood-btn{font-size:16px;cursor:pointer;opacity:.35;transition:all .15s;padding:3px 5px;border-radius:3px}
.mood-btn:hover,.mood-btn.active{opacity:1;background:rgba(255,255,255,.06)}
</style>
</head>
<body>

<!-- LOGIN -->
<div class="screen active" id="s-login">
  <div class="box">
    <div class="box-logo">Planejamento</div>
    <div class="box-sub">WorldSkills #54 — Cyber Security</div>
    <div style="font-size:10px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin-bottom:10px">Selecionar usuário</div>
    <div class="user-pills" id="user-pills"></div>
    <div class="divider"></div>
    <div class="lbl">Senha</div>
    <input class="inp" type="password" id="pw-inp" placeholder="••••••••">
    <div class="err-msg" id="login-err"></div>
    <button class="primary-btn" onclick="doLogin()">ENTRAR</button>
    <div style="margin-top:14px;font-size:10px;color:var(--muted);text-align:center">WSC #54 · Acesso restrito</div>
  </div>
</div>

<!-- PRIMEIRO LOGIN -->
<div class="screen" id="s-firstpw">
  <div class="box">
    <div class="box-logo">Planejamento</div>
    <div class="box-sub" id="fpw-sub">Primeiro acesso — definir senha</div>
    <div style="font-size:11px;color:var(--muted2);margin-bottom:16px;line-height:1.7">Defina uma senha pessoal para continuar.</div>
    <div class="lbl">Nova senha</div>
    <input class="inp" type="password" id="np1" placeholder="mínimo 8 caracteres" oninput="chkNewPw()">
    <div class="lbl">Confirmar senha</div>
    <input class="inp" type="password" id="np2" placeholder="repetir nova senha" oninput="chkNewPw()">
    <div class="pw-hint">Mínimo <em>8 caracteres</em>, <em>1 número</em> e <em>1 maiúscula</em>.</div>
    <div class="err-msg" id="fpw-err"></div>
    <button class="primary-btn" id="fpw-btn" onclick="doFirstPw()" disabled>DEFINIR SENHA</button>
  </div>
</div>

<!-- TROCAR SENHA -->
<div class="screen" id="s-changepw">
  <div class="box">
    <div class="box-logo">Planejamento</div>
    <div class="box-sub" id="cpw-sub">Alterar senha</div>
    <div class="lbl">Senha atual</div>
    <input class="inp" type="password" id="cp0" placeholder="••••••••">
    <div class="lbl">Nova senha</div>
    <input class="inp" type="password" id="cp1" placeholder="mínimo 8 caracteres" oninput="chkCpw()">
    <div class="lbl">Confirmar nova senha</div>
    <input class="inp" type="password" id="cp2" placeholder="repetir" oninput="chkCpw()">
    <div class="pw-hint">Mínimo 8 caracteres, 1 número, 1 maiúscula.</div>
    <div class="err-msg" id="cpw-err"></div>
    <div class="ok-msg" id="cpw-ok"></div>
    <button class="primary-btn" id="cpw-btn" onclick="doChPw()" disabled>SALVAR NOVA SENHA</button>
    <button class="secondary-btn" onclick="cancelCpw()">CANCELAR</button>
  </div>
</div>

<!-- APP -->
<div id="app">
<div class="app">
<header>
  <div>
    <div class="logo">Planejamento</div>
    <div class="logo-sub" id="app-sub">—</div>
  </div>
  <div class="hdr-r">
    <div class="ubadge"><div class="bdot" id="bdot"></div><span id="buser" style="font-size:11px"></span></div>
    <button class="hbtn blue" onclick="goChPw()">⚿ Senha</button>
    <button class="hbtn red" onclick="doLogout()">SAIR</button>
  </div>
</header>
<div class="tabs" id="tabs-bar"></div>

<!-- ── DASHBOARD ── -->
<div class="view" id="v-dashboard">
  <!-- FEEDBACK + META DO DIA (competidores) -->
  <div id="coach-info-block" style="margin-bottom:10px;display:none"></div>

  <!-- OVERVIEW DO AVALIADOR -->
  <div id="coach-overview" style="display:none"></div>

  <!-- VISÃO DO COMPETIDOR -->
  <div id="athlete-view" style="display:none">
    <!-- Banner senha padrão -->
    <div id="pw-default-banner" style="display:none;align-items:center;gap:12px;padding:12px 16px;background:rgba(245,166,35,.08);border:1px solid rgba(245,166,35,.3);border-radius:5px;margin-bottom:12px">
      <span style="font-size:16px">⚠</span>
      <div style="flex:1">
        <div style="font-size:12px;color:var(--amber);font-weight:600">Você está usando a senha padrão</div>
        <div style="font-size:11px;color:var(--muted2);margin-top:2px">Defina uma senha pessoal para proteger sua conta.</div>
      </div>
      <button onclick="goChPw()" style="background:rgba(245,166,35,.12);border:1px solid rgba(245,166,35,.4);color:var(--amber);font-family:var(--mono);font-size:11px;padding:7px 14px;border-radius:4px;cursor:pointer;white-space:nowrap;flex-shrink:0">Trocar agora</button>
    </div>
    <div class="g3">
      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Ciclo Atual</div>
        <div class="bignum g" id="s-cycle">1</div>
        <div class="slbl">de 21 ciclos</div>
        <div style="font-size:11px;color:var(--muted2);margin-top:10px" id="s-cname"></div>
      </div>
      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Nota do Avaliador</div>
        <div class="bignum b" id="s-avg-coach">—</div>
        <div class="slbl">média publicada</div>
        <div style="height:3px;background:var(--border);border-radius:2px;overflow:hidden;margin-top:10px"><div id="avg-bar-c" style="height:100%;background:var(--blue);border-radius:2px;width:0%;transition:width .6s"></div></div>
      </div>
      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Progresso</div>
        <div class="bignum a" id="s-week">1</div>
        <div class="slbl" id="s-pct">semana de ~84</div>
        <div style="height:3px;background:var(--border);border-radius:2px;overflow:hidden;margin-top:10px"><div id="prog-bar" style="height:100%;background:var(--amber);border-radius:2px;width:1%;transition:width .6s"></div></div>
      </div>
    </div>
    <div class="g2r">
      <div style="display:flex;flex-direction:column;gap:10px">
        <div class="card">
          <div class="clabel"><div class="clabel-dot"></div>Auto-avaliação <span id="self-hint" style="color:var(--muted)"></span></div>
          <div id="self-bars"></div>
        </div>
        <div class="card" id="coach-eval-card" style="display:none">
          <div class="clabel"><div class="clabel-dot" style="background:var(--purple);box-shadow:0 0 5px var(--purple)"></div>Avaliação do Treinador <span style="color:var(--muted);font-size:9px" id="coach-eval-date"></span></div>
          <div id="coach-bars"></div>
        </div>
        <div class="card" id="msg-dia-card" style="display:none">
          <div class="clabel"><div class="clabel-dot" style="background:var(--amber);box-shadow:0 0 5px var(--amber)"></div>Mensagem do Dia</div>
          <div id="msg-do-dia" style="font-size:11px;color:var(--muted2);line-height:1.7;font-style:italic"></div>
        </div>
      </div>
      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Ciclos <span id="cyc-hint" style="color:var(--muted)"></span></div>
        <div class="cyc-list" id="cyc-list"></div>
      </div>
    </div>
    <div class="g2">
      <div class="card">
        <div class="clabel"><div class="clabel-dot" style="background:var(--amber);box-shadow:0 0 5px var(--amber)"></div>Revisão de Sexta</div>
        <div style="font-size:11px;color:var(--muted);margin-bottom:10px;font-style:italic">As três precisam ser sim para a semana contar.</div>
        <div id="rev-items"></div>
        <div style="margin-top:10px;display:flex;justify-content:space-between;align-items:center">
          <div id="rev-status" style="font-size:11px;color:var(--muted)">0/3</div>
          <button class="hbtn" onclick="clearRev()" style="font-size:9px;padding:3px 9px">↺ reset</button>
        </div>
      </div>
      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Regras de Operação</div>
        <div id="rules-list"></div>
      </div>
    </div>
    <div id="status-log-box" style="margin-top:10px;display:none"></div>
  </div>
</div>

<!-- ── CICLOS ── -->
<div class="view" id="v-cycles">
  <div style="display:grid;grid-template-columns:240px 1fr;gap:12px">
    <div class="card" style="padding:12px">
      <div class="clabel"><div class="clabel-dot"></div>Ciclos</div>
      <div class="cyc-list" id="cyc-list2"></div>
    </div>
    <div class="card">
      <div class="det-title" id="d-title">—</div>
      <div class="det-meta" id="d-meta"></div>
      <div class="ssbl">Objetivo</div>
      <div class="goal" id="d-goal"></div>
      <div class="ssbl">Tarefas</div>
      <div id="d-tasks"></div>
      <div class="exit-box">
        <div class="exit-lbl"><div style="width:5px;height:5px;border-radius:50%;background:var(--accent);box-shadow:0 0 5px var(--accent)"></div>CRITÉRIO DE SAÍDA</div>
        <div id="d-exits"></div>
        <div class="exit-ok" id="d-ok"><span>◆</span><span>Ciclo completo. Duplo-clique no ativo para avançar.</span></div>
      </div>
      <div style="margin-top:10px;font-size:10px;color:var(--muted)">DESBLOQUEIO: <span id="d-unlock" style="color:var(--accent)"></span></div>
    </div>
  </div>
</div>

<!-- ── CHAT ── -->
<div class="view" id="v-chat">
  <div style="display:grid;grid-template-columns:200px 1fr 220px;gap:12px">

    <!-- SIDEBAR: lista de canais -->
    <div style="display:flex;flex-direction:column;gap:8px">
      <div class="card" style="padding:14px">
        <div class="clabel" style="margin-bottom:10px"><div class="clabel-dot"></div>Canais</div>
        <div id="channel-list"></div>
      </div>
      <!-- LOG DE STATUS -->
      <div id="chat-status-log" style="display:none"></div>
    </div>

    <!-- JANELA DO CANAL ATIVO -->
    <div class="card">
      <div class="clabel" id="chat-channel-label"><div class="clabel-dot"></div>—</div>
      <div class="chat-wrap" id="chat-msgs"></div>
      <div class="chat-input-wrap">
        <input class="chat-inp" id="chat-inp" placeholder="Mensagem..." onkeydown="chatKey(event)">
        <button class="chat-send" onclick="sendChat()">↵ Enviar</button>
      </div>
    </div>

    <!-- PAINEL LATERAL DIREITO -->
    <div style="display:flex;flex-direction:column;gap:10px">
      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Humor do Dia</div>
        <div style="display:flex;gap:4px;margin-bottom:8px">
          <div class="mood-btn" onclick="setMood(this,'😤')">😤</div>
          <div class="mood-btn" onclick="setMood(this,'😐')">😐</div>
          <div class="mood-btn" onclick="setMood(this,'🙂')">🙂</div>
          <div class="mood-btn" onclick="setMood(this,'🔥')">🔥</div>
        </div>
        <div id="mood-msg" style="font-size:10px;color:var(--muted)"></div>
      </div>
      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>7 Dias</div>
        <div id="heatmap" style="display:flex;gap:4px;margin-bottom:6px"></div>
        <div style="font-size:9px;color:var(--muted)">■ = dia ativo</div>
      </div>
      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Sequência</div>
        <div style="font-family:var(--display);font-size:34px;font-weight:800;color:var(--amber)" id="streak-n">0</div>
        <div style="font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em">dias seguidos</div>
        <div style="font-size:10px;color:var(--muted2);margin-top:6px" id="streak-m"></div>
      </div>
    </div>

  </div>
</div>

<!-- ── AGENDA ── -->
<div class="view" id="v-agenda">
  <div style="display:grid;grid-template-columns:1fr 320px;gap:12px">
    <div>
      <div class="card">
        <div class="clabel"><div class="clabel-dot" style="background:var(--purple);box-shadow:0 0 5px var(--purple)"></div>Próximas Provas</div>
        <div id="provas-list"><div style="font-size:11px;color:var(--muted);font-style:italic">Nenhuma prova cadastrada.</div></div>
      </div>
    </div>
    <div class="card" id="prova-add-card" style="display:none">
      <div class="clabel"><div class="clabel-dot"></div>Adicionar Prova</div>
      <div class="lbl" style="margin-top:0">Nome</div>
      <input class="inp" id="prova-nm" placeholder="Ex: Estadual 2025">
      <div class="lbl">Data</div>
      <input class="inp" type="date" id="prova-dt">
      <div class="lbl">Local</div>
      <input class="inp" id="prova-loc" placeholder="Ex: SENAI SP">
      <div class="lbl">Tipo</div>
      <select class="inp" id="prova-tipo" style="cursor:pointer">
        <option value="estadual">Estadual</option>
        <option value="nacional">Nacional</option>
        <option value="mundial">Mundial</option>
        <option value="simulado">Simulado</option>
        <option value="outro">Outro</option>
      </select>
      <button class="abtn btn-g" style="margin-top:12px" onclick="addProva()">+ Adicionar</button>
      <div class="small-ok" id="prova-ok"></div>
    </div>
  </div>
</div>

<!-- ── ROTINA ── -->
<div class="view" id="v-week">
  <div style="display:flex;flex-direction:column;gap:12px">
    <div class="card">
      <div class="clabel"><div class="clabel-dot"></div>Bloco Diário — 08h às 18h</div>
      <div id="bloco-diario"></div>
    </div>
    <div class="card">
      <div class="clabel"><div class="clabel-dot"></div>Rotina Semanal</div>
      <div class="wk-grid" id="rotina-semanal"></div>
    </div>
  </div>
</div>

<!-- ── CONFIGURAÇÕES (só avaliador) ── -->
<div class="view" id="v-config">
  <div style="display:grid;grid-template-columns:1fr 1fr;gap:14px;margin-bottom:14px">

    <!-- COL 1 -->
    <div style="display:flex;flex-direction:column;gap:14px">

      <div class="card">
        <div class="clabel"><div class="clabel-dot" style="background:var(--amber);box-shadow:0 0 5px var(--amber)"></div>Mensagem do Dia</div>
        <div style="font-size:11px;color:var(--muted2);margin-bottom:8px">Aparece no dashboard de todos os competidores.</div>
        <textarea class="ta" id="cfg-msg-dia" placeholder="Mensagem de hoje para os competidores..." style="min-height:72px"></textarea>
        <button class="abtn btn-a" onclick="cfgSaveMsgDia()">Salvar Mensagem do Dia</button>
        <div class="small-ok" id="cfg-msg-ok"></div>
      </div>

      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Regras de Operação</div>
        <div style="font-size:11px;color:var(--muted2);margin-bottom:8px">Uma regra por linha. Aparece no dashboard de todos.</div>
        <textarea class="ta" id="cfg-rules" style="min-height:120px"></textarea>
        <button class="abtn btn-b" onclick="cfgSaveRules()">Salvar Regras</button>
        <div class="small-ok" id="cfg-rules-ok"></div>
      </div>

      <div class="card">
        <div class="clabel"><div class="clabel-dot" style="background:var(--cyan);box-shadow:0 0 5px var(--cyan)"></div>Bloco Diário</div>
        <div style="font-size:11px;color:var(--muted2);margin-bottom:8px">
          JSON array — cada item: <code style="color:var(--amber)">{"time":"HH:MM–HH:MM","cor":"#hex","txt":"..."}</code><br>
          Use <code style="color:var(--muted2)">null</code> em <code>cor</code> para sem destaque.
        </div>
        <textarea class="ta" id="cfg-bloco" style="min-height:160px;font-size:10px"></textarea>
        <button class="abtn btn-g" onclick="cfgSaveBloco()">Salvar Bloco Diário</button>
        <div class="small-ok" id="cfg-bloco-ok"></div>
      </div>

    </div>

    <!-- COL 2 -->
    <div style="display:flex;flex-direction:column;gap:14px">

      <div class="card">
        <div class="clabel"><div class="clabel-dot" style="background:var(--purple);box-shadow:0 0 5px var(--purple)"></div>Rotina Semanal</div>
        <div style="font-size:11px;color:var(--muted2);margin-bottom:8px">
          JSON array — cada item: <code style="color:var(--amber)">{"day":"...","cor":"#hex","mod":"...","sub":"...","nota":"..."}</code>
        </div>
        <textarea class="ta" id="cfg-semanal" style="min-height:160px;font-size:10px"></textarea>
        <button class="abtn btn-pu" onclick="cfgSaveSemanal()">Salvar Rotina Semanal</button>
        <div class="small-ok" id="cfg-semanal-ok"></div>
      </div>

      <div class="card">
        <div class="clabel"><div class="clabel-dot" style="background:var(--blue);box-shadow:0 0 5px var(--blue)"></div>Metas e Feedback por Competidor</div>
        <div id="cfg-per-athlete"></div>
      </div>

      <div class="card">
        <div class="clabel"><div class="clabel-dot"></div>Resetar para Padrões</div>
        <div style="font-size:11px;color:var(--muted2);margin-bottom:10px">Restaura mensagem, regras, bloco e rotina para os valores originais. Não afeta os ciclos.</div>
        <button class="abtn btn-r" onclick="cfgResetAll()">⚠ Resetar Configurações</button>
      </div>

    </div>
  </div>

  <!-- EDITOR DE CICLOS (full-width) -->
  <div class="card">
    <div class="clabel"><div class="clabel-dot" style="background:var(--accent);box-shadow:0 0 5px var(--accent)"></div>
      Ciclos — Editar Nome, Conteúdo e Sequência
      <span style="color:var(--muted);font-size:9px">· alterações afetam todos os competidores</span>
    </div>
    <div style="font-size:11px;color:var(--muted2);margin-bottom:12px">
      Clique em qualquer ciclo para editar. Arraste para reordenar. As edições substituem os valores padrão.
    </div>
    <div style="display:flex;gap:8px;margin-bottom:12px;flex-wrap:wrap">
      <button class="abtn btn-r" onclick="cfgResetCycles()" style="width:auto;padding:6px 14px;margin-top:0;font-size:10px">↺ Restaurar ciclos padrão</button>
      <div class="small-ok" id="cfg-cyc-ok" style="align-self:center;margin-top:0"></div>
    </div>
    <div id="cfg-cycles-list"></div>
  </div>
</div>

<!-- ── PAINEL TREINADOR ── -->
<div class="view" id="v-coach">
  <div style="margin-bottom:14px">
    <div style="font-size:10px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin-bottom:6px">Painel do Avaliador</div>
    <div style="font-size:11px;color:var(--muted2)">Avalie módulos, publique feedback e gerencie senhas.</div>
  </div>
  <div class="cg" id="coach-grid"></div>
</div>

<footer>
  <span>Planejamento · WSC #54 · <span id="footer-user">—</span></span>
  <span id="footer-date"></span>
</footer>
</div>
</div>

<!-- MODAL MÓDULO -->
<div class="backdrop" id="mod-bg" onclick="closeMod(event)">
  <div class="modal">
    <h3 id="m-title">Módulo</h3>
    <p id="m-sub"></p>
    <div class="sl-wrap">
      <input type="range" min="0" max="10" step="1" id="m-sl" oninput="slMv(this.value)">
      <div class="sval" id="m-val">0</div>
    </div>
    <div class="sdesc" id="m-desc"></div>
    <div class="mbns">
      <button class="mbtn mbtn-c" onclick="closeMod()">Cancelar</button>
      <button class="mbtn mbtn-s" id="m-save" onclick="saveLevel()">Salvar</button>
    </div>
  </div>
</div>

<script>
// ════════════════════════════════════════════════════════════════════
// CRYPTO
// ════════════════════════════════════════════════════════════════════

async function sha256(s){
  const b=await crypto.subtle.digest('SHA-256',new TextEncoder().encode(s));
  return Array.from(new Uint8Array(b)).map(x=>x.toString(16).padStart(2,'0')).join('');
}
function genSalt(){
  const a=new Uint8Array(16);crypto.getRandomValues(a);
  return Array.from(a).map(x=>x.toString(16).padStart(2,'0')).join('');
}
async function hashPw(pw,salt){return await sha256(salt+':'+pw);}
async function verifyPw(pw,stored){return(await hashPw(pw,stored.salt))===stored.hash;}

// ════════════════════════════════════════════════════════════════════
// USERS
// ════════════════════════════════════════════════════════════════════

const USERS=[
  {id:'raul',    name:'Raul Cambiatti',   role:'Competidor',color:'#00e87a'},
  {id:'antonio', name:'Antonio Cerdeira', role:'Competidor',color:'#3b9eff'},
  {id:'thiago',  name:'Thiago',           role:'Avaliador', color:'#f5a623'},
];
const isCoach=uid=>uid==='thiago';

const pwKey =uid=>'pw_'+uid;
const flKey =uid=>'fl_'+uid;
const stKey =uid=>'oplog_'+uid;
const shKey =k=>'sh_'+k;   // shared data keys

function loadPw(uid){try{return JSON.parse(localStorage.getItem(pwKey(uid)));}catch{return null;}}
function savePw(uid,s){localStorage.setItem(pwKey(uid),JSON.stringify(s));}
async function ensureDefault(uid){
  if(!loadPw(uid)){
    const salt=genSalt(),hash=await hashPw(uid+'123',salt);
    savePw(uid,{hash,salt});
    localStorage.setItem(flKey(uid),'pending');
  }
}
function isFirstLogin(uid){return localStorage.getItem(flKey(uid))==='pending';}
function clearFirstLogin(uid){localStorage.setItem(flKey(uid),'done');}
async function resetPw(uid){
  const salt=genSalt(),hash=await hashPw(uid+'123',salt);
  savePw(uid,{hash,salt});
  localStorage.setItem(flKey(uid),'pending');
}
function validatePw(pw){
  if(pw.length<8)return'Mínimo 8 caracteres.';
  if(!/[0-9]/.test(pw))return'Precisa ter pelo menos 1 número.';
  if(!/[A-Z]/.test(pw))return'Precisa ter pelo menos 1 maiúscula.';
  return null;
}

// Shared state (visible to all users)
function loadShared(k){try{return JSON.parse(localStorage.getItem(shKey(k))||'null');}catch{return null;}}
function saveShared(k,v){localStorage.setItem(shKey(k),JSON.stringify(v));}

// Per-user state
function loadSt(uid){
  try{
    const s=JSON.parse(localStorage.getItem(stKey(uid))||'{}');
    return{
      levels:   s.levels   ||{A:0,B:0,C:0,D:0,E:0,F:0},
      cycle:    s.cycle    ||1,
      exits:    s.exits    ||{},
      review:   s.review   ||[false,false,false],
      mood:     s.mood     ||{},
    };
  }catch{
    return{levels:{A:0,B:0,C:0,D:0,E:0,F:0},cycle:1,exits:{},review:[false,false,false],mood:{}};
  }
}
function saveSt(uid,st){try{localStorage.setItem(stKey(uid),JSON.stringify(st));}catch{}}

// ════════════════════════════════════════════════════════════════════
// SCREENS
// ════════════════════════════════════════════════════════════════════

function showScreen(id){
  document.querySelectorAll('.screen').forEach(s=>{s.style.display='none';s.classList.remove('active');});
  document.getElementById('app').style.display='none';
  if(id==='app'){document.getElementById('app').style.display='block';}
  else{const el=document.getElementById('s-'+id);if(el){el.style.display='flex';el.classList.add('active');}}
}

// ════════════════════════════════════════════════════════════════════
// SESSION
// ════════════════════════════════════════════════════════════════════

let SEL=null,SES=null,ST=null,sCyc=1;

function renderLoginUsers(){
  document.getElementById('user-pills').innerHTML=USERS.map(u=>{
    const pending=isFirstLogin(u.id);
    return`<div class="user-pill" id="pill-${u.id}" onclick="selU('${u.id}')">
      <div class="uav" style="background:${u.color}22;border:1px solid ${u.color}44;color:${u.color}">${u.name[0]}</div>
      <div style="flex:1">
        <div style="font-size:12px;color:var(--text)">${u.name}</div>
        <div style="font-size:10px;color:var(--muted)">${u.role}</div>
      </div>
      ${pending?`<span style="font-size:9px;color:var(--amber);background:rgba(245,166,35,.1);border:1px solid rgba(245,166,35,.3);border-radius:3px;padding:2px 7px;white-space:nowrap">senha padrão</span>`:''}
    </div>`;
  }).join('');
}

function selU(id){
  SEL=id;
  document.querySelectorAll('.user-pill').forEach(p=>p.classList.remove('selected'));
  document.getElementById('pill-'+id).classList.add('selected');
  document.getElementById('pw-inp').focus();
  document.getElementById('login-err').textContent='';
}

async function doLogin(){
  if(!SEL){document.getElementById('login-err').textContent='Selecione um usuário.';return;}
  const pw=document.getElementById('pw-inp').value;
  if(!pw){document.getElementById('login-err').textContent='Digite a senha.';return;}
  const stored=loadPw(SEL);
  if(!stored){document.getElementById('login-err').textContent='Erro. Recarregue.';return;}
  const ok=await verifyPw(pw,stored);
  if(!ok){
    document.getElementById('login-err').textContent='Senha incorreta.';
    document.getElementById('pw-inp').value='';
    document.getElementById('pw-inp').focus();
    return;
  }
  SES={user:USERS.find(u=>u.id===SEL)};
  ST=loadSt(SEL);
  sCyc=ST.cycle;
  document.getElementById('pw-inp').value='';
  if(isFirstLogin(SEL)){
    // Mostrar aviso de senha padrão na tela de first-login
    document.getElementById('fpw-sub').textContent=`Primeiro acesso — ${SES.user.name.split(' ')[0]}`;
    document.getElementById('np1').value='';
    document.getElementById('np2').value='';
    document.getElementById('fpw-err').textContent='';
    document.getElementById('fpw-btn').disabled=true;
    showScreen('firstpw');
    document.getElementById('np1').focus();
  }else{startApp();}
}

function doLogout(){
  SES=null;ST=null;SEL=null;
  document.querySelectorAll('.user-pill').forEach(p=>p.classList.remove('selected'));
  document.getElementById('pw-inp').value='';
  document.getElementById('login-err').textContent='';
  showScreen('login');
}

// ════════════════════════════════════════════════════════════════════
// FIRST LOGIN
// ════════════════════════════════════════════════════════════════════

function chkNewPw(){
  const p1=document.getElementById('np1').value,p2=document.getElementById('np2').value;
  document.getElementById('fpw-btn').disabled=!(!validatePw(p1)&&p1===p2&&p2.length>0);
}

async function doFirstPw(){
  const p1=document.getElementById('np1').value,p2=document.getElementById('np2').value;
  const err=validatePw(p1);
  if(err){document.getElementById('fpw-err').textContent=err;return;}
  if(p1!==p2){document.getElementById('fpw-err').textContent='Senhas não coincidem.';return;}
  const salt=genSalt(),hash=await hashPw(p1,salt);
  savePw(SES.user.id,{hash,salt});
  clearFirstLogin(SES.user.id);
  startApp();
}

// ════════════════════════════════════════════════════════════════════
// CHANGE PASSWORD
// ════════════════════════════════════════════════════════════════════

function goChPw(){
  document.getElementById('cpw-sub').textContent=`Alterar senha — ${SES.user.name}`;
  ['cp0','cp1','cp2'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('cpw-err').textContent='';
  document.getElementById('cpw-ok').textContent='';
  document.getElementById('cpw-btn').disabled=true;
  showScreen('changepw');
}

function cancelCpw(){showScreen('app');buildTabs();switchTab('dashboard');}

function chkCpw(){
  const p1=document.getElementById('cp1').value,p2=document.getElementById('cp2').value;
  document.getElementById('cpw-btn').disabled=!(!validatePw(p1)&&p1===p2&&p2.length>0);
}

async function doChPw(){
  const old=document.getElementById('cp0').value;
  const p1=document.getElementById('cp1').value,p2=document.getElementById('cp2').value;
  document.getElementById('cpw-err').textContent='';
  document.getElementById('cpw-ok').textContent='';
  const stored=loadPw(SES.user.id);
  if(!(await verifyPw(old,stored))){document.getElementById('cpw-err').textContent='Senha atual incorreta.';return;}
  const err=validatePw(p1);
  if(err){document.getElementById('cpw-err').textContent=err;return;}
  if(p1!==p2){document.getElementById('cpw-err').textContent='Senhas não coincidem.';return;}
  const salt=genSalt(),hash=await hashPw(p1,salt);
  savePw(SES.user.id,{hash,salt});
  document.getElementById('cpw-ok').textContent='✓ Senha alterada.';
  ['cp0','cp1','cp2'].forEach(id=>document.getElementById(id).value='');
  setTimeout(()=>cancelCpw(),1200);
}

// ════════════════════════════════════════════════════════════════════
// APP START
// ════════════════════════════════════════════════════════════════════

function startApp(){
  showScreen('app');
  const u=SES.user;
  document.getElementById('bdot').style.background=u.color;
  document.getElementById('buser').textContent=u.name;
  document.getElementById('app-sub').textContent=`WorldSkills #54 · ${u.role}`;
  document.getElementById('footer-user').textContent=u.name;
  document.getElementById('footer-date').textContent=
    new Date().toLocaleDateString('pt-BR',{weekday:'long',year:'numeric',month:'long',day:'numeric'});
  buildTabs();
  switchTab('dashboard');
}

function buildTabs(){
  const coach=isCoach(SES.user.id);
  const ts=[
    {id:'dashboard',l:'Dashboard'},{id:'cycles',l:'Ciclos'},
    {id:'chat',l:'Chat'},{id:'agenda',l:'Agenda'},
    {id:'week',l:'Rotina'},
  ];
  if(coach){
    ts.push({id:'config',l:'Configurações'});
    ts.push({id:'coach',l:'Painel Avaliador'});
  }
  document.getElementById('tabs-bar').innerHTML=ts.map(t=>
    `<div class="tab" data-tab="${t.id}" onclick="switchTab('${t.id}')">${t.l}</div>`
  ).join('');
}

function switchTab(t){
  document.querySelectorAll('.tab').forEach(el=>el.classList.toggle('active',el.dataset.tab===t));
  document.querySelectorAll('.view').forEach(el=>el.classList.remove('active'));
  const v=document.getElementById('v-'+t);if(v)v.classList.add('active');
  if(t==='dashboard')renderDash();
  if(t==='cycles'){renderCycList('cyc-list2');renderCycDet(sCyc);}
  if(t==='chat')renderChat();
  if(t==='agenda')renderAgenda();
  if(t==='week')renderWeek();
  if(t==='config')renderConfig();
  if(t==='coach')renderCoach();
}

// ════════════════════════════════════════════════════════════════════
// DATA
// ════════════════════════════════════════════════════════════════════

const MODS=[
  {id:'A',name:'Infra / Hardening', color:'#00e87a'},
  {id:'B',name:'CTF / Red Team',    color:'#3b9eff'},
  {id:'C',name:'IR & Forense',      color:'#ff4b6e'},
  {id:'D',name:'Blue Team / SIEM',  color:'#f5a623'},
  {id:'E',name:'App Security',      color:'#a78bfa'},
  {id:'F',name:'Governance/Report', color:'#67e8f9'},
];

const LVL=['Nunca fez','Viu o conceito','Fez com tutorial','Fez com consulta ocasional',
  'Executa com alguma consulta','Executa de forma autônoma','Autônomo, entende edge cases',
  'Executa sob pressão e tempo','Explica, cobre edge cases','Referência técnica','Nível mundial'];

const REV_Q=[
  'Resolvi algo essa semana que semana passada me travaria?',
  'Consigo explicar o mecanismo interno — não só o comando?',
  'Tenho evidência no repo (write-up, commit, documento)?',
];

const DEFAULT_RULES=[
  '01 — Um entregável por semana. Horas não contam, entregáveis contam.',
  '02 — 90 min travado = anota, fecha, passa.',
  '03 — Write-up no mesmo dia do lab.',
  '04 — Nível estagnado 2 meses: ciclo inteiro vai para esse módulo.',
  '05 — Sexta-feira não pula.',
];

// Bloco diário e rotina semanal (pode ser editado pelo treinador via shared)
const DEFAULT_BLOCO=[
  {time:'08:00–09:30',cor:'#00e87a',txt:'CONCEITO — leitura, vídeo, doc. Terminal fechado.'},
  {time:'09:30–12:00',cor:'#3b9eff',txt:'LAB — meta concreta, não "explorar".'},
  {time:'12:00–13:00',cor:null,txt:'Almoço — sem tela.'},
  {time:'13:00–15:30',cor:'#a78bfa',txt:'CONSTRUÇÃO — projeto do ciclo ou cert. Commit obrigatório.'},
  {time:'15:30–17:00',cor:'#f5a623',txt:'WRITE-UP — MITRE + defesa + o que aprendeu.'},
  {time:'17:00–18:00',cor:'#67e8f9',txt:'FECHAMENTO — o que ficou aberto, planejamento.'},
];
const DEFAULT_SEMANAL=[
  {day:'Segunda',cor:'#3b9eff',mod:'Módulo B',sub:'Ofensivo',nota:'lab HTB/THM + write-up'},
  {day:'Terça',cor:'#ff4b6e',mod:'Módulo C/D',sub:'Forense/SIEM',nota:'lab + write-up'},
  {day:'Quarta',cor:'#00e87a',mod:'Módulo A',sub:'Infra/Hardening',nota:'lab caseiro'},
  {day:'Quinta',cor:'#a78bfa',mod:'Módulo E/F',sub:'Web/Report',nota:'PortSwigger'},
  {day:'Sexta ★',cor:'#f5a623',mod:'Revisão',sub:'Não pular',nota:'3 perguntas + repo'},
];

// Ciclos worldskills — nível padrão 7 (estadual) e 10 (mundial)
const CYC=[
  {n:1,name:'Forense Windows',mod:'C',pl:'CyberDefenders',wk:'1–4',goal:'Volatility 3, artefatos Windows, timeline.',tasks:['Volatility: pslist, netscan, cmdline, malfind','MemLab 1 sem hint','Artefatos: Prefetch, Event Logs, MFT','MemLab 2 — timeline 10+ eventos MITRE'],exits:['MemLab 1 sem walkthrough','MemLab 2 sem walkthrough','Timeline 10+ eventos do zero'],unlock:'Abrir dump e saber por onde começar',target:{estadual:7,mundial:10}},
  {n:2,name:'SIEM e Detecção',mod:'D',pl:'Splunk / BOTSv1',wk:'5–8',goal:'SPL, detecção de TTPs. BOTSv1 com dataset real.',tasks:['SPL: stats, eval, rex, transaction','BOTSv1: 20 perguntas sem dica','BOTSv1: lateral movement e exfiltração','3 detecções próprias'],exits:['70%+ BOTSv1 sem dica','3 queries documentadas'],unlock:'Formular hipótese em < 30 min',target:{estadual:7,mundial:10}},
  {n:3,name:'AD Ofensivo',mod:'B',pl:'HackTheBox',wk:'9–12',goal:'Kerberoasting, AS-REP, PtH, ACL abuse, BloodHound.',tasks:['Lab AD + BloodHound','HTB Forest sem walkthrough','HTB Sauna sem walkthrough','ACL abuse no lab'],exits:['Forest sem walkthrough','Sauna sem walkthrough','BloodHound DA < 20 min'],unlock:'Enumerar AD sem checklist',target:{estadual:7,mundial:10}},
  {n:4,name:'Hardening e Infra',mod:'A',pl:'CIS-CAT + MS SCT',wk:'13–16',goal:'CIS Benchmark, PAM, GPO baseline.',tasks:['CIS-CAT Lite Linux','Corrigir até 85%+ CIS Level 1','GPO baseline Windows','Hardening do zero < 2h'],exits:['Linux CIS > 85%','GPO + Credential Guard','Hardening < 2h'],unlock:'VM limpa: saber o que fazer',target:{estadual:7,mundial:10}},
  {n:5,name:'Web App Security',mod:'E',pl:'PortSwigger',wk:'17–20',goal:'SQLi, XSS, File Upload. Mecanismo, não payload.',tasks:['SQLi: 8 labs sem hint','SQLi blind: 16 labs + script Python','XSS: 10+ labs + bypass CSP','File Upload + JWT bypass'],exits:['16 SQLi sem hint','10 XSS + CSP bypass','Script boolean blind'],unlock:'Mapear vetores antes do Burp',target:{estadual:7,mundial:10}},
  {n:6,name:'Incident Response',mod:'C',pl:'BTLO',wk:'21–24',goal:'PICERL na prática, playbooks, IOCs.',tasks:['BTLO Phishing 100%','BTLO Maldoc — olevba, ANY.RUN','BTLO Seized — timeline, hipótese','Playbook ransomware 15+ ações'],exits:['3 labs 100%','Playbook no repo'],unlock:'PICERL mentalmente ao ouvir incidente',target:{estadual:7,mundial:10}},
  {n:7,name:'Malware Analysis',mod:'C',pl:'MalwareBazaar',wk:'25–28',goal:'Análise estática + dinâmica + YARA.',tasks:['FlareVM/REMnux setup','Amostra 1: ANY.RUN + Ghidra','Amostras 2-3 + YARA','Script Python IOCs'],exits:['3 famílias com relatório','3 YARA sem falso positivo','Script rodando'],unlock:'Binário → ordem de análise sem consultar',target:{estadual:7,mundial:10}},
  {n:8,name:'AD Avançado + Pivoting',mod:'B',pl:'HackTheBox',wk:'29–32',goal:'DCSync, Golden Ticket, ligolo-ng.',tasks:['Ligolo-ng do zero','HTB Cascade sem walkthrough','HTB Monteverde sem walkthrough','Golden Ticket completo'],exits:['Cascade sem walkthrough','Monteverde sem walkthrough','Ligolo-ng < 30 min'],unlock:'Foothold → pivoting imediatamente',target:{estadual:7,mundial:10}},
  {n:9,name:'C2 na Prática',mod:'B',pl:'Lab Próprio',wk:'33–36',goal:'Sliver, jitter, kill date, OPSEC.',tasks:['Sliver + HTTPS + agente','Jitter + kill date + Wireshark','AMSI bypass','OPSEC document'],exits:['Beacon jitter + kill date','Tráfego documentado','OPSEC 10+ decisões'],unlock:'Descrever o que blue team veria',target:{estadual:7,mundial:10}},
  {n:10,name:'Purple Team',mod:'D',pl:'Atomic Red Team',wk:'37–40',goal:'20+ TTPs. Coverage matrix.',tasks:['Discovery TTPs + gaps','Execution + Persistence','Credential Access + LM','Coverage matrix'],exits:['20+ atomics','Coverage matrix','5+ regras criadas'],unlock:'Ataque + detecção simultâneos',target:{estadual:7,mundial:10}},
  {n:11,name:'Cloud — Azure AD',mod:'B',pl:'Azure Free',wk:'41–44',goal:'Azure AD, attack paths, Sentinel + KQL.',tasks:['Azure AD + PowerShell','Attack paths no lab','Sentinel + KQL','3 Sigma → KQL'],exits:['Lab ataque + detecção','3 KQL gerando alertas'],unlock:'AD on-prem vs Azure híbrido',target:{estadual:7,mundial:10}},
  {n:12,name:'Reporting Técnico',mod:'F',pl:'Próprio',wk:'45–48',goal:'Sumário + Findings + CVSS.',tasks:['Sumário sem jargão','5 Findings com CVSS','Revisar como não técnico','Apresentar 3 findings em 5 min'],exits:['10+ páginas no repo','Sumário aprovado','CVSS em cada finding'],unlock:'Explicar RCE para gestor',target:{estadual:7,mundial:10}},
  {n:13,name:'Simulados F3',mod:'P',pl:'Lab + Timebox',wk:'49–52',goal:'Simulados cronometrados.',tasks:['Simulado A','Simulado B/C','Gap analysis','Reforço'],exits:['Score > 7/10'],unlock:'Identificar gaps a tempo',target:{estadual:7,mundial:10}},
  {n:14,name:'Refinamento F3-1',mod:'P',pl:'Variável',wk:'53–56',goal:'Módulo mais fraco.',tasks:['Identificar fraco','Lab central','Simulado','Atualizar régua'],exits:['Módulo fraco > 7/10'],unlock:'Sem módulo claramente fraco',target:{estadual:7,mundial:10}},
  {n:15,name:'Refinamento F3-2',mod:'P',pl:'Variável',wk:'57–60',goal:'Segundo módulo fraco.',tasks:['Gap analysis','Lab','Simulado','Régua'],exits:['Segundo > 7/10','Nenhum < 6/10'],unlock:'Régua uniforme ≥ 6/10',target:{estadual:7,mundial:10}},
  {n:16,name:'Simulado Completo',mod:'P',pl:'3 dias',wk:'61–64',goal:'3 dias formato competição.',tasks:['Dia 1: A+B','Dia 2: C+D','Dia 3: E+F','Debrief'],exits:['3d finalizado','Debrief documentado'],unlock:'Sentir como é a competição',target:{estadual:7,mundial:10}},
  {n:17,name:'Refinamento pós-sim',mod:'P',pl:'Variável',wk:'65–68',goal:'Gaps do simulado.',tasks:['Gap analysis','Reforço fraco','Segundo reforço','Simulado parcial'],exits:['Média > 7.5/10'],unlock:'Confiança nos pontos fracos',target:{estadual:7,mundial:10}},
  {n:18,name:'Refinamento Final',mod:'P',pl:'Variável',wk:'69–72',goal:'Últimos ajustes.',tasks:['Simulado parcial','Reforço','Validação','Prep Fase 4'],exits:['Todos > 7/10','Sem gap crítico'],unlock:'Entrada no Pico',target:{estadual:7,mundial:10}},
  {n:19,name:'Pico de Forma I',mod:'P',pl:'Simulados',wk:'73–76',goal:'Zero conteúdo novo. Velocidade.',tasks:['Simulado 3d #2','Debrief velocidade','Treino velocidade','Simulado parcial'],exits:['Todos > 8/10','Velocidade consistente'],unlock:'Todos > 8/10',target:{estadual:8,mundial:10}},
  {n:20,name:'Pico de Forma II',mod:'P',pl:'Simulados',wk:'77–80',goal:'Máxima consistência.',tasks:['Simulado 3d #3','Debrief ajuste fino','Revisão módulo','Descanso ativo'],exits:['Nenhum < 7.5/10'],unlock:'Nenhum < 7.5/10',target:{estadual:8,mundial:10}},
  {n:21,name:'Semana Final',mod:'P',pl:'WorldSkills',wk:'81–84',goal:'Pré-Aichi. Descanso e confiança.',tasks:['Revisão pontos fortes','Revisão metodologia','Descanso real','AICHI 2028 🏆'],exits:['Chegar descansado','Todos os sistemas go'],unlock:'🏆 WorldSkills Aichi 2028',target:{estadual:9,mundial:10}},
];

// ════════════════════════════════════════════════════════════════════
// DASHBOARD
// ════════════════════════════════════════════════════════════════════

function renderDash(){
  const uid=SES.user.id;
  const coach=isCoach(uid);

  if(coach){
    document.getElementById('athlete-view').style.display='none';
    document.getElementById('coach-overview').style.display='block';
    document.getElementById('coach-info-block').style.display='none';
    renderCoachOverview();
    return;
  }

  // ── VISÃO COMPETIDOR ──────────────────────────────────────────────
  document.getElementById('athlete-view').style.display='block';
  document.getElementById('coach-overview').style.display='none';

  renderCoachInfoBlock(uid);

  // Banner senha padrão
  const pwBanner=document.getElementById('pw-default-banner');
  if(pwBanner) pwBanner.style.display=isFirstLogin(uid)?'flex':'none';

  // Stats
  const evalDate=loadShared('eval_date_'+uid)||'';
  const coachEval=evalDate?(loadShared('eval_'+uid)||{}):{};
  const cvals=Object.values(coachEval).filter(v=>v>0);
  const cavg=cvals.length?(cvals.reduce((a,b)=>a+b,0)/cvals.length):0;
  document.getElementById('s-avg-coach').textContent=cavg?cavg.toFixed(1):'—';
  document.getElementById('avg-bar-c').style.width=(cavg*10)+'%';
  document.getElementById('s-cycle').textContent=ST.cycle;
  const cy=getCycles()[ST.cycle-1];
  document.getElementById('s-cname').textContent=cy?cy.name:'—';
  const week=(ST.cycle-1)*4+1;
  document.getElementById('s-week').textContent=week;
  const pct=Math.round((week/84)*100);
  document.getElementById('prog-bar').style.width=pct+'%';
  document.getElementById('s-pct').textContent=pct+'% (semana '+week+' de ~84)';

  // Self bars
  document.getElementById('self-hint').textContent='— clique para editar';
  document.getElementById('self-bars').innerHTML=MODS.map(m=>{
    const v=ST.levels[m.id]||0,p=v*10;
    return`<div class="mrow" onclick="openMod('${m.id}','self')">
      <span class="mid">${m.id}</span><span class="mnm">${m.name}</span>
      <div class="bt"><div class="bf" style="width:${p}%;background:${m.color}"></div></div>
      <span class="bv" style="color:${v>=7?m.color:'#4a5568'}">${v}/10</span>
      <span class="bbtn">↑</span>
    </div>`;
  }).join('');

  // Coach eval — só se publicada
  const hasEval=!!evalDate&&cvals.length>0;
  document.getElementById('coach-eval-card').style.display=hasEval?'block':'none';
  if(hasEval){
    document.getElementById('coach-eval-date').textContent=evalDate;
    document.getElementById('coach-bars').innerHTML=MODS.map(m=>{
      const v=coachEval[m.id]||0,p=v*10;
      const tcy=getCycles()[ST.cycle-1]?.target||{estadual:7,mundial:10};
      const color=v>=tcy.mundial?'#00e87a':v>=tcy.estadual?'#f5a623':'#ff4b6e';
      return`<div class="mrow ro">
        <span class="mid">${m.id}</span><span class="mnm">${m.name}</span>
        <div class="bt"><div class="bf" style="width:${p}%;background:${m.color}"></div></div>
        <span class="bv" style="color:${color}">${v}/10</span>
      </div>`;
    }).join('');
  }

  // Mensagem do dia — só se definida
  const msgDia=loadShared('msg_dia')||'';
  document.getElementById('msg-dia-card').style.display=msgDia?'block':'none';
  document.getElementById('msg-do-dia').textContent=msgDia;

  // Ciclos
  document.getElementById('cyc-hint').textContent='— duplo clique no ativo para avançar';
  renderCycList('cyc-list');

  // Revisão
  document.getElementById('rev-items').innerHTML=REV_Q.map((q,i)=>{
    const on=ST.review[i];
    return`<div class="rev-q${on?' on':''}" onclick="togRev(${i})">
      <div class="qb">${on?'✓':''}</div>
      <span style="font-size:11px;${on?'color:var(--text)':'color:var(--muted2)'}">${q}</span>
    </div>`;
  }).join('');
  const rn=ST.review.filter(Boolean).length;
  const rc=rn===3?'var(--accent)':rn>=1?'var(--amber)':'var(--muted)';
  document.getElementById('rev-status').innerHTML=`<span style="color:${rc}">${rn}/3</span>${rn===3?' — ✓ semana fechada':''}`;

  // Regras
  const rules=loadShared('rules')||DEFAULT_RULES;
  document.getElementById('rules-list').innerHTML=rules.map(r=>
    `<div class="exit-item ro" style="cursor:default;padding:6px 0;font-size:11px;color:var(--muted2)">${r}</div>`
  ).join('');

  // Log de status
  const slb=document.getElementById('status-log-box');
  slb.style.display='block';
  const st=loadSt(uid);
  const payload=JSON.stringify({uid,name:SES.user.name,...st},null,2);
  slb.innerHTML=`<div class="card">
    <div class="clabel"><div class="clabel-dot" style="background:var(--blue);box-shadow:0 0 5px var(--blue)"></div>Log de Status <span style="color:var(--muted);font-size:9px">— envie ao avaliador para ele atualizar seu progresso</span></div>
    <div style="position:relative">
      <div class="json-block" id="export-json-text">${payload}</div>
      <button class="copy-btn" onclick="copyJson()">Copiar</button>
    </div>
  </div>`;
}

// ── DASHBOARD DO AVALIADOR ────────────────────────────────────────────
function renderCoachOverview(){
  const aths=USERS.filter(u=>!isCoach(u.id));

  // Próximas provas
  const provas=(loadShared('provas')||[])
    .filter(p=>new Date(p.date+'T00:00')>=new Date())
    .sort((a,b)=>new Date(a.date)-new Date(b.date));

  const tipoC={estadual:'var(--amber)',nacional:'var(--accent)',mundial:'var(--blue)',simulado:'var(--purple)',outro:'var(--muted2)'};

  // Dados de cada atleta
  const athData=aths.map(a=>{
    const ast=loadSt(a.id);
    const evalDate=loadShared('eval_date_'+a.id)||'';
    const eval_=evalDate?(loadShared('eval_'+a.id)||{}):{};
    const selfVals=Object.values(ast.levels).filter(v=>v>0);
    const selfAvg=selfVals.length?(selfVals.reduce((x,y)=>x+y,0)/selfVals.length):0;
    const evalVals=Object.values(eval_).filter(v=>v>0);
    const evalAvg=evalVals.length?(evalVals.reduce((x,y)=>x+y,0)/evalVals.length):0;
    const cy=getCycles()[ast.cycle-1];
    const tcy=cy?.target||{estadual:7,mundial:10};
    const pendingPw=isFirstLogin(a.id);
    const week=(ast.cycle-1)*4+1;
    const prog=Math.round((week/84)*100);
    const rn=ast.review.filter(Boolean).length;
    return{a,ast,evalDate,eval_,selfAvg,evalAvg,cy,tcy,pendingPw,prog,rn};
  });

  document.getElementById('coach-overview').innerHTML=`

  <!-- BARRA SUPERIOR: stats rápidos + próxima prova + mensagem do dia -->
  <div style="display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:14px">
    ${athData.map(({a,ast,selfAvg,evalAvg,evalDate,prog,pendingPw})=>`
      <div class="card" style="border-left:3px solid ${a.color};padding-left:14px">
        <div style="display:flex;align-items:center;gap:8px;margin-bottom:10px">
          <div style="width:28px;height:28px;border-radius:50%;background:${a.color}20;border:1px solid ${a.color}50;color:${a.color};display:flex;align-items:center;justify-content:center;font-family:var(--display);font-size:11px;font-weight:800;flex-shrink:0">${a.name[0]}</div>
          <div>
            <div style="font-family:var(--display);font-size:13px;font-weight:700">${a.name.split(' ')[0]}</div>
            <div style="font-size:9px;color:var(--muted)">Ciclo ${ast.cycle}/21</div>
          </div>
          ${pendingPw?`<div style="margin-left:auto;font-size:8px;color:var(--amber);background:rgba(245,166,35,.1);border:1px solid rgba(245,166,35,.3);border-radius:2px;padding:2px 5px">⚠ pw</div>`:''}
        </div>
        <div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:4px;text-align:center">
          <div style="background:var(--bg3);border:1px solid var(--border);border-radius:3px;padding:6px 4px">
            <div style="font-family:var(--display);font-size:18px;font-weight:800;color:${a.color}">${selfAvg?selfAvg.toFixed(1):'—'}</div>
            <div style="font-size:8px;color:var(--muted);text-transform:uppercase">auto</div>
          </div>
          <div style="background:var(--bg3);border:1px solid var(--border);border-radius:3px;padding:6px 4px">
            <div style="font-family:var(--display);font-size:18px;font-weight:800;color:${evalDate?'var(--purple)':'var(--muted)'}">${evalAvg&&evalDate?evalAvg.toFixed(1):'—'}</div>
            <div style="font-size:8px;color:var(--muted);text-transform:uppercase">nota</div>
          </div>
          <div style="background:var(--bg3);border:1px solid var(--border);border-radius:3px;padding:6px 4px">
            <div style="font-family:var(--display);font-size:18px;font-weight:800;color:var(--amber)">${prog}%</div>
            <div style="font-size:8px;color:var(--muted);text-transform:uppercase">prog</div>
          </div>
        </div>
        <div style="height:3px;background:var(--border);border-radius:2px;overflow:hidden;margin-top:8px">
          <div style="height:100%;width:${prog}%;background:${a.color};border-radius:2px;transition:width .6s"></div>
        </div>
      </div>
    `).join('')}
    <div class="card" style="border-left:3px solid var(--purple)">
      <div class="clabel" style="margin-bottom:8px"><div class="clabel-dot" style="background:var(--purple);box-shadow:0 0 5px var(--purple)"></div>Próxima Prova</div>
      ${provas.length?`
        <div style="font-family:var(--display);font-size:22px;font-weight:800;color:var(--amber)">
          ${new Date(provas[0].date+'T00:00').toLocaleDateString('pt-BR',{day:'2-digit',month:'short'})}
        </div>
        <div style="font-size:12px;color:var(--text);margin-top:3px">${provas[0].name}</div>
        <div style="font-size:10px;color:var(--muted);margin-top:2px">${provas[0].local||'—'}</div>
        <div style="font-size:9px;color:${tipoC[provas[0].tipo]||'var(--muted2)'};margin-top:4px;text-transform:uppercase">${provas[0].tipo}</div>
      `:`<div style="font-size:11px;color:var(--muted);margin-top:8px;font-style:italic">Sem provas agendadas</div>`}
    </div>
  </div>

  <!-- COMPARATIVO DETALHADO POR COMPETIDOR -->
  <div style="font-size:9px;letter-spacing:.18em;text-transform:uppercase;color:var(--muted);margin-bottom:12px;display:flex;align-items:center;gap:8px">
    <div class="clabel-dot" style="background:var(--purple);box-shadow:0 0 5px var(--purple)"></div>
    Avaliação Detalhada — Auto-avaliação vs Nota do Avaliador
    <span style="font-size:9px;color:var(--muted);font-weight:400;letter-spacing:.04em;text-transform:none">
      (verde ≥ meta mundial · âmbar ≥ meta estadual · vermelho abaixo)
    </span>
  </div>
  <div style="display:grid;grid-template-columns:${aths.map(()=>'1fr').join(' ')};gap:12px;margin-bottom:14px">
    ${athData.map(({a,ast,eval_,evalDate,selfAvg,evalAvg,cy,tcy,pendingPw,rn})=>`
      <div class="card" style="border-top:2px solid ${a.color}">
        <!-- CABEÇALHO -->
        <div style="display:flex;align-items:center;gap:10px;margin-bottom:14px;padding-bottom:12px;border-bottom:1px solid var(--border)">
          <div style="width:36px;height:36px;border-radius:50%;background:${a.color}20;border:1px solid ${a.color}60;color:${a.color};display:flex;align-items:center;justify-content:center;font-family:var(--display);font-size:15px;font-weight:800;flex-shrink:0">${a.name[0]}</div>
          <div style="flex:1">
            <div style="font-family:var(--display);font-size:14px;font-weight:700">${a.name}</div>
            <div style="font-size:10px;color:var(--muted)">Ciclo ${ast.cycle}/21 · ${cy?cy.name:'—'}</div>
          </div>
          ${pendingPw?`<div style="font-size:9px;color:var(--amber);background:rgba(245,166,35,.08);border:1px solid rgba(245,166,35,.25);border-radius:2px;padding:3px 7px">⚠ senha padrão</div>`:''}
        </div>

        <!-- CABEÇALHO DAS COLUNAS -->
        <div style="display:grid;grid-template-columns:14px 1fr 38px 38px 22px;gap:6px;align-items:center;margin-bottom:6px;font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.06em">
          <span></span><span></span><span style="text-align:right">Auto</span><span style="color:var(--purple);text-align:right">Nota</span><span style="text-align:right">Δ</span>
        </div>

        <!-- MÓDULOS -->
        ${MODS.map(m=>{
          const sv=ast.levels[m.id]||0;
          const cv=eval_[m.id]||0;
          const cc=evalDate?(cv>=tcy.mundial?'#00e87a':cv>=tcy.estadual?'#f5a623':cv>0?'#ff4b6e':'#4a5568'):'var(--muted)';
          const diff=evalDate&&cv>0?cv-sv:null;
          const dStr=diff===null?'':diff>0?`+${diff}`:diff===0?'=':String(diff);
          const dColor=diff===null?'transparent':diff>0?'var(--accent)':diff===0?'var(--muted2)':'var(--red)';
          return`<div style="display:grid;grid-template-columns:14px 1fr 38px 38px 22px;gap:6px;align-items:center;padding:5px 0;border-bottom:1px solid rgba(255,255,255,.03)">
            <span style="font-size:9px;color:var(--blue)">${m.id}</span>
            <div style="position:relative;height:5px;background:var(--border);border-radius:3px;overflow:hidden">
              <div style="position:absolute;left:0;top:0;bottom:0;width:${sv*10}%;background:${m.color};border-radius:3px;opacity:.7"></div>
              <div style="position:absolute;left:0;top:0;bottom:0;width:${evalDate?cv*10:0}%;background:var(--purple);border-radius:3px;opacity:.5"></div>
              <div style="position:absolute;top:0;bottom:0;left:${tcy.estadual*10}%;width:1px;background:rgba(245,166,35,.5)"></div>
              <div style="position:absolute;top:0;bottom:0;left:${tcy.mundial*10}%;width:1px;background:rgba(0,232,122,.5)"></div>
            </div>
            <span style="font-size:10px;color:${sv>=7?m.color:'#6b7a94'};text-align:right;font-weight:500">${sv}</span>
            <span style="font-size:10px;color:${cc};text-align:right;font-weight:500">${evalDate?cv:'—'}</span>
            <span style="font-size:9px;color:${dColor};text-align:right">${dStr}</span>
          </div>`;
        }).join('')}

        <!-- REVISÃO DE SEXTA -->
        <div style="margin-top:10px;padding-top:10px;border-top:1px solid var(--border);display:flex;align-items:center;justify-content:space-between">
          <div style="font-size:10px;color:var(--muted)">Revisão de sexta</div>
          <div style="font-size:10px;color:${rn===3?'var(--accent)':rn>=1?'var(--amber)':'var(--muted)'};font-weight:500">${rn}/3${rn===3?' ✓':''}</div>
        </div>

        <!-- AÇÕES RÁPIDAS -->
        <div style="display:flex;gap:6px;margin-top:10px">
          <button class="abtn btn-pu" onclick="switchTab('coach')" style="padding:6px 0;font-size:10px;margin-top:0">Avaliar</button>
          <button class="abtn btn-g" onclick="coachAdvCyc('${a.id}')" style="padding:6px 0;font-size:10px;margin-top:0">↑ Ciclo</button>
          <button class="abtn btn-r" onclick="coachReset('${a.id}','${a.name.split(' ')[0]}')" style="padding:6px 0;font-size:10px;margin-top:0">⚿ Senha</button>
        </div>
      </div>
    `).join('')}
  </div>

  <!-- LEGENDA DAS BARRAS -->
  <div style="font-size:10px;color:var(--muted);display:flex;gap:16px;flex-wrap:wrap;padding:10px 14px;background:var(--bg2);border:1px solid var(--border);border-radius:3px">
    <span><span style="color:var(--muted2)">■</span> barra clara = auto-avaliação</span>
    <span><span style="color:var(--purple)">■</span> barra escura = nota do avaliador</span>
    <span><span style="color:rgba(245,166,35,.8)">|</span> linha âmbar = meta estadual</span>
    <span><span style="color:rgba(0,232,122,.8)">|</span> linha verde = meta mundial</span>
    <span><span style="color:var(--accent)">Δ+</span> diferença nota vs auto</span>
  </div>
  `;
}

function renderCoachInfoBlock(uid){
  const fb=loadShared('feedback_'+uid)||'';
  const fbDate=loadShared('feedback_date_'+uid)||'';
  const meta=loadShared('meta_'+uid)||'';
  const avName=USERS.find(u=>isCoach(u.id))?.name||'Avaliador';
  const block=document.getElementById('coach-info-block');
  let html='';
  if(fb){
    html+=`<div class="card" style="border-color:rgba(167,139,250,.25);margin-bottom:8px">
      <div class="clabel"><div class="clabel-dot" style="background:var(--purple);box-shadow:0 0 5px var(--purple)"></div>Feedback de ${avName} <span style="color:var(--muted);font-size:9px">${fbDate}</span></div>
      <div style="font-size:11px;color:var(--muted2);line-height:1.7;border-left:2px solid var(--purple);padding-left:10px;font-style:italic">${fb}</div>
    </div>`;
  }
  if(meta){
    html+=`<div class="card" style="border-color:rgba(0,232,122,.2);margin-bottom:8px">
      <div class="clabel"><div class="clabel-dot"></div>Meta do Dia — <span style="color:var(--muted2)">${avName}</span></div>
      <div style="font-size:12px;color:var(--accent);font-weight:500">${meta}</div>
    </div>`;
  }
  block.innerHTML=html;
  block.style.display=html?'block':'none';
}


function togRev(i){ST.review[i]=!ST.review[i];saveSt(SES.user.id,ST);renderDash();}
function clearRev(){ST.review=[false,false,false];saveSt(SES.user.id,ST);renderDash();}

function copyJson(){
  const txt=document.getElementById('export-json-text')?.textContent;
  if(!txt)return;
  navigator.clipboard.writeText(txt).then(()=>{
    const btn=document.querySelector('.copy-btn');
    if(btn){btn.textContent='Copiado!';setTimeout(()=>btn.textContent='Copiar',2000);}
  });
}

// ════════════════════════════════════════════════════════════════════
// CONFIGURAÇÕES (só avaliador)
// ════════════════════════════════════════════════════════════════════

function renderConfig(){
  document.getElementById('cfg-msg-dia').value=loadShared('msg_dia')||'';
  const rules=loadShared('rules')||DEFAULT_RULES;
  document.getElementById('cfg-rules').value=rules.join('\n');
  const bloco=loadShared('bloco')||DEFAULT_BLOCO;
  document.getElementById('cfg-bloco').value=JSON.stringify(bloco,null,2);
  const sem=loadShared('semanal')||DEFAULT_SEMANAL;
  document.getElementById('cfg-semanal').value=JSON.stringify(sem,null,2);
  // Per-athlete
  const aths=USERS.filter(u=>!isCoach(u.id));
  document.getElementById('cfg-per-athlete').innerHTML=aths.map(a=>{
    const fb=loadShared('feedback_'+a.id)||'';
    const meta=loadShared('meta_'+a.id)||'';
    const fn=a.name.split(' ')[0];
    return`<div style="margin-bottom:16px;padding-bottom:16px;border-bottom:1px solid var(--border)">
      <div style="font-size:11px;color:${a.color};font-weight:700;margin-bottom:8px">${a.name}</div>
      <div class="lbl" style="margin-top:0">Meta do Dia</div>
      <input class="inp" id="cfg-meta-${a.id}" value="${meta}" placeholder="Meta de hoje para ${fn}..." style="margin-top:4px">
      <div class="lbl">Feedback</div>
      <textarea class="ta" id="cfg-fb-${a.id}" style="min-height:60px;margin-top:4px">${fb}</textarea>
      <button class="abtn btn-b" onclick="cfgSaveAthlete('${a.id}')" style="margin-top:6px">Salvar para ${fn}</button>
      <div class="small-ok" id="cfg-ath-ok-${a.id}"></div>
    </div>`;
  }).join('');
  // Ciclos
  cfgRenderCycles();
}

// ── CICLOS CUSTOMIZÁVEIS ─────────────────────────────────────────────
// getCycles() retorna CYC com overrides do avaliador aplicados, na ordem customizada
function getCycles(){
  const custom=loadShared('cycles_custom');
  if(!custom)return CYC;
  // custom = array de objetos com campos opcionais sobrescrevendo CYC
  // Se custom tem 21 entradas, usa a ordem e os campos deles
  return custom.map((ov,i)=>{
    const base=CYC.find(c=>c.n===(ov.n||i+1))||CYC[i]||CYC[0];
    return{...base,...ov};
  });
}

let cfgEditingCyc=null; // índice sendo editado (0-based na lista customizada)
let cfgDragSrc=null;

function cfgRenderCycles(){
  const cycs=getCycles();
  const el=document.getElementById('cfg-cycles-list');
  el.innerHTML=cycs.map((cy,i)=>`
    <div class="cfg-cyc-row" data-idx="${i}" draggable="true"
      ondragstart="cfgDragStart(event,${i})"
      ondragover="cfgDragOver(event)"
      ondrop="cfgDrop(event,${i})"
      ondragend="cfgDragEnd()"
      style="display:flex;align-items:center;gap:10px;padding:8px 12px;background:var(--bg3);border:1px solid var(--border);border-radius:4px;margin-bottom:4px;cursor:grab;transition:all .12s">
      <span style="color:var(--muted);font-size:10px;cursor:grab;padding:0 4px;user-select:none">⠿</span>
      <span style="font-size:10px;color:var(--muted);width:20px;flex-shrink:0">${String(i+1).padStart(2,'0')}</span>
      <span class="tag t${cy.mod}" style="flex-shrink:0">${cy.mod}</span>
      <span style="flex:1;font-size:11px;color:var(--text)">${cy.name}</span>
      <span style="font-size:10px;color:var(--muted2);margin-right:4px">${cy.pl||''}</span>
      <button onclick="cfgEditCyc(${i})" style="padding:3px 10px;background:transparent;border:1px solid var(--border2);color:var(--muted2);font-family:var(--mono);font-size:10px;border-radius:3px;cursor:pointer;transition:all .12s" onmouseover="this.style.borderColor='var(--blue)';this.style.color='var(--blue)'" onmouseout="this.style.borderColor='var(--border2)';this.style.color='var(--muted2)'">editar</button>
    </div>
    ${cfgEditingCyc===i?cfgEditForm(cy,i):''}
  `).join('');
}

function cfgEditForm(cy,i){
  return`<div style="background:var(--bg2);border:1px solid rgba(0,232,122,.2);border-radius:4px;padding:16px;margin-bottom:8px;margin-top:-4px">
    <div style="display:grid;grid-template-columns:1fr 1fr 80px;gap:10px;margin-bottom:10px">
      <div>
        <div class="lbl" style="margin-top:0">Nome do ciclo</div>
        <input class="inp" id="cedit-name" value="${cy.name}" style="margin-top:4px">
      </div>
      <div>
        <div class="lbl" style="margin-top:0">Plataforma</div>
        <input class="inp" id="cedit-pl" value="${cy.pl||''}" style="margin-top:4px">
      </div>
      <div>
        <div class="lbl" style="margin-top:0">Módulo</div>
        <select class="inp" id="cedit-mod" style="margin-top:4px;cursor:pointer">
          ${['A','B','C','D','E','F','P'].map(m=>`<option value="${m}"${cy.mod===m?' selected':''}>${m}</option>`).join('')}
        </select>
      </div>
    </div>
    <div style="margin-bottom:10px">
      <div class="lbl" style="margin-top:0">Objetivo</div>
      <textarea class="ta" id="cedit-goal" style="min-height:48px;margin-top:4px">${cy.goal||''}</textarea>
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:10px">
      <div>
        <div class="lbl" style="margin-top:0">Tarefas (uma por linha)</div>
        <textarea class="ta" id="cedit-tasks" style="min-height:80px;margin-top:4px">${(cy.tasks||[]).join('\n')}</textarea>
      </div>
      <div>
        <div class="lbl" style="margin-top:0">Critérios de saída (um por linha)</div>
        <textarea class="ta" id="cedit-exits" style="min-height:80px;margin-top:4px">${(cy.exits||[]).join('\n')}</textarea>
      </div>
    </div>
    <div style="margin-bottom:12px">
      <div class="lbl" style="margin-top:0">Desbloqueio</div>
      <input class="inp" id="cedit-unlock" value="${cy.unlock||''}" style="margin-top:4px">
    </div>
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:10px">
      <div>
        <div class="lbl" style="margin-top:0">Meta estadual</div>
        <input class="inp" type="number" min="0" max="10" id="cedit-est" value="${cy.target?.estadual??7}" style="margin-top:4px">
      </div>
      <div>
        <div class="lbl" style="margin-top:0">Meta mundial</div>
        <input class="inp" type="number" min="0" max="10" id="cedit-mun" value="${cy.target?.mundial??10}" style="margin-top:4px">
      </div>
    </div>
    <div style="display:flex;gap:8px">
      <button class="abtn btn-g" onclick="cfgSaveCyc(${i})" style="margin-top:0;width:auto;padding:8px 20px">Salvar</button>
      <button class="abtn btn-r" onclick="cfgCancelCyc()" style="margin-top:0;width:auto;padding:8px 16px">Cancelar</button>
    </div>
  </div>`;
}

function cfgEditCyc(i){
  cfgEditingCyc=(cfgEditingCyc===i)?null:i;
  cfgRenderCycles();
  if(cfgEditingCyc!==null){
    setTimeout(()=>document.getElementById('cedit-name')?.scrollIntoView({behavior:'smooth',block:'nearest'}),80);
  }
}

function cfgCancelCyc(){cfgEditingCyc=null;cfgRenderCycles();}

function cfgSaveCyc(i){
  const cycs=getCycles();
  const base={...cycs[i]};
  base.name=document.getElementById('cedit-name').value.trim()||base.name;
  base.pl=document.getElementById('cedit-pl').value.trim();
  base.mod=document.getElementById('cedit-mod').value;
  base.goal=document.getElementById('cedit-goal').value.trim();
  base.tasks=document.getElementById('cedit-tasks').value.split('\n').map(l=>l.trim()).filter(l=>l);
  base.exits=document.getElementById('cedit-exits').value.split('\n').map(l=>l.trim()).filter(l=>l);
  base.unlock=document.getElementById('cedit-unlock').value.trim();
  base.target={
    estadual:parseInt(document.getElementById('cedit-est').value)||7,
    mundial:parseInt(document.getElementById('cedit-mun').value)||10,
  };
  // Salvar array completo com essa entrada atualizada
  const all=getCycles().map((c,idx)=>idx===i?base:c);
  saveShared('cycles_custom',all);
  cfgEditingCyc=null;
  cfgRenderCycles();
  const el=document.getElementById('cfg-cyc-ok');
  el.textContent=`✓ Ciclo ${i+1} salvo`;setTimeout(()=>el.textContent='',2000);
}

// Drag-and-drop reordenação
function cfgDragStart(e,i){
  cfgDragSrc=i;
  e.currentTarget.style.opacity='.4';
  e.dataTransfer.effectAllowed='move';
}
function cfgDragOver(e){e.preventDefault();e.dataTransfer.dropEffect='move';}
function cfgDrop(e,i){
  e.preventDefault();
  if(cfgDragSrc===null||cfgDragSrc===i)return;
  const cycs=[...getCycles()];
  const [moved]=cycs.splice(cfgDragSrc,1);
  cycs.splice(i,0,moved);
  // Re-numerar n sequencialmente
  cycs.forEach((c,idx)=>c.n=idx+1);
  saveShared('cycles_custom',cycs);
  cfgEditingCyc=null;
  cfgRenderCycles();
  const el=document.getElementById('cfg-cyc-ok');
  el.textContent='✓ Ordem salva';setTimeout(()=>el.textContent='',2000);
}
function cfgDragEnd(){
  document.querySelectorAll('.cfg-cyc-row').forEach(r=>r.style.opacity='1');
  cfgDragSrc=null;
}

function cfgResetCycles(){
  if(!confirm('Restaurar todos os ciclos para os valores padrão?'))return;
  localStorage.removeItem(shKey('cycles_custom'));
  cfgEditingCyc=null;
  cfgRenderCycles();
  const el=document.getElementById('cfg-cyc-ok');
  el.textContent='✓ Ciclos restaurados';setTimeout(()=>el.textContent='',2000);
}

function cfgSaveMsgDia(){
  saveShared('msg_dia',document.getElementById('cfg-msg-dia').value.trim());
  const el=document.getElementById('cfg-msg-ok');
  el.textContent='✓ Salvo';setTimeout(()=>el.textContent='',2000);
}

function cfgSaveRules(){
  const lines=document.getElementById('cfg-rules').value.split('\n').map(l=>l.trim()).filter(l=>l);
  saveShared('rules',lines);
  const el=document.getElementById('cfg-rules-ok');
  el.textContent='✓ Salvo';setTimeout(()=>el.textContent='',2000);
}

function cfgSaveBloco(){
  try{
    const v=JSON.parse(document.getElementById('cfg-bloco').value);
    saveShared('bloco',v);
    const el=document.getElementById('cfg-bloco-ok');
    el.textContent='✓ Salvo';setTimeout(()=>el.textContent='',2000);
  }catch{
    document.getElementById('cfg-bloco-ok').textContent='JSON inválido.';
  }
}

function cfgSaveSemanal(){
  try{
    const v=JSON.parse(document.getElementById('cfg-semanal').value);
    saveShared('semanal',v);
    const el=document.getElementById('cfg-semanal-ok');
    el.textContent='✓ Salvo';setTimeout(()=>el.textContent='',2000);
  }catch{
    document.getElementById('cfg-semanal-ok').textContent='JSON inválido.';
  }
}

function cfgSaveAthlete(uid){
  const meta=document.getElementById('cfg-meta-'+uid).value.trim();
  const fb=document.getElementById('cfg-fb-'+uid).value.trim();
  saveShared('meta_'+uid,meta);
  saveShared('feedback_'+uid,fb);
  saveShared('feedback_date_'+uid,new Date().toLocaleDateString('pt-BR'));
  const el=document.getElementById('cfg-ath-ok-'+uid);
  el.textContent='✓ Salvo';setTimeout(()=>el.textContent='',2000);
}

function cfgResetAll(){
  if(!confirm('Resetar mensagem do dia, regras, bloco diário e rotina semanal para os valores padrão?'))return;
  ['msg_dia','rules','bloco','semanal'].forEach(k=>localStorage.removeItem(shKey(k)));
  renderConfig();
}

// Log de status no chat sidebar — competidor publica JSON, avaliador atualiza
function renderChatStatusLog(){
  const uid=SES.user.id;
  const coach=isCoach(uid);
  const el=document.getElementById('chat-status-log');
  if(!el)return;

  if(!coach){
    // Competidor vê o próprio JSON copiável
    const st=loadSt(uid);
    const payload=JSON.stringify({uid,name:SES.user.name,...st},null,2);
    el.style.display='block';
    el.innerHTML=`<div class="card" style="padding:12px">
      <div class="clabel" style="margin-bottom:8px"><div class="clabel-dot" style="background:var(--blue);box-shadow:0 0 5px var(--blue)"></div>Log de Status</div>
      <div style="font-size:11px;color:var(--muted2);margin-bottom:6px">Copie e envie ao avaliador.</div>
      <div style="position:relative">
        <div class="json-block" id="chat-json-txt" style="max-height:80px;font-size:9px">${payload}</div>
        <button class="copy-btn" onclick="copyChatJson()">Copiar</button>
      </div>
    </div>`;
  } else {
    // Avaliador vê um card por competidor com botão "Atualizar Status"
    const aths=USERS.filter(u=>!isCoach(u.id));
    el.style.display='block';
    el.innerHTML=`<div class="card" style="padding:12px">
      <div class="clabel" style="margin-bottom:10px"><div class="clabel-dot" style="background:var(--amber);box-shadow:0 0 5px var(--amber)"></div>Atualizar Status</div>
      ${aths.map(a=>{
        const lastUp=loadShared('status_updated_'+a.id)||'—';
        return`<div style="margin-bottom:10px;padding-bottom:10px;border-bottom:1px solid var(--border)">
          <div style="font-size:11px;color:${a.color};margin-bottom:4px">${a.name.split(' ')[0]}</div>
          <div style="font-size:9px;color:var(--muted);margin-bottom:6px">Atualizado: ${lastUp}</div>
          <textarea class="ta" id="status-json-${a.id}" placeholder="Cole o JSON de ${a.name.split(' ')[0]}..." style="min-height:48px;font-size:9px;margin-top:0"></textarea>
          <button class="abtn btn-g" onclick="coachUpdateStatus('${a.id}')" style="margin-top:4px;padding:5px 0;font-size:10px">↑ Atualizar</button>
          <div class="small-ok" id="status-ok-${a.id}" style="font-size:9px"></div>
        </div>`;
      }).join('')}
    </div>`;
  }
}

function copyChatJson(){
  const txt=document.getElementById('chat-json-txt')?.textContent;
  if(!txt)return;
  navigator.clipboard.writeText(txt).then(()=>{
    const btn=document.querySelector('#chat-status-log .copy-btn');
    if(btn){btn.textContent='Copiado!';setTimeout(()=>btn.textContent='Copiar',2000);}
  });
}

function coachUpdateStatus(uid){
  const raw=document.getElementById('status-json-'+uid)?.value.trim();
  if(!raw){document.getElementById('status-ok-'+uid).textContent='Cole o JSON primeiro.';return;}
  try{
    const data=JSON.parse(raw);
    if(data.uid!==uid)throw new Error('UID não bate');
    const{uid:_,name:__,...st}=data;
    saveSt(uid,st);
    saveShared('status_updated_'+uid,new Date().toLocaleDateString('pt-BR',{day:'2-digit',month:'short',hour:'2-digit',minute:'2-digit'}));
    document.getElementById('status-json-'+uid).value='';
    const el=document.getElementById('status-ok-'+uid);
    el.textContent='✓ Status atualizado';
    setTimeout(()=>{el.textContent='';renderChatStatusLog();},2000);
  }catch(e){
    document.getElementById('status-ok-'+uid).textContent='JSON inválido.';
  }
}

// ════════════════════════════════════════════════════════════════════
// CYCLE LIST + DETAIL
// ════════════════════════════════════════════════════════════════════

function renderCycList(elId){
  const canAdv=!isCoach(SES.user.id);
  document.getElementById(elId).innerHTML=getCycles().map(cy=>{
    let state='locked',dot='dlock';
    if(cy.n<ST.cycle){state='done';dot='ddone';}
    else if(cy.n===ST.cycle){state='active';dot='don';}
    else if(cy.n===ST.cycle+1){state='';dot='dnext';}
    return`<div class="cyc ${state}" onclick="pickCyc(${cy.n},'${elId}')" ${canAdv?`ondblclick="advCyc(${cy.n})"`:''}>
      <span class="cn">${String(cy.n).padStart(2,'0')}</span>
      <span class="cnm">${cy.name}</span>
      <span class="tag t${cy.mod}">${cy.mod}</span>
      <div class="cdot ${dot}"></div>
    </div>`;
  }).join('');
}

function pickCyc(n,listId){sCyc=n;if(listId==='cyc-list2')renderCycDet(n);}

function advCyc(n){
  if(n!==ST.cycle)return;
  if(!confirm(`Avançar para o Ciclo ${ST.cycle+1}?`))return;
  ST.cycle=Math.min(ST.cycle+1,21);sCyc=ST.cycle;
  saveSt(SES.user.id,ST);renderDash();renderCycList('cyc-list2');renderCycDet(sCyc);
}

function renderCycDet(n){
  const cy=getCycles()[n-1];if(!cy)return;
  const coach=isCoach(SES.user.id);
  document.getElementById('d-title').textContent=`Ciclo ${cy.n} — ${cy.name}`;
  document.getElementById('d-meta').innerHTML=
    `<span>Módulo ${cy.mod}</span><span>·</span><span>${cy.pl}</span><span>·</span><span>Sem. ${cy.wk}</span>`+
    `<span>·</span><span style="color:var(--amber)">Meta estadual: ${cy.target.estadual}/10</span>`+
    `<span>·</span><span style="color:var(--accent)">Meta mundial: ${cy.target.mundial}/10</span>`;
  document.getElementById('d-goal').textContent=cy.goal;
  document.getElementById('d-tasks').innerHTML=cy.tasks.map((t,i)=>
    `<div class="exit-item ro" style="cursor:default;padding:5px 0">
      <div class="exit-lbl" style="font-size:9px;min-width:16px;color:var(--muted2);margin-top:1px">${i+1}</div>
      <span>${t}</span>
    </div>`
  ).join('');
  const k=`c${n}`;
  if(!ST.exits[k])ST.exits[k]=cy.exits.map(()=>false);
  document.getElementById('d-exits').innerHTML=cy.exits.map((e,i)=>{
    const done=ST.exits[k][i];
    return`<div class="exit-item${coach?' ro':''}" onclick="${coach?'':(`togExit(${n},${i})`)}">
      <div class="chk${done?' done':''}">${done?'✓':''}</div>
      <span style="${done?'text-decoration:line-through;opacity:.55':''}">${e}</span>
    </div>`;
  }).join('');
  const all=ST.exits[k]&&ST.exits[k].every(Boolean);
  document.getElementById('d-ok').classList.toggle('show',all);
  document.getElementById('d-unlock').textContent=cy.unlock;
}

function togExit(n,i){
  const k=`c${n}`;
  if(!ST.exits[k])ST.exits[k]=getCycles()[n-1].exits.map(()=>false);
  ST.exits[k][i]=!ST.exits[k][i];
  saveSt(SES.user.id,ST);renderCycDet(n);
}

// ════════════════════════════════════════════════════════════════════
// MODAL MÓDULO
// ════════════════════════════════════════════════════════════════════

let editModId=null,editModCtx=null;

function openMod(id,ctx){
  editModId=id;editModCtx=ctx;
  const m=MODS.find(x=>x.id===id);
  const v=ctx==='self'?(ST.levels[id]||0):(loadShared('eval_'+SES.user.id)||{})[id]||0;
  document.getElementById('m-title').textContent=`Módulo ${id} — ${m.name}`;
  document.getElementById('m-sub').textContent=ctx==='self'?'Sua auto-avaliação.':'Avaliação do avaliador.';
  document.getElementById('m-sl').value=v;
  document.getElementById('m-val').textContent=v;
  document.getElementById('m-desc').textContent=LVL[v];
  document.getElementById('m-save').onclick=saveLevel;
  document.getElementById('mod-bg').classList.add('open');
}

function coachOpenMod(uid,id,cur){
  editModId=id;editModCtx='coach_'+uid;
  const m=MODS.find(x=>x.id===id);
  document.getElementById('m-title').textContent=`${uid} — Módulo ${id}`;
  document.getElementById('m-sub').textContent='Avaliação do treinador.';
  document.getElementById('m-sl').value=cur;
  document.getElementById('m-val').textContent=cur;
  document.getElementById('m-desc').textContent=LVL[cur];
  document.getElementById('m-save').onclick=()=>saveLevel();
  document.getElementById('mod-bg').classList.add('open');
}

function slMv(v){document.getElementById('m-val').textContent=v;document.getElementById('m-desc').textContent=LVL[v];}

function saveLevel(){
  const v=parseInt(document.getElementById('m-sl').value);
  if(editModCtx==='self'){
    ST.levels[editModId]=v;saveSt(SES.user.id,ST);renderDash();
  }else if(editModCtx&&editModCtx.startsWith('coach_')){
    const uid=editModCtx.replace('coach_','');
    const eval_=loadShared('eval_'+uid)||{};
    eval_[editModId]=v;saveShared('eval_'+uid,eval_);
    // não publica ainda — só salva para quando o coach decidir enviar
  }
  closeMod();
}

function closeMod(e){
  if(!e||e.target===document.getElementById('mod-bg'))
    document.getElementById('mod-bg').classList.remove('open');
}

// ════════════════════════════════════════════════════════════════════
// ════════════════════════════════════════════════════════════════════
// CHAT — multi-canal
// Canais:
//   "geral"        — todos veem e escrevem
//   "dm_raul"      — raul + thiago
//   "dm_antonio"   — antonio + thiago
// Competidor vê: geral + seu canal individual
// Treinador vê: geral + canal de cada competidor
// ════════════════════════════════════════════════════════════════════

function today(){return new Date().toISOString().split('T')[0];}

// Retorna os canais visíveis para o usuário logado
function myChannels(){
  const uid=SES.user.id;
  const coach=isCoach(uid);
  const athletes=USERS.filter(u=>!isCoach(u.id));
  const channels=[];
  channels.push({key:'geral',label:'# Geral',color:'var(--accent)',desc:'Todos'});
  if(coach){
    athletes.forEach(a=>{
      channels.push({key:'dm_'+a.id,  label:'@ '+a.name.split(' ')[0], color:a.color, desc:a.name});
      channels.push({key:'json_'+a.id, label:'⇄ Status '+a.name.split(' ')[0], color:'#4a5568', desc:'Sincronização · '+a.name, isJson:true, athleteId:a.id});
    });
  }else{
    const coachUser=USERS.find(u=>isCoach(u.id));
    channels.push({key:'dm_'+uid,   label:'@ '+coachUser.name, color:coachUser.color, desc:'Com '+coachUser.name});
    channels.push({key:'json_'+uid, label:'⇄ Status',           color:'#4a5568', desc:'Sincronização com avaliador', isJson:true, athleteId:uid});
  }
  return channels;
}

// Canal ativo (persiste na sessão)
let activeChan='geral';

function renderChannelList(){
  const chs=myChannels();
  const uid=SES.user.id;
  document.getElementById('channel-list').innerHTML=chs.map(ch=>{
    const storageKey=ch.isJson?('chat_json_'+ch.athleteId):('chat_'+ch.key);
    const msgs=loadShared(storageKey)||[];
    const lastSeen=parseInt(localStorage.getItem('seen_'+uid+'_'+ch.key)||'0');
    const unread=ch.isJson
      ? msgs.filter(m=>m.jsonData&&m.ts>lastSeen&&m.uid!==uid).length
      : msgs.filter(m=>m.ts>lastSeen&&m.uid!==uid&&!m.sys).length;
    const jsonCount=ch.isJson?msgs.filter(m=>m.jsonData).length:0;
    return`<div class="ch-item${activeChan===ch.key?' active':''}" onclick="switchChan('${ch.key}')">
      <div class="ch-dot" style="background:${ch.color}"></div>
      <span class="ch-nm">${ch.label}</span>
      ${unread>0?`<span class="ch-badge">${unread}</span>`:''}
      ${ch.isJson&&jsonCount>0&&unread===0?`<span style="font-size:9px;color:var(--muted);background:var(--bg3);border:1px solid var(--border);border-radius:2px;padding:1px 5px">${jsonCount}</span>`:''}
    </div>`;
  }).join('');
}

function switchChan(key){
  activeChan=key;
  // marcar como lido
  localStorage.setItem('seen_'+SES.user.id+'_'+key, Date.now().toString());
  renderChannelList();
  renderChatWindow();
}

function sendChat(){
  const msg=document.getElementById('chat-inp').value.trim();
  if(!msg)return;
  const msgs=loadShared('chat_'+activeChan)||[];
  const now=new Date();
  msgs.push({
    uid:SES.user.id,name:SES.user.name,color:SES.user.color,
    msg,chan:activeChan,
    time:now.toLocaleTimeString('pt-BR',{hour:'2-digit',minute:'2-digit'}),
    date:today(),ts:now.getTime(),
  });
  if(msgs.length>500)msgs.shift();
  saveShared('chat_'+activeChan,msgs);
  localStorage.setItem('seen_'+SES.user.id+'_'+activeChan, Date.now().toString());
  document.getElementById('chat-inp').value='';
  renderChatWindow();
  renderChannelList();
}

function chatKey(e){if(e.key==='Enter')sendChat();}

function setMood(el,emoji){
  document.querySelectorAll('.mood-btn').forEach(b=>b.classList.remove('active'));
  el.classList.add('active');
  ST.mood[today()]=emoji;
  saveSt(SES.user.id,ST);
  // Registra humor no canal ativo como mensagem de sistema
  const msgs=loadShared('chat_'+activeChan)||[];
  const now=new Date();
  msgs.push({uid:SES.user.id,name:SES.user.name,color:SES.user.color,
    msg:`Humor: ${emoji}`,chan:activeChan,
    time:now.toLocaleTimeString('pt-BR',{hour:'2-digit',minute:'2-digit'}),
    date:today(),ts:now.getTime(),sys:true});
  saveShared('chat_'+activeChan,msgs);
  document.getElementById('mood-msg').textContent='Humor registrado.';
  renderChatWindow();
}

function renderChatWindow(){
  const uid=SES.user.id;
  const coach=isCoach(uid);
  const msgs=loadShared('chat_'+activeChan)||[];
  const ch=myChannels().find(c=>c.key===activeChan)||{label:activeChan,color:'var(--accent)'};

  // Label
  document.getElementById('chat-channel-label').innerHTML=
    `<div class="clabel-dot" style="background:${ch.color};box-shadow:0 0 5px ${ch.color}40"></div>${ch.label} <span style="color:var(--muted);font-size:9px">${ch.desc||''}</span>`;

  const wrap=document.getElementById('chat-msgs');

  // ── CANAL JSON ────────────────────────────────────────────────────
  if(ch.isJson){
    const athId=ch.athleteId;
    const lastEntry=msgs.filter(m=>m.jsonData).pop(); // último status enviado
    const lastTs=lastEntry?new Date(lastEntry.ts).toLocaleString('pt-BR'):'—';

    if(coach){
      // Avaliador vê o último JSON enviado e pode aplicar
      wrap.innerHTML=`
        <div style="padding:8px;background:var(--bg3);border:1px solid var(--border);border-radius:4px;margin-bottom:8px">
          <div style="font-size:10px;color:var(--muted);margin-bottom:6px">Último status enviado: <span style="color:var(--muted2)">${lastTs}</span></div>
          ${lastEntry
            ? `<div class="json-block" style="max-height:180px;margin-top:0">${JSON.stringify(lastEntry.jsonData,null,2)}</div>
               <button class="abtn btn-g" onclick="applyJsonStatus('${athId}')" style="margin-top:8px">↓ Aplicar este status</button>
               <div class="small-ok" id="apply-ok-${athId}"></div>`
            : `<div style="font-size:11px;color:var(--muted);font-style:italic">Nenhum status enviado ainda.</div>`}
        </div>
        <div style="font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin-bottom:6px">Histórico de envios</div>
        ${msgs.filter(m=>m.jsonData).map(m=>`
          <div style="display:flex;align-items:center;gap:8px;padding:6px 8px;background:var(--bg3);border:1px solid var(--border);border-radius:3px;margin-bottom:4px">
            <span style="font-size:10px;color:var(--muted)">${m.time} · ${m.date}</span>
            <span style="flex:1;font-size:10px;color:var(--muted2)">Ciclo ${m.jsonData.cycle||'?'} · ${Object.values(m.jsonData.levels||{}).filter(v=>v>0).length}/6 módulos avaliados</span>
          </div>`).join('')||'<div style="font-size:11px;color:var(--muted);font-style:italic">Sem histórico.</div>'}
      `;
    }else{
      // Competidor vê botão de sincronizar
      const st=loadSt(uid);
      const payload=JSON.stringify({uid,name:SES.user.name,...st},null,2);
      wrap.innerHTML=`
        <div style="text-align:center;padding:20px 0 10px">
          <div style="font-size:28px;margin-bottom:10px">⇄</div>
          <div style="font-size:13px;color:var(--text);margin-bottom:6px">Canal de Sincronização</div>
          <div style="font-size:11px;color:var(--muted2);margin-bottom:16px;max-width:280px;margin-left:auto;margin-right:auto">
            Clique em Sincronizar para enviar seu status atual ao avaliador. Ele pode aplicar diretamente.
          </div>
          <button onclick="syncJsonStatus()" style="background:rgba(0,232,122,.12);border:1px solid var(--accent);color:var(--accent);font-family:var(--mono);font-size:12px;padding:12px 28px;border-radius:4px;cursor:pointer;transition:all .15s;letter-spacing:.04em">
            ↑ Sincronizar Status
          </button>
          <div id="sync-ok" style="font-size:11px;color:var(--accent);margin-top:10px;min-height:18px"></div>
        </div>
        <div style="font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin:10px 0 6px">Histórico de envios</div>
        ${msgs.filter(m=>m.jsonData&&m.uid===uid).map(m=>`
          <div style="display:flex;align-items:center;gap:8px;padding:6px 8px;background:var(--bg3);border:1px solid var(--border);border-radius:3px;margin-bottom:4px">
            <span style="font-size:10px;color:var(--muted)">${m.time} · ${m.date}</span>
            <span style="flex:1;font-size:10px;color:var(--muted2)">Ciclo ${m.jsonData.cycle||'?'} enviado</span>
          </div>`).join('')||'<div style="font-size:11px;color:var(--muted);font-style:italic">Sem envios anteriores.</div>'}
      `;
    }
    // Esconde input de texto em canal JSON
    document.getElementById('chat-inp').closest('.chat-input-wrap').style.display='none';
    wrap.scrollTop=wrap.scrollHeight;

    // Atualizar heatmap/streak igual ao normal
    renderChatStats();
    return;
  }

  // ── CANAL NORMAL ─────────────────────────────────────────────────
  document.getElementById('chat-inp').closest('.chat-input-wrap').style.display='flex';

  if(!msgs.length){
    wrap.innerHTML='<div style="color:var(--muted);font-size:11px;padding:8px 0;text-align:center">Sem mensagens ainda.</div>';
  }else{
    let lastDate='';
    wrap.innerHTML=msgs.map(m=>{
      const mine=m.uid===uid;
      let dateDiv='';
      if(m.date!==lastDate){
        lastDate=m.date;
        const label=m.date===today()?'Hoje':new Date(m.date+'T00:00').toLocaleDateString('pt-BR',{weekday:'long',day:'2-digit',month:'short'});
        dateDiv=`<div style="text-align:center;font-size:9px;color:var(--muted);padding:8px 0;letter-spacing:.06em;text-transform:uppercase">${label}</div>`;
      }
      if(m.sys){
        return dateDiv+`<div style="text-align:center;font-size:10px;color:var(--muted);padding:3px 0">${m.name.split(' ')[0]}: ${m.msg}</div>`;
      }
      return dateDiv+`<div class="msg-row${mine?' mine':''}">
        <div class="msg-av" style="background:${m.color}22;border:1px solid ${m.color}44;color:${m.color}">${m.name[0]}</div>
        <div>
          <div class="msg-bubble">${m.msg}</div>
          <div class="msg-meta">${mine?'':'<span>'+m.name.split(' ')[0]+' · </span>'}<span>${m.time}</span></div>
        </div>
      </div>`;
    }).join('');
  }
  wrap.scrollTop=wrap.scrollHeight;
  renderChatStats();
}

function syncJsonStatus(){
  const uid=SES.user.id;
  const st=loadSt(uid);
  const payload={uid,name:SES.user.name,...st};
  const msgs=loadShared('chat_json_'+uid)||[];
  const now=new Date();
  msgs.push({
    uid,name:SES.user.name,color:SES.user.color,
    msg:'Status sincronizado',jsonData:payload,
    time:now.toLocaleTimeString('pt-BR',{hour:'2-digit',minute:'2-digit'}),
    date:today(),ts:now.getTime(),
  });
  if(msgs.length>50)msgs.shift();
  saveShared('chat_json_'+uid,msgs);
  localStorage.setItem('seen_'+uid+'_json_'+uid,Date.now().toString());
  const el=document.getElementById('sync-ok');
  if(el){el.textContent='✓ Status enviado ao avaliador';setTimeout(()=>el.textContent='',3000);}
  renderChatWindow();
  renderChannelList();
}

function applyJsonStatus(athId){
  const msgs=loadShared('chat_json_'+athId)||[];
  const last=msgs.filter(m=>m.jsonData).pop();
  if(!last){return;}
  const{uid:_,name:__,...st}=last.jsonData;
  saveSt(athId,st);
  saveShared('status_updated_'+athId,new Date().toLocaleString('pt-BR'));
  const el=document.getElementById('apply-ok-'+athId);
  if(el){el.textContent='✓ Status aplicado';setTimeout(()=>{if(el)el.textContent='';},2500);}
  showToast(`✓ Status de ${USERS.find(u=>u.id===athId)?.name.split(' ')[0]} aplicado`,'green');
}

function renderChatStats(){
  const uid=SES.user.id;
  // Heatmap/streak baseado em mensagens normais (não JSON)
  const allMsgs=myChannels()
    .filter(c=>!c.isJson)
    .flatMap(c=>(loadShared('chat_'+c.key)||[]).filter(m=>m.uid===uid&&!m.sys));
  const d=today();
  const days=[];
  for(let i=6;i>=0;i--){
    const dx=new Date();dx.setDate(dx.getDate()-i);
    const dk=dx.toISOString().split('T')[0];
    days.push({dk,has:allMsgs.some(m=>m.date===dk),isToday:i===0,d:dx});
  }
  document.getElementById('heatmap').innerHTML=days.map(d2=>{
    const col=d2.has?'var(--accent)':'var(--border)';
    const brd=d2.isToday?'1px solid var(--accent)':'1px solid transparent';
    const dy=d2.d.toLocaleDateString('pt-BR',{weekday:'short'}).replace('.','').toUpperCase();
    return`<div style="text-align:center;flex:1"><div style="height:18px;background:${col};border-radius:2px;border:${brd};opacity:${d2.has?1:.28}"></div><div style="font-size:8px;color:var(--muted);margin-top:3px">${dy}</div></div>`;
  }).join('');
  let streak=0;
  for(let i=0;i<60;i++){
    const dx=new Date();dx.setDate(dx.getDate()-i);
    if(allMsgs.some(m=>m.date===dx.toISOString().split('T')[0]))streak++;else if(i>0)break;
  }
  document.getElementById('streak-n').textContent=streak;
  document.getElementById('streak-m').textContent=streak===0?'Escreva hoje.':streak<3?'Começando.':streak<7?'Consistência.':streak<14?'Ritmo sólido.':'Em operação.';
  const sm=ST.mood[d];
  if(sm)document.querySelectorAll('.mood-btn').forEach(b=>b.classList.toggle('active',b.textContent===sm));
}

function renderChat(){
  // Garante canal válido para o usuário
  const valid=myChannels().map(c=>c.key);
  if(!valid.includes(activeChan))activeChan='geral';
  renderChannelList();
  renderChatWindow();
  renderChatStatusLog();
}

// ════════════════════════════════════════════════════════════════════
// AGENDA
// ════════════════════════════════════════════════════════════════════

function renderAgenda(){
  const coach=isCoach(SES.user.id);
  document.getElementById('prova-add-card').style.display=coach?'block':'none';
  const provas=loadShared('provas')||[];
  const sorted=[...provas.entries()].sort((a,b)=>new Date(a[1].date)-new Date(b[1].date));
  const tipoColor={estadual:'rgba(245,166,35,.1)',nacional:'rgba(0,232,122,.1)',mundial:'rgba(0,136,255,.1)',simulado:'rgba(167,139,250,.1)',outro:'rgba(255,255,255,.05)'};
  const tipoText={estadual:'var(--amber)',nacional:'var(--accent)',mundial:'var(--blue)',simulado:'var(--purple)',outro:'var(--muted2)'};
  document.getElementById('provas-list').innerHTML=sorted.length
    ?sorted.map(([origIdx,p])=>{
      const dt=new Date(p.date+'T00:00');
      const passed=dt<new Date();
      const day=dt.toLocaleDateString('pt-BR',{day:'2-digit'});
      const mon=dt.toLocaleDateString('pt-BR',{month:'short'}).replace('.','').toUpperCase();
      const yr=dt.getFullYear();
      return`<div class="prova-item" style="${passed?'opacity:.45':''}">
        <div style="text-align:center;min-width:44px">
          <div class="prova-date">${day}</div>
          <div class="prova-month">${mon} ${yr}</div>
        </div>
        <div class="prova-info">
          <div class="prova-nm">${p.name}</div>
          <div class="prova-loc">${p.local||'—'}</div>
        </div>
        <div class="prova-tag" style="background:${tipoColor[p.tipo]||tipoColor.outro};color:${tipoText[p.tipo]||tipoText.outro}">${p.tipo}</div>
        ${coach?`<button class="prova-del" onclick="delProva(${origIdx})">✕</button>`:''}
      </div>`;
    }).join('')
    :'<div style="font-size:11px;color:var(--muted);font-style:italic;padding:8px 0">Nenhuma prova cadastrada.</div>';
}

function addProva(){
  const nm=document.getElementById('prova-nm').value.trim();
  const dt=document.getElementById('prova-dt').value;
  if(!nm||!dt){document.getElementById('prova-ok').textContent='Preencha nome e data.';return;}
  const provas=loadShared('provas')||[];
  provas.push({name:nm,date:dt,local:document.getElementById('prova-loc').value.trim(),tipo:document.getElementById('prova-tipo').value});
  saveShared('provas',provas);
  ['prova-nm','prova-dt','prova-loc'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('prova-ok').textContent='✓ Adicionada';
  setTimeout(()=>document.getElementById('prova-ok').textContent='',2000);
  renderAgenda();
}

function delProva(i){
  if(!confirm('Remover esta prova?'))return;
  const provas=loadShared('provas')||[];
  provas.splice(i,1);saveShared('provas',provas);renderAgenda();
}

// ════════════════════════════════════════════════════════════════════
// ROTINA
// ════════════════════════════════════════════════════════════════════

function renderWeek(){
  const bloco=loadShared('bloco')||DEFAULT_BLOCO;
  document.getElementById('bloco-diario').innerHTML=bloco.map(s=>
    `<div style="padding:8px 10px;${s.cor?`background:${s.cor}15;border:1px solid ${s.cor}30;`:''}border-radius:3px;margin-bottom:5px;font-size:11px">
      <span style="color:${s.cor||'var(--muted)'};display:block;font-size:10px;letter-spacing:.06em;margin-bottom:2px">${s.time}</span>${s.txt}
    </div>`
  ).join('');
  const sem=loadShared('semanal')||DEFAULT_SEMANAL;
  document.getElementById('rotina-semanal').innerHTML=sem.map(d=>
    `<div class="day-card" style="border-color:${d.cor}40">
      <div class="day-nm" style="color:${d.cor}">${d.day}</div>
      <div style="font-size:11px;color:var(--muted2)">${d.mod} — ${d.sub}</div>
      <div style="font-size:10px;color:var(--muted);margin-top:6px">${d.nota}</div>
    </div>`
  ).join('');
}

// ════════════════════════════════════════════════════════════════════
// COACH PANEL
// ════════════════════════════════════════════════════════════════════

function renderCoach(){
  const aths=USERS.filter(u=>!isCoach(u.id));
  const avName=SES.user.name;
  document.getElementById('coach-grid').innerHTML=aths.map(a=>{
    const ast=loadSt(a.id);
    const eval_=loadShared('eval_'+a.id)||{};
    const evals=Object.values(eval_).filter(v=>v>0);
    const eavg=evals.length?(evals.reduce((x,y)=>x+y,0)/evals.length).toFixed(1):'—';
    const cy=getCycles()[ast.cycle-1];
    const fn=a.name.split(' ')[0];
    const pendingPw=isFirstLogin(a.id);
    const fb=loadShared('feedback_'+a.id)||'';
    const meta=loadShared('meta_'+a.id)||'';
    return`<div class="ath-card">
      <div class="ath-hdr">
        <div class="ath-av" style="background:${a.color}22;border:1px solid ${a.color}44;color:${a.color}">${a.name[0]}</div>
        <div><div class="ath-nm">${a.name}</div><div class="ath-meta">Ciclo ${ast.cycle} — ${cy?cy.name:'—'} · Avaliação média ${eavg}/10</div></div>
      </div>
      ${pendingPw?`<div class="warn-badge">⚠ ${fn} ainda não trocou a senha padrão.</div>`:''}

      <div style="font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin-bottom:8px">
        Auto-avaliação de ${fn}
      </div>
      ${MODS.map(m=>{
        const sv=ast.levels[m.id]||0,spct=sv*10;
        return`<div class="mrow ro"><span class="mid">${m.id}</span><span class="mnm">${m.name}</span>
          <div class="bt"><div class="bf" style="width:${spct}%;background:${m.color}"></div></div>
          <span class="bv" style="color:${sv>=7?m.color:'#4a5568'}">${sv}/10</span></div>`;
      }).join('')}

      <div style="font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin:12px 0 8px">
        Avaliação do Avaliador <span style="color:var(--muted2);font-size:9px">(não enviado até publicar)</span>
      </div>
      ${MODS.map(m=>{
        const cv=eval_[m.id]||0,cpct=cv*10;
        const tcy=cy?.target||{estadual:7,mundial:10};
        const cc=cv>=tcy.mundial?'#00e87a':cv>=tcy.estadual?'#f5a623':'#ff4b6e';
        return`<div class="mrow" onclick="coachOpenMod('${a.id}','${m.id}',${cv})">
          <span class="mid">${m.id}</span><span class="mnm">${m.name}</span>
          <div class="bt"><div class="bf" style="width:${cpct}%;background:${m.color}"></div></div>
          <span class="bv" style="color:${cc}">${cv}/10</span>
          <span class="bbtn">↑</span></div>`;
      }).join('')}
      <button class="abtn btn-pu" onclick="publishEval('${a.id}')" style="margin-top:8px">Publicar Avaliação para ${fn}</button>
      <div class="small-ok" id="eval-ok-${a.id}"></div>

      <div style="font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin:12px 0 4px">Ciclo</div>
      <div style="font-size:11px;color:var(--muted2);margin-bottom:8px">${cy?cy.name:'—'} (${ast.cycle}/21)</div>
      <button class="abtn btn-g" style="margin-top:0" onclick="coachAdvCyc('${a.id}')">↑ Avançar Ciclo de ${fn}</button>

      <div style="font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin:12px 0 4px">Feedback para ${fn}</div>
      <textarea class="ta" id="fb-${a.id}" placeholder="Feedback para ${fn}...">${fb}</textarea>
      <button class="abtn btn-b" onclick="saveFb('${a.id}')">Enviar Feedback</button>
      <div class="small-ok" id="fb-ok-${a.id}"></div>

      <div style="font-size:9px;color:var(--muted);text-transform:uppercase;letter-spacing:.1em;margin:12px 0 4px">Meta do Dia para ${fn}</div>
      <input class="inp" id="meta-${a.id}" value="${meta}" placeholder="Ex: Completar MemLab 2 hoje" style="margin-top:0">
      <button class="abtn btn-a" onclick="saveMeta('${a.id}')" style="margin-top:8px">Definir Meta do Dia</button>
      <div class="small-ok" id="meta-ok-${a.id}"></div>

      <div style="font-size:9px;color:var(--red);text-transform:uppercase;letter-spacing:.1em;margin:12px 0 4px">Senha</div>
      <div style="font-size:11px;color:var(--muted2);margin-bottom:8px">Reset → <code style="color:var(--amber)">${a.id}123</code> e força troca no login.</div>
      <button class="abtn btn-r" style="margin-top:0" onclick="coachReset('${a.id}','${fn}')">⚠ Resetar senha de ${fn}</button>
      <div class="small-ok" id="pw-ok-${a.id}"></div>
    </div>`;
  }).join('');
}

function publishEval(uid){
  const eval_=loadShared('eval_'+uid)||{};
  saveShared('eval_'+uid,eval_);
  saveShared('eval_date_'+uid,new Date().toLocaleDateString('pt-BR'));
  const el=document.getElementById('eval-ok-'+uid);
  el.textContent='✓ Avaliação publicada';setTimeout(()=>el.textContent='',2500);
}

function coachAdvCyc(uid){
  const ast=loadSt(uid);if(ast.cycle>=21)return;
  const fn=USERS.find(u=>u.id===uid).name.split(' ')[0];
  if(!confirm(`Avançar ciclo de ${fn}?`))return;
  ast.cycle++;saveSt(uid,ast);renderCoach();
}

function saveFb(uid){
  const txt=document.getElementById('fb-'+uid).value.trim();
  saveShared('feedback_'+uid,txt);
  saveShared('feedback_date_'+uid,new Date().toLocaleDateString('pt-BR'));
  const el=document.getElementById('fb-ok-'+uid);
  el.textContent='✓ Feedback enviado';setTimeout(()=>el.textContent='',2000);
}

function saveMeta(uid){
  const txt=document.getElementById('meta-'+uid).value.trim();
  saveShared('meta_'+uid,txt);
  const el=document.getElementById('meta-ok-'+uid);
  el.textContent='✓ Meta definida';setTimeout(()=>el.textContent='',2000);
}

async function coachReset(uid,fn){
  if(!confirm(`Resetar senha de ${fn}?\n\nSenha voltará para "${uid}123".\nNo próximo login ele será obrigado a trocar.`))return;
  await resetPw(uid);
  showToast(`✓ Senha de ${fn} resetada para ${uid}123`,'amber');
}

// Toast global — CSS base fixo, não concatenado
function showToast(msg,type='green'){
  let t=document.getElementById('global-toast');
  if(!t){
    t=document.createElement('div');
    t.id='global-toast';
    document.body.appendChild(t);
  }
  const base='position:fixed;top:24px;right:24px;z-index:99999;padding:10px 18px;border-radius:4px;font-family:var(--mono);font-size:12px;pointer-events:none;max-width:360px;transition:opacity .3s;';
  const colors={
    green:base+'background:rgba(0,232,122,.15);border:1px solid #00e87a;color:#00e87a;',
    amber:base+'background:rgba(245,166,35,.15);border:1px solid #f5a623;color:#f5a623;',
    red:  base+'background:rgba(255,75,110,.15);border:1px solid #ff4b6e;color:#ff4b6e;',
  };
  t.style.cssText=(colors[type]||colors.green)+'opacity:1;';
  t.textContent=msg;
  clearTimeout(t._timer);
  t._timer=setTimeout(()=>{ t.style.opacity='0'; },3500);
}


// ════════════════════════════════════════════════════════════════════
// INIT
// ════════════════════════════════════════════════════════════════════

async function init(){
  for(const u of USERS)await ensureDefault(u.id);
  renderLoginUsers();
  showScreen('login');
  document.getElementById('pw-inp').addEventListener('keydown',e=>{if(e.key==='Enter')doLogin();});
}
init();
</script>
</body>
</html>
