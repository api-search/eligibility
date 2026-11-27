---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Loans may only be made to residents of, or secured by real property located in, states where Lenders are licensed or authorized to make such loans.
  entity_types:
  - text: You may use the Service only if you are a natural person (i.e., not a business or other corporate entity) and can form a binding contract with Own Up.
    type: individual
  minimum_age:
    text: The Services are intended for use only by users who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Use by minors
    text: Any use or access to the Service by anyone under the age of majority in the State in which they reside is strictly prohibited
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may verify your identity. You authorize us to make any inquiries we consider necessary to validate your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Own Up
provenance_date: '2026-11-10'
provider_name: Own Up
provider_slug: own-up
slug: own-up-eligibility
source_date: '2026-11-10'
source_filename: own-up-eligibility.yml
source_heading: Eligibility
source_page: https://www.ownup.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Own Up\naid: own-up\nurl: https://www.ownup.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Loans may only be made to residents of, or secured by real property located in, states where Lenders are\n    licensed or authorized to make such loans.\nentity_types:\n- type: individual\n  text: You may use the Service only if you are a natural person (i.e., not a business or other corporate entity)\n    and can form a binding contract with Own Up.\nrestricted_uses:\n- summary: Use by minors\n  text: Any use or access to the Service by anyone under\
  \ the age of majority in the State in which they reside is\n    strictly prohibited\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may verify your identity. You authorize us to make any inquiries we consider necessary to validate your\n    identity.\nminimum_age:\n  value: '18'\n  text: The Services are intended for use only by users who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/own-up/eligibility/own-up-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Own Up's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mortgage
- Lending
- Fintech
- Home Loans
- Real Estate
- Marketplace
- Consumer Finance
---
