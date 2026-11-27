---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Products or services may not be available in all countries and jurisdictions.
  entity_types:
  - text: You also confirm that you are old enough in your country or state to enter into a binding contract.
    type: individual
  - text: If you use the Website on behalf of another person or organization, you confirm that you have authority to accept these Terms of Use for them.
    type: business
  minimum_age:
    text: You also confirm that you are old enough in your country or state to enter into a binding contract.
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: use the Website for any unlawful, unauthorized, fraudulent, or malicious purpose
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
name: Corebridge Financial
provenance_date: '2026-11-09'
provider_name: Corebridge Financial
provider_slug: corebridge-financial
slug: corebridge-financial-eligibility
source_date: '2026-11-09'
source_filename: corebridge-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.corebridgefinancial.com/privacy-security/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corebridge Financial\naid: corebridge-financial\nurl: https://www.corebridgefinancial.com/privacy-security/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Products or services may not be available in all countries and jurisdictions.\nentity_types:\n- type: individual\n  text: You also confirm that you are old enough in your country or state to enter into a binding contract.\n- type: business\n  text: If you use the Website on behalf of another person or organization, you confirm that you have authority\n    to accept these Terms of Use for them.\nrestricted_uses:\n-\
  \ summary: Unlawful or fraudulent use\n  text: use the Website for any unlawful, unauthorized, fraudulent, or malicious purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You also confirm that you are old enough in your country or state to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/corebridge-financial/eligibility/corebridge-financial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Corebridge Financial's own page on 2026-11-09.
synthetic: false
tags:
- AIG
- Annuities
- Financial Services
- Fortune 500
- Insurance
- K-12
- Life Insurance
- Retirement
- Variable Annuities
---
