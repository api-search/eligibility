---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: are intended for use only by residents of the United States, its territories and Puerto Rico.
  entity_types:
  - text: The personalized clinical support, education, advisory, and management services are meant for individuals diagnosed with or predisposed to chronic diseases.
    type: individual
  minimum_age:
    text: By using this Site you represent that you are not less than eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Illegal use
    text: you may not use the Site or the Services where it would be illegal to do so.
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
name: Cecelia Health
provenance_date: '2026-11-09'
provider_name: Cecelia Health
provider_slug: cecelia-health
slug: cecelia-health-eligibility
source_date: '2026-11-09'
source_filename: cecelia-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.ceceliahealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cecelia Health\naid: cecelia-health\nurl: https://www.ceceliahealth.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: are intended for use only by residents of the United States, its territories and Puerto Rico.\nentity_types:\n- type: individual\n  text: The personalized clinical support, education, advisory, and management services are meant for individuals\n    diagnosed with or predisposed to chronic diseases.\nrestricted_uses:\n- summary: Illegal use\n  text: you may not use the Site or the Services where it would be illegal to do so.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using this Site you represent that you are not less than eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/cecelia-health/eligibility/cecelia-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cecelia Health's own page on 2026-11-09.
synthetic: false
tags:
- Virtual Care
- Cardiometabolic Care
- GLP‑1 Support
- Employer Solutions
- Pharma Patient Support
---
