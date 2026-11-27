---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are entering into these Terms on your own behalf, that you are at least 18 years of age
    type: individual
  - text: if you are contracting on behalf of a company, or other legal entity, that you are at least 18 years of age and have the authority necessary to bind the company or other legal entity you represent to these Terms.
    type: business
  minimum_age:
    text: if you are entering into these Terms on your own behalf, that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Trial use limited to evaluation
    text: you may only use the Services for the limited trial period specified by us or on the Website at the time of the commencement of your trial period, solely for the purpose of evaluating the Services.
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
name: Carnot Fleet
provenance_date: '2026-11-09'
provider_name: Carnot Fleet
provider_slug: carnot-fleet
slug: carnot-fleet-eligibility
source_date: '2026-11-09'
source_filename: carnot-fleet-eligibility.yml
source_heading: Eligibility
source_page: https://carnotfleet.com/termsofuse.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carnot Fleet\naid: carnot-fleet\nurl: https://carnotfleet.com/termsofuse.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are entering into these Terms on your own behalf, that you are at least 18 years of age\n- type: business\n  text: if you are contracting on behalf of a company, or other legal entity, that you are at least 18 years of\n    age and have the authority necessary to bind the company or other legal entity you represent to these Terms.\nrestricted_uses:\n- summary: Trial use limited to evaluation\n  text:\
  \ you may only use the Services for the limited trial period specified by us or on the Website at the time\n    of the commencement of your trial period, solely for the purpose of evaluating the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are entering into these Terms on your own behalf, that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/carnot-fleet/eligibility/carnot-fleet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Carnot Fleet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cold Chain
- Logistics
- Supply Chain
- Refrigeration
- Temperature Monitoring
- IoT
- Fleet Management
- Hardware
---
