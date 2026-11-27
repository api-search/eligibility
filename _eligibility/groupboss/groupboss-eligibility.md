---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual you shall be at least 18 years of age.
    type: individual
  minimum_age:
    text: If you are an individual you shall be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: You hereby acknowledge that you shall use the Service solely for lawful purposes and complying with the Agreement.
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
name: Groupboss
provenance_date: '2026-11-09'
provider_name: Groupboss
provider_slug: groupboss
slug: groupboss-eligibility
source_date: '2026-11-09'
source_filename: groupboss-eligibility.yml
source_heading: Eligibility
source_page: https://groupboss.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Groupboss\naid: groupboss\nurl: https://groupboss.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual you shall be at least 18 years of age.\nrestricted_uses:\n- summary: Lawful use only\n  text: You hereby acknowledge that you shall use the Service solely for lawful purposes and complying with the\n    Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are an individual you shall be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/groupboss/eligibility/groupboss-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Groupboss's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Lead Generation
- Marketing
- Marketing Automation
- Email Marketing
- CRM
- Social Media
- Community
- Browser Extension
- Software-as-a-Service
---
