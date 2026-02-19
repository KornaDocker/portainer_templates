
📖 [View detailed folder documentation](details.md)

---

## 📅 Changelog Calendar

<style>
.changelog-container {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  max-width: 1200px;
  margin: 0 auto;
}
.year-section {
  margin-bottom: 40px;
  border-left: 4px solid #3498db;
  padding-left: 20px;
}
.year-header {
  font-size: 2em;
  color: #2c3e50;
  margin-bottom: 20px;
  font-weight: 700;
}
.month-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}
.month-card {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 12px;
  padding: 20px;
  color: white;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}
.month-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.2);
}
.month-card.feb-2026 { background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); }
.month-card.dec-2025 { background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); }
.month-card.oct-2025 { background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%); }
.month-card.aug-2025 { background: linear-gradient(135deg, #fa709a 0%, #fee140 100%); }
.month-card.jun-2025 { background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%); color: #333; }
.month-card.may-2025 { background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%); color: #333; }
.month-card.mar-2025 { background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%); color: #333; }
.month-card.feb-2025 { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
.month-card.jan-2025 { background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); }
.month-card.nov-2024 { background: linear-gradient(135deg, #fc5c7d 0%, #6a82fb 100%); }
.month-card.oct-2024 { background: linear-gradient(135deg, #f6d365 0%, #fda085 100%); color: #333; }
.month-card.sep-2024 { background: linear-gradient(135deg, #84fab0 0%, #8fd3f4 100%); color: #333; }
.month-card.aug-2024 { background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 100%); color: #333; }
.month-card.jul-2024 { background: linear-gradient(135deg, #fbc2eb 0%, #a6c1ee 100%); color: #333; }
.month-card.jun-2024 { background: linear-gradient(135deg, #fdcbf1 0%, #e6dee9 100%); color: #333; }
.month-card.may-2024 { background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%); color: #333; }
.month-card.apr-2024 { background: linear-gradient(135deg, #d299c2 0%, #fef9d7 100%); color: #333; }
.month-card.mar-2024 { background: linear-gradient(135deg, #89f7fe 0%, #66a6ff 100%); }
.month-card.feb-2024 { background: linear-gradient(135deg, #fddb92 0%, #d1fdff 100%); color: #333; }
.month-card.jan-2024 { background: linear-gradient(135deg, #a1ffce 0%, #faffd1 100%); color: #333; }
.month-card.dec-2023 { background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%); color: #333; }
.month-card.nov-2023 { background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%); color: #333; }
.month-card.oct-2023 { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
.month-card.sep-2023 { background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); }
.month-card.aug-2023 { background: linear-gradient(135deg, #fc5c7d 0%, #6a82fb 100%); }
.month-card.jul-2023 { background: linear-gradient(135deg, #f6d365 0%, #fda085 100%); color: #333; }
.month-card.jun-2023 { background: linear-gradient(135deg, #84fab0 0%, #8fd3f4 100%); color: #333; }
.month-card.may-2023 { background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 100%); color: #333; }
.month-card.apr-2023 { background: linear-gradient(135deg, #fbc2eb 0%, #a6c1ee 100%); color: #333; }
.month-card.mar-2023 { background: linear-gradient(135deg, #fdcbf1 0%, #e6dee9 100%); color: #333; }
.month-card.feb-2023 { background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%); color: #333; }
.month-card.jan-2023 { background: linear-gradient(135deg, #d299c2 0%, #fef9d7 100%); color: #333; }
.month-card.dec-2022 { background: linear-gradient(135deg, #89f7fe 0%, #66a6ff 100%); }
.month-card.nov-2022 { background: linear-gradient(135deg, #fddb92 0%, #d1fdff 100%); color: #333; }
.month-card.oct-2022 { background: linear-gradient(135deg, #a1ffce 0%, #faffd1 100%); color: #333; }
.month-card.sep-2022 { background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%); color: #333; }
.month-card.aug-2022 { background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%); color: #333; }
.month-card.jul-2022 { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
.month-card.jun-2022 { background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); }
.month-card.may-2022 { background: linear-gradient(135deg, #fc5c7d 0%, #6a82fb 100%); }
.month-card.mar-2022 { background: linear-gradient(135deg, #f6d365 0%, #fda085 100%); color: #333; }
.month-card.feb-2022 { background: linear-gradient(135deg, #84fab0 0%, #8fd3f4 100%); color: #333; }
.month-card.jan-2022 { background: linear-gradient(135deg, #a1c4fd 0%, #c2e9fb 100%); color: #333; }
.month-card.dec-2021 { background: linear-gradient(135deg, #fbc2eb 0%, #a6c1ee 100%); color: #333; }
.month-card.nov-2021 { background: linear-gradient(135deg, #fdcbf1 0%, #e6dee9 100%); color: #333; }

.month-title {
  font-size: 1.5em;
  font-weight: 700;
  margin-bottom: 15px;
  border-bottom: 2px solid rgba(255,255,255,0.3);
  padding-bottom: 10px;
}
.service-list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.service-item {
  background: rgba(255,255,255,0.2);
  margin: 8px 0;
  padding: 8px 12px;
  border-radius: 6px;
  font-size: 0.95em;
  backdrop-filter: blur(10px);
  border-left: 3px solid rgba(255,255,255,0.5);
  transition: all 0.2s;
}
.service-item:hover {
  background: rgba(255,255,255,0.3);
  transform: translateX(5px);
}
.service-date {
  font-size: 0.8em;
  opacity: 0.9;
  font-weight: 600;
  margin-right: 8px;
}
.badge-new {
  background: #ff4757;
  color: white;
  font-size: 0.7em;
  padding: 2px 6px;
  border-radius: 10px;
  margin-left: 5px;
  font-weight: bold;
}
.stats-bar {
  background: #f8f9fa;
  padding: 15px;
  border-radius: 8px;
  margin-bottom: 30px;
  text-align: center;
  border: 1px solid #e9ecef;
}
.stats-item {
  display: inline-block;
  margin: 0 20px;
  font-weight: 600;
  color: #495057;
}
</style>

<div class="changelog-container">

<div class="stats-bar">
  <span class="stats-item">📦 <strong>200+</strong> Services</span>
  <span class="stats-item">📅 <strong>5+</strong> Years Active</span>
  <span class="stats-item">🔄 <strong>Type 3</strong> Stacks</span>
  <span class="stats-item">⭐ <strong>Community</strong> Driven</span>
</div>

<!-- 2026 -->
<div class="year-section">
  <div class="year-header">2026 🚀</div>
  <div class="month-grid">
    
    <div class="month-card feb-2026">
      <div class="month-title">February 2026 <span class="badge-new">LATEST</span></div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">13/02</span>Crowdsec Web UI</li>
        <li class="service-item"><span class="service-date">09/02</span>Solidtime</li>
        <li class="service-item"><span class="service-date">09/02</span>TRIP</li>
        <li class="service-item"><span class="service-date">09/02</span>Checkle</li>
        <li class="service-item"><span class="service-date">09/02</span>Lidify-FULL</li>
        <li class="service-item"><span class="service-date">09/02</span>Lidify</li>
        <li class="service-item"><span class="service-date">09/02</span>Aurral</li>
        <li class="service-item"><span class="service-date">06/02</span>PriceGhost</li>
        <li class="service-item"><span class="service-date">06/02</span>GoCostWeb</li>
      </ul>
    </div>

  </div>
</div>

<!-- 2025 -->
<div class="year-section">
  <div class="year-header">2025</div>
  <div class="month-grid">
    
    <div class="month-card dec-2025">
      <div class="month-title">December</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">31/12</span>Lunalytics</li>
        <li class="service-item"><span class="service-date">18/12</span>DockerComposeMaker</li>
        <li class="service-item"><span class="service-date">18/12</span>Arcane</li>
      </ul>
    </div>

    <div class="month-card oct-2025">
      <div class="month-title">October</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">17/10</span>Netbox <em>(Update)</em></li>
      </ul>
    </div>

    <div class="month-card aug-2025">
      <div class="month-title">August</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">27/08</span>Marreta</li>
      </ul>
    </div>

    <div class="month-card jun-2025">
      <div class="month-title">June</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">02/06</span>Kestra</li>
      </ul>
    </div>

    <div class="month-card may-2025">
      <div class="month-title">May</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">16/05</span>Loggifly</li>
        <li class="service-item"><span class="service-date">12/05</span>Dawarich</li>
      </ul>
    </div>

    <div class="month-card mar-2025">
      <div class="month-title">March</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">16/03</span>Checkmate</li>
        <li class="service-item"><span class="service-date">06/03</span>Nutify</li>
      </ul>
    </div>

    <div class="month-card feb-2025">
      <div class="month-title">February</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">19/02</span>RomM</li>
        <li class="service-item"><span class="service-date">07/02</span>Kasm Workspaces</li>
      </ul>
    </div>

    <div class="month-card jan-2025">
      <div class="month-title">January</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">09/01</span>Blinko</li>
      </ul>
    </div>

  </div>
</div>

<!-- 2024 -->
<div class="year-section">
  <div class="year-header">2024</div>
  <div class="month-grid">
    
    <div class="month-card nov-2024">
      <div class="month-title">November</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">07/11</span>N8n</li>
        <li class="service-item"><span class="service-date">07/11</span>Pinchflat</li>
      </ul>
    </div>

    <div class="month-card oct-2024">
      <div class="month-title">October</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">29/10</span>Nexterm</li>
        <li class="service-item"><span class="service-date">14/10</span>Web Check</li>
      </ul>
    </div>

    <div class="month-card sep-2024">
      <div class="month-title">September</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">20/09</span>TinyMediaManager</li>
        <li class="service-item"><span class="service-date">03/09</span>Hoarder</li>
      </ul>
    </div>

    <div class="month-card aug-2024">
      <div class="month-title">August</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">29/08</span>Markopolis</li>
        <li class="service-item"><span class="service-date">26/08</span>Fusion</li>
        <li class="service-item"><span class="service-date">26/08</span>Medama Analytics</li>
      </ul>
    </div>

    <div class="month-card jul-2024">
      <div class="month-title">July</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">26/07</span>Beszel</li>
      </ul>
    </div>

    <div class="month-card jun-2024">
      <div class="month-title">June</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">27/06</span>Gathio</li>
      </ul>
    </div>

    <div class="month-card may-2024">
      <div class="month-title">May</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">27/05</span>OpnForm</li>
        <li class="service-item"><span class="service-date">23/05</span>Speedtest Tracker</li>
        <li class="service-item"><span class="service-date">01/05</span>TimeTagger</li>
      </ul>
    </div>

    <div class="month-card apr-2024">
      <div class="month-title">April</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">09/04</span>NetAlertX</li>
      </ul>
    </div>

    <div class="month-card mar-2024">
      <div class="month-title">March</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">11/03</span>Stirling-PDF</li>
        <li class="service-item"><span class="service-date">04/03</span>Pingvin-Share</li>
      </ul>
    </div>

    <div class="month-card feb-2024">
      <div class="month-title">February</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">26/02</span>Chibisafe</li>
      </ul>
    </div>

    <div class="month-card jan-2024">
      <div class="month-title">January</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">03/01</span>Webtrees</li>
        <li class="service-item"><span class="service-date">03/01</span>Wordpress</li>
      </ul>
    </div>

  </div>
</div>

<!-- 2023 -->
<div class="year-section">
  <div class="year-header">2023</div>
  <div class="month-grid">
    
    <div class="month-card dec-2023">
      <div class="month-title">December</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">12/12</span>Dokemon</li>
      </ul>
    </div>

    <div class="month-card nov-2023">
      <div class="month-title">November</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">19/11</span>Dockge</li>
        <li class="service-item"><span class="service-date">17/11</span>Activepieces</li>
        <li class="service-item"><span class="service-date">17/11</span>Draw.io</li>
        <li class="service-item"><span class="service-date">17/11</span>netboot.xyz</li>
        <li class="service-item"><span class="service-date">03/11</span>pve-exporter</li>
      </ul>
    </div>

    <div class="month-card oct-2023">
      <div class="month-title">October</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">26/10</span>Hauk</li>
        <li class="service-item"><span class="service-date">26/10</span>Shaarli</li>
        <li class="service-item"><span class="service-date">26/10</span>FlowiseAI</li>
        <li class="service-item"><span class="service-date">24/10</span>Plane</li>
        <li class="service-item"><span class="service-date">18/10</span>Bazarr <em>(Stack Update)</em></li>
        <li class="service-item"><span class="service-date">16/10</span>Feedcord</li>
        <li class="service-item"><span class="service-date">16/10</span>Fetchcord</li>
      </ul>
    </div>

    <div class="month-card sep-2023">
      <div class="month-title">September</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">26/09</span>Pingvin-share</li>
      </ul>
    </div>

    <div class="month-card aug-2023">
      <div class="month-title">August</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">10/08</span>Kapowarr</li>
      </ul>
    </div>

    <div class="month-card jul-2023">
      <div class="month-title">July</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">10/07</span>Mend.io Renovate</li>
        <li class="service-item"><span class="service-date">09/07</span>Kiwix (ZIM reader)</li>
      </ul>
    </div>

    <div class="month-card jun-2023">
      <div class="month-title">June</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">27/06</span>Grocy</li>
        <li class="service-item"><span class="service-date">13/06</span>Linkstack</li>
        <li class="service-item"><span class="service-date">08/06</span>Ansible-semaphore</li>
        <li class="service-item"><span class="service-date">02/06</span>Shiori</li>
      </ul>
    </div>

    <div class="month-card may-2023">
      <div class="month-title">May</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">23/05</span>Funkwhale</li>
        <li class="service-item"><span class="service-date">23/05</span>Airsonic</li>
        <li class="service-item"><span class="service-date">09/05</span>Tubearchivist</li>
      </ul>
    </div>

    <div class="month-card apr-2023">
      <div class="month-title">April</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">07/04</span>Flood UI with QTorrent</li>
        <li class="service-item"><span class="service-date">06/04</span>WatchRARr</li>
        <li class="service-item"><span class="service-date">06/04</span>Unpackerr</li>
      </ul>
    </div>

    <div class="month-card mar-2023">
      <div class="month-title">March</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">24/03</span>Autobrr</li>
        <li class="service-item"><span class="service-date">24/03</span>Baikal</li>
        <li class="service-item"><span class="service-date">15/03</span>Glances</li>
        <li class="service-item"><span class="service-date">07/03</span>Gokapi</li>
        <li class="service-item"><span class="service-date">01/03</span>Mastodon</li>
      </ul>
    </div>

    <div class="month-card feb-2023">
      <div class="month-title">February <span class="badge-new">TYPE 3</span></div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">21/02</span>Snibox (Stack)</li>
        <li class="service-item"><span class="service-date">21/02</span>Adguard Home (Stack)</li>
        <li class="service-item"><span class="service-date">21/02</span>Overseerr (Stack)</li>
        <li class="service-item"><span class="service-date">21/02</span>Organizr (Stack)</li>
        <li class="service-item"><span class="service-date">21/02</span>Ombi (Stack)</li>
        <li class="service-item"><span class="service-date">21/02</span>Nodered (Stack)</li>
        <li class="service-item"><span class="service-date">21/02</span>Tailscale</li>
        <li class="service-item"><span class="service-date">15/02</span>Documize</li>
        <li class="service-item"><span class="service-date">15/02</span>Dashdot (Updated)</li>
        <li class="service-item"><span class="service-date">15/02</span>Homarr</li>
        <li class="service-item"><span class="service-date">11/02</span>Tabby</li>
        <li class="service-item"><span class="service-date">11/02</span>Remotely</li>
        <li class="service-item"><span class="service-date">11/02</span>Rport</li>
        <li class="service-item"><span class="service-date">11/02</span>Rust Desk</li>
        <li class="service-item"><span class="service-date">11/02</span>MeshCentral</li>
        <li class="service-item"><span class="service-date">05/02</span>UpSnap</li>
        <li class="service-item"><span class="service-date">05/02</span>Excalidraw</li>
        <li class="service-item"><span class="service-date">04/02</span>Tooljet</li>
        <li class="service-item"><span class="service-date">01/02</span>Syncthing</li>
        <li class="service-item"><span class="service-date">01/02</span>Meilisearch</li>
        <li class="service-item"><span class="service-date">01/02</span>Ory Kratos (Oathkeeper)</li>
        <li class="service-item"><span class="service-date">01/02</span>Ory Kratos (Standalone)</li>
        <li class="service-item"><span class="service-date">01/02</span>Budibase</li>
        <li class="service-item"><span class="service-date">01/02</span>AppSmith</li>
      </ul>
    </div>

    <div class="month-card jan-2023">
      <div class="month-title">January</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">27/01</span>Moodle</li>
        <li class="service-item"><span class="service-date">27/01</span>ProxiTok</li>
        <li class="service-item"><span class="service-date">27/01</span>Miniflux</li>
        <li class="service-item"><span class="service-date">27/01</span>Traggo</li>
        <li class="service-item"><span class="service-date">27/01</span>FreeScout</li>
        <li class="service-item"><span class="service-date">27/01</span>Wger</li>
        <li class="service-item"><span class="service-date">27/01</span>Tdarr</li>
        <li class="service-item"><span class="service-date">27/01</span>Uptime Kuma (Update)</li>
        <li class="service-item"><span class="service-date">25/01</span>Docker Container Stats</li>
        <li class="service-item"><span class="service-date">19/01</span>Ferdium</li>
        <li class="service-item"><span class="service-date">19/01</span>NocoDB</li>
        <li class="service-item"><span class="service-date">17/01</span>Codex</li>
        <li class="service-item"><span class="service-date">16/01</span>Monica</li>
        <li class="service-item"><span class="service-date">13/01</span>Whisparr</li>
        <li class="service-item"><span class="service-date">13/01</span>Midarr</li>
        <li class="service-item"><span class="service-date">03/01</span>Signal proxy</li>
      </ul>
    </div>

  </div>
</div>

<!-- 2022 -->
<div class="year-section">
  <div class="year-header">2022</div>
  <div class="month-grid">
    
    <div class="month-card dec-2022">
      <div class="month-title">December</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">25/12</span>ChiefOnboarding</li>
        <li class="service-item"><span class="service-date">19/12</span>Medusa (e-Commerce CMS)</li>
        <li class="service-item"><span class="service-date">19/12</span>Castopod</li>
        <li class="service-item"><span class="service-date">19/12</span>Mautic</li>
        <li class="service-item"><span class="service-date">15/12</span>YourSpotify</li>
        <li class="service-item"><span class="service-date">13/12</span>Influxdb2 & Telegraf</li>
        <li class="service-item"><span class="service-date">13/12</span>Influxdb2 (standalone)</li>
        <li class="service-item"><span class="service-date">12/12</span>Grafana (latest)</li>
        <li class="service-item"><span class="service-date">08/12</span>Silverstripe CMS</li>
        <li class="service-item"><span class="service-date">08/12</span>FileStash</li>
      </ul>
    </div>

    <div class="month-card nov-2022">
      <div class="month-title">November</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">30/11</span>Readarr</li>
        <li class="service-item"><span class="service-date">24/11</span>Mailpile</li>
        <li class="service-item"><span class="service-date">24/11</span>Appwrite</li>
        <li class="service-item"><span class="service-date">18/11</span>Poste.io</li>
        <li class="service-item"><span class="service-date">03/11</span>Lazytainer</li>
      </ul>
    </div>

    <div class="month-card oct-2022">
      <div class="month-title">October</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">14/10</span>iperf</li>
      </ul>
    </div>

    <div class="month-card sep-2022">
      <div class="month-title">September</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">27/09</span>Homepage</li>
        <li class="service-item"><span class="service-date">26/09</span>I hate money</li>
        <li class="service-item"><span class="service-date">22/09</span>Fireshare</li>
      </ul>
    </div>

    <div class="month-card aug-2022">
      <div class="month-title">August</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">03/08</span>Jump</li>
        <li class="service-item"><span class="service-date">03/08</span>Filepizza</li>
        <li class="service-item"><span class="service-date">01/08</span>XWiki</li>
      </ul>
    </div>

    <div class="month-card jul-2022">
      <div class="month-title">July</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">29/07</span>Leantime</li>
        <li class="service-item"><span class="service-date">29/07</span>Jellyseer</li>
        <li class="service-item"><span class="service-date">29/07</span>Trudesk [WIP]</li>
        <li class="service-item"><span class="service-date">29/07</span>Dash/Dashdot [WIP]</li>
        <li class="service-item"><span class="service-date">28/07</span>Koillection [WIP]</li>
        <li class="service-item"><span class="service-date">22/07</span>Zusam</li>
        <li class="service-item"><span class="service-date">21/07</span>Vikunja</li>
        <li class="service-item"><span class="service-date">05/07</span>massCode [no Docker]</li>
        <li class="service-item"><span class="service-date">01/07</span>Facebox [WIP]</li>
      </ul>
    </div>

    <div class="month-card jun-2022">
      <div class="month-title">June</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">01/06</span>Eufy Security WS</li>
      </ul>
    </div>

    <div class="month-card may-2022">
      <div class="month-title">May</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">31/05</span>Servas/Wallabag [WIP]</li>
        <li class="service-item"><span class="service-date">24/05</span>Tandoor</li>
        <li class="service-item"><span class="service-date">10/05</span>Trilium Notes</li>
        <li class="service-item"><span class="service-date">09/05</span>Audiobookshelf</li>
        <li class="service-item"><span class="service-date">04/05</span>Baserow</li>
        <li class="service-item"><span class="service-date">04/05</span>GoAccess for NPM Logs</li>
      </ul>
    </div>

    <div class="month-card mar-2022">
      <div class="month-title">March</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">15/03</span>Fenrus</li>
      </ul>
    </div>

    <div class="month-card feb-2022">
      <div class="month-title">February</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">17/02</span>Kavita</li>
      </ul>
    </div>

    <div class="month-card jan-2022">
      <div class="month-title">January</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">28/01</span>Pi.alert</li>
        <li class="service-item"><span class="service-date">11/01</span>Navidrome</li>
      </ul>
    </div>

  </div>
</div>

<!-- 2021 -->
<div class="year-section">
  <div class="year-header">2021 🎂 Inception</div>
  <div class="month-grid">
    
    <div class="month-card dec-2021">
      <div class="month-title">December</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">12/12</span>Firefox</li>
        <li class="service-item"><span class="service-date">07/12</span>Broadlink Manager</li>
        <li class="service-item"><span class="service-date">07/12</span>Homebridge</li>
        <li class="service-item"><span class="service-date">07/12</span>NUTS</li>
        <li class="service-item"><span class="service-date">06/12</span>Dozzle</li>
      </ul>
    </div>

    <div class="month-card nov-2021">
      <div class="month-title">November</div>
      <ul class="service-list">
        <li class="service-item"><span class="service-date">16/11</span>Flame Dashboard</li>
        <li class="service-item"><span class="service-date">12/11</span>Snippet Box</li>
        <li class="service-item"><span class="service-date">12/11</span>Photoprism</li>
        <li class="service-item"><span class="service-date">12/11</span>Teleport</li>
        <li class="service-item"><span class="service-date">08/11</span>Aria2 Pro</li>
        <li class="service-item"><span class="service-date">08/11</span>Apprise-API</li>
        <li class="service-item"><span class="service-date">08/11</span>Cryptofolio</li>
        <li class="service-item"><span class="service-date">05/11</span>Umami.is</li>
        <li class="service-item"><span class="service-date">05/11</span>Matomo</li>
        <li class="service-item"><span class="service-date">05/11</span>N.eko Rooms</li>
        <li class="service-item"><span class="service-date">05/11</span>Changedetection.io</li>
        <li class="service-item"><span class="service-date">05/11</span>Ghost</li>
        <li class="service-item"><span class="service-date">05/11</span>Monica</li>
        <li class="service-item"><span class="service-date">05/11</span>Netbox</li>
        <li class="service-item"><span class="service-date">05/11</span>Freeboard</li>
        <li class="service-item"><span class="service-date">05/11</span>Nodered</li>
        <li class="service-item"><span class="service-date">05/11</span>Reveal.js</li>
        <li class="service-item"><span class="service-date">05/11</span>Statping</li>
        <li class="service-item"><span class="service-date">05/11</span>Frigate NVR</li>
        <li class="service-item"><span class="service-date">05/11</span>Ferdi</li>
        <li class="service-item"><span class="service-date">04/11</span>Uptime-Kuma</li>
        <li class="service-item"><span class="service-date">04/11</span>Dashy</li>
        <li class="service-item"><span class="service-date">04/11</span>WebTop [ubuntu-kde]</li>
        <li class="service-item"><span class="service-date">04/11</span>Littlelink-server</li>
      </ul>
    </div>

  </div>
</div>

</div>

---

## 🗂️ App Categories

<details>
<summary><strong>🔐 Authentication & Security</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Authelia | SSO and 2FA portal |
| Vaultwarden | Bitwarden-compatible password manager |
| Adguard | Network-wide ad blocker |
| Crowdsec | Collaborative security engine |
| Tailscale | Zero-config VPN |
</details>

<details>
<summary><strong>📊 Monitoring & Analytics</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Uptime Kuma | Monitoring dashboard |
| Beszel | System monitoring |
| Speedtest Tracker | Internet speed monitoring |
| NetAlertX | Network scanner and alerts |
| Glances | System monitoring |
| Checkmate | Status page |
| Lunalytics | Analytics platform |
</details>

<details>
<summary><strong>🎬 Media & Entertainment</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Navidrome | Music server |
| Audiobookshelf | Audiobook server |
| Kavita | Digital library |
| Komga (implied) | Comics server |
| Jellyseer | Media request manager |
| Bazarr | Subtitle manager |
| TinyMediaManager | Media management |
</details>

<details>
<summary><strong>☁️ Productivity & Collaboration</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| N8n | Workflow automation |
| Plane | Project management |
| Tooljet | Low-code platform |
| AppSmith | Internal tool builder |
| Budibase | Low-code platform |
| Excalidraw | Virtual whiteboard |
| Draw.io | Diagramming tool |
</details>

<details>
<summary><strong>🧠 Knowledge Management</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Hoarder | Bookmark manager |
| Blinko | Note-taking |
| Trilium Notes | Hierarchical notes |
| Bookstack | Documentation wiki |
| Wiki.js | Modern wiki |
| TiddlyWiki | Non-linear notebook |
</details>

<details>
<summary><strong>🔧 Development & DevOps</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Portainer | Container management |
| Dockge | Docker compose stack manager |
| Kasm Workspaces | Streaming workspaces |
| Code-Server | VS Code in browser |
| GitLab (implied) | Git repository |
| Jenkins (implied) | CI/CD automation |
| Kestra | Workflow orchestration |
</details>

<details>
<summary><strong>🏠 Home Automation</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Homebridge | HomeKit integration |
| Domoticz | Home automation system |
| Nodered | Flow-based programming |
| Eufy Security WS | Security camera integration |
</details>

<details>
<summary><strong>📥 Download Management</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Aria2 Pro | Download manager |
| Transmission-OpenVPN | BitTorrent client with VPN |
| Flood UI | qBittorrent web UI |
| Pinchflat | YouTube downloader |
| Tubearchivist | YouTube archive |
</details>

<details>
<summary><strong>🌐 Networking & Proxy</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Nginx Proxy Manager | Reverse proxy |
| Tailscale | Mesh VPN |
| Netbox | IPAM and DCIM |
| Lazytainer | Lazy container starter |
</details>

<details>
<summary><strong>🗄️ Databases & Storage</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| InfluxDB2 | Time-series database |
| Grafana | Data visualization |
| NocoDB | Airtable alternative |
| Baserow | Database GUI |
| Meilisearch | Search engine |
</details>

<details>
<summary><strong>📧 Communication</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Ferdium | Messaging aggregator |
| Signal Proxy | Signal proxy server |
| Murmur | Voice chat server |
| Castopod | Podcast hosting |
</details>

<details>
<summary><strong>🛠️ Utilities & Tools</strong></summary>
<br>

| Service | Description |
|---------|-------------|
| Stirling-PDF | PDF manipulation |
| Chibisafe | File uploader |
| Pingvin-Share | File sharing |
| FileStash | File manager |
| Syncthing | Continuous sync |
| Watchtower | Container updates |
</details>

---

## 👥 Authors & Contributors

| Contributor | Role | Profile |
|-------------|------|---------|
| **Vagelis Fragkos** | *Maintainer* | [@xneo1](https://github.com/xneo1) |
| **NASHosted** | *Current Work* | [@nashosted](https://github.com/nashosted) |
| **SelfhostedPro** | *Current Work* | [@SelfhostedPro](https://github.com/SelfhostedPro) |
| **Jos Visser** | *Initial Work* | [@Qballjos](https://github.com/Qballjos) |
| **xe-nvdk** | *Template Conversion* | [@xe-nvdk](https://github.com/xe-nvdk) |
| **tbiering** | *Cleanup & Fixes* | [@tbiering](https://github.com/tbiering) |

[View all contributors](https://github.com/xneo1/portainer_templates/graphs/contributors)

---

<p align="center">
  <sub>Built with ❤️ for the self-hosted community</sub>
</p>
