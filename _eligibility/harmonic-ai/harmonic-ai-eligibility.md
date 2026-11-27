---
api_specs:
- filename: harmonic-ai-companies-api-openapi.yml
  format: yaml
  label: Harmonic REST & GraphQL API
  slug: harmonic-rest-graphql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harmonic-ai/openapi/harmonic-ai-companies-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and operated from facilities in the United States. You may not use the Services if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: If you're using the Services for an organization, you're agreeing to this Agreement on behalf of that organization, and represent and warrant that you can do so.
    type: business
  minimum_age:
    text: The Services are not intended for and may not be used by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: FCRA consumer eligibility
    text: You will not use Company Data to determine a consumer’s eligibility for (a) credit or insurance for personal, family or household purposes, (b) employment, (c) a government license or benefit, or (d) any other purpose governed by the Fair Credit Reporting Act or any similar law.
  - summary: Excluded data submission
    text: 'You will not submit to the Services, including to any AI Feature: (a) payment card data; (b) protected health information or clinical data; (c) classified information'
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
name: Harmonic.ai
provenance_date: '2026-11-09'
provider_name: Harmonic.ai
provider_slug: harmonic-ai
slug: harmonic-ai-eligibility
source_date: '2026-11-09'
source_filename: harmonic-ai-eligibility.yml
source_heading: Eligibility
source_page: https://harmonic.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harmonic.ai\naid: harmonic-ai\nurl: https://harmonic.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and operated from facilities in the United States. You may not use the Services\n    if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked\n    or denied by the United States government.\nentity_types:\n- type: business\n  text: If you're using the Services for an organization, you're agreeing to this Agreement on behalf of that organization,\n    and represent and warrant\
  \ that you can do so.\nrestricted_uses:\n- summary: FCRA consumer eligibility\n  text: You will not use Company Data to determine a consumer’s eligibility for (a) credit or insurance for personal,\n    family or household purposes, (b) employment, (c) a government license or benefit, or (d) any other purpose\n    governed by the Fair Credit Reporting Act or any similar law.\n- summary: Excluded data submission\n  text: 'You will not submit to the Services, including to any AI Feature: (a) payment card data; (b) protected\n    health information or clinical data; (c) classified information'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for and may not be used by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/harmonic-ai/eligibility/harmonic-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Harmonic.ai's own page on 2026-11-09.
synthetic: false
tags:
- Startup Intelligence
- Venture Capital
- Company Data
- People Data
- investor-data
- Funding Data
- Data Enrichment
- Sales Intelligence
- Market Intelligence
- GraphQL
- MCP
- Agent-Native
---
