---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the individual accepting these Terms of Service is accepting on behalf of a business entity or other legal entity, such individual represents that he or she has the authority to bind such business entity or other legal entity and its Affiliates to these Terms of Service
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business purposes only
    text: use the Software for any purpose other than Customer’s internal business purposes
  - summary: Compliance with laws
    text: Customer agrees that it will not use the Software for any purposes prohibited by United States federal or state laws.
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
name: Apprentice
provenance_date: '2026-11-09'
provider_name: Apprentice
provider_slug: apprentice
slug: apprentice-eligibility
source_date: '2026-11-09'
source_filename: apprentice-eligibility.yml
source_heading: Eligibility
source_page: https://www.apprentice.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apprentice\naid: apprentice\nurl: https://www.apprentice.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the individual accepting these Terms of Service is accepting on behalf of a business entity or other\n    legal entity, such individual represents that he or she has the authority to bind such business entity or other\n    legal entity and its Affiliates to these Terms of Service\nrestricted_uses:\n- summary: Internal business purposes only\n  text: use the Software for any purpose other than Customer’s internal\
  \ business purposes\n- summary: Compliance with laws\n  text: Customer agrees that it will not use the Software for any purposes prohibited by United States federal or\n    state laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apprentice/eligibility/apprentice-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Apprentice's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Life Sciences
- Pharmaceuticals
- Manufacturing
- Manufacturing Execution System
- Cloud
- GxP
- Quality
---
