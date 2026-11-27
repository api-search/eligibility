---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In case of a legal person, at least one natural person must be given as the authorised representative
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited advertising
    text: This means laudatory, misleading or comparable advertising is prohibited.
  - summary: Unlawful use
    text: The customer must ensure that the customer user account is not used for purposes that violate official regulations or requirements
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The authorisation for opening a customer user account at samedi must be validated by samedi prior to customer user account being activated.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: samedi
provenance_date: '2026-11-10'
provider_name: samedi
provider_slug: samedi
slug: samedi-eligibility
source_date: '2026-11-10'
source_filename: samedi-eligibility.yml
source_heading: Eligibility
source_page: https://legal.samedi.de/en/for_customers/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: samedi\naid: samedi\nurl: https://legal.samedi.de/en/for_customers/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: In case of a legal person, at least one natural person must be given as the authorised representative\nrestricted_uses:\n- summary: Prohibited advertising\n  text: This means laudatory, misleading or comparable advertising is prohibited.\n- summary: Unlawful use\n  text: The customer must ensure that the customer user account is not used for purposes that violate official regulations\n    or requirements\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: true\n  text: The authorisation for opening a customer user account at samedi must be validated by samedi prior to customer\n    user account being activated.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/samedi/eligibility/samedi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from samedi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Scheduling
- Appointments
- Booking
- Patient Engagement
- OAuth
- FHIR
- Telehealth
- Germany
- Authentication
---
