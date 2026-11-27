---
api_specs:
- filename: scribe-documents-api-openapi.yml
  format: yaml
  label: Scribe Documents API
  slug: scribe-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scribe/openapi/scribe-documents-api-openapi.yml
- filename: scribe-search-api-openapi.yml
  format: yaml
  label: Scribe Search API
  slug: scribe-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scribe/openapi/scribe-search-api-openapi.yml
- filename: scribe-teams-api-openapi.yml
  format: yaml
  label: Scribe Teams API
  slug: scribe-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scribe/openapi/scribe-teams-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are (i) of legal age to form a binding contract; and (ii) not a person barred from using Company Properties under the laws of the United States, your place of residence, or any other applicable jurisdiction.
  entity_types:
  - text: The Services made available to you are workplace tools intended for use by businesses and organizations and their respective personnel, vendors and other individuals engaged with these entities for employment and business purposes, and not for personal, household or other consumer purposes.
    type: business
  minimum_age:
    text: You must be over 16 years of age to use the Services, and children under the age of 16 cannot use or register for the Services.
    value: over 16
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: use the Company Properties in violation of any applicable law, for illegal activities, for any fraudulent activity or purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree not to create an Account using a false identity or information, or on behalf of someone other than yourself.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scribe
provenance_date: '2026-11-10'
provider_name: Scribe
provider_slug: scribe
slug: scribe-eligibility
source_date: '2026-11-10'
source_filename: scribe-eligibility.yml
source_heading: Eligibility
source_page: https://scribe.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scribe\naid: scribe\nurl: https://scribe.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are (i) of legal age to form a binding contract; and (ii) not a person\n    barred from using Company Properties under the laws of the United States, your place of residence, or any other\n    applicable jurisdiction.\nentity_types:\n- type: business\n  text: The Services made available to you are workplace tools intended for use by businesses and organizations\n    and their respective personnel, vendors and other individuals\
  \ engaged with these entities for employment and\n    business purposes, and not for personal, household or other consumer purposes.\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: use the Company Properties in violation of any applicable law, for illegal activities, for any fraudulent\n    activity or purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree not to create an Account using a false identity or information, or on behalf of someone other\n    than yourself.\nminimum_age:\n  value: over 16\n  text: You must be over 16 years of age to use the Services, and children under the age of 16 cannot use or register\n    for the Services.\n"
source_yaml_url: https://artifacts.apis.io/scribe/eligibility/scribe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Scribe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Documentation
- Knowledge Management
- Search
- Workflows
- Process Documentation
- Enterprise
---
