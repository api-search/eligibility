---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and offered by us from our facilities in the United States of America. We make no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: You affirm that you are over 18 years of age or possess the legal capacity to enter into this Agreement
    type: individual
  - text: Users who are accessing the Service or posting content for or on behalf of a company, entity, or organization must be authorized representatives of such company, entity, or organization
    type: business
  minimum_age:
    text: The Service is not intended for minors under 18.
    value: '18'
  restricted_uses:
  - summary: Commercial or promotional use
    text: Without our prior written approval, Using the Service for commercial or promotional purposes
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
name: Execthread
provenance_date: '2026-11-09'
provider_name: Execthread
provider_slug: execthread
slug: execthread-eligibility
source_date: '2026-11-09'
source_filename: execthread-eligibility.yml
source_heading: Eligibility
source_page: https://execthread.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Execthread\naid: execthread\nurl: https://execthread.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and offered by us from our facilities in the United States of America. We make\n    no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You affirm that you are over 18 years of age or possess the legal capacity to enter into this Agreement\n- type: business\n  text: Users who are accessing the Service or posting content for or on behalf of a company, entity, or organization\n\
  \    must be authorized representatives of such company, entity, or organization\nrestricted_uses:\n- summary: Commercial or promotional use\n  text: Without our prior written approval, Using the Service for commercial or promotional purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is not intended for minors under 18.\n"
source_yaml_url: https://artifacts.apis.io/execthread/eligibility/execthread-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Execthread's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Executive Search
- Job
- Recruiting
- Careers
- Talent
- Networking
- Human Resources
---
