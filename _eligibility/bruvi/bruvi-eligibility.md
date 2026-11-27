---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region or jurisdiction.
  entity_types:
  - text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    type: individual
  - text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
    type: business
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal or harmful conduct
    text: You may not use our products for any illegal or unauthorized purpose
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
name: Bruvi
provenance_date: '2026-11-09'
provider_name: Bruvi
provider_slug: bruvi
slug: bruvi-eligibility
source_date: '2026-11-09'
source_filename: bruvi-eligibility.yml
source_heading: Eligibility
source_page: https://bruvi.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bruvi\naid: bruvi\nurl: https://bruvi.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region or jurisdiction.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\n- type: business\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n  \
  \  resellers or distributors.\nrestricted_uses:\n- summary: Illegal or harmful conduct\n  text: You may not use our products for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/bruvi/eligibility/bruvi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bruvi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coffee
- Subscription
- Sustainability
- E-Commerce
---
