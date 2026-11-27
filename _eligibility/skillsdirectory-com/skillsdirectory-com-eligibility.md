---
api_specs:
- filename: skillsdirectory-com-categories-api-openapi.yml
  format: yaml
  label: Skills Directory Categories API
  slug: skillsdirectory-com-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skillsdirectory-com/openapi/skillsdirectory-com-categories-api-openapi.yml
- filename: skillsdirectory-com-registry-api-openapi.yml
  format: yaml
  label: Skills Directory Registry API
  slug: skillsdirectory-com-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skillsdirectory-com/openapi/skillsdirectory-com-registry-api-openapi.yml
- filename: skillsdirectory-com-scan-api-openapi.yml
  format: yaml
  label: Skills Directory Scan API
  slug: skillsdirectory-com-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skillsdirectory-com/openapi/skillsdirectory-com-scan-api-openapi.yml
- filename: skillsdirectory-com-skills-api-openapi.yml
  format: yaml
  label: Skills Directory Skills API
  slug: skillsdirectory-com-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skillsdirectory-com/openapi/skillsdirectory-com-skills-api-openapi.yml
- filename: skillsdirectory-com-stats-api-openapi.yml
  format: yaml
  label: Skills Directory Stats API
  slug: skillsdirectory-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skillsdirectory-com/openapi/skillsdirectory-com-stats-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The price is shown on the Pro page and at checkout, and depends on the country you buy from.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You can sign in with GitHub. You're responsible for activity on your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Skills Directory
provenance_date: '2026-11-10'
provider_name: Skills Directory
provider_slug: skillsdirectory-com
slug: skillsdirectory-com-eligibility
source_date: '2026-11-10'
source_filename: skillsdirectory-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.skillsdirectory.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skills Directory\naid: skillsdirectory-com\nurl: https://www.skillsdirectory.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The price is shown on the Pro page and at checkout, and depends on the country you buy from.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You can sign in with GitHub. You're responsible for activity on your account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skillsdirectory-com/eligibility/skillsdirectory-com-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Skills Directory's own page on 2026-11-10.
synthetic: false
tags:
- Agent Skills
- AI Agents
- Claude
- Directory
- Security Scanning
---
