---
api_specs:
- filename: rightmove-property-api-openapi.yml
  format: yaml
  label: Rightmove Property API
  slug: rightmove-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightmove/openapi/rightmove-property-api-openapi.yml
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: The Platform is directed to individuals residing in the United Kingdom.
  entity_types:
  - text: Registration is only permitted for natural persons who are 18 years or older.
    type: individual
  - text: If you are acting in the course of business, you may use the Platform to search for commercial property listings.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: You must not misuse the Platform, or use the Platform in any unlawful manner or for any unlawful purpose, or act fraudulently or maliciously.
  - summary: Impersonation or false enquiries
    text: You must not use the Platform to impersonate others, submit false or misleading information, or harass, abuse, or defame any individual or organisation.
  - source: https://api-docs.rightmove.co.uk/terms
    summary: Internal use only; no resale
    text: We only supply the Specification for internal use by Your business, and You agree not to use the Specification for any re-sale purposes or commercial exploitation save for the operation of Your Customer Records Management (CRM) system.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may refuse your application for registration at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rightmove
provenance_date: '2026-11-10'
provider_name: Rightmove
provider_slug: rightmove
slug: rightmove-eligibility
source_date: '2026-11-10'
source_filename: rightmove-eligibility.yml
source_heading: Eligibility
source_page: https://www.rightmove.co.uk/c/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rightmove\naid: rightmove\nurl: https://www.rightmove.co.uk/c/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://api-docs.rightmove.co.uk/terms\n  - https://www.rightmove.co.uk/c/terms-of-use/\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: The Platform is directed to individuals residing in the United Kingdom.\nentity_types:\n- type: individual\n  text: Registration is only permitted for natural persons who are 18 years or older.\n- type: business\n  text: If you are acting in the course of business, you may use the Platform to search for commercial property\n    listings.\nrestricted_uses:\n\
  - summary: Unlawful or fraudulent use\n  text: You must not misuse the Platform, or use the Platform in any unlawful manner or for any unlawful purpose,\n    or act fraudulently or maliciously.\n- summary: Impersonation or false enquiries\n  text: You must not use the Platform to impersonate others, submit false or misleading information, or harass,\n    abuse, or defame any individual or organisation.\n- summary: Internal use only; no resale\n  text: We only supply the Specification for internal use by Your business, and You agree not to use the Specification\n    for any re-sale purposes or commercial exploitation save for the operation of Your Customer Records Management\n    (CRM) system.\n  source: https://api-docs.rightmove.co.uk/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We may refuse your application for registration at our discretion.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/rightmove/eligibility/rightmove-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Rightmove's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- United Kingdom
- Property Listings
- Property Portal
- PropTech
- Rentals
- Commercial Real Estate
- Data Feed
---
