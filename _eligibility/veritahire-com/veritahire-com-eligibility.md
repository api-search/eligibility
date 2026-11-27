---
api_specs:
- filename: veritahire-com-account-api-openapi.yml
  format: yaml
  label: veritahire-com Account API
  slug: veritahire-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-account-api-openapi.yml
- filename: veritahire-com-employer-profile-api-openapi.yml
  format: yaml
  label: veritahire-com Employer profile API
  slug: veritahire-com-employer-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-employer-profile-api-openapi.yml
- filename: veritahire-com-free-no-key-api-openapi.yml
  format: yaml
  label: veritahire-com Free, no key API
  slug: veritahire-com-free-no-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-free-no-key-api-openapi.yml
- filename: veritahire-com-hiring-market-php-api-openapi.yml
  format: yaml
  label: veritahire-com Hiring Market.php API
  slug: veritahire-com-hiring-market-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-hiring-market-php-api-openapi.yml
- filename: veritahire-com-hiring-velocity-api-openapi.yml
  format: yaml
  label: veritahire-com Hiring velocity API
  slug: veritahire-com-hiring-velocity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-hiring-velocity-api-openapi.yml
- filename: veritahire-com-postings-api-openapi.yml
  format: yaml
  label: veritahire-com Postings API
  slug: veritahire-com-postings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-postings-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 and able to form a binding agreement.
    type: individual
  minimum_age:
    text: You must be at least 16 and able to form a binding agreement.
    value: '16'
  restricted_uses:
  - summary: Unlawful or malicious uploads
    text: Don’t upload anything unlawful, infringing, or containing malware.
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
name: veritahire-com
provenance_date: '2026-11-10'
provider_name: veritahire-com
provider_slug: veritahire-com
slug: veritahire-com-eligibility
source_date: '2026-11-10'
source_filename: veritahire-com-eligibility.yml
source_heading: Eligibility
source_page: https://veritahire.com/terms.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: veritahire-com\naid: veritahire-com\nurl: https://veritahire.com/terms.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 and able to form a binding agreement.\nrestricted_uses:\n- summary: Unlawful or malicious uploads\n  text: Don’t upload anything unlawful, infringing, or containing malware.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 and able to form a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/veritahire-com/eligibility/veritahire-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from veritahire-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Job
- Hiring
- Data
---
