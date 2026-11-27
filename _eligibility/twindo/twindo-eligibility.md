---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and certify that you are of legal age to form a binding contract
    type: individual
  - text: you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: To register for the Service, you must be 13 years or over.
    value: '13'
  restricted_uses:
  - summary: Minors may not submit Content
    text: Minors may not submit Content to the Service.
  - summary: Personal non-commercial use only
    text: for your personal, non-commercial use only
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
name: Twindo
provenance_date: '2026-11-10'
provider_name: Twindo
provider_slug: twindo
slug: twindo-eligibility
source_date: '2026-11-10'
source_filename: twindo-eligibility.yml
source_heading: Eligibility
source_page: https://www.twindo.com/occipital-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Twindo\naid: twindo\nurl: https://www.twindo.com/occipital-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and certify that you are of legal age to form a binding contract\n- type: business\n  text: you are accepting these Terms (on behalf of yourself or the entity that you represent)\nrestricted_uses:\n- summary: Minors may not submit Content\n  text: Minors may not submit Content to the Service.\n- summary: Personal non-commercial use only\n  text: for your personal, non-commercial use only\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To register for the Service, you must be 13 years or over.\n"
source_yaml_url: https://artifacts.apis.io/twindo/eligibility/twindo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Twindo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Spatial Intelligence
- LiDAR
- Scan to CAD
- BIM
- Digital Twin
- Reality Capture
- Architecture
- Construction
- Interior Design
---
