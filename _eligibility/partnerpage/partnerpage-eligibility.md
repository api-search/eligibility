---
api_specs:
- filename: partnerpage-openapi-generated.yml
  format: yaml
  label: PartnerPage API
  slug: partnerpage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/partnerpage/openapi/_ae-authored/partnerpage-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The PartnerPage Directory Service is hosted by servers located in the United States. Using the PartnerPage Directory Service may be prohibited or restricted in certain other countries.
  entity_types:
  - text: means the vendor of a software-as-a-service or similar offering that has entered into a Subscription Agreement with PartnerPage
    type: business
  minimum_age:
    text: AFFIRM THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU RESIDE)
    value: '18'
  restricted_uses:
  - summary: Competitive build or feature copying
    text: (xii) access the PartnerPage Directory Service in order to build a competitive product or service, or copy any features, functions or graphics of the PartnerPage Directory Service;
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
name: PartnerPage
provenance_date: '2026-11-10'
provider_name: PartnerPage
provider_slug: partnerpage
slug: partnerpage-eligibility
source_date: '2026-11-10'
source_filename: partnerpage-eligibility.yml
source_heading: Eligibility
source_page: https://www.partnerpage.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PartnerPage\naid: partnerpage\nurl: https://www.partnerpage.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The PartnerPage Directory Service is hosted by servers located in the United States. Using the PartnerPage\n    Directory Service may be prohibited or restricted in certain other countries.\nentity_types:\n- type: business\n  text: means the vendor of a software-as-a-service or similar offering that has entered into a Subscription Agreement\n    with PartnerPage\nrestricted_uses:\n- summary: Competitive build or feature copying\n  text: (xii) access the\
  \ PartnerPage Directory Service in order to build a competitive product or service, or copy\n    any features, functions or graphics of the PartnerPage Directory Service;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: AFFIRM THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE\n    YOU RESIDE)\n"
source_yaml_url: https://artifacts.apis.io/partnerpage/eligibility/partnerpage-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from PartnerPage's own page on 2026-11-10.
synthetic: false
tags:
- Partners
- Directory
- Software-as-a-Service
- B2B
- No-Code
---
