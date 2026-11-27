---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it on behalf of an organisation, you agree on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Impersonation or misrepresentation
    text: impersonate anyone or misrepresent your affiliation with any person or organisation;
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
name: Gain Security
provenance_date: '2026-11-09'
provider_name: Gain Security
provider_slug: gain-security
slug: gain-security-eligibility
source_date: '2026-11-09'
source_filename: gain-security-eligibility.yml
source_heading: Eligibility
source_page: https://gain.security/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gain Security\naid: gain-security\nurl: https://gain.security/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it on behalf of an organisation, you agree on its behalf.\nrestricted_uses:\n- summary: Impersonation or misrepresentation\n  text: impersonate anyone or misrepresent your affiliation with any person or organisation;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gain-security/eligibility/gain-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Gain Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Platform
- Threat Detection
- Vulnerability Management
---
