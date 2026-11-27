---
api_specs:
- filename: nvd-cpe-api-openapi.yml
  format: yaml
  label: NVD CPE API
  slug: nvd-cpe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-cpe-api-openapi.yml
- filename: nvd-cpe-match-api-openapi.yml
  format: yaml
  label: NVD CPE Match API
  slug: nvd-cpe-match-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-cpe-match-api-openapi.yml
- filename: nvd-cve-api-openapi.yml
  format: yaml
  label: NVD CVE API
  slug: nvd-cve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-cve-api-openapi.yml
- filename: nvd-cve-change-history-api-openapi.yml
  format: yaml
  label: NVD CVE Change History API
  slug: nvd-cve-change-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-cve-change-history-api-openapi.yml
- filename: nvd-sources-api-openapi.yml
  format: yaml
  label: NVD Sources API
  slug: nvd-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nvd/openapi/nvd-sources-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: More than the public rate limit requires that you register for an API key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NVD
provenance_date: '2026-11-10'
provider_name: NVD
provider_slug: nvd
slug: nvd-eligibility
source_date: '2026-11-10'
source_filename: nvd-eligibility.yml
source_heading: Eligibility
source_page: https://nvd.nist.gov/developers/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NVD\naid: nvd\nurl: https://nvd.nist.gov/developers/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: More than the public rate limit requires that you register for an API key.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nvd/eligibility/nvd-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from NVD's own page on 2026-11-10.
synthetic: false
tags:
- Security
- CVE
- CPE
- Vulnerabilities
- CVSS
- Vulnerability Management
---
