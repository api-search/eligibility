---
api_specs:
- filename: cbre-real-estate-api-openapi.yml
  format: yaml
  label: CBRE Real Estate API
  slug: cbre-real-estate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cbre/openapi/cbre-real-estate-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: In order to use the site, you must be at least 18 years of age.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In the event that any area of the site requires you to register with us prior to our granting you access to such areas of the site, you agree to provide truthful information, including but not limited to a member name and password as well as your name, address, telephone number and a valid email address
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CBRE
provenance_date: '2026-11-09'
provider_name: CBRE
provider_slug: cbre
slug: cbre-eligibility
source_date: '2026-11-09'
source_filename: cbre-eligibility.yml
source_heading: Eligibility
source_page: https://www.cbre.com/about-us/disclaimer-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CBRE\naid: cbre\nurl: https://www.cbre.com/about-us/disclaimer-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In the event that any area of the site requires you to register with us prior to our granting you access\n    to such areas of the site, you agree to provide truthful information, including but not limited to a member\n    name and password as well as your name, address, telephone number and a valid email address\nminimum_age:\n  value: '18'\n\
  \  text: In order to use the site, you must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/cbre/eligibility/cbre-eligibility.yml
stated_fields:
- verification
- minimum_age
summary_line: 2 quoted statements, read from CBRE's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Commercial Real Estate
- Facilities Management
- Fortune 500
- Investment Management
- Property Management
- Real Estate
- Valuation
---
