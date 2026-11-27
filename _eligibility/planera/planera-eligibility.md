---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 13 years of age
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable
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
name: Planera
provenance_date: '2026-11-10'
provider_name: Planera
provider_slug: planera
slug: planera-eligibility
source_date: '2026-11-10'
source_filename: planera-eligibility.yml
source_heading: Eligibility
source_page: https://www.planera.io/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Planera\naid: planera\nurl: https://www.planera.io/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: is dangerous, harmful, fraudulent, deceptive, threatening,\
  \ harassing, defamatory, obscene, or otherwise\n    objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/planera/eligibility/planera-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Planera's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction Technology
- Construction
- Scheduling
- Project Management
- Preconstruction
- CPM
---
