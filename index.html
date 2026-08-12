<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Placement Intelligence Dashboard | DMI Patna</title>
  
  <!-- Inter & IBM Plex Sans Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@400;500;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  
  <!-- Chart.js and Lucide Icons CDN -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.1/dist/chart.umd.min.js"></script>
  <script src="https://unpkg.com/lucide@latest"></script>

  <style>
    :root {
      --primary-navy: #162844;
      --primary-navy-dark: #0f1c30;
      --primary-navy-light: #243b5e;
      --accent-green: #1a6b4b;
      --accent-green-light: #e6f4ea;
      --accent-amber: #b45309;
      --accent-amber-light: #fef3c7;
      --accent-red: #991b1b;
      --accent-red-light: #fee2e2;
      --accent-blue: #2563eb;
      --accent-blue-light: #eff6ff;
      --bg-main: #f8fafc;
      --bg-card: #ffffff;
      --border-color: #e2e8f0;
      --border-subtle: #edf2f7;
      --text-main: #1e293b;
      --text-muted: #64748b;
      --text-light: #94a3b8;
      --sidebar-width: 260px;
      --header-height: 64px;
      --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
      --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.07), 0 2px 4px -2px rgba(0, 0, 0, 0.05);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background-color: var(--bg-main);
      color: var(--text-main);
      line-height: 1.5;
      font-size: 14px;
      overflow-x: hidden;
    }

    /* Top Utility Banner */
    .demo-disclaimer-banner {
      background: #fdf8e6;
      border-bottom: 1px solid #f9e295;
      color: #78350f;
      padding: 6px 16px;
      font-size: 11.5px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    .demo-disclaimer-banner strong { font-weight: 600; }

    /* Layout Structure */
    .app-container {
      display: flex;
      min-height: calc(100vh - 30px);
    }

    /* Sidebar Navigation */
    aside.sidebar {
      width: var(--sidebar-width);
      background-color: var(--primary-navy-dark);
      color: #e2e8f0;
      flex-shrink: 0;
      display: flex;
      flex-direction: column;
      border-right: 1px solid #111d2e;
      position: sticky;
      top: 30px;
      height: calc(100vh - 30px);
      overflow-y: auto;
    }

    .sidebar-brand {
      padding: 18px 20px;
      border-bottom: 1px solid rgba(255, 255, 255, 0.08);
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .brand-mark {
      background-color: var(--accent-green);
      color: #fff;
      font-weight: 700;
      font-size: 14px;
      letter-spacing: 0.5px;
      padding: 6px 8px;
      border-radius: 4px;
      line-height: 1;
    }

    .brand-title {
      font-size: 15px;
      font-weight: 700;
      letter-spacing: -0.2px;
      color: #ffffff;
    }
    .brand-sub {
      font-size: 11px;
      color: #94a3b8;
      font-weight: 400;
    }

    .nav-section {
      padding: 12px 0;
    }
    .nav-section-title {
      font-size: 10.5px;
      text-transform: uppercase;
      letter-spacing: 0.8px;
      font-weight: 600;
      color: #64748b;
      padding: 6px 20px;
    }

    .nav-item {
      display: flex;
      align-items: center;
      gap: 12px;
      padding: 9px 20px;
      color: #cbd5e1;
      text-decoration: none;
      font-size: 13px;
      font-weight: 500;
      cursor: pointer;
      border-left: 3px solid transparent;
      transition: all 0.15s ease;
    }
    .nav-item:hover {
      background-color: rgba(255, 255, 255, 0.05);
      color: #ffffff;
    }
    .nav-item.active {
      background-color: rgba(26, 107, 75, 0.22);
      color: #ffffff;
      border-left-color: #34d399;
    }
    .nav-item i {
      width: 16px;
      height: 16px;
      opacity: 0.85;
    }

    /* Main Content Area */
    main.main-content {
      flex: 1;
      display: flex;
      flex-direction: column;
      min-width: 0;
      background-color: var(--bg-main);
    }

    /* Top Institutional Header */
    header.dashboard-header {
      background-color: #ffffff;
      border-bottom: 1px solid var(--border-color);
      padding: 12px 28px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 12px;
    }

    .header-titles h1 {
      font-size: 18px;
      font-weight: 700;
      color: var(--primary-navy);
      letter-spacing: -0.3px;
    }
    .header-titles p {
      font-size: 12px;
      color: var(--text-muted);
    }

    .header-controls {
      display: flex;
      align-items: center;
      gap: 10px;
      flex-wrap: wrap;
    }

    .filter-badge {
      display: flex;
      align-items: center;
      gap: 6px;
      background: #f1f5f9;
      border: 1px solid var(--border-color);
      border-radius: 4px;
      padding: 5px 10px;
      font-size: 12px;
    }
    .filter-badge select {
      background: transparent;
      border: none;
      font-size: 12px;
      font-weight: 600;
      color: var(--primary-navy);
      cursor: pointer;
      outline: none;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 6px 12px;
      border-radius: 4px;
      font-size: 12px;
      font-weight: 600;
      cursor: pointer;
      border: 1px solid transparent;
      transition: all 0.15s ease;
    }
    .btn-primary {
      background-color: var(--primary-navy);
      color: #fff;
    }
    .btn-primary:hover {
      background-color: var(--primary-navy-light);
    }
    .btn-outline {
      background-color: #fff;
      border-color: var(--border-color);
      color: var(--text-main);
    }
    .btn-outline:hover {
      background-color: #f8fafc;
    }

    /* Dynamic Filter Bar */
    .global-filter-strip {
      background: #ffffff;
      border-bottom: 1px solid var(--border-color);
      padding: 8px 28px;
      display: flex;
      align-items: center;
      gap: 16px;
      font-size: 12px;
      flex-wrap: wrap;
    }
    .filter-item {
      display: flex;
      align-items: center;
      gap: 6px;
    }
    .filter-item label {
      color: var(--text-muted);
      font-weight: 500;
    }
    .filter-item select, .filter-item input {
      border: 1px solid var(--border-color);
      padding: 4px 8px;
      border-radius: 4px;
      font-size: 12px;
      background: #fff;
    }

    /* Content Views */
    .view-container {
      padding: 24px 28px;
      display: none;
    }
    .view-container.active {
      display: block;
    }

    /* Section Headers */
    .section-head {
      margin-bottom: 18px;
    }
    .section-head h2 {
      font-size: 16px;
      font-weight: 700;
      color: var(--primary-navy);
      letter-spacing: -0.2px;
    }
    .section-head p {
      font-size: 12.5px;
      color: var(--text-muted);
    }

    /* KPI Grid */
    .kpi-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 14px;
      margin-bottom: 22px;
    }

    .kpi-card {
      background-color: var(--bg-card);
      border: 1px solid var(--border-color);
      border-radius: 6px;
      padding: 14px 16px;
      box-shadow: var(--shadow-sm);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      position: relative;
    }
    .kpi-card::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 3px;
      background: #cbd5e1;
      border-radius: 6px 6px 0 0;
    }
    .kpi-card.accent-green::before { background: var(--accent-green); }
    .kpi-card.accent-amber::before { background: var(--accent-amber); }
    .kpi-card.accent-blue::before { background: var(--accent-blue); }

    .kpi-label {
      font-size: 11.5px;
      font-weight: 600;
      color: var(--text-muted);
      text-transform: uppercase;
      letter-spacing: 0.4px;
    }
    .kpi-value {
      font-size: 22px;
      font-weight: 700;
      color: var(--primary-navy);
      margin: 4px 0;
    }
    .kpi-sub {
      font-size: 11px;
      color: var(--text-muted);
      display: flex;
      align-items: center;
      gap: 4px;
    }
    .kpi-sub.positive { color: var(--accent-green); font-weight: 600; }
    .kpi-sub.warning { color: var(--accent-amber); font-weight: 600; }

    /* Diagnostic Callout Trio */
    .diagnostic-trio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 14px;
      margin-bottom: 24px;
    }

    .diag-card {
      background: #ffffff;
      border: 1px solid var(--border-color);
      border-radius: 6px;
      padding: 16px;
      border-left: 4px solid #cbd5e1;
    }
    .diag-card.strength { border-left-color: var(--accent-green); }
    .diag-card.watch { border-left-color: var(--accent-amber); }
    .diag-card.priority { border-left-color: var(--primary-navy); }

    .diag-card-title {
      font-size: 12.5px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      margin-bottom: 10px;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    .strength .diag-card-title { color: var(--accent-green); }
    .watch .diag-card-title { color: var(--accent-amber); }
    .priority .diag-card-title { color: var(--primary-navy); }

    .diag-list {
      list-style: none;
      font-size: 12.5px;
      color: #334155;
    }
    .diag-list li {
      margin-bottom: 6px;
      position: relative;
      padding-left: 14px;
    }
    .diag-list li::before {
      content: '•';
      position: absolute;
      left: 0;
      color: var(--text-muted);
      font-weight: bold;
    }

    /* Standard Card Container */
    .analytics-card {
      background: var(--bg-card);
      border: 1px solid var(--border-color);
      border-radius: 6px;
      padding: 18px 20px;
      margin-bottom: 20px;
      box-shadow: var(--shadow-sm);
    }
    .analytics-card-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 14px;
      padding-bottom: 10px;
      border-bottom: 1px solid var(--border-subtle);
    }
    .card-title-group h3 {
      font-size: 14px;
      font-weight: 700;
      color: var(--primary-navy);
    }
    .card-title-group p {
      font-size: 11.5px;
      color: var(--text-muted);
    }

    /* Grid Layouts */
    .grid-2 {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 18px;
    }
    .grid-3 {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }
    @media (max-width: 1024px) {
      .grid-2, .grid-3 { grid-template-columns: 1fr; }
    }

    /* Tables */
    .table-responsive {
      overflow-x: auto;
    }
    table.data-table {
      width: 100%;
      border-collapse: collapse;
      font-size: 12.5px;
      text-align: left;
    }
    table.data-table th {
      background: #f8fafc;
      color: #475569;
      font-weight: 600;
      padding: 9px 12px;
      border-bottom: 2px solid var(--border-color);
      white-space: nowrap;
    }
    table.data-table td {
      padding: 9px 12px;
      border-bottom: 1px solid var(--border-subtle);
      color: #1e293b;
    }
    table.data-table tr:hover td {
      background-color: #f8fafc;
    }

    /* Badges & Status */
    .status-pill {
      display: inline-flex;
      align-items: center;
      gap: 4px;
      padding: 2px 8px;
      border-radius: 12px;
      font-size: 11px;
      font-weight: 600;
    }
    .status-pill.green { background: var(--accent-green-light); color: var(--accent-green); }
    .status-pill.amber { background: var(--accent-amber-light); color: var(--accent-amber); }
    .status-pill.red { background: var(--accent-red-light); color: var(--accent-red); }
    .status-pill.blue { background: var(--accent-blue-light); color: var(--accent-blue); }

    /* Ask Data Assistant */
    .ask-assistant-box {
      background: #ffffff;
      border: 1px solid #cbd5e1;
      border-radius: 6px;
      padding: 14px 18px;
      margin-bottom: 22px;
    }
    .ask-input-row {
      display: flex;
      gap: 10px;
    }
    .ask-input-row input {
      flex: 1;
      border: 1px solid var(--border-color);
      border-radius: 4px;
      padding: 8px 12px;
      font-size: 13px;
      outline: none;
    }
    .ask-input-row input:focus {
      border-color: var(--primary-navy);
    }
    .ask-response-box {
      margin-top: 10px;
      padding: 10px 14px;
      background: #f1f5f9;
      border-left: 3px solid var(--accent-green);
      border-radius: 4px;
      font-size: 12.5px;
      color: #1e293b;
      display: none;
    }

    /* Recruiter 2x2 Matrix */
    .matrix-container {
      display: grid;
      grid-template-columns: 1fr 1fr;
      grid-template-rows: 1fr 1fr;
      gap: 10px;
      min-height: 380px;
      background: #f8fafc;
      padding: 10px;
      border: 1px dashed #cbd5e1;
      border-radius: 6px;
      position: relative;
    }
    .matrix-quadrant {
      background: #ffffff;
      border: 1px solid var(--border-color);
      border-radius: 4px;
      padding: 12px;
      display: flex;
      flex-direction: column;
    }
    .matrix-quadrant h4 {
      font-size: 12px;
      font-weight: 700;
      color: var(--primary-navy);
      display: flex;
      justify-content: space-between;
      border-bottom: 1px solid var(--border-subtle);
      padding-bottom: 4px;
      margin-bottom: 8px;
    }
    .matrix-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
    }
    .recruiter-tag {
      font-size: 11px;
      background: #f1f5f9;
      border: 1px solid #e2e8f0;
      padding: 3px 6px;
      border-radius: 3px;
      color: #334155;
    }

    /* Recommendations & Governance */
    .recommendation-item {
      background: #ffffff;
      border: 1px solid var(--border-color);
      border-radius: 6px;
      padding: 16px;
      margin-bottom: 12px;
      display: flex;
      flex-direction: column;
      gap: 8px;
    }
    .rec-top {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .rec-title {
      font-size: 14px;
      font-weight: 700;
      color: var(--primary-navy);
    }
    .rec-meta {
      display: flex;
      gap: 16px;
      font-size: 11.5px;
      color: var(--text-muted);
      margin-top: 4px;
    }

    /* Footer */
    footer.institutional-footer {
      background-color: #ffffff;
      border-top: 1px solid var(--border-color);
      padding: 16px 28px;
      font-size: 11.5px;
      color: var(--text-muted);
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: auto;
    }

    /* Print Stylesheet */
    @media print {
      aside.sidebar, .demo-disclaimer-banner, .header-controls, .global-filter-strip, .ask-assistant-box {
        display: none !important;
      }
      .app-container { display: block; }
      .view-container { display: block !important; padding: 0; }
    }
  </style>
</head>
<body>

  <!-- Data Authenticity Protocol Banner -->
  <div class="demo-disclaimer-banner">
    <div>
      <i data-lucide="info" style="width: 14px; height: 14px; vertical-align: middle; margin-right: 4px;"></i>
      <strong>Institutional MIS Notice:</strong> Demonstration dataset active for analytical evaluation. Replace with validated DMI Placement Cell archives for official reporting.
    </div>
    <div>
      <span>Role: <strong>Placement Coordinator</strong></span>
      <span style="margin-left: 12px;">Institute: <strong>DMI Patna (Est. 2014)</strong></span>
    </div>
  </div>

  <div class="app-container">
    
    <!-- Left Navigation Sidebar -->
    <aside class="sidebar">
      <div class="sidebar-brand">
        <div class="brand-mark">DMI</div>
        <div>
          <div class="brand-title">Placement Intel</div>
          <div class="brand-sub">Decision Support System</div>
        </div>
      </div>

      <div class="nav-section">
        <div class="nav-section-title">Overview</div>
        <a class="nav-item active" onclick="switchTab('tab-executive')">
          <i data-lucide="layout-dashboard"></i> Executive Overview
        </a>
      </div>

      <div class="nav-section">
        <div class="nav-section-title">Diagnostics</div>
        <a class="nav-item" onclick="switchTab('tab-diagnostics')">
          <i data-lucide="bar-chart-2"></i> Placement Diagnostics
        </a>
        <a class="nav-item" onclick="switchTab('tab-skills')">
          <i data-lucide="cpu"></i> Skill Gap Analysis
        </a>
        <a class="nav-item" onclick="switchTab('tab-interview')">
          <i data-lucide="git-merge"></i> Interview Analytics
        </a>
        <a class="nav-item" onclick="switchTab('tab-student')">
          <i data-lucide="user-check"></i> Student Diagnostic
        </a>
      </div>

      <div class="nav-section">
        <div class="nav-section-title">Market Intelligence</div>
        <a class="nav-item" onclick="switchTab('tab-recruiters')">
          <i data-lucide="briefcase"></i> Recruiter Intelligence
        </a>
        <a class="nav-item" onclick="switchTab('tab-sectors')">
          <i data-lucide="pie-chart"></i> Sector Hiring Trends
        </a>
      </div>

      <div class="nav-section">
        <div class="nav-section-title">Academic & Network</div>
        <a class="nav-item" onclick="switchTab('tab-curriculum')">
          <i data-lucide="book-open"></i> Curriculum Alignment
        </a>
        <a class="nav-item" onclick="switchTab('tab-alumni')">
          <i data-lucide="network"></i> Alumni Intelligence
        </a>
      </div>

      <div class="nav-section">
        <div class="nav-section-title">Governance</div>
        <a class="nav-item" onclick="switchTab('tab-recommendations')">
          <i data-lucide="compass"></i> Placement Strategy
        </a>
        <a class="nav-item" onclick="switchTab('tab-governance')">
          <i data-lucide="shield-check"></i> Data Quality
        </a>
      </div>
    </aside>

    <!-- Main Dynamic Area -->
    <main class="main-content">
      
      <!-- Top Institutional Header -->
      <header class="dashboard-header">
        <div class="header-titles">
          <h1 id="page-heading">Placement Intelligence — Executive Overview</h1>
          <p id="page-subheading">Development Management Institute (DMI), Patna • Post-Graduate Programme in Development Management (PDM)</p>
        </div>

        <div class="header-controls">
          <div class="filter-badge">
            <span>Cycle:</span>
            <select id="header-cycle-select" onchange="applyGlobalFilters()">
              <option value="2026">Placements 2026 (Ongoing)</option>
              <option value="2025" selected>2024–25 (PDM 12)</option>
              <option value="2024">2023–24 (PDM 11)</option>
              <option value="2023">2022–23 (PDM 10)</option>
            </select>
          </div>

          <button class="btn btn-outline" onclick="window.print()">
            <i data-lucide="printer"></i> Print MIS
          </button>
          <button class="btn btn-primary" onclick="exportCSVData()">
            <i data-lucide="download"></i> Export Data
          </button>
        </div>
      </header>

      <!-- Global Filter Strip -->
      <div class="global-filter-strip">
        <div class="filter-item">
          <label>Cohort:</label>
          <select id="global-batch" onchange="applyGlobalFilters()">
            <option value="ALL">All Cohorts (PDM 10–12)</option>
            <option value="PDM12" selected>PDM 12 (Current)</option>
            <option value="PDM11">PDM 11</option>
            <option value="PDM10">PDM 10</option>
          </select>
        </div>
        <div class="filter-item">
          <label>Sector Domain:</label>
          <select id="global-sector" onchange="applyGlobalFilters()">
            <option value="ALL">All Development Sectors</option>
            <option value="Livelihoods">Livelihoods & Collectives</option>
            <option value="RuralDev">Rural Dev & Parastatals</option>
            <option value="CSR">CSR Foundations</option>
            <option value="Microfinance">Financial Inclusion / MFI</option>
            <option value="Consulting">Development Consulting & Data</option>
          </select>
        </div>
        <div class="filter-item">
          <label>View Mode:</label>
          <select id="global-role-view">
            <option>Placement Cell (Full Access)</option>
            <option>Faculty & Curriculum Committee</option>
            <option>Institute Leadership</option>
          </select>
        </div>
        <button class="btn btn-outline" style="padding: 3px 8px; font-size: 11px;" onclick="resetFilters()">Reset Filters</button>
      </div>

      <!-- VIEW 1: EXECUTIVE OVERVIEW -->
      <div id="tab-executive" class="view-container active">
        
        <!-- Ask the Data Component -->
        <div class="ask-assistant-box">
          <div style="font-size: 12px; font-weight: 700; color: var(--primary-navy); margin-bottom: 6px;">
            <i data-lucide="sparkles" style="width: 14px; height: 14px; vertical-align: middle; color: var(--accent-green);"></i> Ask Placement Decision Assistant
          </div>
          <div class="ask-input-row">
            <input type="text" id="nl-query-input" placeholder="e.g., Why did interview conversion decline? | Which skills are critical in CSR? | Top repeat recruiters?" />
            <button class="btn btn-primary" onclick="handleNLQuery()">Analyze</button>
          </div>
          <div id="nl-query-response" class="ask-response-box"></div>
        </div>

        <!-- 8 Core KPI Cards -->
        <div class="kpi-grid">
          <div class="kpi-card accent-green">
            <div class="kpi-label">Placement Rate</div>
            <div class="kpi-value" id="kpi-placement-rate">94.0%</div>
            <div class="kpi-sub positive">↑ +3.8 pp vs PDM 11</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">Students Placed</div>
            <div class="kpi-value" id="kpi-students-placed">47 / 50</div>
            <div class="kpi-sub">3 in final stage interview</div>
          </div>
          <div class="kpi-card accent-blue">
            <div class="kpi-label">Active Recruiters</div>
            <div class="kpi-value" id="kpi-active-recruiters">28</div>
            <div class="kpi-sub">Across 7 social sectors</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">New Recruiters</div>
            <div class="kpi-value">8</div>
            <div class="kpi-sub positive">28.5% new organization rate</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">Repeat Recruiter Rate</div>
            <div class="kpi-value">60.7%</div>
            <div class="kpi-sub">17 continuous partners</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">Interview Conversion</div>
            <div class="kpi-value" id="kpi-conversion-rate">31.8%</div>
            <div class="kpi-sub warning">↓ -2.4 pp in Case rounds</div>
          </div>
          <div class="kpi-card accent-amber">
            <div class="kpi-label">Critical Skill Gaps</div>
            <div class="kpi-value">4 Areas</div>
            <div class="kpi-sub warning">Advanced Excel, Power BI, Case M&E</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">Data Completeness</div>
            <div class="kpi-value">88.4%</div>
            <div class="kpi-sub positive">Governance score verified</div>
          </div>
        </div>

        <!-- Diagnostic Insights Trio -->
        <div class="diagnostic-trio">
          <div class="diag-card strength">
            <div class="diag-card-title"><i data-lucide="check-circle-2" style="width: 16px;"></i> What is Working Well</div>
            <ul class="diag-list">
              <li><strong>High Field Immersion Traction:</strong> Development Immersion (DI) and Enterprise Learning (EL) give graduates a strong edge in grassroots project roles.</li>
              <li><strong>Sustained Parastatal & Livelihood Demand:</strong> High intent from state rural livelihood missions and national producer collectives.</li>
              <li><strong>Repeat Recruiter Loyalty:</strong> 61% of participating agencies returned for subsequent hiring rounds.</li>
            </ul>
          </div>
          <div class="diag-card watch">
            <div class="diag-card-title"><i data-lucide="alert-triangle" style="width: 16px;"></i> What Needs Attention</div>
            <ul class="diag-list">
              <li><strong>Uneven Analytical Proficiency:</strong> Significant variance in spreadsheet modeling and Power BI during technical screenings.</li>
              <li><strong>Case Rejection Concentration:</strong> 42% of final-round interview rejections cite structured problem-solving gaps in case interviews.</li>
              <li><strong>Sector Concentration Risk:</strong> Top 3 development domains account for over 68% of cumulative offers.</li>
            </ul>
          </div>
          <div class="diag-card priority">
            <div class="diag-card-title"><i data-lucide="target" style="width: 16px;"></i> Strategic Next Steps</div>
            <ul class="diag-list">
              <li><strong>Pre-Placement Analytics Bootcamp:</strong> Deploy intensive 4-week Excel + M&E Dashboard module before PDM 13 campus drive.</li>
              <li><strong>Account Management for Key Partners:</strong> Institute formal key-account dialogue with long-standing mission partners.</li>
              <li><strong>Alumni-in-Residence Mock Clinics:</strong> Deploy domain alumni for structured social sector case prep.</li>
            </ul>
          </div>
        </div>

        <!-- Charts Grid -->
        <div class="grid-2">
          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Recruitment by Sector Demand</h3>
                <p>Offers distributed across development management domains</p>
              </div>
            </div>
            <div style="height: 250px;">
              <canvas id="chartExecSector"></canvas>
            </div>
          </div>

          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Placement Progression Funnel</h3>
                <p>Applications through Shortlists, Interviews, Offers and Acceptances</p>
              </div>
            </div>
            <div style="height: 250px;">
              <canvas id="chartExecFunnel"></canvas>
            </div>
          </div>
        </div>
      </div>

      <!-- VIEW 2: PLACEMENT DIAGNOSTICS -->
      <div id="tab-diagnostics" class="view-container">
        <div class="section-head">
          <h2>Placement Diagnostics & Outcome Matrix</h2>
          <p>Multi-dimensional analysis of recruitment conversion and sectoral health</p>
        </div>

        <div class="grid-2">
          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Historical Placement Rate Trend (% Placed)</h3>
                <p>Three-year cohort trajectory across PDM batches</p>
              </div>
            </div>
            <div style="height: 240px;">
              <canvas id="chartDiagTrend"></canvas>
            </div>
          </div>

          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Conversion Efficiency by Sector</h3>
                <p>Ratio of total interviews completed to final offers accepted</p>
              </div>
            </div>
            <div style="height: 240px;">
              <canvas id="chartDiagConversion"></canvas>
            </div>
          </div>
        </div>

        <!-- Diagnostic Table -->
        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Comprehensive Cohort Outcome Matrix</h3>
              <p>Granular diagnostics broken down by domain and experiential learning background</p>
            </div>
          </div>
          <div class="table-responsive">
            <table class="data-table">
              <thead>
                <tr>
                  <th>Sector Domain</th>
                  <th>Eligible Students</th>
                  <th>Applications</th>
                  <th>Shortlisted</th>
                  <th>Offers Made</th>
                  <th>Placement Rate</th>
                  <th>Health Status</th>
                  <th>Prescribed Action</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td><strong>Livelihoods & Collectives</strong></td>
                  <td>18</td>
                  <td>64</td>
                  <td>32</td>
                  <td>17</td>
                  <td>94.4%</td>
                  <td><span class="status-pill green">🟢 Strong</span></td>
                  <td>Maintain active relationship with state federations</td>
                </tr>
                <tr>
                  <td><strong>Rural Development & Missions</strong></td>
                  <td>14</td>
                  <td>52</td>
                  <td>26</td>
                  <td>13</td>
                  <td>92.8%</td>
                  <td><span class="status-pill green">🟢 Strong</span></td>
                  <td>Expand project management immersion electives</td>
                </tr>
                <tr>
                  <td><strong>CSR Foundations</strong></td>
                  <td>8</td>
                  <td>38</td>
                  <td>14</td>
                  <td>6</td>
                  <td>75.0%</td>
                  <td><span class="status-pill amber">🟡 Watch</span></td>
                  <td>Enhance corporate ESG and proposal writing rigor</td>
                </tr>
                <tr>
                  <td><strong>Financial Inclusion / MFI</strong></td>
                  <td>6</td>
                  <td>24</td>
                  <td>11</td>
                  <td>5</td>
                  <td>83.3%</td>
                  <td><span class="status-pill green">🟢 Strong</span></td>
                  <td>Align rural banking & credit risk modules</td>
                </tr>
                <tr>
                  <td><strong>Development Data & Consulting</strong></td>
                  <td>4</td>
                  <td>28</td>
                  <td>8</td>
                  <td>3</td>
                  <td>75.0%</td>
                  <td><span class="status-pill red">🔴 Intervention</span></td>
                  <td>Reinforce Advanced Excel, Power BI, Stata/R proficiency</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- VIEW 3: SKILL GAP ANALYSIS -->
      <div id="tab-skills" class="view-container">
        <div class="section-head">
          <h2>Skill Demand vs. Student Proficiency Analysis</h2>
          <p>Direct comparison of employer JD requirements against validated student competency indices (1.0 to 5.0 scale)</p>
        </div>

        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Employer Demand vs. Student Proficiency</h3>
              <p>Grouped evaluation identifying institutional training deficits</p>
            </div>
          </div>
          <div style="height: 320px;">
            <canvas id="chartSkillGaps"></canvas>
          </div>
        </div>

        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Priority Skill Index (Gap × Employer Demand)</h3>
              <p>Mathematically prioritized skill interventions for immediate curriculum & workshop allocation</p>
            </div>
          </div>
          <div class="table-responsive">
            <table class="data-table">
              <thead>
                <tr>
                  <th>Competency Domain</th>
                  <th>Employer Demand (1-5)</th>
                  <th>Student Proficiency (1-5)</th>
                  <th>Deficit Gap</th>
                  <th>Priority Index</th>
                  <th>Strategic Priority</th>
                  <th>Recommended Intervention</th>
                </tr>
              </thead>
              <tbody id="skill-priority-table-body">
                <!-- Dynamically populated -->
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- VIEW 4: INTERVIEW ANALYTICS -->
      <div id="tab-interview" class="view-container">
        <div class="section-head">
          <h2>Interview Analytics & Root-Cause Rejection Diagnostics</h2>
          <p>Deconstructing candidate attrition across evaluation rounds to prevent recurring bottlenecks</p>
        </div>

        <div class="grid-2">
          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Primary Rejection Root Causes (Pareto Breakdown)</h3>
                <p>Categorized feedback from participating recruiters</p>
              </div>
            </div>
            <div style="height: 250px;">
              <canvas id="chartRejectionPareto"></canvas>
            </div>
          </div>

          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Stage-wise Attrition Funnel</h3>
                <p>Conversion leakage across recruitment stages</p>
              </div>
            </div>
            <div style="height: 250px;">
              <canvas id="chartStageAttrition"></canvas>
            </div>
          </div>
        </div>

        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Rejection Risk Matrix by Skill & Interview Stage</h3>
              <p>Illustrative diagnostic mapping of where deficits lead to candidate drop-out</p>
            </div>
          </div>
          <div class="table-responsive">
            <table class="data-table">
              <thead>
                <tr>
                  <th>Competency Area</th>
                  <th>Resume Screening</th>
                  <th>Technical / Analytical Round</th>
                  <th>Case Study Presentation</th>
                  <th>HR / Leadership Fit</th>
                  <th>Vulnerability Level</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td><strong>Advanced Excel / Modeling</strong></td>
                  <td><span class="status-pill green">Low (5%)</span></td>
                  <td><span class="status-pill red">High (48%)</span></td>
                  <td><span class="status-pill amber">Med (22%)</span></td>
                  <td><span class="status-pill green">Low (0%)</span></td>
                  <td><span class="status-pill red">Critical Vulnerability</span></td>
                </tr>
                <tr>
                  <td><strong>Structured Problem Solving (Case)</strong></td>
                  <td><span class="status-pill green">Low (2%)</span></td>
                  <td><span class="status-pill amber">Med (18%)</span></td>
                  <td><span class="status-pill red">High (54%)</span></td>
                  <td><span class="status-pill green">Low (4%)</span></td>
                  <td><span class="status-pill red">Critical Vulnerability</span></td>
                </tr>
                <tr>
                  <td><strong>Executive Communication & Pitch</strong></td>
                  <td><span class="status-pill green">Low (4%)</span></td>
                  <td><span class="status-pill amber">Med (14%)</span></td>
                  <td><span class="status-pill amber">Med (28%)</span></td>
                  <td><span class="status-pill red">High (38%)</span></td>
                  <td><span class="status-pill amber">Moderate Risk</span></td>
                </tr>
                <tr>
                  <td><strong>Field / Development Domain Knowledge</strong></td>
                  <td><span class="status-pill green">Low (2%)</span></td>
                  <td><span class="status-pill green">Low (6%)</span></td>
                  <td><span class="status-pill green">Low (8%)</span></td>
                  <td><span class="status-pill green">Low (3%)</span></td>
                  <td><span class="status-pill green">Institutional Strength</span></td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- VIEW 5: STUDENT DIAGNOSTIC -->
      <div id="tab-student" class="view-container">
        <div class="section-head">
          <h2>Student Diagnostic & Employability Profile</h2>
          <p>Anonymized individual diagnostic profiles for targeted mentoring and remedial support</p>
        </div>

        <div class="analytics-card" style="padding: 14px 18px;">
          <div style="display: flex; gap: 12px; align-items: center; flex-wrap: wrap;">
            <label style="font-weight: 600;">Select Anonymized Student ID:</label>
            <select id="student-picker" onchange="renderStudentProfile()" style="padding: 6px 12px; border-radius: 4px; border: 1px solid var(--border-color); font-weight: 600;">
              <option value="PDM12-004">Student PDM12-004 (Livelihoods Track)</option>
              <option value="PDM12-019">Student PDM12-019 (Rural Analytics Track)</option>
              <option value="PDM12-031">Student PDM12-031 (CSR & M&E Track)</option>
              <option value="PDM12-044">Student PDM12-044 (Enterprise & Finance Track)</option>
            </select>
            <span class="status-pill blue" style="margin-left: auto;">Role-Restricted View</span>
          </div>
        </div>

        <div class="grid-2">
          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3 id="student-name-header">Student Profile — PDM12-004</h3>
                <p id="student-track-sub">Development Immersion: JEEViKA • Enterprise Learning: Milk Union</p>
              </div>
            </div>
            <div style="display: flex; flex-direction: column; gap: 12px; font-size: 13px;">
              <div style="display: flex; justify-content: space-between; border-bottom: 1px solid var(--border-subtle); padding-bottom: 6px;">
                <span style="color: var(--text-muted);">Academic Performance Band:</span>
                <strong>CGPA 7.85 / 10.0 (Top Quartile)</strong>
              </div>
              <div style="display: flex; justify-content: space-between; border-bottom: 1px solid var(--border-subtle); padding-bottom: 6px;">
                <span style="color: var(--text-muted);">Development Immersion Rating:</span>
                <strong style="color: var(--accent-green);">Outstanding (Field Grade: O)</strong>
              </div>
              <div style="display: flex; justify-content: space-between; border-bottom: 1px solid var(--border-subtle); padding-bottom: 6px;">
                <span style="color: var(--text-muted);">Interviews Attended:</span>
                <strong>3 Rounds (1 Offer Received)</strong>
              </div>
              <div style="display: flex; justify-content: space-between; border-bottom: 1px solid var(--border-subtle); padding-bottom: 6px;">
                <span style="color: var(--text-muted);">Illustrative Employability Index:</span>
                <strong style="color: var(--primary-navy); font-size: 16px;">84 / 100</strong>
              </div>
            </div>

            <div style="margin-top: 18px; padding-top: 14px; border-top: 1px solid var(--border-subtle);">
              <h4 style="font-size: 12.5px; font-weight: 700; margin-bottom: 6px;">Prescribed Career Action:</h4>
              <p style="font-size: 12px; color: var(--text-muted);" id="student-prescribed-action">
                Clear for high-complexity program management roles. Recommended to complete Power BI dashboard certification to access Tier-1 development consulting tracks.
              </p>
            </div>
          </div>

          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Competency Readiness Radar</h3>
                <p>Six-pillar diagnostic assessment</p>
              </div>
            </div>
            <div style="height: 250px;">
              <canvas id="chartStudentRadar"></canvas>
            </div>
          </div>
        </div>
      </div>

      <!-- VIEW 6: RECRUITER INTELLIGENCE -->
      <div id="tab-recruiters" class="view-container">
        <div class="section-head">
          <h2>Recruiter Intelligence & Relationship Matrix</h2>
          <p>Strategic portfolio mapping of verified historical and potential institutional recruiting partners</p>
        </div>

        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Recruiter Strategic Positioning (2×2 Matrix)</h3>
              <p>Relationship Strength vs. Long-term Hiring Potential</p>
            </div>
          </div>
          
          <div class="matrix-container">
            <div class="matrix-quadrant" style="border-top: 3px solid var(--accent-green);">
              <h4>Strategic Partners (High Strength, High Potential) <span class="status-pill green">Priority 1</span></h4>
              <p style="font-size: 11px; color: var(--text-muted); margin-bottom: 8px;">Key accounts requiring dedicated placement liaison.</p>
              <div class="matrix-tags">
                <span class="recruiter-tag">BRLPS (JEEViKA)</span>
                <span class="recruiter-tag">TechnoServe</span>
                <span class="recruiter-tag">Aga Khan Rural Support</span>
                <span class="recruiter-tag">COMFED (Sudha)</span>
                <span class="recruiter-tag">JSLPS</span>
              </div>
            </div>

            <div class="matrix-quadrant" style="border-top: 3px solid var(--accent-blue);">
              <h4>Growth Opportunities (Lower Engagement, High Potential) <span class="status-pill blue">Priority 2</span></h4>
              <p style="font-size: 11px; color: var(--text-muted); margin-bottom: 8px;">High-value targets to convert via alumni & leadership outreach.</p>
              <div class="matrix-tags">
                <span class="recruiter-tag">Tata Trusts</span>
                <span class="recruiter-tag">CARE India</span>
                <span class="recruiter-tag">Bill & Melinda Gates Fdn</span>
                <span class="recruiter-tag">Piramal Foundation</span>
              </div>
            </div>

            <div class="matrix-quadrant" style="border-top: 3px solid #64748b;">
              <h4>Maintain & Deepen (High Strength, Moderate Intake) <span class="status-pill">Maintain</span></h4>
              <p style="font-size: 11px; color: var(--text-muted); margin-bottom: 8px;">Consistent, specialized niche employers.</p>
              <div class="matrix-tags">
                <span class="recruiter-tag">SRIJAN</span>
                <span class="recruiter-tag">Quest Alliance</span>
                <span class="recruiter-tag">Syngenta Foundation</span>
                <span class="recruiter-tag">FES</span>
              </div>
            </div>

            <div class="matrix-quadrant" style="border-top: 3px solid var(--accent-amber);">
              <h4>Re-Engage & Realign (Low Engagement, Moderate Potential) <span class="status-pill amber">Re-engage</span></h4>
              <p style="font-size: 11px; color: var(--text-muted); margin-bottom: 8px;">Dormant recruiters with past hiring history.</p>
              <div class="matrix-tags">
                <span class="recruiter-tag">Maahi Milk Producer</span>
                <span class="recruiter-tag">NABARD Financial</span>
                <span class="recruiter-tag">PRADAN</span>
              </div>
            </div>
          </div>
        </div>

        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Recruiter Partner Diagnostic Portfolio</h3>
              <p>Illustrative metrics based on engagement longevity and hiring volume</p>
            </div>
          </div>
          <div class="table-responsive">
            <table class="data-table">
              <thead>
                <tr>
                  <th>Recruiter / Agency</th>
                  <th>Primary Sector</th>
                  <th>Engagement History</th>
                  <th>Total Hired (Demo)</th>
                  <th>Conversion Rate</th>
                  <th>Relationship Score</th>
                  <th>Account Status</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td><strong>BRLPS (JEEViKA)</strong></td>
                  <td>State Livelihood Mission</td>
                  <td>6+ Seasons</td>
                  <td>24 Students</td>
                  <td>42%</td>
                  <td><strong>94 / 100</strong></td>
                  <td><span class="status-pill green">Strategic Anchor</span></td>
                </tr>
                <tr>
                  <td><strong>TechnoServe</strong></td>
                  <td>Enterprise / Agribusiness</td>
                  <td>4 Seasons</td>
                  <td>11 Students</td>
                  <td>34%</td>
                  <td><strong>88 / 100</strong></td>
                  <td><span class="status-pill green">Strategic Partner</span></td>
                </tr>
                <tr>
                  <td><strong>COMFED / Bihar Milk Federation</strong></td>
                  <td>Cooperative / Dairy</td>
                  <td>5 Seasons</td>
                  <td>14 Students</td>
                  <td>45%</td>
                  <td><strong>89 / 100</strong></td>
                  <td><span class="status-pill green">Strategic Partner</span></td>
                </tr>
                <tr>
                  <td><strong>Tata Trusts / CInI</strong></td>
                  <td>CSR Foundation</td>
                  <td>2 Seasons</td>
                  <td>5 Students</td>
                  <td>28%</td>
                  <td><strong>76 / 100</strong></td>
                  <td><span class="status-pill blue">High Potential</span></td>
                </tr>
                <tr>
                  <td><strong>Quest Alliance</strong></td>
                  <td>Youth & Skill Dev</td>
                  <td>3 Seasons</td>
                  <td>7 Students</td>
                  <td>31%</td>
                  <td><strong>79 / 100</strong></td>
                  <td><span class="status-pill">Maintain Account</span></td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- VIEW 7: SECTOR HIRING TRENDS -->
      <div id="tab-sectors" class="view-container">
        <div class="section-head">
          <h2>Development Sector Hiring Trends</h2>
          <p>Longitudinal shifts in demand across social enterprises, state missions, and funding foundations</p>
        </div>

        <div class="grid-2">
          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Sector Trajectory Trends (3-Year YoY Intake)</h3>
                <p>Tracking shifts from traditional NGOs to data-driven development</p>
              </div>
            </div>
            <div style="height: 250px;">
              <canvas id="chartSectorGrowth"></canvas>
            </div>
          </div>

          <div class="analytics-card">
            <div class="analytics-card-header">
              <div class="card-title-group">
                <h3>Role Demands by Sector Category</h3>
                <p>Functional role profile distribution</p>
              </div>
            </div>
            <div style="height: 250px;">
              <canvas id="chartRoleDist"></canvas>
            </div>
          </div>
        </div>
      </div>

      <!-- VIEW 8: CURRICULUM ALIGNMENT -->
      <div id="tab-curriculum" class="view-container">
        <div class="section-head">
          <h2>Curriculum & Employability Pathway Alignment</h2>
          <p>Aligning academic courses, experiential learning (DI / EL / MI), and certifications with industry demand</p>
        </div>

        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Course-to-Market Alignment Index</h3>
              <p>Curriculum Alignment Score = Employer Skill Demand × Course Skill Coverage × Student Proficiency</p>
            </div>
          </div>
          <div class="table-responsive">
            <table class="data-table">
              <thead>
                <tr>
                  <th>Course / Academic Module</th>
                  <th>Core Skills Imparted</th>
                  <th>Skill Coverage (1-5)</th>
                  <th>Market Demand (1-5)</th>
                  <th>Alignment Score</th>
                  <th>Action Recommendation</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td><strong>Monitoring, Evaluation & Learning (MEL)</strong></td>
                  <td>Results Framework, Quantitative Survey, LogFrame</td>
                  <td>4.5</td>
                  <td>4.7</td>
                  <td><strong style="color: var(--accent-green);">94%</strong></td>
                  <td>Integrate real-world KoboToolbox / Power BI datasets</td>
                </tr>
                <tr>
                  <td><strong>Managing Cooperatives & FPOs</strong></td>
                  <td>Governance, Agribusiness Value Chains, Collectives</td>
                  <td>4.7</td>
                  <td>4.6</td>
                  <td><strong style="color: var(--accent-green);">96%</strong></td>
                  <td>Benchmark against national producer company best practices</td>
                </tr>
                <tr>
                  <td><strong>Data Analytics & MIS in Development</strong></td>
                  <td>Advanced Excel, BI Dashboards, Spatial Basics</td>
                  <td>3.6</td>
                  <td>4.8</td>
                  <td><strong style="color: var(--accent-amber);">75%</strong></td>
                  <td>Add 15 hours of practical spreadsheet case labs</td>
                </tr>
                <tr>
                  <td><strong>Social Finance & Financial Inclusion</strong></td>
                  <td>MFI Modeling, Credit Appraisal, SHG Bank Linkage</td>
                  <td>4.2</td>
                  <td>4.1</td>
                  <td><strong style="color: var(--accent-green);">86%</strong></td>
                  <td>Include digital public infrastructure (DPI) & fintech cases</td>
                </tr>
                <tr>
                  <td><strong>CSR Management & ESG Strategy</strong></td>
                  <td>Schedule VII Compliance, ESG Metrics, Impact Audits</td>
                  <td>3.8</td>
                  <td>4.4</td>
                  <td><strong style="color: var(--accent-amber);">83%</strong></td>
                  <td>Introduce corporate partner live consulting projects</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- VIEW 9: ALUMNI INTELLIGENCE -->
      <div id="tab-alumni" class="view-container">
        <div class="section-head">
          <h2>Alumni Intelligence & Placement Network</h2>
          <p>Mobilizing alumni in senior positions across the development management ecosystem</p>
        </div>

        <div class="kpi-grid">
          <div class="kpi-card">
            <div class="kpi-label">Alumni Mapped</div>
            <div class="kpi-value">340+</div>
            <div class="kpi-sub">Across 10 Cohorts</div>
          </div>
          <div class="kpi-card accent-green">
            <div class="kpi-label">In Key Dev Roles</div>
            <div class="kpi-value">84%</div>
            <div class="kpi-sub">Leadership & Specialists</div>
          </div>
          <div class="kpi-card accent-blue">
            <div class="kpi-label">Alumni in Hiring Orgs</div>
            <div class="kpi-value">42 Orgs</div>
            <div class="kpi-sub">High referral potential</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">Mentor Volunteers</div>
            <div class="kpi-value">38 Active</div>
            <div class="kpi-sub">Supporting Mock Interviews</div>
          </div>
        </div>

        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Alumni Network Mapping (Illustrative Anonymized Sample)</h3>
              <p>Key alumni positions and recruiter conversion readiness</p>
            </div>
          </div>
          <div class="table-responsive">
            <table class="data-table">
              <thead>
                <tr>
                  <th>Alumni ID</th>
                  <th>Cohort</th>
                  <th>Organization Type</th>
                  <th>Designation Level</th>
                  <th>Location</th>
                  <th>Recruitment Potential</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>Alumnus A-014</td>
                  <td>PDM 03</td>
                  <td>State Livelihoods Mission</td>
                  <td>State Project Manager</td>
                  <td>Patna, Bihar</td>
                  <td><span class="status-pill green">Active Recruiter Anchor</span></td>
                </tr>
                <tr>
                  <td>Alumnus A-052</td>
                  <td>PDM 05</td>
                  <td>International NGO</td>
                  <td>Lead - Program Evaluation</td>
                  <td>New Delhi</td>
                  <td><span class="status-pill green">High Potential Partner</span></td>
                </tr>
                <tr>
                  <td>Alumnus A-089</td>
                  <td>PDM 07</td>
                  <td>National Dairy Enterprise</td>
                  <td>Manager - Rural Marketing</td>
                  <td>Anand, Gujarat</td>
                  <td><span class="status-pill blue">Internship Provider</span></td>
                </tr>
                <tr>
                  <td>Alumnus A-112</td>
                  <td>PDM 08</td>
                  <td>CSR Foundation</td>
                  <td>Senior Program Officer</td>
                  <td>Mumbai</td>
                  <td><span class="status-pill green">Campus Hiring Lead</span></td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>

      <!-- VIEW 10: RECOMMENDATIONS -->
      <div id="tab-recommendations" class="view-container">
        <div class="section-head">
          <h2>Placement Decision Support & Recommendations</h2>
          <p>Prescriptive action plans formulated from diagnostic findings</p>
        </div>

        <div class="recommendation-item" style="border-left: 4px solid var(--accent-red);">
          <div class="rec-top">
            <div class="rec-title">REC-01: Institute Mandatory 4-Week "Applied Excel & Development Analytics" Lab</div>
            <span class="status-pill red">HIGH PRIORITY • PDM 13</span>
          </div>
          <p style="font-size: 13px; color: #334155;">
            <strong>Diagnostic Evidence:</strong> Spreadsheet modeling and Power BI represent a -1.3 deficiency gap and account for 48% of second-round screening rejections.
          </p>
          <div class="rec-meta">
            <span><strong>Owner:</strong> Placement Cell + Quantitative Methods Area</span>
            <span><strong>Timeline:</strong> 4 Weeks Prior to Placement Drive</span>
            <span><strong>Target Outcome:</strong> Lift Technical Interview Conversion from 31% to &gt;45%</span>
          </div>
        </div>

        <div class="recommendation-item" style="border-left: 4px solid var(--accent-amber);">
          <div class="rec-top">
            <div class="rec-title">REC-02: Deploy Key Account Management for Top 10 Repeat Recruiters</div>
            <span class="status-pill amber">MEDIUM-HIGH PRIORITY</span>
          </div>
          <p style="font-size: 13px; color: #334155;">
            <strong>Diagnostic Evidence:</strong> 61% repeat recruiter rate generates 74% of total offers. Systematic relationship management protects baseline demand.
          </p>
          <div class="rec-meta">
            <span><strong>Owner:</strong> Chairperson - Placements & Corporate Relations</span>
            <span><strong>Timeline:</strong> Continuous</span>
            <span><strong>Target Outcome:</strong> 100% renewal of core development recruiters</span>
          </div>
        </div>

        <div class="recommendation-item" style="border-left: 4px solid var(--accent-green);">
          <div class="rec-top">
            <div class="rec-title">REC-03: Establish Structured Alumni-Led "Social Sector Case Interview" Clinics</div>
            <span class="status-pill green">SYSTEMIC ACTION</span>
          </div>
          <p style="font-size: 13px; color: #334155;">
            <strong>Diagnostic Evidence:</strong> Rejection analytics indicate structured case problem solving is the primary blocker in final-round conversions.
          </p>
          <div class="rec-meta">
            <span><strong>Owner:</strong> Alumni Committee + Placement Cell</span>
            <span><strong>Timeline:</strong> 6 Weekend Masterclasses</span>
            <span><strong>Target Outcome:</strong> Reduce Case Round Attrition by 20 pp</span>
          </div>
        </div>
      </div>

      <!-- VIEW 11: DATA GOVERNANCE -->
      <div id="tab-governance" class="view-container">
        <div class="section-head">
          <h2>Data Quality, Privacy & Governance</h2>
          <p>Audit scores monitoring data integrity, record completeness, and privacy compliance</p>
        </div>

        <div class="kpi-grid">
          <div class="kpi-card accent-green">
            <div class="kpi-label">Overall Data Quality</div>
            <div class="kpi-value">88.4%</div>
            <div class="kpi-sub positive">Verified Institutional Standard</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">Student Records</div>
            <div class="kpi-value">98.2%</div>
            <div class="kpi-sub">Complete Academic Profiles</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">Interview Feedback</div>
            <div class="kpi-value">74.5%</div>
            <div class="kpi-sub warning">Recruiter Notes Needed</div>
          </div>
          <div class="kpi-card">
            <div class="kpi-label">Alumni Telemetry</div>
            <div class="kpi-value">71.0%</div>
            <div class="kpi-sub">Designation update active</div>
          </div>
        </div>

        <div class="analytics-card">
          <div class="analytics-card-header">
            <div class="card-title-group">
              <h3>Data Governance & Privacy Policies</h3>
              <p>Strict confidentiality and data usage standards</p>
            </div>
          </div>
          <div style="font-size: 13px; color: #334155; line-height: 1.6;">
            <p><strong>1. Anonymization Protocol:</strong> Individual student records must be displayed strictly via anonymized identifiers (e.g., <code>PDM12-XXX</code>) on all dashboard analytics to protect candidate privacy.</p>
            <p style="margin-top: 8px;"><strong>2. Demonstration Mode Flag:</strong> When validated DMI placement archives are not loaded, analytical modules must display the mandatory demonstration disclaimer.</p>
            <p style="margin-top: 8px;"><strong>3. Role-Based Access:</strong> Detailed recruiter compensation metrics and candidate evaluation scores are restricted to authorized Placement Cell coordinators.</p>
          </div>
        </div>
      </div>

      <!-- Institutional Footer -->
      <footer class="institutional-footer">
        <div>
          <strong>Placement Intelligence Dashboard</strong> | Development Management Institute (DMI), Patna
          <br>
          <span style="font-size: 11px;">Autonomous Institution established in 2014 on the initiative of the Government of Bihar</span>
        </div>
        <div>
          <span style="display: inline-block; margin-right: 14px;">Data Note: Demonstration Prototype</span>
          <span>Security: Role-Governed Access</span>
        </div>
      </footer>

    </main>
  </div>

  <script>
    // ==========================================
    // 1. DATA REPOSITORY & DEMONSTRATION ENGINE
    // ==========================================
    const skillData = [
      { name: 'Advanced Excel / Modeling', demand: 4.8, prof: 3.2, category: 'Technical' },
      { name: 'Power BI / Dashboarding', demand: 4.4, prof: 3.1, category: 'Technical' },
      { name: 'Structured Case Problem Solving', demand: 4.6, prof: 3.4, category: 'Analytical' },
      { name: 'Field Research & M&E Design', demand: 4.7, prof: 4.4, category: 'Domain' },
      { name: 'Executive Communication & Pitch', demand: 4.5, prof: 3.6, category: 'Communication' },
      { name: 'Community Immersion & Mobilization', demand: 4.6, prof: 4.6, category: 'Domain' },
      { name: 'Financial Inclusion & Microfinance', demand: 4.1, prof: 3.9, category: 'Domain' },
      { name: 'Project Management & LogFrame', demand: 4.3, prof: 4.1, category: 'Management' }
    ];

    // Calculate priority indices
    skillData.forEach(item => {
      item.gap = parseFloat((item.demand - item.prof).toFixed(1));
      item.priorityIndex = parseFloat((item.gap * item.demand).toFixed(2));
    });
    // Sort descending by priority
    skillData.sort((a, b) => b.priorityIndex - a.priorityIndex);

    const studentProfiles = {
      'PDM12-004': {
        name: 'Student PDM12-004',
        track: 'Development Immersion: JEEViKA • Enterprise Learning: COMFED',
        cgpa: '7.85 / 10.0 (Top Quartile)',
        diGrade: 'Outstanding (Field Grade: O)',
        interviews: '3 Rounds (1 Offer Received)',
        index: '84 / 100',
        action: 'Clear for high-complexity program management roles. Recommended to complete Power BI dashboard certification to access Tier-1 development consulting tracks.',
        scores: [4.2, 4.8, 3.8, 4.5, 3.4, 4.6]
      },
      'PDM12-019': {
        name: 'Student PDM12-019',
        track: 'Development Immersion: JSLPS • Enterprise Learning: Agri-Producer Co.',
        cgpa: '8.40 / 10.0 (Top 5%)',
        diGrade: 'Outstanding (Field Grade: O+)',
        interviews: '2 Rounds (2 Offers Received)',
        index: '92 / 100',
        action: 'Strong analytical and field combination. Optimal candidate for state mission project lead or consulting associate roles.',
        scores: [4.8, 4.7, 4.5, 4.6, 4.2, 4.9]
      },
      'PDM12-031': {
        name: 'Student PDM12-031',
        track: 'Development Immersion: Aga Khan Foundation • Enterprise Learning: CSR Lead',
        cgpa: '7.10 / 10.0',
        diGrade: 'Very Good (Field Grade: A)',
        interviews: '4 Rounds (1 Offer Pending)',
        index: '76 / 100',
        action: 'Solid grassroots field execution. Needs immediate remedial coaching in structured case presentation and quantitative spreadsheets.',
        scores: [3.4, 4.5, 3.2, 4.1, 2.9, 4.2]
      },
      'PDM12-044': {
        name: 'Student PDM12-044',
        track: 'Development Immersion: NABARD Project • Enterprise Learning: MFI Pilot',
        cgpa: '7.60 / 10.0',
        diGrade: 'Excellent (Field Grade: A+)',
        interviews: '3 Rounds (1 Offer Received)',
        index: '81 / 100',
        action: 'High competency in financial appraisal and cooperative accounting. Recommended for social banking and livelihood finance portfolios.',
        scores: [4.0, 4.3, 3.9, 4.0, 3.7, 4.4]
      }
    };

    // ==========================================
    // 2. INITIALIZATION & CHART ENGINE
    // ==========================================
    let chartExecSector, chartExecFunnel, chartDiagTrend, chartDiagConversion;
    let chartSkillGaps, chartRejectionPareto, chartStageAttrition, chartStudentRadar;
    let chartSectorGrowth, chartRoleDist;

    document.addEventListener('DOMContentLoaded', () => {
      lucide.createIcons();
      renderSkillTable();
      initCharts();
      renderStudentProfile();
    });

    function renderSkillTable() {
      const tbody = document.getElementById('skill-priority-table-body');
      tbody.innerHTML = '';
      skillData.forEach(s => {
        let priorityTag = '';
        if (s.priorityIndex >= 5.0) {
          priorityTag = '<span class="status-pill red">🔴 High Priority</span>';
        } else if (s.priorityIndex >= 2.5) {
          priorityTag = '<span class="status-pill amber">🟡 Moderate Priority</span>';
        } else {
          priorityTag = '<span class="status-pill green">🟢 Low Deficit</span>';
        }

        let recAction = s.gap > 1.0 
          ? 'Mandatory 15-hr workshop lab' 
          : (s.gap > 0.4 ? 'Elective practice modules' : 'Maintain current syllabus');

        const tr = document.createElement('tr');
        tr.innerHTML = `
          <td><strong>${s.name}</strong></td>
          <td>${s.demand} / 5.0</td>
          <td>${s.prof} / 5.0</td>
          <td><strong style="color: ${s.gap > 0.8 ? 'var(--accent-red)' : 'var(--text-main)'};">-${s.gap}</strong></td>
          <td><strong>${s.priorityIndex}</strong></td>
          <td>${priorityTag}</td>
          <td>${recAction}</td>
        `;
        tbody.appendChild(tr);
      });
    }

    function initCharts() {
      // 1. Executive Sector Doughnut
      const ctxExecSector = document.getElementById('chartExecSector').getContext('2d');
      chartExecSector = new Chart(ctxExecSector, {
        type: 'doughnut',
        data: {
          labels: ['Livelihoods & Collectives', 'Rural Dev & Missions', 'CSR Foundations', 'Microfinance & Inclusive Banking', 'Dev Consulting & Data'],
          datasets: [{
            data: [36, 28, 14, 12, 10],
            backgroundColor: ['#162844', '#1a6b4b', '#2563eb', '#d97706', '#64748b'],
            borderWidth: 2,
            borderColor: '#ffffff'
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          plugins: {
            legend: { position: 'right', labels: { boxWidth: 12, font: { size: 11, family: 'Inter' } } }
          }
        }
      });

      // 2. Executive Funnel
      const ctxExecFunnel = document.getElementById('chartExecFunnel').getContext('2d');
      chartExecFunnel = new Chart(ctxExecFunnel, {
        type: 'bar',
        data: {
          labels: ['Applications', 'Shortlisted', 'Interviews', 'Final Offers', 'Accepted'],
          datasets: [{
            label: 'Candidate Count',
            data: [210, 118, 78, 49, 47],
            backgroundColor: '#1e3a5f',
            borderRadius: 4
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          plugins: { legend: { display: false } },
          scales: {
            y: { beginAtZero: true, grid: { color: '#f1f5f9' }, ticks: { font: { family: 'Inter' } } },
            x: { grid: { display: false }, ticks: { font: { family: 'Inter' } } }
          }
        }
      });

      // 3. Diagnostics Trend
      const ctxDiagTrend = document.getElementById('chartDiagTrend').getContext('2d');
      chartDiagTrend = new Chart(ctxDiagTrend, {
        type: 'line',
        data: {
          labels: ['PDM 09 (2021-22)', 'PDM 10 (2022-23)', 'PDM 11 (2023-24)', 'PDM 12 (2024-25)'],
          datasets: [{
            label: 'Placement Rate (%)',
            data: [96.0, 95.2, 90.2, 94.0],
            borderColor: '#1a6b4b',
            backgroundColor: 'rgba(26, 107, 75, 0.08)',
            fill: true,
            tension: 0.3,
            borderWidth: 2.5,
            pointRadius: 4
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          scales: {
            y: { min: 80, max: 100, ticks: { callback: v => v + '%' } }
          }
        }
      });

      // 4. Sector Conversion
      const ctxDiagConversion = document.getElementById('chartDiagConversion').getContext('2d');
      chartDiagConversion = new Chart(ctxDiagConversion, {
        type: 'bar',
        data: {
          labels: ['Livelihoods', 'State Missions', 'CSR', 'Financial Inc.', 'Consulting'],
          datasets: [{
            label: 'Interview to Offer Conversion Rate (%)',
            data: [53.1, 50.0, 42.8, 45.4, 37.5],
            backgroundColor: '#2563eb',
            borderRadius: 4
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          scales: { y: { beginAtZero: true, max: 70, ticks: { callback: v => v + '%' } } }
        }
      });

      // 5. Skill Gaps Bar Chart
      const ctxSkillGaps = document.getElementById('chartSkillGaps').getContext('2d');
      chartSkillGaps = new Chart(ctxSkillGaps, {
        type: 'bar',
        data: {
          labels: skillData.map(s => s.name),
          datasets: [
            {
              label: 'Employer Demand Rating (1-5)',
              data: skillData.map(s => s.demand),
              backgroundColor: '#162844',
              borderRadius: 3
            },
            {
              label: 'Student Assessed Proficiency (1-5)',
              data: skillData.map(s => s.prof),
              backgroundColor: '#34d399',
              borderRadius: 3
            }
          ]
        },
        options: {
          indexAxis: 'y',
          responsive: true,
          maintainAspectRatio: false,
          scales: {
            x: { min: 0, max: 5.0, ticks: { stepSize: 1.0 } }
          }
        }
      });

      // 6. Rejection Pareto
      const ctxRejectionPareto = document.getElementById('chartRejectionPareto').getContext('2d');
      chartRejectionPareto = new Chart(ctxRejectionPareto, {
        type: 'bar',
        data: {
          labels: ['Excel / Tech Screening', 'Structured Case Fit', 'Communication / Pitch', 'Domain Knowledge', 'Location Preference'],
          datasets: [{
            label: 'Share of Candidate Rejections (%)',
            data: [38, 29, 18, 10, 5],
            backgroundColor: '#b45309',
            borderRadius: 4
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          scales: { y: { beginAtZero: true, ticks: { callback: v => v + '%' } } }
        }
      });

      // 7. Stage Attrition Funnel
      const ctxStageAttrition = document.getElementById('chartStageAttrition').getContext('2d');
      chartStageAttrition = new Chart(ctxStageAttrition, {
        type: 'line',
        data: {
          labels: ['Applied (100%)', 'Resume Shortlist (56%)', 'Technical Assessment (37%)', 'Final Case Round (23%)', 'Selected (22.4%)'],
          datasets: [{
            label: 'Candidate Retention Rate (%)',
            data: [100, 56.2, 37.1, 23.3, 22.4],
            borderColor: '#991b1b',
            backgroundColor: 'rgba(153, 27, 27, 0.05)',
            fill: true,
            tension: 0.2,
            borderWidth: 2
          }]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          scales: { y: { beginAtZero: true, max: 100, ticks: { callback: v => v + '%' } } }
        }
      });

      // 8. Sector Longitudinal Trends
      const ctxSectorGrowth = document.getElementById('chartSectorGrowth').getContext('2d');
      chartSectorGrowth = new Chart(ctxSectorGrowth, {
        type: 'line',
        data: {
          labels: ['2022-23 (PDM 10)', '2023-24 (PDM 11)', '2024-25 (PDM 12)', '2025-26 (Projected)'],
          datasets: [
            { label: 'Livelihoods & Collectives', data: [14, 15, 17, 18], borderColor: '#162844', tension: 0.2 },
            { label: 'Rural Missions & Parastatals', data: [11, 12, 13, 14], borderColor: '#1a6b4b', tension: 0.2 },
            { label: 'CSR Foundations', data: [4, 5, 6, 8], borderColor: '#2563eb', tension: 0.2 },
            { label: 'Dev Data & Consulting', data: [1, 2, 3, 5], borderColor: '#d97706', tension: 0.2 }
          ]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          scales: { y: { beginAtZero: true, title: { display: true, text: 'Total Placed Candidates' } } }
        }
      });

      // 9. Role Distribution
      const ctxRoleDist = document.getElementById('chartRoleDist').getContext('2d');
      chartRoleDist = new Chart(ctxRoleDist, {
        type: 'bar',
        data: {
          labels: ['Livelihoods', 'State Missions', 'CSR', 'Fin Inclusion', 'Consulting'],
          datasets: [
            { label: 'Field Project Manager', data: [8, 6, 2, 1, 0], backgroundColor: '#162844' },
            { label: 'M&E / Program Specialist', data: [4, 4, 3, 1, 2], backgroundColor: '#1a6b4b' },
            { label: 'Value Chain / Enterprise Lead', data: [5, 3, 1, 3, 1], backgroundColor: '#2563eb' }
          ]
        },
        options: {
          responsive: true,
          maintainAspectRatio: false,
          scales: { x: { stacked: true }, y: { stacked: true, beginAtZero: true } }
        }
      });
    }

    // ==========================================
    // 3. STUDENT PROFILE DIAGNOSTIC LOGIC
    // ==========================================
    function renderStudentProfile() {
      const selectedId = document.getElementById('student-picker').value;
      const data = studentProfiles[selectedId];
      if (!data) return;

      document.getElementById('student-name-header').innerText = `Student Profile — ${selectedId}`;
      document.getElementById('student-track-sub').innerText = data.track;
      document.getElementById('student-prescribed-action').innerText = data.action;

      const radarData = {
        labels: ['Academic & Field', 'Analytical / Excel', 'Domain (Rural/M&E)', 'Case Formulation', 'Communication', 'Leadership / Immersion'],
        datasets: [{
          label: selectedId,
          data: data.scores,
          backgroundColor: 'rgba(26, 107, 75, 0.2)',
          borderColor: '#1a6b4b',
          pointBackgroundColor: '#1a6b4b',
          borderWidth: 2
        }]
      };

      if (chartStudentRadar) {
        chartStudentRadar.destroy();
      }

      const ctxStudentRadar = document.getElementById('chartStudentRadar').getContext('2d');
      chartStudentRadar = new Chart(ctxStudentRadar, {
        type: 'radar',
        data: radarData,
        options: {
          responsive: true,
          maintainAspectRatio: false,
          scales: {
            r: {
              angleLines: { color: '#e2e8f0' },
              grid: { color: '#e2e8f0' },
              suggestedMin: 0,
              suggestedMax: 5.0,
              ticks: { stepSize: 1.0 }
            }
          }
        }
      });
    }

    // ==========================================
    // 4. TAB SWITCHING & GLOBAL INTERACTION
    // ==========================================
    function switchTab(tabId) {
      document.querySelectorAll('.view-container').forEach(el => el.classList.remove('active'));
      document.querySelectorAll('.nav-item').forEach(el => el.classList.remove('active'));

      const targetView = document.getElementById(tabId);
      if (targetView) targetView.classList.add('active');

      const clickedNav = Array.from(document.querySelectorAll('.nav-item')).find(el => {
        const attr = el.getAttribute('onclick');
        return attr && attr.includes(tabId);
      });
      if (clickedNav) clickedNav.classList.add('active');

      // Update page headers dynamically
      const titleMap = {
        'tab-executive': { title: 'Placement Intelligence — Executive Overview', sub: 'A decision-support view of placement outcomes, employer demand and student employability' },
        'tab-diagnostics': { title: 'Placement Diagnostics & Outcome Matrix', sub: 'Understand where recruitment performance is strong, fragile, or requires intervention' },
        'tab-skills': { title: 'Skill Demand & Gap Analysis', sub: 'Direct diagnostic comparison of employer JD requirements against student competencies' },
        'tab-interview': { title: 'Interview Analytics & Rejection Diagnostics', sub: 'Root-cause deconstruction of candidate dropouts across evaluation rounds' },
        'tab-student': { title: 'Student Diagnostic & Employability Profile', sub: 'Anonymized competency indices for personalized intervention and mentoring' },
        'tab-recruiters': { title: 'Recruiter Intelligence & Relationship Matrix', sub: 'Strategic portfolio analysis of institutional hiring partners' },
        'tab-sectors': { title: 'Development Sector Hiring Trends', sub: 'Emerging sectoral trajectories and programmatic employment demand' },
        'tab-curriculum': { title: 'Curriculum & Employability Pathways', sub: 'Decision-support alignment connecting courses, electives, and employer requirements' },
        'tab-alumni': { title: 'Alumni Intelligence & Placement Network', sub: 'Mobilizing alumni working in senior social-sector roles for recruitment' },
        'tab-recommendations': { title: 'Placement Strategy Recommendations', sub: 'Actionable institutional directives with assigned owners and timelines' },
        'tab-governance': { title: 'Data Quality & Governance Audit', sub: 'Institutional data completeness, integrity scores, and privacy safeguards' }
      };

      if (titleMap[tabId]) {
        document.getElementById('page-heading').innerText = titleMap[tabId].title;
        document.getElementById('page-subheading').innerText = titleMap[tabId].sub;
      }

      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function applyGlobalFilters() {
      const batch = document.getElementById('global-batch').value;
      const sector = document.getElementById('global-sector').value;

      // Demonstrating dynamic reactive values
      if (batch === 'PDM11') {
        document.getElementById('kpi-placement-rate').innerText = '90.2%';
        document.getElementById('kpi-students-placed').innerText = '46 / 51';
        document.getElementById('kpi-conversion-rate').innerText = '29.4%';
      } else if (batch === 'PDM10') {
        document.getElementById('kpi-placement-rate').innerText = '95.2%';
        document.getElementById('kpi-students-placed').innerText = '40 / 42';
        document.getElementById('kpi-conversion-rate').innerText = '34.1%';
      } else {
        document.getElementById('kpi-placement-rate').innerText = '94.0%';
        document.getElementById('kpi-students-placed').innerText = '47 / 50';
        document.getElementById('kpi-conversion-rate').innerText = '31.8%';
      }
    }

    function resetFilters() {
      document.getElementById('global-batch').value = 'PDM12';
      document.getElementById('global-sector').value = 'ALL';
      document.getElementById('header-cycle-select').value = '2025';
      applyGlobalFilters();
    }

    // ==========================================
    // 5. "ASK THE DATA" NL ANALYTICS ENGINE
    // ==========================================
    function handleNLQuery() {
      const input = document.getElementById('nl-query-input').value.trim().toLowerCase();
      const respBox = document.getElementById('nl-query-response');
      
      if (!input) {
        respBox.style.display = 'none';
        return;
      }

      respBox.style.display = 'block';

      if (input.includes('conversion') || input.includes('decline') || input.includes('why')) {
        respBox.innerHTML = `<strong>Diagnostic Finding:</strong> Interview conversion declined by 2.4 percentage points primarily in the Consulting and CSR domains. The largest contributing factors in demonstration feedback were <em>Advanced Spreadsheet Modeling (48%)</em> and <em>Structured Case Solving (29%)</em>.`;
      } else if (input.includes('skill') || input.includes('gap')) {
        respBox.innerHTML = `<strong>Top Skill Gaps:</strong> The most significant gaps between employer demand and student proficiency are <strong>Advanced Excel / Modeling (-1.3 gap)</strong>, <strong>Power BI / Dashboards (-1.3 gap)</strong>, and <strong>Structured Case Problem Solving (-1.2 gap)</strong>.`;
      } else if (input.includes('recruiter') || input.includes('prioritize') || input.includes('partner')) {
        respBox.innerHTML = `<strong>Strategic Recruiter Priority:</strong> Institutional priority rests on deep anchors including <strong>BRLPS (JEEViKA)</strong>, <strong>TechnoServe</strong>, and <strong>COMFED</strong>, while growth engagement should target <strong>Tata Trusts</strong> and <strong>CARE India</strong>.`;
      } else if (input.includes('sector') || input.includes('grow')) {
        respBox.innerHTML = `<strong>Sector Growth Trend:</strong> Livelihood collectivities and state parastatals continue to absorb ~60% of graduates, while <strong>Development Data & Consulting</strong> has demonstrated a 150% growth rate over the past three cycles.`;
      } else {
        respBox.innerHTML = `<strong>Analytical Insight:</strong> For cohort <strong>PDM 12</strong>, overall placement health stands at <strong>94.0%</strong> with 28 active recruiters. Recommended immediate priority is deploying the 4-week Excel & Case workshop.`;
      }
    }

    // Allow Enter key to trigger Ask the Data
    document.getElementById('nl-query-input').addEventListener('keypress', function (e) {
      if (e.key === 'Enter') {
        handleNLQuery();
      }
    });

    // ==========================================
    // 6. CSV DATA EXPORT GENERATOR
    // ==========================================
    function exportCSVData() {
      let csvContent = "data:text/csv;charset=utf-8,";
      csvContent += "Competency_Domain,Employer_Demand,Student_Proficiency,Deficit_Gap,Priority_Index\n";
      
      skillData.forEach(row => {
        csvContent += `"${row.name}",${row.demand},${row.prof},${row.gap},${row.priorityIndex}\n`;
      });

      const encodedUri = encodeURI(csvContent);
      const link = document.createElement("a");
      link.setAttribute("href", encodedUri);
      link.setAttribute("download", "DMI_Patna_Placement_Analytics_Export.csv");
      document.body.appendChild(link);
      link.click();
      document.body.removeChild(link);
    }
  </script>
</body>
</html>
