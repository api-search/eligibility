---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Crowdcast
    type: individual
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial App licence
    text: to run the App solely for your own personal non-commercial purposes
  - summary: No commercial use of Services
    text: Use the Services, or any portion thereof, for any commercial purpose or for the benefit of any third party or in any manner not permitted by these Terms
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Crowdcast
provenance_date: '2026-11-09'
provider_name: Crowdcast
provider_slug: crowdcast
slug: crowdcast-eligibility
source_date: '2026-11-09'
source_filename: crowdcast-eligibility.yml
source_heading: Eligibility
source_page: https://www.crowdcast.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crowdcast\naid: crowdcast\nurl: https://www.crowdcast.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Crowdcast\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such\
  \ as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Personal non-commercial App licence\n  text: to run the App solely for your own personal non-commercial purposes\n- summary: No commercial use of Services\n  text: Use the Services, or any portion thereof, for any commercial purpose or for the benefit of any third party\n    or in any manner not permitted by these Terms\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/crowdcast/eligibility/crowdcast-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Crowdcast's own page on 2026-11-09.
synthetic: false
tags:
- Video
- Live Streaming
- Webinars
- Community
- Software-as-a-Service
---
