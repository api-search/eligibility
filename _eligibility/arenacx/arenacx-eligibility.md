---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: ArenaCX operates from the United States, but the Sites may be accessible internationally.
  entity_types:
  - text: The Sites are intended principally for business and professional audiences, including organizations seeking outsourcing or related services
    type: business
  - text: public-sector organizations, and their respective personnel and representatives.
    type: government
  minimum_age:
    text: You must be at least eighteen (18) years of age, or the age of legal majority where you reside if higher, to affirmatively agree to these Terms or submit a business inquiry through a Site.
    value: '18'
  restricted_uses:
  - summary: Use only in compliance with law
    text: You must use the Sites in compliance with applicable law, including applicable intellectual-property, privacy, cybersecurity, anti-spam, export-control, and economic-sanctions laws.
  - summary: No submission of regulated data via public forms
    text: 'Without ArenaCX’s express prior authorization and an ArenaCX-approved secure transmission method, you must not submit through a public Site form: (a) Social Security numbers or comparable national identification numbers'
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
name: ArenaCX
provenance_date: '2026-11-09'
provider_name: ArenaCX
provider_slug: arenacx
slug: arenacx-eligibility
source_date: '2026-11-09'
source_filename: arenacx-eligibility.yml
source_heading: Eligibility
source_page: https://arenacx.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ArenaCX\naid: arenacx\nurl: https://arenacx.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: ArenaCX operates from the United States, but the Sites may be accessible internationally.\nentity_types:\n- type: business\n  text: The Sites are intended principally for business and professional audiences, including organizations seeking\n    outsourcing or related services\n- type: government\n  text: public-sector organizations, and their respective personnel and representatives.\nrestricted_uses:\n- summary: Use only in compliance with law\n  text: You must use the\
  \ Sites in compliance with applicable law, including applicable intellectual-property, privacy,\n    cybersecurity, anti-spam, export-control, and economic-sanctions laws.\n- summary: No submission of regulated data via public forms\n  text: 'Without ArenaCX’s express prior authorization and an ArenaCX-approved secure transmission method, you must\n    not submit through a public Site form: (a) Social Security numbers or comparable national identification numbers'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age, or the age of legal majority where you reside if higher,\n    to affirmatively agree to these Terms or submit a business inquiry through a Site.\n"
source_yaml_url: https://artifacts.apis.io/arenacx/eligibility/arenacx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from ArenaCX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- BPO
- Customer Operations
- Platform
- Managed Service
---
