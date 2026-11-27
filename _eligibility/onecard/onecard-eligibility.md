---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: You are not barred or otherwise legally prohibited from accessing or using App and / or Website under the laws of Republic of India
  entity_types:
  - text: You hereby represent and warrant to the Company that you are at least eighteen (18) years of age or above and are capable of entering, performing and adhering to these Terms
    type: individual
  minimum_age:
    text: You hereby represent and warrant to the Company that you are at least eighteen (18) years of age or above
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: You shall not use any product or service available on App / Website for commercial purposes
  - summary: Unlawful or harmful use prohibited
    text: or use the Services in any way that is unlawful, or harms the Company or any other person or entity
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: On completion of the above process and successful evaluation and assessment of your application or request to avail the Services, you will be a registered user of App
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Onecard
provenance_date: '2026-11-10'
provider_name: Onecard
provider_slug: onecard
slug: onecard-eligibility
source_date: '2026-11-10'
source_filename: onecard-eligibility.yml
source_heading: Eligibility
source_page: https://www.getonecard.app/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onecard\naid: onecard\nurl: https://www.getonecard.app/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: You are not barred or otherwise legally prohibited from accessing or using App and / or Website under the\n    laws of Republic of India\nentity_types:\n- type: individual\n  text: You hereby represent and warrant to the Company that you are at least eighteen (18) years of age or above\n    and are capable of entering, performing and adhering to these Terms\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: You shall not use any product or service\
  \ available on App / Website for commercial purposes\n- summary: Unlawful or harmful use prohibited\n  text: or use the Services in any way that is unlawful, or harms the Company or any other person or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: On completion of the above process and successful evaluation and assessment of your application or request\n    to avail the Services, you will be a registered user of App\nminimum_age:\n  value: '18'\n  text: You hereby represent and warrant to the Company that you are at least eighteen (18) years of age or above\n"
source_yaml_url: https://artifacts.apis.io/onecard/eligibility/onecard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Onecard's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Credit
- Fintech
- Credit Cards
- Payments
- Banking
- India
- Consumer Finance
---
