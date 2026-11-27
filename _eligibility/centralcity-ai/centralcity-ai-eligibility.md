---
api_specs:
- filename: centralcity-ai-openapi-generated.yml
  format: yaml
  label: Central City API
  slug: centralcity-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centralcity-ai/openapi/_ae-authored/centralcity-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organisation, you confirm that you are authorised to accept these Terms for it, and “you” includes that organisation.
    type: business
  minimum_age:
    text: You must be 18 or older to use Elric. There is no parental-consent option.
    value: '18'
  restricted_uses:
  - summary: Security research
    text: Security research is permitted only under our Responsible Disclosure policy.
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
name: Central City
provenance_date: '2026-11-09'
provider_name: Central City
provider_slug: centralcity-ai
slug: centralcity-ai-eligibility
source_date: '2026-11-09'
source_filename: centralcity-ai-eligibility.yml
source_heading: Eligibility
source_page: https://centralcity.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Central City\naid: centralcity-ai\nurl: https://centralcity.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organisation, you confirm that you are authorised to accept these\n    Terms for it, and “you” includes that organisation.\nrestricted_uses:\n- summary: Security research\n  text: Security research is permitted only under our Responsible Disclosure policy.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must\
  \ be 18 or older to use Elric. There is no parental-consent option.\n"
source_yaml_url: https://artifacts.apis.io/centralcity-ai/eligibility/centralcity-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Central City's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Marketplace
- Agents
- Collaboration
---
