---
api_specs:
- filename: phosphorus-alerts-api-openapi.yml
  format: yaml
  label: Phosphorus Alerts API
  slug: phosphorus-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phosphorus/openapi/phosphorus-alerts-api-openapi.yml
- filename: phosphorus-device-api-openapi.yml
  format: yaml
  label: Phosphorus Device API
  slug: phosphorus-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phosphorus/openapi/phosphorus-device-api-openapi.yml
- filename: phosphorus-devices-api-openapi.yml
  format: yaml
  label: Phosphorus Devices API
  slug: phosphorus-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phosphorus/openapi/phosphorus-devices-api-openapi.yml
- filename: phosphorus-dynamic-scans-api-openapi.yml
  format: yaml
  label: Phosphorus Dynamic Scans API
  slug: phosphorus-dynamic-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phosphorus/openapi/phosphorus-dynamic-scans-api-openapi.yml
- filename: phosphorus-providers-api-openapi.yml
  format: yaml
  label: Phosphorus Providers API
  slug: phosphorus-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phosphorus/openapi/phosphorus-providers-api-openapi.yml
- filename: phosphorus-search-api-openapi.yml
  format: yaml
  label: Phosphorus Search API
  slug: phosphorus-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phosphorus/openapi/phosphorus-search-api-openapi.yml
- filename: phosphorus-sites-api-openapi.yml
  format: yaml
  label: Phosphorus Sites API
  slug: phosphorus-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phosphorus/openapi/phosphorus-sites-api-openapi.yml
- filename: phosphorus-vault-api-openapi.yml
  format: yaml
  label: Phosphorus Vault API
  slug: phosphorus-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phosphorus/openapi/phosphorus-vault-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Licensee” means the customer entity that purchases a limited license to the Software from the Licensor.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competing products or services
    text: developing, using, or providing a competing software product or service
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
name: Phosphorus
provenance_date: '2026-11-10'
provider_name: Phosphorus
provider_slug: phosphorus
slug: phosphorus-eligibility
source_date: '2026-11-10'
source_filename: phosphorus-eligibility.yml
source_heading: Eligibility
source_page: https://www.phosphorus.io:443/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phosphorus\naid: phosphorus\nurl: https://www.phosphorus.io:443/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Licensee” means the customer entity that purchases a limited license to the Software from the Licensor.\nrestricted_uses:\n- summary: Competing products or services\n  text: developing, using, or providing a competing software product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/phosphorus/eligibility/phosphorus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Phosphorus's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- xIoT Security
- IoT Security
- OT Security
- IoMT
- Asset Discovery
- Vulnerability Management
- Firmware Management
- Certificate Management
- Credential Management
- Critical Infrastructure
- Device Management
---
