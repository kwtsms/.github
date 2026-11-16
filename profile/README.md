<!-- 2026-11-16 15:15 +03: org profile v2 (brand banner, logos, directory), Boss msg 923, q-org-profile -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/banner-dark.png">
  <img alt="kwtSMS: SMS from the tools you already use. 12 client libraries and 42 integrations." src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/banner-light.png" width="100%">
</picture>

<p align="center">
  <a href="https://www.kwtsms.com/cportal/signup/"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/btn-signup.png" height="44" alt="Create a free account"></a>&nbsp;
  <a href="https://www.kwtsms.com/api-documentation.html"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/btn-api.png" height="44" alt="API documentation"></a>&nbsp;
  <a href="https://www.kwtsms.com/developers.html"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/btn-dev.png" height="44" alt="Developers"></a>&nbsp;
  <a href="https://www.kwtsms.com/support.html"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/btn-support.png" height="44" alt="Support"></a>
</p>

kwtSMS sends SMS, OTP codes and alerts to all four Kuwait networks (Zain, Ooredoo, stc, Virgin) and to more than 220 countries. One credit is one SMS and credits never expire. Every account gets free test credits, and `test=1` checks a send without delivering it.

```bash
curl -X POST https://www.kwtsms.com/API/send/ \
  -H "Content-Type: application/json" \
  -d '{"username": "API_USER", "password": "API_PASS",
       "sender": "KWT-SMS", "mobile": "965XXXXXXXX",
       "message": "Hello from kwtSMS", "test": "1"}'
```

## Client libraries

<table>
<tr>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-php"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-php.png" width="52" height="52" alt=""><br><b>PHP</b></a><br><sub><code>composer require kwtsms/kwtsms-php</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-python"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-python.png" width="52" height="52" alt=""><br><b>Python</b></a><br><sub><code>pip install kwtsms</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-js"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-typescript.png" width="52" height="52" alt=""><br><b>JavaScript / TypeScript</b></a><br><sub><code>npm install kwtsms</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-go"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-go.png" width="52" height="52" alt=""><br><b>Go</b></a><br><sub><code>go get github.com/kwtsms/kwtsms-go</code></sub></td>
</tr>
<tr>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-java"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-java.png" width="52" height="52" alt=""><br><b>Java</b></a><br><sub><code>JitPack</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-kotlin"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-kotlin.png" width="52" height="52" alt=""><br><b>Kotlin</b></a><br><sub><code>JitPack</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-csharp"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-csharp.png" width="52" height="52" alt=""><br><b>C# / .NET</b></a><br><sub><code>dotnet add package KwtSMS</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-ruby"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-ruby.png" width="52" height="52" alt=""><br><b>Ruby</b></a><br><sub><code>gem install kwtsms</code></sub></td>
</tr>
<tr>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-rust"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-rust.png" width="52" height="52" alt=""><br><b>Rust</b></a><br><sub><code>cargo add kwtsms</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-swift"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-swift.png" width="52" height="52" alt=""><br><b>Swift</b></a><br><sub><code>Swift Package Manager</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-dart"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-dart.png" width="52" height="52" alt=""><br><b>Dart / Flutter</b></a><br><sub><code>dart pub add kwtsms</code></sub></td>
<td align="center" width="240"><a href="https://github.com/kwtsms/kwtsms-zig"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/l-zig.png" width="52" height="52" alt=""><br><b>Zig</b></a><br><sub><code>zig fetch</code></sub></td>
</tr>
</table>

## Integrations

### Online stores

<table>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-wordpress.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-wordpress"><b>WordPress and WooCommerce</b></a></td><td width="660">The open-source website builder, and the store plugin that runs on it</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-shopify.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-shopify"><b>Shopify</b></a></td><td width="660">Hosted platform for running an online store</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-magento.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-magento"><b>Magento (Adobe Commerce)</b></a></td><td width="660">Open-source e-commerce platform for large catalogs, owned by Adobe</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-opencart.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-opencart"><b>OpenCart</b></a></td><td width="660">Free, open-source PHP shopping cart</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-prestashop.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-prestashop"><b>PrestaShop</b></a></td><td width="660">Open-source e-commerce software for independent stores</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-ecwid.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-ecwid"><b>Ecwid (Lightspeed)</b></a></td><td width="660">Online store you can add to an existing website or social page</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-cscart.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/boxlinknet/kwtsms-cs-cart"><b>CS-Cart</b></a></td><td width="660">PHP shopping cart and multi-vendor marketplace software</td></tr>
</table>

### Business apps, CRM and help desk

