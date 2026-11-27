---
api_specs:
- filename: connells-branches-api-openapi.yml
  format: yaml
  label: Connells Group Branches API
  slug: connells-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connells/openapi/connells-branches-api-openapi.yml
- filename: connells-locations-api-openapi.yml
  format: yaml
  label: Connells Group Locations API
  slug: connells-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connells/openapi/connells-locations-api-openapi.yml
- filename: connells-people-api-openapi.yml
  format: yaml
  label: Connells Group People API
  slug: connells-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connells/openapi/connells-people-api-openapi.yml
- filename: connells-testimonials-api-openapi.yml
  format: yaml
  label: Connells Group Testimonials API
  slug: connells-testimonials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/connells/openapi/connells-testimonials-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: the information on the Site is directed solely at those who access the Site from the United Kingdom (of Great Britain and Northern Ireland) and at those who are residents of the United Kingdom
  minimum_age:
    text: If you register with us or make any on-line electronic application (or other electronic communication), you are stating that you are eighteen [18] years of age or over.
    value: '18'
  restricted_uses:
  - summary: Using address information to contact parties
    text: Where address information is located on connells.co.uk, in our details, code, reports, forms and search results, you may not use such information to contact any party.
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
name: Connells Group
provenance_date: '2026-11-09'
provider_name: Connells Group
provider_slug: connells
slug: connells-eligibility
source_date: '2026-11-09'
source_filename: connells-eligibility.yml
source_heading: Eligibility
source_page: https://www.connellsgroup.co.uk/legal-notices/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Connells Group\naid: connells\nurl: https://www.connellsgroup.co.uk/legal-notices/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: the information on the Site is directed solely at those who access the Site from the United Kingdom (of\n    Great Britain and Northern Ireland) and at those who are residents of the United Kingdom\nentity_types: []\nrestricted_uses:\n- summary: Using address information to contact parties\n  text: Where address information is located on connells.co.uk, in our details, code, reports, forms and search\n    results, you may not use such information\
  \ to contact any party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you register with us or make any on-line electronic application (or other electronic communication),\n    you are stating that you are eighteen [18] years of age or over.\n"
source_yaml_url: https://artifacts.apis.io/connells/eligibility/connells-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Connells Group's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- United Kingdom
- Property Listings
- Brokerage
- Estate Agency
- Rentals
- Valuation
- Conveyancing
- Mortgage
- Property Management
- Auctions
- PropTech
---
