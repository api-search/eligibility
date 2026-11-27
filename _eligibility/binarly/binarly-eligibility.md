---
api_specs:
- filename: binarly-assistant-api-openapi.yml
  format: yaml
  label: Binarly Assistant API
  slug: binarly-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-assistant-api-openapi.yml
- filename: binarly-chart-api-openapi.yml
  format: yaml
  label: Binarly Chart API
  slug: binarly-chart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-chart-api-openapi.yml
- filename: binarly-escalation-api-openapi.yml
  format: yaml
  label: Binarly Escalation API
  slug: binarly-escalation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-escalation-api-openapi.yml
- filename: binarly-file-api-openapi.yml
  format: yaml
  label: Binarly File API
  slug: binarly-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-file-api-openapi.yml
- filename: binarly-finding-api-openapi.yml
  format: yaml
  label: Binarly Finding API
  slug: binarly-finding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-finding-api-openapi.yml
- filename: binarly-grid-api-openapi.yml
  format: yaml
  label: Binarly Grid API
  slug: binarly-grid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-grid-api-openapi.yml
- filename: binarly-group-api-openapi.yml
  format: yaml
  label: Binarly Group API
  slug: binarly-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-group-api-openapi.yml
- filename: binarly-image-api-openapi.yml
  format: yaml
  label: Binarly Image API
  slug: binarly-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-image-api-openapi.yml
- filename: binarly-integration-api-openapi.yml
  format: yaml
  label: Binarly Integration API
  slug: binarly-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-integration-api-openapi.yml
- filename: binarly-notification-api-openapi.yml
  format: yaml
  label: Binarly Notification API
  slug: binarly-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-notification-api-openapi.yml
- filename: binarly-product-api-openapi.yml
  format: yaml
  label: Binarly Product API
  slug: binarly-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-product-api-openapi.yml
- filename: binarly-rolebinding-api-openapi.yml
  format: yaml
  label: Binarly RoleBinding API
  slug: binarly-rolebinding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-rolebinding-api-openapi.yml
- filename: binarly-scan-api-openapi.yml
  format: yaml
  label: Binarly Scan API
  slug: binarly-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-scan-api-openapi.yml
- filename: binarly-search-api-openapi.yml
  format: yaml
  label: Binarly Search API
  slug: binarly-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-search-api-openapi.yml
- filename: binarly-subscription-api-openapi.yml
  format: yaml
  label: Binarly Subscription API
  slug: binarly-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-subscription-api-openapi.yml
- filename: binarly-tempfile-api-openapi.yml
  format: yaml
  label: Binarly TempFile API
  slug: binarly-tempfile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-tempfile-api-openapi.yml
- filename: binarly-user-api-openapi.yml
  format: yaml
  label: Binarly User API
  slug: binarly-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-user-api-openapi.yml
- filename: binarly-userstorage-api-openapi.yml
  format: yaml
  label: Binarly UserStorage API
  slug: binarly-userstorage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-userstorage-api-openapi.yml
- filename: binarly-vulnerability-api-openapi.yml
  format: yaml
  label: Binarly Vulnerability API
  slug: binarly-vulnerability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-vulnerability-api-openapi.yml
- filename: binarly-custom-rules-api-openapi.yml
  format: yaml
  label: Binarly Custom Rules API
  slug: binarly-custom-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/binarly/openapi/binarly-custom-rules-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these terms and conditions
    type: business
  minimum_age:
    text: null
    value: null
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
name: Binarly
provenance_date: '2026-11-09'
provider_name: Binarly
provider_slug: binarly
slug: binarly-eligibility
source_date: '2026-11-09'
source_filename: binarly-eligibility.yml
source_heading: Eligibility
source_page: https://www.binarly.io/legal-and-compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Binarly\naid: binarly\nurl: https://www.binarly.io/legal-and-compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind such entity to these terms and conditions\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/binarly/eligibility/binarly-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Binarly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Firmware Security
- Supply Chain Security
- Vulnerability Management
- SBOM
- Binary Analysis
- Post-Quantum Cryptography
- UEFI
- DevSecOps
---
