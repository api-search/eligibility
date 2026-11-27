---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Clearbrief makes no representations that the Clearbrief Services are appropriate or available for use in other locations. You may not use the Clearbrief Services if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: an individual subscriber, customer, member, or user of at least 18 years of age
    type: individual
  - text: a single Clearbrief, organization, or entity
    type: business
  minimum_age:
    text: THE CLEARBRIEF SERVICES ARE NOT AVAILABLE TO PERSONS UNDER 18 YEARS OF AGE
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: Use the Clearbrief Services for any purpose that is unlawful or is otherwise prohibited by these Terms
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
name: Clearbrief
provenance_date: '2026-11-09'
provider_name: Clearbrief
provider_slug: clearbrief
slug: clearbrief-eligibility
source_date: '2026-11-09'
source_filename: clearbrief-eligibility.yml
source_heading: Eligibility
source_page: https://clearbrief.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clearbrief\naid: clearbrief\nurl: https://clearbrief.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Clearbrief makes no representations that the Clearbrief Services are appropriate or available for use in\n    other locations. You may not use the Clearbrief Services if you are a resident of a country embargoed by the\n    United States, or are a foreign person or entity blocked or denied by the United States government.\nentity_types:\n- type: individual\n  text: an individual subscriber, customer, member, or user of at least 18 years of age\n- type: business\n  text:\
  \ a single Clearbrief, organization, or entity\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: Use the Clearbrief Services for any purpose that is unlawful or is otherwise prohibited by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: THE CLEARBRIEF SERVICES ARE NOT AVAILABLE TO PERSONS UNDER 18 YEARS OF AGE\n"
source_yaml_url: https://artifacts.apis.io/clearbrief/eligibility/clearbrief-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Clearbrief's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Artificial Intelligence
- Document Automation
- CitationChecking
- Microsoft Word
---
