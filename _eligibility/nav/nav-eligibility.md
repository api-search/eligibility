---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services made available through the Websites are intended for use by U.S. users only.
  entity_types:
  - text: By registering, you certify that you are eighteen (18) years of age or older.
    type: individual
  minimum_age:
    text: By registering, you certify that you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Authorized users only for secure areas
    text: Your access to and use of password protected and/or secure areas of the Product Websites are restricted to authorized users only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To request a credit report or score, or purchase any Product, you must have an address within the United States, provide a valid Social Security number, address, email address and date of birth and agree to be bound by these Terms and Conditions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nav
provenance_date: '2026-11-10'
provider_name: Nav
provider_slug: nav
slug: nav-eligibility
source_date: '2026-11-10'
source_filename: nav-eligibility.yml
source_heading: Eligibility
source_page: https://www.nav.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nav\naid: nav\nurl: https://www.nav.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services made available through the Websites are intended for use by U.S. users only.\nentity_types:\n- type: individual\n  text: By registering, you certify that you are eighteen (18) years of age or older.\nrestricted_uses:\n- summary: Authorized users only for secure areas\n  text: Your access to and use of password protected and/or secure areas of the Product Websites are restricted\n    to authorized users only.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: To request a credit report or score, or purchase any Product, you must have an address within the United\n    States, provide a valid Social Security number, address, email address and date of birth and agree to be bound\n    by these Terms and Conditions.\nminimum_age:\n  value: '18'\n  text: By registering, you certify that you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/nav/eligibility/nav-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Nav's own page on 2026-11-10.
synthetic: false
tags:
- Business Credit
- Small Business
- Financial Services
- Embedded Finance
- Lending
- Credit Score
- Credit Reporting
- Financing Marketplace
- Fintech
- Partner API
---
