---
api_specs:
- filename: wappalyzer-metadata-api-openapi.yml
  format: yaml
  label: Wappalyzer Metadata API
  slug: wappalyzer-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-metadata-api-openapi.yml
- filename: wappalyzer-basics-api-openapi.yml
  format: yaml
  label: Wappalyzer Basics API
  slug: wappalyzer-basics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-basics-api-openapi.yml
- filename: wappalyzer-lists-api-openapi.yml
  format: yaml
  label: Wappalyzer Lists API
  slug: wappalyzer-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-lists-api-openapi.yml
- filename: wappalyzer-lookup-api-openapi.yml
  format: yaml
  label: Wappalyzer Lookup API
  slug: wappalyzer-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-lookup-api-openapi.yml
- filename: wappalyzer-subdomains-api-openapi.yml
  format: yaml
  label: Wappalyzer Subdomains API
  slug: wappalyzer-subdomains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-subdomains-api-openapi.yml
- filename: wappalyzer-verify-api-openapi.yml
  format: yaml
  label: Wappalyzer Verify API
  slug: wappalyzer-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wappalyzer/openapi/wappalyzer-verify-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: To comply with the Spam Act 2003, we do not supply email addresses and phone numbers if you are in Australia or carry on business or activities in Australia.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No spam or unlawful marketing
    text: Do not use contact details included in the data to send spam or other unlawful marketing communications.
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
name: Wappalyzer
provenance_date: '2026-11-10'
provider_name: Wappalyzer
provider_slug: wappalyzer
slug: wappalyzer-eligibility
source_date: '2026-11-10'
source_filename: wappalyzer-eligibility.yml
source_heading: Eligibility
source_page: https://www.wappalyzer.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wappalyzer\naid: wappalyzer\nurl: https://www.wappalyzer.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: To comply with the Spam Act 2003, we do not supply email addresses and phone numbers if you are in Australia\n    or carry on business or activities in Australia.\nentity_types: []\nrestricted_uses:\n- summary: No spam or unlawful marketing\n  text: Do not use contact details included in the data to send spam or other unlawful marketing communications.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/wappalyzer/eligibility/wappalyzer-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Wappalyzer's own page on 2026-11-10.
synthetic: false
tags:
- Technology Detection
- Technographics
- Website Analysis
- CMS Detection
- Framework Detection
- Lead Enrichment
- Sales Intelligence
- Subdomain Discovery
- Email Verification
- Market Research
- Data Enrichment
---
