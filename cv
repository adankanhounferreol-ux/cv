<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ferreol Anold ADANKANHOUN — CV</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
<style>
  :root{
    --ink:#20242C;
    --sidebar-bg:#232732;
    --sidebar-text:#E9E7DF;
    --sidebar-muted:#AEB0AC;
    --paper:#FCFBF8;
    --accent:#A9793E;
    --accent-soft:#D9C6A3;
    --rule:#E1DACB;
    --muted:#686C72;
    --page-w: 960px;
  }

  *{ box-sizing:border-box; }

  html,body{
    margin:0; padding:0;
    background:#DEDAD0;
    font-family:'Montserrat', sans-serif;
    color:var(--ink);
    -webkit-font-smoothing:antialiased;
  }

  .sheet{
    max-width:var(--page-w);
    margin:28px auto;
    background:var(--paper);
    box-shadow:0 10px 40px rgba(0,0,0,.18);
    display:grid;
    grid-template-columns:32% 68%;
    grid-template-rows:auto 1fr;
  }

  /* ---------- HEADER BAND ---------- */
  .header{
    grid-column:1 / -1;
    background:var(--ink);
    color:var(--sidebar-text);
    display:grid;
    grid-template-columns:auto 1fr;
    align-items:center;
    gap:28px;
    padding:34px 42px;
  }
  .header .avatar{
    width:104px; height:104px;
    border-radius:50%;
    overflow:hidden;
    border:3px solid var(--accent-soft);
    flex-shrink:0;
  }
  .header .avatar img{ width:100%; height:100%; object-fit:cover; display:block; }

  .header .id .name{
    font-size:30px;
    font-weight:700;
    letter-spacing:.3px;
    margin:0 0 4px 0;
    line-height:1.15;
  }
  .header .id .name .family{
    font-weight:800;
    color:#fff;
  }
  .header .id .tagline{
    font-size:13.5px;
    font-weight:500;
    color:var(--accent-soft);
    letter-spacing:.4px;
    margin:0 0 14px 0;
  }
  .header .contacts{
    display:flex;
    flex-wrap:wrap;
    gap:18px 26px;
    font-size:12px;
    font-weight:400;
    color:var(--sidebar-muted);
  }
  .header .contacts span{
    display:inline-flex;
    align-items:center;
    gap:7px;
    white-space:nowrap;
  }
  .header .contacts svg{ width:13px; height:13px; fill:none; stroke:var(--accent-soft); stroke-width:1.8; flex-shrink:0; }

  /* ---------- SIDEBAR ---------- */
  .sidebar{
    background:var(--sidebar-bg);
    color:var(--sidebar-text);
    padding:34px 32px 44px;
  }
  .side-block{ margin-bottom:30px; }
  .side-block:last-child{ margin-bottom:0; }

  .side-title{
    font-size:11px;
    font-weight:700;
    letter-spacing:1.6px;
    text-transform:uppercase;
    color:var(--accent-soft);
    margin:0 0 14px 0;
    padding-bottom:8px;
    border-bottom:1px solid rgba(233,231,223,.18);
  }

  .skill-group{ margin-bottom:14px; }
  .skill-group:last-child{ margin-bottom:0; }
  .skill-group h4{
    font-size:11.5px;
    font-weight:600;
    margin:0 0 8px 0;
    color:#fff;
    letter-spacing:.2px;
  }
  .tag-row{ display:flex; flex-wrap:wrap; gap:6px; }
  .tag{
    font-size:10.5px;
    font-weight:400;
    padding:4px 9px;
    border-radius:11px;
    background:rgba(233,231,223,.09);
    border:1px solid rgba(233,231,223,.16);
    color:var(--sidebar-text);
    line-height:1.4;
  }

  .lang-row{
    display:grid;
    grid-template-columns:1fr auto;
    align-items:center;
    gap:8px;
    font-size:12px;
    margin-bottom:11px;
  }
  .lang-row:last-child{ margin-bottom:0; }
  .lang-name{ font-weight:500; }
  .dots{ display:flex; gap:4px; }
  .dot{ width:7px; height:7px; border-radius:50%; background:rgba(233,231,223,.22); }
  .dot.on{ background:var(--accent-soft); }

  .edu-item{ margin-bottom:16px; font-size:12px; line-height:1.5; }
  .edu-item:last-child{ margin-bottom:0; }
  .edu-item .deg{ font-weight:600; color:#fff; display:block; }
  .edu-item .school{ color:var(--sidebar-muted); font-weight:400; }

  .cert-item{ margin-bottom:13px; font-size:11.5px; line-height:1.5; }
  .cert-item:last-child{ margin-bottom:0; }
  .cert-item .cname{ font-weight:600; color:#fff; display:block; }
  .cert-item .cmeta{ color:var(--sidebar-muted); font-size:11px; }

  .chip-list{ display:flex; flex-wrap:wrap; gap:7px; }
  .chip-list span{
    font-size:11px;
    color:var(--sidebar-text);
    position:relative;
    padding-left:12px;
  }
  .chip-list span::before{
    content:"";
    position:absolute; left:0; top:6px;
    width:5px; height:5px; border-radius:50%;
    background:var(--accent-soft);
  }

  /* ---------- MAIN ---------- */
  .main{
    padding:38px 46px 50px;
  }
  .main-title{
    font-size:13px;
    font-weight:700;
    letter-spacing:1.6px;
    text-transform:uppercase;
    color:var(--accent);
    margin:0 0 14px 0;
    padding-bottom:9px;
    border-bottom:2px solid var(--rule);
  }
  .section{ margin-bottom:32px; }
  .section:last-child{ margin-bottom:0; }

  .profile-text p{
    font-size:13px;
    line-height:1.75;
    color:#3B3F45;
    font-weight:400;
    margin:0 0 12px 0;
  }
  .profile-text p:last-child{ margin-bottom:0; }
  .profile-text .placeholder{ color:var(--muted); font-style:italic; }

  .timeline{ position:relative; padding-left:22px; }
  .timeline::before{
    content:"";
    position:absolute; left:4px; top:6px; bottom:6px;
    width:1.5px;
    background:var(--rule);
  }
  .job{ position:relative; margin-bottom:26px; }
  .job:last-child{ margin-bottom:0; }
  .job::before{
    content:"";
    position:absolute; left:-22px; top:4px;
    width:9px; height:9px; border-radius:50%;
    background:var(--paper);
    border:2.5px solid var(--accent);
  }
  .job-head{
    display:flex;
    justify-content:space-between;
    align-items:baseline;
    flex-wrap:wrap;
    gap:4px 14px;
    margin-bottom:2px;
  }
  .job-role{ font-size:14.5px; font-weight:700; color:var(--ink); }
  .job-org{ font-weight:500; color:var(--accent); }
  .job-dates{
    font-size:11px;
    font-weight:600;
    letter-spacing:.3px;
    color:var(--muted);
    white-space:nowrap;
  }
  .job-lead{
    font-size:12px;
    font-style:italic;
    color:var(--muted);
    margin:4px 0 8px 0;
    line-height:1.5;
  }
  .job ul{ margin:0; padding-left:16px; }
  .job li{
    font-size:12.5px;
    line-height:1.65;
    color:#3B3F45;
    margin-bottom:4px;
  }
  .job li:last-child{ margin-bottom:0; }
  .job li .placeholder{ color:var(--muted); font-style:italic; }

  .quality-row{
    display:flex; flex-wrap:wrap; gap:9px 10px;
  }
  .quality-row span{
    font-size:11.5px;
    font-weight:500;
    color:var(--ink);
    background:#F2EEE4;
    border:1px solid var(--rule);
    padding:6px 13px;
    border-radius:4px;
  }

  .interest-row{ display:flex; flex-wrap:wrap; gap:8px 22px; }
  .interest-row span{
    font-size:12px;
    color:#3B3F45;
    position:relative;
    padding-left:14px;
  }
  .interest-row span::before{
    content:"";
    position:absolute; left:0; top:7px;
    width:5px; height:5px;
    background:var(--accent);
    transform:rotate(45deg);
  }

  @media print{
    html,body{ background:#fff; }
    .sheet{ box-shadow:none; margin:0; max-width:none; }
    * { -webkit-print-color-adjust:exact; print-color-adjust:exact; }
  }
  @page{ size:A4; margin:0; }

  @media (max-width:760px){
    .sheet{ grid-template-columns:1fr; }
    .header{ grid-template-columns:1fr; text-align:center; padding:28px 24px; }
    .header .id{ display:flex; flex-direction:column; align-items:center; }
    .header .contacts{ justify-content:center; }
    .main{ padding:30px 26px; }
    .sidebar{ padding:28px 26px; }
  }
</style>
</head>
<body>

<div class="sheet">

  <!-- HEADER -->
  <header class="header">
    <div class="avatar">
      <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wBDAAQDAwMDAgQDAwMEBAQFBgoGBgUFBgwICQcKDgwPDg4MDQ0PERYTDxAVEQ0NExoTFRcYGRkZDxIbHRsYHRYYGRj/2wBDAQQEBAYFBgsGBgsYEA0QGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBgYGBj/wAARCAH0AfQDASIAAhEBAxEB/8QAHwAAAQUBAQEBAQEAAAAAAAAAAAECAwQFBgcICQoL/8QAtRAAAgEDAwIEAwUFBAQAAAF9AQIDAAQRBRIhMUEGE1FhByJxFDKBkaEII0KxwRVS0fAkM2JyggkKFhcYGRolJicoKSo0NTY3ODk6Q0RFRkdISUpTVFVWV1hZWmNkZWZnaGlqc3R1dnd4eXqDhIWGh4iJipKTlJWWl5iZmqKjpKWmp6ipqrKztLW2t7i5usLDxMXGx8jJytLT1NXW19jZ2uHi4+Tl5ufo6erx8vP09fb3+Pn6/8QAHwEAAwEBAQEBAQEBAQAAAAAAAAECAwQFBgcICQoL/8QAtREAAgECBAQDBAcFBAQAAQJ3AAECAxEEBSExBhJBUQdhcRMiMoEIFEKRobHBCSMzUvAVYnLRChYkNOEl8RcYGRomJygpKjU2Nzg5OkNERUZHSElKU1RVVldYWVpjZGVmZ2hpanN0dXZ3eHl6goOEhYaHiImKkpOUlZaXmJmaoqOkpaanqKmqsrO0tba3uLm6wsPExcbHyMnK0tPU1dbX2Nna4uPk5ebn6Onq8vP09fb3+Pn6/9oADAMBAAIRAxEAPwD7+ooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKx/EfijQPCWiPq3iPVLbT7RCAZZ3Cgk9BQBsUx5I4k3yOqL6scCvjf4j/twrYas+nfDzw/DeRplRf37kCRumVQfw98k5NfJ/jX41/EfxvK8vivxhqV0vmF1to5DDAhGcBUXAHXA607Dt3P1J1n4tfDTw/M0WseONDtnX7ym7RivOOcE4rAP7RfwSEyxH4jaKCSefMOOPU4x349a/J6a4kM6nEe1wMvjkMev1qOS+aB1eVyyg4woxk98etFg0P130743fCbVSBYfEDQ5CW2AG5Vct6DPU121lqFjqdmt3p15Bd27/AHZYJA6n8RX4lSajJcXAMWVI5UOuCB356V0fhrxx4q8MXQuvD/ifUdMfPItLmSMfXg7SfwosGh+zdFfn/wDB/wDbT8RaDFBo/wASIH1nT0IT+0Ix/pMa8D5uz4/M19reC/iP4K+IWkLqPhHX7TUYiOURsSJ6hkPIpA0dVRRRQIKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiigAooooAKKKKACiiuM+JnxK8OfDDwNdeINevI42VGFtbkndcS4JVAB6kdaAK/xS+LHhX4T+Ezq/iK6BmkBFrZRnMtwwHQD09T0Ga/NX4p/GjxZ8WfGMuoa40kNorbbXT4nJhgX2Hc9yTzWP8SviXr3xL8bXXiPX7jfczErFEWISFP4Y1HZR+p5rj7LTtWvpGlhtFk5wCrkAd/w/wDr0XUdzSMW9EQ3d2WnQu6YUE7s/offpWVPNbtMWUPIw+6AuT9fQGu70zwLPdXIn1BSvU+WpyMmu0sPBWkWrK6WyFhztYZ/WsZYiKOmGCnPfQ8VbTNQZoZLhDGrIGBZwSeevvkVFPC0jtE6GNg2QwxjA7GvfW8KaZM+97eLceMgU6LwrpavzZxk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" alt="Ferréol Anold Adankanhoun">
    </div>
    <div class="id">
      <p class="name">Ferreol Anold <span class="family">ADANKANHOUN</span></p>
      <p class="tagline">SUPERVISEUR BACK OFFICE — CUSTOMER EXPERIENCE &amp; PERFORMANCE OPÉRATIONNELLE</p>
      <div class="contacts">
        <span><svg viewBox="0 0 24 24"><path d="M12 21s-7-6.2-7-11.5A7 7 0 0 1 19 9.5C19 14.8 12 21 12 21z"/><circle cx="12" cy="9.5" r="2.3"/></svg>Abomey-Calavi, Bénin</span>
        <span><svg viewBox="0 0 24 24"><path d="M4 4h4l2 5-2.5 1.5a11 11 0 0 0 5 5L14 13l5 2v4a2 2 0 0 1-2 2C9.5 21 3 14.5 3 6a2 2 0 0 1 1-2z"/></svg>+229 0152000959 / 0167341742</span>
        <span><svg viewBox="0 0 24 24"><path d="M3 6h18v12H3z"/><path d="M3 7l9 6 9-6"/></svg>adankanhoun.ferreol@gmail.com</span>
      </div>
    </div>
  </header>

  <!-- SIDEBAR -->
  <aside class="sidebar">

    <div class="side-block">
      <p class="side-title">Compétences</p>
      <div class="skill-group">
        <h4>Relation Client</h4>
        <div class="tag-row">
          <span class="tag">Gestion des réclamations</span>
          <span class="tag">Satisfaction client</span>
          <span class="tag">Fidélisation</span>
          <span class="tag">Escalades</span>
        </div>
      </div>
      <div class="skill-group">
        <h4>Management</h4>
        <div class="tag-row">
          <span class="tag">Encadrement d'équipes</span>
          <span class="tag">Coaching</span>
          <span class="tag">Gestion de la performance</span>
          <span class="tag">Coordination</span>
        </div>
      </div>
      <div class="skill-group">
        <h4>Back Office &amp; Outils</h4>
        <div class="tag-row">
          <span class="tag">Dossiers complexes</span>
          <span class="tag">Contrôle qualité</span>
          <span class="tag">Excel · Word · PPT</span>
          <span class="tag">CRM</span>
        </div>
      </div>
    </div>

    <div class="side-block">
      <p class="side-title">Langues</p>
      <div class="lang-row">
        <span class="lang-name">Français</span>
        <span class="dots"><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span></span>
      </div>
      <div class="lang-row">
        <span class="lang-name">Sahouè</span>
        <span class="dots"><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span></span>
      </div>
      <div class="lang-row">
        <span class="lang-name">Fon</span>
        <span class="dots"><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span></span>
      </div>
      <div class="lang-row">
        <span class="lang-name">Anglais</span>
        <span class="dots"><span class="dot on"></span><span class="dot on"></span><span class="dot on"></span><span class="dot"></span><span class="dot"></span></span>
      </div>
    </div>

    <div class="side-block">
      <p class="side-title">Formation</p>
      <div class="edu-item">
        <span class="deg">Licence Professionnelle en Communication</span>
        <span class="school">Université d'Abomey-Calavi (UAC)</span>
      </div>
      <div class="edu-item">
        <span class="deg">Baccalauréat Série A2</span>
        <span class="school">CEG Azonlihoué</span>
      </div>
    </div>

    <div class="side-block">
      <p class="side-title">Certifications</p>
      <div class="cert-item">
        <span class="cname">Réussir sa prise de poste en tant que manager</span>
        <span class="cmeta">LinkedIn Learning — Janvier 2026</span>
      </div>
      <div class="cert-item">
        <span class="cname">Choisir d'être un bon manager</span>
        <span class="cmeta">LinkedIn Learning — Février 2026</span>
      </div>
      <div class="cert-item">
        <span class="cname">Devenir un bon leader</span>
        <span class="cmeta">Edflex — Février 2026</span>
      </div>
    </div>

    <div class="side-block">
      <p class="side-title">Centres d'intérêt</p>
      <div class="chip-list">
        <span>Relation client &amp; expérience utilisateur</span>
        <span>Technologies numériques</span>
        <span>Développement personnel</span>
        <span>Lecture &amp; veille professionnelle</span>
        <span>Communication visuelle &amp; design</span>
      </div>
    </div>

  </aside>

  <!-- MAIN -->
  <main class="main">

    <section class="section">
      <p class="main-title">Profil professionnel</p>
      <div class="profile-text">
        <p>Professionnel de la relation client avec 03 ans d'expérience en supervision opérationnelle dans un centre de contacts. Expert en gestion d'équipes, pilotage des activités Back Office et suivi des KPI. Spécialiste du traitement des réclamations complexes et de l'amélioration continue de l'expérience client.</p>
        <p>Reconnu pour son leadership, son sens du relationnel, sa réactivité et son orientation résultats.</p>
      </div>
    </section>

    <section class="section">
      <p class="main-title">Expérience professionnelle</p>
      <div class="timeline">

        <div class="job">
          <div class="job-head">
            <span><span class="job-role">Superviseur Back Office</span> — <span class="job-org">MTN Bénin (Palladium Africa)</span></span>
            <span class="job-dates">MAI 2026 — AUJOURD'HUI</span>
          </div>
          <p class="job-lead">Pilotage de la performance opérationnelle du service Back Office.</p>
          <ul>
            <li>Supervision des activités quotidiennes et coordination inter-équipes</li>
            <li>Résolution des réclamations complexes et gestion des escalades prioritaires</li>
            <li>Garantie du respect des procédures, standards qualité et délais de traitement</li>
            <li>Production et analyse des KPI pour orienter les décisions opérationnelles</li>
            <li>Accompagnement des équipes vers l'atteinte des objectifs qualitatifs</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-head">
            <span><span class="job-role">Superviseur Digital</span> — <span class="job-org">MTN Bénin (Palladium Africa)</span></span>
            <span class="job-dates">MARS 2025 — AVRIL 2026</span>
          </div>
          <p class="job-lead">Supervision des équipes digitales et coordination Back Office.</p>
          <ul>
            <li>Suivi des performances individuelles et collectives, coaching des collaborateurs</li>
            <li>Traitement des demandes clients complexes et gestion des situations sensibles</li>
            <li>Amélioration du NPS et des métriques de satisfaction</li>
            <li>Élaboration des rapports d'activité et reporting opérationnel</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-head">
            <span><span class="job-role">Téléconseiller</span> — <span class="job-org">Palladium Africa</span></span>
            <span class="job-dates">AVRIL 2023 — MARS 2025</span>
          </div>
          <p class="job-lead">Prise en charge des demandes clients multicanal (réseaux sociaux, chat, e-mail).</p>
          <ul>
            <li>Accompagnement client sur les produits et services digitaux</li>
            <li>Traitement et suivi des réclamations jusqu'à résolution</li>
            <li>Respect des standards de qualité et de délai</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-head">
            <span><span class="job-role">Stagiaire Professionnel (CRCD)</span> — <span class="job-org">Palladium Africa</span></span>
            <span class="job-dates">JUILLET 2022 — MARS 2023</span>
          </div>
          <ul>
            <li>Prise en charge des demandes clients via canaux digitaux</li>
            <li>Traitement des réclamations selon les procédures établies</li>
          </ul>
        </div>

        <div class="job">
          <div class="job-head">
            <span><span class="job-role">Secrétaire Bureautique</span> — <span class="job-org">Plume Électronique</span></span>
            <span class="job-dates">SEPT. 2019 — JUIN 2021</span>
          </div>
          <ul>
            <li>Gestion administrative, traitement et archivage documentaire</li>
          </ul>
        </div>

      </div>
    </section>

    <section class="section">
      <p class="main-title">Qualités professionnelles</p>
      <div class="quality-row">
        <span>Leadership</span>
        <span>Sens du service client</span>
        <span>Réactivité</span>
        <span>Esprit d'analyse</span>
        <span>Organisation</span>
        <span>Gestion des priorités</span>
        <span>Travail en équipe</span>
        <span>Discrétion</span>
      </div>
    </section>

  </main>

</div>

</body>
</html>
