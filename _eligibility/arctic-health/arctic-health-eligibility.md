---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Website on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or fraudulent use
    text: Use the Website for any illegal purpose, including healthcare fraud or misrepresentation
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
name: Arctic Health
provenance_date: '2026-11-09'
provider_name: Arctic Health
provider_slug: arctic-health
slug: arctic-health-eligibility
source_date: '2026-11-09'
source_filename: arctic-health-eligibility.yml
source_heading: Eligibility
source_page: https://arctic.health/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arctic Health\naid: arctic-health\nurl: https://arctic.health/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Website on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms.\nrestricted_uses:\n- summary: No illegal or fraudulent use\n  text: Use the Website for any illegal purpose, including healthcare fraud or misrepresentation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arctic-health/eligibility/arctic-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Arctic Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Credentialing
- Provider Enrollment
- Payer Enrollment
- Health Insurance
- Revenue Cycle Management
- Artificial Intelligence
---
