---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users apply to be prescreened for participation in a clinical study by completing an application form on the Site.
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering. In addition, if you are under 18 years old, you may use the Service, with or without registering, only with the express consent of your parent or guardian
    value: '18'
  restricted_uses:
  - summary: Competitors
    text: By viewing, using, or accessing the Service, you represent and warrant that you are not a competitor of Leapcure or any Leapcure Affiliate
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
name: Leapcure
provenance_date: '2026-11-09'
provider_name: Leapcure
provider_slug: leapcure
slug: leapcure-eligibility
source_date: '2026-11-09'
source_filename: leapcure-eligibility.yml
source_heading: Eligibility
source_page: https://leapcure.com/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leapcure\naid: leapcure\nurl: https://leapcure.com/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users apply to be prescreened for participation in a clinical study by completing an application form on\n    the Site.\nrestricted_uses:\n- summary: Competitors\n  text: By viewing, using, or accessing the Service, you represent and warrant that you are not a competitor of\n    Leapcure or any Leapcure Affiliate\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n    In addition, if you are under 18 years old, you may use the Service, with or without registering, only with\n    the express consent of your parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/leapcure/eligibility/leapcure-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Leapcure's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Clinical Trials
- Patient Recruitment
- Healthcare
- Blog
- content-api
- WordPress
---