<table>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-odoo.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-odoo"><b>Odoo</b></a></td><td width="660">Open-source suite of business apps: sales, invoicing, inventory and more</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-salesforce.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-salesforce"><b>Salesforce</b></a></td><td width="660">Cloud CRM for sales and service teams</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-hubspot.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-hubspot"><b>HubSpot</b></a></td><td width="660">CRM platform for marketing, sales and customer service</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-zoho.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-zoho"><b>Zoho CRM</b></a></td><td width="660">Cloud CRM, part of the Zoho business suite</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-krayin.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-krayin"><b>Krayin</b></a></td><td width="660">Open-source CRM built on Laravel</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-monday.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-monday"><b>monday.com</b></a></td><td width="660">Work management platform with boards and automations</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-zendesk.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-zendesk"><b>Zendesk</b></a></td><td width="660">Customer service and ticketing software</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-freshdesk.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-freshdesk"><b>Freshdesk</b></a></td><td width="660">Help desk software from Freshworks</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-freescout.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-freescout"><b>FreeScout</b></a></td><td width="660">Open-source help desk and shared inbox</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-osticket.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-osticket"><b>osTicket</b></a></td><td width="660">Open-source support ticket system</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-whmcs.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-whmcs"><b>WHMCS</b></a></td><td width="660">Billing and automation platform for web hosting companies</td></tr>
</table>

### Websites and learning

<table>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-drupal.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-drupal"><b>Drupal</b></a></td><td width="660">Open-source CMS for complex, structured websites</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-joomla.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-joomla"><b>Joomla</b></a></td><td width="660">Open-source CMS for websites and portals</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-moodle.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/moodle-local_kwtsms"><b>Moodle</b></a></td><td width="660">Open-source learning platform for schools, universities and training</td></tr>
</table>

### Automation and spreadsheets

<table>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-n8n.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-n8n"><b>n8n</b></a></td><td width="660">Workflow automation tool you can self-host</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-powerautomate.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-mspowerauto"><b>Power Automate</b></a></td><td width="660">Microsoft's service for automated workflows between apps</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-googlesheets.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-googlesheets"><b>Google Sheets</b></a></td><td width="660">Google's online spreadsheets</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-excel.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-msexcel"><b>Microsoft Excel</b></a></td><td width="660">Microsoft's spreadsheet app</td></tr>
</table>

### App backends, frameworks and sign-in

<table>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-laravel.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-laravel"><b>Laravel</b></a></td><td width="660">PHP web framework</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-laravel.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-notification-channel"><b>Laravel Notifications</b></a></td><td width="660">The notification system built into Laravel</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-firebase.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-firebase"><b>Firebase</b></a></td><td width="660">Google's app backend: database, sign-in and cloud functions</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-supabase.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-supabase"><b>Supabase</b></a></td><td width="660">Open-source Postgres backend with sign-in and edge functions</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-convex.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-convex"><b>Convex</b></a></td><td width="660">Reactive backend for TypeScript apps</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-betterauth.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-better-auth"><b>Better Auth</b></a></td><td width="660">Authentication library for TypeScript apps</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-nextjs.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-nextjs-otp"><b>Next.js</b></a></td><td width="660">React framework for web apps</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-clerk.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-auth-relay"><b>Clerk and Neon Auth</b></a></td><td width="660">Hosted user sign-in services</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-nodejs.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-otp"><b>Node.js, Bun and Workers</b></a></td><td width="660">JavaScript runtimes for servers and the edge</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-keycloak.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-keycloak"><b>Keycloak</b></a></td><td width="660">Open-source identity and access management server</td></tr>
</table>

### Monitoring and smart home

<table>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-zabbix.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-zabbix"><b>Zabbix</b></a></td><td width="660">Open-source monitoring for networks, servers and applications</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-nagios.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-nagios"><b>Nagios and Icinga</b></a></td><td width="660">Open-source infrastructure monitoring and alerting</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-prometheus.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-prometheus"><b>Prometheus</b></a></td><td width="660">Open-source metrics and alerting toolkit</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-homeassistant.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-homeassistant"><b>Home Assistant</b></a></td><td width="660">Open-source home automation platform</td></tr>
</table>

### AI assistants and the terminal

For AI tools, start with the MCP server (no install, test mode by default, the AI never sees your password) and add
the kwtSMS skill next to it. Use the CLI for terminal agents, scripts and cron.

<table>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-mcp.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-mcp"><b>MCP</b></a></td><td width="660">Open protocol that connects AI assistants to outside tools</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-claude.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-ai"><b>Claude Code</b></a></td><td width="660">Anthropic's coding assistant for the terminal</td></tr>
<tr><td width="44" align="center"><img src="https://raw.githubusercontent.com/kwtsms/.github/main/profile/assets/icons/s-terminal.png" width="32" height="32" alt=""></td><td width="250"><a href="https://github.com/kwtsms/kwtsms-cli"><b>Your terminal</b></a></td><td width="660">Shell scripts, cron jobs and CI pipelines</td></tr>
</table>

---

<p align="center">
  Missing your platform? <a href="https://www.kwtsms.com/support.html">Tell us</a>, or build on the <a href="https://www.kwtsms.com/api-documentation.html">API</a> with one of the libraries above.<br>
  <sub>kwtSMS is a service of BoxLink, Kuwait.</sub>
</p>
