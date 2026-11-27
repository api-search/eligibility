---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You confirm that you are receiving any Services provided by Chargezen for the purposes of carrying on a business activity and not for any personal, household or family purpose.
    type: business
  minimum_age:
    text: 'You must be the older of: (i) 18 years, or (ii) at least the age of majority in the jurisdiction where you reside and from which you use the Services to open an Account.'
    value: '18'
  restricted_uses:
  - summary: No illegal or unauthorized purposes
    text: You may not use the Chargezen Services for any illegal or unauthorized purpose nor may you, in the use of the Service, violate any laws in your jurisdiction.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Chargezen may reject your application for an Account, or cancel an existing Account, for any reason, at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: chargezen-com
provenance_date: '2026-11-09'
provider_name: chargezen-com
provider_slug: chargezen-com
slug: chargezen-com-eligibility
source_date: '2026-11-09'
source_filename: chargezen-com-eligibility.yml
source_heading: Eligibility
source_page: https://chargezen.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: chargezen-com\naid: chargezen-com\nurl: https://chargezen.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You confirm that you are receiving any Services provided by Chargezen for the purposes of carrying on a\n    business activity and not for any personal, household or family purpose.\nrestricted_uses:\n- summary: No illegal or unauthorized purposes\n  text: You may not use the Chargezen Services for any illegal or unauthorized purpose nor may you, in the use of\n    the Service, violate any laws in your jurisdiction.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: Chargezen may reject your application for an Account, or cancel an existing Account, for any reason, at\n    our sole discretion.\nminimum_age:\n  value: '18'\n  text: 'You must be the older of: (i) 18 years, or (ii) at least the age of majority in the jurisdiction where\n    you reside and from which you use the Services to open an Account.'\n"
source_yaml_url: https://artifacts.apis.io/chargezen-com/eligibility/chargezen-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from chargezen-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
