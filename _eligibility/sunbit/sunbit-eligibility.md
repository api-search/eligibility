---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may not be appropriate or available for use in jurisdictions outside of the United States.
  minimum_age:
    text: The Services are not intended for, and should not be used by, persons who have not reached the age of majority in their states of residence.
    value: age of majority
  restricted_uses:
  - summary: Unlawful or prohibited jurisdictions
    text: The Services are not intended for, and should not be used by, any person or entity in any jurisdiction or country where such distribution or use would be contrary to local laws or regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Submission of any information and/or an application does not automatically qualify you for Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sunbit
provenance_date: '2026-11-10'
provider_name: Sunbit
provider_slug: sunbit
slug: sunbit-eligibility
source_date: '2026-11-10'
source_filename: sunbit-eligibility.yml
source_heading: Eligibility
source_page: https://sunbit.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sunbit\naid: sunbit\nurl: https://sunbit.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services may not be appropriate or available for use in jurisdictions outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited jurisdictions\n  text: The Services are not intended for, and should not be used by, any person or entity in any jurisdiction or\n    country where such distribution or use would be contrary to local laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Submission\
  \ of any information and/or an application does not automatically qualify you for Services.\nminimum_age:\n  value: age of majority\n  text: The Services are not intended for, and should not be used by, persons who have not reached the age of majority\n    in their states of residence.\n"
source_yaml_url: https://artifacts.apis.io/sunbit/eligibility/sunbit-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Sunbit's own page on 2026-11-10.
synthetic: false
tags:
- Buy Now Pay Later
- Point of Sale Financing
- Consumer Lending
- Payments
- Fintech
- Checkout
- Merchant Onboarding
- Webhook
- Automotive
- Dental
- Veterinary
- Eyewear
- healthcare-financing
- Embedded Finance
---
