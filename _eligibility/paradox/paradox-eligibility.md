---
api_specs:
- filename: paradox-authentication-api-openapi.yml
  format: yaml
  label: Paradox Authentication API
  slug: paradox-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-authentication-api-openapi.yml
- filename: paradox-candidate-attributes-api-openapi.yml
  format: yaml
  label: Paradox Candidate Attributes API
  slug: paradox-candidate-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-candidate-attributes-api-openapi.yml
- filename: paradox-candidates-api-openapi.yml
  format: yaml
  label: Paradox Candidates API
  slug: paradox-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-candidates-api-openapi.yml
- filename: paradox-company-api-openapi.yml
  format: yaml
  label: Paradox Company API
  slug: paradox-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-company-api-openapi.yml
- filename: paradox-location-areas-api-openapi.yml
  format: yaml
  label: Paradox Location Areas API
  slug: paradox-location-areas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-location-areas-api-openapi.yml
- filename: paradox-location-rooms-api-openapi.yml
  format: yaml
  label: Paradox Location Rooms API
  slug: paradox-location-rooms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-location-rooms-api-openapi.yml
- filename: paradox-locations-api-openapi.yml
  format: yaml
  label: Paradox Locations API
  slug: paradox-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-locations-api-openapi.yml
- filename: paradox-reporting-api-openapi.yml
  format: yaml
  label: Paradox Reporting API
  slug: paradox-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-reporting-api-openapi.yml
- filename: paradox-scheduling-api-openapi.yml
  format: yaml
  label: Paradox Scheduling API
  slug: paradox-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-scheduling-api-openapi.yml
- filename: paradox-user-permissions-api-openapi.yml
  format: yaml
  label: Paradox User Permissions API
  slug: paradox-user-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-user-permissions-api-openapi.yml
- filename: paradox-users-api-openapi.yml
  format: yaml
  label: Paradox Users API
  slug: paradox-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paradox/openapi/paradox-users-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated employment decisions require human oversight
    text: use the Cloud Software for any automated decision-marking purposes (such as employment decisions) that have legal effects, unless Client ensures a human being makes, reviews, or oversees the final decisions
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
name: Paradox
provenance_date: '2026-11-10'
provider_name: Paradox
provider_slug: paradox
slug: paradox-eligibility
source_date: '2026-11-10'
source_filename: paradox-eligibility.yml
source_heading: Eligibility
source_page: https://www.paradox.ai/legal/service-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paradox\naid: paradox\nurl: https://www.paradox.ai/legal/service-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Automated employment decisions require human oversight\n  text: use the Cloud Software for any automated decision-marking purposes (such as employment decisions) that have\n    legal effects, unless Client ensures a human being makes, reviews, or oversees the final decisions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paradox/eligibility/paradox-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Paradox's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Candidate Screening
- Chatbots
- Conversational AI
- Hiring Automation
- HR Technology
- Interview Scheduling
- Recruiting
- SMS
- Talent Acquisition
---
