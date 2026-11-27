---
api_specs:
- filename: cosmic-ephemeris-calculations-api-openapi.yml
  format: yaml
  label: Cosmic Ephemeris Calculations API
  slug: cosmic-ephemeris-calculations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmic-ephemeris/openapi/cosmic-ephemeris-calculations-api-openapi.yml
- filename: cosmic-ephemeris-interpretation-api-openapi.yml
  format: yaml
  label: Cosmic Ephemeris Interpretation API
  slug: cosmic-ephemeris-interpretation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmic-ephemeris/openapi/cosmic-ephemeris-interpretation-api-openapi.yml
- filename: cosmic-ephemeris-pro-timeline-api-openapi.yml
  format: yaml
  label: Cosmic Ephemeris Pro timeline API
  slug: cosmic-ephemeris-pro-timeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmic-ephemeris/openapi/cosmic-ephemeris-pro-timeline-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is offered online to eligible adults and organizations internationally where both we and you may lawfully transact.
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract where you live.
    type: individual
  - text: If you use the Service for an organization, you represent that you have authority to bind it, and "you" includes that organization.
    type: business
  - text: The Service is designed for developers and businesses and is not directed to children.
    type: developer
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract where you live.
    value: '18'
  restricted_uses:
  - summary: High-impact decisions
    text: use the Service as the sole or determinative basis for medical, legal, financial, insurance, lending, employment, housing, education, immigration, emergency, safety-critical, or other high-impact decisions
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: New accounts follow the same signup acceptance and email-verification steps
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cosmic Ephemeris
provenance_date: '2026-11-09'
provider_name: Cosmic Ephemeris
provider_slug: cosmic-ephemeris
slug: cosmic-ephemeris-eligibility
source_date: '2026-11-09'
source_filename: cosmic-ephemeris-eligibility.yml
source_heading: Eligibility
source_page: https://cosmicephemeris.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cosmic Ephemeris\naid: cosmic-ephemeris\nurl: https://cosmicephemeris.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is offered online to eligible adults and organizations internationally where both we and you\n    may lawfully transact.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract where you live.\n- type: business\n  text: If you use the Service for an organization, you represent that you have authority to bind it, and \"you\"\n    includes that organization.\n- type: developer\n  text:\
  \ The Service is designed for developers and businesses and is not directed to children.\nrestricted_uses:\n- summary: High-impact decisions\n  text: use the Service as the sole or determinative basis for medical, legal, financial, insurance, lending, employment,\n    housing, education, immigration, emergency, safety-critical, or other high-impact decisions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: New accounts follow the same signup acceptance and email-verification steps\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract where you live.\n"
source_yaml_url: https://artifacts.apis.io/cosmic-ephemeris/eligibility/cosmic-ephemeris-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Cosmic Ephemeris's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- Developers
- Data
- U.S.-based
---
