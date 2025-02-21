<h1>Enterprise Ticketing System - osTicket Implementation & Customization</h1>

<h2>Description</h2>
This repository documents the setup, configuration, and management of an enterprise-level ticketing system using <b>osTicket</b>, an open-source help desk and ticket management solution. The system was deployed to streamline IT service management (ITSM) by efficiently handling customer and internal support requests within a corporate environment.
<br />

<h2>Key Features & Configurations</h2>

- <b>Multi-Department Ticketing Workflow:</b> Implemented ticket routing for IT, HR, and Customer Support teams.
- <b>Automated Ticket Assignment & SLA Enforcement:</b> Configured help topics, auto-assignments, and response deadlines.
- <b>Custom Ticket Statuses & Lifecycle Management:</b> Optimized the end-to-end ticket lifecycle.
- <b>Email Piping & Notifications:</b> Integrated email-to-ticket functionality for seamless request submissions.
- <b>User Roles & Permissions:</b> Restricted access based on staff hierarchy and department.
- <b>Custom Forms & Fields:</b> Tailored ticket submission fields to capture necessary information.
- <b>Performance & Reporting:</b> Leveraged analytics to monitor agent response times and resolution efficiency.

<h2>Ticket Lifecycle Management</h2>

<h3>1. Ticket Submission</h3>
- Users submit tickets via <b>email, web portal, or API</b>.
- Help topics automatically categorize tickets (e.g., IT Support, Billing, HR).

<h3>2. Ticket Triage & Assignment</h3>
- Incoming tickets are <b>automatically routed</b> based on department and priority.
- SLA rules enforce response and resolution timelines.

<h3>3. Agent Response & Investigation</h3>
- Assigned staff acknowledge and update tickets with troubleshooting steps.
- Internal and external notes provide context for resolution.

<h3>4. Escalation & SLA Management</h3>
- Tickets breaching SLAs trigger <b>automated escalation</b> to senior staff.
- Multi-tiered escalation workflows prevent ticket stagnation.

<h3>5. Resolution & Closure</h3>
- Agents resolve tickets with documented solutions.
- Customers receive a <b>resolution summary</b> and can confirm issue resolution.

<h3>6. Post-Ticket Review & Reporting</h3>
- Ticket resolution data is logged for performance tracking.
- Weekly and monthly reports analyze response efficiency and common issues.

<h2>Environments Used</h2>

- <b>Ubuntu 22.04 LTS</b> (Production Server)
- <b>Windows 10</b> (Testing Environment)

<h2>System Deployment</h2>

- <b>Environment:</b> Apache2, MySQL 8.0, PHP 8.1
- <b>Installation:</b> osTicket v1.17 configured with custom plugins
- <b>Database Optimization:</b> Indexed MySQL tables for performance gains
- <b>Security Enhancements:</b> SSL encryption, access control, and daily backups

<h2>Program Walkthrough:</h2>

<p align="center">
Installation Process: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="osTicket Installation"/>
<br />
<br />
Ticket Submission Portal:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Ticket Submission"/>
<br />
<br />
Agent Dashboard: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Agent Dashboard"/>
<br />
<br />
Ticket Resolution Workflow:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Resolution Workflow"/>
<br />
<br />
Analytics & Reporting:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Reporting Dashboard"/>
</p>

<h2>How to Deploy This Project</h2>
<ol>
    <li>Clone the repository and configure the <b>osTicket environment</b>.</li>
    <li>Set up <b>Apache2, MySQL, and PHP</b> dependencies.</li>
    <li>Customize ticket workflows, SLAs, and user roles as per organizational needs.</li>
    <li>Implement email piping for automated ticket creation.</li>
    <li>Deploy analytics dashboards for monitoring support efficiency.</li>
</ol>

<h2>Conclusion</h2>
This <b>osTicket implementation</b> showcases how <b>enterprise-grade ticketing systems</b> can be deployed, customized, and managed effectively to improve <b>ITSM processes</b>. By leveraging <b>automated workflows, SLA enforcement, and structured lifecycle management</b>, businesses can <b>enhance customer support efficiency and ensure timely issue resolution</b>.

<!--
```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
