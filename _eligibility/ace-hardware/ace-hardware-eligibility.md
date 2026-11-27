---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: are intended only for residents of the fifty (50) United States and the District of Columbia
  entity_types:
  - text: The Online Services accounts are intended for personal, household use by consumers and may not be used by businesses or other entities or for commercial purposes except through a business account
    type: individual
  - text: except through a business account, which may be subject to additional terms and conditions
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use the Online Services.
    value: '18'
  restricted_uses:
  - summary: No drop-ship use by resellers
    text: Ace does not permit the Online Services to be used by resellers as a drop ship supplier.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require verification of information prior to the acceptance and/or shipment of any order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ace Hardware
provenance_date: '2026-11-09'
provider_name: Ace Hardware
provider_slug: ace-hardware
slug: ace-hardware-eligibility
source_date: '2026-11-09'
source_filename: ace-hardware-eligibility.yml
source_heading: Eligibility
source_page: https://www.acehardware.com/customer-service-center/safety-security-privacy#terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ace Hardware\naid: ace-hardware\nurl: https://www.acehardware.com/customer-service-center/safety-security-privacy#terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: are intended only for residents of the fifty (50) United States and the District of Columbia\nentity_types:\n- type: individual\n  text: The Online Services accounts are intended for personal, household use by consumers and may not be used by\n    businesses or other entities or for commercial purposes except through a business account\n- type: business\n  text: except through a business\
  \ account, which may be subject to additional terms and conditions\nrestricted_uses:\n- summary: No drop-ship use by resellers\n  text: Ace does not permit the Online Services to be used by resellers as a drop ship supplier.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require verification of information prior to the acceptance and/or shipment of any order.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Online Services.\n"
source_yaml_url: https://artifacts.apis.io/ace-hardware/eligibility/ace-hardware-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ace Hardware's own page on 2026-11-09.
synthetic: false
tags:
- Retail
- Hardware
- Home Improvement
- Tools
- Paint
- Cooperative
- EDI
- Affiliates
---
