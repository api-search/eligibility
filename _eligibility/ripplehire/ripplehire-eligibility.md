---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you, the Enterprise Customer, Member, or User
    type: business
  minimum_age:
    text: User is 18 years or older
    value: '18'
  restricted_uses:
  - summary: Competitors excluded
    text: User is neither a competitor of the Trampoline Tech Private Limited nor using the Services for reasons that are in competition with the Trampoline Tech Private Limited
  - summary: No HIPAA-protected data without addendum
    text: You agree not to use the Platform to process highly sensitive, prohibited data (e.g., protected health information under HIPAA) unless expressly supported by a specific addendum.
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
name: RippleHire
provenance_date: '2026-11-10'
provider_name: RippleHire
provider_slug: ripplehire
slug: ripplehire-eligibility
source_date: '2026-11-10'
source_filename: ripplehire-eligibility.yml
source_heading: Eligibility
source_page: https://www.ripplehire.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RippleHire\naid: ripplehire\nurl: https://www.ripplehire.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you, the Enterprise Customer, Member, or User\nrestricted_uses:\n- summary: Competitors excluded\n  text: User is neither a competitor of the Trampoline Tech Private Limited nor using the Services for reasons that\n    are in competition with the Trampoline Tech Private Limited\n- summary: No HIPAA-protected data without addendum\n  text: You agree not to use the Platform to process highly sensitive, prohibited data\
  \ (e.g., protected health information\n    under HIPAA) unless expressly supported by a specific addendum.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: User is 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/ripplehire/eligibility/ripplehire-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from RippleHire's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recruiting
- Applicant Tracking
- Human Resources
- Hiring
- Employee Referrals
- Talent Acquisition
- Onboarding
---
