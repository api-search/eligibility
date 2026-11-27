---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The services and information provided through this site are for financial advisor or financial institution use only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Advisor and institution use only
    text: The services and information provided through this site are for financial advisor or financial institution use only.
  - summary: Institutional audience only
    text: It is not intended for institutional investors in any jurisdiction in which distribution or purchase is not authorized.
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
name: Halo Investing
provenance_date: '2026-11-09'
provider_name: Halo Investing
provider_slug: halo-investing
slug: halo-investing-eligibility
source_date: '2026-11-09'
source_filename: halo-investing-eligibility.yml
source_heading: Eligibility
source_page: https://haloinvesting.com/important-disclosures/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halo Investing\naid: halo-investing\nurl: https://haloinvesting.com/important-disclosures/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The services and information provided through this site are for financial advisor or financial institution\n    use only.\nrestricted_uses:\n- summary: Advisor and institution use only\n  text: The services and information provided through this site are for financial advisor or financial institution\n    use only.\n- summary: Institutional audience only\n  text: It is not intended for institutional\
  \ investors in any jurisdiction in which distribution or purchase is\n    not authorized.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/halo-investing/eligibility/halo-investing-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Halo Investing's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- WealthTech
- Investing
- Structured Notes
- Annuities
- Insurance
- Broker-Dealer
- Capital Markets
- Wealth Management
---
