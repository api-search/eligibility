---
api_specs:
- filename: revinate-hotel-sets-api-openapi.yml
  format: yaml
  label: Revinate Hotel Sets API
  slug: revinate-hotel-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revinate/openapi/revinate-hotel-sets-api-openapi.yml
- filename: revinate-hotels-api-openapi.yml
  format: yaml
  label: Revinate Hotels API
  slug: revinate-hotels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revinate/openapi/revinate-hotels-api-openapi.yml
- filename: revinate-languages-api-openapi.yml
  format: yaml
  label: Revinate Languages API
  slug: revinate-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revinate/openapi/revinate-languages-api-openapi.yml
- filename: revinate-review-sites-api-openapi.yml
  format: yaml
  label: Revinate Review Sites API
  slug: revinate-review-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revinate/openapi/revinate-review-sites-api-openapi.yml
- filename: revinate-reviews-api-openapi.yml
  format: yaml
  label: Revinate Reviews API
  slug: revinate-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revinate/openapi/revinate-reviews-api-openapi.yml
- filename: revinate-widget-reviews-api-openapi.yml
  format: yaml
  label: Revinate Widget Reviews API
  slug: revinate-widget-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revinate/openapi/revinate-widget-reviews-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided within or in connection with your website use is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: If you are using the website on behalf of a legal entity, you represent that you are authorized to enter into an agreement on behalf of that legal entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use the website for any illegal or unauthorized purpose.
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
name: Revinate
provenance_date: '2026-11-10'
provider_name: Revinate
provider_slug: revinate
slug: revinate-eligibility
source_date: '2026-11-10'
source_filename: revinate-eligibility.yml
source_heading: Eligibility
source_page: https://www.revinate.com/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revinate\naid: revinate\nurl: https://www.revinate.com/website-terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided within or in connection with your website use is not intended for distribution\n    to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary\n    to law or regulation\nentity_types:\n- type: business\n  text: If you are using the website on behalf of a legal entity, you represent that you are authorized to enter\n    into an agreement on behalf of that legal entity.\nrestricted_uses:\n\
  - summary: Illegal or unauthorized purposes\n  text: You may not use the website for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/revinate/eligibility/revinate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Revinate's own page on 2026-11-10.
synthetic: false
tags:
- Hospitality
- Hotels
- Reviews
- Reputation Management
- Guest Data Platform
- CRM
- Sentiment Analysis
- Travel
- Marketing
- Customer Feedback
---
