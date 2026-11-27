---
api_specs:
- filename: alpen-org-openapi-generated.yml
  format: yaml
  label: Alpen Labs API
  slug: alpen-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpen-org/openapi/_ae-authored/alpen-org-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided ... is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: you, whether personally or on behalf of an entity ("you")
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use the Services.
    value: '18'
  restricted_uses:
  - summary: No regulated or sensitive information
    text: The Services are not designed to receive or process protected health information, nonpublic financial information subject to sector-specific regulation, government-classified information, or other regulated or highly sensitive information.
  - summary: No high-impact decisions using Outputs
    text: Use Alpen Chat outputs to make decisions about another person in employment, housing, credit, education, healthcare, insurance, legal services, or another high-impact context.
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
name: Alpen Labs
provenance_date: '2026-11-09'
provider_name: Alpen Labs
provider_slug: alpen-org
slug: alpen-org-eligibility
source_date: '2026-11-09'
source_filename: alpen-org-eligibility.yml
source_heading: Eligibility
source_page: https://www.alpen.org/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alpen Labs\naid: alpen-org\nurl: https://www.alpen.org/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided ... is not intended for distribution to or use by any person or entity in any jurisdiction\n    or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: you, whether personally or on behalf of an entity (\"you\")\nrestricted_uses:\n- summary: No regulated or sensitive information\n\
  \  text: The Services are not designed to receive or process protected health information, nonpublic financial information\n    subject to sector-specific regulation, government-classified information, or other regulated or highly sensitive\n    information.\n- summary: No high-impact decisions using Outputs\n  text: Use Alpen Chat outputs to make decisions about another person in employment, housing, credit, education,\n    healthcare, insurance, legal services, or another high-impact context.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/alpen-org/eligibility/alpen-org-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Alpen Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
