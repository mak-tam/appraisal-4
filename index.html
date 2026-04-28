<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>TAM Self-Assessment Workbook — Advisory</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,500;0,9..144,600;0,9..144,700;1,9..144,400&family=Inter+Tight:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --ink: #0d0b1f;
    --ink-soft: #2a2640;
    --ink-muted: #6b6783;
    --paper: #f5f1e8;
    --paper-warm: #ebe4d3;
    --paper-deep: #e0d7c0;
    --indigo: #4f46e5;
    --indigo-deep: #3730a3;
    --indigo-dark: #1e1b4b;
    --accent: #fbbf24;
    --accent-deep: #f59e0b;
    --rose: #e11d48;
    --line: rgba(13, 11, 31, 0.12);
    --line-strong: rgba(13, 11, 31, 0.28);
    --shadow-sm: 0 1px 2px rgba(13, 11, 31, 0.06);
    --shadow-md: 0 4px 16px rgba(13, 11, 31, 0.08);
    --shadow-lg: 0 20px 48px rgba(13, 11, 31, 0.12);
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    font-family: 'Inter Tight', -apple-system, sans-serif;
    background: var(--paper);
    color: var(--ink);
    line-height: 1.55;
    font-size: 15px;
    overflow-x: hidden;
  }

  /* Subtle noise overlay for paper texture */
  body::before {
    content: '';
    position: fixed;
    inset: 0;
    pointer-events: none;
    opacity: 0.4;
    z-index: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='2' stitchTiles='stitch'/%3E%3CfeColorMatrix values='0 0 0 0 0.05 0 0 0 0 0.04 0 0 0 0 0.12 0 0 0 0 0 0 0.08 0'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");
  }

  /* ============ GATE (department + level selector) ============ */
  body.gate-active {
    overflow: hidden;
  }
  body.gate-active .wrap,
  body.gate-active section.export {
    visibility: hidden;
  }

  .gate {
    position: fixed;
    inset: 0;
    z-index: 300;
    background: linear-gradient(135deg, #1e1b4b 0%, #2d1b69 60%, #0d0b1f 100%);
    color: var(--paper);
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 40px 24px;
    overflow-y: auto;
  }
  .gate.hidden {
    display: none;
  }

  .gate-bg-noise {
    position: absolute;
    inset: 0;
    pointer-events: none;
    opacity: 0.35;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='gn'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='2' stitchTiles='stitch'/%3E%3CfeColorMatrix values='0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.05 0'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23gn)'/%3E%3C/svg%3E");
  }

  .gate-inner {
    position: relative;
    z-index: 2;
    max-width: 640px;
    width: 100%;
  }

  .gate-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 64px;
    padding-bottom: 20px;
    border-bottom: 1px solid rgba(245, 241, 232, 0.15);
  }

  .gate-brand {
    color: #ffffff;
    font-size: 38px;
    font-weight: 700;
    letter-spacing: -0.025em;
  }
  .gate-brand .diamond {
    background: var(--accent);
    width: 18px;
    height: 18px;
  }

  .gate-eyebrow {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    color: rgba(245, 241, 232, 0.6);
  }

  .gate-title {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: clamp(38px, 5.5vw, 64px);
    line-height: 1;
    letter-spacing: -0.03em;
    margin-bottom: 16px;
    color: var(--paper);
  }
  .gate-title em {
    font-style: italic;
    font-weight: 400;
    color: var(--accent);
  }

  .gate-sub {
    font-size: 16px;
    line-height: 1.6;
    color: rgba(245, 241, 232, 0.75);
    max-width: 520px;
    margin-bottom: 48px;
  }

  .gate-fields {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin-bottom: 28px;
  }

  .gate-field {
    display: flex;
    flex-direction: column;
  }

  .gate-field .field-label {
    color: var(--accent);
    margin-bottom: 8px;
  }
  .gate-field .field-label .opt-tag {
    color: rgba(245, 241, 232, 0.5);
    font-weight: 400;
    text-transform: none;
    letter-spacing: 0.04em;
    margin-left: 6px;
  }
  .gate-fields-track { margin-top: -8px; }

  .gate-field select {
    width: 100%;
    background: rgba(245, 241, 232, 0.08);
    border: 1px solid rgba(245, 241, 232, 0.2);
    color: var(--paper);
    padding: 14px 16px;
    font-size: 15px;
    font-family: inherit;
    border-radius: 3px;
    cursor: pointer;
    transition: all 0.2s;
    appearance: none;
    background-image: url("data:image/svg+xml,%3Csvg width='12' height='8' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M1 1l5 5 5-5' stroke='%23fbbf24' stroke-width='1.5' fill='none'/%3E%3C/svg%3E");
    background-repeat: no-repeat;
    background-position: right 14px center;
    padding-right: 40px;
  }
  .gate-field select:focus {
    outline: none;
    border-color: var(--accent);
    background-color: rgba(245, 241, 232, 0.12);
  }
  .gate-field select:disabled {
    opacity: 0.4;
    cursor: not-allowed;
  }
  .gate-field select option {
    background: var(--indigo-dark);
    color: var(--paper);
  }

  .gate-status {
    min-height: 24px;
    margin-bottom: 16px;
    font-size: 13px;
    color: var(--accent);
    font-style: italic;
  }
  .gate-status.muted {
    color: rgba(245, 241, 232, 0.55);
    font-style: normal;
  }

  .gate-actions {
    margin-bottom: 32px;
  }

  .btn-lg {
    padding: 18px 36px;
    font-size: 12px;
  }

  .btn-primary:disabled {
    background: rgba(245, 241, 232, 0.15);
    color: rgba(245, 241, 232, 0.4);
    cursor: not-allowed;
    transform: none;
  }
  .btn-primary:disabled:hover {
    background: rgba(245, 241, 232, 0.15);
    color: rgba(245, 241, 232, 0.4);
    transform: none;
  }

  .gate-footnote {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: rgba(245, 241, 232, 0.4);
    line-height: 1.7;
    padding-top: 24px;
    border-top: 1px solid rgba(245, 241, 232, 0.1);
  }

  @media (max-width: 640px) {
    .gate-fields { grid-template-columns: 1fr; }
    .gate-header { margin-bottom: 40px; }
    .gate-sub { margin-bottom: 32px; }
  }

  .wrap {
    position: relative;
    z-index: 1;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 32px;
  }

  /* ============ HEADER ============ */
  header.masthead {
    padding: 40px 0 28px;
    border-bottom: 1px solid var(--line);
    position: relative;
  }

  .masthead-row {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 32px;
  }

  .brand {
    display: flex;
    align-items: center;
    gap: 16px;
  }

  .brand-mark {
    font-family: 'Fraunces', serif;
    font-weight: 600;
    font-size: 28px;
    letter-spacing: -0.02em;
    color: var(--ink);
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .brand-mark .diamond {
    width: 14px;
    height: 14px;
    background: var(--indigo);
    transform: rotate(45deg);
    display: inline-block;
  }

  .meta-pill {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: var(--ink-muted);
    padding: 8px 14px;
    border: 1px solid var(--line-strong);
    border-radius: 100px;
    background: rgba(255, 255, 255, 0.4);
  }

  .title-block {
    margin-top: 48px;
    display: grid;
    grid-template-columns: 1fr auto;
    gap: 48px;
    align-items: end;
  }

  h1.title {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: clamp(42px, 6vw, 76px);
    line-height: 0.95;
    letter-spacing: -0.035em;
    color: var(--ink);
  }

  h1.title em {
    font-style: italic;
    font-weight: 400;
    color: var(--indigo-deep);
  }

  .title-side {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    line-height: 1.8;
    color: var(--ink-muted);
    max-width: 280px;
    text-align: right;
    padding-bottom: 12px;
  }

  .title-side strong {
    color: var(--ink);
    font-weight: 500;
  }

  .change-link {
    color: var(--indigo-deep);
    text-decoration: none;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    border-bottom: 1px dotted var(--indigo-deep);
    padding-bottom: 1px;
  }
  .change-link:hover {
    color: var(--ink);
    border-bottom-color: var(--ink);
  }

  .intro {
    margin-top: 40px;
    max-width: 620px;
    font-size: 17px;
    line-height: 1.65;
    color: var(--ink-soft);
  }

  .intro em {
    font-family: 'Fraunces', serif;
    font-style: italic;
    color: var(--indigo-deep);
  }

  /* ============ PROGRESS NAV ============ */
  .progress-nav {
    position: sticky;
    top: 0;
    z-index: 50;
    background: var(--paper);
    padding: 20px 0;
    margin-top: 56px;
    border-top: 1px solid var(--line);
    border-bottom: 1px solid var(--line);
  }

  .progress-nav::before {
    content: '';
    position: absolute;
    inset: 0;
    background: var(--paper);
    opacity: 0.95;
    backdrop-filter: blur(8px);
    z-index: -1;
  }

  .progress-wrap {
    display: flex;
    align-items: center;
    gap: 4px;
    flex-wrap: wrap;
  }

  .prog-item {
    flex: 1;
    min-width: 120px;
    position: relative;
    padding: 12px 0;
    cursor: pointer;
    border-top: 2px solid var(--line);
    transition: border-color 0.3s;
  }

  .prog-item.active { border-top-color: var(--indigo); }
  .prog-item.done { border-top-color: var(--accent-deep); }

  .prog-item:hover { border-top-color: var(--ink); }

  .prog-num {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    color: var(--ink-muted);
    letter-spacing: 0.1em;
  }

  .prog-label {
    font-family: 'Fraunces', serif;
    font-size: 15px;
    color: var(--ink);
    margin-top: 2px;
    font-weight: 500;
  }

  .prog-item.done .prog-num::after {
    content: ' ✓';
    color: var(--accent-deep);
  }

  /* ============ SECTION ============ */
  section.dimension {
    padding: 80px 0 100px;
    border-bottom: 1px solid var(--line);
    position: relative;
  }

  section.dimension:last-of-type {
    border-bottom: none;
  }

  .section-header {
    display: grid;
    grid-template-columns: 100px 1fr;
    gap: 32px;
    align-items: start;
    margin-bottom: 48px;
  }

  .section-num {
    font-family: 'Fraunces', serif;
    font-style: italic;
    font-weight: 400;
    font-size: 72px;
    line-height: 1;
    color: var(--indigo-deep);
    letter-spacing: -0.03em;
  }

  .section-title {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 40px;
    line-height: 1.05;
    letter-spacing: -0.025em;
    color: var(--ink);
  }

  .section-desc {
    font-size: 15px;
    color: var(--ink-muted);
    margin-top: 12px;
    max-width: 640px;
    line-height: 1.6;
  }

  /* ============ FRAMEWORK CONTEXT CARD ============ */
  .framework-card {
    background: var(--ink-dark, #1e1b4b);
    background: linear-gradient(135deg, var(--indigo-dark) 0%, #2d1b69 100%);
    color: var(--paper);
    padding: 28px 32px;
    border-radius: 4px;
    margin-bottom: 32px;
    position: relative;
    overflow: hidden;
  }

  .framework-card::before {
    content: '';
    position: absolute;
    top: -50%;
    right: -20%;
    width: 400px;
    height: 400px;
    background: radial-gradient(circle, rgba(251, 191, 36, 0.08) 0%, transparent 70%);
    pointer-events: none;
  }

  .framework-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    color: var(--accent);
    margin-bottom: 12px;
  }

  .framework-title {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 20px;
    margin-bottom: 10px;
    color: var(--paper);
  }

  .framework-desc {
    font-size: 14px;
    line-height: 1.65;
    color: rgba(245, 241, 232, 0.82);
    max-width: 780px;
  }

  .framework-indicators {
    margin-top: 20px;
    padding-top: 20px;
    border-top: 1px solid rgba(245, 241, 232, 0.15);
  }

  .framework-indicators summary {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: var(--accent);
    cursor: pointer;
    list-style: none;
    display: flex;
    align-items: center;
    gap: 8px;
    user-select: none;
  }

  .framework-indicators summary::-webkit-details-marker { display: none; }

  .framework-indicators summary::before {
    content: '+';
    display: inline-block;
    width: 16px;
    height: 16px;
    line-height: 14px;
    text-align: center;
    border: 1px solid var(--accent);
    border-radius: 50%;
    font-size: 12px;
    transition: transform 0.2s;
  }

  .framework-indicators[open] summary::before {
    content: '−';
    transform: rotate(180deg);
  }

  .indicator-list {
    margin-top: 16px;
    display: grid;
    gap: 12px;
  }

  .indicator-list li {
    list-style: none;
    padding-left: 20px;
    position: relative;
    font-size: 13px;
    color: rgba(245, 241, 232, 0.85);
    line-height: 1.55;
  }

  .indicator-list li::before {
    content: '';
    position: absolute;
    left: 0;
    top: 8px;
    width: 8px;
    height: 8px;
    background: var(--accent);
    transform: rotate(45deg);
  }

  .indicator-list li strong {
    color: var(--paper);
    font-weight: 600;
    display: block;
    margin-bottom: 2px;
    font-size: 13px;
  }

  /* ============ EVIDENCE ENTRIES ============ */
  .entries {
    display: flex;
    flex-direction: column;
    gap: 16px;
  }

  .entry {
    background: rgba(255, 255, 255, 0.55);
    border: 1px solid var(--line);
    border-radius: 4px;
    padding: 24px;
    position: relative;
    transition: border-color 0.2s;
  }

  .entry:focus-within {
    border-color: var(--indigo);
    box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.1);
  }

  .entry-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 16px;
  }

  .entry-header-left {
    display: flex;
    align-items: center;
    gap: 10px;
  }

  .entry-num {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--ink-muted);
    letter-spacing: 0.1em;
    text-transform: uppercase;
  }

  .entry-tag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 9px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    padding: 3px 8px;
    border-radius: 100px;
    font-weight: 500;
  }
  .entry-tag-required {
    background: var(--indigo);
    color: var(--paper);
  }
  .entry-tag-optional {
    background: rgba(13, 11, 31, 0.06);
    color: var(--ink-muted);
    border: 1px solid var(--line);
  }

  .entry-required {
    border-left: 3px solid var(--indigo);
  }
  .entry-required.entry-error {
    border-left-color: var(--rose);
    box-shadow: 0 0 0 2px rgba(225, 29, 72, 0.1);
  }
  .entry-optional {
    border-left: 3px solid rgba(13, 11, 31, 0.08);
  }

  .remove-btn {
    background: none;
    border: none;
    color: var(--ink-muted);
    font-size: 18px;
    cursor: pointer;
    padding: 4px 8px;
    line-height: 1;
    border-radius: 4px;
    transition: all 0.2s;
  }

  .remove-btn:hover {
    color: var(--rose);
    background: rgba(225, 29, 72, 0.08);
  }

  .field {
    margin-bottom: 16px;
  }

  .field:last-child { margin-bottom: 0; }

  .field-label {
    display: block;
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.12em;
    color: var(--ink-muted);
    margin-bottom: 6px;
    font-weight: 500;
  }

  .field-label .req {
    color: var(--rose);
    margin-left: 2px;
  }

  .field-hint {
    font-size: 12px;
    color: var(--ink-muted);
    margin-top: 4px;
    font-style: italic;
  }

  input[type="text"], textarea, select {
    width: 100%;
    font-family: inherit;
    font-size: 14px;
    color: var(--ink);
    background: rgba(255, 255, 255, 0.8);
    border: 1px solid var(--line-strong);
    border-radius: 3px;
    padding: 10px 12px;
    transition: all 0.2s;
    line-height: 1.5;
  }

  input[type="text"]:focus, textarea:focus, select:focus {
    outline: none;
    border-color: var(--indigo);
    background: #fff;
  }

  textarea {
    resize: vertical;
    min-height: 80px;
  }

  .entry-title {
    font-family: 'Fraunces', serif;
    font-size: 18px;
    font-weight: 500;
    border: none;
    background: transparent;
    padding: 0;
    border-bottom: 1px dashed var(--line-strong);
    border-radius: 0;
    padding-bottom: 6px;
    color: var(--ink);
  }

  .entry-title::placeholder {
    font-style: italic;
    color: var(--ink-muted);
  }

  .entry-title:focus {
    border-bottom-color: var(--indigo);
    background: transparent;
  }

  /* Add entry button */
  .add-entry {
    margin-top: 4px;
    padding: 18px;
    border: 1.5px dashed var(--line-strong);
    background: transparent;
    border-radius: 4px;
    width: 100%;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.12em;
    color: var(--ink-muted);
    cursor: pointer;
    transition: all 0.2s;
  }

  .add-entry:hover {
    border-color: var(--indigo);
    color: var(--indigo);
    background: rgba(79, 70, 229, 0.04);
  }

  /* ============ SELF-RATING BLOCK ============ */
  .rating-block {
    margin-top: 32px;
    background: var(--paper-warm);
    border: 1px solid var(--line-strong);
    padding: 28px;
    border-radius: 4px;
  }

  .rating-block-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    color: var(--indigo-deep);
    margin-bottom: 8px;
  }

  .rating-block-title {
    font-family: 'Fraunces', serif;
    font-size: 22px;
    font-weight: 500;
    color: var(--ink);
    margin-bottom: 4px;
  }

  .rating-block-sub {
    font-size: 13px;
    color: var(--ink-muted);
    margin-bottom: 20px;
  }

  .rating-options {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 8px;
  }

  .rating-option {
    position: relative;
    cursor: pointer;
  }

  .rating-option input {
    position: absolute;
    opacity: 0;
    pointer-events: none;
  }

  .rating-card {
    padding: 14px 12px;
    background: rgba(255, 255, 255, 0.5);
    border: 1.5px solid var(--line);
    border-radius: 3px;
    transition: all 0.2s;
    height: 100%;
  }

  .rating-option:hover .rating-card {
    border-color: var(--ink-muted);
    background: rgba(255, 255, 255, 0.8);
  }

  .rating-option input:checked + .rating-card {
    border-color: var(--indigo);
    background: #fff;
    box-shadow: 0 0 0 2px rgba(79, 70, 229, 0.15);
  }

  .rating-name {
    font-family: 'Fraunces', serif;
    font-weight: 600;
    font-size: 13px;
    color: var(--ink);
    margin-bottom: 6px;
    line-height: 1.2;
  }

  .rating-option input:checked + .rating-card .rating-name {
    color: var(--indigo-deep);
  }

  .rating-desc {
    font-size: 11px;
    color: var(--ink-muted);
    line-height: 1.4;
  }

  /* Values rating (4-option) */
  .rating-options.three-col {
    grid-template-columns: repeat(4, 1fr);
  }

  .values-grid {
    display: grid;
    gap: 20px;
    margin-top: 8px;
  }

  .value-row {
    background: rgba(255, 255, 255, 0.55);
    border: 1px solid var(--line);
    padding: 20px 24px;
    border-radius: 4px;
  }

  .value-header {
    display: flex;
    align-items: baseline;
    gap: 14px;
    margin-bottom: 14px;
  }

  .value-name {
    font-family: 'Fraunces', serif;
    font-size: 19px;
    font-weight: 500;
    color: var(--ink);
  }

  .value-name .diamond {
    width: 9px;
    height: 9px;
    background: var(--accent-deep);
    display: inline-block;
    transform: rotate(45deg);
    margin-right: 8px;
    vertical-align: middle;
  }

  .value-tagline {
    font-size: 12px;
    color: var(--ink-muted);
    font-style: italic;
  }

  .value-field {
    margin-bottom: 14px;
  }

  /* ============ OVERALL RATING (standout) ============ */
  section.overall-section {
    border-bottom: none;
    padding: 0;
  }

  .overall-stage {
    margin-top: 40px;
    padding: 64px 56px 72px;
    background: linear-gradient(135deg, #1e1b4b 0%, #2d1b69 60%, #0d0b1f 100%);
    color: var(--paper);
    border-radius: 4px;
    position: relative;
    overflow: hidden;
  }

  .overall-stage::before {
    content: '';
    position: absolute;
    top: -10%;
    left: -5%;
    width: 380px;
    height: 380px;
    background: radial-gradient(circle, rgba(251, 191, 36, 0.10) 0%, transparent 65%);
    pointer-events: none;
  }
  .overall-stage::after {
    content: '';
    position: absolute;
    bottom: -20%;
    right: -10%;
    width: 500px;
    height: 500px;
    background: radial-gradient(circle, rgba(79, 70, 229, 0.18) 0%, transparent 65%);
    pointer-events: none;
  }

  .overall-eyebrow {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.18em;
    color: var(--accent);
    margin-bottom: 24px;
    position: relative;
    z-index: 2;
  }

  .overall-headline {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: clamp(34px, 4.2vw, 52px);
    line-height: 1.05;
    letter-spacing: -0.025em;
    color: var(--paper);
    margin-bottom: 20px;
    position: relative;
    z-index: 2;
  }
  .overall-headline em {
    font-style: italic;
    font-weight: 400;
    color: var(--accent);
  }

  .overall-sub {
    font-size: 16px;
    line-height: 1.65;
    color: rgba(245, 241, 232, 0.75);
    max-width: 680px;
    margin-bottom: 40px;
    position: relative;
    z-index: 2;
  }

  .overall-rating-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 12px;
    position: relative;
    z-index: 2;
  }

  .overall-rating-option {
    cursor: pointer;
    position: relative;
  }
  .overall-rating-option input {
    position: absolute;
    opacity: 0;
    pointer-events: none;
  }

  .overall-rating-card {
    padding: 24px 20px;
    background: rgba(245, 241, 232, 0.06);
    border: 1.5px solid rgba(245, 241, 232, 0.2);
    border-radius: 3px;
    height: 100%;
    transition: all 0.2s;
  }
  .overall-rating-option:hover .overall-rating-card {
    background: rgba(245, 241, 232, 0.12);
    border-color: rgba(245, 241, 232, 0.4);
  }
  .overall-rating-option input:checked + .overall-rating-card {
    background: var(--accent);
    border-color: var(--accent);
    color: var(--ink-dark, #1e1b4b);
    box-shadow: 0 8px 24px rgba(251, 191, 36, 0.25);
  }
  .overall-rating-option input:checked + .overall-rating-card .overall-rating-num,
  .overall-rating-option input:checked + .overall-rating-card .overall-rating-name,
  .overall-rating-option input:checked + .overall-rating-card .overall-rating-desc {
    color: var(--ink-dark, #1e1b4b);
  }

  .overall-rating-num {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--accent);
    letter-spacing: 0.08em;
    margin-bottom: 12px;
  }
  .overall-rating-name {
    font-family: 'Fraunces', serif;
    font-weight: 600;
    font-size: 17px;
    color: var(--paper);
    margin-bottom: 8px;
    line-height: 1.15;
  }
  .overall-rating-desc {
    font-size: 12px;
    color: rgba(245, 241, 232, 0.65);
    line-height: 1.5;
  }

  @media (max-width: 900px) {
    .overall-rating-grid { grid-template-columns: repeat(2, 1fr); }
    .overall-stage { padding: 48px 28px; }
  }

  /* ============ EXPORT SECTION ============ */
  section.export {
    padding: 100px 0 140px;
    background: var(--ink-dark, #1e1b4b);
    background: linear-gradient(180deg, #1e1b4b 0%, #0d0b1f 100%);
    color: var(--paper);
    margin-top: 60px;
    position: relative;
    overflow: hidden;
  }

  section.export::before {
    content: '';
    position: absolute;
    top: 10%;
    left: -10%;
    width: 500px;
    height: 500px;
    background: radial-gradient(circle, rgba(251, 191, 36, 0.12) 0%, transparent 60%);
    pointer-events: none;
  }

  section.export::after {
    content: '';
    position: absolute;
    bottom: 0;
    right: -5%;
    width: 400px;
    height: 400px;
    background: radial-gradient(circle, rgba(79, 70, 229, 0.18) 0%, transparent 60%);
    pointer-events: none;
  }

  .export .section-num { color: var(--accent); }
  .export .section-title { color: var(--paper); }
  .export .section-desc { color: rgba(245, 241, 232, 0.7); }

  .export-actions {
    display: flex;
    gap: 16px;
    margin-top: 40px;
    flex-wrap: wrap;
  }

  .btn {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    padding: 16px 28px;
    border: none;
    border-radius: 3px;
    cursor: pointer;
    transition: all 0.2s;
    font-weight: 500;
  }

  .btn-primary {
    background: var(--accent);
    color: var(--ink-dark, #1e1b4b);
  }

  .btn-primary:hover {
    background: #fcd34d;
    transform: translateY(-1px);
  }

  .btn-ghost {
    background: transparent;
    color: var(--paper);
    border: 1px solid rgba(245, 241, 232, 0.3);
  }

  .btn-ghost:hover {
    border-color: var(--accent);
    color: var(--accent);
  }

  /* Preview area */
  .preview {
    margin-top: 48px;
    background: var(--paper);
    color: var(--ink);
    padding: 48px 56px;
    border-radius: 4px;
    box-shadow: var(--shadow-lg);
    max-height: 600px;
    overflow-y: auto;
    font-size: 14px;
    line-height: 1.65;
    display: none;
  }

  .preview.visible { display: block; }

  .preview h2 {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 28px;
    margin-bottom: 4px;
    color: var(--ink);
  }

  .preview .sub {
    color: var(--ink-muted);
    font-size: 13px;
    margin-bottom: 28px;
    font-family: 'JetBrains Mono', monospace;
    letter-spacing: 0.05em;
  }

  .preview h3 {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 20px;
    margin-top: 28px;
    margin-bottom: 12px;
    color: var(--indigo-deep);
    padding-bottom: 4px;
    border-bottom: 1px solid var(--line);
  }

  .preview h4 {
    font-family: 'Inter Tight', sans-serif;
    font-weight: 600;
    font-size: 14px;
    margin-top: 14px;
    margin-bottom: 4px;
    color: var(--ink);
  }

  .preview p { margin-bottom: 10px; }

  .preview .rating-line {
    background: var(--paper-warm);
    padding: 12px 16px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    margin: 12px 0 20px;
    border-left: 3px solid var(--indigo);
    border-radius: 2px;
  }

  .preview .empty {
    color: var(--ink-muted);
    font-style: italic;
    font-size: 13px;
  }

  /* ============ FOOTER ============ */
  footer {
    padding: 48px 0 64px;
    border-top: 1px solid var(--line);
    margin-top: 0;
    color: var(--ink-muted);
    font-size: 12px;
    font-family: 'JetBrains Mono', monospace;
    letter-spacing: 0.05em;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 16px;
  }

  /* ============ EMPLOYEE INFO BLOCK ============ */
  .employee-info {
    margin-top: 48px;
    padding: 32px;
    background: rgba(255, 255, 255, 0.5);
    border: 1px solid var(--line);
    border-radius: 4px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
  }

  .employee-info .field {
    margin-bottom: 0;
  }

  /* ============ RESPONSIVE ============ */
  @media (max-width: 768px) {
    .wrap { padding: 0 20px; }
    .title-block { grid-template-columns: 1fr; gap: 24px; }
    .title-side { text-align: left; max-width: 100%; }
    .section-header { grid-template-columns: 1fr; gap: 16px; }
    .section-num { font-size: 56px; }
    .section-title { font-size: 30px; }
    .rating-options { grid-template-columns: 1fr 1fr; }
    .rating-options.three-col { grid-template-columns: 1fr 1fr; }
    .employee-info { grid-template-columns: 1fr; }
    .export-actions { flex-direction: column; }
    .btn { width: 100%; }
    .preview { padding: 28px 24px; }
  }

  /* Print styles */
  @media print {
    body::before { display: none; }
    .progress-nav, section.export, .export-actions, footer { display: none; }
    .preview { max-height: none; box-shadow: none; }
  }

  /* ============ ADMIN MODAL ============ */
  .admin-link {
    color: var(--ink-muted);
    text-decoration: none;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    border-bottom: 1px dotted var(--ink-muted);
    padding-bottom: 1px;
    transition: color 0.2s, border-color 0.2s;
  }
  .admin-link:hover {
    color: var(--indigo-deep);
    border-bottom-color: var(--indigo-deep);
  }
  .footer-sep {
    margin: 0 12px;
    color: var(--line);
  }

  .admin-overlay {
    position: fixed;
    inset: 0;
    background: rgba(13, 11, 31, 0.6);
    backdrop-filter: blur(4px);
    z-index: 200;
    display: none;
    align-items: flex-start;
    justify-content: center;
    padding: 5vh 24px;
    overflow-y: auto;
  }
  .admin-overlay.show { display: flex; }

  .admin-modal {
    background: var(--paper);
    border-radius: 4px;
    box-shadow: 0 30px 80px rgba(0,0,0,0.4);
    width: 100%;
    max-width: 900px;
    max-height: 90vh;
    display: flex;
    flex-direction: column;
    overflow: hidden;
  }

  .admin-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    padding: 28px 36px 20px;
    border-bottom: 1px solid var(--line);
    background: linear-gradient(135deg, var(--indigo-dark) 0%, #2d1b69 100%);
    color: var(--paper);
  }
  .admin-eyebrow {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    color: var(--accent);
    margin-bottom: 4px;
  }
  .admin-title {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 26px;
    letter-spacing: -0.02em;
    color: var(--paper);
  }
  .admin-close {
    background: none;
    border: none;
    color: var(--paper);
    font-size: 28px;
    cursor: pointer;
    line-height: 1;
    opacity: 0.7;
    transition: opacity 0.2s;
    padding: 0 6px;
  }
  .admin-close:hover { opacity: 1; }

  .admin-login {
    padding: 40px 36px;
  }
  .admin-login-msg {
    font-size: 14px;
    color: var(--ink-soft);
    margin-bottom: 16px;
  }
  .admin-login-row {
    display: flex;
    gap: 8px;
    margin-bottom: 12px;
  }
  .admin-login-row input {
    flex: 1;
    padding: 12px 14px;
    border: 1px solid var(--line-strong);
    border-radius: 3px;
    font-size: 14px;
    background: #fff;
  }
  .admin-login-row input:focus {
    outline: none;
    border-color: var(--indigo);
  }
  .admin-login-hint {
    font-size: 12px;
    color: var(--ink-muted);
  }
  .admin-login-hint code {
    background: var(--paper-warm);
    padding: 2px 6px;
    border-radius: 3px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: var(--ink);
  }

  .admin-body {
    flex: 1;
    display: flex;
    flex-direction: column;
    overflow: hidden;
  }

  .admin-toolbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 36px;
    border-bottom: 1px solid var(--line);
    background: var(--paper-warm);
  }
  .admin-stats {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    text-transform: uppercase;
    letter-spacing: 0.08em;
    color: var(--ink-soft);
  }
  .admin-toolbar-actions {
    display: flex;
    gap: 8px;
  }

  .btn-sm {
    padding: 10px 16px;
    font-size: 10px;
  }
  .btn-danger {
    background: var(--rose);
    color: var(--paper);
  }
  .btn-danger:hover { background: #be123c; }

  .admin-table-wrap {
    flex: 1;
    overflow-y: auto;
    padding: 0 36px;
  }
  .admin-table {
    width: 100%;
    border-collapse: collapse;
    margin: 16px 0;
  }
  .admin-table th {
    text-align: left;
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: var(--ink-muted);
    font-weight: 500;
    padding: 12px 8px 10px;
    border-bottom: 1px solid var(--line-strong);
  }
  .admin-table td {
    padding: 14px 8px;
    border-bottom: 1px solid var(--line);
    font-size: 13px;
    vertical-align: middle;
  }
  .admin-table tr:hover td { background: rgba(255,255,255,0.5); }
  .admin-table .t-right { text-align: right; }
  .admin-table .name { font-weight: 600; color: var(--ink); }
  .admin-table .rating-pill {
    display: inline-block;
    padding: 4px 10px;
    border-radius: 100px;
    background: var(--indigo-dark);
    color: var(--accent);
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.06em;
  }
  .admin-table .rating-pill.muted {
    background: rgba(13,11,31,0.08);
    color: var(--ink-muted);
  }
  .admin-table .row-action {
    background: none;
    border: 1px solid var(--line-strong);
    padding: 6px 12px;
    border-radius: 3px;
    cursor: pointer;
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.08em;
    color: var(--ink-soft);
    margin-left: 6px;
    transition: all 0.2s;
  }
  .admin-table .row-action:hover { border-color: var(--ink); color: var(--ink); }
  .admin-table .row-action.danger:hover {
    border-color: var(--rose);
    color: var(--rose);
    background: rgba(225,29,72,0.05);
  }

  .admin-empty {
    padding: 48px 0;
    text-align: center;
    color: var(--ink-muted);
    font-style: italic;
    font-size: 13px;
  }

  .admin-danger {
    padding: 16px 36px 24px;
    border-top: 1px solid var(--line);
    text-align: right;
  }


  .toast {
    position: fixed;
    bottom: 32px;
    right: 32px;
    background: var(--ink-dark, #1e1b4b);
    color: var(--paper);
    padding: 14px 22px;
    border-radius: 4px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    box-shadow: var(--shadow-lg);
    transform: translateY(120%);
    transition: transform 0.3s ease;
    z-index: 100;
    border-left: 3px solid var(--accent);
  }

  .toast.show { transform: translateY(0); }
</style>
</head>
<body>

<!-- ============ DEPARTMENT + LEVEL GATE ============ -->
<div class="gate" id="gate">
  <div class="gate-bg-noise"></div>
  <div class="gate-inner">
    <div class="gate-header">
      <div class="brand-mark gate-brand">
        <span class="diamond"></span>
        TAM
      </div>
      <div class="gate-eyebrow">Self-Assessment Workbook · Mid-Year Cycle 2026</div>
    </div>

    <h1 class="gate-title">Let's tailor this <em>to you</em>.</h1>
    <p class="gate-sub">Choose your department and level to load the right competency framework. The workbook below will adapt to match.</p>

    <div class="gate-fields">
      <div class="gate-field">
        <label class="field-label">Department</label>
        <select id="gateDept" onchange="onDeptChange()">
          <option value="">— Select your department —</option>
          <option value="advisory">Advisory</option>
          <option value="bd">Business Development</option>
          <option value="digital">Digital</option>
          <option value="support">Support (Branding · HR · Finance)</option>
        </select>
      </div>

      <div class="gate-field">
        <label class="field-label">Level</label>
        <select id="gateLevel" disabled onchange="onLevelChange()">
          <option value="">— Pick department first —</option>
        </select>
      </div>
    </div>

    <div class="gate-fields gate-fields-track" id="gateTrackRow" style="display:none; grid-template-columns: 1fr;">
      <div class="gate-field">
        <label class="field-label">Track <span class="opt-tag">(Digital only)</span></label>
        <select id="gateTrack" onchange="onTrackChange()">
          <option value="">— Select your track —</option>
        </select>
      </div>
    </div>

    <div class="gate-status" id="gateStatus"></div>

    <div class="gate-actions">
      <button class="btn btn-primary btn-lg" id="gateEnter" onclick="enterWorkbook()" disabled>Enter workbook</button>
    </div>

    <div class="gate-footnote">
      Choose your department and level to load the right competency framework. For Digital, also pick your track. The workbook below will adapt to match.
    </div>
  </div>
</div>

<div class="wrap">

  <!-- ============ MASTHEAD ============ -->
  <header class="masthead">
    <div class="masthead-row">
      <div class="brand">
        <div class="brand-mark">
          <span class="diamond"></span>
          TAM
        </div>
      </div>
      <div class="meta-pill">Mid-Year · Cycle 2026</div>
    </div>

    <div class="title-block">
      <h1 class="title">Your <em>growth</em><br>starts with your story.</h1>
      <div class="title-side">
        <strong>Self-Assessment Workbook</strong><br>
        <span id="ctxDeptLevel">Advisory · Associate Level</span><br>
        — <br>
        Built to help you capture<br>
        what you've accomplished<br>
        with clarity and evidence.
        <br><br>
        <a href="#" class="change-link" onclick="reopenGate(event)">Change selection</a>
      </div>
    </div>

    <p class="intro">
      Your self-assessment is the foundation of a useful conversation about your growth. This workbook walks you through all <em>five dimensions</em> of how TAM evaluates performance, with the <span id="ctxDeptName">Advisory</span> framework for your level surfaced inline. Fill in what you've actually done, with specific examples. Your assessor will use this alongside feedback from your exposure list and your KPIs to write your growth report.
    </p>
  </header>

  <!-- ============ PROGRESS NAV ============ -->
  <nav class="progress-nav">
    <div class="progress-wrap" id="progressNav">
      <a class="prog-item active" data-section="info"><div class="prog-num">00</div><div class="prog-label">About You</div></a>
      <a class="prog-item" data-section="client"><div class="prog-num">01</div><div class="prog-label" id="navLabel-client">Client</div></a>
      <a class="prog-item" data-section="firm"><div class="prog-num">02</div><div class="prog-label" id="navLabel-firm">Firm</div></a>
      <a class="prog-item" data-section="thought"><div class="prog-num">03</div><div class="prog-label" id="navLabel-thought">Thought</div></a>
      <a class="prog-item" data-section="people"><div class="prog-num">04</div><div class="prog-label" id="navLabel-people">People</div></a>
      <a class="prog-item" data-section="values"><div class="prog-num">05</div><div class="prog-label">Values</div></a>
      <a class="prog-item" data-section="overall"><div class="prog-num">06</div><div class="prog-label">Overall</div></a>
      <a class="prog-item" data-section="export"><div class="prog-num">07</div><div class="prog-label">Export</div></a>
    </div>
  </nav>

  <!-- ============ EMPLOYEE INFO ============ -->
  <section class="dimension" id="info">
    <div class="section-header">
      <div class="section-num">00</div>
      <div>
        <div class="section-title">About you</div>
      </div>
    </div>

    <div class="employee-info">
      <div class="field">
        <label class="field-label">Your name</label>
        <input type="text" id="empName" placeholder="Full name" />
      </div>
      <div class="field">
        <label class="field-label">Assessor's name</label>
        <select id="empAssessor">
          <option value="">— Select your assessor —</option>
          <option value="Ammar Alrjoub">Ammar Alrjoub</option>
          <option value="Mayada Akasha">Mayada Akasha</option>
          <option value="Abdullah Alratroot">Abdullah Alratroot</option>
          <option value="Other">Other (specify in chat)</option>
        </select>
      </div>
      <div class="field">
        <label class="field-label">Tenure at TAM</label>
        <input type="text" id="empTenure" placeholder="e.g., 2 years 3 months" />
      </div>
      <div class="field">
        <label class="field-label">Tenure in current position</label>
        <input type="text" id="empPosition" placeholder="e.g., 1 year 1 month" />
      </div>
    </div>
  </section>

  <!-- ============ 1. CLIENT LEADERSHIP ============ -->
  <section class="dimension" id="client">
    <div class="section-header">
      <div class="section-num">01</div>
      <div>
        <div class="section-title" id="dimTitle-client">Client Leadership</div>
        <div class="section-desc" id="dimDesc-client">Your ability to manage and develop client and stakeholder relationships in an effective manner — building trust, communicating clearly, and delivering value.</div>
      </div>
    </div>

    <div class="framework-card" data-fw="client">
      <div class="framework-label">What's expected at Associate level</div>
      <div class="framework-title">You're moving from contributor to leader of client moments.</div>
      <div class="framework-desc">
        As an Associate, you're expected to take the lead in cultivating junior client relationships, establish collaborative coaching relationships with junior clients, and communicate compellingly in written and verbal forms. You should produce near-client-ready documents with limited support, lead development of presentation decks with confidence, and consistently meet all commitments with a growing capacity to contribute to proposals.
      </div>
      <details class="framework-indicators">
        <summary>See the detailed behaviors expected</summary>
        <ul class="indicator-list">
          <li><strong>Takes a lead in cultivating junior client relationships</strong>Establishes collaborative coaching relationships with junior clients, providing guidance and support.</li>
          <li><strong>Exhibits a solid understanding of the client's context</strong>Translates context into actionable solutions within proposals.</li>
          <li><strong>Communicates in a clear, compelling, and convincing manner</strong>Both in written and verbal forms, effectively employing top-down communication techniques.</li>
          <li><strong>Develops near-client-ready documents</strong>Showcases growing proficiency in communication and document preparation, requiring limited support from the BD manager.</li>
          <li><strong>Leads development of presentation decks</strong>Shows good understanding of creating effective presentations with ability to present it internally.</li>
          <li><strong>Consistently delivers proposals</strong>Efficiently meets all deadlines and commitments, ensuring the TAM's work provides value to clients/stakeholders.</li>
        </ul>
      </details>
    </div>

    <div class="entries" data-dim="client" id="entriesClient"></div>
    <button class="add-entry" onclick="addEntry('client')">+ Add another accomplishment</button>

    <div class="rating-block">
      <div class="rating-block-label" id="rateLabel-client">Your self-rating · Client Leadership</div>
      <div class="rating-block-title">How would you rate your performance?</div>
      <div class="rating-block-sub">Be honest. Your assessor will compare this with exposure feedback and KPIs. Sandbagging and inflation are both unhelpful.</div>
      <div class="rating-options" data-dim="client">
        <label class="rating-option"><input type="radio" name="rate-client" value="Underperforms" /><div class="rating-card"><div class="rating-name">Underperforms</div><div class="rating-desc">Fails to meet core requirements.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-client" value="Below Expectations" /><div class="rating-card"><div class="rating-name">Below Expectations</div><div class="rating-desc">Inconsistent or below standards.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-client" value="Meets Expectations" /><div class="rating-card"><div class="rating-name">Meets Expectations</div><div class="rating-desc">Consistent, reliable, hits the mark.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-client" value="Exceeds Expectations" /><div class="rating-card"><div class="rating-name">Exceeds Expectations</div><div class="rating-desc">Above expectations, goes beyond scope.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-client" value="Outstanding" /><div class="rating-card"><div class="rating-name">Outstanding</div><div class="rating-desc">Company-level impact, innovates, mentors.</div></div></label>
      </div>
    </div>
  </section>

  <!-- ============ 2. FIRM LEADERSHIP ============ -->
  <section class="dimension" id="firm">
    <div class="section-header">
      <div class="section-num">02</div>
      <div>
        <div class="section-title" id="dimTitle-firm">Firm Leadership</div>
        <div class="section-desc" id="dimDesc-firm">Your ability to make an impact, take ownership, and contribute to building TAM — beyond just your client projects.</div>
      </div>
    </div>

    <div class="framework-card" data-fw="firm">
      <div class="framework-label">What's expected at Associate level</div>
      <div class="framework-title">You start acting like an owner, not just a contributor.</div>
      <div class="framework-desc">
        At Associate level, you should identify areas of improvement in TAM's operations and actively contribute to firm initiatives. You demonstrate a growing sense of ownership, take responsibility for tasks, proactively seek opportunities to enhance value, and participate in knowledge codification and sharing efforts within the team.
      </div>
      <details class="framework-indicators">
        <summary>See the detailed behaviors expected</summary>
        <ul class="indicator-list">
          <li><strong>Contributes to firm initiatives</strong>Identifies areas of improvement and actively works on initiatives designed to enhance TAM's capabilities.</li>
          <li><strong>Demonstrates ownership</strong>Takes responsibility for tasks with a growing sense of accountability; proactively seeks opportunities to add value.</li>
          <li><strong>Shares knowledge</strong>Actively acquires and shares knowledge with the team. Contributes to codification of knowledge and participates in knowledge-sharing.</li>
          <li><strong>Supports business development</strong>Identifies opportunities during engagements to support BD; helps on proposal development when needed.</li>
        </ul>
      </details>
    </div>

    <div class="entries" data-dim="firm" id="entriesFirm"></div>
    <button class="add-entry" onclick="addEntry('firm')">+ Add another accomplishment</button>

    <div class="rating-block">
      <div class="rating-block-label" id="rateLabel-firm">Your self-rating · Firm Leadership</div>
      <div class="rating-block-title">How would you rate your performance?</div>
      <div class="rating-block-sub">Think squads, internal initiatives, BD support, knowledge codification.</div>
      <div class="rating-options" data-dim="firm">
        <label class="rating-option"><input type="radio" name="rate-firm" value="Underperforms" /><div class="rating-card"><div class="rating-name">Underperforms</div><div class="rating-desc">Fails to meet core requirements.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-firm" value="Below Expectations" /><div class="rating-card"><div class="rating-name">Below Expectations</div><div class="rating-desc">Inconsistent or below standards.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-firm" value="Meets Expectations" /><div class="rating-card"><div class="rating-name">Meets Expectations</div><div class="rating-desc">Consistent, reliable, hits the mark.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-firm" value="Exceeds Expectations" /><div class="rating-card"><div class="rating-name">Exceeds Expectations</div><div class="rating-desc">Above expectations, goes beyond scope.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-firm" value="Outstanding" /><div class="rating-card"><div class="rating-name">Outstanding</div><div class="rating-desc">Company-level impact, innovates, mentors.</div></div></label>
      </div>
    </div>
  </section>

  <!-- ============ 3. THOUGHT LEADERSHIP ============ -->
  <section class="dimension" id="thought">
    <div class="section-header">
      <div class="section-num">03</div>
      <div>
        <div class="section-title" id="dimTitle-thought">Thought Leadership</div>
        <div class="section-desc" id="dimDesc-thought">Your technical mastery — analytical thinking, conceptual problem-solving, continuous learning, and innovation.</div>
      </div>
    </div>

    <div class="framework-card" data-fw="thought">
      <div class="framework-label">What's expected at Associate level</div>
      <div class="framework-title">You drive issue identification and bring structured, client-ready thinking.</div>
      <div class="framework-desc">
        As an Associate, you should drive issue identification and problem structuring, take the lead on aspects of problem-solving in proposals, independently structure standard proposals with only limited guidance, demonstrate competence and attention to detail in complex analytical tasks, and actively contribute clear, reasonable, and actionable solutions to team problem-solving.
      </div>
      <details class="framework-indicators">
        <summary>See the detailed behaviors expected</summary>
        <ul class="indicator-list">
          <li><strong>Drives issue identification and problem structuring</strong>Takes the lead on aspects of problem-solving in proposals and client issues.</li>
          <li><strong>Independently structures standard proposals</strong>Shows growing proficiency; requires only limited guidance from managers.</li>
          <li><strong>Demonstrates analytical competence</strong>Clear thinking and attention to detail in complex analytical tasks.</li>
          <li><strong>Contributes actionable solutions</strong>Drives clear, reasonable, actionable solutions for clients and stakeholders.</li>
          <li><strong>Integrates thinking for team problem-solving</strong>Brings knowledge and integrated thinking to the team's problem-solving efforts.</li>
          <li><strong>Applies frameworks effectively</strong>Actively seeks and adapts relevant frameworks and tools to enhance problem-solving.</li>
        </ul>
      </details>
    </div>

    <div class="entries" data-dim="thought" id="entriesThought"></div>
    <button class="add-entry" onclick="addEntry('thought')">+ Add another accomplishment</button>

    <div class="rating-block">
      <div class="rating-block-label" id="rateLabel-thought">Your self-rating · Thought Leadership</div>
      <div class="rating-block-title">How would you rate your performance?</div>
      <div class="rating-block-sub">Think deliverables, analytical work, storylining, frameworks, innovation.</div>
      <div class="rating-options" data-dim="thought">
        <label class="rating-option"><input type="radio" name="rate-thought" value="Underperforms" /><div class="rating-card"><div class="rating-name">Underperforms</div><div class="rating-desc">Fails to meet core requirements.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-thought" value="Below Expectations" /><div class="rating-card"><div class="rating-name">Below Expectations</div><div class="rating-desc">Inconsistent or below standards.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-thought" value="Meets Expectations" /><div class="rating-card"><div class="rating-name">Meets Expectations</div><div class="rating-desc">Consistent, reliable, hits the mark.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-thought" value="Exceeds Expectations" /><div class="rating-card"><div class="rating-name">Exceeds Expectations</div><div class="rating-desc">Above expectations, goes beyond scope.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-thought" value="Outstanding" /><div class="rating-card"><div class="rating-name">Outstanding</div><div class="rating-desc">Company-level impact, innovates, mentors.</div></div></label>
      </div>
    </div>
  </section>

  <!-- ============ 4. PEOPLE LEADERSHIP ============ -->
  <section class="dimension" id="people">
    <div class="section-header">
      <div class="section-num">04</div>
      <div>
        <div class="section-title" id="dimTitle-people">People Leadership</div>
        <div class="section-desc" id="dimDesc-people">Your ability to collaborate with, coach, and sponsor other TAMers — building and supporting high-performing teams.</div>
      </div>
    </div>

    <div class="framework-card" data-fw="people">
      <div class="framework-label">What's expected at Associate level</div>
      <div class="framework-title">You start leading collaboration, not just participating in it.</div>
      <div class="framework-desc">
        At Associate level, you lead and facilitate collaboration among team members, manage small groups of junior colleagues to deliver specific tasks, support training and coaching through onboarding, identify areas of improvement in yourself and others, and deliver regular constructive feedback — both upward and downward.
      </div>
      <details class="framework-indicators">
        <summary>See the detailed behaviors expected</summary>
        <ul class="indicator-list">
          <li><strong>Leads and facilitates collaboration</strong>Demonstrates a proactive approach to team cohesion and problem-solving through collaboration.</li>
          <li><strong>Manages small groups of juniors</strong>Able to manage a small group of junior colleagues to deliver a specific task.</li>
          <li><strong>Supports training and coaching</strong>Through onboarding and leading others to aid in their development.</li>
          <li><strong>Self-awareness about development</strong>Identifies areas of improvement in one's self.</li>
          <li><strong>Delivers constructive feedback</strong>Asks for feedback from leadership and provides constructive upward feedback. Helps colleagues grow through regular constructive feedback.</li>
          <li><strong>Positive team dynamics</strong>Contributes to team energy and demonstrates genuine concern for peers and clients.</li>
        </ul>
      </details>
    </div>

    <div class="entries" data-dim="people" id="entriesPeople"></div>
    <button class="add-entry" onclick="addEntry('people')">+ Add another accomplishment</button>

    <div class="rating-block">
      <div class="rating-block-label" id="rateLabel-people">Your self-rating · People Leadership</div>
      <div class="rating-block-title">How would you rate your performance?</div>
      <div class="rating-block-sub">Think coaching, mentoring, feedback culture, team contribution.</div>
      <div class="rating-options" data-dim="people">
        <label class="rating-option"><input type="radio" name="rate-people" value="Underperforms" /><div class="rating-card"><div class="rating-name">Underperforms</div><div class="rating-desc">Fails to meet core requirements.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-people" value="Below Expectations" /><div class="rating-card"><div class="rating-name">Below Expectations</div><div class="rating-desc">Inconsistent or below standards.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-people" value="Meets Expectations" /><div class="rating-card"><div class="rating-name">Meets Expectations</div><div class="rating-desc">Consistent, reliable, hits the mark.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-people" value="Exceeds Expectations" /><div class="rating-card"><div class="rating-name">Exceeds Expectations</div><div class="rating-desc">Above expectations, goes beyond scope.</div></div></label>
        <label class="rating-option"><input type="radio" name="rate-people" value="Outstanding" /><div class="rating-card"><div class="rating-name">Outstanding</div><div class="rating-desc">Company-level impact, innovates, mentors.</div></div></label>
      </div>
    </div>
  </section>

  <!-- ============ 5. VALUES ============ -->
  <section class="dimension" id="values">
    <div class="section-header">
      <div class="section-num">05</div>
      <div>
        <div class="section-title">Adhering to Values</div>
        <div class="section-desc">How you live TAM's five values in everyday work. Rated on a three-level scale: <em>Does Not Demonstrate</em> · <em>Demonstrates</em> · <em>Role Model</em>.</div>
      </div>
    </div>

    <div class="values-grid">

      <div class="value-row">
        <div class="value-header">
          <div class="value-name"><span class="diamond"></span>Own Your Impact</div>
          <div class="value-tagline">Reliability · Impact orientation · Empowerment · Recognition & mistakes</div>
        </div>
        <div class="value-field">
          <label class="field-label">Describe how you lived this value</label>
          <textarea data-value="impact-evidence" placeholder="Where did you take full ownership? Where did you deliver beyond 'ticking the box' because you cared about the impact?"></textarea>
        </div>
        <div class="rating-options three-col" data-value-dim="impact">
          <label class="rating-option"><input type="radio" name="val-impact" value="Does Not Demonstrate" /><div class="rating-card"><div class="rating-name">Does Not Demonstrate</div><div class="rating-desc">Shows little ownership; blames others.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-impact" value="Partially Demonstrates" /><div class="rating-card"><div class="rating-name">Partially Demonstrates</div><div class="rating-desc">Inconsistent ownership; shows it sometimes.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-impact" value="Demonstrates" /><div class="rating-card"><div class="rating-name">Demonstrates</div><div class="rating-desc">Reliably owns and delivers on commitments.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-impact" value="Role Model" /><div class="rating-card"><div class="rating-name">Role Model</div><div class="rating-desc">Champions ownership as a cultural value.</div></div></label>
        </div>
      </div>

      <div class="value-row">
        <div class="value-header">
          <div class="value-name"><span class="diamond"></span>Respect the Truth</div>
          <div class="value-tagline">Integrity · Psychological safety · Evidence · Respectful communication</div>
        </div>
        <div class="value-field">
          <label class="field-label">Describe how you lived this value</label>
          <textarea data-value="truth-evidence" placeholder="When did you say the hard thing? When did you make it safe for someone else to speak up? Where did you ground discussions in evidence?"></textarea>
        </div>
        <div class="rating-options three-col" data-value-dim="truth">
          <label class="rating-option"><input type="radio" name="val-truth" value="Does Not Demonstrate" /><div class="rating-card"><div class="rating-name">Does Not Demonstrate</div><div class="rating-desc">Avoids difficult conversations.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-truth" value="Partially Demonstrates" /><div class="rating-card"><div class="rating-name">Partially Demonstrates</div><div class="rating-desc">Honest in some contexts but not consistently.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-truth" value="Demonstrates" /><div class="rating-card"><div class="rating-name">Demonstrates</div><div class="rating-desc">Communicates openly and honestly.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-truth" value="Role Model" /><div class="rating-card"><div class="rating-name">Role Model</div><div class="rating-desc">Creates psychological safety for others.</div></div></label>
        </div>
      </div>

      <div class="value-row">
        <div class="value-header">
          <div class="value-name"><span class="diamond"></span>Win as a Team</div>
          <div class="value-tagline">Caring · Company interest first · Trust · Collaboration</div>
        </div>
        <div class="value-field">
          <label class="field-label">Describe how you lived this value</label>
          <textarea data-value="team-evidence" placeholder="When did you prioritize the team or the firm over your own interest? When did you collaborate through a tough moment?"></textarea>
        </div>
        <div class="rating-options three-col" data-value-dim="team">
          <label class="rating-option"><input type="radio" name="val-team" value="Does Not Demonstrate" /><div class="rating-card"><div class="rating-name">Does Not Demonstrate</div><div class="rating-desc">Disrupts teamwork; operates in a silo.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-team" value="Partially Demonstrates" /><div class="rating-card"><div class="rating-name">Partially Demonstrates</div><div class="rating-desc">Collaborates with prompting; uneven across situations.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-team" value="Demonstrates" /><div class="rating-card"><div class="rating-name">Demonstrates</div><div class="rating-desc">Reliable collaborator who facilitates work.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-team" value="Role Model" /><div class="rating-card"><div class="rating-name">Role Model</div><div class="rating-desc">Actively breaks silos and elevates others.</div></div></label>
        </div>
      </div>

      <div class="value-row">
        <div class="value-header">
          <div class="value-name"><span class="diamond"></span>Adapt & Innovate</div>
          <div class="value-tagline">Open-mindedness · Curiosity · Courage · Resourcefulness</div>
        </div>
        <div class="value-field">
          <label class="field-label">Describe how you lived this value</label>
          <textarea data-value="adapt-evidence" placeholder="When did you challenge the status quo? When did you find a creative way around a constraint? When did you learn and apply something new?"></textarea>
        </div>
        <div class="rating-options three-col" data-value-dim="adapt">
          <label class="rating-option"><input type="radio" name="val-adapt" value="Does Not Demonstrate" /><div class="rating-card"><div class="rating-name">Does Not Demonstrate</div><div class="rating-desc">Actively resists change.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-adapt" value="Partially Demonstrates" /><div class="rating-card"><div class="rating-name">Partially Demonstrates</div><div class="rating-desc">Adapts when required; not yet proactive.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-adapt" value="Demonstrates" /><div class="rating-card"><div class="rating-name">Demonstrates</div><div class="rating-desc">Adapts positively and learns from feedback.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-adapt" value="Role Model" /><div class="rating-card"><div class="rating-name">Role Model</div><div class="rating-desc">Catalyst for innovation; experiments boldly.</div></div></label>
        </div>
      </div>

      <div class="value-row">
        <div class="value-header">
          <div class="value-name"><span class="diamond"></span>Grow with Wellbeing</div>
          <div class="value-tagline">Growth mindset · Holistic effort · Potential over competency · Praising effort</div>
        </div>
        <div class="value-field">
          <label class="field-label">Describe how you lived this value</label>
          <textarea data-value="grow-evidence" placeholder="How did you work on your own development? How did you help others grow? How did you balance performance and wellbeing?"></textarea>
        </div>
        <div class="rating-options three-col" data-value-dim="grow">
          <label class="rating-option"><input type="radio" name="val-grow" value="Does Not Demonstrate" /><div class="rating-card"><div class="rating-name">Does Not Demonstrate</div><div class="rating-desc">Disengaged from development.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-grow" value="Partially Demonstrates" /><div class="rating-card"><div class="rating-name">Partially Demonstrates</div><div class="rating-desc">Engages in development inconsistently.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-grow" value="Demonstrates" /><div class="rating-card"><div class="rating-name">Demonstrates</div><div class="rating-desc">Actively works on development plan.</div></div></label>
          <label class="rating-option"><input type="radio" name="val-grow" value="Role Model" /><div class="rating-card"><div class="rating-name">Role Model</div><div class="rating-desc">Models sustainable high performance; coaches others.</div></div></label>
        </div>
      </div>

    </div>
  </section>

  <!-- ============ OVERALL RATING (its own standout section) ============ -->
  <section class="dimension overall-section" id="overall">
    <div class="overall-stage">
      <div class="overall-eyebrow">06 · Your overall self-rating</div>
      <h2 class="overall-headline">Taking everything together,<br>what's your <em>honest</em> overall rating?</h2>
      <p class="overall-sub">This is your holistic view across all four competency dimensions and the values. Your assessor will weigh this alongside exposure feedback and KPIs — be candid. Sandbagging and inflation are both unhelpful.</p>

      <div class="overall-rating-grid" data-dim="overall">
        <label class="overall-rating-option"><input type="radio" name="rate-overall" value="Underperforms" />
          <div class="overall-rating-card">
            <div class="overall-rating-num">01</div>
            <div class="overall-rating-name">Underperforms</div>
            <div class="overall-rating-desc">Fails to meet core requirements; performance has negative impact.</div>
          </div>
        </label>
        <label class="overall-rating-option"><input type="radio" name="rate-overall" value="Below Expectations" />
          <div class="overall-rating-card">
            <div class="overall-rating-num">02</div>
            <div class="overall-rating-name">Below Expectations</div>
            <div class="overall-rating-desc">Performance is inconsistent or below standards; quality is unreliable.</div>
          </div>
        </label>
        <label class="overall-rating-option"><input type="radio" name="rate-overall" value="Meets Expectations" />
          <div class="overall-rating-card">
            <div class="overall-rating-num">03</div>
            <div class="overall-rating-name">Meets Expectations</div>
            <div class="overall-rating-desc">Consistent throughout the year; meets all expectations and occasionally exceeds them.</div>
          </div>
        </label>
        <label class="overall-rating-option"><input type="radio" name="rate-overall" value="Exceeds Expectations" />
          <div class="overall-rating-card">
            <div class="overall-rating-num">04</div>
            <div class="overall-rating-name">Exceeds Expectations</div>
            <div class="overall-rating-desc">Frequently delivers above expectations; goes beyond job requirements and scope.</div>
          </div>
        </label>
        <label class="overall-rating-option"><input type="radio" name="rate-overall" value="Outstanding" />
          <div class="overall-rating-card">
            <div class="overall-rating-num">05</div>
            <div class="overall-rating-name">Outstanding</div>
            <div class="overall-rating-desc">Always exceeds; company-level impact; constantly innovates, leads, and mentors.</div>
          </div>
        </label>
      </div>
    </div>
  </section>

  <!-- ============ EXPORT ============ -->
</div>

<section class="export" id="export">
  <div class="wrap">
    <div class="section-header">
      <div class="section-num">07</div>
      <div>
        <div class="section-title">You're done.</div>
        <div class="section-desc">Preview what your assessor will see, then export it. You can copy the full text, download it as an HTML file, or print/save to PDF.</div>
      </div>
    </div>

    <div class="export-actions">
      <button class="btn btn-primary btn-save" onclick="submitAssessment()">Submit &amp; save</button>
      <button class="btn btn-ghost" onclick="generatePreview()">Preview</button>
      <button class="btn btn-ghost" onclick="exportPolishedPDF()">Export polished PDF</button>
      <button class="btn btn-ghost" onclick="copyToClipboard()">Copy as text</button>
      <button class="btn btn-ghost" onclick="downloadHTML()">Download as HTML</button>
    </div>

    <div class="preview" id="previewArea"></div>
  </div>
</section>

<div class="wrap">
  <footer>
    <div>TAM · Self-Assessment Workbook · Advisory — Associate</div>
    <div>
      <a href="#" class="admin-link" onclick="openAdmin(event)">Admin</a>
      <span class="footer-sep">·</span>
      Your story, structured.
    </div>
  </footer>
</div>

<!-- ============ ADMIN MODAL ============ -->
<div class="admin-overlay" id="adminOverlay" onclick="if(event.target===this)closeAdmin()">
  <div class="admin-modal">
    <div class="admin-header">
      <div>
        <div class="admin-eyebrow">TAM · Restricted</div>
        <h2 class="admin-title">Self-Assessment Admin</h2>
      </div>
      <button class="admin-close" onclick="closeAdmin()" aria-label="Close">&times;</button>
    </div>

    <!-- Login gate -->
    <div class="admin-login" id="adminLogin">
      <div class="admin-login-msg">Enter the admin passcode to view saved self-assessments.</div>
      <div class="admin-login-row">
        <input type="password" id="adminPass" placeholder="Passcode" onkeydown="if(event.key==='Enter')checkAdminPass()" />
        <button class="btn btn-primary" onclick="checkAdminPass()">Enter</button>
      </div>
      <div class="admin-login-hint">Default passcode: <code>tam2025</code> — change in the JS to whatever you want.</div>
    </div>

    <!-- Body shown after login -->
    <div class="admin-body" id="adminBody" style="display:none;">
      <div class="admin-toolbar">
        <div class="admin-stats" id="adminStats">0 self-assessments saved</div>
        <div class="admin-toolbar-actions">
          <button class="btn btn-ghost btn-sm" onclick="refreshAdmin()">Refresh</button>
          <button class="btn btn-primary btn-sm" onclick="exportAllExcel()">Export all to Excel</button>
        </div>
      </div>

      <div class="admin-table-wrap">
        <table class="admin-table" id="adminTable">
          <thead>
            <tr>
              <th>Name</th>
              <th>Department</th>
              <th>Level</th>
              <th>Assessor</th>
              <th>Overall</th>
              <th>Saved</th>
              <th class="t-right">Actions</th>
            </tr>
          </thead>
          <tbody id="adminTbody"></tbody>
        </table>
        <div class="admin-empty" id="adminEmpty">No self-assessments saved yet.</div>
      </div>

      <div class="admin-danger">
        <button class="btn btn-danger btn-sm" onclick="deleteAllAssessments()">Delete all assessments</button>
      </div>
    </div>
  </div>
</div>

<div class="toast" id="toast">Copied to clipboard</div>

<script>
  // ============ FRAMEWORK DATA ============
  // Advisory framework — distilled from the Advisory Role Expectations PDF
  // Each level has: title (short summary), client/firm/thought/people cards (headline, description, list of indicators)
  const ADVISORY_FRAMEWORK = {
    'analyst': {
      label: 'Analyst',
      client: {
        headline: "You're learning to listen, capture, and communicate clearly.",
        desc: "As an Analyst, you're expected to actively listen during client interactions, capture needs and preferences accurately, communicate clearly and professionally in writing and verbally, and support meeting prep and follow-ups. You're building basic understanding of the client's business and applying feedback to grow.",
        indicators: [
          ['Demonstrates active listening', 'Pays close attention to client and internal discussions; asks clarifying questions when needed.'],
          ['Communicates clearly and professionally', 'Prepares concise written materials with appropriate tone; speaks confidently in team discussions.'],
          ['Supports client meeting prep and follow-up', 'Helps create presentations, briefs, or data; takes accurate meeting notes; follows through on actions.'],
          ['Shows basic understanding of client context', 'Aware of client business and industry; tailors communication to be relevant.'],
          ['Seeks feedback to improve communication', 'Welcomes input on style and content; applies feedback to increase clarity and effectiveness.']
        ]
      },
      firm: {
        headline: "You start contributing to the firm beyond your tasks.",
        desc: "Contribute to firm initiatives, view yourself as an owner with strong sense of accountability, and begin identifying potential knowledge or service areas to contribute to. Aim to support proposal development.",
        indicators: [
          ['Contributes to firm initiatives', 'Participates in initiatives that improve TAM operations and capabilities.'],
          ['Acts like an owner', 'Takes ownership of individual responsibilities with a strong sense of accountability.'],
          ['Identifies knowledge to share', 'Begins to identify potential areas of knowledge or service lines to contribute to or build upon.'],
          ['Proposal development', 'Targets supporting on 3 proposals.']
        ]
      },
      thought: {
        headline: "You think clearly and execute analytical tasks accurately.",
        desc: "Approach tasks with logical structure, collect and analyze relevant data, identify patterns and root causes, ensure accuracy and rigor in analysis, and support decisions with fact-based inputs. Aim for ≥95% accuracy on outputs.",
        indicators: [
          ['Approaches tasks with logical structure', 'Breaks problems into manageable parts; follows step-by-step methods.'],
          ['Collects and analyzes data', 'Uses Excel, Power BI, SQL, or other tools to summarize findings and draw accurate conclusions.'],
          ['Identifies patterns and root causes', 'Recognizes inconsistencies and patterns; questions assumptions when something seems off.'],
          ['Ensures analytical rigor', 'Double-checks calculations and logic; maintains precision; understands quality implications.'],
          ['Supports decisions with facts', 'Presents findings clearly to support team or client decisions; tailors insights to the audience.']
        ]
      },
      people: {
        headline: "You collaborate well and seek feedback proactively.",
        desc: "Collaborate effectively with teammates, contribute positively to team energy and dynamics, understand basic coaching concepts and identify areas of self-improvement, and ask for and act on feedback from leadership.",
        indicators: [
          ['Collaborates effectively', 'Builds strong relationships with teammates; works selflessly with colleagues to achieve common goals.'],
          ['Contributes to team energy', 'Positively contributes to team dynamics and shows genuine concern for peers and clients.'],
          ['Self-aware about development', 'Understands coaching concepts and identifies areas of improvement in oneself.'],
          ['Seeks and acts on feedback', 'Asks for feedback from leadership and provides constructive upward feedback.']
        ]
      }
    },

    'sr-analyst': {
      label: 'Sr Analyst',
      client: {
        headline: "You're producing near-client-ready work and building presence.",
        desc: "As a Sr Analyst, you communicate clearly with growing confidence, develop documents that are almost client-ready (with limited support from the BD manager), contribute to presentation decks, and identify gaps in the client context to communicate to leadership.",
        indicators: [
          ['Active listening to client needs', 'Pays close attention; takes detailed notes; demonstrates understanding by paraphrasing.'],
          ['Clear and professional communication', 'Prepares draft emails, presentations, and updates that require minimal rework.'],
          ['Responsiveness and follow-up', 'Responds promptly to client requests; escalates appropriately to senior team members.'],
          ['Contributes to client meetings', 'Prepares materials, attends meetings with seniors, contributes when appropriate.'],
          ['Professional conduct in interactions', 'Represents the firm professionally and adapts to client communication preferences.'],
          ['Builds client knowledge', 'Develops basic understanding of the client industry, business model, and key stakeholders.']
        ]
      },
      firm: {
        headline: "You take ownership and actively share knowledge.",
        desc: "Contribute to firm initiatives, demonstrate ownership, and actively acquire and share knowledge with the team. Contribute to codification of knowledge and participate in knowledge-sharing efforts.",
        indicators: [
          ['Contributes to firm initiatives', 'Participates in initiatives that enhance TAM operations and capabilities.'],
          ['Acts like an owner', 'Takes responsibility for individual responsibilities with strong accountability.'],
          ['Shares knowledge actively', 'Acquires and shares knowledge; contributes to codification efforts; participates in knowledge-sharing.'],
          ['Proposal development', 'Targets supporting on 4 proposals.']
        ]
      },
      thought: {
        headline: "You drive issue identification and structure problems.",
        desc: "Drive issue identification and problem structuring on aspects of problem-solving, execute analytical tasks efficiently and accurately, demonstrate emerging conceptual thinking, and apply frameworks effectively.",
        indicators: [
          ['Drives issue identification', 'Takes the lead on aspects of problem-solving in client issues and proposals.'],
          ['Structures parts of proposals', 'Demonstrates a foundational understanding of effective structuring and story-lining.'],
          ['Executes analytical tasks', 'Performs analytical work efficiently, effectively, and accurately.'],
          ['Emerging conceptual thinking', 'Develops creative insights and contributes structured thinking to problems.'],
          ['Pragmatic team problem-solving', 'Participates in team problem solving with a focus on pragmatic solutions for the client.'],
          ['Applies frameworks', 'Uses appropriate frameworks and tools to perform assigned work.']
        ]
      },
      people: {
        headline: "You support training, coaching, and team development.",
        desc: "Collaborate effectively, contribute to team energy and dynamics, support training and coaching of others, and provide constructive upward feedback.",
        indicators: [
          ['Collaborates effectively', 'Builds strong relationships and works selflessly with colleagues.'],
          ['Contributes to team energy', 'Positively contributes to team dynamics and shows concern for peers and clients.'],
          ['Supports training and coaching', 'Aids others in their development; identifies areas of self-improvement.'],
          ['Provides upward feedback', 'Asks for feedback from leadership and provides constructive upward feedback.']
        ]
      }
    },

    'associate': {
      label: 'Associate',
      client: {
        headline: "You're moving from contributor to leader of client moments.",
        desc: "As an Associate, you're expected to take the lead in cultivating junior client relationships, establish collaborative coaching relationships with junior clients, and communicate compellingly in written and verbal forms. You should produce near-client-ready documents with limited support, lead development of presentation decks with confidence, and consistently meet all commitments with a growing capacity to contribute to proposals.",
        indicators: [
          ['Takes a lead in cultivating junior client relationships', 'Establishes collaborative coaching relationships with junior clients, providing guidance and support.'],
          ["Exhibits a solid understanding of the client's context", 'Translates context into actionable solutions within proposals.'],
          ['Communicates in a clear, compelling, and convincing manner', 'Both in written and verbal forms, effectively employing top-down communication techniques.'],
          ['Develops near-client-ready documents', 'Showcases growing proficiency in communication and document preparation, requiring limited support from the BD manager.'],
          ['Leads development of presentation decks', 'Shows good understanding of creating effective presentations with ability to present it internally.'],
          ['Consistently delivers proposals', "Efficiently meets all deadlines and commitments, ensuring the TAM's work provides value to clients/stakeholders."]
        ]
      },
      firm: {
        headline: "You start acting like an owner, not just a contributor.",
        desc: "At Associate level, you should identify areas of improvement in TAM's operations and actively contribute to firm initiatives. You demonstrate a growing sense of ownership, take responsibility for tasks, proactively seek opportunities to enhance value, and participate in knowledge codification and sharing efforts within the team.",
        indicators: [
          ['Contributes to firm initiatives', "Identifies areas of improvement and actively works on initiatives designed to enhance TAM's capabilities."],
          ['Demonstrates ownership', 'Takes responsibility for tasks with a growing sense of accountability; proactively seeks opportunities to add value.'],
          ['Shares knowledge', 'Actively acquires and shares knowledge with the team. Contributes to codification of knowledge and participates in knowledge-sharing.'],
          ['Supports business development', 'Identifies opportunities during engagements to support BD; helps on proposal development when needed.']
        ]
      },
      thought: {
        headline: "You drive issue identification and bring structured, client-ready thinking.",
        desc: "As an Associate, you should drive issue identification and problem structuring, take the lead on aspects of problem-solving in proposals, independently structure standard proposals with only limited guidance, demonstrate competence and attention to detail in complex analytical tasks, and actively contribute clear, reasonable, and actionable solutions to team problem-solving.",
        indicators: [
          ['Drives issue identification and problem structuring', 'Takes the lead on aspects of problem-solving in proposals and client issues.'],
          ['Independently structures standard proposals', 'Shows growing proficiency; requires only limited guidance from managers.'],
          ['Demonstrates analytical competence', 'Clear thinking and attention to detail in complex analytical tasks.'],
          ['Contributes actionable solutions', 'Drives clear, reasonable, actionable solutions for clients and stakeholders.'],
          ['Integrates thinking for team problem-solving', "Brings knowledge and integrated thinking to the team's problem-solving efforts."],
          ['Applies frameworks effectively', 'Actively seeks and adapts relevant frameworks and tools to enhance problem-solving.']
        ]
      },
      people: {
        headline: "You start leading collaboration, not just participating in it.",
        desc: "At Associate level, you lead and facilitate collaboration among team members, manage small groups of junior colleagues to deliver specific tasks, support training and coaching through onboarding, identify areas of improvement in yourself and others, and deliver regular constructive feedback — both upward and downward.",
        indicators: [
          ['Leads and facilitates collaboration', 'Demonstrates a proactive approach to team cohesion and problem-solving through collaboration.'],
          ['Manages small groups of juniors', 'Able to manage a small group of junior colleagues to deliver a specific task.'],
          ['Supports training and coaching', 'Through onboarding and leading others to aid in their development.'],
          ['Self-awareness about development', "Identifies areas of improvement in one's self."],
          ['Delivers constructive feedback', 'Asks for feedback from leadership and provides constructive upward feedback. Helps colleagues grow through regular constructive feedback.'],
          ['Positive team dynamics', 'Contributes to team energy and demonstrates genuine concern for peers and clients.']
        ]
      }
    },

    'sr-associate': {
      label: 'Sr Associate',
      client: {
        headline: "You lead client relationships and run client meetings with confidence.",
        desc: "Take a lead in cultivating client relationships and lasting connections, create client-ready documents independently, demonstrate strong meeting facilitation and presentation skills, and consistently deliver on proposals with growing capacity to contribute meaningfully.",
        indicators: [
          ['Cultivates lasting client relationships', 'Maintains connections after proposals are completed and develops collaborative, lasting relationships.'],
          ['Translates context into solutions', "Exhibits solid understanding of the client's context and translates it into actionable solutions."],
          ['Communicates compellingly', 'Effectively employs top-down communication techniques both in written and verbal forms.'],
          ['Creates client-ready documents independently', 'Displays high level of competence in crafting clear and effective communication materials.'],
          ['Demonstrates meeting facilitation skills', 'Runs meetings effectively and engages clients through compelling presentations.'],
          ['Works independently and reliably', 'Consistently delivers on commitments in a reliable and trustworthy manner.']
        ]
      },
      firm: {
        headline: "You lead knowledge sharing and codification efforts.",
        desc: "Identify areas of improvement and contribute to firm initiatives. Demonstrate deep understanding of knowledge and service lines. Actively lead knowledge-sharing initiatives and take charge of codification, fostering a culture of continuous learning.",
        indicators: [
          ['Contributes to firm initiatives', 'Identifies improvement areas and actively works on initiatives to enhance TAM operations.'],
          ['Owns work outcomes', 'Takes responsibility for tasks; proactively seeks opportunities to enhance value.'],
          ['Leads knowledge sharing', 'Demonstrates deep understanding of service lines; actively leads knowledge-sharing within the team.'],
          ['Codifies knowledge', 'Takes charge of knowledge codification efforts; fosters a culture of continuous learning.']
        ]
      },
      thought: {
        headline: "You lead problem-solving efforts within proposals.",
        desc: "Take charge of issue identification and problem structuring, effectively lead problem-solving efforts within proposals, structure technical and financial proposals with limited guidance, and demonstrate competence and attention to detail in complex analytical tasks.",
        indicators: [
          ['Leads problem-solving in proposals', 'Effectively leads problem-solving efforts within for the proposals.'],
          ['Structures technical and financial proposals', 'Shows growing proficiency in structuring with only limited guidance from managers.'],
          ['Detail-oriented analytical work', 'Clear thinking and attention to detail in complex analytical tasks.'],
          ['Drives actionable solutions', 'Actively contributes to driving clear, reasonable, and actionable solutions for clients.'],
          ['Integrates thinking for team', "Brings integrated thinking to the team's problem-solving efforts."],
          ['Adapts frameworks effectively', 'Actively seeks and adapts relevant frameworks and tools to enhance problem-solving.']
        ]
      },
      people: {
        headline: "You train and coach others to grow.",
        desc: "Lead and facilitate collaboration, contribute positively to team dynamics, train and coach others while contributing to their growth and skill enhancement, and provide regular constructive feedback that helps colleagues develop.",
        indicators: [
          ['Leads collaboration', 'Demonstrates a proactive approach to team cohesion and problem-solving through effective collaboration.'],
          ['Contributes to team dynamics', 'Positively contributes to team energy and demonstrates concern for peers and clients.'],
          ['Trains and coaches others', 'Actively contributes to the growth and skill enhancement of colleagues.'],
          ['Delivers regular constructive feedback', 'Helps colleagues grow by delivering regular constructive feedback.']
        ]
      }
    },

    'manager': {
      label: 'Manager',
      client: {
        headline: "You become a trusted advisor and shape client expectations.",
        desc: "Take a lead in cultivating senior client relationships, develop comprehensive understanding of the 'big picture' in client context, anticipate and address client requirements proactively, communicate compellingly in critical situations using top-down techniques, and present effectively to high-level executives.",
        indicators: [
          ['Builds strong client relationships', 'Develops trusted advisor status by consistently delivering value and insight; maintains regular professional communication.'],
          ['Manages client expectations', 'Sets realistic timelines; proactively addresses scope changes, delays, or risks with transparency.'],
          ['Communicates with clarity and influence', 'Leads high-stakes meetings with confidence; translates complex information into business-friendly terms.'],
          ['Anticipates client needs', 'Identifies unstated client needs through careful listening and business insight; suggests forward-looking solutions.'],
          ['Facilitates cross-team communication', 'Resolves misunderstandings or tension between stakeholders diplomatically; guides teams.'],
          ['Maintains professionalism under pressure', 'Handles difficult feedback or conflicts with composure; protects firm credibility.']
        ]
      },
      firm: {
        headline: "You instill ownership in your team and lead knowledge codification.",
        desc: "Identify areas of improvement and contribute to firm initiatives, lead by example by instilling a culture of ownership within the team, take full ownership of proposals, demonstrate deep understanding of knowledge areas, and lead knowledge codification across the firm.",
        indicators: [
          ['Contributes to firm initiatives', 'Identifies improvement areas and actively contributes to initiatives that enhance TAM operations.'],
          ['Leads by example on ownership', 'Instills a culture of ownership within the team; takes full ownership of proposals.'],
          ['Fosters team accountability', 'Ensures the team collectively takes ownership of TAM successes.'],
          ['Leads knowledge sharing', 'Deep understanding of knowledge areas and service lines; actively leads knowledge-sharing within the team.'],
          ['Codifies knowledge', 'Takes charge of knowledge codification efforts and fosters a culture of continuous learning.'],
          ['Proposal development', 'Targets supporting on 5 proposals.']
        ]
      },
      thought: {
        headline: "You lead complex problem-solving and integrate thinking across functions.",
        desc: "Take charge of issue identification, lead the structuring of proposals, develop clear and actionable solutions based on analysis, foster inclusive and creative problem-solving within the team, and integrate thinking across industries, functions, and frameworks.",
        indicators: [
          ['Leads complex structured analysis', 'Designs and oversees structured problem-solving frameworks and analysis models.'],
          ['Synthesizes data into insights', 'Translates quantitative and qualitative data into meaningful business insights.'],
          ['Ensures analytical rigor across team', 'Reviews and challenges team analyses to confirm accuracy, logic, and assumptions; coaches on tools.'],
          ['Makes data-driven recommendations', 'Uses insights to support recommendations that are compelling and feasible; quantifies impact.'],
          ['Identifies patterns and root causes', 'Goes beyond symptoms to find underlying issues; spots trends across projects, teams, or industries.'],
          ['Balances detail with big-picture', 'Knows when to dive deep and when to zoom out; simplifies complex analytics into high-level takeaways.']
        ]
      },
      people: {
        headline: "You manage and coach a team of TAMers actively.",
        desc: "Foster collaboration within the team, create effective plans and manage team members and resources appropriately, train and coach others to aid in their development, and ask for feedback while delivering constructive upward and downward feedback.",
        indicators: [
          ['Fosters collaboration', 'Proactively encourages and guides team members to work cohesively and leverage diverse strengths.'],
          ['Manages people and resources', 'Creates effective plans and manages team and other internal resources appropriately.'],
          ['Recognizes team efforts', 'Recognizes teams for their efforts and manages upward intelligently.'],
          ['Trains, coaches, and leads', 'Actively contributes to the growth and skill enhancement of colleagues.'],
          ['Provides constructive feedback', 'Asks for feedback and helps colleagues grow by delivering regular constructive feedback.'],
          ['PHC / coaching cadence', 'Targets PHC score of 3 or below 90% of the time, with 4 sessions per team member per year.']
        ]
      }
    },

    'sr-manager': {
      label: 'Sr Manager',
      client: {
        headline: "You build long-lasting business relationships with senior clients.",
        desc: "Build long-lasting business relationships with clients that serve TAM's immediate and long-term goals, shape and execute the strategic vision of client relationships, and lead high-stakes communication with high-level executives.",
        indicators: [
          ['Builds long-lasting business relationships', "Plays a key role in enhancing TAM's strategic partnerships."],
          ['Shapes client relationship vision', 'Drives business growth and long-term connections through strategic vision.'],
          ['Demonstrates big-picture understanding', 'Leads discussions on future client needs and proactively addresses requirements.'],
          ['Communicates compellingly to executives', 'Showcases mastery of top-down communication and synthesizes effectively rather than just summarizing.'],
          ['Tailors documents for senior clients', 'Demonstrates advanced ability to communicate with high-level executives.'],
          ['Manages procurement and senior clients', 'Negotiates effectively while delivering value through proposals and ensuring commitments are met.']
        ]
      },
      firm: {
        headline: "You lead firm initiatives and develop TAM's expertise.",
        desc: "Lead and manage firm initiatives that drive the development and enhancement of TAM's capabilities, lead by example to instill ownership culture, lead knowledge areas across TAM, and codify knowledge in projects and firm-wide initiatives.",
        indicators: [
          ['Leads and manages firm initiatives', "Drives the development and enhancement of TAM's capabilities."],
          ['Instills ownership culture', 'Leads by example; fosters responsibility among team members and ensures collective ownership.'],
          ['Leads knowledge areas across TAM', 'Plays a pivotal role in developing and disseminating expertise throughout TAM.'],
          ['Codifies knowledge firm-wide', 'Takes the lead in codifying knowledge within projects and firm-wide initiatives.']
        ]
      },
      thought: {
        headline: "You apply advanced problem-solving to complex challenges.",
        desc: "Approach problem-solving with rigor, offer innovative and insightful solutions to complex challenges, lead by example in advanced techniques, and integrate thinking across industries, functions, and frameworks.",
        indicators: [
          ['Approaches problems with rigor', 'Offers innovative and insightful solutions to complex challenges.'],
          ['Leads structuring of proposals', 'Provides guidance and actively shapes the approach.'],
          ['Develops actionable solutions', 'Solutions are clear, reasonable, and based on analysis.'],
          ['Fosters inclusive problem-solving', 'Actively encourages and implements innovative solutions and ideas within the team.'],
          ['Guides knowledge integration', "Takes a leadership role in guiding integrated thinking within the team's problem-solving."],
          ['Integrates thinking across functions', 'Generates innovative solutions; promotes resourcefulness within the team.']
        ]
      },
      people: {
        headline: "You drive a culture of collaboration and develop high-performing teams.",
        desc: "Lead the team in driving collaborative and inclusive culture, create inclusive environments for all colleagues, develop and recognize high-performing juniors, and provide regular constructive feedback at scale.",
        indicators: [
          ['Drives collaborative culture', 'Proactively encourages cohesion and leverages diverse strengths to deliver exceptional results.'],
          ['Creates inclusive environments', 'Develops, inspires, and recognizes juniors; builds high-performing teams.'],
          ['Trains, coaches, and leads', 'Actively contributes to the growth and skill enhancement of colleagues.'],
          ['Provides constructive feedback at scale', 'Asks for and provides upward feedback; helps colleagues grow through regular constructive feedback.']
        ]
      }
    },

    'director': {
      label: 'Director',
      client: {
        headline: "You cultivate strategic trust with senior client stakeholders.",
        desc: "Build long-lasting business relationships, shape and execute the strategic vision of client relationships, apply in-depth understanding of the client's industry to shape solutions, manage external communications and set high standards for clarity and effectiveness, and develop sustainable solutions that consider future implications.",
        indicators: [
          ['Cultivates strategic trust', 'Develops trusted partner status with VP/SVP-level contacts; portfolio-level understanding of business.'],
          ['Shapes client expectations at portfolio level', 'Negotiates multi-project timelines; balances competing demands across client teams/functions.'],
          ['Leads strategic client dialogues', 'Orchestrates outcome-focused discussions; coaches managers on executive presence.'],
          ['Drives expansion opportunities', 'Spots white space; connects client needs with cross-practice offerings; positions firm as indispensable partner.'],
          ['Optimizes client engagement models', 'Designs account-specific communication rhythms and governance.'],
          ['Safeguards strategic client health', 'Monitors relationship metrics; intervenes in high-risk situations before escalation to Partners.']
        ]
      },
      firm: {
        headline: "You exhibit exemplary ownership at organizational level.",
        desc: "Lead and manage firm initiatives, exhibit exemplary ownership behavior extended to organizational levels, demonstrate strong accountability for TAM's growth, and lead knowledge areas while codifying knowledge across firm-wide initiatives.",
        indicators: [
          ['Leads firm initiatives', "Drives the development and enhancement of TAM's capabilities."],
          ['Exemplary organizational ownership', 'Demonstrates strong accountability for TAM growth; fosters culture of shared responsibility.'],
          ['Leads knowledge areas firm-wide', 'Plays a pivotal role in developing and disseminating expertise.'],
          ['Codifies knowledge in firm-wide initiatives', 'Leads codification within projects and firm-wide initiatives.']
        ]
      },
      thought: {
        headline: "You architect strategic analysis and shape executive decisions.",
        desc: "Architect strategic analysis frameworks, synthesize insights for executive decision-making, elevate analytical capability at scale, drive data-informed strategy, anticipate systemic trends, and balance depth with organizational impact.",
        indicators: [
          ['Architects strategic analysis frameworks', 'Designs cross-functional or enterprise-level analytical approaches.'],
          ['Synthesizes for executive decisions', 'Translates complex data into executive-ready narratives tied to outcomes (revenue, risk, growth).'],
          ['Elevates analytical capability at scale', 'Institutionalizes best practices, tools, and standards across teams; coaches managers.'],
          ['Drives data-informed strategy', 'Uses analytics to shape business unit or practice strategy; influences C-suite/Partner decisions.'],
          ['Anticipates systemic trends', 'Diagnoses enterprise-wide or industry-level root causes; flags emerging risks/opportunities.'],
          ['Balances depth with organizational impact', 'Aligns analysis with firm strategic priorities; simplifies into actionable executive mandates.']
        ]
      },
      people: {
        headline: "You sponsor a diverse range of colleagues and build high-performing teams.",
        desc: "Foster cross-team collaboration, develop and inspire high-performing teams, sponsor career development of a diverse range of colleagues, and provide constructive feedback that drives growth at all levels.",
        indicators: [
          ['Fosters collaboration', 'Proactively encourages cohesion across the team and with other departments.'],
          ['Builds high-performing teams', 'Develops, inspires, and recognizes juniors; creates inclusive environments.'],
          ['Coaches and challenges others', 'Strengths-based approach; sponsors a diverse range of colleagues for career development.'],
          ['Provides constructive feedback', 'Asks for feedback; helps colleagues grow through regular constructive feedback.']
        ]
      }
    },

    'sr-director': {
      label: 'Sr Director',
      client: {
        headline: "You lead the firm's strategic client portfolio and shape long-term partnerships.",
        desc: "At Sr Director level, you build long-lasting business relationships at the highest level, shape strategic vision across the portfolio, drive thought leadership for clients, and ensure communication efforts build TAM's reputation as a trusted advisor.",
        indicators: [
          ['Leads strategic client portfolio', 'Builds and maintains strong relationships with key executive stakeholders across the portfolio.'],
          ['Shapes long-term vision', 'Drives strategic vision of client relationships; positions firm for sustained partnership.'],
          ['Drives thought leadership', 'Provides strategic guidance to clients; uses expertise to position firm as trusted advisor.'],
          ['Develops communication plans', 'Supports business objectives; builds firm reputation through executive-level communication.'],
          ['Mentors communication professionals', 'Develops senior communication capabilities across the team.']
        ]
      },
      firm: {
        headline: "You shape TAM's organizational direction and culture.",
        desc: "Lead and manage firm initiatives at the highest level, exhibit exemplary ownership extended across the organization, lead and codify knowledge areas firm-wide, and shape TAM's overall strategic direction.",
        indicators: [
          ['Leads firm at organizational level', "Drives development and enhancement of TAM's capabilities firm-wide."],
          ['Sets organizational ownership tone', 'Models accountability for TAM growth; fosters culture of shared responsibility.'],
          ['Leads knowledge areas firm-wide', 'Plays a pivotal role in developing and disseminating expertise across TAM.'],
          ['Shapes firm strategic direction', 'Codifies knowledge within firm-wide initiatives; influences strategic priorities.']
        ]
      },
      thought: {
        headline: "You define analytical strategy at the firm level.",
        desc: "Define analytical strategy at the firm level, drive data-informed strategy across the organization, anticipate systemic trends and root causes, and shape the firm's intellectual property and service offerings.",
        indicators: [
          ['Defines analytical strategy', 'Sets the firm-wide approach to analysis and frameworks.'],
          ['Drives data-informed strategy', 'Influences C-suite and Partner-level decisions with evidence-based scenarios.'],
          ['Anticipates systemic trends', 'Diagnoses industry-level root causes; refines firm IP and service offerings.'],
          ['Shapes IP and offerings', 'Identifies patterns across engagements to evolve firm strategy.']
        ]
      },
      people: {
        headline: "You shape the firm's people strategy and culture.",
        desc: "Build the firm's leadership pipeline, shape culture of collaboration and inclusion, sponsor a diverse range of leaders, and ensure constructive feedback drives growth at every level.",
        indicators: [
          ['Builds leadership pipeline', 'Develops and inspires senior leaders across the firm.'],
          ['Shapes culture firm-wide', 'Models inclusive environment; builds high-performing teams across departments.'],
          ['Sponsors diverse leaders', 'Strengths-based approach; supports career development at the most senior level.'],
          ['Drives feedback culture', 'Models constructive feedback; helps senior colleagues grow through regular dialogue.']
        ]
      }
    }
  };

  // BD framework — same 5 dimensions as Advisory (Client/Firm/Thought/People/Values)
  // Distilled from the BD Competency Framework PDF
  const BD_FRAMEWORK = {
    'analyst': {
      label: 'Analyst',
      client: {
        headline: "You're learning to represent TAM and communicate clearly with stakeholders.",
        desc: "As a BD Analyst, you convey a positive professional presence when representing TAM, build interpersonal skills with junior clients/stakeholders, demonstrate clear written and verbal communication including top-down techniques, and contribute to presentations by preparing decks and managing your activities reliably.",
        indicators: [
          ['Conveys positive, confident professional presence', 'Effectively represents TAM in a way that contributes to a positive initial impression.'],
          ['Builds interpersonal skills with junior clients', 'Develops a foundation for productive relationships with junior clients and stakeholders.'],
          ['Demonstrates good judgment of needs', 'Understands client/stakeholder needs and addresses them in proposals.'],
          ['Demonstrates clear written and verbal communication', 'Begins to understand and apply top-down communication principles.'],
          ['Contributes to presentations effectively', 'Can prepare presentation decks supporting BD efforts.'],
          ['Manages activities reliably', 'Consistently delivers on all commitments in a reliable and trustworthy manner.'],
          ['Identifies stakeholder gaps', 'Understands gaps in client/stakeholder context, recognizes improvement areas, and communicates them to leadership.']
        ]
      },
      firm: {
        headline: "You contribute as an owner from day one.",
        desc: "Contribute to firm initiatives, view yourself as an owner with strong sense of accountability, and begin to identify potential areas of knowledge or service lines to contribute to or build upon. Actively contribute to codification of knowledge within proposals.",
        indicators: [
          ['Contributes to firm initiatives', 'Participates in initiatives that improve TAM operations and capabilities.'],
          ['Acts like an owner', 'Views self as an owner, not just an employee, taking ownership of individual responsibilities with a strong sense of accountability.'],
          ['Identifies knowledge to share', 'Begins to identify potential areas of knowledge or service lines to contribute to or build upon.'],
          ['Contributes to knowledge codification', 'Actively contributes to the codification of knowledge within proposals.']
        ]
      },
      thought: {
        headline: "You bring foundational problem-solving skills and analytical rigor.",
        desc: "Demonstrate good problem-solving skills, structure parts of proposals with manager guidance, execute analytical tasks accurately, develop conceptual thinking, contribute to team problem-solving with pragmatic solutions, and use frameworks and tools to perform assigned work.",
        indicators: [
          ['Good problem-solving', 'Identifies issues and challenges within scope of work.'],
          ['Structures parts of proposals', 'Demonstrates a foundational understanding of effective structuring and story-lining (with manager guidance).'],
          ['Executes analytical tasks accurately', 'Performs analytical work efficiently, effectively, and accurately.'],
          ['Develops conceptual thinking', 'Demonstrates an emerging ability to think conceptually and develop creative insights.'],
          ['Contributes to team problem-solving', 'Participates with focus on pragmatic solutions for the client.'],
          ['Uses frameworks and tools', 'Efficiently uses appropriate frameworks and tools by understanding the relevance of related resources/content.']
        ]
      },
      people: {
        headline: "You collaborate well, build strong relationships, and seek feedback.",
        desc: "Collaborate effectively and build strong relationships with teammates, contribute positively to team energy and dynamics, understand coaching concepts, and seek feedback from leadership while providing constructive upward feedback.",
        indicators: [
          ['Collaborates and builds strong relationships', 'Works selflessly with colleagues to achieve common goals.'],
          ['Contributes positively to team energy', 'Demonstrates genuine concern for peers and clients.'],
          ['Understands coaching concepts', 'Identifies areas of improvement within oneself.'],
          ['Asks for and provides feedback', 'Asks for feedback from leadership and provides constructive upward feedback.']
        ]
      }
    },
    'sr-analyst': {
      label: 'Sr Analyst',
      client: {
        headline: "You produce near-client-ready documents with growing communication proficiency.",
        desc: "Convey confident professional presence, develop interpersonal skills with junior clients, identify gaps in client/stakeholder context, develop near-client-ready documents requiring limited support from the BD Manager, and contribute to presentations effectively.",
        indicators: [
          ['Conveys confident professional presence', 'Effectively represents TAM and contributes to a positive initial impression.'],
          ['Builds interpersonal skills', 'Develops a foundation for productive relationships with junior clients/stakeholders.'],
          ['Demonstrates good judgment', 'Understands client/stakeholder needs and addresses them in proposals.'],
          ['Develops near-client-ready documents', 'Requires limited support from the BD manager; showcases growing proficiency in communication and document preparation.'],
          ['Contributes to presentation decks', 'Can effectively prepare presentation decks.'],
          ['Manages activities efficiently', 'Consistently delivers on all commitments in a reliable and trustworthy manner.'],
          ['Identifies and communicates gaps', 'Identifies gaps in the client/stakeholder context, recognizes areas for improvement, and effectively communicates them to leadership.']
        ]
      },
      firm: {
        headline: "You actively share knowledge and codify learnings with the team.",
        desc: "Contribute to firm initiatives, take strong ownership of individual responsibilities, and actively acquire and share knowledge with the team. Contribute to knowledge codification, actively participating in knowledge-sharing efforts.",
        indicators: [
          ['Contributes to firm initiatives', 'Participates in initiatives that enhance TAM operations and capabilities.'],
          ['Strong ownership', 'Takes responsibility for individual responsibilities with strong sense of ownership and accountability.'],
          ['Actively shares knowledge', 'Acquires and shares learnings with the team.'],
          ['Codifies knowledge', 'Contributes to the codification of knowledge, actively participating in knowledge-sharing efforts.']
        ]
      },
      thought: {
        headline: "You drive issue identification and structure problem-solving in proposals.",
        desc: "Drive issue identification and problem structuring, taking the lead on aspects of problem-solving in client issues and addressing them in proposals. Structure parts of proposals with manager guidance, execute analytical tasks effectively, and apply frameworks effectively.",
        indicators: [
          ['Drives issue identification', 'Takes the lead on aspects of problem-solving in client issues and addressing them in proposals.'],
          ['Structures parts of proposals', 'Demonstrates foundational understanding of effective structuring and story-lining (with manager guidance).'],
          ['Executes analytical tasks effectively', 'Performs analytical work efficiently, effectively, and accurately.'],
          ['Develops conceptual thinking', 'Demonstrates an emerging ability to think conceptually and develop creative insights.'],
          ['Contributes pragmatic solutions', 'Participates in team problem-solving with focus on pragmatic solutions for the client/stakeholder.'],
          ['Uses frameworks effectively', 'Efficiently uses appropriate frameworks and tools by understanding the relevance of related resources/content.']
        ]
      },
      people: {
        headline: "You support training and coaching of others.",
        desc: "Collaborate effectively, contribute positively to team energy and dynamics, support training and coaching others to aid in their development, and provide constructive upward feedback while seeking feedback from leadership.",
        indicators: [
          ['Collaborates effectively', 'Builds strong relationships with teammates; works selflessly with colleagues.'],
          ['Contributes to team energy', 'Positively contributes to team dynamics; demonstrates genuine concern for peers and clients.'],
          ['Supports training and coaching', 'Supports in training, coaching, and leading others to aid in their development.'],
          ['Identifies areas of improvement', "Identifies areas of improvement within one's self."],
          ['Asks for and provides feedback', 'Asks for feedback from leadership and provides constructive upward feedback.']
        ]
      }
    },
    'associate': {
      label: 'Associate',
      client: {
        headline: "You take a lead in cultivating client relationships and providing value.",
        desc: "Take a lead in cultivating junior client relationships and fostering long-term collaboration, establish collaborative coaching relationships with junior clients, exhibit solid understanding of client context, communicate compellingly using top-down techniques, develop near-client-ready documents, and lead development of presentation decks with confidence.",
        indicators: [
          ['Takes a lead in cultivating junior client relationships', 'Fosters long-term collaboration through coaching and support.'],
          ['Establishes coaching relationships', 'Provides guidance and support to junior clients.'],
          ['Exhibits solid understanding of context', 'Translates context into actionable solutions within proposals.'],
          ['Communicates in clear, compelling, convincing manner', 'Effectively employs top-down communication techniques in written and verbal forms.'],
          ['Develops near-client-ready documents', 'Showcases growing proficiency in communication and document preparation; requires limited support from the BD manager.'],
          ['Leads development of presentation decks', 'Shows good understanding of creating effective presentations with ability to present internally.'],
          ['Works independently and reliably', "Demonstrates a growing capacity to contribute to proposals while ensuring TAM's work provides value."]
        ]
      },
      firm: {
        headline: "You actively take ownership and lead knowledge sharing.",
        desc: "Identify areas of improvement and contribute to firm initiatives, demonstrate growing sense of ownership while proactively seeking opportunities, actively acquire and share knowledge, and contribute to codification of knowledge.",
        indicators: [
          ['Identifies improvement areas', "Actively contributes to firm initiatives designed to enhance TAM's operations and capabilities."],
          ['Growing ownership', 'Demonstrates a growing sense of ownership; actively takes responsibility for tasks.'],
          ['Proactively seeks value', 'Proactively seeks opportunities to enhance value.'],
          ['Actively shares knowledge', 'Acquires and shares knowledge with the team.'],
          ['Codifies knowledge', 'Contributes to knowledge codification, actively participating in knowledge-sharing efforts.']
        ]
      },
      thought: {
        headline: "You independently structure proposals and drive analytical work.",
        desc: "Drive issue identification and problem structuring, take the lead on aspects of problem-solving in proposals, independently structure standard proposals with limited guidance, demonstrate competence in complex analytical tasks, and actively contribute clear, reasonable, and actionable solutions.",
        indicators: [
          ['Drives issue identification and problem structuring', 'Takes the lead on aspects of problem-solving in client issues and addressing them in proposals.'],
          ['Independently structures standard proposals', 'Showcases growing proficiency in structuring; requires only limited guidance from managers.'],
          ['Demonstrates analytical competence', 'Clear thinking and attention to detail in complex analytical tasks.'],
          ['Drives actionable solutions', 'Actively contributes to driving clear, reasonable, and actionable solutions for clients/stakeholders.'],
          ['Contributes integrated thinking', "Actively contributes knowledge and integrated thinking to team problem-solving."],
          ['Adapts frameworks effectively', 'Actively seeks and adapts relevant frameworks and tools to enhance problem-solving.']
        ]
      },
      people: {
        headline: "You lead collaboration, manage juniors, and coach others.",
        desc: "Lead and facilitate collaboration among team members, manage small groups of junior colleagues to deliver specific tasks, support training and coaching through onboarding, identify areas of improvement in yourself, and deliver regular constructive feedback both upward and downward.",
        indicators: [
          ['Leads and facilitates collaboration', 'Demonstrates a proactive approach to team cohesion and problem-solving through effective collaboration.'],
          ['Manages small groups of juniors', 'Able to manage a small group of junior colleagues to deliver a specific task.'],
          ['Supports training and coaching', 'Through onboarding and leading others to aid in their development.'],
          ['Self-aware about improvement', "Identifies areas of improvement within one's self."],
          ['Delivers constructive feedback', 'Asks for feedback from leadership and provides constructive upward feedback. Helps colleagues grow by delivering regular constructive feedback.']
        ]
      }
    },
    'sr-associate': {
      label: 'Sr Associate',
      client: {
        headline: "You build lasting relationships and lead client-facing meetings confidently.",
        desc: "Take a lead in cultivating client relationships and fostering long-term collaboration, develop collaborative and lasting relationships maintained even after proposals close, create client-ready documents independently with high level of competence, and demonstrate strong meeting facilitation and presentation skills.",
        indicators: [
          ['Takes a lead in cultivating client relationships', 'Fosters long-term collaboration with clients.'],
          ['Develops lasting relationships', 'Maintains connections with clients after proposals are completed.'],
          ['Translates context into solutions', "Exhibits solid understanding of the client's context within proposals."],
          ['Communicates compellingly', 'Effectively employs top-down communication techniques in written and verbal forms.'],
          ['Creates client-ready documents independently', 'Displays high level of competence in crafting clear and effective communication materials.'],
          ['Demonstrates meeting facilitation skills', 'Runs meetings effectively, engaging clients through compelling presentations.'],
          ['Works independently and reliably', 'Consistently delivers on commitments; demonstrates growing capacity to contribute to proposals.']
        ]
      },
      firm: {
        headline: "You lead knowledge sharing and codification within the team.",
        desc: "Identify improvement areas and contribute to firm initiatives, demonstrate growing ownership of tasks, deeply understand knowledge areas and service lines, actively lead knowledge-sharing initiatives, and take charge of knowledge codification efforts while fostering continuous learning.",
        indicators: [
          ['Contributes to firm initiatives', "Identifies improvement areas; actively contributes to TAM's enhancement."],
          ['Growing ownership', 'Actively takes responsibility for tasks; proactively seeks opportunities to enhance value.'],
          ['Deep understanding of service lines', 'Demonstrates strong knowledge of service offerings.'],
          ['Leads knowledge sharing', 'Actively leads knowledge-sharing initiatives within the team.'],
          ['Takes charge of codification', 'Fosters a culture of continuous learning through knowledge codification.']
        ]
      },
      thought: {
        headline: "You lead problem-solving in proposals with strong analytical depth.",
        desc: "Take charge of issue identification and problem structuring, effectively lead problem-solving efforts within proposals, structure technical and financial proposals with limited guidance, demonstrate competence and attention to detail in complex analytical tasks, and adapt frameworks effectively.",
        indicators: [
          ['Leads problem-solving in proposals', 'Effectively leads problem-solving efforts within for the proposals.'],
          ['Structures technical and financial proposals', 'Shows growing proficiency; requires only limited guidance from managers.'],
          ['Detail-oriented analytical work', 'Clear thinking and attention to detail in complex analytical tasks.'],
          ['Drives actionable solutions', 'Actively contributes to driving clear, reasonable, actionable solutions for clients.'],
          ['Integrates thinking for team', "Brings integrated thinking to team's problem-solving efforts."],
          ['Adapts frameworks effectively', 'Actively seeks and adapts relevant frameworks and tools to enhance problem-solving.']
        ]
      },
      people: {
        headline: "You train and coach others, contributing to their growth.",
        desc: "Lead and facilitate collaboration among team members, contribute positively to team dynamics, train and coach others while actively supporting their growth and skill enhancement, and provide regular constructive feedback that helps colleagues develop.",
        indicators: [
          ['Leads collaboration', 'Demonstrates a proactive approach to team cohesion through effective collaboration.'],
          ['Contributes to team dynamics', 'Positively contributes to team energy; shows genuine concern for peers and clients.'],
          ['Trains and coaches others', 'Actively contributes to the growth and skill enhancement of colleagues.'],
          ['Provides regular constructive feedback', 'Helps colleagues grow through regular feedback delivery.']
        ]
      }
    },
    'manager': {
      label: 'Manager',
      client: {
        headline: "You build trusted advisor relationships and shape client expectations.",
        desc: "Take a lead in cultivating senior client relationships, develop comprehensive understanding of the 'big picture', anticipate and address client requirements proactively, communicate compellingly in critical situations, and present effectively to high-level executives.",
        indicators: [
          ['Cultivates senior client relationships', 'Maintains connections with clients after proposals are completed; fosters long-term collaboration.'],
          ['Big-picture understanding', 'Comprehensive understanding of the client context; can lead discussions on future client needs.'],
          ['Anticipates client requirements', 'Proactively addresses needs and frustrations.'],
          ['Communicates compellingly in critical situations', 'Demonstrates mastery of top-down communications by synthesizing information effectively rather than just summarizing.'],
          ['Presents to executives', 'Showcases advanced ability to communicate effectively with high-level executives and stakeholders.'],
          ['Tailors solutions to client needs', 'Actively engages in problem-solving to provide valuable results, especially in critical situations.'],
          ['Manages client expectations', 'Negotiates with procurement and senior clients; ensures team meets all commitments and deadlines.']
        ]
      },
      firm: {
        headline: "You lead by example and instill ownership culture.",
        desc: "Identify improvement areas and lead firm initiatives that enhance TAM's operations, instill a culture of ownership in the team, take full ownership of proposals, lead knowledge areas, and take charge of knowledge codification across firm-wide initiatives.",
        indicators: [
          ['Leads firm initiatives', "Actively contributes to initiatives designed to enhance TAM's capabilities."],
          ['Instills ownership culture', 'Leads by example; fosters responsibility among team members.'],
          ['Full ownership of proposals', 'Takes full ownership; ensures collective ownership of TAM successes.'],
          ['Leads knowledge areas', 'Plays a pivotal role in developing and disseminating expertise.'],
          ['Codifies knowledge across firm', 'Takes the lead in codifying knowledge within projects and firm-wide initiatives.']
        ]
      },
      thought: {
        headline: "You lead complex problem-solving and integrate cross-disciplinary thinking.",
        desc: "Take charge of issue identification and problem structuring, lead the structuring of proposals with hands-on guidance, develop clear and actionable solutions, foster inclusive and creative problem-solving in the team, and integrate thinking across industries, functions, and frameworks.",
        indicators: [
          ['Takes charge of issue identification', 'Effectively leads problem-solving efforts within for the proposals.'],
          ['Leads structuring of proposals', 'Offers guidance to team members; actively shaping and refining the approach.'],
          ['Develops clear, actionable solutions', 'Solutions based on thorough analysis.'],
          ['Fosters inclusive problem-solving', 'Actively encourages and implements innovative solutions and ideas.'],
          ['Guides team thinking', "Takes a leadership role in guiding knowledge and integrated thinking within the team's efforts."],
          ['Integrates across functions', 'Generates innovative and comprehensive solutions; promotes resourcefulness within the team.']
        ]
      },
      people: {
        headline: "You manage and develop your team, fostering high performance.",
        desc: "Foster collaboration within the team, create effective plans and manage resources appropriately, demonstrate ability to address collaboration challenges, train and coach others to aid in their development, and ask for and provide regular constructive feedback.",
        indicators: [
          ['Fosters collaboration', 'Proactively encourages and guides team members to work cohesively; leverages diverse strengths.'],
          ['Manages resources effectively', 'Creates effective plans for team and other internal resources.'],
          ['Manages team health', "Leads team's health, energy and dynamics; demonstrates concern for peers and clients."],
          ['Recognizes team efforts', 'Recognizes teams for their efforts; manages upward intelligently.'],
          ['Trains and coaches', 'Actively contributes to growth and skill enhancement of colleagues.'],
          ['Asks for and provides feedback', 'Asks for feedback; helps colleagues grow through regular constructive feedback.']
        ]
      }
    },
    'sr-manager': {
      label: 'Sr Manager',
      client: {
        headline: "You build long-lasting business relationships at senior client levels.",
        desc: "Build long-lasting business relationships that serve TAM's immediate and long-term goals, shape and execute strategic vision of client relationships, drive business growth and long-term connections, and play a key role in enhancing TAM's strategic partnerships.",
        indicators: [
          ['Builds long-lasting relationships', "Plays a key role in enhancing TAM's strategic partnerships; serves immediate and long-term objectives."],
          ['Shapes strategic vision', 'Drives business growth and long-term connections through strategic vision of client relationships.'],
          ['Comprehensive big-picture understanding', 'Leads discussions on future client needs; anticipates and addresses requirements proactively.'],
          ['Communicates compellingly to executives', 'Demonstrates mastery of top-down communication through synthesis rather than summarization.'],
          ['Tailors solutions to client needs', 'Actively engages in problem-solving to provide valuable results, especially in critical situations.'],
          ['Manages senior client relationships', 'Manages expectations and frustration; negotiates with procurement and senior clients.'],
          ['Ensures team meets commitments', 'Delivers intended impact on all assigned proposals; ensures team meets deadlines and expectations.']
        ]
      },
      firm: {
        headline: "You lead firm initiatives and develop TAM's expertise.",
        desc: "Lead and manage firm initiatives that drive development and enhancement of TAM's capabilities, lead by example to instill ownership culture, lead knowledge areas across TAM, and codify knowledge in projects and firm-wide initiatives.",
        indicators: [
          ['Leads and manages firm initiatives', "Drives development and enhancement of TAM's capabilities."],
          ['Instills ownership culture', 'Leads by example; fosters responsibility among team members; ensures collective ownership.'],
          ['Leads knowledge areas across TAM', 'Plays a pivotal role in developing and disseminating expertise throughout TAM.'],
          ['Codifies knowledge firm-wide', 'Takes the lead in codifying knowledge within projects and firm-wide initiatives.']
        ]
      },
      thought: {
        headline: "You apply rigor to complex challenges and lead by example in advanced techniques.",
        desc: "Approach problem-solving with rigor, offer innovative and insightful solutions to complex challenges, lead by example in applying advanced techniques, lead structuring of proposals with hands-on guidance, foster inclusive problem-solving, and integrate thinking across industries.",
        indicators: [
          ['Approaches problems with rigor', 'Offers innovative and insightful solutions to complex challenges.'],
          ['Leads by example in advanced techniques', 'Applies advanced problem-solving methodologies.'],
          ['Leads structuring of proposals', 'Offers guidance to team members and actively shapes and refines the approach.'],
          ['Develops actionable solutions', 'Clear, reasonable, and actionable solutions based on analysis.'],
          ['Fosters innovative problem-solving', 'Actively encourages and implements innovative solutions and ideas within the team.'],
          ['Integrates across industries', 'Generates innovative solutions; promotes resourcefulness within the team.']
        ]
      },
      people: {
        headline: "You drive collaboration and develop high-performing teams.",
        desc: "Lead the team in driving collaborative and inclusive culture, create inclusive and respectful environments, develop and recognize high-performing juniors, train and coach others, and provide regular constructive feedback at scale.",
        indicators: [
          ['Drives collaborative culture', 'Proactively encourages cohesion and leverages diverse strengths.'],
          ['Creates inclusive environments', 'Develops, inspires, and recognizes juniors; builds high-performing teams.'],
          ['Trains and coaches', 'Actively contributes to growth and skill enhancement of colleagues.'],
          ['Provides constructive feedback', 'Asks for and provides upward feedback; helps colleagues grow through regular feedback.']
        ]
      }
    },
    'director': {
      label: 'Director',
      client: {
        headline: "You cultivate strategic trust and drive expansion opportunities.",
        desc: "Build long-lasting business relationships at the highest level, shape strategic vision of client relationships, apply in-depth understanding of client industry to shape client-centric solutions, and develop sustainable solutions that consider future implications.",
        indicators: [
          ['Cultivates strategic trust', 'Develops trusted partner status; portfolio-level understanding of business.'],
          ['Shapes long-term vision', 'Drives strategic vision of client relationships across the portfolio.'],
          ['Applies industry understanding', 'In-depth knowledge of client industry, challenges, and goals.'],
          ['Manages external communications', 'Sets high standards for clarity and effectiveness; maintains trust as a valued business partner.'],
          ['Excels in presentation skills', 'Sets the gold standard for presentation techniques within TAM.'],
          ['Develops sustainable solutions', 'Considers future implications and client requirements.'],
          ['Goes beyond proposal delivery', 'Actively creates opportunities for broadening client impact.']
        ]
      },
      firm: {
        headline: "You exhibit exemplary ownership at organizational level.",
        desc: "Lead firm initiatives, exhibit exemplary ownership extended to organizational levels, demonstrate strong accountability for TAM's growth, drive ownership culture, lead knowledge areas, and codify knowledge across firm-wide initiatives.",
        indicators: [
          ['Leads firm initiatives', "Drives development and enhancement of TAM's capabilities."],
          ['Exemplary organizational ownership', "Demonstrates strong accountability for TAM's growth; fosters culture of shared responsibility."],
          ['Leads knowledge areas firm-wide', 'Plays a pivotal role in developing and disseminating expertise.'],
          ['Codifies knowledge in firm-wide initiatives', 'Takes lead in codifying knowledge within projects and firm-wide initiatives.']
        ]
      },
      thought: {
        headline: "You bring new perspectives and develop creative problem-solving frameworks.",
        desc: "Approach problem-solving with rigor, bring new perspectives and innovative ideas to enhance structuring and story-lining, develop clear and actionable solutions, foster inclusive problem-solving, develop creative frameworks and culture of innovation, and integrate thinking across industries.",
        indicators: [
          ['Approaches problems with rigor', 'Offers innovative and insightful solutions to complex challenges.'],
          ['Brings new perspectives', 'Enhances structuring and story-lining techniques.'],
          ['Develops clear, actionable solutions', 'Solutions based on thorough analysis.'],
          ['Fosters creative problem-solving', 'Actively encourages and implements innovative solutions and ideas.'],
          ['Develops creative frameworks', 'Fosters a culture of innovation within TAM.'],
          ['Integrates across industries', 'Generates innovative solutions; promotes resourcefulness within the team.']
        ]
      },
      people: {
        headline: "You sponsor diverse colleagues and build high-performing teams.",
        desc: "Foster cross-team collaboration, develop and inspire high-performing teams, sponsor career development of a diverse range of colleagues, and provide constructive feedback that drives growth at all levels.",
        indicators: [
          ['Fosters collaboration', 'Proactively encourages cohesion across team and with other departments.'],
          ['Builds high-performing teams', 'Develops, inspires, and recognizes juniors; creates inclusive environments.'],
          ['Coaches and challenges', 'Strengths-based approach; sponsors a diverse range of colleagues.'],
          ['Supports career development', 'Actively supports career development across TAM.'],
          ['Provides constructive feedback', 'Asks for feedback; helps colleagues grow through regular constructive feedback.']
        ]
      }
    },
    'sr-director': {
      label: 'Sr Director',
      client: {
        headline: "You shape TAM's strategic client portfolio at the highest level.",
        desc: "Build long-lasting business relationships at the executive level, shape strategic vision across the portfolio, drive thought leadership for clients and stakeholders, and ensure communication efforts build TAM's reputation as a trusted advisor across the firm.",
        indicators: [
          ['Builds executive-level relationships', "Plays a key role in enhancing TAM's strategic partnerships at the highest level."],
          ['Shapes portfolio strategy', 'Drives strategic vision of client relationships across the firm.'],
          ['Drives thought leadership', 'Provides strategic guidance to clients and stakeholders.'],
          ['Sets the standard for communication', 'Excels in presentation skills; sets the gold standard for presentation techniques.'],
          ['Develops sustainable solutions', 'Considers future implications and client requirements at strategic scale.'],
          ['Creates opportunities for broadening impact', 'Goes beyond proposal delivery to actively expand client impact.']
        ]
      },
      firm: {
        headline: "You shape TAM's organizational direction and culture.",
        desc: "Lead and manage firm initiatives at the highest level, exhibit exemplary ownership extended across the organization, lead and codify knowledge areas firm-wide, and shape TAM's overall strategic direction and culture of shared responsibility.",
        indicators: [
          ['Leads firm at organizational level', "Drives development and enhancement of TAM's capabilities firm-wide."],
          ['Sets organizational ownership tone', 'Models accountability for TAM growth; fosters shared responsibility culture.'],
          ['Leads knowledge areas firm-wide', 'Plays a pivotal role in developing and disseminating expertise across TAM.'],
          ['Shapes firm strategic direction', 'Codifies knowledge within firm-wide initiatives; influences strategic priorities.']
        ]
      },
      thought: {
        headline: "You define analytical and strategic vision for the firm.",
        desc: "Define problem-solving approaches at the firm level, lead innovation in structuring and storytelling, shape creative problem-solving frameworks, drive a culture of innovation, and integrate thinking across industries to evolve firm IP.",
        indicators: [
          ['Defines firm-level approaches', 'Sets the firm-wide approach to problem-solving and frameworks.'],
          ['Leads innovation', 'Brings new perspectives that evolve structuring and story-lining at scale.'],
          ['Shapes creative frameworks', 'Develops problem-solving frameworks adopted across the firm.'],
          ['Drives innovation culture', 'Fosters a culture of innovation within TAM.'],
          ['Evolves firm IP', 'Integrates thinking across industries to refine firm IP and service offerings.']
        ]
      },
      people: {
        headline: "You shape the firm's people strategy and culture.",
        desc: "Build the firm's leadership pipeline, shape culture of collaboration and inclusion, sponsor a diverse range of leaders, and ensure constructive feedback drives growth at every level.",
        indicators: [
          ['Builds leadership pipeline', 'Develops and inspires senior leaders across the firm.'],
          ['Shapes culture firm-wide', 'Models inclusive environment; builds high-performing teams across departments.'],
          ['Sponsors diverse leaders', 'Strengths-based approach; supports career development at the most senior level.'],
          ['Drives feedback culture', 'Models constructive feedback; helps senior colleagues grow through regular dialogue.']
        ]
      }
    }
  };

  // ============ DIGITAL FRAMEWORK ============
  // Digital uses 4 dimensions: Client & Stakeholder Leadership / Making an Impact / Technical Capabilities / People Leadership
  // Plus Values (universal). It also has 6 technical tracks with their own level naming.
  const DIGITAL_FRAMEWORK = {
    _schema: 'digital',
    _trackable: true,
    _trackOptions: [
      { key: 'product-management', label: 'Business — Product Management' },
      { key: 'product-ops', label: 'Business — Product Operations & PMO' },
      { key: 'uiux-delivery', label: 'Technical — UI/UX Delivery' },
      { key: 'software-engineering', label: 'Technical — Software Engineering' },
      { key: 'uiux-design', label: 'Technical — UI/UX Design' },
      { key: 'customer-experience', label: 'Technical — Customer Experience' }
    ],

    'analyst': {
      label: 'Analyst',
      client_stakeholder: {
        headline: "You provide accurate service and communicate clearly with stakeholders.",
        desc: "Provide accurate and efficient service to Tamers and stakeholders, communicate effectively with team members and internal stakeholders giving clear and concise updates, and continuously develop expertise to provide value-added services to clients and stakeholders.",
        indicators: [
          ['Quality of service', 'Provides accurate and efficient service; understands company policies, procedures, and industry standards.'],
          ['Building strong relationships', 'Communicates effectively with team members and internal stakeholders; articulates ideas clearly, tailoring style to the audience.'],
          ['Solution-focused', 'Strong desire to learn and develop expertise; proactively seeks opportunities to expand knowledge and apply it.']
        ]
      },
      making_impact: {
        headline: "You look for process improvements and report data with quality.",
        desc: "Constantly look for opportunities to improve processes and increase efficiencies, maintain data and generate standardized reporting with high quality, and have a proficient understanding of relevant regulations and compliance requirements.",
        indicators: [
          ['Driving process improvements', 'Identifies and eliminates redundant tasks; works collaboratively to implement and track improvements.'],
          ['Delivering strategic insights', 'Maintains data and generates standardized reporting with high quality.'],
          ['Ensuring compliance and risk management', 'Proficient understanding of regulations; identifies risks and escalates appropriately.']
        ]
      },
      technical: {
        headline: "You're building foundational technical skills in your area.",
        desc: "Develop foundational skills in your technical area with familiarity in core concepts and ability to perform operational tasks. Specific expectations vary by track (PM, PMO, UI/UX Delivery, Software Engineering, UI/UX Design, Customer Experience).",
        indicators: [
          ['Mastery of automation and products', 'Proficient understanding of products used by the organization; can troubleshoot and report issues.'],
          ['Track-specific capabilities', 'Specific expectations depend on your track. PM: develops foundational understanding of product strategy. SWE: develops foundational programming skills. Design: develops basic visual and research skills. CX: basic human-centered design understanding.']
        ]
      },
      people: {
        headline: "You collaborate well, support others, and celebrate team success.",
        desc: "Work effectively as part of a team, share knowledge with colleagues, be open to mentoring while taking initiative to research independently, and celebrate team and individual successes.",
        indicators: [
          ['Collaboration', 'Communicates and collaborates effectively; shares knowledge; willing to learn from others.'],
          ['Support and mentorship', 'Takes actionable steps to research independently; asks for support timely; supports and assists colleagues.'],
          ['Recognition and celebration', 'Celebrates team and individual successes; promotes a positive and supportive culture.']
        ]
      }
    },

    'sr-analyst': {
      label: 'Sr Analyst',
      client_stakeholder: {
        headline: "You handle complex needs and identify process improvements.",
        desc: "Have a deeper understanding of company policies and standards applied to complex needs, communicate clearly with internal stakeholders at all levels anticipating issues proactively, and continuously update expertise while identifying emerging trends.",
        indicators: [
          ['Quality of service', 'Deep understanding of policies and standards applied to more complex Tamer and stakeholder needs.'],
          ['Building strong relationships', 'Communicates clearly with stakeholders at all levels; anticipates and proactively addresses communication issues.'],
          ['Solution-focused', 'Continuously updates expertise; identifies emerging trends and opportunities; communicates insights to colleagues.']
        ]
      },
      making_impact: {
        headline: "You drive process improvements and mentor on methodologies.",
        desc: "Constantly look for improvement opportunities and mentor specialists on process improvement methodologies, suggest new reporting processes that improve efficiency and accuracy, and proactively identify and mitigate compliance risks.",
        indicators: [
          ['Driving process improvements', 'Mentors and trains specialist-level team members on methodologies and tools.'],
          ['Delivering strategic insights', 'Knowledge of data management; suggests new reporting processes; identifies improvement opportunities.'],
          ['Ensuring compliance and risk management', 'Strong understanding of regulations; proactively identifies and mitigates risks; provides guidance.']
        ]
      },
      technical: {
        headline: "You demonstrate proficiency in your technical area.",
        desc: "Apply proficient technical skills, support junior colleagues with system utilization, and contribute to improvements in tools and workflows. Specific expectations vary by track.",
        indicators: [
          ['Mastery of automation and products', 'Deep understanding of products; provides expert guidance to juniors; suggests improvements that increase efficiency.'],
          ['Track-specific capabilities', 'Specific expectations depend on your track. PM: proficient in roadmaps and market research. SWE: proficient in writing clean efficient code. Design: proficient in user research and wireframing. CX: developing journey mapping and HCD proficiency.']
        ]
      },
      people: {
        headline: "You collaborate, support juniors, and recognize achievements.",
        desc: "Collaborate effectively with stakeholders, work independently while seeking guidance from seniors, mentor and support juniors, and recognize team achievements actively.",
        indicators: [
          ['Collaboration', 'Builds strong relationships; works independently while seeking guidance as needed.'],
          ['Support and mentorship', 'Collaborates effectively; provides guidance and assistance; continues active learning.'],
          ['Recognition and celebration', 'Recognizes and celebrates successes; participates in showing appreciation.']
        ]
      }
    },

    'associate': {
      label: 'Associate',
      client_stakeholder: {
        headline: "You consistently deliver high-quality service and communicate with diverse stakeholders.",
        desc: "Consistently deliver high-quality service to Tamers and stakeholders handling routine and non-routine tasks, communicate effectively with a variety of stakeholders adapting style to needs, and work with clients to identify challenges and develop data-driven recommendations.",
        indicators: [
          ['Quality of service', 'Consistently delivers high-quality service handling routine and non-routine tasks with professionalism.'],
          ['Building strong relationships', 'Communicates effectively with team members, managers, and cross-functional partners; adapts style.'],
          ['Solution-focused', 'Works with stakeholders to identify challenges; analyzes data to draw insights; collaborates on solutions.']
        ]
      },
      making_impact: {
        headline: "You take ownership of process improvements and analyze complex data.",
        desc: "Take ownership of process improvements working collaboratively with cross-functional teams, interpret complex information and identify trends, communicate findings to stakeholders, and proactively implement risk mitigation strategies.",
        indicators: [
          ['Driving process improvements', 'Takes ownership; works with cross-functional teams; develops and implements new policies.'],
          ['Delivering strategic insights', 'Solid understanding of data analysis; interprets complex information; communicates findings.'],
          ['Ensuring compliance and risk management', 'Takes ownership of compliance and risk; collaborates with stakeholders; proactively implements strategies.']
        ]
      },
      technical: {
        headline: "You apply advanced technical skills and own quality standards.",
        desc: "Apply advanced technical skills appropriate to your track, take ownership of data quality and accuracy, and identify opportunities to streamline workflows. Specific expectations vary by track.",
        indicators: [
          ['Mastery of automation and products', 'Navigates and troubleshoots products; takes ownership of data quality and accuracy.'],
          ['Track-specific capabilities', 'Specific expectations depend on your track. PM: expert in product strategies and roadmaps. SWE: advanced multi-language proficiency, system design. Design: drives user-centered design practices. CX: proficient in HCD principles and methodologies.']
        ]
      },
      people: {
        headline: "You build effective working relationships and contribute to team success.",
        desc: "Build and maintain effective working relationships with colleagues and stakeholders, contribute to team success and go above and beyond, take actionable steps to research independently, and celebrate team successes serving as a positive role model.",
        indicators: [
          ['Collaboration', 'Builds and maintains effective relationships; contributes to team success; willing to go above and beyond.'],
          ['Support and mentorship', 'Takes actionable steps to research independently; willing to learn; seeks development opportunities.'],
          ['Recognition and celebration', 'Celebrates team and individual successes; serves as positive role model.']
        ]
      }
    },

    'sr-associate': {
      label: 'Sr Associate',
      client_stakeholder: {
        headline: "You handle complex challenges and lead data-driven recommendations.",
        desc: "Consistently deliver high-quality service handling complex and challenging tasks with minimal guidance, communicate effectively with broader stakeholders including cross-functional partners, and lead collaborative efforts to provide data-driven recommendations.",
        indicators: [
          ['Quality of service', 'Consistently delivers high-quality service for complex tasks; resolves issues with minimal guidance.'],
          ['Building strong relationships', 'Communicates effectively with broader stakeholders; communicates complex ideas clearly.'],
          ['Solution-focused', 'Leads collaborative efforts; analyzes data from multiple sources; provides insights for decisions.']
        ]
      },
      making_impact: {
        headline: "You lead process improvements and take a leadership role in compliance.",
        desc: "Lead process improvements working with cross-functional teams, advanced understanding of data analysis providing strategic recommendations, mentor junior team members, and take a leadership role in compliance and risk management.",
        indicators: [
          ['Driving process improvements', 'Leads improvements; proactively seeks feedback; mentors juniors to continuously improve efficiency.'],
          ['Delivering strategic insights', 'Advanced understanding of data analysis; provides strategic recommendations; mentors juniors.'],
          ['Ensuring compliance and risk management', 'Takes leadership role; collaborates with stakeholders; mentors associates; proactively implements strategies.']
        ]
      },
      technical: {
        headline: "You lead technical efforts and develop strategies.",
        desc: "Lead technical efforts in your area, develop strategies to improve quality and streamline workflows, and mentor junior team members. Specific expectations vary by track.",
        indicators: [
          ['Mastery of automation and products', 'Leads troubleshooting; develops and implements quality measures; collaborates cross-functionally on strategy.'],
          ['Track-specific capabilities', 'Specific expectations depend on your track. PM: leads roadmap creation and provides strategic UX guidance. SWE: leads teams in solving complex problems. Design: leads user research and complex UI design. CX: leads and mentors junior designers.']
        ]
      },
      people: {
        headline: "You lead team culture and develop juniors actively.",
        desc: "Take a leadership role in promoting positive collaborative team culture, actively contribute to development of junior team members, and lead recognition culture providing opportunities for celebration.",
        indicators: [
          ['Collaboration', 'Builds effective relationships; takes leadership role in positive culture; goes above and beyond.'],
          ['Support and mentorship', 'Actively contributes to junior development through guidance, feedback, and mentorship.'],
          ['Recognition and celebration', 'Actively promotes recognition culture; provides celebration opportunities; leads by example.']
        ]
      }
    },

    'manager': {
      label: 'Manager',
      client_stakeholder: {
        headline: "You lead the team in delivering high-quality service and building strong client relationships.",
        desc: "Effectively lead your team in providing high-quality service, lead the team in building and maintaining strong client relationships through effective communication, and lead the team in identifying and implementing solutions to client needs.",
        indicators: [
          ['Quality of service', 'Leads team in high-quality service; identifies improvements; monitors performance and provides coaching.'],
          ['Building strong relationships', 'Leads team in building relationships; develops communication strategies; handles difficult conversations professionally.'],
          ['Solution-focused', 'Leads team in identifying and implementing customized solutions for specific needs.']
        ]
      },
      making_impact: {
        headline: "You manage process improvements and oversee compliance frameworks.",
        desc: "Effectively manage process improvement initiatives setting clear goals and metrics, lead development of strategic insights using data to inform decisions, and oversee compliance and risk management approach in your function.",
        indicators: [
          ['Driving process improvements', 'Establishes goals and metrics; leads cross-functional teams; works with stakeholders on solutions.'],
          ['Delivering strategic insights', 'Leads strategic insights development; uses data for recommendations; oversees departmental analytics.'],
          ['Ensuring compliance and risk management', 'Establishes protocols; conducts risk assessments; develops risk register; ensures team is trained.']
        ]
      },
      technical: {
        headline: "You oversee technical operations and drive culture of excellence.",
        desc: "Oversee technical operations and processes ensuring optimization, work with stakeholders to evaluate and implement improvements, and contribute to product/process strategy. Specific expectations vary by track.",
        indicators: [
          ['Mastery of automation and products', 'Oversees product operations; ensures optimization; works with stakeholders on improvements.'],
          ['Track-specific capabilities', 'Specific expectations depend on your track. PM: sets product strategy direction. SWE: experienced in leading technical initiatives across teams. Design: leads UX strategy. CX: provides expertise and thought leadership in HCD.']
        ]
      },
      people: {
        headline: "You establish team culture, mentor, and create celebration culture.",
        desc: "Establish and maintain a collaborative and inclusive team culture fostering open communication, lead the team in providing effective support and mentorship to colleagues, and establish a culture of celebration and recognition setting clear performance metrics.",
        indicators: [
          ['Collaboration', 'Establishes inclusive culture; resolves conflicts; manages challenges constructively.'],
          ['Support and mentorship', 'Leads team in support and mentorship; oversees personalized learning plans.'],
          ['Recognition and celebration', 'Establishes celebration culture; sets metrics; recognizes and rewards achievements.']
        ]
      }
    },

    'sr-manager': {
      label: 'Sr Manager',
      client_stakeholder: {
        headline: "You strategically lead service delivery and high-level relationships.",
        desc: "Strategically lead and manage your team in providing high-quality service developing strategic plans, develop and implement strategies to build strong relationships at high levels, and provide innovative solutions to enhance the client experience.",
        indicators: [
          ['Quality of service', 'Develops strategic plans; collaborates across teams; analyzes metrics; provides innovative solutions.'],
          ['Building strong relationships', 'Develops high-level stakeholder strategies; navigates complex environments; mentors team in communication.'],
          ['Solution-focused', 'Strategically leads team in innovative solutions; analyzes metrics for continuous improvement.']
        ]
      },
      making_impact: {
        headline: "You lead large-scale process initiatives and provide strategic data direction.",
        desc: "Lead and direct large-scale process improvement initiatives providing strategic guidance, leverage data and insights to inform decision-making, and provide strategic direction for compliance and risk management.",
        indicators: [
          ['Driving process improvements', 'Leads large-scale initiatives; provides strategic guidance to cross-functional teams.'],
          ['Delivering strategic insights', 'Provides strategic direction; leverages data; oversees departmental analytics for senior leadership.'],
          ['Ensuring compliance and risk management', 'Provides strategic direction and oversight; establishes risk framework; leads cross-functional risk assessments.']
        ]
      },
      technical: {
        headline: "You drive technical strategy and innovation culture.",
        desc: "Drive product and process strategy for the organization, oversee evaluation and implementation of new products, and drive culture of innovation and continuous improvement. Specific expectations vary by track.",
        indicators: [
          ['Mastery of automation and products', 'Contributes to product and process strategy; identifies key priorities; drives innovation culture.'],
          ['Track-specific capabilities', 'Specific expectations depend on your track. PM: manages complex product portfolios. SWE: leads technical initiatives across multiple teams. Design: expertise in strategic design analysis. CX: advanced HCD proficiency at strategic scale.']
        ]
      },
      people: {
        headline: "You drive collaborative culture and lead recognition development.",
        desc: "Lead the team in driving collaborative inclusive culture encouraging innovation, set strategic direction for learning and development, and lead development of celebration and recognition culture across the organization.",
        indicators: [
          ['Collaboration', 'Drives collaborative culture; manages conflicts effectively; leads cross-functional implementation.'],
          ['Support and mentorship', 'Sets strategic direction for L&D; develops programs; leads personalized planning.'],
          ['Recognition and celebration', 'Leads celebration culture; sets metrics; provides strategic guidance.']
        ]
      }
    },

    'director': {
      label: 'Director',
      client_stakeholder: {
        headline: "You oversee service delivery and build executive-level relationships.",
        desc: "Oversee and manage delivery of high-quality service across multiple areas of the company, build and maintain strong relationships with key clients at executive level, and think strategically and creatively to develop innovative solutions to complex challenges.",
        indicators: [
          ['Quality of service', 'Sets and communicates high standards; monitors performance; provides strategic guidance.'],
          ['Building strong relationships', 'Builds executive-level relationships; provides thought leadership; develops communication plans.'],
          ['Solution-focused', 'Develops innovative departmental solutions; inspires team; develops and executes plans.']
        ]
      },
      making_impact: {
        headline: "You drive culture of continuous improvement and ethical compliance.",
        desc: "Lead cross-functional teams to identify and implement organizational improvements, drive a culture of data-driven decision-making across the organization, and drive a culture of ethical and compliant behavior.",
        indicators: [
          ['Driving process improvements', 'Leads cross-functional teams; establishes continuous improvement culture; drives initiatives.'],
          ['Delivering strategic insights', 'Drives data-driven decision-making; invests in analytics; models best practices.'],
          ['Ensuring compliance and risk management', 'Drives ethical compliance culture; engages senior leadership; collaborates with departments.']
        ]
      },
      technical: {
        headline: "You drive technical excellence and stay current with industry trends.",
        desc: "Drive a culture of technical excellence across the department, invest in resources for ongoing learning, and stay current with industry best practices and new technologies. Specific expectations vary by track.",
        indicators: [
          ['Mastery of automation and products', 'Drives technical excellence; invests in learning resources; stays current with best practices.'],
          ['Track-specific capabilities', 'Specific expectations depend on your track. PM: sets organizational vision for product management. SWE: sets technical standards and guidelines. Design: oversees design strategies across the organization. CX: subject matter expert; sets design standards.']
        ]
      },
      people: {
        headline: "You promote cross-functional collaboration and continuous improvement culture.",
        desc: "Promote cross-functional collaboration within and across departments, drive a culture of continuous improvement investing in mentorship and growth programs, and drive culture of celebration across the department.",
        indicators: [
          ['Collaboration', 'Promotes cross-functional collaboration; identifies opportunities for shared goals.'],
          ['Support and mentorship', 'Drives continuous improvement; invests in mentorship and growth programs.'],
          ['Recognition and celebration', 'Drives celebration culture; establishes metrics; promotes positivity and inclusivity.']
        ]
      }
    },

    'sr-director': {
      label: 'Sr Director',
      client_stakeholder: {
        headline: "You lead service delivery and stakeholder relationships at the organizational level.",
        desc: "Lead and oversee delivery of high-quality service at the organizational level setting ambitious standards, lead development and implementation of comprehensive communication strategies for executive relationships, and think strategically about innovative solutions to company-wide challenges.",
        indicators: [
          ['Quality of service', 'Sets ambitious standards; provides strategic direction to enhance capabilities and reputation.'],
          ['Building strong relationships', 'Leads comprehensive communication strategies; mentors communication professionals.'],
          ['Solution-focused', 'Inspires teams company-wide; develops and executes strategic plans aligned with overall strategy.']
        ]
      },
      making_impact: {
        headline: "You drive organization-wide continuous improvement and compliance excellence.",
        desc: "Drive a culture of continuous improvement across the organization identifying and implementing best practices, drive data-driven decision-making with advanced analytics capabilities, and lead development of comprehensive compliance and risk management programs.",
        indicators: [
          ['Driving process improvements', 'Drives organization-wide improvement; establishes vision; empowers employees to take ownership.'],
          ['Delivering strategic insights', 'Drives data-driven culture; ensures data skills; identifies strategic decision opportunities.'],
          ['Ensuring compliance and risk management', 'Leads comprehensive compliance program; designs policies; fosters ethical culture.']
        ]
      },
      technical: {
        headline: "You drive organization-wide technical excellence and external partnerships.",
        desc: "Drive a culture of technical excellence across the organization, collaborate with departments for cross-functional learning, and establish relationships with external partners and vendors. Specific expectations vary by track.",
        indicators: [
          ['Mastery of automation and products', 'Drives org-wide technical excellence; establishes external partnerships; identifies emerging tech.'],
          ['Track-specific capabilities', 'Specific expectations depend on your track. PM: oversees product strategy company-wide. SWE: sets technical vision for entire organization. Design: oversees design vision and strategy. CX: visionary leader in HCD; influences industry trends.']
        ]
      },
      people: {
        headline: "You drive collaboration, talent management, and recognition at organizational level.",
        desc: "Drive culture of collaboration and shared responsibility across the organization, drive culture of excellence in talent management, and drive culture of celebration and recognition with senior leaders.",
        indicators: [
          ['Collaboration', 'Drives collaboration culture; invests in cross-functional resources; addresses barriers; develops metrics.'],
          ['Support and mentorship', 'Drives excellence in talent management; develops mentorship programs; works on talent attraction and retention.'],
          ['Recognition and celebration', 'Drives celebration culture; works with senior leaders; integrates recognition into strategy.']
        ]
      }
    }
  };

  // ============ SUPPORT FRAMEWORK ============
  // Support uses 4 dimensions like Digital but no sub-tracks. Levels: Specialist → Sr Director.
  const SUPPORT_FRAMEWORK = {
    _schema: 'support',
    _trackable: false,

    'specialist': {
      label: 'Specialist',
      client_stakeholder: {
        headline: "You provide accurate service and continuously develop expertise.",
        desc: "Provide accurate and efficient service to Tamers and stakeholders meeting their needs, communicate effectively with team members and internal stakeholders, and continuously develop expertise to provide value-added services.",
        indicators: [
          ['Quality of service', 'Provides accurate and efficient service; understands company policies, procedures, and industry standards.'],
          ['Building strong relationships', 'Communicates effectively with team members and internal stakeholders; tailors style to audience.'],
          ['Solution-focused', 'Strong desire to learn and develop expertise; proactively seeks opportunities to expand knowledge.']
        ]
      },
      making_impact: {
        headline: "You look for process improvements and report data with quality.",
        desc: "Constantly look for opportunities to improve processes, maintain data and generate standardized reporting with high quality, and have a proficient understanding of relevant regulations and compliance.",
        indicators: [
          ['Driving process improvements', 'Identifies and eliminates redundant tasks; works collaboratively to implement improvements.'],
          ['Delivering strategic insights', 'Maintains data and generates standardized reporting with high quality.'],
          ['Ensuring compliance and risk management', 'Proficient understanding of regulations; identifies risks and escalates appropriately.']
        ]
      },
      technical: {
        headline: "You build mastery of systems, professional standards, and quality of work.",
        desc: "Have proficient understanding of data systems used by the organization, commit to ongoing learning in your area of expertise, and produce high-quality work meeting needs of clients and stakeholders.",
        indicators: [
          ['Mastery of automation and systems', 'Effectively utilizes data systems; troubleshoots and resolves issues related to functionality and integrity.'],
          ['Professional standards and continuous learning', 'Committed to ongoing learning; sufficient knowledge to perform operational tasks.'],
          ['Quality of work', 'Produces high-quality work; identifies issues and takes proactive steps to address them.']
        ]
      },
      people: {
        headline: "You collaborate well, support others, and celebrate team success.",
        desc: "Work effectively as part of a team sharing knowledge, be open to mentoring while taking initiative independently, and celebrate team and individual successes promoting positive culture.",
        indicators: [
          ['Collaboration', 'Communicates and collaborates effectively; shares knowledge; uses tools effectively.'],
          ['Support and mentorship', 'Takes actionable steps to research independently; supports and assists colleagues.'],
          ['Recognition and celebration', 'Celebrates successes; shows appreciation; promotes positive supportive culture.']
        ]
      }
    },

    'sr-specialist': {
      label: 'Sr Specialist',
      client_stakeholder: {
        headline: "You handle complex needs and identify process improvements.",
        desc: "Have deeper understanding of company policies and standards applied to complex needs, communicate clearly with internal stakeholders at all levels anticipating issues, and identify emerging trends to provide value-added services.",
        indicators: [
          ['Quality of service', 'Deep understanding applied to complex Tamer and stakeholder needs.'],
          ['Building strong relationships', 'Communicates with stakeholders at all levels; proactively addresses communication issues.'],
          ['Solution-focused', 'Continuously updates expertise; identifies emerging trends; communicates insights.']
        ]
      },
      making_impact: {
        headline: "You drive process improvements and mentor on methodologies.",
        desc: "Look for improvement opportunities and mentor specialists on methodologies, suggest new reporting processes that improve efficiency, and proactively identify and mitigate compliance risks.",
        indicators: [
          ['Driving process improvements', 'Mentors and trains specialist-level team members on methodologies and tools.'],
          ['Delivering strategic insights', 'Knowledge of data management; suggests new reporting processes for efficiency.'],
          ['Ensuring compliance and risk management', 'Strong understanding of regulations; proactively identifies and mitigates risks.']
        ]
      },
      technical: {
        headline: "You demonstrate deep system knowledge and produce excellent work.",
        desc: "Have deep understanding of organizational data systems and provide expert guidance to juniors, continuously develop your expertise and stay current with industry trends, and consistently produce high-quality work that exceeds expectations.",
        indicators: [
          ['Mastery of automation and systems', 'Deep understanding of data systems; provides expert guidance to juniors; supports user training.'],
          ['Professional standards and continuous learning', 'Proficient expertise; seeks development opportunities; stays current with trends.'],
          ['Quality of work', 'Consistently produces work that exceeds expectations; anticipates and mitigates issues proactively.']
        ]
      },
      people: {
        headline: "You work independently, take ownership, and recognize achievements.",
        desc: "Collaborate effectively with stakeholders, work independently while seeking guidance from seniors, mentor and support juniors, and recognize team achievements actively.",
        indicators: [
          ['Collaboration', 'Builds strong relationships; works independently while seeking guidance.'],
          ['Support and mentorship', 'Collaborates effectively; provides guidance; continues active learning.'],
          ['Recognition and celebration', 'Recognizes and celebrates successes; participates in showing appreciation.']
        ]
      }
    },

    'associate': {
      label: 'Associate',
      client_stakeholder: {
        headline: "You consistently deliver high-quality service and communicate with diverse stakeholders.",
        desc: "Consistently deliver high-quality service handling routine and non-routine tasks, communicate effectively with variety of internal stakeholders, and work with clients and stakeholders to identify challenges and develop recommendations.",
        indicators: [
          ['Quality of service', 'Consistently delivers high-quality service handling routine and non-routine tasks.'],
          ['Building strong relationships', 'Communicates effectively with team members, managers, and cross-functional partners.'],
          ['Solution-focused', 'Works with stakeholders to identify challenges; analyzes data; develops recommendations.']
        ]
      },
      making_impact: {
        headline: "You take ownership of process improvements and analyze complex data.",
        desc: "Take ownership of process improvements with cross-functional teams, interpret complex information and identify trends, and proactively implement risk mitigation strategies.",
        indicators: [
          ['Driving process improvements', 'Takes ownership; works with cross-functional teams; develops and implements policies.'],
          ['Delivering strategic insights', 'Solid understanding of data analysis; interprets complex information; communicates findings.'],
          ['Ensuring compliance and risk management', 'Takes ownership of compliance; proactively implements risk mitigation strategies.']
        ]
      },
      technical: {
        headline: "You navigate systems with ownership of quality and stay current with best practice.",
        desc: "Navigate and troubleshoot data systems taking ownership of quality and accuracy, take ownership of your learning and development, and consistently produce high-quality work with feedback to juniors.",
        indicators: [
          ['Mastery of automation and systems', 'Navigates and troubleshoots systems; develops validation processes; runs system tests.'],
          ['Professional standards and continuous learning', 'Takes ownership of learning; pursues certifications; leverages best practice.'],
          ['Quality of work', 'Consistently produces high-quality work; provides feedback to juniors; stays current with best practices.']
        ]
      },
      people: {
        headline: "You build effective relationships and contribute to team success.",
        desc: "Build effective working relationships, contribute to team success going above and beyond, take initiative to research independently, and celebrate team successes serving as a positive role model.",
        indicators: [
          ['Collaboration', 'Builds effective relationships; contributes to team success; willing to go above and beyond.'],
          ['Support and mentorship', 'Takes actionable steps to research independently; willing to learn.'],
          ['Recognition and celebration', 'Celebrates successes; fosters sense of achievement; serves as positive role model.']
        ]
      }
    },

    'sr-associate': {
      label: 'Sr Associate',
      client_stakeholder: {
        headline: "You handle complex tasks and lead data-driven recommendations.",
        desc: "Consistently deliver high-quality service handling complex tasks with minimal guidance, communicate effectively with broader stakeholders communicating complex ideas clearly, and lead collaborative efforts to provide data-driven recommendations.",
        indicators: [
          ['Quality of service', 'Consistently delivers for complex tasks; resolves issues with minimal guidance.'],
          ['Building strong relationships', 'Communicates with broader stakeholders; communicates complex ideas clearly.'],
          ['Solution-focused', 'Leads collaborative efforts; analyzes data from multiple sources; provides insights.']
        ]
      },
      making_impact: {
        headline: "You lead process improvements and take leadership in compliance.",
        desc: "Lead process improvements with cross-functional teams, advanced understanding of data analysis providing strategic recommendations, mentor junior team members, and take a leadership role in compliance and risk management.",
        indicators: [
          ['Driving process improvements', 'Leads improvements; proactively seeks feedback; mentors juniors.'],
          ['Delivering strategic insights', 'Advanced data analysis understanding; provides strategic recommendations; mentors juniors.'],
          ['Ensuring compliance and risk management', 'Takes leadership role; mentors associates; proactively implements risk mitigation.']
        ]
      },
      technical: {
        headline: "You lead complex troubleshooting and drive innovation.",
        desc: "Lead troubleshooting efforts of complex data systems and ensure accuracy, take ownership of advanced learning and apply to complex problems, and consistently produce high-quality work while mentoring juniors.",
        indicators: [
          ['Mastery of automation and systems', 'Leads troubleshooting of complex systems; collaborates cross-functionally on data quality.'],
          ['Professional standards and continuous learning', 'Stays current with emerging trends; applies knowledge to complex problems.'],
          ['Quality of work', 'Consistently exceeds expectations; mentors juniors; drives improvements and innovation.']
        ]
      },
      people: {
        headline: "You lead team culture and develop juniors actively.",
        desc: "Take leadership role in promoting positive collaborative culture, actively contribute to development of junior team members, and lead recognition culture providing celebration opportunities.",
        indicators: [
          ['Collaboration', 'Builds effective relationships; takes leadership role in positive culture.'],
          ['Support and mentorship', 'Actively contributes to junior development through guidance and mentorship.'],
          ['Recognition and celebration', 'Promotes recognition culture; provides celebration opportunities; leads by example.']
        ]
      }
    },

    'manager': {
      label: 'Manager',
      client_stakeholder: {
        headline: "You lead the team in delivering high-quality service.",
        desc: "Effectively lead the team in providing high-quality service, lead in building strong client relationships through effective communication, and lead in identifying and implementing customized solutions.",
        indicators: [
          ['Quality of service', 'Leads team in high-quality service; identifies improvements; provides coaching.'],
          ['Building strong relationships', 'Develops communication strategies; handles difficult conversations professionally.'],
          ['Solution-focused', 'Leads team in customized solutions for specific needs.']
        ]
      },
      making_impact: {
        headline: "You manage process improvements and oversee compliance frameworks.",
        desc: "Manage process improvement initiatives with clear goals and metrics, lead development of strategic insights, and oversee compliance and risk management approach.",
        indicators: [
          ['Driving process improvements', 'Establishes goals and metrics; leads cross-functional teams; works with stakeholders on solutions.'],
          ['Delivering strategic insights', 'Leads strategic insights; uses data for recommendations; oversees departmental analytics.'],
          ['Ensuring compliance and risk management', 'Establishes protocols; conducts risk assessments; ensures team is trained.']
        ]
      },
      technical: {
        headline: "You lead system optimization, learning, and quality across the team.",
        desc: "Oversee data systems and processes ensuring optimization, oversee learning and development establishing growth metrics, and lead a team in producing high-quality work aligned with objectives.",
        indicators: [
          ['Mastery of automation and systems', 'Oversees systems; ensures optimization; works with stakeholders on new systems.'],
          ['Professional standards and continuous learning', 'Oversees L&D; establishes goals; develops personalized learning plans.'],
          ['Quality of work', 'Leads team in high-quality work; ensures alignment with objectives.']
        ]
      },
      people: {
        headline: "You establish team culture, mentorship, and recognition culture.",
        desc: "Establish a collaborative inclusive team culture fostering open communication, lead the team in providing effective support and mentorship, and establish a culture of celebration and recognition.",
        indicators: [
          ['Collaboration', 'Establishes inclusive culture; resolves conflicts; manages challenges constructively.'],
          ['Support and mentorship', 'Leads team in support and mentorship; oversees personalized learning.'],
          ['Recognition and celebration', 'Establishes celebration culture; sets metrics; recognizes achievements.']
        ]
      }
    },

    'sr-manager': {
      label: 'Sr Manager',
      client_stakeholder: {
        headline: "You strategically lead service delivery and high-level relationships.",
        desc: "Strategically lead and manage your team in providing high-quality service developing strategic plans, develop and implement strategies for high-level stakeholder relationships, and provide innovative solutions for client experience.",
        indicators: [
          ['Quality of service', 'Develops strategic plans; collaborates across teams; analyzes metrics.'],
          ['Building strong relationships', 'Develops high-level relationship strategies; navigates complex environments.'],
          ['Solution-focused', 'Strategically leads team in providing innovative solutions; analyzes metrics for improvement.']
        ]
      },
      making_impact: {
        headline: "You lead large-scale process initiatives and strategic data direction.",
        desc: "Lead and direct large-scale process improvement initiatives, leverage data and insights to inform decision-making, and provide strategic direction for compliance and risk management.",
        indicators: [
          ['Driving process improvements', 'Leads large-scale initiatives; provides strategic guidance.'],
          ['Delivering strategic insights', 'Provides strategic direction; oversees departmental analytics.'],
          ['Ensuring compliance and risk management', 'Provides oversight; establishes risk framework; leads risk assessments.']
        ]
      },
      technical: {
        headline: "You lead organization-wide technical strategy and continuous learning.",
        desc: "Lead development and execution of data systems strategy for the organization, establish a culture of continuous learning and development, and develop strategies to improve team performance.",
        indicators: [
          ['Mastery of automation and systems', 'Leads systems strategy; identifies key priorities; oversees implementation.'],
          ['Professional standards and continuous learning', 'Establishes continuous learning culture; promotes cross-functional opportunities.'],
          ['Quality of work', 'Develops strategies to improve performance; provides guidance and mentorship.']
        ]
      },
      people: {
        headline: "You drive collaborative culture and lead recognition development.",
        desc: "Lead the team in driving collaborative inclusive culture encouraging innovation, set strategic direction for learning and development, and lead development of celebration and recognition culture.",
        indicators: [
          ['Collaboration', 'Drives collaborative culture; manages conflicts; identifies improvements.'],
          ['Support and mentorship', 'Sets strategic direction for L&D; develops programs.'],
          ['Recognition and celebration', 'Leads culture of celebration; sets metrics; provides strategic guidance.']
        ]
      }
    },

    'director': {
      label: 'Director',
      client_stakeholder: {
        headline: "You oversee service delivery and build executive-level relationships.",
        desc: "Oversee delivery of high-quality service across multiple areas, build relationships with key executives, and develop innovative solutions to complex departmental challenges.",
        indicators: [
          ['Quality of service', 'Sets and communicates high standards; provides strategic guidance.'],
          ['Building strong relationships', 'Builds executive-level relationships; provides thought leadership.'],
          ['Solution-focused', 'Develops innovative departmental solutions; develops and executes plans.']
        ]
      },
      making_impact: {
        headline: "You drive culture of continuous improvement and ethical compliance.",
        desc: "Lead cross-functional teams to identify and implement improvements, drive culture of data-driven decision-making, and drive culture of ethical compliant behavior.",
        indicators: [
          ['Driving process improvements', 'Leads cross-functional teams; establishes continuous improvement culture.'],
          ['Delivering strategic insights', 'Drives data-driven decision-making; invests in analytics.'],
          ['Ensuring compliance and risk management', 'Drives ethical compliance culture; integrates compliance into all aspects.']
        ]
      },
      technical: {
        headline: "You drive technical excellence and quality standards across the department.",
        desc: "Drive a culture of technical excellence across the department, establish vision and strategy for learning and development initiatives, and oversee development of quality standards and processes.",
        indicators: [
          ['Mastery of automation and systems', 'Drives technical excellence; invests in resources; stays current with best practices.'],
          ['Professional standards and continuous learning', 'Establishes vision for L&D; develops metrics; evaluates effectiveness.'],
          ['Quality of work', 'Oversees quality standards; leads cross-functional teams; provides guidance.']
        ]
      },
      people: {
        headline: "You promote cross-functional collaboration and continuous improvement culture.",
        desc: "Promote cross-functional collaboration, drive culture of continuous improvement investing in mentorship, and drive culture of celebration across the department.",
        indicators: [
          ['Collaboration', 'Promotes cross-functional collaboration; identifies opportunities for shared goals.'],
          ['Support and mentorship', 'Drives continuous improvement; invests in mentorship and growth programs.'],
          ['Recognition and celebration', 'Drives celebration culture; establishes metrics; promotes positivity.']
        ]
      }
    },

    'sr-director': {
      label: 'Sr Director',
      client_stakeholder: {
        headline: "You lead service delivery at the organizational level.",
        desc: "Lead and oversee delivery of high-quality service at organizational level, lead development of comprehensive communication strategies, and think strategically about innovative solutions to company-wide challenges.",
        indicators: [
          ['Quality of service', 'Sets ambitious organizational standards; provides strategic direction.'],
          ['Building strong relationships', 'Leads communication strategies; mentors communication professionals.'],
          ['Solution-focused', 'Inspires teams company-wide; develops and executes strategic plans.']
        ]
      },
      making_impact: {
        headline: "You drive organization-wide improvement and compliance excellence.",
        desc: "Drive culture of continuous improvement across the organization, drive data-driven decision-making with advanced analytics, and lead development of comprehensive compliance program.",
        indicators: [
          ['Driving process improvements', 'Drives org-wide improvement; establishes vision; empowers ownership.'],
          ['Delivering strategic insights', 'Drives data-driven decision-making; ensures data skills across teams.'],
          ['Ensuring compliance and risk management', 'Leads comprehensive compliance program; designs policies; fosters ethical culture.']
        ]
      },
      technical: {
        headline: "You drive organization-wide excellence in systems, learning, and quality.",
        desc: "Drive a culture of technical excellence across the organization, drive design and implementation of innovative learning programs, and drive a culture of excellence setting the standard for high-quality work.",
        indicators: [
          ['Mastery of automation and systems', 'Drives org-wide technical excellence; establishes external partnerships.'],
          ['Professional standards and continuous learning', 'Drives innovative L&D programs; champions continuous learning culture.'],
          ['Quality of work', 'Drives culture of excellence; develops industry-leading practices; thought leader.']
        ]
      },
      people: {
        headline: "You drive collaboration, talent management, and recognition at organizational level.",
        desc: "Drive culture of collaboration across the organization, drive culture of excellence in talent management, and drive culture of celebration and recognition at organizational level.",
        indicators: [
          ['Collaboration', 'Drives collaboration culture; addresses barriers; develops measurement metrics.'],
          ['Support and mentorship', 'Drives excellence in talent management; develops mentorship programs.'],
          ['Recognition and celebration', 'Drives celebration culture; works with senior leaders; integrates into strategy.']
        ]
      }
    }
  };

  const ALL_FRAMEWORKS = {
    advisory: ADVISORY_FRAMEWORK,
    bd: BD_FRAMEWORK,
    digital: DIGITAL_FRAMEWORK,
    support: SUPPORT_FRAMEWORK
  };


  const DEPT_LABELS = {
    advisory: 'Advisory',
    bd: 'Business Development',
    digital: 'Digital',
    support: 'Support'
  };

  // ============ SCHEMAS ============
  // Each schema defines what the four DOM dimension slots (client/firm/thought/people)
  // represent for that department. The DOM keys stay stable; the labels change.
  const SCHEMAS = {
    advisory: {
      label: 'Advisory',
      dims: {
        client:  { fwKey: 'client',  title: 'Client Leadership',  desc: 'Your ability to manage and develop client and stakeholder relationships in an effective manner — building trust, communicating clearly, and delivering value.', navLabel: 'Client' },
        firm:    { fwKey: 'firm',    title: 'Firm Leadership',    desc: 'Your ability to make an impact, take ownership, and contribute to building TAM — beyond just your client projects.', navLabel: 'Firm' },
        thought: { fwKey: 'thought', title: 'Thought Leadership', desc: 'Your technical mastery — analytical thinking, conceptual problem-solving, continuous learning, and innovation.', navLabel: 'Thought' },
        people:  { fwKey: 'people',  title: 'People Leadership',  desc: 'Your ability to collaborate with, coach, and sponsor other TAMers — building and supporting high-performing teams.', navLabel: 'People' }
      },
      placeholders: {
        client:  { title: 'e.g., "Client relationship on Policy Lab"', context: 'Which project or engagement? Which client?', action: 'What did you actually do?', outcome: 'What was the outcome? (Quantify if possible.)' },
        firm:    { title: 'e.g., "Led XYZ squad initiative"', context: 'Which squad, initiative, or BD effort?', action: 'What did you do specifically?', outcome: 'What was the result? Who benefited?' },
        thought: { title: 'e.g., "Structured analytical approach for ABC project"', context: 'What was the problem? What was hard about it?', action: 'What was your analytical or conceptual contribution?', outcome: 'What did it unlock? (Deliverable, insight, client decision.)' },
        people:  { title: 'e.g., "Coached junior Analyst on XYZ track"', context: 'Who did you work with? What was the context?', action: 'How did you collaborate, coach, or give feedback?', outcome: 'What changed for them or the team?' }
      }
    },
    bd: {
      label: 'Business Development',
      dims: {
        client:  { fwKey: 'client',  title: 'Client / Stakeholder Leadership', desc: 'Cultivating strong client and stakeholder relationships, comprehending their needs, and ensuring effective communication in proposals and engagements.', navLabel: 'Client' },
        firm:    { fwKey: 'firm',    title: 'Firm Leadership', desc: "Taking initiative and actively contributing to TAM's growth and success through leadership and ownership in BD efforts.", navLabel: 'Firm' },
        thought: { fwKey: 'thought', title: 'Thought Leadership', desc: 'Exhibiting mastery in technical skills, commitment to continuous learning, fostering innovation, and actively sharing knowledge across BD work.', navLabel: 'Thought' },
        people:  { fwKey: 'people',  title: 'People Leadership', desc: 'Collaborating effectively with others, providing guidance and nurturing teams to create a collaborative, high-performance work environment.', navLabel: 'People' }
      },
      placeholders: {
        client:  { title: 'e.g., "Led BD outreach for ABC sector"', context: 'Which client or sector? What was the engagement?', action: 'What did you do — outreach, meetings, proposal pitches?', outcome: 'What was the outcome? (Lead conversion, relationship built, etc.)' },
        firm:    { title: 'e.g., "Led XYZ proposal end-to-end"', context: 'Which proposal or BD initiative?', action: 'What was your contribution and ownership?', outcome: 'What was the result? (Win, learnings, internal asset.)' },
        thought: { title: 'e.g., "Built new sector POV / framework"', context: 'What was the problem or opportunity?', action: 'What analytical or conceptual contribution did you make?', outcome: 'How was it used? Who benefited?' },
        people:  { title: 'e.g., "Coached BD analyst on proposal craft"', context: 'Who did you work with?', action: 'How did you collaborate, coach, or give feedback?', outcome: 'What changed for them or the team?' }
      }
    },
    digital: {
      label: 'Digital',
      dims: {
        client:  { fwKey: 'client_stakeholder', title: 'Client & Stakeholder Leadership', desc: 'Quality of service, building strong relationships through effective communication, and being solution-focused for Tamers and stakeholders.', navLabel: 'Client' },
        firm:    { fwKey: 'making_impact',      title: 'Making an Impact', desc: 'Driving process improvements, delivering strategic insights, and ensuring compliance and risk management across the function.', navLabel: 'Impact' },
        thought: { fwKey: 'technical',          title: 'Technical Capabilities', desc: 'Mastery of automation, products, and technical skills relevant to your track (PM, PMO, UI/UX Delivery, Software Engineering, UI/UX Design, or Customer Experience).', navLabel: 'Technical' },
        people:  { fwKey: 'people',             title: 'People Leadership', desc: 'Collaboration, support and mentorship of others, and recognition and celebration of team and individual successes.', navLabel: 'People' }
      },
      placeholders: {
        client:  { title: 'e.g., "Stakeholder onboarding for ABC platform"', context: 'Which Tamers or stakeholders?', action: 'What did you do?', outcome: 'What was the result for them?' },
        firm:    { title: 'e.g., "Process improvement on XYZ workflow"', context: 'Which process? What was inefficient?', action: 'What did you change or optimize?', outcome: 'How much time/quality was saved? Who benefited?' },
        thought: { title: 'e.g., "Built new product feature / system"', context: 'What was the technical challenge?', action: 'What did you build or design?', outcome: 'What did it unlock for users or the team?' },
        people:  { title: 'e.g., "Mentored a junior on technical craft"', context: 'Who did you work with?', action: 'How did you collaborate, coach, or recognize them?', outcome: 'What changed for them or the team?' }
      }
    },
    support: {
      label: 'Support',
      dims: {
        client:  { fwKey: 'client_stakeholder', title: 'Client & Stakeholder Leadership', desc: 'Quality of service, building strong relationships through effective communication, and being solution-focused for Tamers and stakeholders.', navLabel: 'Client' },
        firm:    { fwKey: 'making_impact',      title: 'Making an Impact', desc: 'Driving process improvements, delivering strategic insights, and ensuring compliance and risk management.', navLabel: 'Impact' },
        thought: { fwKey: 'technical',          title: 'Technical Capabilities', desc: 'Mastery of automation and systems, professional standards and continuous learning, and quality of work.', navLabel: 'Technical' },
        people:  { fwKey: 'people',             title: 'People Leadership', desc: 'Collaboration, support and mentorship of others, and recognition and celebration of team and individual successes.', navLabel: 'People' }
      },
      placeholders: {
        client:  { title: 'e.g., "Onboarded a new Tamer cohort"', context: 'Which Tamers or stakeholders?', action: 'What service did you provide?', outcome: 'What was the result?' },
        firm:    { title: 'e.g., "Improved policy / reporting workflow"', context: 'Which process? What was inefficient?', action: 'What did you change?', outcome: 'How much time/quality was saved?' },
        thought: { title: 'e.g., "Mastered a new system / certification"', context: 'What system or capability?', action: 'What did you do to develop expertise?', outcome: 'How is it being applied?' },
        people:  { title: 'e.g., "Mentored a junior or recognized team"', context: 'Who did you work with?', action: 'How did you collaborate or coach?', outcome: 'What changed for them or the team?' }
      }
    }
  };

  // ============ GATE LOGIC ============
  let currentDept = null;
  let currentLevel = null;
  let currentTrack = null;

  // Block scrolling and hide workbook until gate cleared
  document.body.classList.add('gate-active');

  function onDeptChange() {
    const dept = document.getElementById('gateDept').value;
    const levelSel = document.getElementById('gateLevel');
    const trackRow = document.getElementById('gateTrackRow');
    const trackSel = document.getElementById('gateTrack');
    const status = document.getElementById('gateStatus');
    const enterBtn = document.getElementById('gateEnter');
    enterBtn.disabled = true;

    if (!dept) {
      levelSel.disabled = true;
      levelSel.innerHTML = '<option value="">— Pick department first —</option>';
      trackRow.style.display = 'none';
      status.textContent = '';
      return;
    }

    const fw = ALL_FRAMEWORKS[dept];
    if (!fw) {
      levelSel.disabled = true;
      levelSel.innerHTML = '<option value="">— Coming soon —</option>';
      trackRow.style.display = 'none';
      status.className = 'gate-status muted';
      status.textContent = `${DEPT_LABELS[dept]} framework is not yet available.`;
      return;
    }

    // Populate level options (skip metadata keys starting with _)
    const levelKeys = Object.keys(fw).filter(k => !k.startsWith('_'));
    levelSel.disabled = false;
    levelSel.innerHTML = '<option value="">— Select your level —</option>' +
      levelKeys.map(key => `<option value="${key}">${fw[key].label}</option>`).join('');

    // Show / hide track row
    if (fw._trackable && fw._trackOptions) {
      trackRow.style.display = 'grid';
      trackSel.innerHTML = '<option value="">— Select your track —</option>' +
        fw._trackOptions.map(opt => `<option value="${opt.key}">${opt.label}</option>`).join('');
    } else {
      trackRow.style.display = 'none';
      trackSel.innerHTML = '<option value="">— Not applicable —</option>';
    }

    status.className = 'gate-status muted';
    status.textContent = `Now choose your level${fw._trackable ? ' and track' : ''}.`;
  }

  function onLevelChange() {
    updateGateReadyState();
  }

  function onTrackChange() {
    updateGateReadyState();
  }

  function updateGateReadyState() {
    const dept = document.getElementById('gateDept').value;
    const level = document.getElementById('gateLevel').value;
    const track = document.getElementById('gateTrack').value;
    const status = document.getElementById('gateStatus');
    const enterBtn = document.getElementById('gateEnter');

    if (!dept || !level) {
      enterBtn.disabled = true;
      return;
    }

    const fw = ALL_FRAMEWORKS[dept];
    if (fw && fw._trackable && !track) {
      enterBtn.disabled = true;
      status.className = 'gate-status muted';
      status.textContent = 'Please also select your track.';
      return;
    }

    enterBtn.disabled = false;
    const levelLabel = fw[level].label;
    const trackLabel = track && fw._trackOptions ? (fw._trackOptions.find(t => t.key === track) || {}).label : null;
    status.className = 'gate-status';
    status.textContent = `Ready: ${DEPT_LABELS[dept]} · ${levelLabel}` + (trackLabel ? ` · ${trackLabel}` : '');
  }

  function enterWorkbook() {
    const dept = document.getElementById('gateDept').value;
    const level = document.getElementById('gateLevel').value;
    const track = document.getElementById('gateTrack').value;
    if (!dept || !level) return;

    const fw = ALL_FRAMEWORKS[dept];
    if (fw && fw._trackable && !track) return;

    currentDept = dept;
    currentLevel = level;
    currentTrack = track || null;

    applySelection(dept, level, currentTrack);

    document.getElementById('gate').classList.add('hidden');
    document.body.classList.remove('gate-active');
    window.scrollTo(0, 0);
  }

  function reopenGate(e) {
    if (e) e.preventDefault();
    document.getElementById('gate').classList.remove('hidden');
    document.body.classList.add('gate-active');
    if (currentDept) {
      document.getElementById('gateDept').value = currentDept;
      onDeptChange();
      if (currentLevel) {
        document.getElementById('gateLevel').value = currentLevel;
      }
      if (currentTrack) {
        document.getElementById('gateTrack').value = currentTrack;
      }
      updateGateReadyState();
    }
    window.scrollTo(0, 0);
  }

  function applySelection(dept, levelKey, trackKey) {
    const fw = ALL_FRAMEWORKS[dept];
    const schema = SCHEMAS[dept];
    if (!fw || !fw[levelKey] || !schema) return;
    const levelLabel = fw[levelKey].label;
    const deptLabel = DEPT_LABELS[dept];
    const trackLabel = trackKey && fw._trackOptions ? (fw._trackOptions.find(t => t.key === trackKey) || {}).label : null;

    // Update title-side and intro context
    const ctxDeptLevel = document.getElementById('ctxDeptLevel');
    const ctxDeptName = document.getElementById('ctxDeptName');
    if (ctxDeptLevel) ctxDeptLevel.textContent = `${deptLabel} · ${levelLabel} Level` + (trackLabel ? ` · ${trackLabel}` : '');
    if (ctxDeptName) ctxDeptName.textContent = deptLabel;

    document.title = `TAM Self-Assessment — ${deptLabel} · ${levelLabel}`;

    // For each DOM slot (client/firm/thought/people), look up what it represents in this schema
    ['client', 'firm', 'thought', 'people'].forEach(slot => {
      const slotConfig = schema.dims[slot];
      if (!slotConfig) return;

      // Update section title and description
      const titleEl = document.getElementById(`dimTitle-${slot}`);
      const descEl  = document.getElementById(`dimDesc-${slot}`);
      const navLabelEl = document.getElementById(`navLabel-${slot}`);
      const rateLabelEl = document.getElementById(`rateLabel-${slot}`);

      if (titleEl) titleEl.textContent = slotConfig.title;
      if (descEl)  descEl.textContent  = slotConfig.desc;
      if (navLabelEl) navLabelEl.textContent = slotConfig.navLabel;
      if (rateLabelEl) rateLabelEl.textContent = `Your self-rating · ${slotConfig.title}`;

      // Update framework card with content from the framework data
      const card = document.querySelector(`.framework-card[data-fw="${slot}"]`);
      if (!card) return;
      const fwData = fw[levelKey][slotConfig.fwKey];
      if (!fwData) {
        card.innerHTML = `<div class="framework-label">What's expected at ${levelLabel} level</div><div class="framework-desc">No framework details available for this dimension.</div>`;
        return;
      }
      const indicatorsHtml = (fwData.indicators || []).map(([title, desc]) => `<li><strong>${title}</strong>${desc}</li>`).join('');
      card.innerHTML = `
        <div class="framework-label">What's expected at ${levelLabel} level${trackLabel ? ' · ' + trackLabel : ''}</div>
        <div class="framework-title">${fwData.headline}</div>
        <div class="framework-desc">${fwData.desc}</div>
        <details class="framework-indicators">
          <summary>See the detailed behaviors expected</summary>
          <ul class="indicator-list">${indicatorsHtml}</ul>
        </details>
      `;
    });

    // Update placeholders on already-existing entries (and seed entries adopt new placeholders too via dimensions{})
    refreshPlaceholders(schema);

    // Update footer
    const footer = document.querySelector('footer > div:first-child');
    if (footer) footer.textContent = `TAM · Self-Assessment Workbook · ${deptLabel} — ${levelLabel}` + (trackLabel ? ` · ${trackLabel}` : '');
  }

  function refreshPlaceholders(schema) {
    if (!schema) return;
    ['client', 'firm', 'thought', 'people'].forEach(slot => {
      const ph = schema.placeholders[slot];
      if (!ph) return;
      // Update the global dimensions object so newly added entries use these placeholders
      if (typeof dimensions !== 'undefined' && dimensions[slot]) {
        dimensions[slot].placeholder = ph;
      }
      // Update existing entries
      const container = document.getElementById('entries' + slot.charAt(0).toUpperCase() + slot.slice(1));
      if (!container) return;
      container.querySelectorAll('.entry').forEach(entry => {
        const titleInput = entry.querySelector('.entry-title');
        const ctxInput = entry.querySelector('.entry-context');
        const actInput = entry.querySelector('.entry-action');
        const outInput = entry.querySelector('.entry-outcome');
        if (titleInput) titleInput.placeholder = ph.title;
        if (ctxInput) ctxInput.placeholder = ph.context;
        if (actInput) actInput.placeholder = ph.action;
        if (outInput) outInput.placeholder = ph.outcome;
      });
    });
  }

  // ============ ENTRY MANAGEMENT ============
  const dimensions = {
    client: { placeholder: { title: 'e.g., "Client Relationship Management on Policy Lab"', context: 'Which project or engagement? Which client?', action: 'What did you actually do?', outcome: 'What was the outcome? (Quantify if possible.)' } },
    firm: { placeholder: { title: 'e.g., "Led XYZ squad initiative"', context: 'Which squad, initiative, or BD effort?', action: 'What did you do specifically?', outcome: 'What was the result? Who benefited?' } },
    thought: { placeholder: { title: 'e.g., "Structured analytical approach for ABC project"', context: 'What was the problem? What was hard about it?', action: 'What was your analytical or conceptual contribution?', outcome: 'What did it unlock? (Deliverable, insight, client decision.)' } },
    people: { placeholder: { title: 'e.g., "Coached junior Analyst on XYZ track"', context: 'Who did you work with? What was the context?', action: 'How did you collaborate, coach, or give feedback?', outcome: 'What changed for them or the team?' } }
  };

  function addEntry(dim) {
    const container = document.getElementById('entries' + dim.charAt(0).toUpperCase() + dim.slice(1));
    const entries = container.querySelectorAll('.entry');
    const isFirst = entries.length === 0;
    const idx = entries.length + 1;
    const ph = dimensions[dim].placeholder;

    const entry = document.createElement('div');
    entry.className = 'entry' + (isFirst ? ' entry-required' : ' entry-optional');
    const removeBtn = isFirst
      ? '' // first entry can't be removed
      : '<button class="remove-btn" title="Remove" onclick="removeEntry(this)">&times;</button>';
    const tag = isFirst
      ? '<span class="entry-tag entry-tag-required">Required</span>'
      : '<span class="entry-tag entry-tag-optional">Optional</span>';

    entry.innerHTML = `
      <div class="entry-header">
        <div class="entry-header-left">
          <span class="entry-num">Accomplishment ${String(idx).padStart(2, '0')}</span>
          ${tag}
        </div>
        ${removeBtn}
      </div>
      <div class="field">
        <input type="text" class="entry-title" placeholder="${ph.title}" ${isFirst ? 'data-required="true"' : ''} />
      </div>
      <div class="field">
        <label class="field-label">Context</label>
        <textarea class="entry-context" rows="2" placeholder="${ph.context}"></textarea>
      </div>
      <div class="field">
        <label class="field-label">What you did${isFirst ? ' <span class="req">*</span>' : ''}</label>
        <textarea class="entry-action" rows="3" placeholder="${ph.action}" ${isFirst ? 'data-required="true"' : ''}></textarea>
      </div>
      <div class="field">
        <label class="field-label">Outcome & impact</label>
        <textarea class="entry-outcome" rows="2" placeholder="${ph.outcome}"></textarea>
      </div>
    `;
    container.appendChild(entry);
    renumberEntries(container);
    if (!isFirst) entry.querySelector('.entry-title').focus();
  }

  function removeEntry(btn) {
    const entry = btn.closest('.entry');
    const container = entry.parentElement;
    entry.remove();
    renumberEntries(container);
  }

  function renumberEntries(container) {
    const entries = container.querySelectorAll('.entry');
    entries.forEach((entry, i) => {
      const numEl = entry.querySelector('.entry-num');
      if (numEl) numEl.textContent = `Accomplishment ${String(i + 1).padStart(2, '0')}`;
    });
  }

  // Seed one entry per dimension
  ['client', 'firm', 'thought', 'people'].forEach(addEntry);

  // ============ PROGRESS NAV ============
  const navItems = document.querySelectorAll('.prog-item');
  navItems.forEach(item => {
    item.addEventListener('click', (e) => {
      e.preventDefault();
      const target = document.getElementById(item.dataset.section);
      if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
    });
  });

  // Intersection observer to mark active section
  const sections = document.querySelectorAll('section.dimension, section.export');
  const obs = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        navItems.forEach(n => n.classList.remove('active'));
        const active = document.querySelector(`.prog-item[data-section="${entry.target.id}"]`);
        if (active) active.classList.add('active');
      }
    });
  }, { rootMargin: '-30% 0px -60% 0px' });
  sections.forEach(s => obs.observe(s));

  // Mark sections as 'done' based on content
  function markDone() {
    const sectionMap = {
      info: () => !!document.getElementById('empName').value && !!document.getElementById('empAssessor').value,
      client: () => hasContent('client'),
      firm: () => hasContent('firm'),
      thought: () => hasContent('thought'),
      people: () => hasContent('people'),
      values: () => {
        const vals = ['impact', 'truth', 'team', 'adapt', 'grow'];
        return vals.every(v => !!document.querySelector(`input[name="val-${v}"]:checked`));
      }
    };
    Object.keys(sectionMap).forEach(key => {
      const navEl = document.querySelector(`.prog-item[data-section="${key}"]`);
      if (navEl && sectionMap[key]()) navEl.classList.add('done');
      else if (navEl) navEl.classList.remove('done');
    });
  }

  function hasContent(dim) {
    const container = document.getElementById('entries' + dim.charAt(0).toUpperCase() + dim.slice(1));
    const entries = container.querySelectorAll('.entry');
    let hasAny = false;
    entries.forEach(e => {
      const title = e.querySelector('.entry-title').value.trim();
      const action = e.querySelector('.entry-action').value.trim();
      if (title && action) hasAny = true;
    });
    const rating = document.querySelector(`input[name="rate-${dim}"]:checked`);
    return hasAny && !!rating;
  }

  document.addEventListener('input', markDone);
  document.addEventListener('change', markDone);

  // ============ DATA COLLECTION ============
  function collectData() {
    const fw = currentDept ? ALL_FRAMEWORKS[currentDept] : null;
    const schema = currentDept ? SCHEMAS[currentDept] : null;
    const trackLabel = currentTrack && fw && fw._trackOptions ? (fw._trackOptions.find(t => t.key === currentTrack) || {}).label : '';

    const data = {
      department: currentDept || 'advisory',
      departmentLabel: DEPT_LABELS[currentDept] || 'Advisory',
      level: currentLevel || '',
      levelLabel: (fw && currentLevel && fw[currentLevel]) ? fw[currentLevel].label : '',
      track: currentTrack || '',
      trackLabel: trackLabel || '',
      name: document.getElementById('empName').value || '[Name]',
      assessor: document.getElementById('empAssessor').value || '[Assessor]',
      tenure: document.getElementById('empTenure').value || '[Tenure]',
      position: document.getElementById('empPosition').value || '[Position tenure]',
      dimensions: {},
      values: {},
      overall: document.querySelector('input[name="rate-overall"]:checked')?.value || null
    };

    ['client', 'firm', 'thought', 'people'].forEach(slot => {
      const container = document.getElementById('entries' + slot.charAt(0).toUpperCase() + slot.slice(1));
      const entries = [];
      if (container) {
        container.querySelectorAll('.entry').forEach(e => {
          const title = e.querySelector('.entry-title').value.trim();
          const context = e.querySelector('.entry-context').value.trim();
          const action = e.querySelector('.entry-action').value.trim();
          const outcome = e.querySelector('.entry-outcome').value.trim();
          if (title || action) entries.push({ title, context, action, outcome });
        });
      }
      const slotLabel = (schema && schema.dims[slot]) ? schema.dims[slot].title : slot;
      data.dimensions[slot] = {
        slotLabel: slotLabel,
        entries,
        rating: document.querySelector(`input[name="rate-${slot}"]:checked`)?.value || null
      };
    });

    ['impact', 'truth', 'team', 'adapt', 'grow'].forEach(v => {
      data.values[v] = {
        evidence: document.querySelector(`textarea[data-value="${v}-evidence"]`)?.value.trim() || '',
        rating: document.querySelector(`input[name="val-${v}"]:checked`)?.value || null
      };
    });

    return data;
  }

  // ============ PREVIEW ============
  // Static fallback labels (used only when slotLabel is missing)
  const dimLabels = {
    client: 'Client Leadership',
    firm: 'Firm Leadership',
    thought: 'Thought Leadership',
    people: 'People Leadership'
  };
  const valueLabels = {
    impact: 'Own Your Impact',
    truth: 'Respect the Truth',
    team: 'Win as a Team',
    adapt: 'Adapt & Innovate',
    grow: 'Grow with Wellbeing'
  };

  function getSlotLabel(data, slot) {
    return (data.dimensions[slot] && data.dimensions[slot].slotLabel) || dimLabels[slot] || slot;
  }

  function generatePreview() {
    const data = collectData();
    const preview = document.getElementById('previewArea');

    const headerLine = [
      data.departmentLabel,
      data.levelLabel,
      data.trackLabel,
    ].filter(Boolean).join(' · ');

    let html = `
      <h2>${data.name}</h2>
      <div class="sub">Self-Assessment · ${headerLine} · Assessor: ${data.assessor} · Tenure: ${data.tenure} (position: ${data.position})</div>
    `;

    ['client', 'firm', 'thought', 'people'].forEach(slot => {
      html += `<h3>${getSlotLabel(data, slot)}</h3>`;
      if (data.dimensions[slot].rating) {
        html += `<div class="rating-line">Self-rating: <strong>${data.dimensions[slot].rating}</strong></div>`;
      }
      if (data.dimensions[slot].entries.length === 0) {
        html += `<p class="empty">No accomplishments captured for this dimension.</p>`;
      } else {
        data.dimensions[slot].entries.forEach(e => {
          if (e.title) html += `<h4>${e.title}</h4>`;
          const parts = [];
          if (e.context) parts.push(e.context);
          if (e.action) parts.push(e.action);
          if (e.outcome) parts.push(e.outcome);
          if (parts.length) html += `<p>${parts.join(' ')}</p>`;
        });
      }
    });

    html += `<h3>Adhering to Values</h3>`;
    Object.keys(valueLabels).forEach(v => {
      html += `<h4>${valueLabels[v]}</h4>`;
      if (data.values[v].rating) {
        html += `<div class="rating-line">Self-rating: <strong>${data.values[v].rating}</strong></div>`;
      }
      if (data.values[v].evidence) {
        html += `<p>${data.values[v].evidence}</p>`;
      } else {
        html += `<p class="empty">No evidence captured.</p>`;
      }
    });

    if (data.overall) {
      html += `<h3>Overall Self-Rating</h3><div class="rating-line"><strong>${data.overall}</strong></div>`;
    }

    preview.innerHTML = html;
    preview.classList.add('visible');
    preview.scrollIntoView({ behavior: 'smooth', block: 'start' });
  }

  // ============ EXPORT ============
  function generatePlainText() {
    const data = collectData();
    const sep = '═'.repeat(60);
    const headerLine = [data.departmentLabel, data.levelLabel, data.trackLabel].filter(Boolean).join(' · ');
    let txt = `SELF-ASSESSMENT — ${headerLine.toUpperCase()}\n${sep}\n\n`;
    txt += `Name: ${data.name}\nAssessor: ${data.assessor}\nTenure at TAM: ${data.tenure}\nTenure in position: ${data.position}\n\n`;

    ['client', 'firm', 'thought', 'people'].forEach(slot => {
      const label = getSlotLabel(data, slot);
      txt += `\n${sep}\n${label.toUpperCase()}\n${sep}\n`;
      if (data.dimensions[slot].rating) txt += `Self-rating: ${data.dimensions[slot].rating}\n\n`;
      data.dimensions[slot].entries.forEach(e => {
        if (e.title) txt += `\n${e.title}\n`;
        if (e.context) txt += `Context: ${e.context}\n`;
        if (e.action) txt += `What I did: ${e.action}\n`;
        if (e.outcome) txt += `Outcome: ${e.outcome}\n`;
      });
    });

    txt += `\n\n${sep}\nADHERING TO VALUES\n${sep}\n`;
    Object.keys(valueLabels).forEach(v => {
      txt += `\n${valueLabels[v]}\n`;
      if (data.values[v].rating) txt += `Self-rating: ${data.values[v].rating}\n`;
      if (data.values[v].evidence) txt += `${data.values[v].evidence}\n`;
    });

    if (data.overall) {
      txt += `\n\n${sep}\nOVERALL SELF-RATING: ${data.overall}\n${sep}\n`;
    }
    return txt;
  }

  function copyToClipboard() {
    const txt = generatePlainText();
    navigator.clipboard.writeText(txt).then(() => showToast('Copied to clipboard'));
  }

  function downloadHTML() {
    const data = collectData();
    generatePreview();
    const preview = document.getElementById('previewArea').innerHTML;
    const html = `<!DOCTYPE html>
<html><head><meta charset="UTF-8"><title>Self-Assessment — ${data.name}</title>
<style>
body { font-family: Georgia, serif; max-width: 720px; margin: 48px auto; padding: 0 32px; color: #0d0b1f; line-height: 1.6; }
h2 { font-size: 28px; margin-bottom: 4px; }
h3 { font-size: 20px; color: #3730a3; margin-top: 28px; padding-bottom: 4px; border-bottom: 1px solid #ddd; }
h4 { font-size: 15px; margin-top: 16px; margin-bottom: 4px; }
.sub { color: #666; font-size: 13px; margin-bottom: 28px; font-family: monospace; }
.rating-line { background: #f5f1e8; padding: 10px 14px; font-family: monospace; font-size: 12px; margin: 10px 0 18px; border-left: 3px solid #4f46e5; }
.empty { color: #888; font-style: italic; }
</style></head><body>${preview}</body></html>`;
    const blob = new Blob([html], { type: 'text/html' });
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    a.href = url;
    a.download = `self-assessment-${data.name.toLowerCase().replace(/\s+/g, '-') || 'draft'}.html`;
    a.click();
    URL.revokeObjectURL(url);
    showToast('Downloaded');
  }

  function exportPolishedPDF() {
    const data = collectData();

    // Helper to build a value rating tag
    const ratingTag = (rating) => rating ? `<span class="tag">${rating}</span>` : `<span class="tag muted">Not rated</span>`;

    // Build dimension blocks
    const dimensionBlocks = ['client', 'firm', 'thought', 'people'].map(slot => {
      const d = data.dimensions[slot];
      const slotLabel = getSlotLabel(data, slot);
      const entriesHtml = d.entries.length === 0
        ? `<p class="empty">No accomplishments captured.</p>`
        : d.entries.map(e => {
            const body = [e.context, e.action, e.outcome].filter(Boolean).join(' ');
            return `
              <div class="entry">
                ${e.title ? `<div class="entry-title">${escapeHtml(e.title)}</div>` : ''}
                ${body ? `<div class="entry-body">${escapeHtml(body)}</div>` : ''}
              </div>`;
          }).join('');

      return `
        <section class="dim">
          <header class="dim-header">
            <h3>${escapeHtml(slotLabel)}</h3>
            ${ratingTag(d.rating)}
          </header>
          ${entriesHtml}
        </section>`;
    }).join('');

    // Build values block
    const valuesHtml = Object.keys(valueLabels).map(v => {
      const val = data.values[v];
      return `
        <div class="value-item">
          <div class="value-row-head">
            <span class="value-name">${valueLabels[v]}</span>
            ${ratingTag(val.rating)}
          </div>
          ${val.evidence ? `<div class="value-evidence">${escapeHtml(val.evidence)}</div>` : `<div class="empty">No evidence captured.</div>`}
        </div>`;
    }).join('');

    const html = `<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Self-Assessment — ${escapeHtml(data.name)}</title>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,500;0,600;1,400&family=Inter+Tight:wght@400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  @page { size: A4 landscape; margin: 12mm 14mm; }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  html, body {
    font-family: 'Inter Tight', sans-serif;
    color: #0d0b1f;
    font-size: 10.5pt;
    line-height: 1.45;
    background: #fff;
  }

  /* MASTHEAD */
  .masthead {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    padding-bottom: 10px;
    border-bottom: 2px solid #1e1b4b;
    margin-bottom: 14px;
  }
  .brand {
    font-family: 'Fraunces', serif;
    font-weight: 600;
    font-size: 22pt;
    letter-spacing: -0.02em;
    display: flex;
    align-items: center;
    gap: 8px;
    color: #1e1b4b;
  }
  .brand .diamond {
    width: 11px; height: 11px;
    background: #4f46e5;
    transform: rotate(45deg);
    display: inline-block;
  }
  .doc-meta {
    text-align: right;
    font-family: 'JetBrains Mono', monospace;
    font-size: 8pt;
    color: #6b6783;
    letter-spacing: 0.04em;
    line-height: 1.5;
  }
  .doc-meta strong { color: #0d0b1f; font-weight: 500; }

  /* HEADER STRIP */
  .person {
    display: grid;
    grid-template-columns: 1.2fr 1fr 1fr 1fr;
    gap: 18px;
    padding: 10px 0 14px;
    margin-bottom: 14px;
    border-bottom: 1px solid rgba(13,11,31,0.12);
  }
  .person .field-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 7pt;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: #6b6783;
    margin-bottom: 2px;
  }
  .person .field-value {
    font-family: 'Fraunces', serif;
    font-size: 13pt;
    font-weight: 500;
    color: #0d0b1f;
    line-height: 1.15;
  }

  /* OVERALL */
  .overall {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 14px;
    background: linear-gradient(90deg, #1e1b4b 0%, #3730a3 100%);
    color: #f5f1e8;
    margin-bottom: 14px;
    border-radius: 2px;
  }
  .overall-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 8pt;
    text-transform: uppercase;
    letter-spacing: 0.15em;
    color: #fbbf24;
  }
  .overall-value {
    font-family: 'Fraunces', serif;
    font-size: 16pt;
    font-weight: 500;
    color: #fff;
  }

  /* TWO COLUMN BODY */
  .body {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 16px;
    align-items: start;
  }

  .col h2 {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 12pt;
    color: #1e1b4b;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    margin-bottom: 8px;
    padding-bottom: 4px;
    border-bottom: 1px solid #1e1b4b;
  }

  /* DIMENSIONS */
  section.dim {
    margin-bottom: 10px;
    padding: 8px 10px;
    background: #faf7f0;
    border-left: 2px solid #4f46e5;
    page-break-inside: avoid;
  }
  .dim-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 6px;
  }
  .dim-header h3 {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 11pt;
    color: #0d0b1f;
  }

  .tag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 7.5pt;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    padding: 3px 8px;
    background: #1e1b4b;
    color: #fbbf24;
    border-radius: 100px;
    white-space: nowrap;
  }
  .tag.muted {
    background: rgba(13,11,31,0.08);
    color: #6b6783;
  }

  .entry {
    margin-top: 5px;
    padding-top: 5px;
    border-top: 1px dotted rgba(13,11,31,0.15);
  }
  .entry:first-of-type {
    margin-top: 0;
    padding-top: 0;
    border-top: none;
  }
  .entry-title {
    font-weight: 600;
    font-size: 10pt;
    color: #0d0b1f;
    margin-bottom: 1px;
    line-height: 1.25;
  }
  .entry-body {
    font-size: 9.5pt;
    color: #2a2640;
    line-height: 1.4;
  }

  /* VALUES */
  .values {
    display: flex;
    flex-direction: column;
    gap: 6px;
  }
  .value-item {
    padding: 6px 10px;
    background: #faf7f0;
    border-left: 2px solid #f59e0b;
    page-break-inside: avoid;
  }
  .value-row-head {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 3px;
  }
  .value-name {
    font-family: 'Fraunces', serif;
    font-weight: 500;
    font-size: 10.5pt;
    color: #0d0b1f;
  }
  .value-evidence {
    font-size: 9pt;
    color: #2a2640;
    line-height: 1.4;
  }
  .empty {
    font-size: 9pt;
    font-style: italic;
    color: #6b6783;
  }

  /* FOOTER */
  .footer {
    margin-top: 18px;
    padding-top: 10px;
    border-top: 1px solid rgba(13,11,31,0.12);
    display: flex;
    justify-content: space-between;
    font-family: 'JetBrains Mono', monospace;
    font-size: 7.5pt;
    color: #6b6783;
    letter-spacing: 0.04em;
  }

  @media print {
    .body { page-break-inside: avoid; }
  }
</style>
</head>
<body>
  <header class="masthead">
    <div class="brand"><span class="diamond"></span>TAM</div>
    <div class="doc-meta">
      <strong>Self-Assessment · Mid-Year 2026</strong><br>
      ${escapeHtml(data.departmentLabel)} · ${escapeHtml(data.levelLabel)}${data.trackLabel ? ' · ' + escapeHtml(data.trackLabel) : ''}
    </div>
  </header>

  <div class="person">
    <div>
      <div class="field-label">Name</div>
      <div class="field-value">${escapeHtml(data.name)}</div>
    </div>
    <div>
      <div class="field-label">Assessor</div>
      <div class="field-value">${escapeHtml(data.assessor)}</div>
    </div>
    <div>
      <div class="field-label">Tenure at TAM</div>
      <div class="field-value">${escapeHtml(data.tenure)}</div>
    </div>
    <div>
      <div class="field-label">Tenure in Position</div>
      <div class="field-value">${escapeHtml(data.position)}</div>
    </div>
  </div>

  ${data.overall ? `
  <div class="overall">
    <span class="overall-label">Overall Self-Rating</span>
    <span class="overall-value">${escapeHtml(data.overall)}</span>
  </div>` : ''}

  <div class="body">
    <div class="col">
      <h2>Competency Dimensions</h2>
      ${dimensionBlocks}
    </div>
    <div class="col">
      <h2>Adhering to Values</h2>
      <div class="values">${valuesHtml}</div>
    </div>
  </div>

  <div class="footer">
    <span>TAM · Self-Assessment · ${new Date().toLocaleDateString('en-US', { month: 'long', year: 'numeric' })}</span>
    <span>Confidential — for performance review use</span>
  </div>

  <scr` + `ipt>
    window.addEventListener('load', () => {
      setTimeout(() => window.print(), 400);
    });
  <\/script>
</body>
</html>`;

    const w = window.open('', '_blank');
    if (!w) {
      showToast('Pop-up blocked — please allow pop-ups');
      return;
    }
    w.document.write(html);
    w.document.close();
    showToast('Opening polished PDF...');
  }

  // Simple HTML escape helper
  function escapeHtml(str) {
    if (str === null || str === undefined) return '';
    return String(str)
      .replace(/&/g, '&amp;')
      .replace(/</g, '&lt;')
      .replace(/>/g, '&gt;')
      .replace(/"/g, '&quot;')
      .replace(/'/g, '&#039;');
  }

  // ============ STORAGE & SUBMIT ============
  // Use window.storage if available (artifact env), fall back to in-memory
  const STORAGE_KEY = 'tam:self-assessments';
  const memoryStore = { items: [] };

  async function loadAll() {
    try {
      if (window.storage && typeof window.storage.get === 'function') {
        const r = await window.storage.get(STORAGE_KEY);
        return r && r.value ? JSON.parse(r.value) : [];
      }
    } catch (e) {
      // key doesn't exist or other error — fall through
    }
    return memoryStore.items;
  }

  async function saveAll(items) {
    if (window.storage && typeof window.storage.set === 'function') {
      try {
        await window.storage.set(STORAGE_KEY, JSON.stringify(items));
        return true;
      } catch (e) {
        console.error('Storage save failed:', e);
      }
    }
    memoryStore.items = items;
    return true;
  }

  async function submitAssessment() {
    // Validate required first-entry fields across all four dimensions
    const dimNames = { client: 'Client', firm: 'Firm', thought: 'Thought', people: 'People' };
    let firstInvalid = null;
    let invalidDim = null;

    for (const dim of ['client', 'firm', 'thought', 'people']) {
      const container = document.getElementById('entries' + dim.charAt(0).toUpperCase() + dim.slice(1));
      if (!container) continue;
      const firstEntry = container.querySelector('.entry');
      if (!firstEntry) continue;

      // Clear any previous error styling
      firstEntry.classList.remove('entry-error');

      const titleEl = firstEntry.querySelector('.entry-title');
      const actionEl = firstEntry.querySelector('.entry-action');
      const titleVal = titleEl ? titleEl.value.trim() : '';
      const actionVal = actionEl ? actionEl.value.trim() : '';

      if (!titleVal || !actionVal) {
        firstEntry.classList.add('entry-error');
        if (!firstInvalid) {
          firstInvalid = firstEntry;
          invalidDim = dim;
        }
      }
    }

    if (firstInvalid) {
      const dimSchema = (currentDept && SCHEMAS[currentDept]) ? SCHEMAS[currentDept].dims[invalidDim] : null;
      const friendlyName = dimSchema ? dimSchema.title : (dimNames[invalidDim] || invalidDim);
      showToast(`Please fill in the required fields for ${friendlyName}`);
      firstInvalid.scrollIntoView({ behavior: 'smooth', block: 'center' });
      // Focus first empty required field
      const empty = firstInvalid.querySelector('[data-required="true"]');
      if (empty && !empty.value.trim()) setTimeout(() => empty.focus(), 600);
      return;
    }

    const data = collectData();
    if (!data.name || data.name === '[Name]') {
      showToast('Please enter your name first');
      const nameField = document.getElementById('empName');
      if (nameField) {
        nameField.scrollIntoView({ behavior: 'smooth', block: 'center' });
        setTimeout(() => nameField.focus(), 600);
      }
      return;
    }

    const record = {
      id: 'sa_' + Date.now() + '_' + Math.random().toString(36).slice(2, 8),
      savedAt: new Date().toISOString(),
      ...data
    };
    const items = await loadAll();
    items.push(record);
    await saveAll(items);
    showToast('Self-assessment saved');
  }

  // ============ ADMIN ============
  const ADMIN_PASS = 'tam2025'; // change this to whatever you like
  let adminUnlocked = false;

  function openAdmin(e) {
    if (e) e.preventDefault();
    document.getElementById('adminOverlay').classList.add('show');
    if (adminUnlocked) {
      document.getElementById('adminLogin').style.display = 'none';
      document.getElementById('adminBody').style.display = 'flex';
      refreshAdmin();
    } else {
      document.getElementById('adminLogin').style.display = 'block';
      document.getElementById('adminBody').style.display = 'none';
      setTimeout(() => document.getElementById('adminPass').focus(), 100);
    }
  }

  function closeAdmin() {
    document.getElementById('adminOverlay').classList.remove('show');
  }

  function checkAdminPass() {
    const val = document.getElementById('adminPass').value;
    if (val === ADMIN_PASS) {
      adminUnlocked = true;
      document.getElementById('adminPass').value = '';
      document.getElementById('adminLogin').style.display = 'none';
      document.getElementById('adminBody').style.display = 'flex';
      refreshAdmin();
    } else {
      showToast('Incorrect passcode');
      document.getElementById('adminPass').value = '';
    }
  }

  async function refreshAdmin() {
    const items = await loadAll();
    const tbody = document.getElementById('adminTbody');
    const empty = document.getElementById('adminEmpty');
    const stats = document.getElementById('adminStats');
    const table = document.getElementById('adminTable');

    stats.textContent = `${items.length} self-assessment${items.length === 1 ? '' : 's'} saved`;

    if (items.length === 0) {
      table.style.display = 'none';
      empty.style.display = 'block';
      tbody.innerHTML = '';
      return;
    }
    table.style.display = 'table';
    empty.style.display = 'none';

    tbody.innerHTML = items.map(item => {
      const date = new Date(item.savedAt);
      const dateStr = date.toLocaleDateString('en-GB', { day: '2-digit', month: 'short', year: 'numeric' });
      const overall = item.overall || null;
      const ratingHtml = overall
        ? `<span class="rating-pill">${escapeHtml(overall)}</span>`
        : `<span class="rating-pill muted">Not rated</span>`;
      return `
        <tr data-id="${item.id}">
          <td class="name">${escapeHtml(item.name || '—')}</td>
          <td>${escapeHtml(item.departmentLabel || 'Advisory')}</td>
          <td>${escapeHtml(item.levelLabel || '—')}${item.trackLabel ? '<br><span style="font-size:11px;color:var(--ink-muted)">' + escapeHtml(item.trackLabel) + '</span>' : ''}</td>
          <td>${escapeHtml(item.assessor || '—')}</td>
          <td>${ratingHtml}</td>
          <td>${dateStr}</td>
          <td class="t-right">
            <button class="row-action" onclick="viewAssessment('${item.id}')">View</button>
            <button class="row-action danger" onclick="deleteAssessment('${item.id}')">Delete</button>
          </td>
        </tr>`;
    }).join('');
  }

  async function viewAssessment(id) {
    const items = await loadAll();
    const item = items.find(i => i.id === id);
    if (!item) return;
    // Inject this record's data into the preview area in a new window
    const valLabels = { impact: 'Own Your Impact', truth: 'Respect the Truth', team: 'Win as a Team', adapt: 'Adapt & Innovate', grow: 'Grow with Wellbeing' };
    const dimLblsFallback = { client: 'Client Leadership', firm: 'Firm Leadership', thought: 'Thought Leadership', people: 'People Leadership' };

    const headerLine = [item.departmentLabel || 'Advisory', item.levelLabel || '', item.trackLabel || ''].filter(Boolean).join(' · ');
    let body = `<h2>${escapeHtml(item.name)}</h2>
      <div class="sub">Self-Assessment · ${escapeHtml(headerLine)} · Assessor: ${escapeHtml(item.assessor)} · Saved: ${new Date(item.savedAt).toLocaleString()}</div>`;

    ['client','firm','thought','people'].forEach(slot => {
      const d = item.dimensions && item.dimensions[slot];
      if (!d) return;
      const slotLabel = d.slotLabel || dimLblsFallback[slot] || slot;
      body += `<h3>${escapeHtml(slotLabel)}</h3>`;
      if (d.rating) body += `<div class="rating-line">Self-rating: <strong>${escapeHtml(d.rating)}</strong></div>`;
      if (!d.entries || d.entries.length === 0) {
        body += `<p class="empty">No accomplishments captured.</p>`;
      } else {
        d.entries.forEach(e => {
          if (e.title) body += `<h4>${escapeHtml(e.title)}</h4>`;
          const parts = [e.context, e.action, e.outcome].filter(Boolean).map(escapeHtml);
          if (parts.length) body += `<p>${parts.join(' ')}</p>`;
        });
      }
    });

    body += `<h3>Adhering to Values</h3>`;
    Object.keys(valLabels).forEach(v => {
      const val = item.values && item.values[v];
      if (!val) return;
      body += `<h4>${valLabels[v]}</h4>`;
      if (val.rating) body += `<div class="rating-line">Self-rating: <strong>${escapeHtml(val.rating)}</strong></div>`;
      if (val.evidence) body += `<p>${escapeHtml(val.evidence)}</p>`;
    });
    if (item.overall) body += `<h3>Overall Self-Rating</h3><div class="rating-line"><strong>${escapeHtml(item.overall)}</strong></div>`;

    const win = window.open('', '_blank');
    if (!win) { showToast('Pop-up blocked'); return; }
    win.document.write(`<!DOCTYPE html><html><head><meta charset="UTF-8"><title>${escapeHtml(item.name)}</title>
<style>body{font-family:Georgia,serif;max-width:760px;margin:48px auto;padding:0 32px;color:#0d0b1f;line-height:1.6}h2{font-size:28px;margin-bottom:4px}h3{font-size:20px;color:#3730a3;margin-top:28px;padding-bottom:4px;border-bottom:1px solid #ddd}h4{font-size:15px;margin-top:16px;margin-bottom:4px}.sub{color:#666;font-size:13px;margin-bottom:28px;font-family:monospace}.rating-line{background:#f5f1e8;padding:10px 14px;font-family:monospace;font-size:12px;margin:10px 0 18px;border-left:3px solid #4f46e5}.empty{color:#888;font-style:italic}</style>
</head><body>${body}</body></html>`);
    win.document.close();
  }

  async function deleteAssessment(id) {
    if (!confirm('Delete this self-assessment? This cannot be undone.')) return;
    const items = await loadAll();
    const filtered = items.filter(i => i.id !== id);
    await saveAll(filtered);
    showToast('Deleted');
    refreshAdmin();
  }

  async function deleteAllAssessments() {
    if (!confirm('Delete ALL saved self-assessments? This cannot be undone.')) return;
    if (!confirm('Are you absolutely sure? This will remove every record.')) return;
    await saveAll([]);
    showToast('All assessments deleted');
    refreshAdmin();
  }

  // ============ EXCEL/CSV EXPORT ============
  async function exportAllExcel() {
    const items = await loadAll();
    if (items.length === 0) {
      showToast('Nothing to export');
      return;
    }

    // Static fallback labels (only used when slotLabel missing on older records)
    const slotFallbacks = {
      client: 'Client Leadership',
      firm: 'Firm Leadership',
      thought: 'Thought Leadership',
      people: 'People Leadership'
    };

    // Schema-friendly header: generic Dim 1..4 + per-record slot label so the export works
    // cleanly across departments with different dimension names (Advisory/BD vs Digital/Support)
    const headers = [
      'Name', 'Department', 'Level', 'Track', 'Assessor', 'Tenure at TAM', 'Tenure in Position', 'Saved At',
      'Overall Rating',
      'Dim 1 — Label', 'Dim 1 — Rating', 'Dim 1 — Accomplishments',
      'Dim 2 — Label', 'Dim 2 — Rating', 'Dim 2 — Accomplishments',
      'Dim 3 — Label', 'Dim 3 — Rating', 'Dim 3 — Accomplishments',
      'Dim 4 — Label', 'Dim 4 — Rating', 'Dim 4 — Accomplishments',
      'Own Your Impact Rating', 'Own Your Impact Evidence',
      'Respect the Truth Rating', 'Respect the Truth Evidence',
      'Win as a Team Rating', 'Win as a Team Evidence',
      'Adapt & Innovate Rating', 'Adapt & Innovate Evidence',
      'Grow with Wellbeing Rating', 'Grow with Wellbeing Evidence'
    ];

    const formatEntries = (entries) => {
      if (!entries || entries.length === 0) return '';
      return entries.map((e, i) => {
        const lines = [];
        if (e.title) lines.push(`[${i + 1}] ${e.title}`);
        if (e.context) lines.push(`Context: ${e.context}`);
        if (e.action) lines.push(`Did: ${e.action}`);
        if (e.outcome) lines.push(`Outcome: ${e.outcome}`);
        return lines.join('\n');
      }).join('\n\n');
    };

    const slotData = (dims, slot) => {
      const d = (dims && dims[slot]) || {};
      const label = d.slotLabel || slotFallbacks[slot] || slot;
      return [label, d.rating || '', formatEntries(d.entries)];
    };

    const rows = items.map(item => {
      const dims = item.dimensions || {};
      const vals = item.values || {};
      return [
        item.name || '',
        item.departmentLabel || 'Advisory',
        item.levelLabel || '',
        item.trackLabel || '',
        item.assessor || '',
        item.tenure || '',
        item.position || '',
        new Date(item.savedAt).toLocaleString(),
        item.overall || '',
        ...slotData(dims, 'client'),
        ...slotData(dims, 'firm'),
        ...slotData(dims, 'thought'),
        ...slotData(dims, 'people'),
        (vals.impact && vals.impact.rating) || '',
        (vals.impact && vals.impact.evidence) || '',
        (vals.truth && vals.truth.rating) || '',
        (vals.truth && vals.truth.evidence) || '',
        (vals.team && vals.team.rating) || '',
        (vals.team && vals.team.evidence) || '',
        (vals.adapt && vals.adapt.rating) || '',
        (vals.adapt && vals.adapt.evidence) || '',
        (vals.grow && vals.grow.rating) || '',
        (vals.grow && vals.grow.evidence) || ''
      ];
    });

    // CSV escape: wrap fields in quotes, double up internal quotes
    const csvEscape = (v) => {
      const s = String(v == null ? '' : v);
      return '"' + s.replace(/"/g, '""') + '"';
    };
    const csvLines = [headers.map(csvEscape).join(',')];
    rows.forEach(row => csvLines.push(row.map(csvEscape).join(',')));
    // BOM for Excel UTF-8 compatibility
    const csv = '\uFEFF' + csvLines.join('\r\n');

    const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
    const url = URL.createObjectURL(blob);
    const a = document.createElement('a');
    const stamp = new Date().toISOString().slice(0, 10);
    a.href = url;
    a.download = `tam-self-assessments-${stamp}.csv`;
    a.click();
    URL.revokeObjectURL(url);
    showToast(`Exported ${items.length} record${items.length === 1 ? '' : 's'}`);
  }

  // Close admin on Escape
  document.addEventListener('keydown', (e) => {
    if (e.key === 'Escape') {
      const overlay = document.getElementById('adminOverlay');
      if (overlay && overlay.classList.contains('show')) closeAdmin();
    }
  });

  function showToast(msg) {
    const t = document.getElementById('toast');
    t.textContent = msg;
    t.classList.add('show');
    setTimeout(() => t.classList.remove('show'), 2200);
  }
</script>

</body>
</html>
