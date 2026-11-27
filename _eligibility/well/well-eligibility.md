---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Applications or Services are not intended for use outside the United States of America.
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age and possess the legal right and ability to agree to these Terms
    type: individual
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: You agree not to use the Services for unlawful purposes
  - summary: Use outside jurisdictions where illegal
    text: Accessing our Application or using our Services from jurisdictions where they may be illegal, or where we do not offer our Services, is prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you meet the eligibility requirements as established by Well in its sole discretion, you may sign up to become a Registered User of the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Well
provenance_date: '2026-11-10'
provider_name: Well
provider_slug: well
slug: well-eligibility
source_date: '2026-11-10'
source_filename: well-eligibility.yml
source_heading: Eligibility
source_page: https://www.well.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Well\naid: well\nurl: https://www.well.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Applications or Services are not intended for use outside the United States of America.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age and possess the legal right and ability\n    to agree to these Terms\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You agree not to use the Services for unlawful purposes\n- summary: Use outside jurisdictions where illegal\n  text: Accessing our Application or using our Services\
  \ from jurisdictions where they may be illegal, or where we\n    do not offer our Services, is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you meet the eligibility requirements as established by Well in its sole discretion, you may sign up\n    to become a Registered User of the Services\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/well/eligibility/well-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Well's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Health Engagement
- Wellness
- Wellbeing
- Employee Benefits
---
