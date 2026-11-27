---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a United States embargo, or that has been designated by the United States government as a "terrorist supporting" country
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: to any person or entity on any United States export control list
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MontyCloud
provenance_date: '2026-11-10'
provider_name: MontyCloud
provider_slug: montycloud
slug: montycloud-eligibility
source_date: '2026-11-10'
source_filename: montycloud-eligibility.yml
source_heading: Eligibility
source_page: https://montycloud.com/wp-content/uploads/2025/10/2026.08-MontyCloud-Subscription-Terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MontyCloud\naid: montycloud\nurl: https://montycloud.com/wp-content/uploads/2025/10/2026.08-MontyCloud-Subscription-Terms.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a United States embargo, or that has been designated\n    by the United States government as a \"terrorist supporting\" country\nentity_types: []\nrestricted_uses:\n- summary: Export control restrictions\n  text: to any person or entity on any United States export control list\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/montycloud/eligibility/montycloud-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from MontyCloud's own page on 2026-11-10.
synthetic: false
tags:
- Cloud
- Cloud Operations
- Amazon Web Services
- Managed Service Providers
- Governance
- Compliance
- Cost Management
- Artificial Intelligence
- Agents
- MCP
- Multi-Tenant
- Infrastructure
---
