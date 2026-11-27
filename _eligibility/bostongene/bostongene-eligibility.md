---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-controlled content
    text: By downloading the Content, you are expressly agreeing that you are not in a country where such export is prohibited or are a person or entity for which such export is prohibited.
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
name: BostonGene
provenance_date: '2026-11-09'
provider_name: BostonGene
provider_slug: bostongene
slug: bostongene-eligibility
source_date: '2026-11-09'
source_filename: bostongene-eligibility.yml
source_heading: Eligibility
source_page: https://bostongene.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BostonGene\naid: bostongene\nurl: https://bostongene.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims concerning whether the Content may be downloaded, viewed, or be appropriate for use outside\n    of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Export-controlled content\n  text: By downloading the Content, you are expressly agreeing that you are not in a country where such export is\n    prohibited or are a person or entity for which such export is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bostongene/eligibility/bostongene-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from BostonGene's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Precision Medicine
- Genomics
- Bioinformatics
- Artificial Intelligence
- Diagnostics
- Life Sciences
- Clinical Laboratory
---
