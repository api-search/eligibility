---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended solely for corporations and persons aged 18 or older.
    type: business
  - text: By accessing our Service as an individual you represent and warrant that you are aged 18 or older.
    type: individual
  minimum_age:
    text: The Service is intended solely for corporations and persons aged 18 or older.
    value: '18'
  restricted_uses:
  - summary: No promotion of unlawful gambling
    text: You shall not promote or facilitate unlawful online gambling or disruptive commercial messages or advertisements.
  - summary: No syndicating or charging for access
    text: You shall not syndicate or otherwise charge a fee for access to the Service.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: we reserve the right at our discretion to reject applications to use our Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Legalesign
provenance_date: '2026-11-09'
provider_name: Legalesign
provider_slug: legalesign
slug: legalesign-eligibility
source_date: '2026-11-09'
source_filename: legalesign-eligibility.yml
source_heading: Eligibility
source_page: https://legalesign.com/opn/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Legalesign\naid: legalesign\nurl: https://legalesign.com/opn/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended solely for corporations and persons aged 18 or older.\n- type: individual\n  text: By accessing our Service as an individual you represent and warrant that you are aged 18 or older.\nrestricted_uses:\n- summary: No promotion of unlawful gambling\n  text: You shall not promote or facilitate unlawful online gambling or disruptive commercial messages or advertisements.\n- summary: No syndicating or\
  \ charging for access\n  text: You shall not syndicate or otherwise charge a fee for access to the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: we reserve the right at our discretion to reject applications to use our Service\nminimum_age:\n  value: '18'\n  text: The Service is intended solely for corporations and persons aged 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/legalesign/eligibility/legalesign-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Legalesign's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Signature
- Automation
- Document Management
---
