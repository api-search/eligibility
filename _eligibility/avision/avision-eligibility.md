---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service may not be appropriate or available for use in some non-U.S. jurisdictions. We may limit the Service's availability at any time, in whole or in part, to any person, geographic area or jurisdiction that we choose.
  entity_types:
  - text: You must be at least 16 years of age to use the Service.
    type: individual
  - text: If you are using our Services on behalf of a business, that business accepts these terms.
    type: business
  minimum_age:
    text: You must be at least 16 years of age to use the Service.
    value: '16'
  restricted_uses:
  - summary: No manned aircraft or safety-critical use
    text: The Service is not intended for use in, and you may not use the Service for, the operation of manned aircraft navigation or communication systems, air traffic control systems, life support machines or other equipment in which the failure of the Service could lead to death, personal injury, or severe physical or environmental damage.
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
name: Avision
provenance_date: '2026-11-09'
provider_name: Avision
provider_slug: avision
slug: avision-eligibility
source_date: '2026-11-09'
source_filename: avision-eligibility.yml
source_heading: Eligibility
source_page: https://avision.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avision\naid: avision\nurl: https://avision.io/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service may not be appropriate or available for use in some non-U.S. jurisdictions. We may limit the\n    Service's availability at any time, in whole or in part, to any person, geographic area or jurisdiction that\n    we choose.\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age to use the Service.\n- type: business\n  text: If you are using our Services on behalf of a business, that business accepts these terms.\nrestricted_uses:\n\
  - summary: No manned aircraft or safety-critical use\n  text: The Service is not intended for use in, and you may not use the Service for, the operation of manned aircraft\n    navigation or communication systems, air traffic control systems, life support machines or other equipment in\n    which the failure of the Service could lead to death, personal injury, or severe physical or environmental damage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/avision/eligibility/avision-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Avision's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Drones
- UAS
- UTM
- U-space
- Airspace
- LAANC
- B4UFLY
- FAA
- Aviation
- Public Safety
- Advanced Air Mobility
- BVLOS
---
