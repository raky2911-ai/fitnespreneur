<!doctype html><html><head><meta charset=utf8><meta name=viewport content="width=device-width,initial-scale=1,viewport-fit=cover"><style>:root{color-scheme:light;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}html{scroll-padding-top:env(safe-area-inset-top,0px)}body{margin:0;padding:0;font:14px -apple-system,BlinkMacSystemFont,sans-serif;background:#faf9f5;color:#141413}img{max-width:100%}[hidden]:not([hidden=until-found i]){display:none!important}</style></head><body>
<title>Fitnesspreneur Playbook</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@600;700;800&family=IBM+Plex+Sans:wght@400;500;600&family=IBM+Plex+Mono:wght@500&display=swap">
<style>
/* Layout: sticky daftar isi di kiri (desktop), satu kolom di ponsel. Tiap bab memakai pola baris WHY > HOW > CONTOH > KESALAHAN > PERTANYAAN > LATIHAN > OUTPUT. Warna fase: konsep=cobalt, discovery=oranye pain, aplikasi=hijau, aksi=emas. */
:root{
  --bg:#F1F4F7; --surface:#FFFFFF; --ink:#14212B; --muted:#52606D; --line:#D4DBE2;
  --accent:#1F4FD8; --accent-soft:#E3EAFB; --on-accent:#FFFFFF;
  --pain:#C2410C; --pain-soft:#FCEADF;
  --ok:#23704A; --ok-soft:#DFF0E6;
  --gold:#8A5A00; --gold-soft:#F8EBCB;
  --f-display:'Barlow Condensed','Arial Narrow',Impact,sans-serif;
  --f-body:'IBM Plex Sans',system-ui,-apple-system,'Segoe UI',sans-serif;
  --f-mono:'IBM Plex Mono',ui-monospace,Menlo,Consolas,monospace;
}
@media (prefers-color-scheme: dark){:root:not([data-theme="light"]){
  --bg:#0E151B; --surface:#16202A; --ink:#E7ECF1; --muted:#9BA8B4; --line:#2B3744;
  --accent:#86A6FF; --accent-soft:#19284A; --on-accent:#0E151B;
  --pain:#FF9D6B; --pain-soft:#3A2217;
  --ok:#74D19C; --ok-soft:#14301F;
  --gold:#EBBC57; --gold-soft:#3A2D0E; color-scheme:dark}}
:root[data-theme="dark"]{
  --bg:#0E151B; --surface:#16202A; --ink:#E7ECF1; --muted:#9BA8B4; --line:#2B3744;
  --accent:#86A6FF; --accent-soft:#19284A; --on-accent:#0E151B;
  --pain:#FF9D6B; --pain-soft:#3A2217;
  --ok:#74D19C; --ok-soft:#14301F;
  --gold:#EBBC57; --gold-soft:#3A2D0E; color-scheme:dark}

*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:1rem}
body{background:var(--bg);color:var(--ink);font:400 16px/1.65 var(--f-body);padding-inline:16px;padding-block:0 4rem;-webkit-text-size-adjust:100%}
a{color:var(--accent)}
:focus-visible{outline:3px solid var(--accent);outline-offset:2px}
h1,h2,h3,h4{margin:0;text-wrap:balance}
p{margin:0 0 .8em}
ul,ol{margin:0 0 .8em;padding-left:1.25em}
li{margin-bottom:.3em}
li>ul{margin-top:.3em}
em{font-style:italic}
strong{font-weight:600}
@media (prefers-reduced-motion: reduce){html{scroll-behavior:auto}}

.shell{max-width:76rem;margin-inline:auto}
.hero{padding-block:3rem 2rem;border-bottom:2px solid var(--ink);margin-bottom:2rem}
.kicker{font:500 .75rem/1.4 var(--f-mono);letter-spacing:.12em;text-transform:uppercase;color:var(--muted);margin-bottom:.9rem}
.hero h1{font:800 clamp(2.8rem,9vw,6rem)/.92 var(--f-display);text-transform:uppercase;letter-spacing:.005em}
.hero h1 span{color:var(--accent)}
.hero .pillars{font:600 clamp(1.2rem,3.4vw,1.7rem)/1.2 var(--f-display);text-transform:uppercase;letter-spacing:.04em;margin:1.2rem 0 .4rem}
.hero .sub{color:var(--muted);max-width:42rem;margin-top:.6rem}
.meta{display:flex;flex-wrap:wrap;gap:.5rem;margin-top:1.4rem}
.chip{font:500 .72rem/1 var(--f-mono);letter-spacing:.06em;text-transform:uppercase;padding:.5rem .65rem;border:1px solid var(--line);background:var(--surface);color:var(--muted);border-radius:4px}

.layout{display:grid;grid-template-columns:minmax(0,1fr);gap:1.5rem}
@media (min-width:1000px){.layout{grid-template-columns:17rem minmax(0,1fr);gap:3rem}}
.toc{align-self:start;font-size:.9rem}
@media (min-width:1000px){.toc{position:sticky;top:1rem;max-height:calc(100vh - 2rem);overflow:auto;padding-right:.5rem}}
.toc details{border:1px solid var(--line);background:var(--surface);border-radius:6px;padding:.6rem .9rem}
@media (min-width:1000px){.toc details{border:0;background:none;padding:0}}
.toc summary{font:700 1rem/1.2 var(--f-display);text-transform:uppercase;letter-spacing:.08em;cursor:pointer;padding:.3rem 0}
@media (min-width:1000px){.toc summary{pointer-events:none;list-style:none}.toc summary::-webkit-details-marker{display:none}}
.toc h4{font:500 .68rem/1.3 var(--f-mono);letter-spacing:.12em;text-transform:uppercase;margin:1rem 0 .3rem;color:var(--ph,var(--muted))}
.toc ol{list-style:none;padding:0;margin:0}
.toc li{margin:0}
.toc a{display:block;padding:.28rem .5rem;margin-left:-.5rem;color:var(--ink);text-decoration:none;border-radius:4px;line-height:1.35}
.toc a:hover{background:var(--accent-soft)}

main{min-width:0}
.sec{margin-bottom:3.5rem}
.sec-intro{background:var(--surface);border:1px solid var(--line);border-radius:8px;padding:1.4rem}
.sec-intro h2,.part-h h2{font:800 clamp(1.8rem,5vw,2.6rem)/1 var(--f-display);text-transform:uppercase;margin-bottom:.8rem}
.part-h{display:flex;flex-wrap:wrap;gap:.5rem 1.2rem;align-items:baseline;justify-content:space-between;border-top:6px solid var(--ph);padding-top:.9rem;margin:3.5rem 0 1.5rem}
.part-h h2{margin:0;color:var(--ph)}
.part-h p{margin:0;font:500 .8rem/1.4 var(--f-mono);letter-spacing:.06em;text-transform:uppercase;color:var(--muted)}
[data-phase="konsep"]{--ph:var(--accent);--ph-soft:var(--accent-soft)}
[data-phase="discovery"]{--ph:var(--pain);--ph-soft:var(--pain-soft)}
[data-phase="aplikasi"]{--ph:var(--ok);--ph-soft:var(--ok-soft)}
[data-phase="aksi"]{--ph:var(--gold);--ph-soft:var(--gold-soft)}

.howto{display:grid;gap:.8rem;grid-template-columns:repeat(auto-fit,minmax(15rem,1fr));margin:1rem 0}
.howto div{border-left:4px solid var(--accent);background:var(--surface);padding:.7rem .9rem;border-radius:0 6px 6px 0}
.howto b{display:block;font:700 1.05rem/1.2 var(--f-display);text-transform:uppercase;letter-spacing:.04em;margin-bottom:.2rem}
.legend{display:grid;gap:.4rem .9rem;grid-template-columns:repeat(auto-fit,minmax(17rem,1fr));font-size:.9rem;margin:1rem 0 0}
.legend span{display:grid;grid-template-columns:7.5rem 1fr;gap:.5rem;align-items:baseline}
.tag{font:500 .68rem/1.2 var(--f-mono);letter-spacing:.08em;text-transform:uppercase;color:var(--ph,var(--accent))}

.chap{background:var(--surface);border:1px solid var(--line);border-radius:8px;margin-bottom:1.6rem;overflow:hidden}
.chap-h{padding:1.3rem 1.4rem 1rem;border-bottom:1px solid var(--line);background:linear-gradient(var(--ph),var(--ph)) left/6px 100% no-repeat,var(--surface);padding-left:1.7rem}
.chap-h .eyebrow{font:500 .72rem/1.3 var(--f-mono);letter-spacing:.1em;text-transform:uppercase;color:var(--ph);margin-bottom:.4rem}
.chap-h h2{font:800 clamp(1.7rem,4.6vw,2.3rem)/1.02 var(--f-display);text-transform:uppercase}
.chap-h .lead{margin:.6rem 0 0;font-size:1.05rem;max-width:44rem}
.row{display:grid;grid-template-columns:9rem minmax(0,1fr);gap:.4rem 1.4rem;padding:1.05rem 1.4rem;border-top:1px solid var(--line)}
.row:first-of-type{border-top:0}
.row>h3{font:500 .72rem/1.4 var(--f-mono);letter-spacing:.1em;text-transform:uppercase;color:var(--muted);padding-top:.25rem}
.row>div{min-width:0;max-width:46rem}
.row>div>*:last-child{margin-bottom:0}
@media (max-width:700px){.row{grid-template-columns:minmax(0,1fr)}.chap-h,.row{padding-inline:1.1rem}.chap-h{padding-left:1.4rem}}
.row.why>h3{color:var(--accent)}
.row.err>h3{color:var(--pain)}
.row.out{background:var(--ph-soft)}
.row.out>h3{color:var(--ph)}
.row.practice>h3{color:var(--ok)}
.row.exm,.row.qs{background:none}
.ex{background:var(--bg);border-left:3px solid var(--ph);padding:.7rem .95rem;border-radius:0 6px 6px 0;margin:.5rem 0 .8rem}
.ex p:last-child{margin-bottom:0}
.q{font-style:italic}
.say{border-left:3px solid var(--line);padding-left:.8rem;margin:.4rem 0;color:var(--ink)}
.say small{display:block;font:500 .68rem/1.4 var(--f-mono);letter-spacing:.08em;text-transform:uppercase;color:var(--muted)}
.big{font:700 clamp(1.3rem,3.5vw,1.8rem)/1.15 var(--f-display);text-transform:uppercase;letter-spacing:.02em;margin:.3rem 0 .8rem}
.swap{display:grid;gap:.8rem;grid-template-columns:repeat(auto-fit,minmax(15rem,1fr));margin:.6rem 0 .8rem}
.swap>div{padding:.8rem .95rem;border-radius:6px;border:1px solid var(--line)}
.swap .old{background:var(--pain-soft)}
.swap .new{background:var(--ok-soft)}
.swap h4{font:500 .7rem/1.3 var(--f-mono);letter-spacing:.1em;text-transform:uppercase;margin-bottom:.35rem}
.swap .old h4{color:var(--pain)}.swap .new h4{color:var(--ok)}
.swap p{margin:0}

.tw{overflow-x:auto;margin:.5rem 0 .9rem;border:1px solid var(--line);border-radius:6px;background:var(--surface)}
table{border-collapse:collapse;width:100%;min-width:34rem;font-size:.92rem}
th,td{text-align:left;vertical-align:top;padding:.6rem .75rem;border-bottom:1px solid var(--line)}
th{font:500 .7rem/1.3 var(--f-mono);letter-spacing:.08em;text-transform:uppercase;color:var(--muted);background:var(--bg);white-space:nowrap}
tr:last-child td{border-bottom:0}
td:first-child{font-weight:600}
td.num,th.num{font-variant-numeric:tabular-nums}

.flow{list-style:none;padding:0;margin:.6rem 0 .9rem;display:grid;gap:0}
.flow li{display:grid;grid-template-columns:2.2rem minmax(0,1fr);gap:.8rem;margin:0;position:relative;padding-bottom:.9rem}
.flow li:last-child{padding-bottom:0}
.flow li::before{content:"";position:absolute;left:1.05rem;top:2.2rem;bottom:0;width:2px;background:var(--line)}
.flow li:last-child::before{display:none}
.flow .n{width:2.2rem;height:2.2rem;border-radius:50%;background:var(--ph,var(--accent));color:var(--surface);display:grid;place-items:center;font:700 .85rem/1 var(--f-mono)}
.flow b{font:700 1.15rem/1.2 var(--f-display);text-transform:uppercase;letter-spacing:.05em;display:block}
.flow span{color:var(--muted);font-size:.93rem}
.flow.compact li{padding-bottom:.55rem}

.pillars3{display:grid;gap:.8rem;grid-template-columns:repeat(auto-fit,minmax(15rem,1fr));margin:1rem 0}
.pillars3>div{background:var(--surface);border:1px solid var(--line);border-top:5px solid var(--ph);border-radius:6px;padding:.9rem 1rem}
.pillars3 h4{font:800 1.4rem/1 var(--f-display);text-transform:uppercase;margin-bottom:.4rem;color:var(--ph)}
.pillars3 p{font-size:.93rem;margin:0 0 .5rem}
.pillars3 .tag{color:var(--muted)}

.case{margin:0 0 1.2rem}
.case>summary{cursor:pointer;list-style:none}
.cases .chap-h{cursor:default}
dl.an{margin:0;display:grid;grid-template-columns:8.5rem minmax(0,1fr);gap:0}
dl.an dt,dl.an dd{margin:0;padding:.55rem .75rem;border-bottom:1px solid var(--line)}
dl.an dt{font:500 .7rem/1.5 var(--f-mono);letter-spacing:.08em;text-transform:uppercase;color:var(--ph);padding-top:.7rem}
dl.an dd{font-size:.95rem}
@media (max-width:620px){dl.an{grid-template-columns:minmax(0,1fr)}dl.an dt{border-bottom:0;padding-bottom:0}}
.profile{padding:1rem 1.4rem;background:var(--bg);border-bottom:1px solid var(--line)}
.profile p:last-child{margin:0}

.qgroup{margin:0 0 1.4rem}
.qgroup h3{font:700 1.25rem/1.2 var(--f-display);text-transform:uppercase;letter-spacing:.05em;color:var(--ph);margin-bottom:.5rem;padding-bottom:.35rem;border-bottom:2px solid var(--ph)}
.qgroup ol{list-style:none;counter-reset:q;padding:0;margin:0}
.qgroup li{counter-increment:q;display:grid;grid-template-columns:2.4rem minmax(0,1fr);gap:.4rem;padding:.4rem 0;margin:0;border-bottom:1px solid var(--line)}
.qgroup li::before{content:counter(q);font:500 .8rem/1.9 var(--f-mono);color:var(--muted);font-variant-numeric:tabular-nums}
.qgroup li{font-size:.97rem}

.ws{display:grid;gap:.9rem;grid-template-columns:repeat(auto-fit,minmax(min(100%,19rem),1fr));padding:1.2rem 1.4rem}
.ws label{display:block;font:700 1.05rem/1.2 var(--f-display);text-transform:uppercase;letter-spacing:.05em;margin-bottom:.15rem}
.ws .hint{display:block;font-size:.82rem;color:var(--muted);margin-bottom:.35rem;line-height:1.4}
.ws textarea{width:100%;min-height:5.2rem;resize:vertical;font:400 .95rem/1.5 var(--f-body);color:var(--ink);background:var(--bg);border:1px solid var(--line);border-radius:6px;padding:.6rem .7rem}
.ws textarea:focus{border-color:var(--accent);outline:2px solid var(--accent);outline-offset:0}
.ws .wide{grid-column:1/-1}
.ws-bar{display:flex;flex-wrap:wrap;gap:.6rem;align-items:center;padding:.9rem 1.4rem;border-top:1px solid var(--line);background:var(--bg)}
.btn{font:600 .9rem/1 var(--f-body);padding:.75rem 1.1rem;border-radius:6px;border:1px solid var(--accent);background:var(--accent);color:var(--on-accent);cursor:pointer}
.btn.ghost{background:none;color:var(--ink);border-color:var(--line)}
.btn.warn{border-color:var(--pain);color:var(--pain)}
.status{font:500 .78rem/1.3 var(--f-mono);color:var(--muted)}

.closing{background:var(--ink);color:var(--bg);border-radius:8px;padding:clamp(1.4rem,5vw,3rem);margin-top:3rem}
.closing p{font:700 clamp(1.25rem,3.6vw,1.9rem)/1.2 var(--f-display);text-transform:uppercase;letter-spacing:.02em;margin:0 0 .7rem}
.closing p.last{margin-top:1.4rem;padding-top:1.2rem;border-top:1px solid color-mix(in srgb,var(--bg) 35%,transparent);color:var(--bg)}
.closing p.last em{font-style:normal;color:var(--gold-soft)}
.note{font-size:.88rem;color:var(--muted)}
.callout{background:var(--gold-soft);border-left:4px solid var(--gold);padding:.8rem 1rem;border-radius:0 6px 6px 0;margin:.7rem 0 1rem;font-size:.95rem}
.callout b{color:var(--gold)}
.top{display:inline-block;margin-top:1.4rem;font:500 .72rem/1 var(--f-mono);letter-spacing:.08em;text-transform:uppercase}
</style>

<div class="shell">
<header class="hero" id="atas">
  <p class="kicker">The Fitnesspreneur Playbook · Modul pembelajaran untuk Fitness Trainer</p>
  <h1>Jangan jual sesi.<br><span>Jual solusi.</span></h1>
  <p class="pillars">Your Skill · Your Knowledge · Your Asset</p>
  <p class="sub">From Customer Pain to Business Asset. Playbook ini dipakai fasilitator untuk membedah potensi bisnis setiap peserta, dimulai dari masalah customer, bukan dari sertifikat atau daftar skill.</p>
  <div class="meta">
    <span class="chip">1 hari ± 7–8 jam, atau 3 sesi</span>
    <span class="chip">19 bab + toolkit fasilitator</span>
    <span class="chip">Hasil: Business Blueprint</span>
    <span class="chip">Bahasa Indonesia</span>
  </div>
</header>

<div class="layout">
<nav class="toc" aria-label="Daftar isi">
<details open id="tocd">
<summary>Daftar isi</summary>
<h4>Mulai di sini</h4>
<ol>
<li><a href="#cara">Cara memakai modul</a></li>
<li><a href="#peta">Peta logika</a></li>
</ol>
<h4 style="--ph:var(--accent)">Konsep · 20%</h4>
<ol>
<li><a href="#b1">1. Masalah yang dipecahkan</a></li>
<li><a href="#b2">2. Fitnesspreneur Value Engine</a></li>
</ol>
<h4 style="--ph:var(--pain)">Discovery · 30%</h4>
<ol>
<li><a href="#b3">3. Pain Ladder</a></li>
<li><a href="#b4">4. Customer Interview</a></li>
<li><a href="#b5">5. Customer Job</a></li>
<li><a href="#b6">6. Prioritas Pain (P.A.I.N.)</a></li>
<li><a href="#b7">7. Segmentasi</a></li>
</ol>
<h4 style="--ph:var(--ok)">Aplikasi · 30%</h4>
<ol>
<li><a href="#b8">8. Your Skill</a></li>
<li><a href="#b9">9. Your Knowledge</a></li>
<li><a href="#b10">10. Value Proposition</a></li>
<li><a href="#b11">11. Offer Design</a></li>
<li><a href="#b12">12. Proof</a></li>
</ol>
<h4 style="--ph:var(--gold)">Aksi bisnis · 20%</h4>
<ol>
<li><a href="#b13">13. Your Asset</a></li>
<li><a href="#b14">14. Proses Assetization</a></li>
<li><a href="#b15">15. Business Model</a></li>
<li><a href="#b16">16. Opportunity Filter</a></li>
<li><a href="#b17">17. Bedah 4 Studi Kasus</a></li>
<li><a href="#b18">18. Signature Exercise</a></li>
<li><a href="#b19">19. Business Blueprint</a></li>
</ol>
<h4>Toolkit fasilitator</h4>
<ol>
<li><a href="#fasil">Peran fasilitator</a></li>
<li><a href="#qbank">Bank pertanyaan (32)</a></li>
<li><a href="#etika">Standar etika &amp; scope</a></li>
<li><a href="#penutup">Penutup</a></li>
</ol>
</details>
</nav>

<main>

<!-- CARA PAKAI -->
<section class="sec" id="cara">
<div class="sec-intro">
<h2>Cara memakai modul</h2>
<p>Modul ini bukan bacaan motivasi. Ini alat kerja. Peserta memilih <strong>satu segmen customer</strong> di awal, lalu membawanya melewati semua bab. Setiap bab ditutup dengan satu output pendek yang langsung mengisi Blueprint di bab 19.</p>
<div class="howto">
<div><b>Peserta</b>Tulis di worksheet, bukan di kepala. Pakai klien nyata, bukan klien rekaan.</div>
<div><b>Fasilitator</b>Bertanya dulu, jangan memberi jawaban. Gunakan bank pertanyaan di bagian bawah.</div>
<div><b>Waktu</b>Setiap bab punya estimasi menit. Bila waktu mepet, kerjakan blok <em>Latihan</em> dan <em>Output</em> saja.</div>
</div>
<p><strong>Setiap bab memakai urutan yang sama:</strong> WHY → HOW → CONTOH → PRACTICE → OUTPUT, ditambah kesalahan umum dan pertanyaan fasilitator.</p>
<div class="legend" style="--ph:var(--accent)">
<span><b class="tag">WHY</b> Mengapa topik ini penting</span>
<span><b class="tag">HOW · Konsep</b> Kerangka dan cara memakainya</span>
<span><b class="tag">Contoh FT</b> Kasus dari dunia trainer</span>
<span><b class="tag">Kesalahan umum</b> Jebakan yang sering terjadi</span>
<span><b class="tag">Pertanyaan</b> Untuk fasilitator</span>
<span><b class="tag">Latihan</b> Aktivitas peserta</span>
<span><b class="tag">Output</b> Hasil yang dibawa pulang</span>
</div>
<p class="note" style="margin-top:1rem">Worksheet di bab 18 dan 19 menyimpan isian di browser perangkat ini. Salin hasilnya ke dokumen Anda sebelum menutup halaman atau berganti perangkat.</p>
</div>
</section>

<!-- PETA LOGIKA -->
<section class="sec" id="peta">
<div class="sec-intro">
<h2>Peta logika</h2>
<p>Modul disusun dari satu rantai. Tidak ada bab yang berdiri sendiri: output bab sebelumnya adalah bahan baku bab berikutnya.</p>
<div class="callout"><b>Rantai besar:</b> Customer Pain → Customer Need → Fitness Solution → Your Skill → Your Knowledge → Your Value → Your Offer → Your Proof → Your Asset → Your Business</div>
<p><strong>Tiga pilar</strong> bukan tiga materi terpisah. Ketiganya adalah tiga pertanyaan yang dijawab dari pain yang sama.</p>
<div class="pillars3">
<div style="--ph:var(--ok)"><h4>Your Skill</h4><p>Apa yang bisa saya lakukan untuk menyelesaikan pain ini?</p><span class="tag">Bab 8, 11</span></div>
<div style="--ph:var(--accent)"><h4>Your Knowledge</h4><p>Mengapa solusi saya layak dipercaya dan lebih tepat?</p><span class="tag">Bab 9, 10, 12</span></div>
<div style="--ph:var(--gold)"><h4>Your Asset</h4><p>Apa yang tetap saya miliki dan bisa dipakai ulang setelah sesi selesai?</p><span class="tag">Bab 13, 14, 15</span></div>
</div>
<p><strong>Aliran output antar bab.</strong> Baca dari atas ke bawah. Kolom terakhir menunjukkan ke mana output mengalir.</p>
<div class="tw"><table>
<thead><tr><th>Bab</th><th>Pertanyaan inti</th><th>Output</th><th>Mengalir ke</th></tr></thead>
<tbody>
<tr><td>1–2</td><td>Mulai dari trainer atau customer?</td><td>Pola pikir baru + peta 11 langkah</td><td>Seluruh modul</td></tr>
<tr><td>3</td><td>Pain di level mana?</td><td>Pain Ladder 1 klien</td><td>Bab 4, 6</td></tr>
<tr><td>4</td><td>Apa kata klien sendiri?</td><td>Kutipan verbatim, failed attempts, why</td><td>Bab 5, 10</td></tr>
<tr><td>5</td><td>Progres apa yang dibeli?</td><td>Customer Job (3 lapis)</td><td>Bab 10, 11</td></tr>
<tr><td>6</td><td>Pain mana yang layak dibangun?</td><td>1 pain prioritas + skor</td><td>Bab 7, 8</td></tr>
<tr><td>7</td><td>Siapa, dalam konteks apa?</td><td>Segmen 1 kalimat</td><td>Bab 8, 10</td></tr>
<tr><td>8</td><td>Skill mana yang relevan?</td><td>Skill–Pain Matrix</td><td>Bab 10, 11</td></tr>
<tr><td>9</td><td>Knowledge apa yang membedakan?</td><td>Insight + method</td><td>Bab 10, 14</td></tr>
<tr><td>10</td><td>Mengapa saya, bukan trainer lain?</td><td>Value Proposition</td><td>Bab 11</td></tr>
<tr><td>11</td><td>Bagaimana dibeli?</td><td>Offer 1 halaman</td><td>Bab 12, 15</td></tr>
<tr><td>12</td><td>Mengapa orang percaya?</td><td>Claim → Proof</td><td>Bab 14</td></tr>
<tr><td>13–14</td><td>Apa yang bisa dimiliki?</td><td>Aset sekarang + aset baru</td><td>Bab 15</td></tr>
<tr><td>15–16</td><td>Model dan layak tidaknya?</td><td>Model bertahap + skor filter</td><td>Bab 19</td></tr>
<tr><td>17–19</td><td>Bisa diterapkan ke diri sendiri?</td><td>Business Blueprint + rencana 90 hari</td><td>Aksi nyata</td></tr>
</tbody></table></div>
<p class="note">Proporsi waktu: 20% Konsep, 30% Discovery, 30% Aplikasi, 20% Aksi bisnis. Setiap konsep langsung disusul contoh FT dan latihan.</p>
</div>
</section>

<!-- ============ KONSEP ============ -->
<div class="part-h" data-phase="konsep"><h2>Bagian 1 · Konsep</h2><p>20% · ± 80 menit</p></div>

<article class="chap" id="b1" data-phase="konsep">
<header class="chap-h"><p class="eyebrow">Bab 1 · Konsep · ± 35 menit</p><h2>Masalah yang harus dipecahkan</h2><p class="lead">Banyak FT memulai bisnis dari apa yang mereka bisa lakukan. Customer membayar untuk masalah yang selesai.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Kalimat yang sering diucapkan FT: <em>"Saya punya sertifikasi." "Saya bisa membuat program." "Saya bisa membantu fat loss." "Saya bisa strength training."</em></p>
<p>Semua kalimat itu tentang <strong>trainer</strong>. Tidak ada satu pun yang menyebut customer. Akibatnya terlihat di lapangan:</p>
<ul>
<li>positioning generik dan semua FT terlihat sama;</li>
<li>perang harga, karena satu-satunya pembeda adalah tarif;</li>
<li>value sulit dijelaskan;</li>
<li>konten ramai tetapi tidak menghasilkan inquiry;</li>
<li>program dibuat dari asumsi;</li>
<li>sulit mendapat premium client;</li>
<li>income tergantung jumlah sesi;</li>
<li>keahlian tidak pernah berkembang menjadi aset.</li>
</ul>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<p>Ganti pertanyaan awal bisnis Anda.</p>
<div class="swap">
<div class="old"><h4>Old thinking</h4><p class="big" style="margin:0">"Saya bisa apa?"</p></div>
<div class="new"><h4>Business thinking</h4><p style="margin:0;font-weight:600">"Siapa yang punya masalah, seberapa penting masalah itu, dan mengapa mereka membutuhkan solusi saya?"</p></div>
</div>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<p>Dua trainer di gym yang sama memperkenalkan diri.</p>
<div class="ex"><p><strong>Rani:</strong> "Saya personal trainer bersertifikat, bisa fat loss, muscle gain, dan strength."</p></div>
<div class="ex"><p><strong>Dimas:</strong> "Saya membantu karyawan usia 35–45 yang sudah sering mulai olahraga tetapi berhenti di minggu ketiga, supaya punya rutinitas yang tetap jalan di tengah jadwal padat."</p></div>
<p>Calon klien yang lelah dan sibuk akan mengingat Dimas. Rani harus bersaing lewat harga.</p>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Mengira sertifikat adalah alasan orang membeli.</li>
<li>Menganggap "lebih banyak konten" menyelesaikan positioning yang kabur.</li>
<li>Menjawab semua kebutuhan sekaligus supaya "tidak kehilangan peluang".</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Dari kalimat perkenalan Anda, siapa yang sebenarnya dibicarakan?"</li>
<li>"Kalau calon klien mendengar ini, masalah apa yang terasa terselesaikan?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p><strong>Coret kata.</strong> Tulis perkenalan 30 detik Anda. Coret semua kata yang hanya menjelaskan diri Anda (sertifikat, jam terbang, jenis latihan). Tanyakan pada pasangan: apa yang tersisa? Berapa persen kalimat yang menyebut customer?</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Satu kalimat <em>old thinking</em> milik Anda dan satu pertanyaan <em>business thinking</em> yang akan dijawab sepanjang modul.</p></div></div>
</article>

<article class="chap" id="b2" data-phase="konsep">
<header class="chap-h"><p class="eyebrow">Bab 2 · Konsep · ± 45 menit</p><h2>The Fitnesspreneur Value Engine</h2><p class="lead">Satu rantai 11 langkah dari customer sampai bisnis. Seluruh modul mengikuti rantai ini.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Tanpa kerangka, FT melompat langsung ke "buat program" atau "buat konten". Value Engine memaksa urutan yang benar: customer dulu, solusi kemudian, aset terakhir. Bagian yang kosong pada rantai menunjukkan di mana bisnis Anda macet.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<ol class="flow" style="--ph:var(--accent)">
<li><span class="n">1</span><div><b>Customer</b><span>Siapa yang ingin saya bantu?</span></div></li>
<li><span class="n">2</span><div><b>Pain</b><span>Apa yang sebenarnya mereka rasakan?</span></div></li>
<li><span class="n">3</span><div><b>Job</b><span>Apa yang sebenarnya ingin mereka capai?</span></div></li>
<li><span class="n">4</span><div><b>Gap</b><span>Mengapa mereka belum berhasil?</span></div></li>
<li><span class="n">5</span><div><b>Solution</b><span>Solusi apa yang dapat saya tawarkan?</span></div></li>
<li><span class="n">6</span><div><b>Skill</b><span>Skill apa yang saya miliki untuk memberikan solusi itu?</span></div></li>
<li><span class="n">7</span><div><b>Knowledge</b><span>Knowledge apa yang membuat solusi saya lebih kredibel?</span></div></li>
<li><span class="n">8</span><div><b>Proof</b><span>Apa bukti bahwa solusi saya bekerja?</span></div></li>
<li><span class="n">9</span><div><b>Offer</b><span>Bagaimana solusi dikemas menjadi sesuatu yang mudah dibeli?</span></div></li>
<li><span class="n">10</span><div><b>Asset</b><span>Apa yang dapat dibangun dari proses ini?</span></div></li>
<li><span class="n">11</span><div><b>Business</b><span>Bagaimana aset menciptakan sustainable value dan revenue?</span></div></li>
</ol>
<p>Langkah 1–4 adalah <strong>Discovery</strong> (bab 3–7). Langkah 5–9 adalah <strong>Aplikasi</strong> (bab 8–12). Langkah 10–11 adalah <strong>Aksi bisnis</strong> (bab 13–19).</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="ex">
<p><strong>Customer:</strong> ibu bekerja usia 38. <strong>Pain:</strong> cepat lelah saat bermain dengan anak. <strong>Job:</strong> punya energi sepanjang hari. <strong>Gap:</strong> latihan lama dan jadwal tidak muat. <strong>Solution:</strong> latihan 3x30 menit yang bisa bertahan. <strong>Skill:</strong> program design, coaching kebiasaan. <strong>Knowledge:</strong> pola kegagalan klien serupa. <strong>Proof:</strong> data kehadiran klien sebelumnya. <strong>Offer:</strong> program 12 minggu. <strong>Asset:</strong> metode dan template. <strong>Business:</strong> program kelompok kecil.</p>
</div>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Mulai dari langkah 5 atau 6 (solusi dan skill), lalu mencari customer yang cocok.</li>
<li>Mengisi semua langkah dengan jawaban umum seperti "orang yang ingin sehat".</li>
<li>Menganggap langkah 10 (asset) bisa dikerjakan tanpa langkah 8 (proof).</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Langkah mana yang paling lama Anda isi? Itu biasanya titik paling lemah."</li>
<li>"Apakah langkah 6 benar-benar menjawab langkah 4?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Pilih satu klien nyata. Isi 11 langkah dalam satu halaman, 1–2 kalimat per langkah. Beri tanda <strong>?</strong> pada langkah yang Anda isi dengan tebakan. Bandingkan dengan pasangan.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Satu halaman Value Engine untuk satu klien dengan daftar langkah bertanda <strong>?</strong>. Daftar itu menjadi agenda sisa modul.</p></div></div>
</article>

<!-- ============ DISCOVERY ============ -->
<div class="part-h" data-phase="discovery"><h2>Bagian 2 · Discovery</h2><p>30% · ± 125 menit</p></div>

<article class="chap" id="b3" data-phase="discovery">
<header class="chap-h"><p class="eyebrow">Bab 3 · Discovery · ± 30 menit</p><h2>Pain Ladder</h2><p class="lead">Pain bukan sekadar "ingin kurus" atau "ingin sehat". Turun tangga sampai ketemu problem di balik problem.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Jawaban pertama klien hampir selalu symptom. Orang membayar mahal untuk pain yang terasa dalam, bukan untuk symptom permukaan. FT yang berhenti di level 1 hanya bisa menjual latihan.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<div class="tw"><table>
<thead><tr><th>Level</th><th>Yang digali</th><th>Contoh</th></tr></thead>
<tbody>
<tr><td>1 · Surface</td><td>Apa yang terlihat?</td><td>Berat badan naik, stamina buruk, badan kaku</td></tr>
<tr><td>2 · Functional</td><td>Apa yang terganggu dalam hidup?</td><td>Cepat lelah saat bermain dengan anak, tidak mampu mengikuti aktivitas teman, takut cedera saat olahraga</td></tr>
<tr><td>3 · Emotional</td><td>Apa yang dirasakan?</td><td>Frustrasi, malu, takut, kehilangan confidence, merasa gagal berkali-kali</td></tr>
<tr><td>4 · Identity</td><td>Bagaimana ia memandang dirinya?</td><td>"Saya bukan orang yang disiplin." "Saya sudah 40, badan tidak seperti dulu." "Saya selalu mulai lalu berhenti."</td></tr>
<tr><td>5 · Consequence</td><td>Apa yang terjadi jika dibiarkan?</td><td>Makin tidak aktif, mobilitas menurun, makin sulit mengubah kebiasaan, kualitas hidup turun</td></tr>
</tbody></table></div>
<p><strong>Cara menurunkan tangga:</strong> ulangi kata klien, lalu tanyakan <em>"Seperti apa itu terasa?"</em> atau <em>"Apa dampaknya buat Anda?"</em></p>
<p class="q">Jangan berhenti pada symptom. Cari problem di balik problem.</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="ex">
<p><strong>L1:</strong> "Perut saya membesar." <strong>L2:</strong> "Celana kerja sudah tidak muat, saya enggan hadir di acara kantor." <strong>L3:</strong> "Saya malu dan kesal pada diri sendiri." <strong>L4:</strong> "Saya memang tidak bisa konsisten." <strong>L5:</strong> "Kalau begini terus, saya takut makin sulit berubah dan makin jarang bergerak."</p>
</div>
<p>Offer untuk L1 adalah "program fat loss". Offer untuk L4 adalah "sistem yang membuktikan Anda bisa konsisten". Yang kedua jauh lebih bernilai.</p>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Berhenti di level 1 dan 2.</li>
<li>Mengarang pain yang menurut FT "pasti dirasakan".</li>
<li>Memakai consequence pain untuk menakut-nakuti. Sampaikan konsekuensi secara jujur, tanpa dramatisasi, tanpa diagnosis, dan tanpa mempermalukan klien.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Ini level berapa? Apa yang ada di bawahnya?"</li>
<li>"Pain ini kata klien atau kata Anda?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Ambil satu klien. Tulis kelima level dengan <strong>kata-kata klien</strong>. Beri bintang pada level yang paling berat bagi klien.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Pain Ladder satu klien dengan satu level terberat yang ditandai.</p></div></div>
</article>

<article class="chap" id="b4" data-phase="discovery">
<header class="chap-h"><p class="eyebrow">Bab 4 · Discovery · ± 40 menit</p><h2>Customer Interview</h2><p class="lead">Pertanyaan umum menghasilkan jawaban umum. Gali kejadian nyata, bukan opini.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Klien sering menjawab <em>"Saya ingin turun berat badan"</em> karena itu jawaban yang aman. Wawancara yang baik membuka cerita di balik kalimat itu, dan cerita itulah bahan offer, konten, dan metode Anda.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<p>Hindari: <span class="q">"Apa yang Anda inginkan dari personal trainer?"</span> Pakai teknik <strong>Past – Present – Failed Attempts – Desired Future</strong>.</p>
<div class="tw"><table>
<thead><tr><th>Tahap</th><th>Pertanyaan</th></tr></thead>
<tbody>
<tr><td>Past</td><td>Sebelumnya pernah mencoba apa? Berapa lama? Dengan siapa? Apa yang terjadi?</td></tr>
<tr><td>Present</td><td>Apa masalah terbesar Anda sekarang? Kapan paling terasa? Apa dampaknya pada kehidupan?</td></tr>
<tr><td>Failed attempts</td><td>Apa yang sudah dicoba? Mengapa berhenti? Apa yang membuat metode itu tidak bekerja?</td></tr>
<tr><td>Desired future</td><td>Kalau masalah ini selesai, apa yang berubah? Apa yang ingin Anda bisa lakukan lagi? Mengapa itu penting?</td></tr>
</tbody></table></div>
<p><strong>Teknik "Why Behind the Why"</strong></p>
<div class="say"><small>Klien</small>"Saya ingin turun 10 kg."</div>
<div class="say"><small>FT</small>"Kenapa 10 kg?"</div>
<div class="say"><small>Klien</small>"Biar lebih sehat."</div>
<div class="say"><small>FT</small>"Kenapa sehat itu penting sekarang?"</div>
<div class="say"><small>Klien</small>"Karena saya punya anak kecil dan ingin bisa aktif bersama mereka."</div>
<p style="margin-top:.6rem">Sekarang FT menemukan <strong>deeper customer value</strong>: bukan 10 kg, melainkan bisa aktif bersama anak.</p>
<p><strong>Aturan wawancara:</strong> tanyakan masa lalu yang nyata, bukan rencana masa depan; diam setelah bertanya; catat kata-kata klien apa adanya (verbatim); jangan menawarkan program selama wawancara.</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="ex">
<p>Pertanyaan lemah: "Apakah Anda butuh program latihan yang fleksibel?" Pertanyaan kuat: "Ceritakan minggu terakhir Anda berusaha olahraga. Apa yang terjadi hari Rabu?" Jawaban kedua membuka fakta: lembur, anak sakit, rasa bersalah, berhenti.</p>
</div>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Pitching di tengah wawancara.</li>
<li>Bertanya pertanyaan tertutup (ya/tidak).</li>
<li>Menerjemahkan jawaban klien ke bahasa teknis sebelum mencatatnya.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Ada berapa 'kenapa' di balik jawaban itu?"</li>
<li>"Kalimat mana yang bisa Anda kutip persis?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p><strong>Triad 3 putaran × 7 menit:</strong> pewawancara, klien (bercerita dari pengalaman sendiri atau klien nyata), pengamat. Pengamat mencatat pertanyaan terbaik dan momen ketika pewawancara berhenti menggali terlalu cepat. Tugas lanjutan: 3 wawancara nyata dalam 7 hari.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Lembar wawancara berisi failed attempts, why behind the why, dan <strong>3 kutipan verbatim</strong> yang akan dipakai di bab 10.</p></div></div>
</article>

<article class="chap" id="b5" data-phase="discovery">
<header class="chap-h"><p class="eyebrow">Bab 5 · Discovery · ± 20 menit</p><h2>Customer Job to Be Done</h2><p class="lead">Customer tidak membeli fitness. Customer membeli progress menuju kehidupan yang mereka inginkan.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Dua klien dengan target sama (turun lemak tubuh) bisa membutuhkan offer yang sama sekali berbeda. Bedanya ada pada tiga lapis job.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<div class="tw"><table>
<thead><tr><th>Job</th><th>Pertanyaan</th></tr></thead>
<tbody>
<tr><td>Functional</td><td>Apa yang ingin mereka lakukan?</td></tr>
<tr><td>Emotional</td><td>Bagaimana mereka ingin merasa?</td></tr>
<tr><td>Social</td><td>Bagaimana mereka ingin dilihat?</td></tr>
</tbody></table></div>
<p>Rumus kalimat: <strong>"Ketika [situasi], saya ingin [progress], supaya [hidup yang diinginkan]."</strong></p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="ex"><p>Seorang eksekutif datang ke gym. <strong>Functional:</strong> menurunkan body fat. <strong>Emotional:</strong> merasa confident. <strong>Social:</strong> terlihat fit dan energik di depan tim.</p>
<p>Offer yang relevan: program yang jadwalnya aman untuk perjalanan dinas, dengan progres terukur yang bisa ia rasakan di rapat, bukan hanya angka di timbangan.</p></div>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Hanya menulis job functional.</li>
<li>Menulis job emotional sebagai tebakan, bukan dari wawancara.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Kalau klien mencapai target tetapi tidak merasa confident, apakah ia akan puas?"</li>
<li>"Siapa yang akan melihat perubahannya, dan apa yang diharapkan dari mereka?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Tulis customer job untuk 3 klien berbeda dalam format kalimat di atas. Tandai klien mana yang job emotional-nya paling kuat.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Customer Job 3 lapis untuk segmen terpilih.</p></div></div>
</article>

<article class="chap" id="b6" data-phase="discovery">
<header class="chap-h"><p class="eyebrow">Bab 6 · Discovery · ± 20 menit</p><h2>Prioritas Pain: P.A.I.N.</h2><p class="lead">Tidak semua pain adalah peluang bisnis. Pain ≠ automatically paid problem.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Customer bisa sangat terganggu oleh sesuatu tetapi belum tentu mau membayar solusinya. Penyaringan lebih awal menghemat berbulan-bulan membangun sesuatu yang tidak dibeli.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<div class="tw"><table>
<thead><tr><th>Huruf</th><th>Aspek</th><th>Pertanyaan</th></tr></thead>
<tbody>
<tr><td>P</td><td>Problem intensity</td><td>Seberapa berat masalahnya?</td></tr>
<tr><td>A</td><td>Awareness</td><td>Apakah customer sadar mereka punya masalah?</td></tr>
<tr><td>I</td><td>Impact</td><td>Seberapa besar dampaknya pada hidup mereka?</td></tr>
<tr><td>N</td><td>Need to solve</td><td>Seberapa kuat keinginan menyelesaikannya?</td></tr>
<tr><td>+</td><td>Willingness to pay</td><td>Apakah mereka sudah, atau mau, mengeluarkan uang untuk ini?</td></tr>
</tbody></table></div>
<p>Beri skor 1–5 pada kelima aspek (maksimal 25). Ini alat bantu keputusan, bukan statistik.</p>
<ul>
<li><strong>20–25:</strong> prioritas. Lanjutkan ke offer.</li>
<li><strong>14–19:</strong> perlu validasi. Wawancarai 3–5 orang lagi.</li>
<li><strong>di bawah 14:</strong> simpan dulu.</li>
</ul>
<p><strong>Sinyal willingness to pay:</strong> sudah membayar gym tetapi tidak datang; pernah memakai aplikasi, dietitian, atau trainer lain; aktif mencari solusi; pernah mengatakan "saya rela bayar asal berhasil".</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="tw"><table>
<thead><tr><th>Pain</th><th class="num">P</th><th class="num">A</th><th class="num">I</th><th class="num">N</th><th class="num">WTP</th><th class="num">Total</th></tr></thead>
<tbody>
<tr><td>Tidak konsisten karena jadwal padat</td><td class="num">4</td><td class="num">5</td><td class="num">4</td><td class="num">5</td><td class="num">4</td><td class="num">22</td></tr>
<tr><td>Bosan dengan variasi latihan</td><td class="num">2</td><td class="num">5</td><td class="num">2</td><td class="num">2</td><td class="num">2</td><td class="num">13</td></tr>
</tbody></table></div>
<p class="note">Angka di atas ilustrasi untuk latihan, bukan data pasar.</p>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Memberi skor tinggi pada pain yang disukai FT.</li>
<li>Mengabaikan awareness. Pain yang tidak disadari butuh edukasi dulu, dan itu biaya.</li>
<li>Menyamakan "banyak orang mengeluh" dengan "banyak orang membayar".</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Apakah ini pain atau hanya preference?"</li>
<li>"Apa bukti mereka sudah pernah membayar untuk masalah ini?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Skor 3 pain dari wawancara bab 4. Minta pasangan menantang satu skor tertinggi Anda: "Apa buktinya?"</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p><strong>Satu pain prioritas</strong> beserta skor dan bukti willingness to pay.</p></div></div>
</article>

<article class="chap" id="b7" data-phase="discovery">
<header class="chap-h"><p class="eyebrow">Bab 7 · Discovery · ± 15 menit</p><h2>Customer Segmentation</h2><p class="lead">"Everyone who wants to get fit" bukan target market.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Segmen yang tajam membuat pesan, offer, dan metode jadi mudah dirancang. Segmen yang luas membuat semuanya generik.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<p class="big">Who + Context + Problem + Desired outcome</p>
<div class="swap">
<div class="old"><h4>Lemah</h4><p>"Saya membantu orang menurunkan berat badan."</p></div>
<div class="new"><h4>Lebih tajam</h4><p>"Saya membantu busy professional usia 30–45 yang sudah beberapa kali mencoba diet tetapi selalu kembali ke pola lama, untuk membangun sistem fat-loss yang realistis tanpa harus hidup di gym."</p></div>
</div>
<p><strong>Tes tajam:</strong> bisakah Anda menyebut 10 orang nyata yang cocok? Di mana mereka berkumpul? Apa yang mereka ketik saat mencari bantuan?</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<p>Dari "perempuan yang ingin bugar" menjadi "perempuan usia 40–55 yang pernah berhenti latihan karena takut cedera, ingin kuat kembali untuk aktivitas harian". Setiap tambahan konteks mempersempit lalu mempertajam.</p>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Takut mempersempit karena "nanti kehilangan klien". Segmen sempit bukan berarti menolak orang lain, melainkan menentukan siapa yang Anda bangun solusinya untuk.</li>
<li>Segmen berdasarkan demografi saja (usia, gender) tanpa konteks dan problem.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Siapa yang paling merasakan pain ini?"</li>
<li>"Kalau saya bertemu orangnya besok, bagaimana saya mengenalinya?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Tulis segmen Anda dalam 3 versi, setiap versi lebih tajam dari sebelumnya. Pilih versi yang masih bisa Anda isi dengan 10 nama nyata.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Satu kalimat segmen: <strong>Who + Context + Problem + Desired outcome</strong>.</p></div></div>
</article>

<!-- ============ APLIKASI ============ -->
<div class="part-h" data-phase="aplikasi"><h2>Bagian 3 · Aplikasi</h2><p>30% · ± 125 menit</p></div>

<article class="chap" id="b8" data-phase="aplikasi">
<header class="chap-h"><p class="eyebrow">Bab 8 · Aplikasi · ± 25 menit</p><h2>Your Skill</h2><p class="lead">Jangan tanya "Apa skill saya?" Tanyakan skill mana yang paling relevan untuk menyelesaikan pain tertentu.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>FT cenderung menonjolkan skill yang disukai. Pasar membayar skill yang menyelesaikan pain. Yang kita cari adalah <strong>skill yang commercially relevant</strong>.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<p>Buat <strong>Skill–Pain Matrix</strong>: tulis pain di kolom kiri, skill yang menjawabnya di kolom kedua, lalu nilai relevansi dan potensi nilainya.</p>
<div class="tw"><table>
<thead><tr><th>Customer pain</th><th>Skill FT</th><th>Relevance</th><th>Potential value</th></tr></thead>
<tbody>
<tr><td>Tidak konsisten</td><td>Habit coaching</td><td>High</td><td>High</td></tr>
<tr><td>Takut cedera</td><td>Movement coaching</td><td>High</td><td>High</td></tr>
<tr><td>Tidak tahu program</td><td>Program design</td><td>High</td><td>High</td></tr>
<tr><td>Bosan latihan</td><td>Coaching + variety</td><td>Medium</td><td>Medium</td></tr>
</tbody></table></div>
<p>Setelah matrix terisi, kelompokkan: <strong>skill inti</strong> (High/High), <strong>skill pendukung</strong>, dan <strong>celah</strong> (pain besar tanpa skill, yang harus dipelajari atau dikolaborasikan).</p>
<div class="callout"><b>Scope of practice.</b> Skill yang Anda tawarkan harus berada di dalam kewenangan FT. Diagnosis medis, rehabilitasi cedera, dan terapi gizi klinis berada di luar scope. Pada kasus seperti itu, rancang kolaborasi atau rujukan sebagai bagian dari solusi.</div>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<p>Seorang FT sangat menyukai olympic lifting, tetapi pain segmennya adalah "tidak konsisten karena jadwal padat". Skill yang relevan adalah program design hemat waktu dan habit coaching. Olympic lifting tetap berharga, hanya bukan inti offer untuk segmen ini.</p>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Mengisi kolom skill dengan "semua yang saya bisa".</li>
<li>Mengabaikan skill lunak (coaching, komunikasi, accountability) yang sering justru menyelesaikan pain terbesar.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Apa skill Anda yang paling relevan untuk pain ini?"</li>
<li>"Skill mana yang Anda sukai tetapi tidak dibayar customer?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Isi Skill–Pain Matrix minimal 5 baris untuk pain prioritas Anda. Tunjuk satu skill inti dan satu celah.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>1–2 skill inti, 1 skill pendukung, dan 1 celah yang akan ditutup.</p></div></div>
</article>

<article class="chap" id="b9" data-phase="aplikasi">
<header class="chap-h"><p class="eyebrow">Bab 9 · Aplikasi · ± 20 menit</p><h2>Your Knowledge</h2><p class="lead">Knowledge menjadi bernilai ketika membantu customer mengambil keputusan atau mendapat hasil.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Knowledge yang hanya disimpan atau dipamerkan tidak membuat orang membeli. Knowledge yang diubah menjadi insight dan metode membuat solusi Anda berbeda dari trainer lain dengan sertifikat yang sama.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<p class="big">Knowledge → Insight → Method → Result</p>
<div class="tw"><table>
<thead><tr><th>Langkah</th><th>Contoh</th></tr></thead>
<tbody>
<tr><td>Knowledge</td><td>Progressive overload</td></tr>
<tr><td>Insight</td><td>Klien tidak selalu butuh latihan lebih berat. Mereka butuh progression yang terukur.</td></tr>
<tr><td>Method</td><td>Structured progression system</td></tr>
<tr><td>Result</td><td>Strength meningkat dan klien melihat progresnya</td></tr>
</tbody></table></div>
<p>Satu knowledge bisa menjadi: methodology, content, program, assessment, education, atau product.</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="ex"><p>Knowledge: adherence. Insight: kebanyakan klien berhenti di masa ketika motivasi awal turun dan jadwal berubah. Method: "minggu rawan" dengan versi latihan yang dikurangi tetapi tetap hadir. Result: klien tetap datang melewati minggu 3–5.</p></div>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Memamerkan istilah teknis tanpa menjelaskan keputusan yang dibantunya.</li>
<li>Berhenti di knowledge tanpa insight.</li>
<li>Mengutip klaim yang tidak bisa dipertanggungjawabkan sebagai knowledge.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Keputusan apa yang jadi lebih mudah bagi klien karena Anda tahu ini?"</li>
<li>"Apa yang klien salah pahami, dan Anda tahu jawabannya?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Pilih 3 knowledge yang Anda kuasai. Jalankan rantai Knowledge → Insight → Method → Result untuk masing-masing. Pilih satu yang paling dekat dengan pain prioritas.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Satu <strong>insight khas</strong> dan nama sementara untuk method Anda.</p></div></div>
</article>

<article class="chap" id="b10" data-phase="aplikasi">
<header class="chap-h"><p class="eyebrow">Bab 10 · Aplikasi · ± 25 menit</p><h2>Value Proposition</h2><p class="lead">Satu kalimat yang menjawab: untuk siapa, masalah apa, hasil apa, lewat cara apa, tanpa keberatan utama apa.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Value proposition adalah titik temu semua hasil sebelumnya: segmen, pain, job, skill, dan insight. Bila kalimat ini lemah, bagian berikutnya (offer, konten, harga) ikut lemah.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<div class="callout" style="background:var(--accent-soft);border-color:var(--accent)">
<b style="color:var(--accent)">Rumus</b><br>
<strong>Untuk</strong> [customer] <strong>yang kesulitan</strong> [pain], <strong>saya membantu</strong> mereka [outcome] <strong>melalui</strong> [method] <strong>tanpa</strong> [keberatan utama].</div>
<div class="ex"><p>Untuk busy professional yang kesulitan konsisten berolahraga, saya membantu mereka membangun strength dan fitness melalui sistem latihan 3x seminggu yang realistis, tanpa harus menghabiskan waktu berjam-jam di gym.</p></div>
<p><strong>Tes kritik generik</strong> (dipakai fasilitator):</p>
<ul>
<li>Bisakah kalimat ini ditempel pada trainer lain tanpa diubah?</li>
<li>Apakah outcome-nya bisa dilihat atau diukur?</li>
<li>Apakah metode jelas, atau hanya "program personal"?</li>
<li>Apakah keberatan utama segmen sudah disebut?</li>
</ul>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="swap">
<div class="old"><h4>Generik</h4><p>"Saya membantu Anda hidup lebih sehat dengan program latihan personal."</p></div>
<div class="new"><h4>Spesifik</h4><p>"Untuk ibu bekerja yang kehabisan energi setelah jam kantor, saya membantu membangun stamina lewat latihan 30 menit tiga kali seminggu, tanpa harus ke gym setiap hari."</p></div>
</div>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Memakai kata kosong: "optimal", "holistik", "transformasi" tanpa isi.</li>
<li>Menjanjikan hasil tubuh yang tidak bisa dijamin.</li>
<li>Menulis metode berupa daftar alat, bukan sistem.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Apa yang membedakan solusi Anda dari trainer sebelah?"</li>
<li>"Kalau klien membaca ini, keberatan apa yang masih muncul di kepalanya?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Tulis value proposition. Tukar dengan pasangan. Pasangan menjalankan tes kritik generik dan menandai satu bagian yang harus dipertajam. Revisi sekali.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Satu kalimat Value Proposition yang lolos empat tes kritik.</p></div></div>
</article>

<article class="chap" id="b11" data-phase="aplikasi">
<header class="chap-h"><p class="eyebrow">Bab 11 · Aplikasi · ± 30 menit</p><h2>Offer Design</h2><p class="lead">A solution becomes a business when it becomes an offer.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Positioning yang bagus berhenti menjadi bisnis bila klien tidak tahu persis apa yang dibeli, berapa nilainya, dan langkah berikutnya. Offer membuat solusi mudah dibeli.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<ol class="flow compact" style="--ph:var(--ok)">
<li><span class="n">1</span><div><b>Customer</b><span>Siapa?</span></div></li>
<li><span class="n">2</span><div><b>Pain</b><span>Masalah apa?</span></div></li>
<li><span class="n">3</span><div><b>Promise</b><span>Outcome apa yang dijanjikan?</span></div></li>
<li><span class="n">4</span><div><b>Method</b><span>Bagaimana cara kerjanya?</span></div></li>
<li><span class="n">5</span><div><b>Experience</b><span>Seperti apa prosesnya dari minggu ke minggu?</span></div></li>
<li><span class="n">6</span><div><b>Proof</b><span>Mengapa orang percaya?</span></div></li>
<li><span class="n">7</span><div><b>Price</b><span>Berapa nilai ekonominya, bukan berapa tarif per jam?</span></div></li>
<li><span class="n">8</span><div><b>Risk reversal</b><span>Bagaimana mengurangi risiko yang dirasakan klien?</span></div></li>
<li><span class="n">9</span><div><b>Next step</b><span>Apa tindakan klien berikutnya?</span></div></li>
</ol>
<p><strong>Harga:</strong> mulai dari nilai bagi klien dan biaya Anda menyampaikannya (waktu, tempat, asisten, follow-up), bukan dari tarif pesaing.</p>
<p><strong>Risk reversal yang etis:</strong> sesi evaluasi di minggu ke-2, kebijakan pembatalan yang jelas, jaminan proses (misalnya "kami evaluasi dan sesuaikan program bila Anda sudah hadir sesuai rencana tetapi belum ada kemajuan yang terukur"). Hindari jaminan hasil tubuh.</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="ex">
<p><strong>"Reset 12 Minggu untuk Profesional Sibuk"</strong><br>
Customer: karyawan 30–45 yang berkali-kali berhenti. Pain: tidak konsisten. Promise: pola latihan 3x seminggu yang bertahan 12 minggu. Method: sistem progression dan "minggu rawan". Experience: asesmen awal, 24 sesi terjadwal, check-in mingguan 10 menit. Proof: data kehadiran klien sebelumnya. Price: paket 12 minggu. Risk reversal: evaluasi di minggu ke-2 dan penyesuaian program. Next step: sesi konsultasi 20 menit.</p>
</div>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Menjual "paket 10 sesi" tanpa outcome.</li>
<li>Menurunkan harga untuk mengurangi keraguan, padahal keraguannya soal risiko.</li>
<li>Menciptakan urgensi palsu atau tekanan yang tidak etis.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Apa yang sebenarnya dibeli klien?"</li>
<li>"Bagaimana solusi ini menjadi offer yang bisa dipahami dalam 20 detik?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Tulis offer satu halaman dengan sembilan komponen. Presentasikan dalam 60 detik ke pasangan yang berperan sebagai klien dengan segmen Anda. Catat satu pertanyaan yang tidak bisa Anda jawab.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Offer satu halaman beserta satu daftar hal yang masih perlu dibuktikan.</p></div></div>
</article>

<article class="chap" id="b12" data-phase="aplikasi">
<header class="chap-h"><p class="eyebrow">Bab 12 · Aplikasi · ± 25 menit</p><h2>Proof</h2><p class="lead">Keahlian tanpa bukti sulit dipercaya. Ubah klaim menjadi bukti.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Calon klien sudah sering mendengar klaim. Yang membuat mereka percaya adalah bukti yang spesifik, jujur, dan relevan dengan situasi mereka.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<p>Jenis proof: client result, testimonial, before/after (etis dan sesuai konteks), case study, adherence, performance improvement, client story, methodology, credential yang relevan.</p>
<p class="big">Claim → Proof</p>
<div class="swap">
<div class="old"><h4>Klaim</h4><p>"Saya expert fat loss."</p></div>
<div class="new"><h4>Klaim + bukti</h4><p>"Dalam 12 minggu, saya membantu X client membangun pola latihan yang konsisten dan mencapai progress yang terukur."</p></div>
</div>
<p><strong>Mulai catat dari sekarang:</strong> tanggal mulai, kondisi awal (baseline), metrik yang disepakati (kehadiran, beban latihan, tes performa, lingkar, catatan klien), tanggal evaluasi.</p>
<div class="callout"><b>Etika proof.</b> Minta izin tertulis sebelum memakai data atau foto klien. Gunakan hanya bukti yang nyata. Jangan membuat klaim kesehatan yang tidak dapat dipertanggungjawabkan, dan jangan menyiratkan bahwa hasil seorang klien akan dialami semua orang.</div>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="ex"><p>Seorang FT belum punya testimoni. Ia menjalankan pilot 5 klien selama 8 minggu dengan harga perkenalan yang disampaikan terbuka. Ia mencatat kehadiran, progres beban, dan satu kalimat klien di akhir. Ia kini punya mini case study yang jujur dan bisa diperiksa.</p></div>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Hanya memakai before/after visual tanpa konteks dan tanpa izin.</li>
<li>Membesar-besarkan angka.</li>
<li>Mencatat bukti setelah semua klien selesai, bukan sejak awal.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Apa bukti Anda?"</li>
<li>"Kalau klien bertanya 'tunjukkan', apa yang Anda tunjukkan?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Ubah 3 klaim Anda menjadi format klaim + bukti. Bila buktinya belum ada, tulis cara mengumpulkannya dalam 30 hari.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>3 pasang Claim → Proof dan rencana pengumpulan bukti 30 hari.</p></div></div>
</article>

<!-- ============ AKSI ============ -->
<div class="part-h" data-phase="aksi"><h2>Bagian 4 · Aksi bisnis</h2><p>20% · ± 105 menit + kerja Blueprint</p></div>

<article class="chap" id="b13" data-phase="aksi">
<header class="chap-h"><p class="eyebrow">Bab 13 · Aksi · ± 15 menit</p><h2>Your Asset</h2><p class="lead">Asset adalah sesuatu yang terus memberikan value setelah effort awal dilakukan.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Setelah customer, pain, value, offer, dan proof jelas, barulah aset bisa dirancang dengan benar. Aset yang dibuat tanpa tahu customer biasanya tidak dipakai siapa pun.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<div class="tw"><table>
<thead><tr><th>Kategori</th><th>Contoh</th></tr></thead>
<tbody>
<tr><td>Customer asset</td><td>Relationship, database klien, community, referral network</td></tr>
<tr><td>Knowledge asset</td><td>Methodology, framework, curriculum, exercise library</td></tr>
<tr><td>Proof asset</td><td>Case study, testimonial, result database</td></tr>
<tr><td>Brand asset</td><td>Reputation, audience, authority</td></tr>
<tr><td>Product asset</td><td>Program, course, workshop, online coaching framework</td></tr>
<tr><td>System asset</td><td>Onboarding, assessment, follow-up, retention, referral</td></tr>
</tbody></table></div>
<p><strong>Tes aset, tiga pertanyaan:</strong> (1) Apakah ia terus memberi nilai setelah sesi selesai? (2) Bisakah dipakai ulang tanpa mulai dari nol? (3) Apakah ia tetap ada bila saya tidak hadir di setiap sesi?</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<p>Trainer dengan 100 klien dan semua catatan di kepala memiliki pengalaman. Trainer dengan 100 klien dan log terstruktur, template onboarding, dan 5 case study memiliki aset.</p>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Menyamakan aset dengan jumlah followers.</li>
<li>Membuat produk digital tanpa metode dan bukti di baliknya.</li>
<li>Menganggap aset otomatis berarti passive income.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Apa yang tetap Anda miliki setelah sesi selesai?"</li>
<li>"Apa yang bisa digunakan kembali tanpa memulai dari nol?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Inventarisasi aset yang <strong>sudah ada</strong> pada enam kategori. Beri tanda: sudah tertulis, ada tetapi di kepala, belum ada.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p><strong>My Existing Asset</strong>: daftar aset yang sudah dimiliki dan statusnya.</p></div></div>
</article>

<article class="chap" id="b14" data-phase="aksi">
<header class="chap-h"><p class="eyebrow">Bab 14 · Aksi · ± 25 menit · Bab terpenting</p><h2>The Assetization Process</h2><p class="lead">Cara mengubah pengalaman menjadi aset yang bisa dipakai berulang.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Pengalaman menghilang bila tidak didokumentasikan. Jalur ini mengubah "saya sudah menangani banyak klien" menjadi metode, bukti, dan produk yang bisa Anda gunakan lagi dan lagi.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<ol class="flow" style="--ph:var(--gold)">
<li><span class="n">1</span><div><b>Experience</b><span>"Saya sudah menangani 100 client."</span></div></li>
<li><span class="n">2</span><div><b>Pattern</b><span>"Saya menemukan pola tertentu."</span></div></li>
<li><span class="n">3</span><div><b>Insight</b><span>"Saya memahami mengapa mereka gagal."</span></div></li>
<li><span class="n">4</span><div><b>Method</b><span>"Saya membuat pendekatan yang lebih efektif."</span></div></li>
<li><span class="n">5</span><div><b>Proof</b><span>"Saya memiliki evidence dari client."</span></div></li>
<li><span class="n">6</span><div><b>Product</b><span>"Saya mengemasnya."</span></div></li>
<li><span class="n">7</span><div><b>Asset</b><span>"Saya memiliki methodology, product, atau system yang dapat digunakan berulang."</span></div></li>
</ol>
<p><strong>Cara mulai mencari pola:</strong> buka catatan 10–20 klien terakhir dan kelompokkan menurut (a) kapan mereka berhenti, (b) apa alasan yang mereka sebutkan, (c) apa yang membuat yang bertahan tetap bertahan.</p>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<div class="ex"><p><strong>Experience:</strong> 120 klien kantoran. <strong>Pattern:</strong> banyak berhenti di minggu 3–5. <strong>Insight:</strong> mereka berhenti saat ritme kerja berubah, bukan saat latihan terlalu berat. <strong>Method:</strong> "Minggu Rawan", versi 20 menit yang tetap menjaga kebiasaan. <strong>Proof:</strong> tingkat kehadiran klien yang memakainya (dengan izin). <strong>Product:</strong> program 12 minggu. <strong>Asset:</strong> metode bernama, template minggu rawan, log kehadiran, materi onboarding.</p></div>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Meloncat dari experience langsung ke product tanpa insight.</li>
<li>Menamai metode sebelum yakin metode itu bekerja.</li>
<li>Tidak menyimpan data sejak awal sehingga proof tidak ada.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Jika Anda menangani 100 client dengan problem yang sama, apa yang bisa Anda dokumentasikan?"</li>
<li>"Apa pattern yang mulai Anda lihat? Apa methodology yang bisa lahir dari pengalaman itu?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Isi ketujuh langkah untuk segmen Anda memakai data nyata dari 10 klien terakhir. Tandai langkah yang datanya belum ada.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p><strong>My New Asset</strong>: satu aset prioritas beserta langkah pembuatannya.</p></div></div>
</article>

<article class="chap" id="b15" data-phase="aksi">
<header class="chap-h"><p class="eyebrow">Bab 15 · Aksi · ± 15 menit</p><h2>Business Model</h2><p class="lead">Jangan mengejar passive income secara naif. Naikkan leverage secara bertahap.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>Pendapatan yang hanya bergantung pada jam sesi memiliki batas jumlah jam. Leverage berarti satu keahlian melayani lebih banyak orang, atau memberi hasil lebih lama, tanpa menambah jam secara linear.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<div class="tw"><table>
<thead><tr><th>Model</th><th>Dijual</th><th>Contoh</th><th>Catatan</th></tr></thead>
<tbody>
<tr><td>1 · Time for money</td><td>Waktu</td><td>1 sesi, 1 pembayaran</td><td>Mudah dimulai, terbatas jam</td></tr>
<tr><td>2 · Expertise for money</td><td>Keahlian</td><td>Konsultasi, asesmen, program tertulis</td><td>Nilai dari insight, bukan lamanya</td></tr>
<tr><td>3 · Product for money</td><td>Produk</td><td>Program, grup kecil, workshop</td><td>Perlu offer dan proof yang jelas</td></tr>
<tr><td>4 · Asset for business</td><td>Aset</td><td>Metodologi, komunitas, brand, sistem, ekosistem produk</td><td>Perlu waktu, disiplin, dan distribusi</td></tr>
</tbody></table></div>
<p>Peserta <strong>tidak harus</strong> langsung pindah dari Model 1 ke Model 4. Tujuannya meningkatkan leverage bertahap, satu anak tangga setiap kali.</p>
<div class="callout"><b>Realita produk.</b> Kelas atau produk digital tetap memerlukan distribusi, dukungan peserta, dan pembaruan. "Passive" jarang benar-benar pasif.</div>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<p>Tahap 1: 15 klien 1:1. Tahap 2: tambahkan asesmen berbayar untuk calon klien. Tahap 3: ubah sebagian klien menjadi program grup 8 orang. Tahap 4: dokumentasikan metode, latih satu asisten, bangun komunitas alumni.</p>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Meninggalkan Model 1 sebelum Model 3 punya bukti.</li>
<li>Menghitung pendapatan tanpa menghitung waktu persiapan, biaya, dan dukungan.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Berapa persen pendapatan Anda sekarang yang berhenti bila Anda sakit satu bulan?"</li>
<li>"Satu langkah apa yang menaikkan leverage tanpa mengorbankan kualitas?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Tempatkan sumber pendapatan Anda saat ini pada empat model. Pilih <strong>satu</strong> langkah naik satu anak tangga untuk 90 hari ke depan.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Posisi model saat ini dan satu langkah leverage berikutnya.</p></div></div>
</article>

<article class="chap" id="b16" data-phase="aksi">
<header class="chap-h"><p class="eyebrow">Bab 16 · Aksi · ± 15 menit</p><h2>Business Opportunity Filter</h2><p class="lead">Uji setiap ide dengan tujuh pertanyaan sebelum menginvestasikan waktu.</p></header>
<div class="row why"><h3>WHY</h3><div>
<p>FT biasanya punya banyak ide. Filter ini membantu memilih satu yang punya peluang terbaik, bukan satu yang paling menarik secara pribadi.</p>
</div></div>
<div class="row how"><h3>HOW · Konsep</h3><div>
<p>Skor setiap kriteria: <strong>0</strong> belum ada, <strong>1</strong> sebagian, <strong>2</strong> kuat. Maksimal 14.</p>
<div class="tw"><table>
<thead><tr><th>#</th><th>Kriteria</th><th>Pertanyaan</th></tr></thead>
<tbody>
<tr><td>1</td><td>Customer pain</td><td>Apakah problem nyata?</td></tr>
<tr><td>2</td><td>Customer demand</td><td>Apakah orang mencari solusi?</td></tr>
<tr><td>3</td><td>Your capability</td><td>Apakah FT mampu menyelesaikannya, dalam scope?</td></tr>
<tr><td>4</td><td>Differentiation</td><td>Mengapa memilih FT ini?</td></tr>
<tr><td>5</td><td>Proof</td><td>Apakah ada evidence?</td></tr>
<tr><td>6</td><td>Economics</td><td>Apakah modelnya masuk akal setelah semua biaya dan waktu?</td></tr>
<tr><td>7</td><td>Asset potential</td><td>Apakah pengalaman ini membangun aset?</td></tr>
</tbody></table></div>
<ul>
<li><strong>11–14:</strong> jalankan.</li>
<li><strong>7–10:</strong> uji kecil (pilot) dulu.</li>
<li><strong>di bawah 7:</strong> revisi atau tunda.</li>
</ul>
</div></div>
<div class="row exm"><h3>Contoh FT</h3><div>
<p>Ide: kelas online "Fat Loss 30 Hari". Skor: pain 1, demand 2, capability 2, differentiation 0, proof 0, economics 1, asset 1 = 7. Putusan: uji kecil. Perbaiki differentiation dan kumpulkan proof sebelum membangun kelas.</p>
</div></div>
<div class="row err"><h3>Kesalahan umum</h3><div>
<ul>
<li>Memberi skor 2 pada demand tanpa melihat bukti pencarian atau pembelian.</li>
<li>Mengabaikan economics sampai produk selesai.</li>
</ul>
</div></div>
<div class="row qs"><h3>Pertanyaan fasilitator</h3><div>
<ul>
<li>"Apa bukti bahwa customer benar-benar mengalami masalah ini?"</li>
<li>"Apakah mereka willing to pay?"</li>
</ul>
</div></div>
<div class="row practice"><h3>Latihan</h3><div>
<p>Uji dua ide Anda dengan filter. Pasangan menantang tiga skor tertinggi.</p>
</div></div>
<div class="row out"><h3>Output</h3><div><p>Dua ide dengan skor dan satu keputusan: jalankan, pilot, atau revisi.</p></div></div>
</article>

<!-- STUDI KASUS -->
<article class="chap cases" id="b17" data-phase="aksi">
<header class="chap-h"><p class="eyebrow">Bab 17 · Aksi · ± 35 menit</p><h2>Bedah 4 Studi Kasus</h2><p class="lead">Setiap kasus dianalisis dengan rantai yang sama: Customer → Pain → Job → Gap → Skill → Knowledge → Value → Offer → Proof → Asset → Business Model.</p></header>
<div class="row how"><h3>Cara pakai</h3><div>
<p>Bagi peserta menjadi 4 kelompok. Beri setiap kelompok profil satu kasus <strong>tanpa analisisnya</strong>. Kelompok mengisi 11 langkah dalam 10 menit, lalu membandingkan dengan analisis di bawah. Kasus-kasus ini fiktif dan disusun untuk latihan.</p>
</div></div>

<div class="profile" style="--ph:var(--accent)"><h3 style="font:800 1.4rem/1.1 var(--f-display);text-transform:uppercase;margin-bottom:.4rem">Kasus 1 · Bayu, skill ada, positioning belum</h3>
<p>Bayu (24) bersertifikat, 8 bulan menjadi FT, punya 6 klien dengan tujuan berbeda-beda. Kontennya acak: tips, meme, video latihan. Ia menjawab "semua orang bisa jadi klien saya".</p></div>
<dl class="an" style="--ph:var(--accent)">
<dt>Customer</dt><dd>Karyawan 25–35 yang pernah ikut gym lalu berhenti.</dd>
<dt>Pain</dt><dd>L2: tidak tahu mulai dari mana. L3: malu di area beban. L4: "Saya bukan orang gym."</dd>
<dt>Job</dt><dd>Functional: rutinitas beban 3x seminggu. Emotional: percaya diri masuk area beban. Social: tidak dianggap pemula.</dd>
<dt>Gap</dt><dd>Program dari internet tidak cocok, tidak ada yang mengoreksi, berhenti di minggu 3.</dd>
<dt>Skill</dt><dd>Program design pemula, teknik dasar, coaching.</dd>
<dt>Knowledge</dt><dd>Progression untuk pemula dan cara onboarding gerakan dasar.</dd>
<dt>Value</dt><dd>"Untuk karyawan 25–35 yang pernah mulai gym lalu berhenti karena bingung dan malu, saya membantu membangun rutinitas latihan beban 3x seminggu selama 8 minggu tanpa harus paham semuanya dulu."</dd>
<dt>Offer</dt><dd>"Mulai 8 Minggu": 12 sesi tatap muka, panduan gerakan, check-in lewat chat.</dd>
<dt>Proof</dt><dd>Belum ada. Pilot 5 klien dengan harga perkenalan yang terbuka, catat kehadiran dan progres beban.</dd>
<dt>Asset</dt><dd>Template onboarding, log pilot, testimoni pertama.</dd>
<dt>Business model</dt><dd>Model 1 → 2/3 (paket program, lalu grup kecil).</dd>
<dt>Langkah berikut</dt><dd>5 klien pilot dalam 30 hari, bukan lebih banyak konten.</dd>
</dl>

<div class="profile" style="--ph:var(--pain);margin-top:1.2rem"><h3 style="font:800 1.4rem/1.1 var(--f-display);text-transform:uppercase;margin-bottom:.4rem">Kasus 2 · Sari, banyak klien, belum ada aset</h3>
<p>Sari memiliki 8 tahun pengalaman dan sekitar 150 klien selama kariernya. Jadwalnya penuh, pendapatannya mentok. Semua catatan ada di kepala dan chat pribadinya.</p></div>
<dl class="an" style="--ph:var(--pain)">
<dt>Customer</dt><dd>Perempuan 35–50 bekerja kantoran yang ingin kembali kuat dan berenergi.</dd>
<dt>Pain</dt><dd>L2: lelah, jadwal padat. L4: "Badan saya tidak seperti dulu." L5: makin jarang bergerak.</dd>
<dt>Job</dt><dd>Functional: latihan konsisten. Emotional: merasa kuat lagi. Social: tetap bisa mengikuti aktivitas keluarga.</dd>
<dt>Gap</dt><dd>Mereka berhenti saat ritme kerja berubah, sekitar minggu 3–5, bukan karena latihan.</dd>
<dt>Skill</dt><dd>Coaching, penyusunan program fleksibel, retensi.</dd>
<dt>Knowledge</dt><dd>Pola dari ±150 klien: kapan, mengapa berhenti, dan apa yang membuat bertahan.</dd>
<dt>Value</dt><dd>"Untuk perempuan pekerja yang berkali-kali berhenti latihan saat kerja sedang padat, saya membantu tetap konsisten 12 minggu lewat sistem latihan yang menyesuaikan jadwal, tanpa harus mulai dari nol setiap kali."</dd>
<dt>Offer</dt><dd>"12 Minggu Tetap Jalan": grup 6 orang, 2 sesi per minggu, protokol Minggu Rawan.</dd>
<dt>Proof</dt><dd>Data kehadiran klien lama (dengan izin), beberapa kisah bertahan.</dd>
<dt>Asset</dt><dd>Metode bernama, template minggu rawan, log retensi, materi onboarding, grup alumni.</dd>
<dt>Business model</dt><dd>1:1 → grup kecil → pelatihan asisten, bertahap.</dd>
<dt>Langkah berikut</dt><dd>Dokumentasikan 20 klien terakhir dalam 2 minggu, lalu pilot satu grup.</dd>
</dl>

<div class="profile" style="--ph:var(--ok);margin-top:1.2rem"><h3 style="font:800 1.4rem/1.1 var(--f-display);text-transform:uppercase;margin-bottom:.4rem">Kasus 3 · Dito, ilmu tinggi, value tidak tersampaikan</h3>
<p>Dito mendalami biomekanik dan membuat konten penuh istilah teknis. Pengikutnya menghargai, tetapi hampir tidak ada yang bertanya soal jasa.</p></div>
<dl class="an" style="--ph:var(--ok)">
<dt>Customer</dt><dd>Pekerja kantoran 30–45 yang takut angkat beban karena pernah merasakan nyeri.</dd>
<dt>Pain</dt><dd>L2: takut cedera. L3: cemas. L4: "Badan saya rapuh." Catatan scope: bila ada nyeri atau riwayat cedera, pastikan klien sudah diperiksa tenaga medis.</dd>
<dt>Job</dt><dd>Functional: kembali latihan beban. Emotional: tenang dan percaya diri. Social: tidak dianggap lemah.</dd>
<dt>Gap</dt><dd>Mereka tidak paham batas aman dan tidak tahu kapan lanjut, kurangi, atau konsultasi ke tenaga medis.</dd>
<dt>Skill</dt><dd>Movement coaching, regresi dan progresi gerakan, komunikasi.</dd>
<dt>Knowledge</dt><dd>Biomekanik, diubah menjadi insight: klien butuh aturan sederhana, bukan teori.</dd>
<dt>Value</dt><dd>"Untuk pekerja kantoran yang takut kembali angkat beban, saya membantu kembali berlatih dengan percaya diri lewat panduan gerakan bertahap, tanpa harus menghafal teori, dan dengan rujukan ke tenaga medis bila ada tanda yang perlu diperiksa."</dd>
<dt>Offer</dt><dd>"Kembali Angkat Beban 4 Minggu": asesmen gerak, program bertahap, dua sesi evaluasi.</dd>
<dt>Proof</dt><dd>Video gerak sebelum dan sesudah (dengan izin), kehadiran, pernyataan klien tentang rasa percaya diri. Tanpa klaim penyembuhan.</dd>
<dt>Asset</dt><dd>Protokol asesmen, library regresi dan progresi, checklist kapan merujuk.</dd>
<dt>Business model</dt><dd>Model 2 (asesmen berbayar) → Model 3 (program 4 minggu).</dd>
<dt>Langkah berikut</dt><dd>Ganti konten istilah teknis dengan cerita klien dan satu aturan sederhana per konten.</dd>
</dl>

<div class="profile" style="--ph:var(--gold);margin-top:1.2rem"><h3 style="font:800 1.4rem/1.1 var(--f-display);text-transform:uppercase;margin-bottom:.4rem">Kasus 4 · Maya, niche dan proof ada, offer tidak profitable</h3>
<p>Maya fokus pada strength training untuk perempuan 40+. Ia punya 12 alumni dan testimoni yang kuat. Namun ia menjual sesi satuan dengan tarif rendah dan merasa lelah.</p></div>
<dl class="an" style="--ph:var(--gold)">
<dt>Customer</dt><dd>Perempuan 40–55 yang ingin tetap kuat dan mandiri secara fisik.</dd>
<dt>Pain</dt><dd>L2: tenaga turun. L4: "Sudah bukan umurnya." L5: takut kehilangan kemandirian.</dd>
<dt>Job</dt><dd>Functional: bertambah kuat. Emotional: percaya pada tubuh sendiri. Social: tetap aktif bersama keluarga.</dd>
<dt>Gap</dt><dd>Kebanyakan program dibuat untuk orang yang lebih muda dan tidak menjelaskan progres.</dd>
<dt>Skill</dt><dd>Strength programming, coaching teknik, komunikasi yang menenangkan.</dd>
<dt>Knowledge</dt><dd>Pengalaman 12 alumni dan pola progres tiap fase.</dd>
<dt>Value</dt><dd>"Untuk perempuan 40+ yang ingin kuat kembali tetapi ragu memulai, saya membantu membangun kekuatan dalam 12 minggu lewat progres yang terukur dan bertahap."</dd>
<dt>Offer</dt><dd>Dari sesi satuan menjadi "Strong 12": grup 8 orang, 2 sesi per minggu, tes kekuatan awal dan akhir.</dd>
<dt>Proof</dt><dd>12 alumni, tes sebelum dan sesudah, kisah klien (dengan izin).</dd>
<dt>Asset</dt><dd>Protokol tes, kurikulum 12 minggu, komunitas alumni.</dd>
<dt>Business model</dt><dd>Contoh ilustrasi: 1:1 Rp300.000 per sesi. Grup 8 orang Rp1.200.000 per orang per bulan untuk 8 sesi menghasilkan Rp9.600.000, atau Rp1.200.000 per jam sesi. Biaya sewa tempat, asisten, dan waktu persiapan harus dihitung sebelum memutuskan harga.</dd>
<dt>Langkah berikut</dt><dd>Hitung biaya penuh, lalu pilot satu grup dengan evaluasi di minggu ke-2.</dd>
</dl>
<div class="row qs" style="border-top:1px solid var(--line);margin-top:1.2rem"><h3>Diskusi</h3><div>
<ul>
<li>"Di langkah mana masing-masing kasus macet? Di mana tebakan Anda berbeda dari analisis?"</li>
<li>"Aset apa yang sebenarnya sudah dimiliki tokoh ini tetapi belum dipakai?"</li>
</ul></div></div>
</article>

<!-- SIGNATURE EXERCISE -->
<article class="chap" id="b18" data-phase="aksi">
<header class="chap-h"><p class="eyebrow">Bab 18 · Aksi · Aktivitas utama</p><h2>From Customer Pain to Business Asset</h2><p class="lead">Signature exercise. Pilih satu segmen customer, lalu isi 14 kolom di bawah. Kerjakan secara bertahap setelah setiap bab, atau sekaligus di akhir.</p></header>
<div class="row how"><h3>Cara pakai</h3><div>
<ul>
<li>Tulis dengan kalimat pendek dan konkret. Satu kolom, 1–3 kalimat.</li>
<li>Kolom yang kosong atau penuh tebakan adalah agenda pekerjaan 90 hari Anda.</li>
<li>Isian tersimpan otomatis di browser ini.</li>
</ul></div></div>
<form id="f-sig" class="ws" autocomplete="off" onsubmit="return false"></form>
<div class="ws-bar" data-for="sig"></div>
</article>

<article class="chap" id="b19" data-phase="aksi">
<header class="chap-h"><p class="eyebrow">Bab 19 · Aksi · Deliverable akhir</p><h2>My Fitnesspreneur Business Blueprint</h2><p class="lead">Dokumen yang dibawa pulang. Salin dari Signature Exercise, lalu rapikan menjadi 16 bagian.</p></header>
<div class="row how"><h3>Rencana 90 hari</h3><div>
<p>Susun bagian 16 dengan tiga fase. Setiap fase maksimal tiga tindakan yang bisa dicek selesai atau tidak.</p>
<div class="tw"><table>
<thead><tr><th>Fase</th><th>Fokus</th><th>Contoh tindakan terukur</th></tr></thead>
<tbody>
<tr><td>Hari 1–30</td><td>Validasi</td><td>3 wawancara customer; skor ulang pain; mulai catat baseline klien</td></tr>
<tr><td>Hari 31–60</td><td>Bangun &amp; uji</td><td>Pilot offer ke 3–5 orang; kumpulkan proof; susun satu aset (template atau log)</td></tr>
<tr><td>Hari 61–90</td><td>Rapikan &amp; naikkan</td><td>Revisi offer dari hasil pilot; dokumentasikan case study; tentukan satu langkah leverage</td></tr>
</tbody></table></div>
<p class="note">Tindakan yang baik punya angka dan tanggal. "Mulai konten" bukan tindakan. "Wawancarai 3 klien sebelum tanggal 15" adalah tindakan.</p>
</div></div>
<form id="f-bp" class="ws" autocomplete="off" onsubmit="return false"></form>
<div class="ws-bar" data-for="bp"></div>
</article>

<!-- ============ TOOLKIT ============ -->
<div class="part-h" data-phase="konsep" style="--ph:var(--ink)"><h2>Toolkit fasilitator</h2><p>Dipakai di sepanjang sesi</p></div>

<article class="chap" id="fasil" data-phase="konsep">
<header class="chap-h"><p class="eyebrow">Toolkit · Peran</p><h2>Peran fasilitator</h2><p class="lead">Fasilitator tidak memberi semua jawaban. Fasilitator membantu peserta bergerak dari pengamatan sampai aset.</p></header>
<div class="row how"><h3>7 tahap</h3><div>
<div class="tw"><table>
<thead><tr><th>Tahap</th><th>Pertanyaan inti</th><th>Yang dilakukan fasilitator</th></tr></thead>
<tbody>
<tr><td>Observe</td><td>Apa yang terjadi?</td><td>Minta peserta menceritakan kasus nyata, tanpa kesimpulan.</td></tr>
<tr><td>Question</td><td>Mengapa terjadi?</td><td>Tanyakan "mengapa" dan "kapan" berulang.</td></tr>
<tr><td>Discover</td><td>Apa pain sebenarnya?</td><td>Turunkan Pain Ladder, minta kutipan verbatim.</td></tr>
<tr><td>Connect</td><td>Apa hubungannya dengan expertise?</td><td>Hubungkan pain dengan skill dan knowledge peserta.</td></tr>
<tr><td>Design</td><td>Solusi apa yang relevan?</td><td>Dorong value proposition dan offer yang spesifik.</td></tr>
<tr><td>Validate</td><td>Apakah customer akan menganggap ini valuable?</td><td>Minta bukti, bukan keyakinan. Arahkan ke wawancara dan pilot.</td></tr>
<tr><td>Assetize</td><td>Apa yang dapat dibangun?</td><td>Cari pola, metode, dan dokumentasi yang bisa dipakai ulang.</td></tr>
</tbody></table></div>
<p><strong>Aturan praktis:</strong> bila Anda berbicara lebih dari 30% waktu, Anda sedang menceramahi. Ganti dengan pertanyaan. Bila peserta mengatakan "semua orang", minta satu nama.</p>
</div></div>
</article>

<section class="sec" id="qbank">
<div class="sec-intro">
<h2>Bank pertanyaan tajam</h2>
<p>32 pertanyaan, dikelompokkan sesuai 7 tahap fasilitasi. Pilih 2–3 per sesi. Pertanyaan yang tidak nyaman biasanya yang paling berguna.</p>

<div class="qgroup" style="--ph:var(--accent)"><h3>Observe &amp; Question</h3><ol>
<li>"Apa pain sebenarnya?"</li>
<li>"Apakah ini pain atau hanya preference?"</li>
<li>"Apa bukti bahwa customer benar-benar mengalami masalah ini?"</li>
<li>"Kapan pain tersebut paling terasa?"</li>
<li>"Apa yang sudah mereka coba?"</li>
<li>"Mengapa solusi sebelumnya gagal?"</li>
</ol></div>

<div class="qgroup" style="--ph:var(--pain)"><h3>Discover</h3><ol>
<li>"Apa consequence jika masalah ini tidak diselesaikan?"</li>
<li>"Siapa yang paling merasakan pain ini?"</li>
<li>"Pain ini ada di level berapa pada Pain Ladder? Apa yang ada di bawahnya?"</li>
<li>"Kalimat apa yang diucapkan klien, persis dengan katanya?"</li>
<li>"Apa yang sebenarnya dibeli orang ini, bukan yang mereka ucapkan?"</li>
<li>"Apa hal yang tidak ingin mereka akui?"</li>
<li>"Seberapa sadar mereka bahwa ini masalah?"</li>
<li>"Apakah mereka willing to pay? Apa buktinya?"</li>
</ol></div>

<div class="qgroup" style="--ph:var(--ok)"><h3>Connect &amp; Design</h3><ol>
<li>"Apa skill Anda yang paling relevan untuk pain ini?"</li>
<li>"Skill mana yang Anda sukai tetapi tidak dibayar customer?"</li>
<li>"Apa yang membedakan solusi Anda dari trainer lain?"</li>
<li>"Apa yang Anda tahu yang membuat klien berhenti mencoba-coba?"</li>
<li>"Kalimat value proposition Anda bisa ditempel pada trainer lain? Mengapa?"</li>
<li>"Bagaimana solusi ini menjadi offer?"</li>
<li>"Apa risiko yang dirasakan klien sebelum membeli, dan bagaimana Anda menguranginya secara etis?"</li>
<li>"Apakah harga Anda mengikuti nilai bagi klien atau tarif pesaing?"</li>
</ol></div>

<div class="qgroup" style="--ph:var(--gold)"><h3>Validate</h3><ol>
<li>"Apa bukti Anda?"</li>
<li>"Siapa yang bisa memverifikasi klaim ini?"</li>
<li>"Apa cara paling murah untuk menguji ide ini minggu depan?"</li>
<li>"Apa yang akan membuat Anda menyimpulkan ide ini salah?"</li>
</ol></div>

<div class="qgroup" style="--ph:var(--ink)"><h3>Assetize</h3><ol>
<li>"Apa bagian dari solusi ini yang dapat menjadi asset?"</li>
<li>"Jika Anda menangani 100 client dengan problem yang sama, apa yang bisa Anda dokumentasikan?"</li>
<li>"Apa pattern yang mulai Anda lihat?"</li>
<li>"Apa methodology yang bisa lahir dari experience tersebut?"</li>
<li>"Apa yang tetap Anda miliki setelah sesi selesai?"</li>
<li>"Apa yang bisa digunakan kembali tanpa memulai dari nol?"</li>
</ol></div>

</div>
</section>

<section class="sec" id="etika">
<div class="sec-intro">
<h2>Standar etika &amp; scope</h2>
<p>Modul ini mengajarkan bisnis yang bisa dipertanggungjawabkan. Fasilitator memeriksa hal berikut pada setiap output peserta.</p>
<ul>
<li><strong>Scope of practice:</strong> tidak ada klaim diagnosis, terapi, atau rehabilitasi medis. Rujuk ke tenaga medis atau gizi bila perlu.</li>
<li><strong>Klaim hasil:</strong> tidak ada jaminan hasil tubuh. Jaminan boleh berupa proses dan evaluasi.</li>
<li><strong>Proof:</strong> nyata, ada izin, tidak menyesatkan, tidak diwakilkan sebagai hasil semua orang.</li>
<li><strong>Penjualan:</strong> tanpa urgensi palsu, tanpa memanfaatkan rasa malu atau takut klien.</li>
<li><strong>Privasi:</strong> data klien disimpan dan dipakai sesuai persetujuan.</li>
<li><strong>Tidak semua FT harus menjadi influencer:</strong> jalur referral, komunitas, dan kemitraan lokal sama sahnya.</li>
</ul>
<p><strong>Cek kualitas output peserta:</strong> berorientasi pada customer problem; spesifik, bukan generik; berbasis pengalaman dan evidence nyata; menghasilkan tindakan konkret yang bisa dicek.</p>
</div>
</section>

<section class="closing" id="penutup" aria-label="Penutup modul">
<p>Jangan mulai bisnis dari apa yang ingin Anda jual.</p>
<p>Mulailah dari masalah yang ingin customer selesaikan.</p>
<p>Gunakan skill Anda untuk menyelesaikannya.</p>
<p>Gunakan knowledge Anda untuk memperkuat solusinya.</p>
<p>Gunakan experience untuk membuktikannya.</p>
<p>Kemudian ubah pengalaman tersebut menjadi asset.</p>
<p>Karena Fitnesspreneur bukan sekadar Fitness Trainer yang menjual lebih banyak sesi.</p>
<p class="last">Fitnesspreneur adalah Fitness Trainer yang mampu mengubah expertise menjadi value, value menjadi business, dan business menjadi <em>asset</em>.</p>
</section>
<a class="top" href="#atas">↑ Kembali ke atas</a>
</main>
</div>
</div>

<script>
(function(){
  var SIG=[
    ["who","Who","Segmen yang saya pilih (siapa + konteks)",""],
    ["pain","Pain","Pain Ladder: dari surface sampai identity/consequence",""],
    ["why","Why","Why behind the why: alasan terdalam",""],
    ["failed","Failed attempts","Apa yang sudah dicoba dan mengapa gagal",""],
    ["outcome","Desired outcome","Apa yang berubah bila masalah selesai",""],
    ["job","Customer job","Functional, emotional, social",""],
    ["skill","My relevant skill","Skill yang paling relevan untuk pain ini",""],
    ["knowledge","My knowledge","Knowledge dan insight khas saya",""],
    ["method","My method","Cara saya menyelesaikannya (nama sementara)",""],
    ["proof","My proof","Claim → proof, dan bukti yang akan dikumpulkan",""],
    ["offer","My offer","Promise, experience, harga, risk reversal, next step",""],
    ["asset","My asset","Aset yang akan lahir dari proses ini",""],
    ["model","Business model","Posisi sekarang dan langkah naik satu model",""],
    ["move","90-day next move","Tiga tindakan dengan angka dan tanggal","wide"]
  ];
  var BP=[
    ["customer","1. Customer","Segmen dalam satu kalimat",""],
    ["pain","2. Customer pain","Pain prioritas dan levelnya",""],
    ["job","3. Customer job","Functional, emotional, social",""],
    ["outcome","4. Desired outcome","Hasil yang diinginkan customer",""],
    ["failed","5. Failed attempts","Yang sudah dicoba dan alasannya gagal",""],
    ["gap","6. Market gap","Celah yang belum dijawab solusi lain",""],
    ["skill","7. My skill","Skill inti dan skill pendukung",""],
    ["knowledge","8. My knowledge","Knowledge dan insight",""],
    ["method","9. My method","Metode dan namanya",""],
    ["vp","10. My value proposition","Untuk … yang kesulitan … saya membantu … melalui … tanpa …","wide"],
    ["proof","11. My proof","Claim → proof",""],
    ["offer","12. My offer","Sembilan komponen offer",""],
    ["existing","13. My existing asset","Aset yang sudah ada",""],
    ["newasset","14. My new asset","Aset yang akan dibangun",""],
    ["model","15. Business model","Posisi model dan langkah leverage",""],
    ["plan","16. 90-day action plan","Hari 1–30, 31–60, 61–90","wide"]
  ];
  function store(k,v){try{if(v===undefined)return localStorage.getItem(k);localStorage.setItem(k,v)}catch(e){return null}}
  function build(formId,key,fields){
    var f=document.getElementById(formId),bar=document.querySelector('[data-for="'+key+'"]');
    if(!f||!bar)return;
    var saved={};try{saved=JSON.parse(store('fp-'+key)||'{}')}catch(e){}
    fields.forEach(function(d){
      var w=document.createElement('div');if(d[3])w.className=d[3];
      var id=key+'-'+d[0];
      var l=document.createElement('label');l.htmlFor=id;l.textContent=d[1];
      var h=document.createElement('span');h.className='hint';h.textContent=d[2];
      var t=document.createElement('textarea');t.id=id;t.name=id;t.value=saved[d[0]]||'';
      t.addEventListener('input',function(){saved[d[0]]=t.value;store('fp-'+key,JSON.stringify(saved));st.textContent='Tersimpan di browser ini'});
      w.appendChild(l);w.appendChild(h);w.appendChild(t);f.appendChild(w);
    });
    var copy=document.createElement('button');copy.type='button';copy.className='btn';copy.textContent='Salin semua';
    var clr=document.createElement('button');clr.type='button';clr.className='btn ghost';clr.textContent='Kosongkan isian';
    var st=document.createElement('span');st.className='status';st.setAttribute('role','status');
    bar.appendChild(copy);bar.appendChild(clr);bar.appendChild(st);
    function text(){return fields.map(function(d){return d[1].toUpperCase()+'\n'+(saved[d[0]]||'-')}).join('\n\n')}
    copy.addEventListener('click',function(){
      var done=function(){st.textContent='Tersalin. Tempel ke dokumen Anda.'};
      var fail=function(){var a=f.querySelector('textarea');st.textContent='Salin manual: pilih isian lalu tekan Ctrl+C';if(a)a.focus()};
      try{navigator.clipboard.writeText(text()).then(done,fail)}catch(e){fail()}
    });
    var armed=false,tm;
    clr.addEventListener('click',function(){
      if(!armed){armed=true;clr.textContent='Klik lagi untuk menghapus';clr.classList.add('warn');tm=setTimeout(reset,4000);return}
      clearTimeout(tm);fields.forEach(function(d){saved[d[0]]='';});
      f.querySelectorAll('textarea').forEach(function(x){x.value=''});
      store('fp-'+key,'{}');st.textContent='Isian dikosongkan';reset();
    });
    function reset(){armed=false;clr.textContent='Kosongkan isian';clr.classList.remove('warn')}
  }
  build('f-sig','sig',SIG);
  build('f-bp','bp',BP);
  var d=document.getElementById('tocd');
  if(d&&window.matchMedia&&!window.matchMedia('(min-width:1000px)').matches)d.open=false;
})();
</script>

</body></html>
