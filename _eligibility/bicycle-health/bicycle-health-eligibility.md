---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Site or the Services is limited exclusively to users located in States within the United States where the Services are available. Services are not available to users located outside the United States.
  minimum_age:
    text: you represent and warrant that you are older than 18 years old, unless you are physically located in Maine. If you are physically located in Maine, you represent and warrant that you are older than 16 years old.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Bicycle Health and your Provider may contact you by telephone, mail, or email to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bicycle Health
provenance_date: '2026-11-09'
provider_name: Bicycle Health
provider_slug: bicycle-health
slug: bicycle-health-eligibility
source_date: '2026-11-09'
source_filename: bicycle-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.bicyclehealth.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bicycle Health\naid: bicycle-health\nurl: https://www.bicyclehealth.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Site or the Services is limited exclusively to users located in States within the\n    United States where the Services are available. Services are not available to users located outside the United\n    States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Bicycle Health and your Provider may contact you by telephone, mail, or email to verify your\
  \ information.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are older than 18 years old, unless you are physically located in Maine.\n    If you are physically located in Maine, you represent and warrant that you are older than 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/bicycle-health/eligibility/bicycle-health-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from Bicycle Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Digital Health
- Behavioral Health
- Addiction Treatment
- Opioid Use Disorder
- Medication for Addiction Treatment
- Virtual Care
---
