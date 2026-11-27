---
claim_count: 1
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
  - summary: Excessive automation and infringement
    text: Prohibited activities include infringement, abuse, security violations and excessive automation.
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
name: MangaTranslate
provenance_date: '2026-11-10'
provider_name: MangaTranslate
provider_slug: mangatranslate
slug: mangatranslate-eligibility
source_date: '2026-11-10'
source_filename: mangatranslate-eligibility.yml
source_heading: Eligibility
source_page: https://www.mangatranslate.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MangaTranslate\naid: mangatranslate\nurl: https://www.mangatranslate.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Excessive automation and infringement\n  text: Prohibited activities include infringement, abuse, security violations and excessive automation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mangatranslate/eligibility/mangatranslate-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from MangaTranslate's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Translation
- Manga
---
