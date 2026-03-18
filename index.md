### Welcome to GitHub Pages.

This automatic page generator is the easiest way to create beautiful pages for all of your projects. Author your page content here [using GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/), select a template crafted by a designer, and publish. After your page is generated, you can check out the new `gh-pages` branch locally. If you’re using GitHub Desktop, simply sync your repository and you’ll see the new branch.

### Designer Templates

We’ve crafted some handsome templates for you to use. Go ahead and click 'Continue to layouts' to browse through them. You can easily go back to edit your page before publishing. After publishing your page, you can revisit the page generator and switch to another theme. Your Page content will be preserved.

### Creating pages manually

If you prefer to not use the automatic generator, push a branch named `gh-pages` to your repository to create a page manually. In addition to supporting regular HTML content, GitHub Pages support Jekyll, a simple, blog aware static site generator. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers intelligent blog support and other advanced templating features.

### Authors and Contributors

You can @mention a GitHub username to generate a link to their profile. The resulting `<a>` element will link to the contributor’s GitHub Profile. For example: In 2007, Chris Wanstrath (@defunkt), PJ Hyett (@pjhyett), and Tom Preston-Werner (@mojombo) founded GitHub.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/pages) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Scott Brinkmeyer</title>
    <style>
      *, *::before, *::after { box-sizing: border-box; }

      :root {
        --bg: #eef0f4;
        --header-bg: #1c2533;
        --card-bg: #ffffff;
        --accent: #2563eb;
        --text: #111827;
        --text-muted: #6b7280;
        --label-text: #374151;
        --border: #e5e7eb;
        --shadow: 0 1px 3px rgba(0,0,0,.07), 0 4px 14px rgba(0,0,0,.06);
        --radius: 10px;
        --out-color: #0d9488;
      }

      body {
        font-family: system-ui, -apple-system, Segoe UI, Roboto, sans-serif;
        background: var(--bg);
        color: var(--text);
        margin: 0;
        padding: 0;
        min-height: 100vh;
      }

      header {
        background: var(--header-bg);
        color: #fff;
        padding: 20px 24px 18px;
      }

      header h1 {
        font-size: 22px;
        font-weight: 700;
        margin: 0 0 4px;
        letter-spacing: 0.01em;
      }

      header p {
        margin: 0;
        font-size: 14px;
        color: rgba(255,255,255,0.6);
        font-weight: 400;
      }

      .page {
        padding: 24px 16px 56px;
        max-width: 560px;
        margin: 0 auto;
      }

      .section-label {
        font-size: 11px;
        font-weight: 700;
        letter-spacing: 0.09em;
        text-transform: uppercase;
        color: var(--text-muted);
        margin: 28px 0 8px;
      }

      .section-label:first-child {
        margin-top: 0;
      }

      .card {
        background: var(--card-bg);
        border-radius: var(--radius);
        box-shadow: var(--shadow);
        overflow: hidden;
      }

      .row {
        display: flex;
        align-items: flex-start;
        gap: 14px;
        padding: 14px 16px;
        border-bottom: 1px solid var(--border);
      }

      .row:last-child {
        border-bottom: none;
      }

      .row-icon {
        font-size: 20px;
        flex-shrink: 0;
        width: 28px;
        text-align: center;
        padding-top: 1px;
      }

      .row-body {
        flex: 1;
        min-width: 0;
      }

      .row-title {
        font-size: 15px;
        font-weight: 600;
        color: var(--text);
        line-height: 1.3;
      }

      .row-desc {
        font-size: 13px;
        color: var(--text-muted);
        margin-top: 3px;
        line-height: 1.5;
      }

      .row-link {
        display: inline-flex;
        align-items: center;
        gap: 5px;
        margin-top: 8px;
        font-size: 13px;
        font-weight: 600;
        color: var(--accent);
        text-decoration: none;
        padding: 5px 10px;
        border: 1.5px solid var(--accent);
        border-radius: 6px;
        transition: background 0.12s;
      }

      .row-link:hover {
        background: #eff6ff;
      }

      .row-link svg {
        width: 13px;
        height: 13px;
        flex-shrink: 0;
      }

      .tag-row {
        display: flex;
        flex-wrap: wrap;
        gap: 6px;
        margin-top: 8px;
      }

      .tag {
        font-size: 11px;
        font-weight: 600;
        letter-spacing: 0.04em;
        text-transform: uppercase;
        padding: 3px 9px;
        border-radius: 20px;
        background: var(--bg);
        color: var(--text-muted);
        border: 1px solid var(--border);
      }

      .tag.green {
        background: #f0fdf4;
        color: #15803d;
        border-color: #bbf7d0;
      }

      .tag.blue {
        background: #eff6ff;
        color: #1d4ed8;
        border-color: #bfdbfe;
      }

      .tag.teal {
        background: #f0fdfa;
        color: #0f766e;
        border-color: #99f6e4;
      }

      footer {
        text-align: center;
        padding: 0 16px 32px;
        font-size: 12px;
        color: var(--text-muted);
      }

      footer a {
        color: var(--text-muted);
        text-decoration: none;
      }

      footer a:hover {
        color: var(--accent);
      }
    </style>

  </head>
  <body>
    <header>
      <h1>Scott Brinkmeyer</h1>
      <p>Building things — in the cloud, in the shop, and on the farm.</p>
    </header>

    <div class="page">

      <div class="section-label">Work</div>
      <div class="card">
        <div class="row">
          <div class="row-icon">☁️</div>
          <div class="row-body">
            <div class="row-title">CI/CD &amp; Cloud Architecture</div>
            <div class="row-desc">A long career designing and shipping cloud infrastructure — pipelines, platforms, and the glue that holds them together.</div>
            <div class="tag-row">
              <span class="tag blue">CI/CD</span>
              <span class="tag blue">Cloud</span>
              <span class="tag blue">DevOps</span>
              <span class="tag blue">Platform Eng</span>
            </div>
            <a class="row-link" href="https://www.linkedin.com/in/scott-brinkmeyer-447187b" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
              LinkedIn
            </a>
          </div>
        </div>
      </div>

      <div class="section-label">Shop</div>
      <div class="card">
        <div class="row">
          <div class="row-icon">🎸</div>
          <div class="row-body">
            <div class="row-title">Guitar Building</div>
            <div class="row-desc">Lutherie as a craft — jointing, shaping, and finishing acoustic and electric instruments by hand.</div>
            <div class="tag-row">
              <span class="tag teal">Lutherie</span>
              <span class="tag teal">Woodworking</span>
              <span class="tag teal">Hand Tools</span>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="row-icon">📐</div>
          <div class="row-body">
            <div class="row-title">Inch · Fraction · mm Converter</div>
            <div class="row-desc">A shop tool I built for converting between decimal inches, fractions, and millimeters — with a board-feet cut list. Installable as a PWA.</div>
            <a class="row-link" href="https://sbrinkmeyer.github.io/fictional-succotash/" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
              Open app
            </a>
          </div>
        </div>
      </div>

      <div class="section-label">Farm</div>
      <div class="card">
        <div class="row">
          <div class="row-icon">🐐</div>
          <div class="row-body">
            <div class="row-title">Dairy Goats</div>
            <div class="row-desc">Raising dairy goats — still figuring out more than I've figured out.</div>
            <div class="tag-row">
              <span class="tag green">Dairy</span>
              <span class="tag green">Livestock</span>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="row-icon">🥚</div>
          <div class="row-body">
            <div class="row-title">Eggs</div>
            <div class="row-desc">Keeping chickens and collecting eggs — simple, satisfying, and reliably humbling.</div>
            <div class="tag-row">
              <span class="tag green">Poultry</span>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="row-icon">🌲</div>
          <div class="row-body">
            <div class="row-title">Forestry</div>
            <div class="row-desc">Managing and working the land — timber, trails, and long-term thinking about what to leave behind.</div>
            <div class="tag-row">
              <span class="tag green">Timber</span>
              <span class="tag green">Land Stewardship</span>
            </div>
          </div>
        </div>
      </div>

      <div class="section-label">Code</div>
      <div class="card">
        <div class="row">
          <div class="row-icon">
            <svg viewBox="0 0 24 24" fill="currentColor" style="width:22px;height:22px;color:#374151"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0112 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
          </div>
          <div class="row-body">
            <div class="row-title">GitHub</div>
            <div class="row-desc">Projects, tools, and experiments.</div>
            <a class="row-link" href="https://github.com/sbrinkmeyer" target="_blank" rel="noopener">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
              github.com/sbrinkmeyer
            </a>
          </div>
        </div>
      </div>

    </div>

    <footer>
      <a href="https://github.com/sbrinkmeyer">sbrinkmeyer</a> · built with GitHub Pages
    </footer>

  </body>
</html>
