---
api_specs:
- filename: cycognito-assets-api-openapi.yml
  format: yaml
  label: CyCognito Assets API
  slug: cycognito-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-assets-api-openapi.yml
- filename: cycognito-audit-logs-api-openapi.yml
  format: yaml
  label: CyCognito Audit Logs API
  slug: cycognito-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-audit-logs-api-openapi.yml
- filename: cycognito-cloud-connectors-api-openapi.yml
  format: yaml
  label: CyCognito Cloud Connectors API
  slug: cycognito-cloud-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-cloud-connectors-api-openapi.yml
- filename: cycognito-export-data-api-openapi.yml
  format: yaml
  label: CyCognito Export Data API
  slug: cycognito-export-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-export-data-api-openapi.yml
- filename: cycognito-issues-api-openapi.yml
  format: yaml
  label: CyCognito Issues API
  slug: cycognito-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-issues-api-openapi.yml
- filename: cycognito-organizations-api-openapi.yml
  format: yaml
  label: CyCognito Organizations API
  slug: cycognito-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-organizations-api-openapi.yml
- filename: cycognito-realm-api-openapi.yml
  format: yaml
  label: CyCognito Realm API
  slug: cycognito-realm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-realm-api-openapi.yml
- filename: cycognito-reports-api-openapi.yml
  format: yaml
  label: CyCognito Reports API
  slug: cycognito-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-reports-api-openapi.yml
- filename: cycognito-revalidation-api-openapi.yml
  format: yaml
  label: CyCognito Revalidation API
  slug: cycognito-revalidation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-revalidation-api-openapi.yml
- filename: cycognito-scope-management-api-openapi.yml
  format: yaml
  label: CyCognito Scope Management API
  slug: cycognito-scope-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-scope-management-api-openapi.yml
- filename: cycognito-users-api-openapi.yml
  format: yaml
  label: CyCognito Users API
  slug: cycognito-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-users-api-openapi.yml
- filename: cycognito-verify-ips-api-openapi.yml
  format: yaml
  label: CyCognito Verify IPs API
  slug: cycognito-verify-ips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cycognito/openapi/cycognito-verify-ips-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Client or you means a legal entity which has a signed agreement or binding purchase order with CyCognito for the provision of Service to that entity.
    type: business
  minimum_age:
    text: you represent and warrant that you are of legal age and have the right and authority to enter into these Terms on your own behalf
    value: null
  restricted_uses:
  - summary: Unlawful or harmful purposes
    text: use the Service and/or Website in any unlawful manner or for any harmful, irresponsible or inappropriate purpose, or in breach of these Terms.
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
name: CyCognito
provenance_date: '2026-11-09'
provider_name: CyCognito
provider_slug: cycognito
slug: cycognito-eligibility
source_date: '2026-11-09'
source_filename: cycognito-eligibility.yml
source_heading: Eligibility
source_page: https://www.cycognito.com/terms-of-service.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CyCognito\naid: cycognito\nurl: https://www.cycognito.com/terms-of-service.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Client or you means a legal entity which has a signed agreement or binding purchase order with CyCognito\n    for the provision of Service to that entity.\nrestricted_uses:\n- summary: Unlawful or harmful purposes\n  text: use the Service and/or Website in any unlawful manner or for any harmful, irresponsible or inappropriate\n    purpose, or in breach of these Terms.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent and warrant that you are of legal age and have the right and authority to enter into these\n    Terms on your own behalf\n"
source_yaml_url: https://artifacts.apis.io/cycognito/eligibility/cycognito-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CyCognito's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Attack Surface Management
- Exposure Management
- Security
- Vulnerability Management
- Cloud Security
- API Security
---
