---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Adult content sites
    text: The block may not be placed on sites with adult content (pornography, sexual services, erotic or fetish communities)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A site starts working after you prove control of its domain (meta tag, file or DNS record).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BarterBanner
provenance_date: '2026-11-09'
provider_name: BarterBanner
provider_slug: barterbanner-com
slug: barterbanner-com-eligibility
source_date: '2026-11-09'
source_filename: barterbanner-com-eligibility.yml
source_heading: Eligibility
source_page: https://barterbanner.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BarterBanner\naid: barterbanner-com\nurl: https://barterbanner.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Adult content sites\n  text: The block may not be placed on sites with adult content (pornography, sexual services, erotic or fetish\n    communities)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A site starts working after you prove control of its domain (meta tag, file or DNS record).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/barterbanner-com/eligibility/barterbanner-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from BarterBanner's own page on 2026-11-09.
synthetic: false
tags:
- Networks
- Publishing
- ContentExchange
- Multi-language
---
