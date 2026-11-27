---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the Software, Site or Content you warrant that you are 18 years old or above.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorised use
    text: In the event that We, in Our sole discretion, considers that you are making any illegal, noncompliant and/or unauthorised use of the Software
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access the Software, you shall be required to register with Us. By registering with Us, you consent to Us conducting verification and security procedures in respect of the information provided by you during the registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Keel
provenance_date: '2026-11-09'
provider_name: Keel
provider_slug: keel
slug: keel-eligibility
source_date: '2026-11-09'
source_filename: keel-eligibility.yml
source_heading: Eligibility
source_page: https://keel.so/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keel\naid: keel\nurl: https://keel.so/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorised use\n  text: In the event that We, in Our sole discretion, considers that you are making any illegal, noncompliant and/or\n    unauthorised use of the Software\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access the Software, you shall be required to register with Us. By registering with Us, you\n    consent to Us conducting verification and security procedures\
  \ in respect of the information provided by you\n    during the registration process.\nminimum_age:\n  value: '18'\n  text: By using the Software, Site or Content you warrant that you are 18 years old or above.\n"
source_yaml_url: https://artifacts.apis.io/keel/eligibility/keel-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Keel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ERP
- Backend
- GraphQL
- Low-Code
- Developer Tools
- Workflows
- Authentication
- TypeScript
---
