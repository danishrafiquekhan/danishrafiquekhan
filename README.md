**Danish Khan**

I work in support/infra roles and I am moving toward detection engineering and identity security. Right now that means Microsoft identity (Entra ID, Sentinel), some AWS, and enough Terraform to not be dangerous with it.

This account is where I keep the actual work instead of just talking about it: Sigma rules, a self-hosted SIEM I run locally, attack simulations, some Terraform labs. Most of it is unfinished on purpose; I would rather show real progress than a repo that looks done and is not.

LinkedIn: https://www.linkedin.com/in/danishrafiquekhan/
Certs so far: SC-100 / SC-300 / SC-200 / AZ-104 / MD-102 / SC-900 / ITIL 4

**Start here**

[`security-lab-notes`](https://github.com/danishrafiquekhan/security-lab-notes) — the complete reference for how everything below actually works: every tool, why it was chosen, what's paid vs free, real bugs hit building it. Read this first if you want the full picture instead of piecing it together repo by repo.

**Detection engineering**
- [`detection-engineering`](https://github.com/danishrafiquekhan/detection-engineering) — Sigma/KQL rules mapped to ATT&CK, plus a self-hosted Wazuh lab actually ingesting real live traffic from six sources (a Cloudflare site, MySQL, Suricata, Auth0, LocalStack, and a Cowrie SSH honeypot) and firing real alerts, not just fixture tests — with a live status dashboard to watch it happen

**Cloud & infrastructure as code**
- [`terraform-labs`](https://github.com/danishrafiquekhan/terraform-labs) — Associate-level study exercises, one folder per topic; the Azure exercises are syntax-validated only (never applied against a real subscription, documented honestly), and a separate exercise proves a real `apply`/`destroy` cycle against LocalStack instead

**SOAR & automation**
- [`sentinel-soar-playbooks`](https://github.com/danishrafiquekhan/sentinel-soar-playbooks) — Logic App playbook designs (enrich a sign-in alert, disable a compromised user, isolate an infected device); designs, not deployments — no real Sentinel tenant exists yet

**Identity & attack validation**
- [`aws-identity-detection`](https://github.com/danishrafiquekhan/aws-identity-detection) — IAM privilege escalation detection, tested against LocalStack
- [`atomic-red-team-validation`](https://github.com/danishrafiquekhan/atomic-red-team-validation) — case studies validating detections against real attack simulations on an isolated Windows VM; two techniques run for real so far (T1059.001 PowerShell, T1078.004 Cloud Accounts adapted via LocalStack), both caught with correct MITRE mapping

None of this is production work and none of the data in here is real, sanitised or made up on purpose.
