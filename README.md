<h1>AWS Cost &amp; Security Optimization</h1>
<h3>AWS Enterprise Environment</h3>

<h2>Overview</h2>
<p>
  This repository documents a cost and security optimization engagement in AWS. The goal was to reduce unnecessary cloud spend
  while maintaining strong security controls using a risk-based approach. The environment was assessed for redundant security
  tooling, unused resources, and high-cost infrastructure components, then optimized and cleaned.
</p>

<hr/>

<h2>Key Responsibilities</h2>
<ul>
  <li>Analyzed AWS security service usage and overlaps across GuardDuty, Security Hub, and Inspector</li>
  <li>Performed a full audit of unused resources (Elastic IPs, NAT Gateways, Load Balancers, snapshots)</li>
  <li>Used AWS Cost Explorer to identify top cost drivers and validate optimization impact</li>
  <li>Deleted unused infrastructure to reduce recurring costs without reducing security coverage</li>
  <li>Replaced NAT Gateway egress with VPC Endpoints where appropriate to lower network costs</li>
  <li>Optimized GuardDuty configuration by limiting enabled regions based on risk and operational needs</li>
  <li>Reduced unnecessary network control overlap (e.g., NACL complexity) while keeping effective segmentation</li>
  <li>Reviewed and cleaned unused KMS keys to improve governance and reduce operational overhead</li>
  <li>Configured budgets to control spending and support continuous cost governance</li>
</ul>

<hr/>

<h2>Tools &amp; Technologies</h2>
<ul>
  <li>AWS Cost Explorer</li>
  <li>AWS Budgets</li>
  <li>Amazon GuardDuty</li>
  <li>AWS Security Hub</li>
  <li>Amazon Inspector</li>
  <li>Amazon VPC Endpoints</li>
  <li>NAT Gateway</li>
  <li>Elastic Load Balancing</li>
  <li>AWS Key Management Service (KMS)</li>
</ul>

<hr/>

<h2>Impact</h2>
<ul>
  <li>Reduced AWS operational costs while maintaining core security detection and compliance controls</li>
  <li>Improved governance by removing unused resources and tightening service configurations</li>
  <li>Lowered network costs by replacing NAT Gateway usage with private VPC endpoints where applicable</li>
  <li>Delivered an estimated 40–50% cost reduction in the simulated environment</li>
</ul>

<hr/>

<h2>Author</h2>
<p>
  <strong>Adedayo</strong><br/>
  AWS Cloud Architect | Cloud Security Specialist
</p>

<hr/>

<h2>Disclaimer</h2>
<p>
  All documentation is anonymized and does not contain confidential or proprietary information.
</p>
