---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services are not intended for distribution to or use in any country or jurisdiction where such distribution or use would violate local law
  minimum_age:
    text: You must be at least 18 years old to use our Services.
    value: '18'
  restricted_uses:
  - summary: Pornography industry excluded
    text: It is therefore our prerogative to not provide services to that industry at this time.
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
name: Hydrahost
provenance_date: '2026-11-09'
provider_name: Hydrahost
provider_slug: hydrahost
slug: hydrahost-eligibility
source_date: '2026-11-09'
source_filename: hydrahost-eligibility.yml
source_heading: Eligibility
source_page: https://hydrahost.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hydrahost\naid: hydrahost\nurl: https://hydrahost.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Services are not intended for distribution to or use in any country or jurisdiction where such distribution\n    or use would violate local law\nentity_types: []\nrestricted_uses:\n- summary: Pornography industry excluded\n  text: It is therefore our prerogative to not provide services to that industry at this time.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/hydrahost/eligibility/hydrahost-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Hydrahost's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GPU Cloud
- Bare Metal
- Artificial Intelligence
- Machine Learning
- Cloud Infrastructure
- Compute
- Neocloud
---
