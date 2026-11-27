---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: be a resident of India
  entity_types:
  - text: be at least 18 years of age
    type: individual
  - text: If you use the Services on behalf of another person (as an authorised representative, nominee, or guardian), you confirm you have authority to bind that person to these Terms.
    type: other
  minimum_age:
    text: be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No competing product training
    text: use the Services to build or train a competing product
  - summary: No emergency use
    text: Do not use the Services in an emergency.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: have received a valid invitation or onboarding from AIWO (invite-only to registered clients)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aiwo
provenance_date: '2026-11-09'
provider_name: Aiwo
provider_slug: aiwo
slug: aiwo-eligibility
source_date: '2026-11-09'
source_filename: aiwo-eligibility.yml
source_heading: Eligibility
source_page: https://aiwo.com/pages/aiwo-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aiwo\naid: aiwo\nurl: https://aiwo.com/pages/aiwo-terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: be a resident of India\nentity_types:\n- type: individual\n  text: be at least 18 years of age\n- type: other\n  text: If you use the Services on behalf of another person (as an authorised representative, nominee, or guardian),\n    you confirm you have authority to bind that person to these Terms.\nrestricted_uses:\n- summary: No competing product training\n  text: use the Services to build or train a competing product\n- summary: No emergency use\n  text: Do not\
  \ use the Services in an emergency.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: have received a valid invitation or onboarding from AIWO (invite-only to registered clients)\nminimum_age:\n  value: '18'\n  text: be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/aiwo/eligibility/aiwo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Aiwo's own page on 2026-11-09.
synthetic: false
tags:
- Health
- Longevity
- Wellness
- Diagnostics
- Artificial Intelligence
---
