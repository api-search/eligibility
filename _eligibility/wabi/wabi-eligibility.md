---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service or any Mini-Apps.
    value: '13'
  restricted_uses:
  - summary: Gambling product
    text: use the Service or any Mini-Apps to create a gambling product
  - summary: Political campaigning or election interference
    text: political campaigning, lobbying, election interference, or voter suppression
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You register with your mobile phone number, which we verify with a one-time code, and confirm your identity with the Google account you signed up with or a code sent to the Outlook, iCloud, or other email address on your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wabi
provenance_date: '2026-11-10'
provider_name: Wabi
provider_slug: wabi
slug: wabi-eligibility
source_date: '2026-11-10'
source_filename: wabi-eligibility.yml
source_heading: Eligibility
source_page: https://wabi.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wabi\naid: wabi\nurl: https://wabi.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Gambling product\n  text: use the Service or any Mini-Apps\
  \ to create a gambling product\n- summary: Political campaigning or election interference\n  text: political campaigning, lobbying, election interference, or voter suppression\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You register with your mobile phone number, which we verify with a one-time code, and confirm your identity\n    with the Google account you signed up with or a code sent to the Outlook, iCloud, or other email address on\n    your account.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service or any Mini-Apps.\n"
source_yaml_url: https://artifacts.apis.io/wabi/eligibility/wabi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Wabi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- App Builder
- No-Code
- Personal Software
- Mini Apps
- Consumer
- Generative AI
---
