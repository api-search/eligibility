---
api_specs:
- filename: codebahn-net-activitypub-api-openapi.yml
  format: yaml
  label: Codebahn Activitypub API
  slug: codebahn-net-activitypub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-activitypub-api-openapi.yml
- filename: codebahn-net-admin-api-openapi.yml
  format: yaml
  label: Codebahn Admin API
  slug: codebahn-net-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-admin-api-openapi.yml
- filename: codebahn-net-issue-api-openapi.yml
  format: yaml
  label: Codebahn Issue API
  slug: codebahn-net-issue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-issue-api-openapi.yml
- filename: codebahn-net-miscellaneous-api-openapi.yml
  format: yaml
  label: Codebahn Miscellaneous API
  slug: codebahn-net-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-miscellaneous-api-openapi.yml
- filename: codebahn-net-notification-api-openapi.yml
  format: yaml
  label: Codebahn Notification API
  slug: codebahn-net-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-notification-api-openapi.yml
- filename: codebahn-net-organization-api-openapi.yml
  format: yaml
  label: Codebahn Organization API
  slug: codebahn-net-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-organization-api-openapi.yml
- filename: codebahn-net-package-api-openapi.yml
  format: yaml
  label: Codebahn Package API
  slug: codebahn-net-package-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-package-api-openapi.yml
- filename: codebahn-net-repository-api-openapi.yml
  format: yaml
  label: Codebahn Repository API
  slug: codebahn-net-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-repository-api-openapi.yml
- filename: codebahn-net-settings-api-openapi.yml
  format: yaml
  label: Codebahn Settings API
  slug: codebahn-net-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-settings-api-openapi.yml
- filename: codebahn-net-user-api-openapi.yml
  format: yaml
  label: Codebahn User API
  slug: codebahn-net-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codebahn-net/openapi/codebahn-net-user-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual may create a personal account.
    type: individual
  - text: If you create an organisation and subscribe on behalf of a company, you agree to these Terms on behalf of that company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Classified information
    text: Store information that a government has classified at any level, for example RESTREINT, NATO RESTRICTED or above.
  - summary: Export-controlled data requiring provider blindness
    text: Store technical data under export controls that require the hosting provider to be unable to read it, such as ITAR or the EAR encryption carve-out.
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
name: Codebahn
provenance_date: '2026-11-09'
provider_name: Codebahn
provider_slug: codebahn-net
slug: codebahn-net-eligibility
source_date: '2026-11-09'
source_filename: codebahn-net-eligibility.yml
source_heading: Eligibility
source_page: https://codebahn.net/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codebahn\naid: codebahn-net\nurl: https://codebahn.net/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Any individual may create a personal account.\n- type: business\n  text: If you create an organisation and subscribe on behalf of a company, you agree to these Terms on behalf of\n    that company\nrestricted_uses:\n- summary: Classified information\n  text: Store information that a government has classified at any level, for example RESTREINT, NATO RESTRICTED\n    or above.\n- summary: Export-controlled data requiring provider\
  \ blindness\n  text: Store technical data under export controls that require the hosting provider to be unable to read it, such\n    as ITAR or the EAR encryption carve-out.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/codebahn-net/eligibility/codebahn-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Codebahn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Git Hosting
- Source Code Management
- Continuous Integration
- Forgejo
- Developer Tools
- EU Hosted
- Data Sovereignty
- MCP
---
