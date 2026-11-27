---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and capable of forming a binding contract to use Citerank.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and capable of forming a binding contract to use Citerank.
    value: '18'
  restricted_uses:
  - summary: No children's data
    text: Submit personal data of children under 13, or under the applicable age of digital consent where you are
  - summary: No Protected Health Information
    text: Submit Protected Health Information, as defined by the HIPAA Privacy Rule (45 C.F.R. §160.103)
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
name: Citerank
provenance_date: '2026-11-09'
provider_name: Citerank
provider_slug: citerankscore-com
slug: citerankscore-com-eligibility
source_date: '2026-11-09'
source_filename: citerankscore-com-eligibility.yml
source_heading: Eligibility
source_page: https://citerankscore.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Citerank\naid: citerankscore-com\nurl: https://citerankscore.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and capable of forming a binding contract to use Citerank.\nrestricted_uses:\n- summary: No children's data\n  text: Submit personal data of children under 13, or under the applicable age of digital consent where you are\n- summary: No Protected Health Information\n  text: Submit Protected Health Information, as defined by the HIPAA Privacy Rule (45 C.F.R. §160.103)\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and capable of forming a binding contract to use Citerank.\n"
source_yaml_url: https://artifacts.apis.io/citerankscore-com/eligibility/citerankscore-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Citerank's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Search
- Visibility
- Platform
- SEO
- Company
---
