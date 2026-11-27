---
api_specs:
- filename: latchbio-openapi-generated.yml
  format: yaml
  label: LatchBio API
  slug: latchbio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latchbio/openapi/_ae-authored/latchbio-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents that (i) Customer is not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: YOU MAY NOT ACCESS OR USE THE LATCHBIO PLATFORM OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    type: individual
  - text: ACCEPTING THIS AGREEMENT (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)
    type: business
  - text: If Customer is a government end user, then this provision also applies to Customer.
    type: government
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE LATCHBIO PLATFORM OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful Customer Content
    text: 'The Customer Content will not: (a) be deceptive, defamatory, obscene, pornographic or unlawful;'
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
name: LatchBio
provenance_date: '2026-11-09'
provider_name: LatchBio
provider_slug: latchbio
slug: latchbio-eligibility
source_date: '2026-11-09'
source_filename: latchbio-eligibility.yml
source_heading: Eligibility
source_page: https://wiki.latch.bio/resources/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LatchBio\naid: latchbio\nurl: https://wiki.latch.bio/resources/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents that (i) Customer is not located in a country that is subject to a U.S. Government embargo,\n    or that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: YOU MAY NOT ACCESS OR USE THE LATCHBIO PLATFORM OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS\n    OLD.\n- type: business\n  text: ACCEPTING THIS AGREEMENT (ON BEHALF OF YOURSELF OR THE ENTITY THAT\
  \ YOU REPRESENT)\n- type: government\n  text: If Customer is a government end user, then this provision also applies to Customer.\nrestricted_uses:\n- summary: Unlawful or harmful Customer Content\n  text: 'The Customer Content will not: (a) be deceptive, defamatory, obscene, pornographic or unlawful;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE LATCHBIO PLATFORM OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST 18 YEARS\n    OLD.\n"
source_yaml_url: https://artifacts.apis.io/latchbio/eligibility/latchbio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from LatchBio's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Lab Automation
- Data Analytics
- Machine Learning
- Platform
- Company
---
