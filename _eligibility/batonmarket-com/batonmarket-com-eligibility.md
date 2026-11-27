---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract.
    value: null
  restricted_uses:
  - summary: Prohibited content and conduct
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
name: Baton Market
provenance_date: '2026-11-09'
provider_name: Baton Market
provider_slug: batonmarket-com
slug: batonmarket-com-eligibility
source_date: '2026-11-09'
source_filename: batonmarket-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.baton.com:443/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baton Market\naid: batonmarket-com\nurl: https://www.baton.com:443/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/batonmarket-com/eligibility/batonmarket-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Baton Market's own page on 2026-11-09.
synthetic: false
tags:
- Business Buying
- Business Valuation
---
