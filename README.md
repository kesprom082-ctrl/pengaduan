senyum dong sayang Biar cepat sehat
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#075db5">
  <title>Form Pengaduan Layanan | RSUD Naibonat</title>
  <style>
    :root{--blue:#075db5;--blue2:#087bd3;--navy:#103c70;--pale:#eef7ff;--line:#d5e5f5;--text:#17324f;--muted:#60758c;--white:#fff}
    *{box-sizing:border-box}
    body{margin:0;font-family:Arial,Helvetica,sans-serif;color:var(--text);background:linear-gradient(135deg,#eaf5ff,#f8fbff 55%,#e6f3ff);min-height:100vh}
    .topbar{background:linear-gradient(110deg,#063d7c,#087bd3);color:#fff;padding:22px 18px;position:relative;overflow:hidden}
    .topbar:after{content:"";position:absolute;width:320px;height:320px;border:45px solid #ffffff16;border-radius:50%;right:-70px;top:-190px}
    .head{max-width:1120px;margin:auto;display:flex;align-items:center;gap:16px;position:relative;z-index:1}
    .logo{width:68px;height:68px;border-radius:50%;background:#fff;color:var(--blue);display:grid;place-items:center;font-size:28px;font-weight:800;border:3px solid #d6edff;flex-shrink:0}
    .head h1{margin:0;font-size:clamp(21px,3vw,31px);letter-spacing:.3px}
    .head p{margin:7px 0 0;color:#e1f1ff;font-size:14px}
    .wrap{max-width:1120px;margin:28px auto;padding:0 16px 28px;display:grid;grid-template-columns:minmax(0,1.8fr) minmax(250px,.8fr);gap:20px}
    .card{background:#fff;border:1px solid #e1edf8;border-radius:18px;box-shadow:0 12px 32px #144a7710;padding:clamp(20px,3vw,30px)}
    .intro{display:flex;gap:14px;align-items:flex-start;margin-bottom:24px}
    .intro-icon{width:54px;height:54px;display:grid;place-items:center;border-radius:50%;background:#e4f2ff;color:var(--blue);font-size:27px;flex-shrink:0}
    h2{font-size:clamp(22px,3vw,28px);margin:2px 0 8px;color:#103b7a}
    .intro p{margin:0;line-height:1.6;color:var(--muted);font-size:14px}
    .grid{display:grid;grid-template-columns:1fr 1fr;gap:18px 20px}
    .field{min-width:0}
    label{display:block;font-weight:700;font-size:14px;margin-bottom:8px;color:#154678}
    .req{color:#d12c36}
    input,select,textarea{width:100%;font:inherit;font-size:14px;color:#193956;border:1px solid #cbdced;border-radius:9px;padding:13px 14px;background:#fff;outline:none;transition:border .2s,box-shadow .2s}
    input,select{min-height:47px}
    textarea{resize:vertical;min-height:118px;line-height:1.5}
    input:focus,select:focus,textarea:focus{border-color:#1683db;box-shadow:0 0 0 3px #1683db1c}
    input::placeholder,textarea::placeholder{color:#8b9db1}
    .full{grid-column:1/-1}
    .hidden{display:none!important}
    .hint{font-size:12px;color:var(--muted);margin:6px 0 0}
    .submit{width:100%;border:0;border-radius:9px;background:linear-gradient(100deg,#0664bd,#0783d9);color:#fff;padding:15px 18px;font-size:16px;font-weight:700;cursor:pointer;box-shadow:0 7px 16px #087bd326;transition:transform .15s,opacity .15s}
    .submit:hover{transform:translateY(-1px)}
    .submit:disabled{opacity:.65;cursor:wait;transform:none}
    .status{display:none;margin-top:14px;padding:12px 14px;border-radius:9px;font-size:14px;line-height:1.5}
    .status.show{display:block}.status.ok{background:#e9f8ef;color:#17633a;border:1px solid #bfe7cc}.status.err{background:#fff0f0;color:#a51d2d;border:1px solid #f0c5c9}
    .side h3{margin:3px 0 18px;color:#103b7a;font-size:21px}
    .info{display:flex;gap:12px;margin:18px 0;line-height:1.55;font-size:14px}
    .info .ico{width:36px;height:36px;border-radius:50%;background:#e6f3ff;color:var(--blue);display:grid;place-items:center;flex-shrink:0;font-size:18px}
    .side .quote{border-top:1px solid var(--line);margin-top:24px;padding-top:20px;color:#075db5;font-style:italic;line-height:1.65}
    .privacy{font-size:12px;color:var(--muted);line-height:1.6;background:#f4f9ff;padding:12px;border-radius:9px;margin-top:20px}
    footer{text-align:center;padding:18px;color:#fff;background:#124c87;font-size:12px}
    @media(max-width:800px){.wrap{grid-template-columns:1fr;margin-top:18px}.side{order:2}}
    @media(max-width:560px){.grid{grid-template-columns:1fr;gap:16px}.full{grid-column:auto}.head{align-items:flex-start}.logo{width:54px;height:54px;font-size:23px}.card{padding:19px}.intro-icon{width:44px;height:44px;font-size:22px}}
  </style>
</head>
<body>
  <header class="topbar">
    <div class="head">
      <div class="logo" aria-label="Logo rumah sakit">✚</div>
      <div>
        <h1>RSUD NAIBONAT</h1>
        <p>Melayani Dengan Hati · Form Pengaduan Layanan</p>
      </div>
    </div>
  </header>

  <main class="wrap">
    <section class="card">
      <div class="intro">
        <div class="intro-icon">✉</div>
        <div>
          <h2>Sampaikan Pengaduan Anda</h2>
          <p>Silakan isi formulir dengan data yang benar dan lengkap. Masukan Anda membantu kami meningkatkan mutu pelayanan rumah sakit.</p>
        </div>
      </div>

      <form id="complaintForm">
        <div class="grid">
          <div class="field">
            <label for="email">Email <span class="req">*</span></label>
            <input id="email" name="email" type="email" placeholder="nama@email.com" autocomplete="email" required>
          </div>
          <div class="field">
            <label for="nama">Nama Pelapor <span class="req">*</span></label>
            <input id="nama" name="nama" type="text" placeholder="Nama lengkap pelapor" autocomplete="name" required maxlength="120">
          </div>
          <div class="field">
            <label for="identitas">No. KTP / RM <span class="req">*</span></label>
            <input id="identitas" name="identitas" type="text" placeholder="Nomor KTP atau nomor rekam medis" required maxlength="40">
            <p class="hint">Isi nomor KTP atau nomor RM yang sesuai.</p>
          </div>
          <div class="field">
            <label for="jenisKunjungan">Jenis Kunjungan <span class="req">*</span></label>
            <select id="jenisKunjungan" name="jenisKunjungan" required>
              <option value="">Pilih jenis kunjungan</option>
              <option value="Rawat Jalan">Rawat Jalan</option>
              <option value="Rawat Inap">Rawat Inap</option>
            </select>
          </div>
          <div class="field hidden" id="poliField">
            <label for="namaPoli">Nama Poli <span class="req">*</span></label>
            <select id="namaPoli" name="namaPoli">
              <option value="">Pilih nama poli</option>
              <option>Poli Umum</option><option>Poli Penyakit Dalam</option>
              <option>Poli Anak</option><option>Poli Kebidanan dan Kandungan</option>
              <option>Poli Bedah</option><option>Poli Gigi dan Mulut</option>
              <option>Poli Mata</option><option>Poli Saraf</option>
              <option>Poli THT</option><option>Poli Kulit dan Kelamin</option>
              <option>Poli lainnya</option>
            </select>
            <p class="hint">Daftar poli dapat disesuaikan dengan layanan rumah sakit.</p>
          </div>
          <div class="field hidden" id="ruanganField">
            <label for="namaRuangan">Nama Ruangan <span class="req">*</span></label>
            <select id="namaRuangan" name="namaRuangan">
              <option value="">Pilih nama ruangan</option>
              <option>Ruang Cendana</option><option>Ruang Lontar</option>
              <option>Ruang Flamboyan</option><option>Ruang Azalea</option>
              <option>Ruang Gamalin</option><option>Ruang Angsana</option>
              <option>Ruang HCU</option><option>Ruang Nicu</option>
              <option>Ruang ICU</option><option>Ruang Perawatan Anak</option>
              <option>Ruang Picu</option><option>Ruang lainnya</option>
            </select>
            <p class="hint">Silakan sesuaikan pilihan dengan nama ruangan yang tersedia.</p>
          </div>
          <div class="field full">
            <label for="pengaduan">Isi Pengaduan <span class="req">*</span></label>
            <textarea id="pengaduan" name="pengaduan" placeholder="Ceritakan pengaduan Anda secara jelas..." required maxlength="3000"></textarea>
            <p class="hint"><span id="complaintCount">0</span>/3000 karakter</p>
          </div>
          <div class="field full">
            <label for="saran">Saran <span class="req">*</span></label>
            <textarea id="saran" name="saran" placeholder="Tuliskan saran untuk perbaikan pelayanan..." required maxlength="1500"></textarea>
            <p class="hint"><span id="suggestionCount">0</span>/1500 karakter</p>
          </div>
          <div class="field full">
            <button class="submit" id="submitBtn" type="submit">➤ &nbsp; Kirim Pengaduan</button>
            <div id="status" class="status" role="status" aria-live="polite"></div>
          </div>
        </div>
      </form>
      <div class="privacy">🔒 <strong>Perlindungan data:</strong> Informasi yang Anda kirim digunakan untuk tindak lanjut pengaduan dan peningkatan pelayanan. Hindari menuliskan informasi medis sensitif yang tidak diperlukan.</div>
    </section>

    <aside class="card side">
      <h3>Informasi Penting</h3>
      <div class="info"><div class="ico">✓</div><div>Pengaduan Anda akan diteruskan kepada petugas terkait untuk ditindaklanjuti.</div></div>
      <div class="info"><div class="ico">🔐</div><div>Pastikan email dan data yang dimasukkan benar agar petugas dapat melakukan tindak lanjut bila diperlukan.</div></div>
      <div class="info"><div class="ico">ⓘ</div><div>Untuk keadaan darurat, segera hubungi petugas rumah sakit secara langsung. Formulir ini bukan layanan darurat.</div></div>
      <div class="quote">“Terima kasih atas partisipasi Anda untuk membantu kami memberikan pelayanan yang lebih baik.”</div>
    </aside>
  </main>

  <footer>© <span id="year"></span> RSUD Naibonat · Form Pengaduan Layanan</footer>

  <script>
    // GANTI nilai ini dengan URL Web App dari Google Apps Script setelah di-deploy.
    const GOOGLE_SCRIPT_URL = "https://script.google.com/macros/s/AKfycbzX-zN36m9E3wtCDQnY1EjXeVn_knJ43wuRYFVZ8xqVOyjJUScMMIj5oH1VtDTpvac/exec";

    const form = document.getElementById("complaintForm");
    const typeSelect = document.getElementById("jenisKunjungan");
    const poliField = document.getElementById("poliField");
    const roomField = document.getElementById("ruanganField");
    const poliSelect = document.getElementById("namaPoli");
    const roomSelect = document.getElementById("namaRuangan");
    const statusBox = document.getElementById("status");
    const submitBtn = document.getElementById("submitBtn");

    document.getElementById("year").textContent = new Date().getFullYear();

    typeSelect.addEventListener("change", () => {
      const rawatJalan = typeSelect.value === "Rawat Jalan";
      const rawatInap = typeSelect.value === "Rawat Inap";
      poliField.classList.toggle("hidden", !rawatJalan);
      roomField.classList.toggle("hidden", !rawatInap);
      poliSelect.required = rawatJalan;
      roomSelect.required = rawatInap;
      if (!rawatJalan) poliSelect.value = "";
      if (!rawatInap) roomSelect.value = "";
    });

    document.getElementById("pengaduan").addEventListener("input", e => {
      document.getElementById("complaintCount").textContent = e.target.value.length;
    });
    document.getElementById("saran").addEventListener("input", e => {
      document.getElementById("suggestionCount").textContent = e.target.value.length;
    });

    function showStatus(message, type) {
      statusBox.textContent = message;
      statusBox.className = "status show " + type;
    }

    form.addEventListener("submit", async (event) => {
      event.preventDefault();
      if (!form.reportValidity()) return;

      if (!GOOGLE_SCRIPT_URL || !GOOGLE_SCRIPT_URL.startsWith("https://script.google.com/macros/s/") || !GOOGLE_SCRIPT_URL.endsWith("/exec")) {
        showStatus("URL Google Apps Script tidak valid. Periksa GOOGLE_SCRIPT_URL pada file index.html.", "err");
        return;
      }

      const data = {
        email: form.email.value.trim(),
        nama: form.nama.value.trim(),
        identitas: form.identitas.value.trim(),
        jenisKunjungan: form.jenisKunjungan.value,
        namaPoli: form.jenisKunjungan.value === "Rawat Jalan" ? form.namaPoli.value : "",
        namaRuangan: form.jenisKunjungan.value === "Rawat Inap" ? form.namaRuangan.value : "",
        pengaduan: form.pengaduan.value.trim(),
        saran: form.saran.value.trim()
      };

      submitBtn.disabled = true;
      submitBtn.textContent = "Mengirim...";
      statusBox.className = "status";
      try {
        // mode no-cors membuat respons tidak dapat dibaca browser; Apps Script menerima kiriman,
        // tetapi browser tidak bisa memverifikasi balasan server secara langsung.
        await fetch(GOOGLE_SCRIPT_URL, {
          method: "POST",
          mode: "no-cors",
          headers: { "Content-Type": "text/plain;charset=utf-8" },
          body: JSON.stringify(data)
        });
        showStatus("Pengaduan telah dikirim. Jika ingin memastikan, periksa Google Sheets yang terhubung.", "ok");
        form.reset();
        poliField.classList.add("hidden");
        roomField.classList.add("hidden");
        poliSelect.required = false;
        roomSelect.required = false;
        document.getElementById("complaintCount").textContent = "0";
        document.getElementById("suggestionCount").textContent = "0";
      } catch (error) {
        showStatus("Pengiriman gagal karena masalah jaringan. Periksa koneksi internet dan coba lagi.", "err");
      } finally {
        submitBtn.disabled = false;
        submitBtn.innerHTML = "➤ &nbsp; Kirim Pengaduan";
      }
    });
  </script>
</body>
</html>
