---
api_specs:
- filename: crawlora-net-openapi-generated.yml
  format: yaml
  label: crawlora-net API
  slug: crawlora-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlora-net/openapi/_ae-authored/crawlora-net-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a region subject to comprehensive sanctions, and that you are not on any restricted party list.
  entity_types:
  - text: If you use Crawlora on behalf of a company or other organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated personal data
    text: collect children's data, health data, financial account data, government identifiers, biometric data, precise geolocation, or similarly regulated data without proper rights and legal basis;
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
name: crawlora-net
provenance_date: '2026-11-09'
provider_name: crawlora-net
provider_slug: crawlora-net
slug: crawlora-net-eligibility
source_date: '2026-11-09'
source_filename: crawlora-net-eligibility.yml
source_heading: Eligibility
source_page: https://crawlora.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: crawlora-net\naid: crawlora-net\nurl: https://crawlora.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, organized under the laws of, or ordinarily resident in a region\n    subject to comprehensive sanctions, and that you are not on any restricted party list.\nentity_types:\n- type: business\n  text: If you use Crawlora on behalf of a company or other organization, you represent that you have authority\n    to bind that organization.\nrestricted_uses:\n- summary: Regulated personal data\n  text: collect children's data, health data,\
  \ financial account data, government identifiers, biometric data, precise\n    geolocation, or similarly regulated data without proper rights and legal basis;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crawlora-net/eligibility/crawlora-net-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from crawlora-net's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Scraping
- Artificial Intelligence
- Data
- MCP
---
