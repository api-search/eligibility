---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If acting for an organisation, you must have authority to do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive or unrelated data
    text: Only submit data you are entitled to share. Do not submit private keys, API keys, passwords, MFA or one-time codes, recovery credentials, payment authorizations, identity documents or unrelated personal or sensitive information through these tools.
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
name: onchaindiligence-com
provenance_date: '2026-11-10'
provider_name: onchaindiligence-com
provider_slug: onchaindiligence-com
slug: onchaindiligence-com-eligibility
source_date: '2026-11-10'
source_filename: onchaindiligence-com-eligibility.yml
source_heading: Eligibility
source_page: https://onchaindiligence.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: onchaindiligence-com\naid: onchaindiligence-com\nurl: https://onchaindiligence.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If acting for an organisation, you must have authority to do so.\nrestricted_uses:\n- summary: Sensitive or unrelated data\n  text: Only submit data you are entitled to share. Do not submit private keys, API keys, passwords, MFA or one-time\n    codes, recovery credentials, payment authorizations, identity documents or unrelated personal or sensitive information\n    through these tools.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onchaindiligence-com/eligibility/onchaindiligence-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from onchaindiligence-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Artificial Intelligence
- Payments
- Reconciliation
- SDK
---
