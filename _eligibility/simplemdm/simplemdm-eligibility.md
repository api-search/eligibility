---
api_specs:
- filename: simplemdm-openapi-generated.yml
  format: yaml
  label: SimpleMDM API
  slug: simplemdm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplemdm/openapi/_ae-authored/simplemdm-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    - SD
    served: []
    text: NEITHER THE SITES, SERVICES, NOR ANY SOFTWARE PROVIDED BY THE COMPANY THROUGH THE SERVICES ("SOFTWARE") MAY BE EXPORTED OR RE-EXPORTED (I) INTO THE TERRITORY OF (OR TO A NATIONAL OR RESIDENT OF) CUBA, NORTH KOREA, IRAN, SYRIA, SUDAN
  entity_types:
  - text: Use of the Sites, Services or Software by or for the United States Government is conditioned upon the Government agreeing that the Sites, Services and Software is subject to Restricted Rights
    type: government
  minimum_age:
    text: User represents and warrants that User (a) has the right, authority, and capacity to enter into Terms of Use, (b) will abide by all of the terms and conditions of these Terms of Use, and (c) is at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No ITAR technical data
    text: User shall not provide to Company any technical data as that term is defined in the International Traffic in Arms Regulations
  - summary: No unlawful or malicious input
    text: (e) input, upload, transmit, or otherwise provide to or through the Sites or Services, any information or materials that are unlawful or injurious, or contain, transmit, or activate any harmful or malicious code
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
- SD
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SimpleMDM
provenance_date: '2026-11-10'
provider_name: SimpleMDM
provider_slug: simplemdm
slug: simplemdm-eligibility
source_date: '2026-11-10'
source_filename: simplemdm-eligibility.yml
source_heading: Eligibility
source_page: https://simplemdm.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SimpleMDM\naid: simplemdm\nurl: https://simplemdm.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  - SD\n  text: NEITHER THE SITES, SERVICES, NOR ANY SOFTWARE PROVIDED BY THE COMPANY THROUGH THE SERVICES (\"SOFTWARE\")\n    MAY BE EXPORTED OR RE-EXPORTED (I) INTO THE TERRITORY OF (OR TO A NATIONAL OR RESIDENT OF) CUBA, NORTH KOREA,\n    IRAN, SYRIA, SUDAN\nentity_types:\n- type: government\n  text: Use of the Sites, Services or Software by or for the United States Government is conditioned upon the Government\n    agreeing that the Sites,\
  \ Services and Software is subject to Restricted Rights\nrestricted_uses:\n- summary: No ITAR technical data\n  text: User shall not provide to Company any technical data as that term is defined in the International Traffic\n    in Arms Regulations\n- summary: No unlawful or malicious input\n  text: (e) input, upload, transmit, or otherwise provide to or through the Sites or Services, any information or\n    materials that are unlawful or injurious, or contain, transmit, or activate any harmful or malicious code\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: User represents and warrants that User (a) has the right, authority, and capacity to enter into Terms of\n    Use, (b) will abide by all of the terms and conditions of these Terms of Use, and (c) is at least 18 years of\n    age.\n"
source_yaml_url: https://artifacts.apis.io/simplemdm/eligibility/simplemdm-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SimpleMDM's own page on 2026-11-10.
synthetic: false
tags:
- Mobile Device Management
- Apple
- MDM
- Enterprise
- Software-as-a-Service
- Company
---
