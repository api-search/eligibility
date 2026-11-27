---
api_specs:
- filename: scratchpay-borrower-application-api-openapi.yml
  format: yaml
  label: Scratchpay Borrower application API
  slug: scratchpay-borrower-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scratchpay/openapi/scratchpay-borrower-application-api-openapi.yml
- filename: scratchpay-borrower-application-result-api-openapi.yml
  format: yaml
  label: Scratchpay Borrower application result API
  slug: scratchpay-borrower-application-result-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scratchpay/openapi/scratchpay-borrower-application-result-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Members of the Scratchpay community must be U.S. Residents that are 18 years of age or older.
  entity_types:
  - text: Members of the Scratchpay community must be U.S. Residents that are 18 years of age or older. Children under the age of 18 are not eligible to participate in the offerings on this website.
    type: individual
  minimum_age:
    text: Members of the Scratchpay community must be U.S. Residents that are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your own personal, noncommercial use
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your eligibility for particular products or services is subject to final determination by Scratchpay.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scratchpay
provenance_date: '2026-11-10'
provider_name: Scratchpay
provider_slug: scratchpay
slug: scratchpay-eligibility
source_date: '2026-11-10'
source_filename: scratchpay-eligibility.yml
source_heading: Eligibility
source_page: https://scratchpay.com/legal/terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scratchpay\naid: scratchpay\nurl: https://scratchpay.com/legal/terms-of-services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Members of the Scratchpay community must be U.S. Residents that are 18 years of age or older.\nentity_types:\n- type: individual\n  text: Members of the Scratchpay community must be U.S. Residents that are 18 years of age or older. Children under\n    the age of 18 are not eligible to participate in the offerings on this website.\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your own personal, noncommercial use\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your eligibility for particular products or services is subject to final determination by Scratchpay.\nminimum_age:\n  value: '18'\n  text: Members of the Scratchpay community must be U.S. Residents that are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/scratchpay/eligibility/scratchpay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Scratchpay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financing
- Payments
- Lending
- Veterinary
- Healthcare
- Fintech
- Buy Now Pay Later
- Point-of-Sale
---
