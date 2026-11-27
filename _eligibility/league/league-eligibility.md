---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the customer set out on the Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities prohibited
    text: Develop any product or service intended for use in a high risk environment requiring failsafe performance
  - summary: Export restriction on SDKs
    text: nor may Customer export the SDKs from and outside New Zealand, the United States of America or Canada, except as permitted under the applicable Laws of New Zealand, the United States of America or Canada.
  - summary: Pre-market clearance required before marketing
    text: Customer will not market the Customer Developed Apps that require pre-market clearance or approval unless such clearance and approval has been obtained
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
name: League
provenance_date: '2026-11-09'
provider_name: League
provider_slug: league
slug: league-eligibility
source_date: '2026-11-09'
source_filename: league-eligibility.yml
source_heading: Eligibility
source_page: https://league.com/developer-program-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: League\naid: league\nurl: https://league.com/developer-program-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the customer set out on the Order Form\nrestricted_uses:\n- summary: High-risk activities prohibited\n  text: Develop any product or service intended for use in a high risk environment requiring failsafe performance\n- summary: Export restriction on SDKs\n  text: nor may Customer export the SDKs from and outside New Zealand, the United States of America or Canada, except\n    as permitted under the applicable Laws of\
  \ New Zealand, the United States of America or Canada.\n- summary: Pre-market clearance required before marketing\n  text: Customer will not market the Customer Developed Apps that require pre-market clearance or approval unless\n    such clearance and approval has been obtained\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/league/eligibility/league-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from League's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Health Benefits
- Interoperability
- FHIR
- Agents
- Artificial Intelligence
- Patient Engagement
- Insurance
- Software-as-a-Service
- Canada
---
