---
permalink: /csp-planning
title: CSP 7-Week Project Plan
search_exclude: true
---
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSP 7-Week Project Plan</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: Arial, sans-serif; background: #f5f5f5; padding: 24px; }
  h1 { text-align: center; font-size: 20px; margin-bottom: 6px; color: #222; }
  p.sub { text-align: center; font-size: 13px; color: #666; margin-bottom: 20px; }

  .gantt { width: 100%; border-collapse: collapse; background: white; border-radius: 10px; overflow: hidden; box-shadow: 0 2px 12px rgba(0,0,0,0.1); }

  .gantt th, .gantt td { padding: 0; border: 1px solid #e0e0e0; }

  /* Week header row */
  .wk-header { font-size: 12px; font-weight: bold; text-align: center; padding: 8px 4px; }
  .wk1, .wk2 { background: #B5D4F4; color: #0C447C; }
  .wk3, .wk4 { background: #C0DD97; color: #27500A; }
  .wk5, .wk6 { background: #FAC775; color: #633806; }
  .wk7       { background: #F09595; color: #791F1F; }

  /* Date sub row */
  .date-row td { font-size: 10px; color: #999; text-align: center; padding: 2px 4px; background: #fafafa; }

  /* Row label column */
  .row-label { font-size: 11px; font-weight: bold; color: #444; text-align: right; padding: 6px 10px 6px 8px; background: #f9f9f9; white-space: nowrap; min-width: 90px; }

  /* Task cells */
  .cell { font-size: 10px; text-align: center; padding: 6px 3px; line-height: 1.35; vertical-align: middle; min-width: 80px; }
  .empty { background: #f9f9f9; }

  /* PPR colors */
  .ppr-light  { background: #CECBF6; color: #26215C; }
  .ppr-mid    { background: #AFA9EC; color: #26215C; }
  .ppr-dark   { background: #7F77DD; color: white; }
  .ppr-submit { background: #534AB7; color: white; font-weight: bold; }

  /* Feature colors */
  .feat-light  { background: #9FE1CB; color: #04342C; }
  .feat-mid    { background: #5DCAA5; color: #04342C; }
  .feat-dark   { background: #1D9E75; color: white; }

  /* Database colors */
  .db-light { background: #C0DD97; color: #173404; }
  .db-dark  { background: #97C459; color: #173404; }

  /* AI/Auth colors */
  .ai-light { background: #FAEEDA; color: #633806; }
  .ai-mid   { background: #FAC775; color: #412402; }
  .ai-dark  { background: #EF9F27; color: #412402; }

  /* UI/UX colors */
  .ui-light { background: #FAECE7; color: #4A1B0C; }
  .ui-mid   { background: #F5C4B3; color: #4A1B0C; }
  .ui-dark  { background: #D85A30; color: white; }

  /* Blog colors */
  .blog-light { background: #D3D1C7; color: #2C2C2A; }
  .blog-mid   { background: #B4B2A9; color: #2C2C2A; }
  .blog-dark  { background: #888780; color: white; }
  .blog-xdark { background: #5F5E5A; color: white; }

  /* Demo colors */
  .demo-light  { background: #FAEEDA; color: #633806; }
  .demo-mid    { background: #FAC775; color: #412402; }
  .demo-dark   { background: #BA7517; color: white; font-weight: bold; }
  .natm        { background: #E24B4A; color: white; font-weight: bold; }

  /* AP Prep colors */
  .ap-light { background: #FBEAF0; color: #72243E; }
  .ap-mid   { background: #F4C0D1; color: #4B1528; }
  .ap-dark  { background: #ED93B1; color: #4B1528; }
  .ap-xdark { background: #D4537E; color: white; }
  .ap-exam  { background: #993556; color: white; font-weight: bold; }

  /* Legend */
  .legend { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 18px; font-size: 11px; }
  .leg { display: flex; align-items: center; gap: 5px; color: #555; }
  .leg-dot { width: 12px; height: 12px; border-radius: 3px; flex-shrink: 0; }

  /* Deadline badge */
  .badge { display: inline-block; background: #fff3; border: 1px solid rgba(255,255,255,0.5); border-radius: 3px; font-size: 9px; padding: 1px 3px; margin-top: 2px; }
</style>
</head>
<body>

<h1>CSP 7-Week Project Plan</h1>
<p class="sub">March 13 – April 30, 2026 &nbsp;|&nbsp; Chamber of Commerce Prototype + PPR Submission</p>

<table class="gantt">
  <colgroup>
    <col style="width:90px">
    <col style="width:calc((100% - 90px)/7)">
    <col style="width:calc((100% - 90px)/7)">
    <col style="width:calc((100% - 90px)/7)">
    <col style="width:calc((100% - 90px)/7)">
    <col style="width:calc((100% - 90px)/7)">
    <col style="width:calc((100% - 90px)/7)">
    <col style="width:calc((100% - 90px)/7)">
  </colgroup>
  <thead>
    <tr>
      <th></th>
      <th class="wk-header wk1">Week 1</th>
      <th class="wk-header wk2">Week 2</th>
      <th class="wk-header wk3">Week 3</th>
      <th class="wk-header wk4">Week 4</th>
      <th class="wk-header wk5">Week 5</th>
      <th class="wk-header wk6">Week 6</th>
      <th class="wk-header wk7">Week 7</th>
    </tr>
  </thead>
  <tbody>
    <tr class="date-row">
      <td></td>
      <td>Mar 13</td>
      <td>Mar 20</td>
      <td>Mar 27</td>
      <td>Apr 3</td>
      <td>Apr 10</td>
      <td>Apr 17</td>
      <td>Apr 24</td>
    </tr>

    <!-- PPR -->
    <tr>
      <td class="row-label">📋 PPR Prep</td>
      <td class="cell ppr-light">Clean screenshots<br>no comments</td>
      <td class="cell ppr-light">Verify procedure<br>+ list usage</td>
      <td class="cell ppr-mid">Stage to AP<br>Digital Portfolio</td>
      <td class="cell ppr-mid">Revise with<br>instructor</td>
      <td class="cell ppr-dark">Final check:<br>all 4 segments</td>
      <td class="cell ppr-dark">Polish &amp;<br>buffer</td>
      <td class="cell ppr-submit">⚑ SUBMIT<br>Apr 30</td>
    </tr>

    <!-- Features -->
    <tr>
      <td class="row-label">🔧 3+ Features</td>
      <td class="cell feat-light">Pick 3 features<br>assign owners</td>
      <td class="cell feat-light">Write issues +<br>design docs</td>
      <td class="cell feat-mid">Build<br>Feature #1</td>
      <td class="cell feat-mid">Build<br>Feature #2</td>
      <td class="cell feat-mid">Build<br>Feature #3</td>
      <td class="cell feat-dark">Integrate +<br>test all</td>
      <td class="cell feat-dark">Bug fixes +<br>edge cases</td>
    </tr>

    <!-- Database -->
    <tr>
      <td class="row-label">🗄️ Database</td>
      <td class="cell empty"></td>
      <td class="cell db-light">Schema design<br>+ setup</td>
      <td class="cell db-dark">Implement<br>CRUD</td>
      <td class="cell db-dark">Backup /<br>restore</td>
      <td class="cell empty"></td>
      <td class="cell empty"></td>
      <td class="cell empty"></td>
    </tr>

    <!-- AI / Auth -->
    <tr>
      <td class="row-label">🤖 AI / Auth</td>
      <td class="cell empty"></td>
      <td class="cell ai-light">Plan flow &amp;<br>architecture</td>
      <td class="cell ai-mid">Prototype<br>integration</td>
      <td class="cell ai-dark">Connect to<br>backend</td>
      <td class="cell ai-dark">Test &amp;<br>refine</td>
      <td class="cell empty"></td>
      <td class="cell empty"></td>
    </tr>

    <!-- UI/UX -->
    <tr>
      <td class="row-label">🎨 UI / UX</td>
      <td class="cell empty"></td>
      <td class="cell empty"></td>
      <td class="cell ui-light">Responsive<br>layout</td>
      <td class="cell ui-mid">Accessibility<br>pass</td>
      <td class="cell ui-dark">Visual<br>polish</td>
      <td class="cell ui-dark">Design<br>review</td>
      <td class="cell ui-dark">Last touches<br>pre-demo</td>
    </tr>

    <!-- Blog / Docs -->
    <tr>
      <td class="row-label">📝 Blog / Docs</td>
      <td class="cell blog-light">Create blog<br>skeleton</td>
      <td class="cell blog-light">Partner needs<br>assessment</td>
      <td class="cell blog-mid">Technical<br>write-ups</td>
      <td class="cell blog-mid">PR + commit<br>evidence</td>
      <td class="cell blog-dark">Code highlights<br>+ testing docs</td>
      <td class="cell blog-dark">LinkedIn<br>page draft</td>
      <td class="cell blog-xdark">Finalize blog<br>+ LinkedIn</td>
    </tr>

    <!-- Demo / N@tM -->
    <tr>
      <td class="row-label">🎤 Demo / N@tM</td>
      <td class="cell empty"></td>
      <td class="cell empty"></td>
      <td class="cell empty"></td>
      <td class="cell demo-light">Incorporate<br>partner feedback</td>
      <td class="cell demo-mid">Pitch script<br>draft</td>
      <td class="cell demo-dark">Instructor Demo<br>(Monday)</td>
      <td class="cell natm">🏛 N@tM<br>Thursday 6pm</td>
    </tr>

    <!-- AP Prep -->
    <tr>
      <td class="row-label">📚 AP Prep</td>
      <td class="cell ap-light">Skim PPR<br>written Qs</td>
      <td class="cell ap-light">Review key<br>concepts</td>
      <td class="cell ap-mid">Practice written<br>responses</td>
      <td class="cell ap-mid">Practice written<br>responses</td>
      <td class="cell ap-dark">PPR review<br>in hand</td>
      <td class="cell ap-xdark">Light<br>review</td>
      <td class="cell ap-exam">Final prep<br>→ May 12–16</td>
    </tr>
  </tbody>
</table>

<div class="legend">
  <div class="leg"><div class="leg-dot" style="background:#7F77DD"></div> PPR work</div>
  <div class="leg"><div class="leg-dot" style="background:#534AB7"></div> PPR deadline Apr 30</div>
  <div class="leg"><div class="leg-dot" style="background:#1D9E75"></div> Feature build</div>
  <div class="leg"><div class="leg-dot" style="background:#97C459"></div> Database</div>
  <div class="leg"><div class="leg-dot" style="background:#EF9F27"></div> AI / Auth</div>
  <div class="leg"><div class="leg-dot" style="background:#D85A30"></div> UI / UX</div>
  <div class="leg"><div class="leg-dot" style="background:#888780"></div> Blog / Docs</div>
  <div class="leg"><div class="leg-dot" style="background:#E24B4A"></div> N@tM showcase</div>
  <div class="leg"><div class="leg-dot" style="background:#993556"></div> AP Exam (May 12–16)</div>
</div>

</body>
</html>
