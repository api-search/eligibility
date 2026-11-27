---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website and its servers are based in the United States. We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside of the United States.
  entity_types:
  - text: By using the Website, you represent and warrant that you are at least eighteen (18) years old and are otherwise capable of forming a binding contract.
    type: individual
  - text: If you are accessing the Website on behalf of an organization, you represent and warrant that you have the authority to bind that organization to this Agreement.
    type: business
  minimum_age:
    text: you represent and warrant that you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or harmful purposes
    text: Will not use the Website for any unlawful, illegal, fraudulent, or harmful purpose
  - summary: Sensitive personal information
    text: Will not upload, transmit, disclose, or otherwise process any sensitive personal information belonging to its employees, its customers, or any third party
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
name: Flashpoint
provenance_date: '2026-11-09'
provider_name: Flashpoint
provider_slug: flashpoint
slug: flashpoint-eligibility
source_date: '2026-11-09'
source_filename: flashpoint-eligibility.yml
source_heading: Eligibility
source_page: https://flashpoint.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flashpoint\naid: flashpoint\nurl: https://flashpoint.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website and its servers are based in the United States. We make no claims concerning whether the Content\n    may be downloaded, viewed, or be appropriate for use outside of the United States.\nentity_types:\n- type: individual\n  text: By using the Website, you represent and warrant that you are at least eighteen (18) years old and are otherwise\n    capable of forming a binding contract.\n- type: business\n  text: If you are accessing the Website on behalf\
  \ of an organization, you represent and warrant that you have the\n    authority to bind that organization to this Agreement.\nrestricted_uses:\n- summary: Unlawful, fraudulent or harmful purposes\n  text: Will not use the Website for any unlawful, illegal, fraudulent, or harmful purpose\n- summary: Sensitive personal information\n  text: Will not upload, transmit, disclose, or otherwise process any sensitive personal information belonging to\n    its employees, its customers, or any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/flashpoint/eligibility/flashpoint-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Flashpoint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Threat Intelligence
- Cybersecurity
- Security
- Fraud Prevention
- Vulnerability Management
- Dark Web
- Data
- Data Analytics
---
