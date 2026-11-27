---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer’s represent that the individual executing the Order Form is entering into this Agreement on behalf of the entity identified on the Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitor access prohibited
    text: JazzHR’s direct competitors are prohibited from accessing the software and/or services provided by JazzHR, except with JazzHR’s prior express written consent.
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
name: JazzHR
provenance_date: '2026-11-09'
provider_name: JazzHR
provider_slug: jazzhr
slug: jazzhr-eligibility
source_date: '2026-11-09'
source_filename: jazzhr-eligibility.yml
source_heading: Eligibility
source_page: https://www.jazzhr.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JazzHR\naid: jazzhr\nurl: https://www.jazzhr.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer’s represent that the individual executing the Order Form is entering into this Agreement on behalf\n    of the entity identified on the Order Form\nrestricted_uses:\n- summary: Competitor access prohibited\n  text: JazzHR’s direct competitors are prohibited from accessing the software and/or services provided by JazzHR,\n    except with JazzHR’s prior express written consent.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jazzhr/eligibility/jazzhr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from JazzHR's own page on 2026-11-09.
synthetic: false
tags:
- Recruiting
- Applicant Tracking
- Small Business
- Hiring
- Software-as-a-Service
- Company
---
