---
layout: default
title: Home
---

<!-- HERO -->
<h2>Helping organizations deliver with confidence, even in the most complex and regulated environments.</h2>
<p>Executive leader in cloud, AI, and transformation — trusted to turn risk into results with clarity and vision.</p>
<p>
  <a class="btn" href="assets/resume.pdf" target="_blank" rel="noopener">Download Resume</a>
  <a class="btn" href="https://www.linkedin.com/in/irenevoskamp" target="_blank" rel="noopener">LinkedIn</a>
  <a class="btn" href="#contact">Contact</a>
</p>

<hr/>

<!-- HIGHLIGHTS -->
<h3 id="highlights">Highlights</h3>
<ul>
  <li><strong>Technology &amp; Transformation Leader</strong> with 15+ years of experience driving secure cloud adoption, AI governance, and large-scale modernization at Microsoft, AWS, Amazon, McAfee, and the Gates Foundation.</li>
  <li>Directed <strong>Microsoft’s confidential cloud strategy</strong>, enabling 20+ critical Azure services to run confidentially.</li>
  <li>At AWS, <strong>doubled GovCloud revenue 4 years running</strong> and unlocked a $400B+ regulated workload market.</li>
  <li>Expert in <strong>Responsible AI</strong>, creating frameworks that accelerate approvals and reduce risk.</li>
  <li>Trusted to lead high-ambiguity programs with 100+ stakeholders, <strong>aligning C-suites, regulators, and engineers.</strong></li>
  <li>Innovator in <strong>Cybersecurity &amp; Privacy</strong> with patents in supply chain attestation, Director of Counterintelligence Operational Analysis Center for DOE, and creator of Microsoft’s AI-powered Transparency Logs, and McAfee’s first enterprise privacy framework.</li>
  <li>Supporting a strong and <strong>Resilient Community</strong> as District IT Manager and Volunteer Firefighter for San Juan Island Fire &amp; Rescue, leading technology modernization to strengthen firefighter readiness and public safety.</li>
  <li>Pioneer in <strong>AI For Community</strong> developing ETHICSENSE and FireRisk AI for wildfire/structure fire prevention.</li>
</ul>

<hr/>

<!-- SELECTED WORK -->
<h3 id="work">Selected Work</h3>
<h4>Cloud for Sovereignty — Microsoft</h4>
<p><strong>Challenge:</strong> Regulated industries hesitated to adopt hyperscale cloud.</p>
<p><strong>Actions:</strong> Designed and launched Microsoft Cloud for Sovereignty with AI-enabled compliance controls.</p>
<p><strong>Results:</strong> Onboarded 10+ enterprise customers in 6 months; unlocked $500M+ contracts.</p>

<h4>GovCloud Growth — AWS</h4>
<p><strong>Challenge:</strong> AWS GovCloud was lagging in revenue and parity.</p>
<p><strong>Actions:</strong> Architected sovereign solutions, built new PMO team, automated DevOps pipelines.</p>
<p><strong>Results:</strong> GovCloud revenue doubled 4 consecutive years; feature parity rose from 35% to 75%.</p>

<h4>AI Design for Dignity</h4>
<p><strong>Challenge:</strong> Teams lacked lightweight governance for AI development.</p>
<p><strong>Actions:</strong> Created ETHICSENSE toolkit to scan AI outputs for privacy, bias, and risk.</p>
<p><strong>Results:</strong> Faster approvals, improved trust, and clear communication with executives.</p>

<hr/>

<!-- COMMUNITY -->
<h3 id="community">Community &amp; Service</h3>
<p>Beyond the corporate arena, I’m committed to making technology and systems more human, resilient, and safe.</p>
<ul>
  <li><strong>Volunteer Firefighter</strong> — San Juan Fire District #3; IT modernization and apparatus operations training.</li>
  <li><strong>FireRisk AI</strong> — predictive analytics for wildfire/structure fire risk from 911 data.</li>
  <li>Advocate for <strong>AI ethics</strong> and <strong>digital dignity</strong>.</li>
</ul>

<hr/>

<!-- ABOUT -->
<h3 id="about">About</h3>
<p>I believe the best leaders don’t just deliver technology — they help people and organizations find clarity in complexity and turn risk into opportunity.</p>
<p>With 15+ years in high-stakes environments — from counterintelligence operations supporting U.S. national security, to cloud computing at Microsoft and AWS, to protecting my friends and neighbors from literal fires — I’ve learned that trust, alignment, and resilience are what carry organizations through transformation.</p>
<p>I bring not just strategy and delivery, but a commitment to building teams and solutions that endure.</p>

<hr/>

<!-- CONTACT -->
<h3 id="contact">Contact</h3>
<p>Use the form below to reach me directly. Your message goes to my inbox — no email exposed.</p>
<form id="contactForm" method="POST" data-form-endpoint="https://formsubmit.co/irene@voskamp.org" novalidate>
  <input type="text" name="_honey" style="display:none">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_subject" value="Portfolio website inquiry">
  <p><label>Name<br><input name="name" type="text" required></label></p>
  <p><label>Email<br><input name="email" type="email" required></label></p>
  <p><label>Message<br><textarea name="message" rows="6" required></textarea></label></p>
  <p><button type="submit">Send</button></p>
  <p id="formStatus" aria-live="polite"></p>
</form>

<script>
  (function() {
    var form = document.getElementById('contactForm');
    var status = document.getElementById('formStatus');
    var endpoint = form.getAttribute('data-form-endpoint');
    form.addEventListener('submit', function(e) {
      e.preventDefault();
      status.textContent = 'Sending…';
      var data = new FormData(form);
      fetch(endpoint, {method: 'POST', body: data}).then(function(res){
        if(res.ok) { status.textContent = 'Thanks — message sent!'; form.reset(); }
        else { status.textContent = 'Hmm, something went wrong. You can email me directly.'; }
      }).catch(function(){ status.textContent = 'Network error. Please email me directly.'; });
    });
  })();
</script>
