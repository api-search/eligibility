---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. government embargo, or that has been designated by the U.S. government as a “terrorist supporting” country
  entity_types:
  - text: If you will be using the Services on behalf of an organization, you agree to these Terms of Use on behalf of that organization
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: Commercial use restricted
    text: you will only use the Services for your own personal or internal business purposes and not for the purpose of commercializing or monetizing the Services, without the express written consent of Photobucket
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
name: Photobucket
provenance_date: '2026-11-10'
provider_name: Photobucket
provider_slug: photobucket
slug: photobucket-eligibility
source_date: '2026-11-10'
source_filename: photobucket-eligibility.yml
source_heading: Eligibility
source_page: https://photobucket.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Photobucket\naid: photobucket\nurl: https://photobucket.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. government embargo, or that has been designated\n    by the U.S. government as a “terrorist supporting” country\nentity_types:\n- type: business\n  text: If you will be using the Services on behalf of an organization, you agree to these Terms of Use on behalf\n    of that organization\nrestricted_uses:\n- summary: Commercial use restricted\n  text: you will only use the Services for your own personal\
  \ or internal business purposes and not for the purpose\n    of commercializing or monetizing the Services, without the express written consent of Photobucket\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/photobucket/eligibility/photobucket-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Photobucket's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Photo Sharing
- Image Hosting
- Video Sharing
- Cloud Storage
- Media
---
