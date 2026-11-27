---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - PH
    text: Residing in the operating and serviceable geographies of ALLCARE (currently Philippines only)
  minimum_age:
    text: Aged between 18 to 60 years old
    value: '18'
  restricted_uses:
  - summary: Abusive or unlawful conduct
    text: Attempt or actually engage in the use of ALLCARE that violates applicable laws, intellectual property, rights of others to use, fraudulent, offensive or defamatory
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Be approved through the validation of the ALLCARE benefits team which includes validating your eligibility vis a vis personal information, work information, submitted documents and other pertinent validation processes that may be required.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AllCare
provenance_date: '2026-11-09'
provider_name: AllCare
provider_slug: allcare
slug: allcare-eligibility
source_date: '2026-11-09'
source_filename: allcare-eligibility.yml
source_heading: Eligibility
source_page: https://www.allcare.ph/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AllCare\naid: allcare\nurl: https://www.allcare.ph/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - PH\n  excluded: []\n  text: Residing in the operating and serviceable geographies of ALLCARE (currently Philippines only)\nentity_types: []\nrestricted_uses:\n- summary: Abusive or unlawful conduct\n  text: Attempt or actually engage in the use of ALLCARE that violates applicable laws, intellectual property, rights\n    of others to use, fraudulent, offensive or defamatory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Be approved through the validation of the ALLCARE\
  \ benefits team which includes validating your eligibility\n    vis a vis personal information, work information, submitted documents and other pertinent validation processes\n    that may be required.\nminimum_age:\n  value: '18'\n  text: Aged between 18 to 60 years old\n"
source_yaml_url: https://artifacts.apis.io/allcare/eligibility/allcare-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from AllCare's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Insurance
- Employee Benefits
- HMO
- Teleconsultation
- Insurtech
- Philippines
- Small Business
---
