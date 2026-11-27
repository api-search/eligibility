---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: TO USE OUR WEBSITE OR ANY OF THE SERVICES, YOU MUST BE AT LEAST 16 YEARS OLD.
    value: '16'
  restricted_uses:
  - summary: Unauthorized targets
    text: You must not use or direct the Services to interact with IPs or Devices for which you are not authorized.
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
name: Beagle Security
provenance_date: '2026-11-09'
provider_name: Beagle Security
provider_slug: beaglesecurity
slug: beaglesecurity-eligibility
source_date: '2026-11-09'
source_filename: beaglesecurity-eligibility.yml
source_heading: Eligibility
source_page: https://beaglesecurity.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beagle Security\naid: beaglesecurity\nurl: https://beaglesecurity.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized targets\n  text: You must not use or direct the Services to interact with IPs or Devices for which you are not authorized.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: TO USE OUR WEBSITE OR ANY OF THE SERVICES, YOU MUST BE AT LEAST 16 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/beaglesecurity/eligibility/beaglesecurity-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Beagle Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- Penetration Testing
- DevSecOps
---
