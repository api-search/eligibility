---
api_specs:
- filename: microsoft-365-copilot-connectors-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot Connectors API
  slug: microsoft-365-copilot-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-connectors-api-openapi.yml
- filename: microsoft-365-copilot-external-items-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot External Items API
  slug: microsoft-365-copilot-external-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-external-items-api-openapi.yml
- filename: microsoft-365-copilot-search-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot Search API
  slug: microsoft-365-copilot-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-search-api-openapi.yml
- filename: microsoft-365-copilot-user-content-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot User Content API
  slug: microsoft-365-copilot-user-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-user-content-api-openapi.yml
- filename: microsoft-365-copilot-copilot-aiinteractionhistory-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot Copilot.ai Interaction History API
  slug: microsoft-365-copilot-copilot-aiinteractionhistory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-copilot-aiinteractionhistory-api-openapi.yml
- filename: microsoft-365-copilot-copilot-aiuser-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot Copilot.ai User API
  slug: microsoft-365-copilot-copilot-aiuser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-copilot-aiuser-api-openapi.yml
- filename: microsoft-365-copilot-copilot-copilotadmin-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot Copilot.copilot Admin API
  slug: microsoft-365-copilot-copilot-copilotadmin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-copilot-copilotadmin-api-openapi.yml
- filename: microsoft-365-copilot-copilot-copilotreportroot-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot Copilot.copilot Report Root API
  slug: microsoft-365-copilot-copilot-copilotreportroot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-copilot-copilotreportroot-api-openapi.yml
- filename: microsoft-365-copilot-copilot-copilotroot-actions-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot Copilot.copilot Root.Actions API
  slug: microsoft-365-copilot-copilot-copilotroot-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-copilot-copilotroot-actions-api-openapi.yml
- filename: microsoft-365-copilot-copilot-copilotroot-api-openapi.yml
  format: yaml
  label: Microsoft 365 Copilot Copilot.copilot Root API
  slug: microsoft-365-copilot-copilot-copilotroot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-365-copilot/openapi/microsoft-365-copilot-copilot-copilotroot-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unless otherwise specified, the Services are for your personal and non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI services restrictions
    text: You may not use the AI services to discover any underlying components of the models, algorithms, and systems.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If any of the Services requires you to open an account, you must complete the registration process by providing us with current, complete and accurate information as prompted by the applicable registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Microsoft 365 Copilot
provenance_date: '2026-11-10'
provider_name: Microsoft 365 Copilot
provider_slug: microsoft-365-copilot
slug: microsoft-365-copilot-eligibility
source_date: '2026-11-10'
source_filename: microsoft-365-copilot-eligibility.yml
source_heading: Eligibility
source_page: https://www.microsoft.com/en-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Microsoft 365 Copilot\naid: microsoft-365-copilot\nurl: https://www.microsoft.com/en-us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Unless otherwise specified, the Services are for your personal and non-commercial use.\nrestricted_uses:\n- summary: AI services restrictions\n  text: You may not use the AI services to discover any underlying components of the models, algorithms, and systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If any of the Services requires you to open\
  \ an account, you must complete the registration process by providing\n    us with current, complete and accurate information as prompted by the applicable registration form.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/microsoft-365-copilot/eligibility/microsoft-365-copilot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Microsoft 365 Copilot's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Copilot
- Enterprise
- LLM
- Microsoft 365
- Natural Language Processing
- Productivity
---
