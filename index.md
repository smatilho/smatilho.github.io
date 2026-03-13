---
layout: default
title: Home
---

<section id="hero" class="hero">
  <div class="container">
    <h1>Steven Morais Atilho</h1>
    <div class="typewriter">
      <span id="typewriter-text"></span><span class="cursor">|</span>
    </div>
    <div class="scroll-indicator">scroll</div>
  </div>
</section>

<section id="about" class="about">
  <div class="container">
    <div class="section-title">
      <span class="brace">{</span>
      <h2>About</h2>
      <span class="brace">}</span>
    </div>
    <div class="about-content">
      <p>By day, I engineer enterprise security solutions, architecting systems that keep tens of thousands of endpoints secure.</p>
      <p>By night (and weekends), I'm building things. Whether it's tinkering with home automation or diving into a new technical rabbit hole, I'm always working on something.</p>
    </div>
  </div>
</section>

<section id="projects" class="projects">
  <div class="container">
    <div class="section-title">
      <span class="brace">{</span>
      <h2>Projects</h2>
      <span class="brace">}</span>
    </div>
    <div class="projects-grid">
      <div class="project-card">
        <h3><span class="icon">//</span> GitHub Projects</h3>
        <p>Open source contributions, personal experiments, and various coding projects. From utilities to full applications.</p>
        <div class="project-tags">
          <span class="project-tag">Open Source</span>
          <span class="project-tag">Code</span>
        </div>
        <a href="https://github.com/smatilho" target="_blank" class="project-link">github.com/smatilho &rarr;</a>
      </div>
      <div class="project-card">
        <h3><span class="icon">//</span> Club OS</h3>
        <p>Club OS is an open-source, multi-tenant blueprint for modern club platforms across public content, member workflows (dues, reservations, and account management), and admin operations. It emerged from modernization work I have been doing with Sterling Ski Club, where an aging stack highlighted the need for a more maintainable, lower-cost architecture with less institutional-knowledge risk.</p>
        <div class="project-tags">
          <span class="project-tag">Architecture-First</span>
          <span class="project-tag">Multi-Tenant</span>
          <span class="project-tag">Maintainability</span>
        </div>
        <a href="https://github.com/smatilho/club-os" target="_blank" class="project-link">github.com/smatilho/club-os &rarr;</a>
      </div>
      <div class="project-card">
        <h3><span class="icon">//</span> Labsight</h3>
        <p>Labsight is an AI-powered operations assistant for self-hosted infrastructure, combining document retrieval with metrics analysis so questions can be answered from real runbooks, configs, and telemetry. I built it as an architecture-focused platform that prioritizes practical observability, traceable responses, and maintainable infrastructure-as-code deployment.</p>
        <div class="project-tags">
          <span class="project-tag">AIOps</span>
          <span class="project-tag">RAG + Agents</span>
          <span class="project-tag">Terraform</span>
        </div>
        <a href="https://github.com/smatilho/labsight" target="_blank" class="project-link">github.com/smatilho/labsight &rarr;</a>
      </div>
      <div class="project-card">
        <h3><span class="icon">//</span> More Coming Soon</h3>
        <p>Always building something new. Check back for updates on current and upcoming projects.</p>
        <div class="project-tags">
          <span class="project-tag">In Progress</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="writeups" class="writeups">
  <div class="container">
    <div class="section-title">
      <span class="brace">{</span>
      <h2>Writeups</h2>
      <span class="brace">}</span>
    </div>
    <div class="writeups-grid">
      <a href="/writeups/second-node-optiplex-5060-homelab/" class="writeup-card">
        <div class="writeup-date">March 12, 2026</div>
        <h3>Adding a Second Node: OptiPlex 5060 Joins the Homelab</h3>
        <p>Expanding from a single Wyse 5070 to a two-node homelab with a Dell OptiPlex 5060 — Proxmox install, integration with existing monitoring, dashboard, and reverse proxy infrastructure.</p>
        <div class="writeup-tags">
          <span class="writeup-tag">Homelab</span>
          <span class="writeup-tag">Proxmox</span>
          <span class="writeup-tag">Multi-Node</span>
          <span class="writeup-tag">OptiPlex 5060</span>
        </div>
      </a>
      <a href="/writeups/monitoring-notifications-dashboard-homelab/" class="writeup-card">
        <div class="writeup-date">February 9, 2026</div>
        <h3>Monitoring, Notifications, and a Dashboard: Completing the Homelab Stack</h3>
        <p>Setting up Uptime Kuma, ntfy, and Homepage on a Proxmox homelab — service monitoring, push notifications, and a single dashboard for everything.</p>
        <div class="writeup-tags">
          <span class="writeup-tag">Monitoring</span>
          <span class="writeup-tag">Uptime Kuma</span>
          <span class="writeup-tag">ntfy</span>
          <span class="writeup-tag">Homepage</span>
        </div>
      </a>
      <a href="/writeups/reverse-proxy-tls-homelab/" class="writeup-card">
        <div class="writeup-date">February 8, 2025</div>
        <h3>Adding HTTPS to Everything: Nginx Proxy Manager on Proxmox</h3>
        <p>Setting up Nginx Proxy Manager with real Let's Encrypt certificates via Cloudflare DNS-01 challenges — no ports exposed to the internet.</p>
        <div class="writeup-tags">
          <span class="writeup-tag">Reverse Proxy</span>
          <span class="writeup-tag">TLS</span>
          <span class="writeup-tag">Cloudflare</span>
          <span class="writeup-tag">Proxmox</span>
        </div>
      </a>
      <a href="/writeups/wyse-5070-homelab-proxmox-adguard-tailscale/" class="writeup-card">
        <div class="writeup-date">February 5, 2025</div>
        <h3>Building a Homelab on a $40 Dell Wyse 5070</h3>
        <p>A complete walkthrough from a stock Windows thin client to a working homelab with Proxmox, AdGuard Home, Unbound, and Tailscale.</p>
        <div class="writeup-tags">
          <span class="writeup-tag">Homelab</span>
          <span class="writeup-tag">Proxmox</span>
          <span class="writeup-tag">AdGuard Home</span>
          <span class="writeup-tag">Tailscale</span>
        </div>
      </a>
      <a href="/writeups/openclaw-oracle-vps-tailscale/" class="writeup-card">
        <div class="writeup-date">January 30, 2025</div>
        <h3>Running OpenClaw on a Free Oracle VPS with Tailscale</h3>
        <p>A complete guide to setting up OpenClaw Gateway on Oracle Cloud's free ARM tier, secured with Tailscale and zero public ports exposed.</p>
        <div class="writeup-tags">
          <span class="writeup-tag">Oracle Cloud</span>
          <span class="writeup-tag">Tailscale</span>
          <span class="writeup-tag">Security</span>
        </div>
      </a>
    </div>
  </div>
