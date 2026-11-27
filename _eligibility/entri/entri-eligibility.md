---
api_specs:
- filename: entri-openapi-generated.yml
  format: yaml
  label: Entri API
  slug: entri-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/entri/openapi/_ae-authored/entri-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an Application Developer that does not have an existing contract or written agreement with Entri, then you will be automatically enrolled in our startup plan
    type: developer
  - text: 'If you are accepting on behalf of your employer or another entity, you represent and warrant that: (i) you have full legal authority to bind your employer or such entity to this Agreement'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or illegal purposes
    text: use the Platform for any fraudulent, illegal or misleading purpose
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
name: Entri
provenance_date: '2026-11-09'
provider_name: Entri
provider_slug: entri
slug: entri-eligibility
source_date: '2026-11-09'
source_filename: entri-eligibility.yml
source_heading: Eligibility
source_page: https://www.entri.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Entri\naid: entri\nurl: https://www.entri.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: If you are an Application Developer that does not have an existing contract or written agreement with Entri,\n    then you will be automatically enrolled in our startup plan\n- type: business\n  text: 'If you are accepting on behalf of your employer or another entity, you represent and warrant that: (i)\n    you have full legal authority to bind your employer or such entity to this Agreement'\nrestricted_uses:\n- summary:\
  \ Fraudulent or illegal purposes\n  text: use the Platform for any fraudulent, illegal or misleading purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/entri/eligibility/entri-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Entri's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Domain
- Integration
- Software-as-a-Service
---
