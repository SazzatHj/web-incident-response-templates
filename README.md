# Web Incident Response Templates

A collection of professional, lightweight, and modern HTML/CSS templates designed for rapid deployment during web incidents, security operations, and server maintenance.

These static templates are built using clean, vanilla code with embedded styles and optimized SVGs, making them plug-and-play for web servers (Nginx, Apache) or reverse proxies (Cloudflare, Cloudfront) without requiring heavy dependencies or external libraries.

---

## Repository Structure

The project follows a standard, web-server-friendly directory layout. Each incident category contains a self-contained `index.html` file for zero-configuration routing:

```text
web-incident-response-templates/
├── under-attack/
│   └── index.html          # Active DDoS mitigation & security screening screen
├── under-construction/
│   └── index.html          # Development progress tracker with live engine animation
├── under-maintenance/
│   └── index.html          # Scheduled optimization & routine systems tuning screen
└── README.md
```

## Included Templates
### 1. [Under Attack](./under-attack)
- **Use Case:** Active DDoS attacks, brute-force mitigation, or mandatory traffic scrubbing periods.

- **Design & Feel:** High-alert dark mode layout featuring an automated threat-filtering indicator.

- **Animations:** Pulse radar glow, infinite security scanning ring, and digital connection-checking dots.

### 2. [Under Construction](./under-construction)
- **Use Case:** Deploying new web architecture, security frameworks, or launching a brand-new backend platform.

- **Design & Feel:** Blueprint engineering theme with an automated amber deployment timeline.

- **Animations:** Continuous live mechanical gear rotation, pulsing laser status indicator, and moving progress bar stripes tracking a 75% build status.

### 3. [Under Maintenance](./under-maintenance)
- **Use Case:** Routine updates, database optimizations, or scheduled patch management.

- **Design & Feel:** Slate dark-themed minimal layout conveying a secure, professional, and trustworthy offline status.

- **Animations:** Subtle processing pulse on a mechanical tuning icon to indicate background system operations.

## Features
- **Zero Dependencies:** Pure HTML/CSS with inline styling—no external assets, fonts, or heavy JS libraries needed.

- **Production Ready:** Pre-configured as index.html inside directory structures to leverage default web server directory indexing.

- **Fully Responsive:** Fluid, mobile-first design ensuring crisp presentation across mobile, tablet, and desktop viewports.

- **Privacy & Performance:** No third-party tracking scripts, CDNs, or external requests—respects absolute privacy and loads instantly under heavy loads.

## Deployment Guide
**To deploy any of these templates during an incident:**

- Copy the contents of the required directory (e.g., under-maintenance/index.html).

- Place it into your web server's root directory or configure your Reverse Proxy / CDN (like Cloudflare Custom Pages) to serve the file on specific HTTP status codes (503 for Maintenance, 403/429 for Security Filtering).

- Update the Support Team mailto link at the bottom of the templates to match your domain infrastructure.

## Disclaimer
These templates are intended to assist web administrators and security professionals in maintaining transparency and security compliance during downtime. Ensure proper HTTP status codes are returned by your server (503 Service Unavailable for maintenance) to maintain SEO rankings.
