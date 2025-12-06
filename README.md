<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Edward J. Rhee – Self-Growth in Motion</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="The luxury self-growth journey of Edward J. Rhee – Porsches, Rolex, travel, fitness, and intentional living." />
  <style>
    :root {
      --bg: #f6efe6;
      --bg-alt: #f3e6d7;
      --bg-soft: #fdf7ee;
      --text: #2b2118;
      --muted: #7c6b5b;
      --accent: #c8a96a;
      --accent-soft: rgba(200, 169, 106, 0.12);
      --accent-strong: #e2c58c;
      --border: rgba(0, 0, 0, 0.06);
      --glass: rgba(255, 255, 255, 0.78);
      --radius-lg: 18px;
      --radius-xl: 28px;
      --shadow-soft: 0 18px 40px rgba(0, 0, 0, 0.06);
      --shadow-subtle: 0 10px 24px rgba(0, 0, 0, 0.05);
      --transition-fast: 200ms ease-out;
    }

    /* NIGHT / FUTURISTIC THEME */
    body[data-theme="night"] {
      --bg: #08070b;
      --bg-alt: #101018;
      --bg-soft: #13121c;
      --text: #f8f4ee;
      --muted: #a39ab9;
      --accent: #f0c36a;
      --accent-soft: rgba(240, 195, 106, 0.18);
      --accent-strong: #ffda8b;
      --border: rgba(255, 255, 255, 0.06);
      --glass: rgba(20, 18, 32, 0.78);
      --shadow-soft: 0 18px 40px rgba(0, 0, 0, 0.7);
      --shadow-subtle: 0 10px 24px rgba(0, 0, 0, 0.6);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, system-ui, -apple-system, "SF Pro Text", "Helvetica Neue", sans-serif;
      background:
        radial-gradient(circle at top left, #fdf7ee 0, var(--bg) 35%, #f1e5d8 100%),
        radial-gradient(circle at bottom right, rgba(200, 169, 106, 0.14), transparent 60%);
      color: var(--text);
      -webkit-font-smoothing: antialiased;
      line-height: 1.6;
      transition: background 260ms ease-out, color 260ms ease-out;
    }

    body[data-theme="night"] {
      background:
        radial-gradient(circle at top left, #171522 0, var(--bg) 40%, #05040a 100%),
        radial-gradient(circle at top right, rgba(220, 186, 118, 0.12), transparent 60%);
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    img {
      max-width: 100%;
      display: block;
    }

    .page {
      max-width: 1120px;
      margin: 0 auto;
      padding: 24px 18px 64px;
    }

    /* HEADER */

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 14px;
      margin-bottom: 24px;
      border-radius: 999px;
      background: var(--glass);
      backdrop-filter: blur(18px) saturate(130%);
      -webkit-backdrop-filter: blur(18px) saturate(130%);
      box-shadow: var(--shadow-subtle);
      position: sticky;
      top: 14px;
      z-index: 20;
      border: 1px solid var(--border);
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .brand-mark {
      width: 30px;
      height: 30px;
      border-radius: 50%;
      background:
        conic-gradient(from 210deg, #fdf5e4, var(--accent), #9c7a40, #fdf5e4);
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fdf7ee;
      font-size: 11px;
      font-weight: 600;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      box-shadow: 0 8px 18px rgba(0, 0, 0, 0.35);
    }

    body[data-theme="night"] .brand-mark {
      box-shadow: 0 12px 24px rgba(0, 0, 0, 0.7);
    }

    .brand-text {
      display: flex;
      flex-direction: column;
    }

    .brand-title {
      font-size: 15px;
      font-weight: 600;
      letter-spacing: 0.08em;
      text-transform: uppercase;
    }

    .brand-subtitle {
      font-size: 11px;
      color: var(--muted);
      letter-spacing: 0.12em;
      text-transform: uppercase;
    }

    nav {
      display: flex;
      gap: 14px;
      font-size: 13px;
      color: var(--muted);
      align-items: center;
    }

    nav a {
      padding: 6px 10px;
      border-radius: 999px;
      transition: background var(--transition-fast), color var(--transition-fast), transform var(--transition-fast);
    }

    nav a:hover {
      background: rgba(0, 0, 0, 0.03);
      color: var(--text);
      transform: translateY(-1px);
    }

    body[data-theme="night"] nav a:hover {
      background: rgba(255, 255, 255, 0.04);
    }

    .nav-cta {
      padding: 6px 12px;
      border-radius: 999px;
      border: 1px solid rgba(200, 169, 106, 0.5);
      background: linear-gradient(120deg, #fdf8f0, #f6ebdc);
      color: var(--text);
      font-weight: 500;
      box-shadow: 0 8px 18px rgba(200, 169, 106, 0.22);
    }

    body[data-theme="night"] .nav-cta {
      background: radial-gradient(circle at top left, rgba(240, 195, 106, 0.18), rgba(10, 8, 30, 1));
      color: #f8f4ee;
      border-color: rgba(240, 195, 106, 0.5);
      box-shadow: 0 0 0 1px rgba(240, 195, 106, 0.14), 0 16px 32px rgba(0, 0, 0, 0.7);
    }

    .nav-cta:hover {
      background: linear-gradient(120deg, #f3e3cf, #f9efe0);
    }

    body[data-theme="night"] .nav-cta:hover {
      filter: brightness(1.07);
    }

    .theme-toggle {
      border-radius: 999px;
      border: 1px solid var(--border);
      padding: 4px 9px;
      font-size: 11px;
      display: flex;
      align-items: center;
      gap: 6px;
      cursor: pointer;
      background: rgba(255, 255, 255, 0.8);
      color: var(--muted);
      transition: background var(--transition-fast), transform var(--transition-fast), box-shadow var(--transition-fast), color var(--transition-fast);
    }

    body[data-theme="night"] .theme-toggle {
      background: rgba(17, 16, 27, 0.92);
      color: var(--muted);
      border-color: rgba(255, 255, 255, 0.06);
      box-shadow: 0 8px 18px rgba(0, 0, 0, 0.65);
    }

    .theme-toggle span.icon {
      font-size: 14px;
    }

    .theme-toggle:hover {
      transform: translateY(-1px);
      box-shadow: var(--shadow-subtle);
      background: #fffdf8;
      color: var(--text);
    }

    body[data-theme="night"] .theme-toggle:hover {
      background: rgba(30, 29, 52, 0.98);
      color: #f8f4ee;
    }

    /* HERO */

    .hero {
      margin-top: 32px;
      margin-bottom: 40px;
      display: grid;
      grid-template-columns: minmax(0, 1.4fr) minmax(0, 1fr);
      gap: 32px;
      align-items: center;
    }

    .hero-kicker {
      font-size: 12px;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      color: var(--muted);
      margin-bottom: 10px;
    }

    .hero-title {
      font-size: clamp(30px, 4vw, 40px);
      letter-spacing: 0.04em;
      text-transform: uppercase;
      font-weight: 600;
      line-height: 1.2;
      margin-bottom: 14px;
    }

    .hero-highlight {
      display: inline-block;
      padding: 2px 10px;
      border-radius: 999px;
      background: var(--accent-soft);
      font-size: 11px;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      margin-left: 4px;
    }

    .hero-subtitle {
      font-size: 14px;
      color: var(--muted);
      max-width: 34rem;
      margin-bottom: 20px;
    }

    .hero-subtitle strong {
      color: var(--text);
      font-weight: 600;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-bottom: 16px;
    }

    .btn-primary {
      border-radius: 999px;
      padding: 11px 20px;
      border: none;
      background: linear-gradient(120deg, var(--accent), var(--accent-strong));
      color: #332616;
      font-size: 13px;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      font-weight: 600;
      box-shadow: 0 14px 28px rgba(176, 142, 77, 0.32);
      cursor: pointer;
      transition: transform var(--transition-fast), box-shadow var(--transition-fast), filter var(--transition-fast);
    }

    body[data-theme="night"] .btn-primary {
      color: #1a1308;
      box-shadow: 0 16px 36px rgba(0, 0, 0, 0.85);
    }

    .btn-primary:hover {
      transform: translateY(-1px);
      filter: brightness(1.04);
      box-shadow: 0 18px 36px rgba(176, 142, 77, 0.38);
    }

    .btn-ghost {
      border-radius: 999px;
      padding: 10px 18px;
      border: 1px solid var(--border);
      background: rgba(255, 255, 255, 0.7);
      font-size: 13px;
      color: var(--muted);
      cursor: pointer;
      display: flex;
      align-items: center;
      gap: 8px;
      transition: background var(--transition-fast), transform var(--transition-fast), color var(--transition-fast), box-shadow var(--transition-fast), border var(--transition-fast);
    }

    body[data-theme="night"] .btn-ghost {
      background: rgba(14, 13, 26, 0.88);
      border-color: rgba(255, 255, 255, 0.05);
    }

    .btn-ghost span.icon {
      font-size: 16px;
    }

    .btn-ghost:hover {
      background: rgba(255, 255, 255, 0.95);
      transform: translateY(-1px);
      color: var(--text);
      box-shadow: var(--shadow-subtle);
      border-color: rgba(0, 0, 0, 0.06);
    }

    body[data-theme="night"] .btn-ghost:hover {
      background: rgba(30, 29, 52, 0.98);
      color: #f8f4ee;
    }

    .hero-meta {
      font-size: 11px;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 0.18em;
    }

    .hero-right {
      position: relative;
    }

    .hero-card {
      border-radius: var(--radius-xl);
      background: linear-gradient(145deg, #221814, #3a2920);
      color: #fdf6ec;
      padding: 18px 18px 20px;
      box-shadow: var(--shadow-soft);
      position: relative;
      overflow: hidden;
    }

    body[data-theme="night"] .hero-card {
      background: radial-gradient(circle at top left, #221b32, #0b0716);
    }

    .hero-card::before {
      content: "";
      position: absolute;
      inset: 0;
      background:
        radial-gradient(circle at top right, rgba(249, 210, 132, 0.16), transparent 55%),
        radial-gradient(circle at bottom left, rgba(112, 228, 255, 0.12), transparent 60%);
      pointer-events: none;
    }

    .hc-top {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 16px;
    }

    .hc-label {
      font-size: 11px;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      opacity: 0.7;
    }

    .hc-pill {
      border-radius: 999px;
      padding: 4px 10px;
      background: rgba(0, 0, 0, 0.45);
      font-size: 11px;
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    .hc-pill-dot {
      width: 6px;
      height: 6px;
      border-radius: 50%;
      background: #7ee39f;
      box-shadow: 0 0 10px rgba(126, 227, 159, 0.9);
    }

    .hc-main-title {
      font-size: 16px;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      font-weight: 550;
      margin-bottom: 6px;
    }

    .hc-sub {
      font-size: 12px;
      opacity: 0.75;
      margin-bottom: 14px;
    }

    .hc-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 10px;
      font-size: 11px;
    }

    .hc-metric {
      padding: 8px 8px 9px;
      border-radius: 14px;
      background: rgba(0, 0, 0, 0.38);
      backdrop-filter: blur(8px);
    }

    .hc-metric-label {
      opacity: 0.7;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      margin-bottom: 2px;
    }

    .hc-metric-value {
      font-size: 13px;
      font-weight: 600;
    }

    .hc-tag-row {
      margin-top: 14px;
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
      font-size: 10px;
      opacity: 0.8;
    }

    .hc-tag {
      padding: 4px 8px;
      border-radius: 999px;
      border: 1px solid rgba(255, 255, 255, 0.18);
      background: rgba(0, 0, 0, 0.3);
    }

    .hc-float {
      position: absolute;
      right: -10px;
      bottom: -10px;
      width: 120px;
      height: 120px;
      border-radius: 50%;
      background: radial-gradient(circle at 30% 20%, #f5e4c5, #b88747);
      opacity: 0.25;
      filter: blur(8px);
    }

    body[data-theme="night"] .hc-float {
      background: radial-gradient(circle at 20% 10%, #ffdf8f, #f0c36a);
      opacity: 0.28;
    }

    /* SECTION SHELLS */

    section {
      margin-bottom: 48px;
    }

    .section-heading {
      font-size: 12px;
      text-transform: uppercase;
      letter-spacing: 0.18em;
      color: var(--muted);
      margin-bottom: 6px;
    }

    .section-title {
      font-size: 20px;
      font-weight: 600;
      margin-bottom: 8px;
      letter-spacing: 0.04em;
      text-transform: uppercase;
    }

    .section-subtitle {
      font-size: 13px;
      color: var(--muted);
      max-width: 32rem;
    }

    /* PILLARS */

    .pillars-grid {
      margin-top: 20px;
      display: grid;
      grid-template-columns: repeat(4, minmax(0, 1fr));
      gap: 16px;
    }

    .pillar-card {
      border-radius: var(--radius-lg);
      padding: 14px 14px 16px;
      background: rgba(255, 255, 255, 0.85);
      border: 1px solid var(--border);
      box-shadow: var(--shadow-subtle);
      display: flex;
      flex-direction: column;
      gap: 8px;
      transition: transform var(--transition-fast), box-shadow var(--transition-fast), border var(--transition-fast), background var(--transition-fast);
    }

    body[data-theme="night"] .pillar-card {
      background: rgba(18, 17, 30, 0.95);
      border-color: rgba(255, 255, 255, 0.04);
    }

    .pillar-card:hover {
      transform: translateY(-3px);
      box-shadow: var(--shadow-soft);
      background: var(--bg-soft);
      border-color: rgba(200, 169, 106, 0.55);
    }

    .pillar-icon {
      font-size: 18px;
      margin-bottom: 2px;
    }

    .pillar-label {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.18em;
      color: var(--muted);
    }

    .pillar-title {
      font-size: 15px;
      font-weight: 600;
    }

    .pillar-text {
      font-size: 13px;
      color: var(--muted);
    }

    .pillar-meta {
      margin-top: auto;
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      color: var(--muted);
    }

    /* JOURNEY TIMELINE */

    .journey-wrap {
      margin-top: 20px;
      display: grid;
      grid-template-columns: minmax(0, 1.1fr) minmax(0, 1.1fr);
      gap: 22px;
      align-items: flex-start;
    }

    .journey-intro-card {
      padding: 16px 16px 18px;
      border-radius: var(--radius-xl);
      background: var(--bg-alt);
      border: 1px solid var(--border);
      box-shadow: var(--shadow-subtle);
      font-size: 13px;
      color: var(--muted);
    }

    body[data-theme="night"] .journey-intro-card {
      background: radial-gradient(circle at top left, #1b1728, #0e0d18);
      color: #cdc4de;
      border-color: rgba(255, 255, 255, 0.04);
    }

    .journey-intro-card p + p {
      margin-top: 10px;
    }

    .journey-intro-meta {
      margin-top: 12px;
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.16em;
    }

    .timeline {
      list-style: none;
      border-left: 1px solid rgba(0, 0, 0, 0.18);
      padding-left: 14px;
      margin-left: 4px;
    }

    body[data-theme="night"] .timeline {
      border-left-color: rgba(255, 255, 255, 0.12);
    }

    .timeline-item {
      position: relative;
      padding-left: 14px;
      margin-bottom: 18px;
    }

    .timeline-item::before {
      content: "";
      position: absolute;
      left: -8px;
      top: 4px;
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background: #fff;
      border: 2px solid var(--accent);
      box-shadow: 0 0 0 4px rgba(200, 169, 106, 0.2);
    }

    body[data-theme="night"] .timeline-item::before {
      background: #0a0712;
      box-shadow: 0 0 0 6px rgba(240, 195, 106, 0.16);
    }

    .timeline-tag {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      color: var(--muted);
      margin-bottom: 2px;
    }

    .timeline-title {
      font-size: 14px;
      font-weight: 600;
    }

    .timeline-desc {
      font-size: 13px;
      color: var(--muted);
    }

    /* EXPERIENCE / INTERACTIVE PAGES */

    .xp-shell {
      margin-top: 20px;
      border-radius: var(--radius-xl);
      background: var(--glass);
      border: 1px solid var(--border);
      box-shadow: var(--shadow-soft);
      padding: 16px 16px 18px;
      backdrop-filter: blur(16px) saturate(130%);
      -webkit-backdrop-filter: blur(16px) saturate(130%);
    }

    body[data-theme="night"] .xp-shell {
      background: rgba(12, 11, 24, 0.96);
      border-color: rgba(255, 255, 255, 0.04);
    }

    .xp-tabs {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-bottom: 16px;
      align-items: center;
      justify-content: space-between;
    }

    .xp-tab-group {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .xp-tab {
      border-radius: 999px;
      padding: 6px 12px;
      font-size: 12px;
      border: 1px solid transparent;
      cursor: pointer;
      background: transparent;
      color: var(--muted);
      display: inline-flex;
      align-items: center;
      gap: 6px;
      transition: background var(--transition-fast), border var(--transition-fast), color var(--transition-fast), transform var(--transition-fast);
    }

    .xp-tab span.icon {
      font-size: 15px;
    }

    .xp-tab[data-active="true"] {
      background: var(--accent-soft);
      border-color: rgba(200, 169, 106, 0.5);
      color: var(--text);
      transform: translateY(-1px);
    }

    body[data-theme="night"] .xp-tab[data-active="true"] {
      background: radial-gradient(circle at top left, rgba(240, 195, 106, 0.28), rgba(20, 18, 34, 0.9));
    }

    .xp-indicator {
      font-size: 11px;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      color: var(--muted);
    }

    .xp-pages {
      margin-top: 4px;
    }

    .xp-page {
      display: none;
      animation: fadeIn 220ms ease-out;
    }

    .xp-page[data-visible="true"] {
      display: grid;
      grid-template-columns: minmax(0, 1.15fr) minmax(0, 1.05fr);
      gap: 18px;
      align-items: flex-start;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(4px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .xp-left-title {
      font-size: 15px;
      font-weight: 600;
      margin-bottom: 4px;
    }

    .xp-left-sub {
      font-size: 12px;
      color: var(--muted);
      margin-bottom: 10px;
      text-transform: uppercase;
      letter-spacing: 0.14em;
    }

    .xp-left-body {
      font-size: 13px;
      color: var(--muted);
      margin-bottom: 10px;
    }

    .xp-keyline {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      color: var(--muted);
      margin-top: 4px;
    }

    .xp-metrics {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 10px;
      margin-top: 10px;
      font-size: 11px;
    }

    .xp-metric-card {
      border-radius: 14px;
      padding: 8px 8px 9px;
      background: rgba(255, 255, 255, 0.9);
      border: 1px solid var(--border);
      box-shadow: var(--shadow-subtle);
    }

    body[data-theme="night"] .xp-metric-card {
      background: rgba(14, 13, 28, 0.96);
      border-color: rgba(255, 255, 255, 0.04);
    }

    .xp-metric-label {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 0.14em;
      color: var(--muted);
      margin-bottom: 2px;
    }

    .xp-metric-value {
      font-size: 13px;
      font-weight: 600;
    }

    .xp-metric-sub {
      font-size: 11px;
      color: var(--muted);
    }

    .xp-right-card {
      border-radius: 18px;
      padding: 14px 14px 16px;
      background: radial-gradient(circle at top left, rgba(255, 255, 255, 0.16), rgba(0, 0, 0, 0.75)), #222;
      color: #fdf6ec;
      box-shadow: var(--shadow-soft);
      position: relative;
      overflow: hidden;
    }

    body[data-theme="night"] .xp-right-card {
      background: radial-gradient(circle at center, rgba(240, 195, 106, 0.16), rgba(6, 5, 18, 0.96));
    }

    .xp-right-chip {
      font-size: 10px;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      opacity: 0.8;
      margin-bottom: 6px;
    }

    .xp-right-main {
      font-size: 15px;
      font-weight: 600;
      margin-bottom: 4px;
    }

    .xp-right-sub {
      font-size: 12px;
      opacity: 0.85;
      margin-bottom: 10px;
    }

    .xp-slider-label {
      font-size: 11px;
      text-transform: uppercase;
      letter-spacing: 0.16em;
      opacity: 0.8;
      margin-bottom: 4px;
    }

    .xp-slider-row {
      display: flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 10px;
    }

    .xp-slider-row input[type="range"] {
      flex: 1;
      -webkit-appearance: none;
      appearance: none;
      height: 4px;
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.25);
      outline: none;
    }

    .xp-slider-row input[type="range"]::-webkit-slider-thumb {
      -webkit-appearance: none;
      appearance: none;
      width: 16px;
      height: 16px;
      border-radius: 50%;
      background: var(--accent-strong);
      box-shadow: 0 0 0 3px rgba(0, 0, 0, 0.4);
      cursor: pointer;
    }

    body[data-theme="night"] .xp-slider-row input[type="range"]::-webkit-slider-thumb {
      box-shadow: 0 0 0 3px rgba(0, 0, 0, 0.8);
    }

    .xp-slider-value {
      font-size: 12px;
      font-weight: 600;
    }

    .xp-right-meta {
      font-size: 11px;
      opacity: 0.9;
      margin-top: 4px;
    }

    .xp-glow-orbit {
      position: absolute;
      right: -30px;
      bottom: -30px;
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 1px solid rgba(255, 255, 255, 0.2);
      opacity: 0.7;
    }

    .xp-glow-orbit::before {
      content: "";
      position: absolute;
      inset: 18px;
      border-radius: inherit;
      border: 1px dashed rgba(255, 255, 255, 0.25);
    }

    /* GALLERY */

    .gallery-grid {
      margin-top: 20px;
      display: grid;
      grid-template-columns: 2.2fr 1.8fr;
      gap: 16px;
    }

    .gallery-main {
      border-radius: var(--radius-xl);
      overflow: hidden;
      background: #d4c3b0;
      position: relative;
      box-shadow: var(--shadow-soft);
      min-height: 220px;
      display: flex;
      align-items: flex-end;
      padding: 16px;
      color: #fdf6ec;
    }

    body[data-theme="night"] .gallery-main {
      background: radial-gradient(circle at top left, #26203c, #0c0b16);
    }

    .gallery-main-label {
      font-size: 11px;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      opacity: 0.85;
      margin-bottom: 3px;
    }

    .gallery-main-title {
      font-size: 16px;
      font-weight: 600;
      margin-bottom: 4px;
    }

    .gallery-main-sub {
      font-size: 12px;
      opacity: 0.9;
      max-width: 16rem;
    }

    .gallery-overlay {
      position: absolute;
      inset: 0;
      background: linear-gradient(to top right, rgba(33, 22, 16, 0.72), rgba(33, 22, 16, 0) 65%);
      z-index: 1;
    }

    body[data-theme="night"] .gallery-overlay {
      background: linear-gradient(to top right, rgba(4, 3, 10, 0.9), rgba(4, 3, 10, 0.1) 65%);
    }

    .gallery-main-inner {
      position: relative;
      z-index: 2;
    }

    .gallery-secondary {
      display: grid;
      grid-template-columns: 1fr;
      gap: 12px;
    }

    .gallery-card {
      border-radius: var(--radius-lg);
      border: 1px solid var(--border);
      background: rgba(255, 255, 255, 0.92);
      padding: 10px 12px;
      font-size: 12px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 10px;
      box-shadow: var(--shadow-subtle);
      transition: transform var(--transition-fast), box-shadow var(--transition-fast), border var(--transition-fast), background var(--transition-fast);
    }

    body[data-theme="night"] .gallery-card {
      background: rgba(16, 15, 30, 0.96);
      border-color: rgba(255, 255, 255, 0.05);
    }

    .gallery-card:hover {
      transform: translateY(-2px);
      box-shadow: var(--shadow-soft);
      border-color: rgba(200, 169, 106, 0.6);
      background: var(--bg-soft);
    }

    .gallery-card-main {
      display: flex;
      flex-direction: column;
      gap: 2px;
    }

    .gallery-card-title {
      font-size: 13px;
      font-weight: 600;
    }

    .gallery-card-tag {
      font-size: 10px;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      color: var(--muted);
    }

    .gallery-card-meta {
      font-size: 11px;
      color: var(--muted);
    }

    /* JOURNAL */

    .journal-grid {
      margin-top: 18px;
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 16px;
    }

    .post-card {
      border-radius: var(--radius-lg);
      background: rgba(255, 255, 255, 0.94);
      border: 1px solid var(--border);
      padding: 12px 14px 14px;
      display: flex;
      flex-direction: column;
      gap: 6px;
      box-shadow: var(--shadow-subtle);
      transition: transform var(--transition-fast), box-shadow var(--transition-fast), border var(--transition-fast), background var(--transition-fast);
    }

    body[data-theme="night"] .post-card {
      background: rgba(16, 15, 30, 0.96);
      border-color: rgba(255, 255, 255, 0.06);
    }

    .post-card:hover {
      transform: translateY(-3px);
      box-shadow: var(--shadow-soft);
      border-color: rgba(200, 169, 106, 0.6);
      background: var(--bg-soft);
    }

    .post-tag {
      font-size: 10px;
      letter-spacing: 0.16em;
      text-transform: uppercase;
      color: var(--muted);
    }

    .post-title {
      font-size: 14px;
      font-weight: 600;
    }

    .post-excerpt {
      font-size: 13px;
      color: var(--muted);
    }

    .post-meta {
      margin-top: auto;
      font-size: 11px;
      color: var(--muted);
      display: flex;
      justify-content: space-between;
    }

    /* CONTACT / FOOTER */

    .contact-card {
      margin-top: 20px;
      border-radius: var(--radius-xl);
      padding: 18px 18px 16px;
      background: linear-gradient(135deg, #f8eee0, #f3ddc4);
      border: 1px solid rgba(200, 169, 106, 0.5);
      box-shadow: var(--shadow-soft);
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 18px;
      align-items: center;
    }

    body[data-theme="night"] .contact-card {
      background: radial-gradient(circle at top left, #221b34, #0a0714);
      border-color: rgba(240, 195, 106, 0.55);
    }

    .contact-main {
      max-width: 360px;
      font-size: 13px;
      color: #4b3a29;
    }

    body[data-theme="night"] .contact-main {
      color: #f8f4ee;
    }

    .contact-main h3 {
      font-size: 16px;
      text-transform: uppercase;
      letter-spacing: 0.14em;
      margin-bottom: 6px;
    }

    .contact-links {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      font-size: 12px;
    }

    .contact-pill {
      border-radius: 999px;
      padding: 7px 12px;
      border: 1px solid rgba(75, 58, 41, 0.12);
      background: rgba(255, 255, 255, 0.82);
      display: flex;
      align-items: center;
      gap: 7px;
      cursor: pointer;
      transition: background var(--transition-fast), transform var(--transition-fast), box-shadow var(--transition-fast), border var(--transition-fast);
    }

    body[data-theme="night"] .contact-pill {
      background: rgba(14, 13, 28, 0.96);
      border-color: rgba(255, 255, 255, 0.08);
      color: #f8f4ee;
    }

    .contact-pill:hover {
      background: #fff9f1;
      transform: translateY(-1px);
      box-shadow: var(--shadow-subtle);
    }

    body[data-theme="night"] .contact-pill:hover {
      background: rgba(32, 30, 56, 0.98);
      box-shadow: 0 12px 26px rgba(0, 0, 0, 0.7);
      border-color: rgba(240, 195, 106, 0.4);
    }

    footer {
      margin-top: 28px;
      font-size: 11px;
      color: var(--muted);
      display: flex;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 8px;
    }

    footer span {
      opacity: 0.8;
    }

    /* RESPONSIVE */

    @media (max-width: 900px) {
      header {
        padding-inline: 14px;
      }

      nav a {
        display: none;
      }

      .nav-cta {
        display: none;
      }

      .hero {
        grid-template-columns: minmax(0, 1fr);
      }

      .hero-right {
        order: -1;
      }

      .pillars-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }

      .journal-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
      }

      .gallery-grid {
        grid-template-columns: minmax(0, 1fr);
      }

      .journey-wrap {
        grid-template-columns: minmax(0, 1fr);
      }

      .xp-page[data-visible="true"] {
        grid-template-columns: minmax(0, 1fr);
      }
    }

    @media (max-width: 600px) {
      .page {
        padding-inline: 16px;
      }

      .pillars-grid {
        grid-template-columns: minmax(0, 1fr);
      }

      .journal-grid {
        grid-template-columns: minmax(0, 1fr);
      }

      .hero-card {
        padding: 16px;
      }

      .contact-card {
        padding: 16px;
      }

      .xp-tabs {
        align-items: flex-start;
      }

      .xp-indicator {
        margin-top: 6px;
      }
    }

    html {
      scroll-behavior: smooth;
    }
  </style>
</head>
<body data-theme="day">
  <div class="page">
    <!-- HEADER -->
    <header>
      <div class="brand">
        <div class="brand-mark">EJR</div>
        <div class="brand-text">
          <div class="brand-title">Edward J. Rhee</div>
          <div class="brand-subtitle">Self-Growth in Motion</div>
        </div>
      </div>
      <nav>
        <a href="#journey">Journey</a>
        <a href="#pillars">Pillars</a>
        <a href="#experience">Experience</a>
        <a href="#gallery">Lifestyle</a>
        <a href="#journal" class="nav-cta">Journal</a>
        <button type="button" class="theme-toggle" id="themeToggle">
          <span class="icon" id="themeIcon">☀️</span>
          <span id="themeLabel">Day drive</span>
        </button>
      </nav>
    </header>

    <!-- HERO -->
    <section class="hero">
      <div>
        <div class="hero-kicker">A Life Built on Intentional Luxury</div>
        <h1 class="hero-title">
          Self-Growth, Captured Through
          <span class="hero-highlight">Performance &amp; Presence</span>
        </h1>
        <p class="hero-subtitle">
          I’m <strong>Edward</strong>, documenting my journey of
          <strong>becoming my best self</strong> through the things I love:
          Porsches, Rolex timepieces, warm interiors, travel, and fitness.
          This isn’t about flexing—this is about
          <strong>earning what you become.</strong>
        </p>
        <div class="hero-actions">
          <button class="btn-primary" onclick="document.getElementById('experience').scrollIntoView({behavior:'smooth'})">
            Open the dashboard
          </button>
          <button class="btn-ghost" onclick="document.getElementById('journal').scrollIntoView({behavior:'smooth'})">
            <span class="icon">➜</span>
            Latest reflections
          </button>
        </div>
        <div class="hero-meta">
          Cars · Watches · Travel · Fitness · Inner Work
        </div>
      </div>
      <div class="hero-right">
        <div class="hero-card">
          <div class="hc-top">
            <div>
              <div class="hc-label">Today’s snapshot</div>
              <div class="hc-main-title">Lifestyle Scorecard</div>
              <div class="hc-sub">A simple way I check in with my progress each week.</div>
            </div>
            <div class="hc-pill">
              <span class="hc-pill-dot"></span>
              Live in progress
            </div>
          </div>
          <div class="hc-grid">
            <div class="hc-metric">
              <div class="hc-metric-label">Body</div>
              <div class="hc-metric-value" id="bodyScore">4 / 5</div>
              <div style="font-size:10px;opacity:.75;margin-top:2px;">Training, recovery, sleep</div>
            </div>
            <div class="hc-metric">
              <div class="hc-metric-label">Mind</div>
              <div class="hc-metric-value" id="mindScore">3 / 5</div>
              <div style="font-size:10px;opacity:.75;margin-top:2px;">Focus &amp; stillness</div>
            </div>
            <div class="hc-metric">
              <div class="hc-metric-label">Lifestyle</div>
              <div class="hc-metric-value" id="lifeScore">+12%</div>
              <div style="font-size:10px;opacity:.75;margin-top:2px;">Small upgrades this month</div>
            </div>
          </div>
          <div class="hc-tag-row">
            <div class="hc-tag">Gym consistency</div>
            <div class="hc-tag">Porsche vision board</div>
            <div class="hc-tag">Morning journaling</div>
          </div>
          <div class="hc-float"></div>
        </div>
      </div>
    </section>

    <!-- PILLARS -->
    <section id="pillars">
      <div class="section-heading">The Pillars</div>
      <div class="section-title">How I Measure Self-Growth</div>
      <p class="section-subtitle">
        Each area of my life is a reflection of my standards. I use these pillars to keep
        my progress honest—far beyond just what’s parked in the garage or on my wrist.
      </p>

      <div class="pillars-grid">
        <article class="pillar-card">
          <div class="pillar-icon">🏎️</div>
          <div class="pillar-label">Performance</div>
          <div class="pillar-title">Porsche &amp; the Pursuit of Precision</div>
          <p class="pillar-text">
            For me, a Porsche isn’t about status. It’s about precision, discipline,
            and the feeling you get when effort finally meets reward.
          </p>
          <div class="pillar-meta">Driving standards up</div>
        </article>

        <article class="pillar-card">
          <div class="pillar-icon">⌚</div>
          <div class="pillar-label">Time</div>
          <div class="pillar-title">Rolex &amp; Respecting Every Hour</div>
          <p class="pillar-text">
            Luxury watches remind me that time is the real flex. I track how I spend mine
            like every second is an investment.
          </p>
          <div class="pillar-meta">Time as currency</div>
        </article>

        <article class="pillar-card">
          <div class="pillar-icon">🏡</div>
          <div class="pillar-label">Environment</div>
          <div class="pillar-title">Curating a Calm, Luxurious Home</div>
          <p class="pillar-text">
            Minimal, warm, and intentional. My space is designed to keep me focused,
            grounded, and inspired to keep building.
          </p>
          <div class="pillar-meta">Space shapes mind</div>
        </article>

        <article class="pillar-card">
          <div class="pillar-icon">🏋🏻‍♂️</div>
          <div class="pillar-label">Body</div>
          <div class="pillar-title">Fitness as a Non-Negotiable</div>
          <p class="pillar-text">
            Strength, mobility, and health first. The car I drive matters—but my body
            is the vehicle I have for life.
          </p>
          <div class="pillar-meta">Discipline daily</div>
        </article>
      </div>
    </section>

    <!-- JOURNEY -->
    <section id="journey">
      <div class="section-heading">The Journey</div>
      <div class="section-title">From Where I Started to Where I’m Going</div>
      <p class="section-subtitle">
        This isn’t an overnight success story. It’s a slow, intentional climb—documented in
        real time. Here’s how the chapters of my life are unfolding.
      </p>

      <div class="journey-wrap">
        <div class="journey-intro-card">
          <p>
            I didn’t grow up surrounded by supercars, luxury watches, or five-star hotels.
            My journey started with small decisions: showing up, learning, and raising my
            standards one habit at a time.
          </p>
          <p>
            Every milestone—financial, physical, or mental—is written here not to impress,
            but to <strong>remind myself</strong> of who I’m becoming.
          </p>
          <div class="journey-intro-meta">
            Next chapter · To be written daily
          </div>
        </div>

        <ul class="timeline">
          <li class="timeline-item">
            <div class="timeline-tag">Early Hustle</div>
            <div class="timeline-title">Learning how money, work, and pressure feel</div>
            <div class="timeline-desc">
              First jobs, long days, and figuring out what kind of life I never wanted
              to settle for again.
            </div>
          </li>
          <li class="timeline-item">
            <div class="timeline-tag">Leveling Up</div>
            <div class="timeline-title">Building skills &amp; raising standards</div>
            <div class="timeline-desc">
              Growing in my career, learning how to manage money, and starting to see
              that the life I wanted was actually possible.
            </div>
          </li>
          <li class="timeline-item">
            <div class="timeline-tag">Body &amp; Mind</div>
            <div class="timeline-title">Treating my health like a luxury asset</div>
            <div class="timeline-desc">
              Taking the gym seriously, dialing in nutrition, and using fitness
              as proof that I can keep promises to myself.
            </div>
          </li>
          <li class="timeline-item">
            <div class="timeline-tag">Now</div>
            <div class="timeline-title">Building the life I used to visualize</div>
            <div class="timeline-desc">
              This is the chapter you’re reading now—where Porsches, Rolex, travel,
              and a calm home are symbols of inner growth, not the goal itself.
            </div>
          </li>
        </ul>
      </div>
    </section>

    <!-- EXPERIENCE / INTERACTIVE PAGES -->
    <section id="experience">
      <div class="section-heading">Interactive</div>
      <div class="section-title">Your Futuristic Lifestyle Dashboard</div>
      <p class="section-subtitle">
        Think of this as a control center for my journey. Four “pages” that track how
        cars, timepieces, travel, and fitness reflect the work I’m putting in.
      </p>

      <div class="xp-shell">
        <div class="xp-tabs">
          <div class="xp-tab-group">
            <button class="xp-tab" data-page="cars" data-active="true">
              <span class="icon">🏎️</span>
              <span>Garage · Performance</span>
            </button>
            <button class="xp-tab" data-page="watches">
              <span class="icon">⌚</span>
              <span>Timepieces · Time</span>
            </button>
            <button class="xp-tab" data-page="travel">
              <span class="icon">✈️</span>
              <span>Travel · Perspective</span>
            </button>
            <button class="xp-tab" data-page="fitness">
              <span class="icon">💪</span>
              <span>Fitness · Discipline</span>
            </button>
          </div>
          <div class="xp-indicator" id="xpIndicator">
            Page: Garage · Performance
          </div>
        </div>

        <div class="xp-pages">
          <!-- CARS PAGE -->
          <div class="xp-page" id="xp-cars" data-visible="true">
            <div>
              <div class="xp-left-sub">Garage overview</div>
              <div class="xp-left-title">Porsche energy level for the year</div>
              <p class="xp-left-body">
                I track my “garage energy” less by the keys I own and more by the
                <strong>skills, income, and patience</strong> I’m building that make owning a Porsche feel normal,
                not impossible. Each step—credit, savings, income—adds to this gauge.
              </p>
              <p class="xp-left-body">
                When this bar is high, it means I'm doing the boring things that actually
                get me closer: paying things on time, stacking cash, learning, and pushing my work.
              </p>
              <div class="xp-keyline">Metrics I watch</div>
              <div class="xp-metrics">
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Income</div>
                  <div class="xp-metric-value">▲ Growing</div>
                  <div class="xp-metric-sub">Skill + leverage focused</div>
                </div>
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Debt</div>
                  <div class="xp-metric-value">Disciplined</div>
                  <div class="xp-metric-sub">No lifestyle debt for flexes</div>
                </div>
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Vision</div>
                  <div class="xp-metric-value">High clarity</div>
                  <div class="xp-metric-sub">Exact model, spec, timeline</div>
                </div>
              </div>
            </div>
            <div class="xp-right-card">
              <div class="xp-right-chip">Live control · Porsche signal</div>
              <div class="xp-right-main">“Garage Readiness” Dial</div>
              <div class="xp-right-sub">
                This is a simple slider that represents how close I feel to
                buying my next dream car with <strong>zero regret</strong>.
              </div>
              <div class="xp-slider-label">Readiness today</div>
              <div class="xp-slider-row">
                <input type="range" min="0" max="100" value="40" id="sliderGarage">
                <div class="xp-slider-value" id="sliderGarageValue">40%</div>
              </div>
              <div class="xp-right-meta">
                Saved locally · Next time you visit, the dial remembers where you left it.
              </div>
              <div class="xp-glow-orbit"></div>
            </div>
          </div>

          <!-- WATCHES PAGE -->
          <div class="xp-page" id="xp-watches">
            <div>
              <div class="xp-left-sub">Timepiece philosophy</div>
              <div class="xp-left-title">Rolex as a milestone, not a personality</div>
              <p class="xp-left-body">
                A Rolex to me is a <strong>receipt for years of consistency</strong>, not a costume.
                I’m more interested in the person I become while earning it than the watch itself.
              </p>
              <p class="xp-left-body">
                I track my time the same way I’d track a complication on a high-end watch:
                precision, no wasted motion, and appreciation for long time horizons.
              </p>
              <div class="xp-keyline">Signals I check</div>
              <div class="xp-metrics">
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Deep work</div>
                  <div class="xp-metric-value">2–4 hrs</div>
                  <div class="xp-metric-sub">Focused, distraction free</div>
                </div>
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Scrolling</div>
                  <div class="xp-metric-value">Controlled</div>
                  <div class="xp-metric-sub">Kept on a short leash</div>
                </div>
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Presence</div>
                  <div class="xp-metric-value">Intentional</div>
                  <div class="xp-metric-sub">Phone down when it matters</div>
                </div>
              </div>
            </div>
            <div class="xp-right-card">
              <div class="xp-right-chip">Micro habit tracker</div>
              <div class="xp-right-main">“How I Spent My Hours”</div>
              <div class="xp-right-sub">
                A rough signal of whether I treated my time like something rare
                and valuable—or something to burn.
              </div>
              <div class="xp-slider-label">Intentional hours today</div>
              <div class="xp-slider-row">
                <input type="range" min="0" max="12" value="4" id="sliderTime">
                <div class="xp-slider-value" id="sliderTimeValue">4 hrs</div>
              </div>
              <div class="xp-right-meta">
                Simple rule: when this number climbs, everything else in my life improves.
              </div>
              <div class="xp-glow-orbit"></div>
            </div>
          </div>

          <!-- TRAVEL PAGE -->
          <div class="xp-page" id="xp-travel">
            <div>
              <div class="xp-left-sub">Movement &amp; perspective</div>
              <div class="xp-left-title">Travel that upgrades my ambition</div>
              <p class="xp-left-body">
                I use travel as a tool to expand what I believe is possible—new cities,
                new standards, and new reminders that the world is bigger than my excuses.
              </p>
              <p class="xp-left-body">
                Instead of collecting random trips, I focus on <strong>intentional destinations</strong>
                that spark new ideas and push my comfort zone.
              </p>
              <div class="xp-keyline">Travel goals</div>
              <div class="xp-metrics">
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Trips / year</div>
                  <div class="xp-metric-value">Quality &gt; quantity</div>
                  <div class="xp-metric-sub">A few meaningful, not many random</div>
                </div>
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Purpose</div>
                  <div class="xp-metric-value">Perspective</div>
                  <div class="xp-metric-sub">Return home thinking differently</div>
                </div>
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Documentation</div>
                  <div class="xp-metric-value">Journal + photo</div>
                  <div class="xp-metric-sub">Not just IG stories</div>
                </div>
              </div>
            </div>
            <div class="xp-right-card">
              <div class="xp-right-chip">Future map</div>
              <div class="xp-right-main">“Next destination” slider</div>
              <div class="xp-right-sub">
                A playful way to mark how close I feel to my next intentional getaway.
              </div>
              <div class="xp-slider-label">Trip readiness</div>
              <div class="xp-slider-row">
                <input type="range" min="0" max="100" value="30" id="sliderTravel">
                <div class="xp-slider-value" id="sliderTravelValue">30%</div>
              </div>
              <div class="xp-right-meta">
                When this hits 100%, it should mean money, time, and purpose all align.
              </div>
              <div class="xp-glow-orbit"></div>
            </div>
          </div>

          <!-- FITNESS PAGE -->
          <div class="xp-page" id="xp-fitness">
            <div>
              <div class="xp-left-sub">Core system</div>
              <div class="xp-left-title">Treating my body like a supercar</div>
              <p class="xp-left-body">
                I’d never drive a Porsche on cheap oil and missed maintenance.
                My body gets the same respect: sleep, training, nutrition, and recovery.
              </p>
              <p class="xp-left-body">
                When my energy is high, every other part of my life gets better—
                money, relationships, and creativity all feed off of it.
              </p>
              <div class="xp-keyline">Fitness indicators</div>
              <div class="xp-metrics">
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Training</div>
                  <div class="xp-metric-value">4–6x / week</div>
                  <div class="xp-metric-sub">Lifting + movement</div>
                </div>
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Nutrition</div>
                  <div class="xp-metric-value">Dialing in</div>
                  <div class="xp-metric-sub">Fuel, not just cravings</div>
                </div>
                <div class="xp-metric-card">
                  <div class="xp-metric-label">Sleep</div>
                  <div class="xp-metric-value">Target 7–9h</div>
                  <div class="xp-metric-sub">Non-negotiable performance mod</div>
                </div>
              </div>
            </div>
            <div class="xp-right-card">
              <div class="xp-right-chip">Body dashboard</div>
              <div class="xp-right-main">“Energy for the day” dial</div>
              <div class="xp-right-sub">
                A quick check-in on how ready I feel to push today—based on sleep,
                food, stress, and mindset.
              </div>
              <div class="xp-slider-label">Energy level</div>
              <div class="xp-slider-row">
                <input type="range" min="0" max="100" value="65" id="sliderEnergy">
                <div class="xp-slider-value" id="sliderEnergyValue">65%</div>
              </div>
              <div class="xp-right-meta">
                The goal is not perfection—just being honest and trending in the right direction.
              </div>
              <div class="xp-glow-orbit"></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- GALLERY / LIFESTYLE -->
    <section id="gallery">
      <div class="section-heading">Visual Story</div>
      <div class="section-title">The Lifestyle That Mirrors the Work</div>
      <p class="section-subtitle">
        Here’s where I share the tangible side of my journey—cars, watches, spaces,
        and places that represent years of quiet effort.
      </p>

      <div class="gallery-grid">
        <div class="gallery-main">
          <div class="gallery-overlay"></div>
          <div class="gallery-main-inner">
            <div class="gallery-main-label">Featured Moment</div>
            <div class="gallery-main-title">First Porsche Test Drive</div>
            <div class="gallery-main-sub">
              The day I realized the gap between “one day” and “this year” is just a
              matter of standards and execution.
            </div>
          </div>
        </div>
        <div class="gallery-secondary">
          <div class="gallery-card">
            <div class="gallery-card-main">
              <div class="gallery-card-tag">Wrist check</div>
              <div class="gallery-card-title">A watch as a reminder</div>
              <div class="gallery-card-meta">
                Documenting Rolex &amp; other timepieces as milestones, not trophies.
              </div>
            </div>
            <div style="font-size:20px;">⌚</div>
          </div>
          <div class="gallery-card">
            <div class="gallery-card-main">
              <div class="gallery-card-tag">Travel</div>
              <div class="gallery-card-title">Stamps, views, and perspective</div>
              <div class="gallery-card-meta">
                Trips focused on experience, growth, and gratitude—not just photos.
              </div>
            </div>
            <div style="font-size:20px;">✈️</div>
          </div>
          <div class="gallery-card">
            <div class="gallery-card-main">
              <div class="gallery-card-tag">Home</div>
              <div class="gallery-card-title">Warm minimal interiors</div>
              <div class="gallery-card-meta">
                Cozy, clean, and intentional spaces that make thinking clearly easier.
              </div>
            </div>
            <div style="font-size:20px;">🏡</div>
          </div>
        </div>
      </div>
    </section>

    <!-- JOURNAL -->
    <section id="journal">
      <div class="section-heading">Journal</div>
      <div class="section-title">Recent Entries</div>
      <p class="section-subtitle">
        Short reflections on what I’m learning in real time—from money and mindset to
        training and travel. These are the thoughts behind the photos.
      </p>

      <div class="journal-grid">
        <article class="post-card">
          <div class="post-tag">Mindset</div>
          <h3 class="post-title">Luxury is a mirror, not the goal</h3>
          <p class="post-excerpt">
            Today I caught myself wanting something just because it looked impressive.
            Here’s how I stepped back and asked what it actually meant to me…
          </p>
          <div class="post-meta">
            <span>Draft entry</span>
            <span>3 min read</span>
          </div>
        </article>

        <article class="post-card">
          <div class="post-tag">Fitness</div>
          <h3 class="post-title">Treating my body like a supercar</h3>
          <p class="post-excerpt">
            I’d never drive a Porsche on cheap oil and missed maintenance. Why would I
            do that to my own body?
          </p>
          <div class="post-meta">
            <span>Coming soon</span>
            <span>Gym · Routine</span>
          </div>
        </article>

        <article class="post-card">
          <div class="post-tag">Travel</div>
          <h3 class="post-title">The trips that changed my ambition</h3>
          <p class="post-excerpt">
            Certain cities make you realize how big the world is—and how small your
            excuses really are.
          </p>
          <div class="post-meta">
            <span>Coming soon</span>
            <span>Perspective</span>
          </div>
        </article>
      </div>
    </section>

    <!-- CONTACT / SOCIAL -->
    <section id="contact">
      <div class="section-heading">Stay Connected</div>
      <div class="section-title">Follow the Journey in Real Time</div>
      <p class="section-subtitle">
        This site is the long-form version of my story. For day-to-day updates—gym,
        snapshots, and behind-the-scenes—connect with me here.
      </p>

      <div class="contact-card">
        <div class="contact-main">
          <h3>Let’s Build Better Lives</h3>
          <p>
            If my journey resonates with you, follow along—or reach out. I want this space
            to inspire you to raise your own standards, not copy mine.
          </p>
        </div>
        <div class="contact-links">
          <!-- Replace # with your real links -->
          <a class="contact-pill" href="#">
            <span>📸</span>
            <span>Instagram</span>
          </a>
          <a class="contact-pill" href="#">
            <span>🎥</span>
            <span>YouTube / Shorts</span>
          </a>
          <a class="contact-pill" href="mailto:youremail@example.com">
            <span>✉️</span>
            <span>Email</span>
          </a>
          <a class="contact-pill" href="#">
            <span>✍️</span>
            <span>Newsletter (coming soon)</span>
          </a>
        </div>
      </div>
    </section>

    <!-- FOOTER -->
    <footer>
      <span>© <span id="year"></span> Edward J. Rhee · Self-Growth in Motion</span>
      <span>Built with intention, warm light, and high standards.</span>
    </footer>
  </div>

  <script>
    // Footer year
    document.getElementById('year').textContent = new Date().getFullYear();

    // THEME TOGGLE (Day / Night drive)
    (function () {
      const body = document.body;
      const toggle = document.getElementById('themeToggle');
      const icon = document.getElementById('themeIcon');
      const label = document.getElementById('themeLabel');

      // Load stored preference
      try {
        const stored = window.localStorage.getItem('ejr-theme');
        if (stored === 'night') {
          body.setAttribute('data-theme', 'night');
          icon.textContent = '🌙';
          label.textContent = 'Night drive';
        }
      } catch (e) {
        // ignore localStorage errors
      }

      toggle.addEventListener('click', () => {
        const current = body.getAttribute('data-theme') || 'day';
        const next = current === 'day' ? 'night' : 'day';
        body.setAttribute('data-theme', next);

        try {
          window.localStorage.setItem('ejr-theme', next);
        } catch (e) {}

        if (next === 'night') {
          icon.textContent = '🌙';
          label.textContent = 'Night drive';
        } else {
          icon.textContent = '☀️';
          label.textContent = 'Day drive';
        }
      });
    })();

    // EXPERIENCE TABS (interactive pages)
    (function () {
      const tabs = Array.from(document.querySelectorAll('.xp-tab'));
      const pages = {
        cars: document.getElementById('xp-cars'),
        watches: document.getElementById('xp-watches'),
        travel: document.getElementById('xp-travel'),
        fitness: document.getElementById('xp-fitness'),
      };
      const indicator = document.getElementById('xpIndicator');

      function setActive(pageKey, labelText) {
        tabs.forEach(t => {
          const key = t.getAttribute('data-page');
          t.setAttribute('data-active', key === pageKey ? 'true' : 'false');
        });
        Object.keys(pages).forEach(key => {
          pages[key].setAttribute('data-visible', key === pageKey ? 'true' : 'false');
        });
        indicator.textContent = 'Page: ' + labelText;
      }

      tabs.forEach(tab => {
        tab.addEventListener('click', () => {
          const key = tab.getAttribute('data-page');
          const label = tab.innerText.trim(); // text without HTML syntax
          setActive(key, label);
        });
      });
    })();

    // SLIDERS: show value + store to localStorage
    (function () {
      function bindSlider(id, valueId, unit, storageKey) {
        const slider = document.getElementById(id);
        const output = document.getElementById(valueId);
        if (!slider || !output) return;

        // Load saved value if any
        try {
          const saved = window.localStorage.getItem(storageKey);
          if (saved !== null) {
            slider.value = saved;
          }
        } catch (e) {}

        // Initial display
        output.textContent = slider.value + unit;

        slider.addEventListener('input', () => {
          output.textContent = slider.value + unit;
          try {
            window.localStorage.setItem(storageKey, slider.value);
          } catch (e) {}
        });
      }

      bindSlider('sliderGarage', 'sliderGarageValue', '%', 'ejr-garage');
      bindSlider('sliderTime', 'sliderTimeValue', ' hrs', 'ejr-time');
      bindSlider('sliderTravel', 'sliderTravelValue', '%', 'ejr-travel');
      bindSlider('sliderEnergy', 'sliderEnergyValue', '%', 'ejr-energy');
    })();
  </script>
</body>
</html>
