---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - SG
    - MY
    - AU
    text: Header navigation lists Singapore, Malaysia and Australia; no eligibility restriction by country is stated in the terms.
  entity_types:
  - text: 'By accessing any of the Platforms, you represent and warrant that: you are of legal age of majority to contract in the jurisdiction in which you reside and in any event, no less than 18 years of age'
    type: individual
  - text: If you’re agreeing to this Agreement on behalf of an organization or entity, you represent and warrant that you are authorized to agree to this Agreement on that organization or entity’s behalf
    type: business
  minimum_age:
    text: no less than 18 years of age
    value: '18'
  restricted_uses:
  - summary: Spam, spyware, or unlawful content
    text: No spam, spyware or virus is allowed on any of the Platforms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As part of the registration of a User Profile, Homage may require you to complete a verification process (in such manner as may be determined by Homage from time to time) to verify the information which you have provided to Homage.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Homage
provenance_date: '2026-11-09'
provider_name: Homage
provider_slug: homage
slug: homage-eligibility
source_date: '2026-11-09'
source_filename: homage-eligibility.yml
source_heading: Eligibility
source_page: https://www.homage.sg/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Homage\naid: homage\nurl: https://www.homage.sg/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - SG\n  - MY\n  - AU\n  excluded: []\n  text: Header navigation lists Singapore, Malaysia and Australia; no eligibility restriction by country is stated\n    in the terms.\nentity_types:\n- type: individual\n  text: 'By accessing any of the Platforms, you represent and warrant that: you are of legal age of majority to\n    contract in the jurisdiction in which you reside and in any event, no less than 18 years of age'\n- type: business\n  text: If you’re agreeing to this Agreement\
  \ on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to this Agreement on that organization or entity’s behalf\nrestricted_uses:\n- summary: Spam, spyware, or unlawful content\n  text: No spam, spyware or virus is allowed on any of the Platforms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As part of the registration of a User Profile, Homage may require you to complete a verification process\n    (in such manner as may be determined by Homage from time to time) to verify the information which you have provided\n    to Homage.\nminimum_age:\n  value: '18'\n  text: no less than 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/homage/eligibility/homage-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Homage's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Caregiving
- Home Care
- Health Services
- Aged Care
- Telehealth
- Singapore
---
