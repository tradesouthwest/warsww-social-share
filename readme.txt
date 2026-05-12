
# WarsWW Social Share

High-performance social sharing module with integrated WarsWW Intelligence telemetry.

Version
1.0.0

Author
WarsWW Lead Developer

License
GPL-3.0-or-later

Text Domain
warsww-social-share

## Description

The WarsWW Social Share plugin is meticulously crafted with modern PHP standards, emphasizing isolation, security, and performance. Its zero-latency asset strategy and atomic meta key usage ensure a seamless experience without bloat.

A robust, zero-dependency social sharing solution designed for performance and insightful analytics.

## Features

Hard Coded by Larry Judd @tradesouthwestgmailcom

Core Functionality
Plugin Initialization
Hooks into `plugins_loaded`, enqueues assets, appends share buttons via `the_content`, and handles AJAX requests.

Core Setup
Zero-Dependency Assets
Inline CSS/JS injection for `is_singular()` views, ensuring minimal impact and no external file loading.

Performance
Telemetry Logging
Asynchronous AJAX `fetch` requests log share events, updating post meta for analytics.

Intelligence
Modern Networks
Supports sharing on Threads, BlueSky, LinkedIn, Facebook, and X (Twitter) with custom intent URLs.

Connectivity
Security Hardened
Employs nonces, capability checks, and sanitization functions for robust protection.

Safety
Intelligence Dashboard
Provides an admin interface under Settings to overview telemetry tie-ins and potential analytics.

<!--notes
The "WarsWW" Social Meta Checklist
The Big Four (Required):

og:title: Keep it under 60 characters to avoid truncation on mobile.

og:type: Set this to article for your daily briefs.

og:image: The gold standard is 1200 x 630 pixels. If it's smaller than 600x315, Facebook might just show a tiny thumbnail instead of a full-width card.

og:url: Always use the canonical URL (no tracking parameters like ?fbclid=...).

The "Secret Sauce" for OSINT:

og:description: Aim for 120–160 characters. Pro-tip: If your title is long enough to wrap to two lines, Facebook often hides the description entirely, so keep the title punchy.

og:image:alt: Crucial for EEAT. Describe the map or infographic for screen readers (e.g., "Tactical map of the GIUK Gap and new Greenland base proposals").

Validation Tool: Once you deploy, run a link through the Facebook Sharing Debugger. It’s the only way to force a "Re-scrape" if you update an image after a post is already live. -->
<svg viewBox="0 0 512 512"><path d="M407 177.6c7.6-24 13.4-47.2 13.4-67.4 0-71.2-60.3-110.2-110.3-110.2-31.1 0-57 18.9-72.1 47.1-15.1-28.2-41-47.1-72.1-47.1-50 0-110.3 39-110.3 110.2 0 20.2 5.8 43.4 13.4 67.4C95.4 259 146.4 340 256 340c109.6 0 160.6-81 186.9-162.4z"/></svg>
<svg viewBox="0 0 24 24"><path d="M12 24c-6.627 0-12-5.373-12-12s5.373-12 12-12 12 5.373 12 12-5.373 12-12 12zm0-2c5.523 0 10-4.477 10-10s-4.477-10-10-10-10 4.477-10 10 4.477 10 10 10z"/></svg>
