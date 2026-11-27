---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: you as an individual provided that you are at least 18 years of age or otherwise have the requisite capacity to contract under applicable law
    type: individual
  minimum_age:
    text: are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No competing use
    text: are not a competitor of BenchPrep or are not using the Services for reasons that are in competition with BenchPrep
  - summary: No use on behalf of others
    text: You may not use the Services (i) on behalf of or in service to other parties other than for the Permitted Purpose
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: BenchPrep has sole discretion in determining whether to accept or refuse your request for a subscription to the Website
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BenchPrep
provenance_date: '2026-11-09'
provider_name: BenchPrep
provider_slug: benchprep
slug: benchprep-eligibility
source_date: '2026-11-09'
source_filename: benchprep-eligibility.yml
source_heading: Eligibility
source_page: https://www.benchprep.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BenchPrep\naid: benchprep\nurl: https://www.benchprep.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: you as an individual provided that you are at least 18 years of age or otherwise have the requisite capacity\n    to contract under applicable law\nrestricted_uses:\n- summary: No competing use\n  text: are not a competitor of BenchPrep or are not using the Services for reasons that are in competition with\n    BenchPrep\n- summary: No\
  \ use on behalf of others\n  text: You may not use the Services (i) on behalf of or in service to other parties other than for the Permitted\n    Purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: BenchPrep has sole discretion in determining whether to accept or refuse your request for a subscription\n    to the Website\nminimum_age:\n  value: '18'\n  text: are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/benchprep/eligibility/benchprep-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BenchPrep's own page on 2026-11-09.
synthetic: false
tags:
- Company
- LMS
- Education
- Training
- Software-as-a-Service
---
