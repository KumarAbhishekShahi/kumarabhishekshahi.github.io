<!--
  Kumar Abhishek Shahi — Modern multi-column profile/resume
  Designed for rendering with a Markdown engine that supports inline HTML and CSS.
  For LinkedIn/GitHub README, use the content sections but expect limited CSS support.
-->

<style>
:root {
  --navy: #102a43;
  --blue: #1976d2;
  --teal: #00897b;
  --gold: #f4a261;
  --ink: #243b53;
  --muted: #627d98;
  --pale-blue: #eaf3ff;
  --pale-teal: #e8f7f3;
  --pale-gold: #fff4e5;
  --line: #d9e2ec;
}
.profile { max-width: 1180px; margin: auto; font-family: Inter, Segoe UI, Arial, sans-serif; color: var(--ink); line-height: 1.55; }
.hero { background: linear-gradient(135deg, var(--navy), #1d4e89 62%, var(--teal)); color: white; padding: 34px 40px; border-radius: 18px; margin-bottom: 18px; }
.hero h1 { margin: 0 0 5px; font-size: 38px; letter-spacing: -1px; }
.hero h2 { margin: 0 0 16px; font-size: 17px; font-weight: 500; color: #d9f2ff; }
.contact { display: flex; flex-wrap: wrap; gap: 9px; }
.contact a, .contact span { color: white; text-decoration: none; border: 1px solid rgba(255,255,255,.38); border-radius: 20px; padding: 5px 11px; font-size: 13px; }
.grid { display: grid; grid-template-columns: 30% 70%; gap: 18px; align-items: start; }
.card { border: 1px solid var(--line); border-radius: 14px; padding: 20px; margin-bottom: 18px; background: white; box-shadow: 0 3px 12px rgba(16,42,67,.06); }
.card.blue { background: var(--pale-blue); border-color: #bdd7f5; }
.card.teal { background: var(--pale-teal); border-color: #b7e4db; }
.card.gold { background: var(--pale-gold); border-color: #f8d5a6; }
.card h2 { color: var(--navy); font-size: 20px; margin: 0 0 12px; border-bottom: 3px solid var(--blue); padding-bottom: 5px; }
.card h3 { color: var(--teal); font-size: 16px; margin: 17px 0 3px; }
.card h3:first-of-type { margin-top: 0; }
.card p { margin: 7px 0; }
.card ul { margin: 7px 0 0 19px; padding: 0; }
.card li { margin: 4px 0; }
.tag { display: inline-block; background: white; border: 1px solid #b8cce0; color: var(--navy); border-radius: 14px; padding: 4px 9px; margin: 3px 2px; font-size: 12px; }
.metric { display: inline-block; width: 46%; vertical-align: top; margin: 1%; text-align: center; background: white; border-radius: 12px; padding: 12px 2px; }
.metric strong { display: block; color: var(--blue); font-size: 25px; }
.metric span { color: var(--muted); font-size: 12px; }
.timeline { border-left: 3px solid #9ac3ed; padding-left: 17px; }
.timeline h3 { position: relative; }
.timeline h3:before { content: ''; width: 10px; height: 10px; background: var(--blue); border: 3px solid white; outline: 2px solid var(--blue); border-radius: 50%; position: absolute; left: -25px; top: 6px; }
.linkbox { display: block; background: white; border-radius: 9px; padding: 8px 10px; margin: 7px 0; text-decoration: none; color: var(--blue); border-left: 4px solid var(--gold); }
.small { font-size: 13px; color: var(--muted); }
.footer { text-align: center; color: var(--muted); font-size: 12px; margin: 20px 0; }
@media (max-width: 780px) { .grid { grid-template-columns: 1fr; } .hero { padding: 25px; } .hero h1 { font-size: 30px; } }
@media print { .profile { max-width: none; } .hero { print-color-adjust: exact; -webkit-print-color-adjust: exact; } .card { break-inside: avoid; box-shadow: none; } }
</style>

<div class="profile">

<div class="hero">
<h1>Kumar Abhishek Shahi</h1>
<h2>Technology Strategist · AI Transformation Leader · Domain Architect · CXO Advisor</h2>
<div class="contact">
<span>📍 Pune, Maharashtra, India</span>
<a href="mailto:abhishek.shahi@gmail.com">✉ abhishek.shahi@gmail.com</a>
<span>☎ +91 9811706611</span>
<a href="https://www.linkedin.com/in/abhishekshahi">in LinkedIn Profile</a>
</div>
</div>

<div class="grid">

<div>
<div class="card blue">
<h2>Profile Snapshot</h2>
<div class="metric"><strong>24+</strong><span>Years of experience</span></div>
<div class="metric"><strong>80+</strong><span>Global engineering team</span></div>
<div class="metric"><strong>$5M</strong><span>Annual portfolio</span></div>
<div class="metric"><strong>82%</strong><span>Processing-time reduction</span></div>
</div>

<div class="card teal">
<h2>Core Expertise</h2>
<span class="tag">AI Transformation</span><span class="tag">GenAI</span><span class="tag">RAG</span><span class="tag">Multi-Agent Systems</span><span class="tag">AI Governance</span><span class="tag">Java</span><span class="tag">Spring Boot</span><span class="tag">Microservices</span><span class="tag">Event-Driven Architecture</span><span class="tag">Cloud Native</span><span class="tag">DevEx</span><span class="tag">DevSecOps</span><span class="tag">SRE</span><span class="tag">DORA Metrics</span><span class="tag">Observability</span><span class="tag">Platform Engineering</span><span class="tag">CXO Advisory</span><span class="tag">Vendor Management</span>
</div>

<div class="card">
<h2>Technology Stack</h2>
<p><strong>AI:</strong> Gemini, Claude, ChatGPT Enterprise, Ollama, LangGraph, RAGAS, LangSmith, ChromaDB, Qdrant, Python.</p>
<p><strong>Architecture:</strong> DDD, C4, Hexagonal Architecture, Microservices, SOA, Event-Driven Architecture, Data Mesh, IDP.</p>
<p><strong>Cloud:</strong> GCP, Azure, OpenShift, Kubernetes, Docker.</p>
<p><strong>Engineering:</strong> Java, Spring Boot, JEE, React, Angular, Oracle, WebLogic, GitHub Actions.</p>
<p><strong>Reliability:</strong> Prometheus, Grafana, Splunk, ScienceLogic, AlertSite, SLOs, SLIs, Error Budgets, FinOps.</p>
</div>

<div class="card gold">
<h2>Education</h2>
<p><strong>MBA</strong><br>Indian Institute of Management Raipur</p>
<p><strong>M.Tech, Data Analytics</strong><br>Birla Institute of Technology and Science, Pilani</p>
</div>

<div class="card">
<h2>Certifications</h2>
<ul>
<li>Google GenAI Leader</li><li>Cloud Engineering with Google Cloud</li><li>Global Enterprise Engineer</li><li>Certified ScrumMaster</li><li>SAFe Certified Practitioner</li><li>Machine Learning for Business Professionals</li><li>IT Project Management</li>
</ul>
<p class="small">Add credential IDs, dates, issuing bodies, and verification links.</p>
</div>

<div class="card teal">
<h2>Contact Me For</h2>
<ul>
<li>Enterprise AI and GenAI transformation</li><li>RAG and multi-agent architecture</li><li>AI governance and responsible adoption</li><li>Java and Spring Boot modernization</li><li>DevEx, platform engineering, and DORA</li><li>DevSecOps, SRE, observability, and FinOps</li><li>Engineering leadership and CXO advisory</li><li>Conferences, seminars, guest lectures, and mentoring</li>
</ul>
</div>
</div>

<div>
<div class="card">
<h2>Professional Experience</h2>
<div class="timeline">
<h3>Domain Architect / Head of Engineering — DevEx & SDLC</h3>
<p><strong>Deutsche Bank</strong> · Pune · April 2020 – Present</p>
<ul>
<li>Lead an 80+ person global organization across five platform domains, nine squads, and three VP direct reports.</li>
<li>Manage a $5M annual RTB, CTB, and ADC investment portfolio across 30+ vendor engagements.</li>
<li>Architect production-grade enterprise RAG pipelines and multi-agent systems using LangGraph, ChromaDB, Qdrant, and Gemini APIs.</li>
<li>Establish prompt-engineering standards and AI governance aligned with the NIST AI Risk Management Framework.</li>
<li>Modernize Java monoliths and batch/Oracle processes with Spring Boot microservices and event-driven architecture.</li>
<li>Reduced processing time from 8.5 hours to 1.5 hours—an 82% reduction.</li>
<li>Embed DORA metrics, SDLC controls, GitHub Actions, DevSecOps, threat modeling, SCA, and container security.</li>
<li>Advise 20+ business lines across IBOR, AML/Sanctions, and Oracle ERP platforms.</li>
</ul>

<h3>Software Development Manager</h3>
<p><strong>Symantec</strong> · Pune · February 2016 – April 2020</p>
<ul>
<li>Led globally distributed teams, partners, contracts, licenses, and SaaS infrastructure with zero downtime.</li>
<li>Improved site delivery by 30% through automation, CDN, and monitoring.</li>
<li>Led cloud transformation, AS-IS to TO-BE migrations, portfolio management, and technical POCs.</li>
<li>Founded an AI CoE and evaluated LLM tools using RAGAS and LangSmith.</li>
</ul>

<h3>Architect</h3>
<p><strong>Oracle Corporation</strong> · NCR, India · December 2010 – February 2016</p>
<ul><li>Led multimillion-dollar solution-architecture engagements for Reliance Jio, American Express FRX, and Emerson Trellis.</li><li>Drove TCO reduction, ROI improvement, governance, and complex technical issue resolution.</li></ul>

<h3>Earlier Architecture and Delivery Roles</h3>
<p><strong>Birlasoft · GlobalLogic · Wipro · NIIT Technologies · Prometric Software</strong> · 2002 onward</p>
<p>Delivered product implementations, architecture, presales, estimation, and technical leadership across internet security, wealth management, and enterprise technology.</p>
</div>
</div>

<div class="card blue">
<h2>Writing and Publications</h2>
<a class="linkbox" href="#">CI/CD using Google Cloud Build and Google Cloud Run — Part 1</a>
<a class="linkbox" href="#">CI/CD using Google Cloud Build and Google Cloud Run — Part 2</a>
<a class="linkbox" href="#">Rule-Based Content Replication from Production to Non-Production in AEM</a>
<a class="linkbox" href="#">Working with PL/SQL Web Services in JDeveloper 12c</a>
<a class="linkbox" href="#">Building and Testing Databound Web Applications using JCS, DCS, and JDeveloper 12c</a>
<h3>LinkedIn Articles</h3>
<p class="small">Add direct links to articles on AI transformation, RAG, agentic AI, DevEx, DORA, Java modernization, SRE, and responsible AI.</p>
<a class="linkbox" href="#">View LinkedIn articles →</a>
<h3>Books and eBooks</h3>
<a class="linkbox" href="#">Add book title, synopsis, publisher, ISBN, and purchase link</a>
<h3>Blogs and Newsletters</h3>
<a class="linkbox" href="#">Personal blog / technical newsletter</a>
</div>

<div class="card teal">
<h2>Speaking and Knowledge Sharing</h2>
<h3>Conferences</h3>
<table><tr><th>Event</th><th>Topic</th><th>Date / Link</th></tr><tr><td>Add event</td><td>AI, architecture, DevEx, or SRE</td><td><a href="#">Details</a></td></tr></table>
<h3>Seminars and Guest Lectures</h3>
<p>Add university, company, community, topic, audience, date, recording, and event link.</p>
<h3>Suggested Topics</h3>
<ul><li>Enterprise RAG and agentic AI systems</li><li>AI-assisted SDLC and governance</li><li>Modernizing Java platforms</li><li>Building Internal Developer Platforms</li><li>DORA metrics and engineering excellence</li><li>SRE for regulated financial systems</li></ul>
</div>

<div class="card gold">
<h2>Community, CSR, and Associations</h2>
<ul>
<li>Women in Tech mentorship</li><li>DEI and inclusive engineering initiatives</li><li>Student and early-career mentoring</li><li>Digital literacy and community technology programs</li><li>Professional technology associations</li><li>Open-source projects and developer communities</li>
</ul>
<p class="small">Add organization, role, dates, outcomes, membership IDs, and links.</p>
</div>

<div class="card">
<h2>Awards and Recognition</h2>
<span class="tag">Multiple Spot Awards</span><span class="tag">Employee of the Month</span><span class="tag">Team of the Month</span><span class="tag">Program Management</span><span class="tag">Site Leadership</span><span class="tag">Generative AI</span><span class="tag">Engineering Excellence</span>
<p class="small">Add award year, organization, citation, and evidence link.</p>
</div>

<div class="card blue">
<h2>Digital Presence</h2>
<a class="linkbox" href="https://www.linkedin.com/in/abhishekshahi">LinkedIn profile</a>
<a class="linkbox" href="#">LinkedIn articles</a>
<a class="linkbox" href="#">GitHub and open-source projects</a>
<a class="linkbox" href="#">YouTube channel</a>
<a class="linkbox" href="#">Instagram</a>
<a class="linkbox" href="#">Personal website / portfolio</a>
<a class="linkbox" href="#">Google Scholar / ORCID / Speaker Deck</a>
</div>
</div>
</div>

<div class="card">
<h2>Short Bio</h2>
<p>Kumar Abhishek Shahi is a technology strategist, AI transformation leader, and domain architect with 24 years of experience in enterprise architecture, GenAI, DevEx, DevSecOps, SRE, cloud-native platforms, and global engineering leadership. He currently leads DevEx and SDLC engineering initiatives at Deutsche Bank, where he architects AI-assisted engineering platforms, governs technology investments, modernizes legacy systems, and advises business and technology leaders across regulated financial environments.</p>
</div>

<div class="footer">Please remove confidential employer, client, architecture, and financial information before publishing this profile publicly.</div>
</div>
