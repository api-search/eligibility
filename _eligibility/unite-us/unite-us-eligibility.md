---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access from territories where they are illegal is prohibited
  minimum_age:
    text: By viewing this Site, you certify that you are 18 years of age or older. Children under the age of 18 are not permitted to access this Site.
    value: '18'
  restricted_uses:
  - summary: Non-eligible party use
    text: Your status as an eligible party is a material condition of use of the Site and any use of the Site by anyone other than an eligible party shall be considered a material misrepresentation.
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
name: Unite Us
provenance_date: '2026-11-10'
provider_name: Unite Us
provider_slug: unite-us
slug: unite-us-eligibility
source_date: '2026-11-10'
source_filename: unite-us-eligibility.yml
source_heading: Eligibility
source_page: https://uniteus.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unite Us\naid: unite-us\nurl: https://uniteus.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access from territories where they are illegal is prohibited\nentity_types: []\nrestricted_uses:\n- summary: Non-eligible party use\n  text: Your status as an eligible party is a material condition of use of the Site and any use of the Site by anyone\n    other than an eligible party shall be considered a material misrepresentation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By viewing this\
  \ Site, you certify that you are 18 years of age or older. Children under the age of 18 are\n    not permitted to access this Site.\n"
source_yaml_url: https://artifacts.apis.io/unite-us/eligibility/unite-us-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Unite Us's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Social Care
- SDOH
- Referrals
- Care Coordination
- Interoperability
- FHIR
---
