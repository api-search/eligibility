---
api_specs:
- filename: evermuse-ingestion-api-openapi.yml
  format: yaml
  label: Evermuse Ingestion API
  slug: evermuse-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evermuse/openapi/evermuse-ingestion-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export and sanctions: Customer represents that it is not located in, and will not use the Service in, a jurisdiction subject to comprehensive sanctions'
  entity_types:
  - text: If the individual accepting these Terms does so on behalf of an organization, that individual represents that they are authorized to bind the organization, and “Customer” refers to that organization.
    type: business
  - text: If Customer is a government agency, department, or entity, the use, duplication, reproduction, release, modification, disclosure, or transfer of the Service or any related documentation is restricted by these Terms
    type: government
  minimum_age:
    text: Customer must be at least 18 years old and able to form a legally binding contract.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: use the Service to generate or disseminate content that is illegal, obscene, defamatory, threatening, harassing, hateful, or racially or ethnically offensive
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
name: Evermuse
provenance_date: '2026-11-09'
provider_name: Evermuse
provider_slug: evermuse
slug: evermuse-eligibility
source_date: '2026-11-09'
source_filename: evermuse-eligibility.yml
source_heading: Eligibility
source_page: https://www.evermuse.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evermuse\naid: evermuse\nurl: https://www.evermuse.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export and sanctions: Customer represents that it is not located in, and will not use the Service in, a\n    jurisdiction subject to comprehensive sanctions'\nentity_types:\n- type: business\n  text: If the individual accepting these Terms does so on behalf of an organization, that individual represents\n    that they are authorized to bind the organization, and “Customer” refers to that organization.\n- type: government\n  text: If Customer is a government agency, department,\
  \ or entity, the use, duplication, reproduction, release,\n    modification, disclosure, or transfer of the Service or any related documentation is restricted by these Terms\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: use the Service to generate or disseminate content that is illegal, obscene, defamatory, threatening, harassing,\n    hateful, or racially or ethnically offensive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Customer must be at least 18 years old and able to form a legally binding contract.\n"
source_yaml_url: https://artifacts.apis.io/evermuse/eligibility/evermuse-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Evermuse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Management
- Customer Feedback
- Voice of Customer
- Artificial Intelligence
- Data Ingestion
- Product Analytics
- MCP
- Developer Tools
---
