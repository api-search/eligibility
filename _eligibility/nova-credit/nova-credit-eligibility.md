---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to our Services from countries or territories, or by individuals, where access is illegal is prohibited.
  entity_types:
  - text: you certify that you are of the age of majority in your local jurisdiction
    type: individual
  minimum_age:
    text: you certify that you are of the age of majority in your local jurisdiction
    value: age of majority
  restricted_uses:
  - summary: Impersonation or false pretenses
    text: perform any fraudulent activity including impersonating any person or entity, claiming a false affiliation
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: We reserve the right to reject your registration or subscription for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nova Credit
provenance_date: '2026-11-10'
provider_name: Nova Credit
provider_slug: nova-credit
slug: nova-credit-eligibility
source_date: '2026-11-10'
source_filename: nova-credit-eligibility.yml
source_heading: Eligibility
source_page: https://www.novacredit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nova Credit\naid: nova-credit\nurl: https://www.novacredit.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to our Services from countries or territories, or by individuals, where access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: you certify that you are of the age of majority in your local jurisdiction\nrestricted_uses:\n- summary: Impersonation or false pretenses\n  text: perform any fraudulent activity including impersonating any person or entity, claiming a false affiliation\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ false\n  text: We reserve the right to reject your registration or subscription for any reason.\nminimum_age:\n  value: age of majority\n  text: you certify that you are of the age of majority in your local jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/nova-credit/eligibility/nova-credit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Nova Credit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Credit Data
- Consumer Credit
- Credit Bureau
- Income Verification
- Underwriting
- Fintech
- Financial Services
- Lending
- Cash Flow Underwriting
- Identity
---
