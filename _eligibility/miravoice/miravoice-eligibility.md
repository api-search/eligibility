---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent and warrant that you have authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age. If you are under 18 years of age, you may not use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited content and uses
    text: 'Prohibited uses include but are not limited to: Criminal activities Malicious, fraudulent, or illegal purposes'
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
name: Miravoice
provenance_date: '2026-11-10'
provider_name: Miravoice
provider_slug: miravoice
slug: miravoice-eligibility
source_date: '2026-11-10'
source_filename: miravoice-eligibility.yml
source_heading: Eligibility
source_page: https://www.miravoice.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Miravoice\naid: miravoice\nurl: https://www.miravoice.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent and warrant that you have authority to\n    bind that organization to these Terms\nrestricted_uses:\n- summary: Unlawful or prohibited content and uses\n  text: 'Prohibited uses include but are not limited to: Criminal activities Malicious, fraudulent, or illegal purposes'\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age. If you are under 18 years of age, you may\n    not use the Service.\n"
source_yaml_url: https://artifacts.apis.io/miravoice/eligibility/miravoice-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Miravoice's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Voice
- Surveys
- Artificial Intelligence
- Automation
---
