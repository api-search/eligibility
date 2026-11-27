---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to users located outside the United States.
  minimum_age:
    text: you represent and warrant that you are older than 18 years old
    value: '18'
  restricted_uses:
  - summary: Misuse of services
    text: Providers reserve the right to deny care for actual or potential misuse of the Services.
  - summary: No controlled substances prescribed
    text: Providers do not provide or prescribe medications or pharmacological products, including any DEA controlled substances or scheduled medications
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Boulder Care or a Provider may contact you by telephone, mail, or email to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Boulder Care
provenance_date: '2026-11-09'
provider_name: Boulder Care
provider_slug: boulder-care
slug: boulder-care-eligibility
source_date: '2026-11-09'
source_filename: boulder-care-eligibility.yml
source_heading: Eligibility
source_page: https://www.boulder.care/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boulder Care\naid: boulder-care\nurl: https://www.boulder.care/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to users located outside the United States.\nentity_types: []\nrestricted_uses:\n- summary: Misuse of services\n  text: Providers reserve the right to deny care for actual or potential misuse of the Services.\n- summary: No controlled substances prescribed\n  text: Providers do not provide or prescribe medications or pharmacological products, including any DEA controlled\n    substances or scheduled medications\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Boulder Care or a Provider may contact you by telephone, mail, or email to verify your information.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are older than 18 years old\n"
source_yaml_url: https://artifacts.apis.io/boulder-care/eligibility/boulder-care-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Boulder Care's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Behavioral Health
- Addiction Treatment
- Substance Use Disorder
- Digital Health
- Medicaid
- Virtual Care
- Mobile Health
---
