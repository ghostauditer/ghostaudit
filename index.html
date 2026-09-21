<!doctype html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>0xrecon / Bug Bounty Hunter</title>
<meta name="description" content="Bug bounty hunter: web, API, casino money flows. Reproducible PoCs, responsible disclosure.">
<style>
:root{
  --bg:#0b0d12;
  --panel:#12151c;
  --panel2:#181c25;
  --text:#e6e9ef;
  --muted:#8a93a6;
  --line:#232836;
  --accent:#7c5cff;
  --accent2:#00e0b8;
  --green:#2ecc71;
  --red:#ff5c5c;
  --orange:#ffb020;
  --radius:14px;
  --shadow:0 10px 40px rgba(0,0,0,.45);
}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--text);font-family:Inter,Roboto,Arial,sans-serif;line-height:1.6}
a{color:var(--accent2);text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:1100px;margin:0 auto;padding:0 22px}
header.hero{padding:90px 0 60px;border-bottom:1px solid var(--line);background:radial-gradient(1200px 500px at 20% -10%,rgba(124,92,255,.18),transparent 60%)}
.hero-tag{display:inline-block;font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--accent2);border:1px solid rgba(0,224,184,.35);padding:6px 12px;border-radius:999px;margin-bottom:22px}
h1{font-size:52px;line-height:1.1;margin:0 0 14px;font-weight:900;letter-spacing:-.02em}
h1 .accent{color:var(--accent2)}
.lead{color:var(--muted);font-size:18px;max-width:640px}
.hero-actions{margin-top:28px;display:flex;gap:12px;flex-wrap:wrap}
.btn{display:inline-block;padding:12px 18px;border-radius:12px;font-weight:700;border:1px solid var(--line);background:var(--panel);color:var(--text);transition:.15s}
.btn:hover{border-color:var(--accent);color:var(--accent2);text-decoration:none;transform:translateY(-1px)}
.btn.primary{background:linear-gradient(135deg,var(--accent),#5b3df0);border-color:transparent;color:#fff}
section{padding:70px 0;border-bottom:1px solid var(--line)}
.section-head{margin-bottom:36px}
.section-head .kicker{font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--accent2);margin-bottom:8px}
h2{font-size:32px;margin:0;font-weight:800;letter-spacing:-.01em}
.grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.grid-2{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:var(--radius);padding:22px;box-shadow:var(--shadow)}
.card h3{margin:0 0 10px;font-size:18px}
.card p{color:var(--muted);margin:0;font-size:15px}
.card .tag{display:inline-block;font-size:11px;padding:4px 8px;border-radius:6px;background:rgba(124,92,255,.15);color:#b8a7ff;margin-bottom:10px;letter-spacing:.06em;text-transform:uppercase}
.cases{display:flex;flex-direction:column;gap:14px}
.case{background:var(--panel);border:1px solid var(--line);border-radius:var(--radius);padding:20px;display:grid;grid-template-columns:1fr auto;gap:16px;align-items:start;transition:.15s}
.case:hover{border-color:var(--accent);transform:translateY(-1px)}
.case h3{margin:0 0 6px;font-size:18px}
.case .meta{color:var(--muted);font-size:13px}
.case .desc{color:var(--muted);font-size:14px;margin-top:8px}
.badge{display:inline-block;font-size:11px;font-weight:800;padding:5px 10px;border-radius:8px;text-transform:uppercase;letter-spacing:.06em}
.badge.paid{background:rgba(46,204,113,.15);color:var(--green);border:1px solid rgba(46,204,113,.3)}
.badge.scam{background:rgba(255,92,92,.12);color:var(--red);border:1px solid rgba(255,92,92,.3)}
.badge.sent{background:rgba(255,176,32,.12);color:var(--orange);border:1px solid rgba(255,176,32,.3)}
.badge.ignored{background:rgba(138,147,166,.12);color:var(--muted);border:1px solid rgba(138,147,166,.3)}
.amount{font-weight:800;color:var(--accent2);font-size:15px;text-align:right;white-space:nowrap}
.tools{display:flex;flex-wrap:wrap;gap:8px}
.tool{background:var(--panel2);border:1px solid var(--line);padding:8px 12px;border-radius:999px;font-size:13px;color:var(--text)}
footer{padding:40px 0;color:var(--muted);font-size:14px;text-align:center}
footer a{color:var(--accent2)}
.path{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;margin-top:10px}
.path .step{background:var(--panel);border:1px solid var(--line);border-radius:var(--radius);padding:18px}
.path .step b{display:block;color:var(--accent2);margin-bottom:6px;font-size:14px}
.path .step span{color:var(--muted);font-size:14px}
@media(max-width:900px){
  h1{font-size:38px}
  .grid-3,.grid-2,.path{grid-template-columns:1fr}
  .case{grid-template-columns:1fr}
  .amount{text-align:left}
}
</style>
</head>
<body>

<header class="hero">
  <div class="wrap">
    <span class="hero-tag">Bug Bounty · Web / API</span>
    <h1><span class="accent">0xrecon</span> / Bug Bounty Hunter</h1>
    <p class="lead">No fluff — only reproducible PoCs and real business impact. I hunt in web apps, APIs, and casino money flows: balance abuse, payment bypass, broken access control, session leaks.</p>
    <div class="hero-actions">
      <a class="btn primary" href="#findings">Смотреть findings</a>
      <a class="btn" href="#contact">Связаться</a>
      <a class="btn" href="https://github.com/ТВОЙНИК" target="_blank">GitHub</a>
    </div>
  </div>
</header>

<section id="about">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">About me</div>
      <h2>Who I am</h2>
    </div>
    <div class="grid-2">
      <div class="card">
        <h3>Focus</h3>
        <p>Web apps, APIs, cloud. Money and access: balance tricks, payment bypass, privilege escalation, backdoors in business logic. If value or access moves the wrong way — I dig in.</p>
      </div>
      <div class="card">
        <h3>Approach</h3>
        <p>Map the attack surface, ship a reproducible PoC, disclose under program rules. No low-impact noise. No shadow gigs. No extortion. Just clear reports and fixes.</p>
      </div>
    </div>
  </div>
</section>

<section id="focus">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">Focus</div>
      <h2>What I look for</h2>
    </div>
    <div class="grid-3">
      <div class="card">
        <span class="tag">Web</span>
        <h3>Web applications</h3>
        <p>XSS, CSRF, IDOR, broken access control, SSRF. Plus money and trust: balance tricks, payment bypass, hidden privilege jumps.</p>
      </div>
      <div class="card">
        <span class="tag">API</span>
        <h3>APIs & integrations</h3>
        <p>Tokens, sessions, header/cookie leaks, rate limits, quota bypass. REST & GraphQL: IDOR, batch and nested queries, OAuth, webhooks, signatures.</p>
      </div>
      <div class="card">
        <span class="tag">Cloud</span>
        <h3>Cloud & infra</h3>
        <p>Bucket misconfigs, leaks via logs and metadata. SSRF to internal services. IAM: excessive roles, cross-account trust, secrets in repos.</p>
      </div>
    </div>
  </div>
</section>

<section id="findings">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">Write-ups / Findings</div>
      <h2>Reports & findings</h2>
    </div>

    <div class="cases">

      <article class="case">
        <div>
          <h3>Pokerok Casino</h3>
          <div class="meta">April 2026 · Per agreement, details not disclosed</div>
          <div class="desc">Full report handed to the operator. Technical details withheld by mutual agreement.</div>
        </div>
        <div>
          <div class="amount">$15,000 paid</div>
          <span class="badge paid">Paid</span>
        </div>
      </article>

      <article class="case">
        <div>
          <h3>ON-X Casino: GraphQL & payouts</h3>
          <div class="meta">April 2026 · Critical / High · Resolved</div>
          <div class="desc">KYC without login, makeRebill without guard, payout and bonus IDOR, retryPaymentUrl, loyalty points, mutation races, WebSocket without token.</div>
        </div>
        <div>
          <div class="amount">$10,000 paid</div>
          <span class="badge paid">Paid</span>
        </div>
      </article>

      <article class="case">
        <div>
          <h3>BC.GAME: report with the operator</h3>
          <div class="meta">April 2026 · Handed to the operator</div>
          <div class="desc">Full information will be published within 14 days.</div>
        </div>
        <div>
          <span class="badge sent">Sent</span>
        </div>
      </article>

      <article class="case">
        <div>
          <h3>Mostbet: public report (scam, ignore)</h3>
          <div class="meta">April 2026 · scam · ignore · public report</div>
          <div class="desc">hraicxmb.com: password leak, Sumsub IDOR, P2P, SSO JWT. Operator ignored findings and paid no bounty.</div>
        </div>
        <div>
          <span class="badge scam">Scam</span>
        </div>
      </article>

      <article class="case">
        <div>
          <h3>1xBet: public report (scam)</h3>
          <div class="meta">April 2026 · scam · ignore · public report</div>
          <div class="desc">Support replied with a clown image; seven findings; full PoC files in assets/1xbet-poc/.</div>
        </div>
        <div>
          <span class="badge scam">Scam</span>
        </div>
      </article>

      <article class="case">
        <div>
          <h3>1xSlots: findings on a casino site</h3>
          <div class="meta">April 2026 · Critical / High · scam · ignore</div>
          <div class="desc">Login and Telegram 2FA without rate limits, negative wallet amounts, session IDOR, password reset issues.</div>
        </div>
        <div>
          <span class="badge scam">Scam</span>
        </div>
      </article>

      <article class="case">
        <div>
          <h3>JetTon Casino: public report</h3>
          <div class="meta">April 2026 · scam · ignore · unpaid</div>
          <div class="desc">Long-lived token without HttpOnly, /api/v1/me, Centrifugo channels, turbine endpoint, wallet API map.</div>
        </div>
        <div>
          <span class="badge scam">Scam</span>
        </div>
      </article>

      <article class="case">
        <div>
          <h3>Eva Casino: owner will not pay</h3>
          <div class="meta">April 2026 · scam · ignore · no bounty budget</div>
          <div class="desc">Wallet IDOR, JWT without HttpOnly, daily-login 500s, captcha off. Owner: not ready to allocate money.</div>
        </div>
        <div>
          <span class="badge scam">Scam</span>
        </div>
      </article>

    </div>
  </div>
</section>

<section id="articles">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">Articles</div>
      <h2>Cases and long-form notes</h2>
    </div>
    <div class="grid-2">
      <div class="card">
        <span class="tag">Wagering</span>
        <h3>Air Boss: pre-round window and wager abuse</h3>
        <p>Bets placed in the ~10s pre-start window can inflate bonus wagering with weaker in-game risk.</p>
      </div>
      <div class="card">
        <span class="tag">Aggregator</span>
        <h3>Rocketman: "money rain" and bonus farming</h3>
        <p>Moving funds between accounts in the same casino to farm cashback and deposit bonuses.</p>
      </div>
      <div class="card">
        <span class="tag">Integration</span>
        <h3>Amusnet: slot, lobby, and bonus playthrough</h3>
        <p>Split live from slots in your systems — turnover may still count as slots, softening wagering.</p>
      </div>
      <div class="card">
        <span class="tag">Cashier</span>
        <h3>P2P deposits: crediting mistakes</h3>
        <p>Webhook retries, races, floating money, weak payment-to-user binding. A checklist for engineering.</p>
      </div>
    </div>
  </div>
</section>

<section id="path">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">My path</div>
      <h2>How I hunt bugs</h2>
    </div>
    <div class="path">
      <div class="step"><b>1. Scope & rules</b><span>Read the program scope and bans. Otherwise you waste time and add risk.</span></div>
      <div class="step"><b>2. Recon</b><span>Endpoints, parameters, APIs. Map where logic can break.</span></div>
      <div class="step"><b>3. Hunting & chains</b><span>Manual testing + scripts. Reproducible issues with clear impact.</span></div>
      <div class="step"><b>4. Report & payout</b><span>PoC, steps, responsible disclosure. Triage on their terms.</span></div>
    </div>
  </div>
</section>

<section id="tools">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">Tools & Skills</div>
      <h2>Stack & habits</h2>
    </div>
    <div class="tools">
      <span class="tool">Burp Suite Pro</span>
      <span class="tool">Nuclei</span>
      <span class="tool">Katana</span>
      <span class="tool">Subfinder</span>
      <span class="tool">ffuf</span>
      <span class="tool">Python</span>
      <span class="tool">Bash</span>
      <span class="tool">Cloud recon</span>
      <span class="tool">API testing</span>
      <span class="tool">GraphQL</span>
      <span class="tool">OAuth</span>
    </div>
  </div>
</section>

<section id="contact">
  <div class="wrap">
    <div class="section-head">
      <div class="kicker">Contact</div>
      <h2>Get in touch</h2>
    </div>
    <div class="grid-2">
      <div class="card">
        <h3>Email</h3>
        <p><a href="mailto:you@example.com">you@example.com</a></p>
      </div>
      <div class="card">
        <h3>Telegram / GitHub</h3>
        <p><a href="https://t.me/ТВОЙНИК" target="_blank">@ТВОЙНИК</a> · <a href="https://github.com/ТВОЙНИК" target="_blank">github.com/ТВОЙНИК</a></p>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="wrap">
    © 2026 0xrecon · Bug Bounty Hunter · Built on GitHub Pages
  </div>
</footer>

</body>
</html>
