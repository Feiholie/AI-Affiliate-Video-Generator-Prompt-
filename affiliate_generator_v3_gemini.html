<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AI Affiliate Video Generator v3</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@3.0.0/tabler-icons.min.css">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:system-ui,-apple-system,sans-serif;background:#f8f7f4;color:#1a1a1a;min-height:100vh;padding:2rem 1rem}
.wrap{max-width:720px;margin:0 auto}
h1{font-size:20px;font-weight:600;margin-bottom:4px}
.sub{font-size:13px;color:#666;margin-bottom:2rem}

/* API KEY MODAL */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.45);z-index:999;display:flex;align-items:center;justify-content:center;padding:1rem}
.modal-overlay.hidden{display:none}
.modal{background:#fff;border-radius:16px;padding:1.5rem;width:100%;max-width:460px;box-shadow:0 20px 60px rgba(0,0,0,.2)}
.modal h2{font-size:16px;font-weight:700;margin-bottom:6px}
.modal p{font-size:13px;color:#555;margin-bottom:.75rem;line-height:1.6}
.modal a{color:#1a73e8;text-decoration:none;font-weight:600}
.modal a:hover{text-decoration:underline}
.modal input{width:100%;padding:10px 12px;border:1.5px solid #ddd;border-radius:9px;font-size:13px;font-family:monospace;margin-bottom:12px;outline:none}
.modal input:focus{border-color:#1a73e8}
.modal-btns{display:flex;gap:8px}
.modal-btns button{flex:1;padding:10px;border-radius:9px;font-size:14px;font-weight:600;cursor:pointer;border:none}
.mbtn-ok{background:#1a73e8;color:#fff}
.mbtn-ok:hover{background:#1558b0}
.mbtn-cancel{background:#f0eeeb;color:#555}
.mbtn-cancel:hover{background:#e5e3de}
.api-note{font-size:11px;color:#999;margin-top:10px;line-height:1.5;padding:8px 10px;background:#f8f7f4;border-radius:7px}
.free-badge{display:inline-flex;align-items:center;gap:5px;background:#e8f5e9;color:#2e7d32;font-size:12px;font-weight:700;padding:4px 10px;border-radius:20px;margin-bottom:10px}

/* API KEY BAR */
.apibar{display:flex;align-items:center;gap:10px;background:#fff;border:1px solid #e5e3de;border-radius:10px;padding:10px 14px;margin-bottom:1.25rem}
.apibar-icon{font-size:18px}
.apibar-info{flex:1}
.apibar-label{font-size:11px;color:#888;font-weight:600;text-transform:uppercase;letter-spacing:.4px}
.apibar-val{font-size:13px;color:#1a1a1a}
.apibar-btn{padding:6px 12px;border-radius:7px;font-size:12px;font-weight:600;cursor:pointer;border:1px solid #ddd;background:#f8f7f4;color:#555}
.apibar-btn:hover{background:#e8e6e1}
.apibar-connected{color:#2e7d32;font-weight:600}
.free-tag{font-size:10px;background:#e8f5e9;color:#2e7d32;border-radius:5px;padding:2px 6px;font-weight:700;margin-left:6px}

.sh{display:flex;align-items:center;gap:10px;margin-bottom:.75rem}
.sb{width:28px;height:28px;border-radius:50%;background:#e8e6e1;border:1px solid #d0cec9;display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:600;color:#555;flex-shrink:0}
.sb.on{background:#1a73e8;color:#fff;border-color:#1a73e8}
.sb.ok{background:#0F6E56;color:#fff;border-color:#0F6E56}
.st{font-size:15px;font-weight:600;color:#1a1a1a}
.ss{font-size:12px;color:#888;margin-top:2px}

.card{background:#fff;border:1px solid #e5e3de;border-radius:14px;padding:1.25rem;margin-bottom:1rem}
label{font-size:13px;color:#555;display:block;margin-bottom:5px}
input[type=text],textarea,select{width:100%;padding:9px 12px;border:1px solid #ddd;border-radius:8px;font-size:14px;font-family:inherit;color:#1a1a1a;background:#fff;outline:none}
input[type=text]:focus,select:focus,textarea:focus{border-color:#1a73e8;box-shadow:0 0 0 3px #1a73e808}
.r2{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:12px}
.f{margin-bottom:12px}

.afflink-wrap{display:flex;gap:8px;align-items:center}
.afflink-wrap input{flex:1}
.aff-tag{font-size:11px;background:#dcfce7;color:#15803d;border-radius:6px;padding:3px 8px;white-space:nowrap;font-weight:600}

.uz{border:2px dashed #ccc;border-radius:12px;padding:2.5rem 1rem;text-align:center;cursor:pointer;background:#fafaf8;margin-bottom:12px;position:relative;transition:.2s}
.uz:hover,.uz.dov{border-color:#1a73e8;background:#f0f5fb}
.uz input[type=file]{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%;height:100%}
.uico{font-size:36px;color:#aaa;margin-bottom:8px}
.utxt{font-size:14px;color:#666;font-weight:500}
.usub{font-size:12px;color:#aaa;margin-top:4px}

.pvw{display:none;border-radius:10px;overflow:hidden;border:1px solid #e5e3de;margin-bottom:12px;position:relative}
.pvw img{width:100%;max-height:240px;object-fit:contain;background:#f8f7f4}
.rmbtn{position:absolute;top:8px;right:8px;background:#fff;border:1px solid #ddd;border-radius:8px;padding:5px 12px;font-size:12px;cursor:pointer;color:#555}
.rmbtn:hover{background:#fee2e2;border-color:#fca5a5;color:#dc2626}

.agrid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:14px}
.ac{border:2px solid transparent;border-radius:10px;padding:10px 6px;text-align:center;cursor:pointer;background:#f8f7f4;transition:.15s}
.ac:hover{border-color:#ccc}
.ac.sel{border-color:#1a73e8;background:#e8f0fe}
.ae{font-size:22px;display:block;margin-bottom:4px}
.an{font-size:11px;color:#333;font-weight:600}
.ad{font-size:10px;color:#888;margin-top:2px}

.bp{width:100%;padding:12px;background:#1a73e8;color:#fff;border:none;border-radius:10px;font-size:15px;font-weight:600;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:8px;margin-top:.5rem;transition:.15s}
.bp:hover{background:#1558b0}
.bp:disabled{opacity:.5;cursor:not-allowed}
.bs{width:100%;padding:11px;background:#fff;color:#333;border:1px solid #ddd;border-radius:10px;font-size:14px;font-weight:500;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:8px;margin-top:10px}
.bs:hover{background:#f8f7f4}
.bexport{width:100%;padding:11px;background:#0F6E56;color:#fff;border:none;border-radius:10px;font-size:14px;font-weight:600;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:8px;margin-top:10px}
.bexport:hover{background:#0a5240}

.pb{background:#f0f4ff;border-left:3px solid #1a73e8;border-radius:0 10px 10px 0;padding:12px 14px;margin-bottom:10px;position:relative}
.pl{font-size:11px;font-weight:700;color:#1a73e8;margin-bottom:5px;text-transform:uppercase;letter-spacing:.5px}
.ob{background:#f8f7f4;border-radius:10px;padding:1rem;margin-bottom:12px;position:relative}
.ol{font-size:11px;font-weight:700;color:#888;text-transform:uppercase;letter-spacing:.5px;margin-bottom:8px}
.ot{font-size:13px;line-height:1.75;color:#1a1a1a;white-space:pre-wrap;word-break:break-word;padding-right:110px}

.skel{background:linear-gradient(90deg,#e8e6e1 25%,#f0eeeb 50%,#e8e6e1 75%);background-size:200% 100%;animation:skel 1.4s infinite;border-radius:6px;height:16px;width:90%;margin-bottom:6px}
.skel.w60{width:60%}.skel.w80{width:80%}
@keyframes skel{0%{background-position:200% 0}100%{background-position:-200% 0}}

.btn-row{display:flex;gap:6px;position:absolute;top:10px;right:10px}
.cb{background:#fff;border:1px solid #ddd;border-radius:8px;padding:5px 10px;font-size:11px;color:#555;cursor:pointer;white-space:nowrap}
.cb:hover{background:#f8f7f4}
.rb{background:#fff;border:1px solid #ddd;border-radius:8px;padding:5px 10px;font-size:11px;color:#1a73e8;cursor:pointer;white-space:nowrap}
.rb:hover{background:#e8f0fe;border-color:#1a73e8}
.rb:disabled{opacity:.4;cursor:not-allowed}

.tr{display:flex;gap:6px;margin-bottom:12px}
.tb{padding:6px 16px;border-radius:20px;font-size:13px;cursor:pointer;border:1px solid #ddd;background:#fff;color:#555;font-weight:500}
.tb.on{background:#1a73e8;color:#fff;border-color:#1a73e8}

.dv{border:none;border-top:1px solid #e5e3de;margin:1.25rem 0}
.hidden{display:none}
.ipill{display:inline-flex;align-items:center;gap:6px;background:#dbeafe;color:#1d4ed8;border-radius:20px;padding:5px 12px;font-size:12px;font-weight:500;margin-bottom:12px}
.inote{font-size:12px;color:#888;margin-bottom:10px;padding:10px 12px;background:#f8f7f4;border-radius:8px}
.anabox{background:#f0f9f5;border-radius:10px;padding:12px;margin-bottom:12px;border:1px solid #9FE1CB}
.anlbl{font-size:11px;font-weight:700;color:#0F6E56;text-transform:uppercase;letter-spacing:.5px;margin-bottom:5px}

/* HISTORY */
.hist-header{display:flex;align-items:center;justify-content:space-between;margin-bottom:.75rem;margin-top:1.5rem}
.hist-title{font-size:15px;font-weight:600}
.hist-clear{font-size:12px;color:#dc2626;cursor:pointer;border:none;background:none;padding:4px 8px;border-radius:6px}
.hist-clear:hover{background:#fee2e2}
.hist-empty{font-size:13px;color:#aaa;text-align:center;padding:1.5rem;background:#fff;border:1px solid #e5e3de;border-radius:14px}
.hist-item{background:#fff;border:1px solid #e5e3de;border-radius:12px;padding:1rem;margin-bottom:.75rem;cursor:pointer;transition:.15s}
.hist-item:hover{border-color:#1a73e8;background:#f8fbff}
.hist-prod{font-size:14px;font-weight:600;color:#1a1a1a}
.hist-meta{font-size:12px;color:#888;margin-top:3px}
.hist-badges{display:flex;gap:6px;margin-top:8px;flex-wrap:wrap}
.hist-badge{font-size:11px;background:#f0eeeb;color:#555;border-radius:6px;padding:3px 8px;font-weight:500}
.hist-load{font-size:12px;color:#1a73e8;font-weight:600;margin-top:6px}
</style>
</head>
<body>

<!-- API KEY MODAL -->
<div class="modal-overlay" id="apiModal">
  <div class="modal">
    <div class="free-badge">🆓 GRATIS — Google Gemini API</div>
    <h2>🔑 Masukkan Gemini API Key</h2>
    <p>Daftar & ambil API Key gratis di:<br>
    👉 <a href="https://aistudio.google.com/apikey" target="_blank">aistudio.google.com/apikey</a><br><br>
    Login pakai Google Account → klik <strong>"Create API Key"</strong> → copy → paste di sini.</p>
    <input type="password" id="apiInput" placeholder="AIzaSy..." autocomplete="off"/>
    <div class="modal-btns">
      <button class="mbtn-cancel" id="apiCancel">Nanti saja</button>
      <button class="mbtn-ok" onclick="saveKey()">Simpan & Mulai</button>
    </div>
    <div class="api-note">💡 Key disimpan di browser kamu (localStorage). Tidak ada biaya — Gemini API gratis 1.500 request/hari.</div>
  </div>
</div>

<div class="wrap">
  <h1>🎬 AI Affiliate Video Generator</h1>
  <div class="sub">Upload foto produk → pilih aesthetic Pinterest → generate semua konten sekaligus</div>

  <!-- API KEY BAR -->
  <div class="apibar" id="apibar">
    <div class="apibar-icon">🔑</div>
    <div class="apibar-info">
      <div class="apibar-label">Gemini API Key <span class="free-tag">GRATIS</span></div>
      <div class="apibar-val" id="apibarVal">Belum diset — klik Pasang Key</div>
    </div>
    <button class="apibar-btn" onclick="openApiModal()">Pasang Key</button>
  </div>

  <!-- STEP 1 -->
  <div class="sh"><div class="sb on">1</div><div><div class="st">Detail Produk</div></div></div>
  <div class="card">
    <div class="f"><label>Nama Produk</label><input type="text" id="produk" placeholder="contoh: Serum Vitamin C Somethinc 20%"/></div>
    <div class="r2">
      <div><label>Kategori</label><select id="kategori"><option value="skincare">Skincare / Kecantikan</option><option value="suplemen">Suplemen / Kesehatan</option><option value="fashion">Fashion / Pakaian</option><option value="gadget">Gadget / Elektronik</option><option value="makanan">Makanan / Minuman</option><option value="digital">Produk Digital</option><option value="rumah">Peralatan Rumah</option></select></div>
      <div><label>Platform Target</label><select id="platform"><option value="tiktok">TikTok</option><option value="reels">Instagram Reels</option><option value="facebook">Facebook</option><option value="youtube">YouTube Shorts</option></select></div>
    </div>
    <div class="f"><label>Keunggulan Produk (pisahkan koma)</label><input type="text" id="benefit" placeholder="contoh: mencerahkan, anti aging, BPOM"/></div>
    <div class="r2">
      <div><label>Target Audiens</label><input type="text" id="audiens" placeholder="contoh: wanita 20-35 tahun"/></div>
      <div><label>Harga / Promo</label><input type="text" id="harga" placeholder="contoh: 89rb, diskon 30%"/></div>
    </div>
    <div class="f"><label>Tone Konten</label><select id="tone"><option value="relatable">Relatable & Santai</option><option value="edukatif">Edukatif & Informatif</option><option value="dramatis">Dramatis & Emosional</option><option value="funny">Lucu & Kocak</option><option value="premium">Premium & Aspirasional</option></select></div>
    <div class="f">
      <label>Link Affiliate <span style="color:#15803d;font-weight:600">(opsional — otomatis masuk ke caption)</span></label>
      <div class="afflink-wrap">
        <input type="text" id="afflink" placeholder="https://shope.ee/xxxxx atau bit.ly/xxxxx"/>
        <span class="aff-tag" id="afftag" style="display:none">✓ Link aktif</span>
      </div>
    </div>
  </div>

  <!-- STEP 2 -->
  <div class="sh"><div class="sb on">2</div><div><div class="st">Upload Foto Produk</div><div class="ss">Opsional — AI analisis foto & sesuaikan prompt dengan produk asli</div></div></div>
  <div class="card">
    <div class="uz" id="uz" ondragover="dov(event)" ondragleave="dol(event)" ondrop="ddr(event)">
      <input type="file" accept="image/*" onchange="hf(event)" id="fi"/>
      <div class="uico">📸</div>
      <div class="utxt">Klik atau drag foto produk ke sini</div>
      <div class="usub">JPG, PNG, WEBP — maks 10MB</div>
    </div>
    <div class="pvw" id="pvw"><img id="pimg" src="" alt="Preview"/><button class="rmbtn" onclick="rmimg()">✕ Hapus</button></div>

    <label style="margin-bottom:8px;font-weight:600">Pilih Aesthetic / Vibe Pinterest</label>
    <div class="agrid">
      <div class="ac sel" onclick="selA(this,'soft-beige')"><span class="ae">🤍</span><div class="an">Soft Beige</div><div class="ad">clean & minimal</div></div>
      <div class="ac" onclick="selA(this,'dark-moody')"><span class="ae">🖤</span><div class="an">Dark Moody</div><div class="ad">dramatic & luxe</div></div>
      <div class="ac" onclick="selA(this,'botanical')"><span class="ae">🌿</span><div class="an">Botanical</div><div class="ad">natural & organic</div></div>
      <div class="ac" onclick="selA(this,'pastel-dream')"><span class="ae">🌸</span><div class="an">Pastel Dream</div><div class="ad">soft & feminine</div></div>
      <div class="ac" onclick="selA(this,'golden-hour')"><span class="ae">🌅</span><div class="an">Golden Hour</div><div class="ad">warm & glowy</div></div>
      <div class="ac" onclick="selA(this,'marble-luxe')"><span class="ae">🪨</span><div class="an">Marble Luxe</div><div class="ad">elegant & premium</div></div>
      <div class="ac" onclick="selA(this,'cafe-latte')"><span class="ae">☕</span><div class="an">Café Latte</div><div class="ad">cozy & earthy</div></div>
      <div class="ac" onclick="selA(this,'clean-white')"><span class="ae">🫧</span><div class="an">Clean White</div><div class="ad">studio & fresh</div></div>
    </div>
    <div id="noImgNote" class="inote">ℹ️ Tanpa foto — AI generate prompt estetik berdasarkan nama produk & aesthetic pilihan.</div>
    <div id="imgNote" class="ipill hidden">✓ Foto terdeteksi — AI analisis & sesuaikan prompt dengan produk asli</div>
  </div>

  <button class="bp" id="bg" onclick="run()">✨ Generate Semua Konten + Prompt Gambar Estetik</button>

  <!-- RESULTS -->
  <div id="res" class="hidden">
    <hr class="dv">
    <div class="sh" style="margin-top:.5rem">
      <div class="sb ok">✓</div>
      <div><div class="st">Prompt Gambar Estetik Pinterest</div><div class="ss">Copy → paste langsung ke FlowAI / Midjourney / Leonardo AI</div></div>
    </div>
    <div class="card">
      <div id="anabox" class="hidden">
        <div class="anabox"><div class="anlbl">📷 Analisis Produk dari Foto</div><div class="ot" id="ana" style="padding-right:0"></div></div>
      </div>
      <div class="pb"><div class="pl">Scene 1 — Hero Shot</div><div class="ot" id="ip1">...</div><div class="btn-row"><button class="rb" onclick="regen('img')" id="rb-img">↻ Ulang</button><button class="cb" onclick="cp('ip1')">📋 salin</button></div></div>
      <div class="pb"><div class="pl">Scene 2 — Detail / Close-up</div><div class="ot" id="ip2">...</div></div>
      <div class="pb"><div class="pl">Scene 3 — Lifestyle / Flatlay</div><div class="ot" id="ip3">...</div></div>
    </div>

    <div class="sh">
      <div class="sb ok">✓</div>
      <div class="st">Prompt Video & Foto Scene</div>
    </div>
    <div class="card">
      <div class="tr">
        <button class="tb on" onclick="swt('foto')">Prompt Foto</button>
        <button class="tb" onclick="swt('video')">Prompt Video</button>
      </div>
      <div id="tfo">
        <div class="ob"><div class="ol">Scene 1 — Hook Visual</div><div class="ot" id="f1">...</div><div class="btn-row"><button class="rb" onclick="regen('foto')" id="rb-foto">↻ Ulang</button><button class="cb" onclick="cp('f1')">📋 salin</button></div></div>
        <div class="ob"><div class="ol">Scene 2 — Product Close-up</div><div class="ot" id="f2">...</div></div>
        <div class="ob"><div class="ol">Scene 3 — Result / Testimonial</div><div class="ot" id="f3">...</div></div>
      </div>
      <div id="tvi" class="hidden">
        <div class="ob"><div class="ol">Scene 1 — Opening Hook (3-5 dtk)</div><div class="ot" id="v1">...</div><div class="btn-row"><button class="rb" onclick="regen('video')" id="rb-video">↻ Ulang</button><button class="cb" onclick="cp('v1')">📋 salin</button></div></div>
        <div class="ob"><div class="ol">Scene 2 — Demo Penggunaan (5-8 dtk)</div><div class="ot" id="v2">...</div></div>
        <div class="ob"><div class="ol">Scene 3 — CTA Closing (3-5 dtk)</div><div class="ot" id="v3">...</div></div>
      </div>
    </div>

    <div class="sh">
      <div class="sb ok">✓</div>
      <div class="st">Hook, Caption & Hashtag</div>
    </div>
    <div class="card">
      <div class="ob"><div class="ol">Hook (3 pilihan)</div><div class="ot" id="hk">...</div><div class="btn-row"><button class="rb" onclick="regen('caption')" id="rb-cap">↻ Ulang</button><button class="cb" onclick="cp('hk')">📋 salin</button></div></div>
      <div class="ob"><div class="ol">Caption Lengkap <span id="affbadge" style="display:none;font-size:10px;background:#dcfce7;color:#15803d;border-radius:5px;padding:2px 6px;font-weight:600;margin-left:6px">+ Link Affiliate</span></div><div class="ot" id="cap">...</div><button class="cb" style="position:absolute;top:10px;right:10px" onclick="cp('cap')">📋 salin</button></div>
      <div class="ob"><div class="ol">Hashtag (20 tag)</div><div class="ot" id="htg">...</div><button class="cb" style="position:absolute;top:10px;right:10px" onclick="cp('htg')">📋 salin</button></div>
    </div>

    <button class="bexport" onclick="exportTxt()">⬇️ Export Semua Hasil ke .TXT</button>
    <button class="bs" onclick="rst()">🔄 Generate Produk Baru</button>
  </div>

  <!-- HISTORY -->
  <div id="histSection">
    <div class="hist-header">
      <div class="hist-title">🕓 Riwayat Generate</div>
      <button class="hist-clear" onclick="clearHist()">Hapus semua</button>
    </div>
    <div id="histList"></div>
  </div>
</div>

<script>
// ── STATE ──────────────────────────────────────────────
let b64=null, imgMime='image/jpeg', aes='soft-beige', lastCtx=null;

const AP={
  'soft-beige':'soft beige linen background, warm neutral tones, minimalist nordic styling, scattered dried pampas grass, subtle shadow play, muted ivory warm sand palette, editorial clean aesthetic',
  'dark-moody':'dark charcoal slate background, dramatic low-key lighting, deep rich shadows, black marble surface, single spotlight rim light, luxury editorial, cinematic moody atmosphere',
  'botanical':'fresh tropical leaves, eucalyptus sprigs, natural wood surface, dappled sunlight through foliage, earthy green palette, organic natural botanical aesthetic',
  'pastel-dream':'soft pastel pink background, fluffy cloud textures, dried flower petals, cotton candy blush and lilac tones, dreamy feminine kawaii styling',
  'golden-hour':'warm golden hour amber light, honey tones, sheer golden fabric, sun flare bokeh, terracotta surface, sunset warmth aesthetic, glowing backlit',
  'marble-luxe':'white carrara marble surface, gold leaf accents, crystal glass props, luxury high-end editorial, platinum ivory palette, premium product photography',
  'cafe-latte':'warm latte brown tones, rustic wooden table, burlap linen textures, vintage ceramic props, caramel mocha palette, cozy cottagecore ambient lighting',
  'clean-white':'pure white seamless studio background, soft diffused white box lighting, crisp clean shadows, professional commercial photography, bright airy minimal'
};

const GEMINI_MODEL = 'gemini-2.5-flash';
const GEMINI_URL = `https://generativelanguage.googleapis.com/v1beta/models/${GEMINI_MODEL}:generateContent`;

// ── API KEY ─────────────────────────────────────────────
function getKey(){return localStorage.getItem('gem_apikey')||'';}
function saveKey(){
  const k=document.getElementById('apiInput').value.trim();
  if(!k){alert('Masukkan API Key dulu!');return;}
  localStorage.setItem('gem_apikey',k);
  closeApiModal();
  updateApiBar();
}
function openApiModal(){
  document.getElementById('apiInput').value=getKey();
  document.getElementById('apiModal').classList.remove('hidden');
}
function closeApiModal(){document.getElementById('apiModal').classList.add('hidden');}
document.getElementById('apiCancel').onclick=closeApiModal;
document.getElementById('apiModal').addEventListener('click',e=>{if(e.target===document.getElementById('apiModal'))closeApiModal();});

function updateApiBar(){
  const k=getKey();
  const val=document.getElementById('apibarVal');
  const btn=document.querySelector('.apibar-btn');
  if(k){
    val.innerHTML=`<span class="apibar-connected">✓ Terhubung</span>&nbsp;<span style="color:#aaa;font-size:11px">${k.slice(0,8)}••••</span>`;
    btn.textContent='Ganti Key';
  } else {
    val.textContent='Belum diset — klik Pasang Key';
    btn.textContent='Pasang Key';
  }
}

window.addEventListener('DOMContentLoaded',()=>{
  const k=getKey();
  if(!k) openApiModal(); else closeApiModal();
  updateApiBar();
  renderHist();
  document.getElementById('afflink').addEventListener('input',()=>{
    const v=document.getElementById('afflink').value.trim();
    document.getElementById('afftag').style.display=v?'inline-flex':'none';
  });
});

// ── UPLOAD ─────────────────────────────────────────────
function dov(e){e.preventDefault();document.getElementById('uz').classList.add('dov')}
function dol(){document.getElementById('uz').classList.remove('dov')}
function ddr(e){e.preventDefault();dol();const f=e.dataTransfer.files[0];if(f&&f.type.startsWith('image/'))pf(f)}
function hf(e){const f=e.target.files[0];if(f)pf(f)}
function pf(f){
  if(f.size>10*1024*1024){alert('File terlalu besar. Maks 10MB.');return;}
  imgMime=f.type||'image/jpeg';
  const r=new FileReader();
  r.onload=e=>{
    b64=e.target.result.split(',')[1];
    document.getElementById('pimg').src=e.target.result;
    document.getElementById('pvw').style.display='block';
    document.getElementById('uz').style.display='none';
    document.getElementById('noImgNote').classList.add('hidden');
    document.getElementById('imgNote').classList.remove('hidden');
  };
  r.readAsDataURL(f);
}
function rmimg(){
  b64=null;
  document.getElementById('pvw').style.display='none';
  document.getElementById('uz').style.display='block';
  document.getElementById('noImgNote').classList.remove('hidden');
  document.getElementById('imgNote').classList.add('hidden');
  document.getElementById('fi').value='';
}
function selA(el,v){document.querySelectorAll('.ac').forEach(c=>c.classList.remove('sel'));el.classList.add('sel');aes=v}
function swt(t){
  document.getElementById('tfo').classList.toggle('hidden',t!=='foto');
  document.getElementById('tvi').classList.toggle('hidden',t!=='video');
  document.querySelectorAll('.tb').forEach((b,i)=>b.classList.toggle('on',(i===0&&t==='foto')||(i===1&&t==='video')));
}
function cp(id){
  navigator.clipboard.writeText(document.getElementById(id).innerText).then(()=>{
    document.querySelectorAll('.cb').forEach(b=>{
      if(b.getAttribute('onclick')===`cp('${id}')`){b.innerText='✓ Tersalin!';setTimeout(()=>b.innerText='📋 salin',2000);}
    });
  });
}
function showSkel(ids){
  ids.forEach(id=>{
    const e=document.getElementById(id);
    if(e)e.innerHTML='<div class="skel"></div><div class="skel w80"></div><div class="skel w60"></div>';
  });
}
function pf2(txt,key){
  for(const l of txt.split('\n')){if(l.trim().startsWith(key+':'))return l.replace(key+':','').trim();}
  const m=txt.match(new RegExp(key+':\\s*(.+)','i'));
  return m?m[1].trim():txt.trim();
}

// ── GEMINI API ─────────────────────────────────────────
async function gemini(prompt, sysTxt, imageData, imageMime){
  const key=getKey();
  if(!key)throw new Error('API Key Gemini belum diset. Klik "Pasang Key" di atas.');

  const parts=[];
  if(imageData){
    parts.push({inline_data:{mime_type:imageMime||'image/jpeg',data:imageData}});
  }
  parts.push({text: prompt});

  const body={
    contents:[{role:'user', parts}],
    generationConfig:{maxOutputTokens:1200,temperature:0.9},
  };
  if(sysTxt){
    body.system_instruction={parts:[{text:sysTxt}]};
  }

  const r=await fetch(`${GEMINI_URL}?key=${key}`,{
    method:'POST',
    headers:{'Content-Type':'application/json'},
    body:JSON.stringify(body)
  });
  const d=await r.json();
  if(d.error)throw new Error(`Gemini Error: ${d.error.message}`);
  return d.candidates?.[0]?.content?.parts?.[0]?.text||'';
}

// ── BUILD CONTEXT ──────────────────────────────────────
function buildCtx(){
  const produk=document.getElementById('produk').value.trim();
  if(!produk){alert('Isi nama produk dulu!');return null;}
  return {
    produk,
    kategori:document.getElementById('kategori').value,
    platform:document.getElementById('platform').value,
    benefit:document.getElementById('benefit').value,
    audiens:document.getElementById('audiens').value,
    harga:document.getElementById('harga').value,
    tone:document.getElementById('tone').value,
    afflink:document.getElementById('afflink').value.trim(),
    aes, ad:AP[aes],
    an:document.querySelector('.ac.sel .an')?.innerText||aes,
    b64, imgMime
  };
}
function ctxStr(ctx){
  return `Produk: ${ctx.produk}\nKategori: ${ctx.kategori}\nPlatform: ${ctx.platform}\nKeunggulan: ${ctx.benefit}\nAudiens: ${ctx.audiens}\nHarga: ${ctx.harga}\nTone: ${ctx.tone}`;
}

// ── MAIN GENERATE ──────────────────────────────────────
async function run(){
  const ctx=buildCtx();
  if(!ctx)return;
  lastCtx=ctx;

  const affStr=ctx.afflink?`\n\nLink Affiliate: ${ctx.afflink} — WAJIB sisipkan di akhir caption dengan teks "🔗 Link di bio / klik link ini: ${ctx.afflink}"`:'';
  document.getElementById('affbadge').style.display=ctx.afflink?'inline':'none';

  const btn=document.getElementById('bg');
  btn.disabled=true;btn.innerHTML='⏳ Sedang generate semua konten...';
  document.getElementById('res').classList.remove('hidden');
  showSkel(['ip1','ip2','ip3','f1','f2','f3','v1','v2','v3','hk','cap','htg']);
  setRegenBtns(true);

  const cs=ctxStr(ctx);
  const sysProd='Kamu adalah photographer dan art director produk profesional. Buat prompt FlowAI/Midjourney sangat detail dan estetik ala Pinterest. Output HANYA format yang diminta, tanpa penjelasan tambahan.';

  // Prompt image: pakai foto jika ada
  const imgPromptTxt = ctx.b64
    ? `Foto produk untuk konten afiliasi.\n\n${cs}\nAesthetic: ${ctx.an} — ${ctx.ad}\n\nTugas:\n1. Analisis produk dari foto\n2. Buat 3 prompt gambar estetik Pinterest sesuai produk asli\n\nFormat TEPAT:\nANALISIS: [deskripsi singkat warna, bentuk, packaging dari foto]\nIMGP1: [prompt hero shot bahasa Inggris — deskripsikan produk dari foto secara spesifik, ${ctx.ad}, Pinterest aesthetic, professional product photography, 8K, --ar 4:5]\nIMGP2: [prompt close-up bahasa Inggris — detail packaging tekstur dari foto, ${ctx.ad}, macro photography, studio light, --ar 1:1]\nIMGP3: [prompt flatlay bahasa Inggris — produk dari foto, ${ctx.ad}, flatlay top view, Pinterest editorial, --ar 4:5]`
    : `Buat 3 prompt gambar estetik Pinterest untuk produk afiliasi:\n\n${cs}\nAesthetic: ${ctx.an} — ${ctx.ad}\n\nFormat TEPAT:\nIMGP1: [prompt hero shot — ${ctx.produk}, ${ctx.ad}, Pinterest aesthetic, professional product photography, natural light, --ar 4:5]\nIMGP2: [prompt close-up detail — ${ctx.produk}, ${ctx.ad}, macro photography, studio lighting, sharp focus, --ar 1:1]\nIMGP3: [prompt flatlay lifestyle — ${ctx.produk}, ${ctx.ad}, flatlay top view, Pinterest editorial styling, --ar 4:5]`;

  if(ctx.b64){
    document.getElementById('anabox').classList.remove('hidden');
    document.getElementById('ana').innerHTML='<div class="skel"></div>';
  }

  try{
    const [ir,fr,vr,kr]=await Promise.all([
      gemini(imgPromptTxt, sysProd, ctx.b64, ctx.imgMime),
      gemini(`Buat 3 prompt foto untuk video afiliasi:\n\n${cs}\n\nFormat HANYA:\nSCENE1: [hook visual emosional, manusia, sinematik, detail kamera lighting bahasa Inggris]\nSCENE2: [close-up produk menggoda, tekstur, studio lighting bahasa Inggris]\nSCENE3: [hasil/ekspresi puas, lifestyle shot bahasa Inggris]`),
      gemini(`Buat 3 prompt video:\n\n${cs}\n\nFormat HANYA:\nVID1: [3-5 dtk opening hook, camera movement, action, mood bahasa Inggris]\nVID2: [5-8 dtk demo produk, close-up, smooth motion bahasa Inggris]\nVID3: [3-5 dtk closing CTA, energetic, satisfying bahasa Inggris]`),
      gemini(`Buat hook, caption, hashtag afiliasi:\n\n${cs}${affStr}\n\nFormat HANYA:\nHOOK1: [hook maks 10 kata, sangat menarik perhatian]\nHOOK2: [pakai angka atau pertanyaan]\nHOOK3: [POV atau relatable]\nCAPTION: [5-7 kalimat Bahasa Indonesia: hook, masalah, solusi, benefit, social proof, CTA comment MINTA. Emoji secukupnya. Jika ada link affiliate sisipkan di akhir.]\nHASHTAG: [20 hashtag relevan campuran Indonesia-Inggris]`)
    ]);

    if(ctx.b64) document.getElementById('ana').innerText=pf2(ir,'ANALISIS');
    document.getElementById('ip1').innerText=pf2(ir,'IMGP1');
    document.getElementById('ip2').innerText=pf2(ir,'IMGP2');
    document.getElementById('ip3').innerText=pf2(ir,'IMGP3');
    document.getElementById('f1').innerText=pf2(fr,'SCENE1');
    document.getElementById('f2').innerText=pf2(fr,'SCENE2');
    document.getElementById('f3').innerText=pf2(fr,'SCENE3');
    document.getElementById('v1').innerText=pf2(vr,'VID1');
    document.getElementById('v2').innerText=pf2(vr,'VID2');
    document.getElementById('v3').innerText=pf2(vr,'VID3');
    document.getElementById('hk').innerText='1. '+pf2(kr,'HOOK1')+'\n2. '+pf2(kr,'HOOK2')+'\n3. '+pf2(kr,'HOOK3');
    document.getElementById('cap').innerText=pf2(kr,'CAPTION');
    document.getElementById('htg').innerText=pf2(kr,'HASHTAG');

    saveHist(ctx);
  }catch(e){
    alert('Error: '+e.message);
    ['ip1','ip2','ip3','f1','f2','f3','v1','v2','v3','hk','cap','htg'].forEach(id=>{
      const el=document.getElementById(id);if(el)el.innerText='Error. Coba lagi.';
    });
  }
  btn.disabled=false;btn.innerHTML='✨ Generate Semua Konten + Prompt Gambar Estetik';
  setRegenBtns(false);
}

// ── REGENERATE PER SECTION ─────────────────────────────
function setRegenBtns(disabled){
  ['rb-img','rb-foto','rb-video','rb-cap'].forEach(id=>{
    const b=document.getElementById(id);if(b)b.disabled=disabled;
  });
}

async function regen(section){
  if(!lastCtx){alert('Generate dulu ya!');return;}
  const ctx=lastCtx;
  const cs=ctxStr(ctx);
  const affStr=ctx.afflink?`\n\nLink Affiliate: ${ctx.afflink} — WAJIB sisipkan di akhir caption dengan teks "🔗 klik link ini: ${ctx.afflink}"`:'';
  const btnId='rb-'+{img:'img',foto:'foto',video:'video',caption:'cap'}[section];
  const btn=document.getElementById(btnId);
  if(btn){btn.disabled=true;btn.innerText='⏳';}

  try{
    if(section==='img'){
      showSkel(['ip1','ip2','ip3']);
      const prompt=ctx.b64
        ?`Foto produk.\n\n${cs}\nAesthetic: ${ctx.an} — ${ctx.ad}\n\nBuat 3 prompt gambar VARIASI BARU:\nIMGP1: [...]\nIMGP2: [...]\nIMGP3: [...]`
        :`Buat 3 prompt gambar VARIASI BARU:\n\n${cs}\nAesthetic: ${ctx.an} — ${ctx.ad}\n\nFormat:\nIMGP1: [...]\nIMGP2: [...]\nIMGP3: [...]`;
      const ir=await gemini(prompt,'Kamu adalah art director. Buat prompt detail estetik Pinterest. Output HANYA format yang diminta.',ctx.b64,ctx.imgMime);
      document.getElementById('ip1').innerText=pf2(ir,'IMGP1');
      document.getElementById('ip2').innerText=pf2(ir,'IMGP2');
      document.getElementById('ip3').innerText=pf2(ir,'IMGP3');
    } else if(section==='foto'){
      showSkel(['f1','f2','f3']);
      const fr=await gemini(`Buat 3 prompt foto VARIASI BARU:\n\n${cs}\n\nFormat:\nSCENE1: [...]\nSCENE2: [...]\nSCENE3: [...]`);
      document.getElementById('f1').innerText=pf2(fr,'SCENE1');
      document.getElementById('f2').innerText=pf2(fr,'SCENE2');
      document.getElementById('f3').innerText=pf2(fr,'SCENE3');
    } else if(section==='video'){
      showSkel(['v1','v2','v3']);
      const vr=await gemini(`Buat 3 prompt video VARIASI BARU:\n\n${cs}\n\nFormat:\nVID1: [...]\nVID2: [...]\nVID3: [...]`);
      document.getElementById('v1').innerText=pf2(vr,'VID1');
      document.getElementById('v2').innerText=pf2(vr,'VID2');
      document.getElementById('v3').innerText=pf2(vr,'VID3');
    } else if(section==='caption'){
      showSkel(['hk','cap','htg']);
      const kr=await gemini(`Buat hook, caption, hashtag VARIASI BARU:\n\n${cs}${affStr}\n\nFormat:\nHOOK1: [...]\nHOOK2: [...]\nHOOK3: [...]\nCAPTION: [...]\nHASHTAG: [...]`);
      document.getElementById('hk').innerText='1. '+pf2(kr,'HOOK1')+'\n2. '+pf2(kr,'HOOK2')+'\n3. '+pf2(kr,'HOOK3');
      document.getElementById('cap').innerText=pf2(kr,'CAPTION');
      document.getElementById('htg').innerText=pf2(kr,'HASHTAG');
    }
  }catch(e){alert('Error regenerate: '+e.message);}
  if(btn){btn.disabled=false;btn.innerText='↻ Ulang';}
}

// ── EXPORT TXT ─────────────────────────────────────────
function exportTxt(){
  const get=id=>document.getElementById(id)?.innerText||'-';
  const now=new Date().toLocaleString('id-ID');
  const txt=`AI AFFILIATE VIDEO GENERATOR — HASIL GENERATE
Generated: ${now}
${'='.repeat(50)}

PRODUK    : ${lastCtx?.produk||'-'}
AESTHETIC : ${lastCtx?.an||'-'}
PLATFORM  : ${lastCtx?.platform||'-'}
LINK AFF  : ${lastCtx?.afflink||'-'}

${'─'.repeat(50)}
PROMPT GAMBAR ESTETIK PINTEREST
${'─'.repeat(50)}

[Hero Shot]
${get('ip1')}

[Detail / Close-up]
${get('ip2')}

[Lifestyle / Flatlay]
${get('ip3')}

${'─'.repeat(50)}
PROMPT FOTO SCENE
${'─'.repeat(50)}

[Scene 1 — Hook Visual]
${get('f1')}

[Scene 2 — Product Close-up]
${get('f2')}

[Scene 3 — Result / Testimonial]
${get('f3')}

${'─'.repeat(50)}
PROMPT VIDEO
${'─'.repeat(50)}

[Opening Hook 3-5 dtk]
${get('v1')}

[Demo Penggunaan 5-8 dtk]
${get('v2')}

[CTA Closing 3-5 dtk]
${get('v3')}

${'─'.repeat(50)}
HOOK, CAPTION & HASHTAG
${'─'.repeat(50)}

[Hook Pilihan]
${get('hk')}

[Caption Lengkap]
${get('cap')}

[Hashtag]
${get('htg')}

${'='.repeat(50)}
Generated by AI Affiliate Video Generator (Gemini API)`.trim();

  const blob=new Blob([txt],{type:'text/plain'});
  const url=URL.createObjectURL(blob);
  const a=document.createElement('a');
  const name=(lastCtx?.produk||'hasil').replace(/[^a-zA-Z0-9]/g,'_').toLowerCase();
  a.href=url;a.download=`affiliate_${name}_${Date.now()}.txt`;
  document.body.appendChild(a);a.click();
  document.body.removeChild(a);URL.revokeObjectURL(url);
}

// ── HISTORY ────────────────────────────────────────────
function getHist(){try{return JSON.parse(localStorage.getItem('aff_hist2')||'[]');}catch{return [];}}
function saveHist(ctx){
  const hist=getHist();
  hist.unshift({
    id:Date.now(), ts:new Date().toISOString(),
    produk:ctx.produk, kategori:ctx.kategori, platform:ctx.platform,
    aes:ctx.aes, an:ctx.an, afflink:ctx.afflink,
    results:{
      ip1:document.getElementById('ip1').innerText,ip2:document.getElementById('ip2').innerText,ip3:document.getElementById('ip3').innerText,
      f1:document.getElementById('f1').innerText,f2:document.getElementById('f2').innerText,f3:document.getElementById('f3').innerText,
      v1:document.getElementById('v1').innerText,v2:document.getElementById('v2').innerText,v3:document.getElementById('v3').innerText,
      hk:document.getElementById('hk').innerText,cap:document.getElementById('cap').innerText,htg:document.getElementById('htg').innerText
    }
  });
  if(hist.length>20)hist.pop();
  localStorage.setItem('aff_hist2',JSON.stringify(hist));
  renderHist();
}
function loadHist(id){
  const entry=getHist().find(h=>h.id===id);
  if(!entry)return;
  document.getElementById('res').classList.remove('hidden');
  document.getElementById('anabox').classList.add('hidden');
  Object.entries(entry.results).forEach(([k,v])=>{const el=document.getElementById(k);if(el)el.innerText=v;});
  document.getElementById('affbadge').style.display=entry.afflink?'inline':'none';
  lastCtx={produk:entry.produk,kategori:entry.kategori,platform:entry.platform,aes:entry.aes,an:entry.an,afflink:entry.afflink||''};
  window.scrollTo({top:0,behavior:'smooth'});
}
function clearHist(){
  if(!confirm('Hapus semua riwayat?'))return;
  localStorage.removeItem('aff_hist2');renderHist();
}
const PLAT={tiktok:'TikTok',reels:'Reels',facebook:'FB',youtube:'YT Shorts'};
function renderHist(){
  const hist=getHist();
  const el=document.getElementById('histList');
  if(!hist.length){el.innerHTML='<div class="hist-empty">Belum ada riwayat. Mulai generate produk pertamamu! ✨</div>';return;}
  el.innerHTML=hist.map(h=>{
    const d=new Date(h.ts);
    const ds=d.toLocaleDateString('id-ID',{day:'numeric',month:'short',year:'numeric'})+' '+d.toLocaleTimeString('id-ID',{hour:'2-digit',minute:'2-digit'});
    return `<div class="hist-item" onclick="loadHist(${h.id})">
      <div class="hist-prod">${h.produk}</div>
      <div class="hist-meta">${ds}</div>
      <div class="hist-badges">
        <span class="hist-badge">${h.an||h.aes}</span>
        <span class="hist-badge">${PLAT[h.platform]||h.platform}</span>
        ${h.afflink?'<span class="hist-badge" style="background:#dcfce7;color:#15803d">🔗 Affiliate</span>':''}
      </div>
      <div class="hist-load">Tap untuk lihat hasil →</div>
    </div>`;
  }).join('');
}
function rst(){
  document.getElementById('res').classList.add('hidden');
  ['produk','benefit','audiens','harga','afflink'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('anabox').classList.add('hidden');
  document.getElementById('afftag').style.display='none';
  document.getElementById('affbadge').style.display='none';
  rmimg(); lastCtx=null;
  window.scrollTo({top:0,behavior:'smooth'});
}
</script>
</body>
</html>
