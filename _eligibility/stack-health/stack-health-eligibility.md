---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is offered only to users located in the United States and is intended for use only by U.S. residents and U.S.-domiciled businesses.
  entity_types:
  - text: In the case of an entity, be domiciled and operating in the United States.
    type: business
  minimum_age:
    text: Be at least eighteen (18) years of age;
    value: '18'
  restricted_uses:
  - summary: Fraud or unlawful conduct
    text: You may not use the Platform to engage in fraudulent, deceptive, or unlawful conduct, including submitting false or misleading information
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Stack may require reasonable security measures, including multi-factor authentication, periodic credential resets, and verification steps, as a condition of access to some or all Platform features.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Stack Health
provenance_date: '2026-11-10'
provider_name: Stack Health
provider_slug: stack-health
slug: stack-health-eligibility
source_date: '2026-11-10'
source_filename: stack-health-eligibility.yml
source_heading: Eligibility
source_page: https://mystack.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stack Health\naid: stack-health\nurl: https://mystack.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is offered only to users located in the United States and is intended for use only by U.S.\n    residents and U.S.-domiciled businesses.\nentity_types:\n- type: business\n  text: In the case of an entity, be domiciled and operating in the United States.\nrestricted_uses:\n- summary: Fraud or unlawful conduct\n  text: You may not use the Platform to engage in fraudulent, deceptive, or unlawful conduct, including submitting\n    false or misleading\
  \ information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Stack may require reasonable security measures, including multi-factor authentication, periodic credential\n    resets, and verification steps, as a condition of access to some or all Platform features.\nminimum_age:\n  value: '18'\n  text: Be at least eighteen (18) years of age;\n"
source_yaml_url: https://artifacts.apis.io/stack-health/eligibility/stack-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Stack Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Insurance
- Healthcare
- Fintech
- Insurance
- Employee Benefits
- Small Business
- HIPAA
---
