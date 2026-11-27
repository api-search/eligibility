---
api_specs:
- filename: cursor-audit-logs-api-openapi.yml
  format: yaml
  label: Cursor Audit Logs API
  slug: cursor-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-audit-logs-api-openapi.yml
- filename: cursor-groups-api-openapi.yml
  format: yaml
  label: Cursor Groups API
  slug: cursor-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-groups-api-openapi.yml
- filename: cursor-members-api-openapi.yml
  format: yaml
  label: Cursor Members API
  slug: cursor-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-members-api-openapi.yml
- filename: cursor-repo-blocklists-api-openapi.yml
  format: yaml
  label: Cursor Repo Blocklists API
  slug: cursor-repo-blocklists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-repo-blocklists-api-openapi.yml
- filename: cursor-spend-api-openapi.yml
  format: yaml
  label: Cursor Spend API
  slug: cursor-spend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-spend-api-openapi.yml
- filename: cursor-usage-api-openapi.yml
  format: yaml
  label: Cursor Usage API
  slug: cursor-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cursor/openapi/cursor-usage-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service may not be used in or for the benefit of, or exported or re-exported to (a) any U.S. embargoed country or territory or (b) any individual or entity with whom dealings are prohibited or restricted under applicable trade laws.
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction (e.g., 18 years old in the United States) or 18 years old, whichever is higher, to use the Service.
    value: '18'
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
name: Cursor
provenance_date: '2026-11-09'
provider_name: Cursor
provider_slug: cursor
slug: cursor-eligibility
source_date: '2026-11-09'
source_filename: cursor-eligibility.yml
source_heading: Eligibility
source_page: https://cursor.com/en-US/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cursor\naid: cursor\nurl: https://cursor.com/en-US/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service may not be used in or for the benefit of, or exported or re-exported to (a) any U.S. embargoed\n    country or territory or (b) any individual or entity with whom dealings are prohibited or restricted under applicable\n    trade laws.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least the age of majority in your\
  \ jurisdiction (e.g., 18 years old in the United States)\n    or 18 years old, whichever is higher, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cursor/eligibility/cursor-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Cursor's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Developer Tools
- Code Editor
- Agents
- IDE
- Cloud Agents
---