</section>

<section id="photography" class="photography">
  <div class="container">
    <div class="section-title">
      <span class="brace">{</span>
      <h2>Photography</h2>
      <span class="brace">}</span>
    </div>
    <div class="photography-intro">
      <p>A growing gallery from travels, projects, and everyday moments.</p>
    </div>
    <div class="photo-grid">
      <figure class="photo-card">
        <a href="/assets/images/photos/full/harley-fort-trumbull.jpeg" target="_blank" rel="noopener" class="photo-link">
          <img src="/assets/images/photos/harley-fort-trumbull.webp" alt="A Harley-Davidson motorcycle near Fort Trumbull." loading="lazy">
        </a>
        <figcaption>Harley Sportster 1200 at Fort Trumbull Beach</figcaption>
      </figure>
      <figure class="photo-card">
        <a href="/assets/images/photos/full/madeira-botanical-gardens.jpeg" target="_blank" rel="noopener" class="photo-link">
          <img src="/assets/images/photos/madeira-botanical-gardens.webp" alt="View from Madeira Botanical Gardens." loading="lazy">
        </a>
        <figcaption>Madeira Botanical Gardens</figcaption>
      </figure>
      <figure class="photo-card">
        <a href="/assets/images/photos/full/porto-moniz.jpeg" target="_blank" rel="noopener" class="photo-link">
          <img src="/assets/images/photos/porto-moniz.webp" alt="Coastline and volcanic pools at Porto Moniz, Madeira." loading="lazy">
        </a>
        <figcaption>Porto Moniz, Madeira</figcaption>
      </figure>
      <figure class="photo-card">
        <a href="/assets/images/photos/full/praia-formosa.jpeg" target="_blank" rel="noopener" class="photo-link">
          <img src="/assets/images/photos/praia-formosa.webp" alt="Waves and shoreline at Praia Formosa beach." loading="lazy">
        </a>
        <figcaption>Praia Formosa</figcaption>
      </figure>
    </div>
  </div>
</section>

<section id="contact" class="contact">
  <div class="container">
    <div class="section-title">
      <span class="brace">{</span>
      <h2>Contact</h2>
      <span class="brace">}</span>
    </div>
    <div class="contact-links">
      <a href="mailto:steven@atilho.com" class="contact-link">
        <span class="icon">@</span>
        steven@atilho.com
      </a>
      <a href="https://linkedin.com/in/stevenati" target="_blank" class="contact-link">
        <span class="icon">in</span>
        linkedin.com/in/stevenati
      </a>
      <a href="https://github.com/smatilho" target="_blank" class="contact-link">
        <span class="icon">&lt;/&gt;</span>
        github.com/smatilho
      </a>
    </div>
  </div>
</section>
