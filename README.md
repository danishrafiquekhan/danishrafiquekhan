### Danish Khan

I work in support/infra roles and I'm moving toward detection engineering and identity security. Right now that means Microsoft identity (Entra ID, Sentinel), some AWS, and enough Terraform to not be dangerous with it.

This account is where I keep the actual work instead of just talking about it — Sigma rules, a self-hosted SIEM I run locally, attack simulations, some Terraform labs. Most of it is unfinished on purpose; I'd rather show real progress than a repo that looks done and isn't.

LinkedIn: https://www.linkedin.com/in/danishrafiquekhan/
Certs so far: SC-100 / SC-300 / SC-200 / AZ-104 / MD-102 / SC-900 / ITIL 4

What I'm poking at at the moment:
- writing Sigma rules and converting them to KQL for Sentinel
- running Wazuh + TheHive/Cortex locally instead of paying for cloud versions to practice on
- Terraform on Azure, working through the Associate material
- trying to close the AWS-side gap a few job postings called out

Repos worth looking at:
- `detection-engineering` — the Sigma/KQL rules, mapped to ATT&CK
- `atomic-red-team-validation` — running actual attacks in an isolated VM to see if my rules catch them
- `sentinel-soar-playbooks` — automation, mostly TheHive/Cortex right now since that's free
- `aws-identity-detection` — IAM privilege escalation detection, AWS side
- `intune-endpoint-health-platform` — an Intune project I built at work-adjacent scale, migrating it in
- `terraform-labs` — Associate study exercises, one folder per topic

None of this is production work and none of the data in here is real — sanitised or made up on purpose.
