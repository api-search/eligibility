---
api_specs:
- filename: cleaninglab-databricks-industry-solutions-api-openapi.yml
  format: yaml
  label: Cleaninglab Databricks Industry Solutions API
  slug: cleaninglab-databricks-industry-solutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleaninglab/openapi/cleaninglab-databricks-industry-solutions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: business
  minimum_age:
    text: You represent that you are over the age of 18.
    value: '18'
  restricted_uses:
  - summary: Sanctions and restricted parties
    text: You are not listed on any United States government list of prohibited or restricted parties.
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
name: Cleaninglab
provenance_date: '2026-11-09'
provider_name: Cleaninglab
provider_slug: cleaninglab
slug: cleaninglab-eligibility
source_date: '2026-11-09'
source_filename: cleaninglab-eligibility.yml
source_heading: Eligibility
source_page: https://cleanlab.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleaninglab\naid: cleaninglab\nurl: https://cleanlab.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo\nentity_types:\n- type: business\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses:\n- summary: Sanctions and restricted parties\n  text: You are not listed on any United States government list of prohibited\
  \ or restricted parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/cleaninglab/eligibility/cleaninglab-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cleaninglab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Safety
- Monitoring
- Hallucination
---
