---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if your employer pays for your access to this Service which is, solely for the purposes set out in this Section 5.12 and the Sections of this Agreement referred to in this Section 5.12, a party to this Agreement.
    type: business
  minimum_age:
    text: If you are a minor, you represent that your legal guardian has reviewed and agreed to these Terms on your behalf.
    value: null
  restricted_uses:
  - summary: Medical restrictions
    text: If you have a condition that requires medical treatment, or are pregnant and/or breastfeeding/lactating, have an eating disorder, you may not use the Service without an approval from your physician or other licensed health adviser;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may also be required to register an account on the Service (an "Account").
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Optimity
provenance_date: '2026-11-10'
provider_name: Optimity
provider_slug: optimity
slug: optimity-eligibility
source_date: '2026-11-10'
source_filename: optimity-eligibility.yml
source_heading: Eligibility
source_page: https://www.myoptimity.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Optimity\naid: optimity\nurl: https://www.myoptimity.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if your employer pays for your access to this Service which is, solely for the purposes set out in this\n    Section 5.12 and the Sections of this Agreement referred to in this Section 5.12, a party to this Agreement.\nrestricted_uses:\n- summary: Medical restrictions\n  text: If you have a condition that requires medical treatment, or are pregnant and/or breastfeeding/lactating,\n    have an eating disorder, you may not use\
  \ the Service without an approval from your physician or other licensed\n    health adviser;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may also be required to register an account on the Service (an \"Account\").\nminimum_age:\n  value: null\n  text: If you are a minor, you represent that your legal guardian has reviewed and agreed to these Terms on your\n    behalf.\n"
source_yaml_url: https://artifacts.apis.io/optimity/eligibility/optimity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Optimity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Wellness
- Rewards
- Gamification
- Corporate Wellness
- Insurance
- Behavioral Science
- Fitness
---
