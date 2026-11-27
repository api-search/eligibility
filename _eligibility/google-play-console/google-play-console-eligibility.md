---
api_specs:
- filename: google-play-console-anomalies-api-openapi.yml
  format: yaml
  label: Google Play Console Developer Reporting Play Console Anomalies API
  slug: google-play-console-anomalies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-play-console/openapi/google-play-console-anomalies-api-openapi.yml
- filename: google-play-console-apps-api-openapi.yml
  format: yaml
  label: Google Play Console Developer Reporting Play Console Apps API
  slug: google-play-console-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-play-console/openapi/google-play-console-apps-api-openapi.yml
- filename: google-play-console-vitals-api-openapi.yml
  format: yaml
  label: Google Play Console Developer Reporting Play Console Vitals API
  slug: google-play-console-vitals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-play-console/openapi/google-play-console-vitals-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Google entities are listed by location (US, Ireland, Singapore); the page does not state which countries are served or excluded, beyond export control and sanctions compliance requirements.
  entity_types:
  - text: If You are agreeing to be bound by this Agreement on behalf of Your employer or other entity, You represent and warrant that You have full legal authority to bind Your employer or such entity to this Agreement.
    type: business
  - text: 'If You are accepting the Agreement on behalf of a United States government entity or a United States city, county, or state government entity, then the following applies instead of the foregoing: the parties agree to remain silent regarding governing law and venue.'
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and sanctions compliance
    text: YOU AGREE TO COMPLY WITH, AND NOT CAUSE GOOGLE TO VIOLATE, ALL EXPORT CONTROL AND SANCTIONS LAWS AND REGULATIONS THAT APPLY TO YOUR DISTRIBUTION OR USE OF PRODUCTS
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Google will not permit the distribution of Your Products through Google Play, and You may not accept the Agreement, unless You are verified as a Developer in good standing.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Play Console Developer Reporting
provenance_date: '2026-11-09'
provider_name: Google Play Console Developer Reporting
provider_slug: google-play-console
slug: google-play-console-eligibility
source_date: '2026-11-09'
source_filename: google-play-console-eligibility.yml
source_heading: Eligibility
source_page: https://play.google/developer-distribution-agreement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Play Console Developer Reporting\naid: google-play-console\nurl: https://play.google/developer-distribution-agreement.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Google entities are listed by location (US, Ireland, Singapore); the page does not state which countries\n    are served or excluded, beyond export control and sanctions compliance requirements.\nentity_types:\n- type: business\n  text: If You are agreeing to be bound by this Agreement on behalf of Your employer or other entity, You represent\n    and warrant that You have full legal authority to bind Your\
  \ employer or such entity to this Agreement.\n- type: government\n  text: 'If You are accepting the Agreement on behalf of a United States government entity or a United States city,\n    county, or state government entity, then the following applies instead of the foregoing: the parties agree to\n    remain silent regarding governing law and venue.'\nrestricted_uses:\n- summary: Export control and sanctions compliance\n  text: YOU AGREE TO COMPLY WITH, AND NOT CAUSE GOOGLE TO VIOLATE, ALL EXPORT CONTROL AND SANCTIONS LAWS AND REGULATIONS\n    THAT APPLY TO YOUR DISTRIBUTION OR USE OF PRODUCTS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Google will not permit the distribution of Your Products through Google Play, and You may not accept the\n    Agreement, unless You are verified as a Developer in good standing.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-play-console/eligibility/google-play-console-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Google Play Console Developer Reporting's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Android
- Application
- Google Play Console
- Quality
- Reporting
---
