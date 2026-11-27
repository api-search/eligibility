---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - US
    text: This Service is only available to users physically located in the United Kingdom and the United States of America.
  entity_types:
  - text: We only provide the Services for your non-exclusive personal use.
    type: individual
  minimum_age:
    text: To use our Services you must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Geographic circumvention prohibited
    text: Any attempt to access or use the Service from outside these territories, including through the use of VPNs, proxies, location spoofing tools, emulator devices, multi-accounting, or any other method intended to circumvent geographic or platform restrictions, is strictly prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: 'Once you reach the Minimum Pro Points Redemption Amount you may be asked by either Prograd or one of our third party partners to: (a) verify your email address; provide your bank details/chosen withdrawal method; (c) provide a qualifying UK identity document'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ProGrad
provenance_date: '2026-11-10'
provider_name: ProGrad
provider_slug: prograd
slug: prograd-eligibility
source_date: '2026-11-10'
source_filename: prograd-eligibility.yml
source_heading: Eligibility
source_page: https://www.prograd.uk/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ProGrad\naid: prograd\nurl: https://www.prograd.uk/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - US\n  excluded: []\n  text: This Service is only available to users physically located in the United Kingdom and the United States of\n    America.\nentity_types:\n- type: individual\n  text: We only provide the Services for your non-exclusive personal use.\nrestricted_uses:\n- summary: Geographic circumvention prohibited\n  text: Any attempt to access or use the Service from outside these territories, including through the use of VPNs,\n    proxies, location spoofing tools, emulator\
  \ devices, multi-accounting, or any other method intended to circumvent\n    geographic or platform restrictions, is strictly prohibited.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: 'Once you reach the Minimum Pro Points Redemption Amount you may be asked by either Prograd or one of our\n    third party partners to: (a) verify your email address; provide your bank details/chosen withdrawal method;\n    (c) provide a qualifying UK identity document'\nminimum_age:\n  value: '18'\n  text: To use our Services you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/prograd/eligibility/prograd-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ProGrad's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Rewards
- Mobile App
- Fintech
- Gen Z
- United Kingdom
---
