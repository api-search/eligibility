---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This website is intended only for use by adult residents of the United States (U.S.) and its territories.
  entity_types:
  - text: This website is intended only for use by adult residents of the United States (U.S.) and its territories.
    type: individual
  minimum_age:
    text: This website is intended only for use by adult residents of the United States (U.S.) and its territories.
    value: adult
  restricted_uses:
  - summary: no medical advice or services
    text: This website does not provide medical services or advice.
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
name: Korro Bio
provenance_date: '2026-11-09'
provider_name: Korro Bio
provider_slug: korro-bio
slug: korro-bio-eligibility
source_date: '2026-11-09'
source_filename: korro-bio-eligibility.yml
source_heading: Eligibility
source_page: https://korrobio.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Korro Bio\naid: korro-bio\nurl: https://korrobio.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This website is intended only for use by adult residents of the United States (U.S.) and its territories.\nentity_types:\n- type: individual\n  text: This website is intended only for use by adult residents of the United States (U.S.) and its territories.\nrestricted_uses:\n- summary: no medical advice or services\n  text: This website does not provide medical services or advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: adult\n  text: This website is intended only for use by adult residents of the United States (U.S.) and its territories.\n"
source_yaml_url: https://artifacts.apis.io/korro-bio/eligibility/korro-bio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Korro Bio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- RNA Editing
- Genetic Medicine
- Drug Discovery
- Life Sciences
- Clinical Trials
- Rare Disease
- Research
---
