---
claim_count: 8
description: ''
doc:
  countries:
    excluded:
    - US
    - NL
    - ES
    - FR
    - DE
    - BE
    - IT
    - AE
    - TR
    - AU
    - SG
    - JP
    - IN
    - CN
    served: []
    text: Some countries, regions or geographical including but not limited to the USA, Netherlands, Spain, France, Germany, Belgium, Italy, UAE, Turkey, Australia, Singapore, Japan, India, China may not be eligible to access or use the Galxe Rewards Hub.
  entity_types:
  - text: To be eligible to use the Services you must be at least 18 years old or of the legal age in the jurisdiction you reside in at the time of using the Services.
    type: individual
  - text: If you are using the Services to create a content space, curate user credentials, deploy NFTs, or create user campaigns, you must first apply for a developer account with us
    type: developer
  - text: 'By subscribing, Client irrevocably agrees: (i) All fees (including quarterly/annual payments) are non-refundable'
    type: business
  minimum_age:
    text: To be eligible to use the Services you must be at least 18 years old or of the legal age in the jurisdiction you reside in
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions
    text: you are not located in a country that is subject to sanctions or embargos by the United States, United Kingdom, European Union or United Nations
  - summary: VPN circumvention of geo-restrictions
    text: You must not use any software or networking techniques, including use of a Virtual Private Network (VPN) to modify your internet protocol address or otherwise circumvent or attempt to circumvent this prohibition.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Galxe may require you to provide additional information and documents at the request of any competent authority or in case of application of any applicable law or regulation
excluded_countries:
- US
- NL
- ES
- FR
- DE
- BE
- IT
- AE
- TR
- AU
- SG
- JP
- IN
- CN
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Galxe
provenance_date: '2026-11-09'
provider_name: Galxe
provider_slug: galxe
slug: galxe-eligibility
source_date: '2026-11-09'
source_filename: galxe-eligibility.yml
source_heading: Eligibility
source_page: https://docs.galxe.com/about/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Galxe\naid: galxe\nurl: https://docs.galxe.com/about/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  - NL\n  - ES\n  - FR\n  - DE\n  - BE\n  - IT\n  - AE\n  - TR\n  - AU\n  - SG\n  - JP\n  - IN\n  - CN\n  text: Some countries, regions or geographical including but not limited to the USA, Netherlands, Spain, France,\n    Germany, Belgium, Italy, UAE, Turkey, Australia, Singapore, Japan, India, China may not be eligible to access\n    or use the Galxe Rewards Hub.\nentity_types:\n- type: individual\n  text: To be eligible to use the Services\
  \ you must be at least 18 years old or of the legal age in the jurisdiction\n    you reside in at the time of using the Services.\n- type: developer\n  text: If you are using the Services to create a content space, curate user credentials, deploy NFTs, or create\n    user campaigns, you must first apply for a developer account with us\n- type: business\n  text: 'By subscribing, Client irrevocably agrees: (i) All fees (including quarterly/annual payments) are non-refundable'\nrestricted_uses:\n- summary: Sanctioned jurisdictions\n  text: you are not located in a country that is subject to sanctions or embargos by the United States, United Kingdom,\n    European Union or United Nations\n- summary: VPN circumvention of geo-restrictions\n  text: You must not use any software or networking techniques, including use of a Virtual Private Network (VPN)\n    to modify your internet protocol address or otherwise circumvent or attempt to circumvent this prohibition.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: Galxe may require you to provide additional information and documents at the request of any competent authority\n    or in case of application of any applicable law or regulation\nminimum_age:\n  value: '18'\n  text: To be eligible to use the Services you must be at least 18 years old or of the legal age in the jurisdiction\n    you reside in\n"
source_yaml_url: https://artifacts.apis.io/galxe/eligibility/galxe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Galxe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web3
- Digital Identity
- Credentials
- Quests
- Loyalty
- GraphQL
- OAuth
- Blockchain
- Authentication
---
