---
api_specs:
- filename: hasdata-com-amazon-openapi-generated.yml
  format: yaml
  label: hasdata-com amazon API
  slug: amazon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-amazon-openapi-generated.yml
- filename: hasdata-com-core-openapi-generated.yml
  format: yaml
  label: hasdata-com core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-core-openapi-generated.yml
- filename: hasdata-com-tiktok-openapi-generated.yml
  format: yaml
  label: hasdata-com tiktok API
  slug: tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-tiktok-openapi-generated.yml
- filename: hasdata-com-walmart-openapi-generated.yml
  format: yaml
  label: hasdata-com walmart API
  slug: walmart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-walmart-openapi-generated.yml
- filename: hasdata-com-yelp-openapi-generated.yml
  format: yaml
  label: hasdata-com yelp API
  slug: yelp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-yelp-openapi-generated.yml
- filename: hasdata-com-youtube-openapi-generated.yml
  format: yaml
  label: hasdata-com youtube API
  slug: youtube-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasdata-com/openapi/_ae-authored/hasdata-com-youtube-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Enterprise account usage is strictly limited to employees of the organization that has signed up for the enterprise account.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Eligibility determinations about individuals
    text: To make credit, insurance, employment, housing, or other eligibility determinations about any individual, or for any purpose regulated by the Fair Credit Reporting Act (FCRA) or similar laws;
  - summary: Stalking or harassment
    text: To engage in stalking, harassment, surveillance, or any activity intended to cause harm to an individual;
  - summary: Unlawful personal data compilation
    text: To compile, collect, or aggregate personal data in violation of any applicable data protection law
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
name: hasdata-com
provenance_date: '2026-11-09'
provider_name: hasdata-com
provider_slug: hasdata-com
slug: hasdata-com-eligibility
source_date: '2026-11-09'
source_filename: hasdata-com-eligibility.yml
source_heading: Eligibility
source_page: https://hasdata.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hasdata-com\naid: hasdata-com\nurl: https://hasdata.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Enterprise account usage is strictly limited to employees of the organization that has signed up for the\n    enterprise account.\nrestricted_uses:\n- summary: Eligibility determinations about individuals\n  text: To make credit, insurance, employment, housing, or other eligibility determinations about any individual,\n    or for any purpose regulated by the Fair Credit Reporting Act (FCRA) or similar laws;\n- summary:\
  \ Stalking or harassment\n  text: To engage in stalking, harassment, surveillance, or any activity intended to cause harm to an individual;\n- summary: Unlawful personal data compilation\n  text: To compile, collect, or aggregate personal data in violation of any applicable data protection law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hasdata-com/eligibility/hasdata-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from hasdata-com's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Data Pipeline
- Artificial Intelligence
- Automation
---
