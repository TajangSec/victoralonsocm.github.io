---
layout: page
icon: fas fa-wrench
order: 2
---

<style>
.tools-section {
  margin-bottom: 2.5rem;
}
.tools-section-title {
  font-family: 'Share Tech Mono', monospace;
  color: var(--retro-green) !important;
  font-size: 1.1rem;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  border-bottom: 1px solid var(--retro-border);
  padding-bottom: 0.4rem;
  margin-bottom: 1.2rem;
}
.tool-card {
  display: block;
  background: var(--retro-bg-surface);
  border: 1px solid var(--retro-border);
  border-radius: 4px;
  padding: 1rem 1.25rem;
  margin-bottom: 0.75rem;
  transition: border-color 0.2s, box-shadow 0.2s;
  text-decoration: none !important;
}
.tool-card:hover {
  border-color: var(--retro-green-dim) !important;
  box-shadow: 0 0 12px var(--retro-green-glow) !important;
  text-shadow: none !important;
}
.tool-card-title {
  font-family: 'Share Tech Mono', monospace;
  color: var(--retro-cyan) !important;
  font-size: 1rem;
  font-weight: 500;
  margin-bottom: 0.3rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}
.tool-card:hover .tool-card-title {
  color: var(--retro-green) !important;
}
.tool-card-desc {
  color: var(--retro-text-dim) !important;
  font-size: 0.85rem;
  line-height: 1.5;
  margin: 0;
}
.tool-card-badge {
  display: inline-block;
  font-size: 0.65rem;
  padding: 0.1rem 0.4rem;
  border-radius: 2px;
  font-family: 'JetBrains Mono', monospace;
  letter-spacing: 0.05em;
  text-transform: uppercase;
  vertical-align: middle;
}
.badge-soon {
  color: var(--retro-amber);
  border: 1px solid var(--retro-amber);
}
.badge-live {
  color: var(--retro-green);
  border: 1px solid var(--retro-green);
}
.badge-github {
  color: var(--retro-purple);
  border: 1px solid var(--retro-purple);
}
</style>

<div class="tools-section">
  <h3 class="tools-section-title">
    <i class="fas fa-terminal fa-fw" style="color: var(--retro-green); margin-right: 0.4rem;"></i>
    Site Tools
  </h3>

  <a href="/site-tools/text-encoder/" class="tool-card">
    <div class="tool-card-title">
      Text Encoding Tools
      <span class="tool-card-badge badge-live">Live</span>
    </div>
    <p class="tool-card-desc">Encode and decode strings in various formats &mdash; Base64, hex, URL encoding, Unicode, ROT13, and more. All client-side, nothing leaves your browser.</p>
  </a>

  <div class="tool-card">
    <div class="tool-card-title">
      PowerShell Reverse Shell Generator & Obfuscator
      <span class="tool-card-badge badge-soon">Coming Soon</span>
    </div>
    <p class="tool-card-desc">Generate reverse shell payloads in PowerShell with built-in obfuscation techniques to bypass common detection mechanisms.</p>
  </div>

  <div class="tool-card">
    <div class="tool-card-title">
      System DLL Proxy Generator
      <span class="tool-card-badge badge-soon">Coming Soon</span>
    </div>
    <p class="tool-card-desc">Generate DLL proxy source code for DLL side-loading and hijacking. Select a target system DLL and get a ready-to-compile proxy with your payload injection point.</p>
  </div>
</div>

<div class="tools-section">
  <h3 class="tools-section-title">
    <i class="fab fa-github fa-fw" style="color: var(--retro-purple); margin-right: 0.4rem;"></i>
    GitHub Projects
  </h3>

  <a href="https://github.com/VictorAlonsoCM/VulnDrivers-n-LOLDrivers-POCs" class="tool-card" target="_blank" rel="noopener noreferrer">
    <div class="tool-card-title">
      <i class="fab fa-github fa-fw" style="color: var(--retro-purple);"></i>
      VulnDrivers-n-LOLDrivers-POCs
      <span class="tool-card-badge badge-github">GitHub</span>
      <i class="fas fa-arrow-up-right-from-square fa-fw" style="color: var(--retro-text-dim); font-size: 0.7rem; margin-left: auto;"></i>
    </div>
    <p class="tool-card-desc">Proof-of-concept code for exploiting vulnerable and Living-off-the-Land drivers (BYOVD). Research collection covering kernel-level primitives and EDR evasion techniques.</p>
  </a>
</div>
