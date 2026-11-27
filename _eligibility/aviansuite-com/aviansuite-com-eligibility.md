---
api_specs:
- filename: aviansuite-com-admin-api-openapi.yml
  format: yaml
  label: AvianSuite Admin API
  slug: aviansuite-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviansuite-com/openapi/aviansuite-com-admin-api-openapi.yml
- filename: aviansuite-com-events-api-openapi.yml
  format: yaml
  label: AvianSuite Events API
  slug: aviansuite-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviansuite-com/openapi/aviansuite-com-events-api-openapi.yml
- filename: aviansuite-com-health-api-openapi.yml
  format: yaml
  label: AvianSuite Health API
  slug: aviansuite-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviansuite-com/openapi/aviansuite-com-health-api-openapi.yml
- filename: aviansuite-com-refs-api-openapi.yml
  format: yaml
  label: AvianSuite Refs API
  slug: aviansuite-com-refs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviansuite-com/openapi/aviansuite-com-refs-api-openapi.yml
- filename: aviansuite-com-root-api-openapi.yml
  format: yaml
  label: AvianSuite Root API
  slug: aviansuite-com-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviansuite-com/openapi/aviansuite-com-root-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity
    type: individual
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: GLBA-violating use
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: AvianSuite
provenance_date: '2026-11-09'
provider_name: AvianSuite
provider_slug: aviansuite-com
slug: aviansuite-com-eligibility
source_date: '2026-11-09'
source_filename: aviansuite-com-eligibility.yml
source_heading: Eligibility
source_page: https://aviansuite.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AvianSuite\naid: aviansuite-com\nurl: https://aviansuite.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Industry-specific regulated data\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance\
  \ Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: GLBA-violating use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/aviansuite-com/eligibility/aviansuite-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AvianSuite's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Business Data
- Automation
- Platform
---
