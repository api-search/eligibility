---
api_specs:
- filename: attlaz-openapi-generated.yml
  format: yaml
  label: Attlaz API
  slug: attlaz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attlaz/openapi/_ae-authored/attlaz-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any person, firm or company (the “Customer”) under which the Supplier supplies the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content and illegal material
    text: 'The Customer shall not access, store, distribute or transmit any Viruses, or any material during the course of its use of the Services that: (a) is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing or racially or ethnically offensive'
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
name: Attlaz
provenance_date: '2026-11-09'
provider_name: Attlaz
provider_slug: attlaz
slug: attlaz-eligibility
source_date: '2026-11-09'
source_filename: attlaz-eligibility.yml
source_heading: Eligibility
source_page: https://attlaz.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Attlaz\naid: attlaz\nurl: https://attlaz.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: any person, firm or company (the “Customer”) under which the Supplier supplies the Services\nrestricted_uses:\n- summary: Prohibited content and illegal material\n  text: 'The Customer shall not access, store, distribute or transmit any Viruses, or any material during the course\n    of its use of the Services that: (a) is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing\n    or racially or ethnically offensive'\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/attlaz/eligibility/attlaz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Attlaz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- Automation
- Data Visualization
- Workflows
---
