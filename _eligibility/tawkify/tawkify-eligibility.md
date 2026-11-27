---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Services are intended for users located in the United States.
  entity_types:
  - text: You are an individual and at least 18 years old;
    type: individual
  minimum_age:
    text: You are an individual and at least 18 years old;
    value: '18'
  restricted_uses:
  - summary: Genuine relationship-seeking only
    text: You are using the Services for genuine relationship-seeking purposes;
  - summary: Automated, commercial or non-dating use
    text: Use the Services for any automated, commercial, unlawful, or non-dating-related purpose;
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may ask you to verify your age or identity with a government-issued ID during account setup, or at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tawkify
provenance_date: '2026-11-10'
provider_name: Tawkify
provider_slug: tawkify
slug: tawkify-eligibility
source_date: '2026-11-10'
source_filename: tawkify-eligibility.yml
source_heading: Eligibility
source_page: https://app.tawkify.com/agreement/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tawkify\naid: tawkify\nurl: https://app.tawkify.com/agreement/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Services are intended for users located in the United States.\nentity_types:\n- type: individual\n  text: You are an individual and at least 18 years old;\nrestricted_uses:\n- summary: Genuine relationship-seeking only\n  text: You are using the Services for genuine relationship-seeking purposes;\n- summary: Automated, commercial or non-dating use\n  text: Use the Services for any automated, commercial, unlawful, or non-dating-related\
  \ purpose;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may ask you to verify your age or identity with a government-issued ID during account setup, or at any\n    time.\nminimum_age:\n  value: '18'\n  text: You are an individual and at least 18 years old;\n"
source_yaml_url: https://artifacts.apis.io/tawkify/eligibility/tawkify-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Tawkify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Matchmaking
- Online Dating
- Relationships
- Consumer Services
- Personal Services
- Concierge
---
