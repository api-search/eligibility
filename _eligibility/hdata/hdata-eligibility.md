---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Website for use only by persons located in the United States.
  entity_types:
  - text: The Website is offered and available to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
    type: individual
  - text: If you are visiting or using this Website on behalf of your employer, you represent and warrant that you are duly authorized to enter into and comply with these Terms of Use and to bind your employer accordingly.
    type: business
  minimum_age:
    text: The Website is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Service bureau or outsourcing use
    text: You must not access or use any part of the Website or any services or materials available through the Website for outsourcing for others or as part of a service bureau business
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
name: HData
provenance_date: '2026-11-09'
provider_name: HData
provider_slug: hdata
slug: hdata-eligibility
source_date: '2026-11-09'
source_filename: hdata-eligibility.yml
source_heading: Eligibility
source_page: https://www.hdata.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HData\naid: hdata\nurl: https://www.hdata.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: The Website is offered and available to users who are 18 years of age or older and reside in the United\n    States or any of its territories or possessions.\n- type: business\n  text: If you are visiting or using this Website on behalf of your employer, you represent and warrant that you\n    are duly authorized to enter into and comply with these Terms\
  \ of Use and to bind your employer accordingly.\nrestricted_uses:\n- summary: Service bureau or outsourcing use\n  text: You must not access or use any part of the Website or any services or materials available through the Website\n    for outsourcing for others or as part of a service bureau business\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/hdata/eligibility/hdata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from HData's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Regulatory
- Utilities
- Regulatory Intelligence
- Analytics
- Artificial Intelligence
- Compliance
- FERC
- Data
---
