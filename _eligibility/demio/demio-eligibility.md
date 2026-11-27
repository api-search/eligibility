---
api_specs:
- filename: demio-events-api-openapi.yml
  format: yaml
  label: Demio Events API
  slug: demio-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demio/openapi/demio-events-api-openapi.yml
- filename: demio-intro-api-openapi.yml
  format: yaml
  label: Demio Intro API
  slug: demio-intro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demio/openapi/demio-intro-api-openapi.yml
- filename: demio-reports-api-openapi.yml
  format: yaml
  label: Demio Reports API
  slug: demio-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demio/openapi/demio-reports-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are for professional/business use only.
    type: business
  minimum_age:
    text: To be eligible, a referrer must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: 'the Services are not designed or intended for access and/or use in or during high-risk activities, including but not limited to: medical procedures'
  - summary: Protected Health Information
    text: submit to, or store in the Services, any Protected Health Information (“PHI”) unless Customer has complied with all laws applicable to PHI and Section 5.1 below
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All Orders are subject to acceptance by Company in its discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Demio
provenance_date: '2026-11-09'
provider_name: Demio
provider_slug: demio
slug: demio-eligibility
source_date: '2026-11-09'
source_filename: demio-eligibility.yml
source_heading: Eligibility
source_page: https://www.demio.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Demio\naid: demio\nurl: https://www.demio.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are for professional/business use only.\nrestricted_uses:\n- summary: High-risk activities\n  text: 'the Services are not designed or intended for access and/or use in or during high-risk activities, including\n    but not limited to: medical procedures'\n- summary: Protected Health Information\n  text: submit to, or store in the Services, any Protected Health Information (“PHI”) unless Customer has complied\n\
  \    with all laws applicable to PHI and Section 5.1 below\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All Orders are subject to acceptance by Company in its discretion.\nminimum_age:\n  value: '18'\n  text: To be eligible, a referrer must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/demio/eligibility/demio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Demio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Webinars
- Virtual Events
- Event Management
- Marketing
- Marketing Technology
- Demand Generation
- Video
- Engagement Marketing
- Lead Generation
- Software-as-a-Service
---
