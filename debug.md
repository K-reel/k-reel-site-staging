---
layout: page
title: Debug Info
permalink: /debug/
---

## Site Configuration

**Build ID:** `{{ site.kb_build_id }}`

**Site URL:** `{{ site.url }}`

**Base URL:** `{{ site.baseurl }}`

**Theme Mode:** `{{ site.theme_mode }}`

**PWA Enabled:** `{{ site.pwa.enabled }}`

**PWA Cache Enabled:** `{{ site.pwa.cache.enabled }}`

## CSS Verification

<div class="debug-css-test" style="border: 3px solid #1e40af; background-color: #eff6ff; padding: 1rem; margin: 1rem 0; border-radius: 0.5rem;">
  <strong>CSS Test Block:</strong> If you see a blue border and light blue background, the stylesheet loaded successfully.
</div>

## Page Generation

Generated at build time. If this page renders correctly with all values populated, the site is building and deploying properly.
