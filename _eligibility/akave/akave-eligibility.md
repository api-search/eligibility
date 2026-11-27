---
api_specs:
- filename: akave-buckets-api-openapi.yml
  format: yaml
  label: Akave Buckets API
  slug: akave-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akave/openapi/akave-buckets-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an entity that is purchasing or registering (or that has purchased or registered) for access to the Data Storage Service
    type: business
  - text: an individual employee or representative of a Subscriber who accesses or uses the Data Storage Service as an authorized user of such Subscriber
    type: individual
  minimum_age:
    text: AFFIRM THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU RESIDE)
    value: '18'
  restricted_uses:
  - summary: Regulated data needs prior written consent
    text: You shall not (and if you are a Subscriber, you shall ensure that your Authorized Users do not) provide Akave with any Data containing or constituting health or medical data
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Akave may choose not to accept Orders at its sole and absolute discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Akave
provenance_date: '2026-11-09'
provider_name: Akave
provider_slug: akave
slug: akave-eligibility
source_date: '2026-11-09'
source_filename: akave-eligibility.yml
source_heading: Eligibility
source_page: https://akave.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Akave\naid: akave\nurl: https://akave.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: an entity that is purchasing or registering (or that has purchased or registered) for access to the Data\n    Storage Service\n- type: individual\n  text: an individual employee or representative of a Subscriber who accesses or uses the Data Storage Service as\n    an authorized user of such Subscriber\nrestricted_uses:\n- summary: Regulated data needs prior written consent\n  text: You shall not (and if you are a Subscriber, you\
  \ shall ensure that your Authorized Users do not) provide\n    Akave with any Data containing or constituting health or medical data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Akave may choose not to accept Orders at its sole and absolute discretion.\nminimum_age:\n  value: '18'\n  text: AFFIRM THAT YOU ARE AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE\n    YOU RESIDE)\n"
source_yaml_url: https://artifacts.apis.io/akave/eligibility/akave-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Akave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Object Storage
- S3 Compatible
- Decentralized Storage
- Cloud Storage
- gRPC
- MCP
---
