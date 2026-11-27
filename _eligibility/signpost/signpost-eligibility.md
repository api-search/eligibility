---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if Merchant is registering for the Services as an individual, that Merchant is at least 18 years of age and has the legal capacity to enter into these Terms of Service
    type: individual
  - text: if registering for the Services as an entity or organization, (a) Merchant is duly authorized to do business in the country or countries where it operates
    type: business
  minimum_age:
    text: if Merchant is registering for the Services as an individual, that Merchant is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No high-risk applications
    text: Merchant may not use the SignpostAI Platform or Services in any application that may involve risks of death, personal injury, property damage or environmental damage.
  - summary: No PHI upload
    text: Merchant agrees to not upload or incorporate into any customer lists, or otherwise provide to SignpostAI any protected health information of any kind within the meaning of the Health Insurance Portability and Accountability Act of 1996, as amended (HIPAA).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: SignpostAI reserves the right to have Merchant complete a credit application to determine Merchant’s creditworthiness as a condition of receiving further Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Signpost
provenance_date: '2026-11-10'
provider_name: Signpost
provider_slug: signpost
slug: signpost-eligibility
source_date: '2026-11-10'
source_filename: signpost-eligibility.yml
source_heading: Eligibility
source_page: https://www.signpost.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Signpost\naid: signpost\nurl: https://www.signpost.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if Merchant is registering for the Services as an individual, that Merchant is at least 18 years of age\n    and has the legal capacity to enter into these Terms of Service\n- type: business\n  text: if registering for the Services as an entity or organization, (a) Merchant is duly authorized to do business\n    in the country or countries where it operates\nrestricted_uses:\n- summary: No high-risk applications\n\
  \  text: Merchant may not use the SignpostAI Platform or Services in any application that may involve risks of death,\n    personal injury, property damage or environmental damage.\n- summary: No PHI upload\n  text: Merchant agrees to not upload or incorporate into any customer lists, or otherwise provide to SignpostAI\n    any protected health information of any kind within the meaning of the Health Insurance Portability and Accountability\n    Act of 1996, as amended (HIPAA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: SignpostAI reserves the right to have Merchant complete a credit application to determine Merchant’s creditworthiness\n    as a condition of receiving further Services.\nminimum_age:\n  value: '18'\n  text: if Merchant is registering for the Services as an individual, that Merchant is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/signpost/eligibility/signpost-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Signpost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Virtual Receptionist
- Answering Service
- Small Business
- Home Services
- Communications
- CRM
- Lead Management
- Messaging
---
