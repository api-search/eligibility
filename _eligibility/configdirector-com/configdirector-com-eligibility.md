---
api_specs:
- filename: configdirector-com-api-tokens-api-openapi.yml
  format: yaml
  label: ConfigDirector API tokens API
  slug: configdirector-com-api-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-api-tokens-api-openapi.yml
- filename: configdirector-com-configs-api-openapi.yml
  format: yaml
  label: ConfigDirector Configs API
  slug: configdirector-com-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-configs-api-openapi.yml
- filename: configdirector-com-discovery-api-openapi.yml
  format: yaml
  label: ConfigDirector Discovery API
  slug: configdirector-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-discovery-api-openapi.yml
- filename: configdirector-com-documentation-api-openapi.yml
  format: yaml
  label: ConfigDirector Documentation API
  slug: configdirector-com-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-documentation-api-openapi.yml
- filename: configdirector-com-environments-api-openapi.yml
  format: yaml
  label: ConfigDirector Environments API
  slug: configdirector-com-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-environments-api-openapi.yml
- filename: configdirector-com-projects-api-openapi.yml
  format: yaml
  label: ConfigDirector Projects API
  slug: configdirector-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-projects-api-openapi.yml
- filename: configdirector-com-scanned-repositories-api-openapi.yml
  format: yaml
  label: ConfigDirector Scanned repositories API
  slug: configdirector-com-scanned-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-scanned-repositories-api-openapi.yml
- filename: configdirector-com-segments-api-openapi.yml
  format: yaml
  label: ConfigDirector Segments API
  slug: configdirector-com-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-segments-api-openapi.yml
- filename: configdirector-com-tags-api-openapi.yml
  format: yaml
  label: ConfigDirector Tags API
  slug: configdirector-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-tags-api-openapi.yml
- filename: configdirector-com-webhooks-api-openapi.yml
  format: yaml
  label: ConfigDirector Webhooks API
  slug: configdirector-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configdirector-com/openapi/configdirector-com-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Not HIPAA/FISMA-regulated interactions
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: No GLBA-violating use
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
name: ConfigDirector
provenance_date: '2026-11-09'
provider_name: ConfigDirector
provider_slug: configdirector-com
slug: configdirector-com-eligibility
source_date: '2026-11-09'
source_filename: configdirector-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.configdirector.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConfigDirector\naid: configdirector-com\nurl: https://www.configdirector.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Not HIPAA/FISMA-regulated interactions\n\
  \  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: No GLBA-violating use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/configdirector-com/eligibility/configdirector-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ConfigDirector's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Feature Flags
- Remote Configuration
- Configuration Management
- Developer Tools
- OpenFeature
- SDKs
- MCP
---
