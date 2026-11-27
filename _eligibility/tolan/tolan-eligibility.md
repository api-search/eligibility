---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States.
  entity_types:
  - text: If you are under the age of 18 (a “Minor User”), you may not use the Service unless a parent or legal guardian (a “Guardian”) first agrees to these Terms on your behalf.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: If you are under the age of 18 (a “Minor User”), you may not use the Service unless a parent or legal guardian (a “Guardian”) first agrees to these Terms on your behalf.
    value: '18'
  restricted_uses:
  - summary: No professional advice use
    text: use the Service as (or to provide) any investment, legal, medical, or other professional advice
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
name: Tolan
provenance_date: '2026-11-10'
provider_name: Tolan
provider_slug: tolan
slug: tolan-eligibility
source_date: '2026-11-10'
source_filename: tolan-eligibility.yml
source_heading: Eligibility
source_page: https://www.tolans.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tolan\naid: tolan\nurl: https://www.tolans.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States.\nentity_types:\n- type: individual\n  text: If you are under the age of 18 (a “Minor User”), you may not use the Service unless a parent or legal guardian\n    (a “Guardian”) first agrees to these Terms on your behalf.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority\
  \ to bind you to these Terms\nrestricted_uses:\n- summary: No professional advice use\n  text: use the Service as (or to provide) any investment, legal, medical, or other professional advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under the age of 18 (a “Minor User”), you may not use the Service unless a parent or legal guardian\n    (a “Guardian”) first agrees to these Terms on your behalf.\n"
source_yaml_url: https://artifacts.apis.io/tolan/eligibility/tolan-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Tolan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Companion
- Consumer
- Mobile
- Conversational AI
- Emotional Support
- iOS
---
