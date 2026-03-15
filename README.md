# ABLE Teambuildings and Events Static Site (`ateamz.able.bg`)

This GitHub repository hosts a static HTML version of the ABLE Teambuildings and Events website. ABLE's Startup Navigator project has been inactive since at least 2020. The ateamz.net website was a WordPress installation, which as of March 14, 2026, was version 4.9 and last updated in before 2020. In March 2026, Stoil Stoilov exported a static HTML version of the last working WordPress installation using the WordPress plugin Simply Static, and uploaded it to be hosted forever for free on GitHub Pages. The original ateamz.net domain has been let go. This archival version of the Startup Navigator website is hosted on [ateamz.able.bg](https://ateamz.able.bg). 

> [!CAUTION]
> **MAINTENANCE STATUS: DECOMMISSIONED & ARCHIVED** > The original WordPress installation (v4.9) used to manage this site has been decommissioned and archived. This repository now serves as the **primary and final source** of the website content.

---

## 🏗 Architecture Overview

This site follows a **Static-Only** architecture:

* **Original CMS:** WordPress (v4.9) — *Now Offline/Archived*.
* **Static Converter:** [Simply Static](https://wordpress.org/plugins/simply-static/).
* **Hosting:** [GitHub Pages](https://pages.github.com/).
* **DNS & Domain:** Cloudflare (pointing to GitHub Pages via A/CNAME records).

---

## 🛠 How to Update the Website

Since the WordPress backend is no longer live, updates cannot be made through a visual editor.

### For Minor Text/Link Changes:

1. Locate the specific `.html` file in this repository (e.g., `index.html` for the homepage or a subfolder for specific pages).
2. Edit the HTML code directly via the GitHub web interface or your preferred code editor.
3. Commit the changes to the `main` branch.

### For Major Structural Changes:

To use a CMS again, a maintainer would need to:

1. Restore the **WordPress Archive** (database and `wp-content` files) to a local environment (e.g., LocalWP or XAMPP).
2. Perform edits within the local WordPress environment.
3. Re-run a Simply Static export and push the new files to this repository.

---

## ⚙️ Critical Settings

To maintain the site's live status, do not modify these configurations:

* **CNAME File:** The file named `CNAME` in the root must remain. It maps `ateamz.able.bg` to this repository.
* **DNS Configuration:** The Cloudflare DNS for `ateamz.able.bg` is set to **DNS Only** (Grey Cloud) to ensure GitHub Pages can manage the SSL certificate renewal.

---

## ⚠️ Known Limitations

Because the source CMS is decommissioned:

* **No Dynamic Forms:** Standard WordPress form plugins will not function. Any active forms must use an external handler (e.g., Formspree).
* **Security:** The site is virtually unhackable because there is no database or PHP execution on the server.

---

## 📁 Archive Information

The original WordPress files and database dump have been securely archived by **Stoil M. Stoilov**. Contact the ABLE if you require the source files to rebuild the site's backend.

---

**Maintained by:** Stoil M. Stoilov and other ABLE IT Team members

**Status:** Archived / Static Mode

**Last Updated:** March 2026

---

## License / Copyright

© 2026 Association of the Bulgarian Leaders and Entrepreneurs. All rights reserved.

This project and its contents are proprietary. No part of this repository may be reproduced, distributed, or transmitted in any form or by any means—including copying, modifying, or incorporating into other projects—without the prior written permission of the owner. 

By viewing this repository, you agree to the [GitHub Terms of Service](https://github.com) regarding public repositories.

