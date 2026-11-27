---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: By accessing or using our Services, you affirm that you are of legal age and have the authority to enter into these Terms.
    value: null
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
name: Ribbon
provenance_date: '2026-11-10'
provider_name: Ribbon
provider_slug: ribbon
slug: ribbon-eligibility
source_date: '2026-11-10'
source_filename: ribbon-eligibility.yml
source_heading: Eligibility
source_page: https://www.ribbon.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ribbon\naid: ribbon\nurl: https://www.ribbon.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By accessing or using our Services, you affirm that you are of legal age and have the authority to enter\n    into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/ribbon/eligibility/ribbon-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Ribbon's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Payments
- Automation
- Banking
---
