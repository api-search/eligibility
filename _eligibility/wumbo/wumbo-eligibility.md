---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You must be at least 18 years of age to use the Platform.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Unlawful or privacy-breaching use
    text: anything that would constitute a breach of an individual’s privacy (including uploading private or personal information without an individual's consent)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register on the Platform to access the Platform’s features.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wumbo
provenance_date: '2026-11-10'
provider_name: Wumbo
provider_slug: wumbo
slug: wumbo-eligibility
source_date: '2026-11-10'
source_filename: wumbo-eligibility.yml
source_heading: Eligibility
source_page: https://wumbo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wumbo\naid: wumbo\nurl: https://wumbo.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country that is subject to a U.S. Government embargo, or that\n    has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Platform.\nrestricted_uses:\n- summary: Unlawful or privacy-breaching use\n  text: anything that would constitute a breach of an individual’s privacy (including uploading private or personal\n    information\
  \ without an individual's consent)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register on the Platform to access the Platform’s features.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/wumbo/eligibility/wumbo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Wumbo's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
