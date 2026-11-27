---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may not be appropriate or available for use in some jurisdictions. We may limit the Services’ availability at any time, in whole or in part, to any person, geographic area or jurisdiction that we choose.
  entity_types:
  - text: THE END USER (ON BEHALF OF YOURSELF, OR YOUR COMPANY OR ORGANIZATION)
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Fraudulent, unlawful, or disruptive use
    text: Interfere with or disrupt the operation of the Services or the servers or networks used to make the Services available, including by hacking or defacing any portion of the Services
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
name: iECURE
provenance_date: '2026-11-09'
provider_name: iECURE
provider_slug: iecure
slug: iecure-eligibility
source_date: '2026-11-09'
source_filename: iecure-eligibility.yml
source_heading: Eligibility
source_page: https://iecure.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iECURE\naid: iecure\nurl: https://iecure.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services may not be appropriate or available for use in some jurisdictions. We may limit the Services’\n    availability at any time, in whole or in part, to any person, geographic area or jurisdiction that we choose.\nentity_types:\n- type: individual\n  text: THE END USER (ON BEHALF OF YOURSELF, OR YOUR COMPANY OR ORGANIZATION)\nrestricted_uses:\n- summary: Fraudulent, unlawful, or disruptive use\n  text: Interfere with or disrupt the operation of the Services or the\
  \ servers or networks used to make the Services\n    available, including by hacking or defacing any portion of the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/iecure/eligibility/iecure-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from iECURE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Genetic Medicine
- Gene Editing
- Gene Therapy
- Rare Disease
- Clinical Trials
- Life Sciences
- Pharmaceuticals
- content-api
---
