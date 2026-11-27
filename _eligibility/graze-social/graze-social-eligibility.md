---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Services from jurisdictions where such access is illegal is prohibited.
  entity_types:
  - text: You must be a legal adult to use the Services.
    type: individual
  - text: If you access the Services on behalf of a company or other entity (“ Entity ”), you represent, agree, and warrant that you are authorized to act on behalf of the Entity and to bind such Entity to these Terms.
    type: business
  minimum_age:
    text: you must be at least 18 years old or the legal age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Access from jurisdictions where illegal
    text: Use of the Services from jurisdictions where such access is illegal is prohibited.
  - summary: Illegal or harmful use
    text: Is illegal, harmful, abusive, defamatory, harassing, or discriminatory
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
name: Graze Social
provenance_date: '2026-11-09'
provider_name: Graze Social
provider_slug: graze-social
slug: graze-social-eligibility
source_date: '2026-11-09'
source_filename: graze-social-eligibility.yml
source_heading: Eligibility
source_page: https://www.graze.social/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Graze Social\naid: graze-social\nurl: https://www.graze.social/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Services from jurisdictions where such access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: You must be a legal adult to use the Services.\n- type: business\n  text: If you access the Services on behalf of a company or other entity (“ Entity ”), you represent, agree, and\n    warrant that you are authorized to act on behalf of the Entity and to bind such Entity to these Terms.\nrestricted_uses:\n- summary: Access from\
  \ jurisdictions where illegal\n  text: Use of the Services from jurisdictions where such access is illegal is prohibited.\n- summary: Illegal or harmful use\n  text: Is illegal, harmful, abusive, defamatory, harassing, or discriminatory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old or the legal age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/graze-social/eligibility/graze-social-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Graze Social's own page on 2026-11-09.
synthetic: false
tags:
- Social
- FeedBuilder
- Bluesky
- Software-as-a-Service
---
