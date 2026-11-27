---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: grants you a non-exclusive, limited, non-transferable, revocable license to use the App solely for personal, private, non-commercial purposes
    type: individual
  minimum_age:
    text: if you are under the age of 13, you must obtain parental consent before creating an account.
    value: '13'
  restricted_uses:
  - summary: Commercial use
    text: Commercial use of the App or its content by any third party is strictly prohibited.
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
name: CoverStar
provenance_date: '2026-11-09'
provider_name: CoverStar
provider_slug: coverstar
slug: coverstar-eligibility
source_date: '2026-11-09'
source_filename: coverstar-eligibility.yml
source_heading: Eligibility
source_page: https://help.coverstar.app/hc/en-us/articles/33484714669332-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoverStar\naid: coverstar\nurl: https://help.coverstar.app/hc/en-us/articles/33484714669332-Terms-of-Service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: grants you a non-exclusive, limited, non-transferable, revocable license to use the App solely for personal,\n    private, non-commercial purposes\nrestricted_uses:\n- summary: Commercial use\n  text: Commercial use of the App or its content by any third party is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: if you are under the age of 13, you must obtain parental consent before creating an account.\n"
source_yaml_url: https://artifacts.apis.io/coverstar/eligibility/coverstar-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CoverStar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social
- Kids
- Safety
- Creative
---
