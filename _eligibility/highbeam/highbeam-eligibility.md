---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may only apply for an Account, and use the applicable Services under such Account, if you are a legal entity formed and registered in the United States and can form a binding contract with Highbeam. Individual consumers and companies organized and registered outside the United States are not permitted to use or attempt to open or use an Account or the Services.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumer or non-commercial use prohibited
    text: Any use of or access to the Services for consumer or non-commercial purposes or by any individual who is not your employee, contractor, agent, or other individual permitted to use your Account on your behalf (“ User ”) is strictly prohibited
  - summary: Sanctioned parties
    text: use the Account or the Services for the benefit of an individual, organization, country, or jurisdiction that is blocked or sanctioned by the United States
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Specific aspects of the Services may be subject to additional requirements, including you continuing to meet (in Highbeam’s sole discretion) Highbeam’s rating and evaluation requirements from time to time
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Highbeam
provenance_date: '2026-11-09'
provider_name: Highbeam
provider_slug: highbeam
slug: highbeam-eligibility
source_date: '2026-11-09'
source_filename: highbeam-eligibility.yml
source_heading: Eligibility
source_page: https://www.highbeam.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Highbeam\naid: highbeam\nurl: https://www.highbeam.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may only apply for an Account, and use the applicable Services under such Account, if you are a legal\n    entity formed and registered in the United States and can form a binding contract with Highbeam. Individual\n    consumers and companies organized and registered outside the United States are not permitted to use or attempt\n    to open or use an Account or the Services.\nentity_types: []\nrestricted_uses:\n- summary: Consumer or non-commercial\
  \ use prohibited\n  text: Any use of or access to the Services for consumer or non-commercial purposes or by any individual who is\n    not your employee, contractor, agent, or other individual permitted to use your Account on your behalf (“ User\n    ”) is strictly prohibited\n- summary: Sanctioned parties\n  text: use the Account or the Services for the benefit of an individual, organization, country, or jurisdiction\n    that is blocked or sanctioned by the United States\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Specific aspects of the Services may be subject to additional requirements, including you continuing to\n    meet (in Highbeam’s sole discretion) Highbeam’s rating and evaluation requirements from time to time\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/highbeam/eligibility/highbeam-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Highbeam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Fintech
- Business Banking
- Financial Services
- E-Commerce
- Working Capital
- Consumer Brand
---
