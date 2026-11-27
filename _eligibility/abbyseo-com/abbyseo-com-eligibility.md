---
api_specs:
- filename: abbyseo-com-email-results-api-openapi.yml
  format: yaml
  label: Abby SEO Email Results API
  slug: abbyseo-com-email-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abbyseo-com/openapi/abbyseo-com-email-results-api-openapi.yml
- filename: abbyseo-com-scan-api-openapi.yml
  format: yaml
  label: Abby SEO Scan API
  slug: abbyseo-com-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abbyseo-com/openapi/abbyseo-com-scan-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old (or 16 in the EEA/UK) to use this Service.
    value: 13 (16 in EEA/UK); 18 or age of majority to purchase
  restricted_uses:
  - summary: Unauthorized scanning
    text: Scan websites you do not own or do not have explicit authorization to scan
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
name: Abby SEO
provenance_date: '2026-11-09'
provider_name: Abby SEO
provider_slug: abbyseo-com
slug: abbyseo-com-eligibility
source_date: '2026-11-09'
source_filename: abbyseo-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.abbyseo.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abby SEO\naid: abbyseo-com\nurl: https://www.abbyseo.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have the authority to\n    bind that organization to these Terms.\nrestricted_uses:\n- summary: Unauthorized scanning\n  text: Scan websites you do not own or do not have explicit authorization to scan\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 (16 in EEA/UK); 18 or age of majority\
  \ to purchase\n  text: You must be at least 13 years old (or 16 in the EEA/UK) to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/abbyseo-com/eligibility/abbyseo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Abby SEO's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- Audit
- Tool
- Free
- Websites
- Analytics
---
