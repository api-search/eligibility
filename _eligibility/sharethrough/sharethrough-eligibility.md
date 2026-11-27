---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Publisher is an individual, Publisher represents and warrants that it was at least eighteen (18) years of age on the Effective Date of this Agreement.
    type: individual
  minimum_age:
    text: If Publisher is an individual, Publisher represents and warrants that it was at least eighteen (18) years of age on the Effective Date of this Agreement.
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: Publisher shall comply with all export control laws and regulations, such as, but not limited to laws administered by OFAC
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Publisher’s use of the Platform is subject to prior approval by Sharethrough and is limited to previously approved Sites.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sharethrough
provenance_date: '2026-11-10'
provider_name: Sharethrough
provider_slug: sharethrough
slug: sharethrough-eligibility
source_date: '2026-11-10'
source_filename: sharethrough-eligibility.yml
source_heading: Eligibility
source_page: https://www.sharethrough.com/publisher-platform-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sharethrough\naid: sharethrough\nurl: https://www.sharethrough.com/publisher-platform-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If Publisher is an individual, Publisher represents and warrants that it was at least eighteen (18) years\n    of age on the Effective Date of this Agreement.\nrestricted_uses:\n- summary: Export control and sanctions\n  text: Publisher shall comply with all export control laws and regulations, such as, but not limited to laws administered\n    by OFAC\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: true\n  text: Publisher’s use of the Platform is subject to prior approval by Sharethrough and is limited to previously\n    approved Sites.\nminimum_age:\n  value: '18'\n  text: If Publisher is an individual, Publisher represents and warrants that it was at least eighteen (18) years\n    of age on the Effective Date of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/sharethrough/eligibility/sharethrough-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Sharethrough's own page on 2026-11-10.
synthetic: false
tags:
- Native Advertising
- Programmatic Advertising
- Supply Side Platform
- DSP
- OpenRTB
- Ad Exchange
- Header Bidding
- CTV
- Sustainability
---
