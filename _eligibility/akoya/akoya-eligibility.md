---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you may use the DAN only if you are located within the United States, even if you are able to access the DAN from outside the United States.
  entity_types:
  - text: The DAN is intended for use only by individuals who have an Account (such individuals, “Registered Users”).
    type: individual
  - text: if you are accepting these Terms on behalf of a company or other legal entity, that legal entity.
    type: business
  minimum_age:
    text: at least 18 years of age (or the minimum age in your jurisdiction for entering into a binding contract)
    value: '18'
  restricted_uses:
  - summary: No fraudulent or illegal use
    text: use the DAN or the Site in connection with any fraudulent or illegal conduct, transaction, or business
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: you must be authorized by a Data Provider, a Data Recipient, or directly by Akoya and register for an account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Akoya
provenance_date: '2026-11-09'
provider_name: Akoya
provider_slug: akoya
slug: akoya-eligibility
source_date: '2026-11-09'
source_filename: akoya-eligibility.yml
source_heading: Eligibility
source_page: https://akoya.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Akoya\naid: akoya\nurl: https://akoya.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you may use the DAN only if you are located within the United States, even if you are able to access the\n    DAN from outside the United States.\nentity_types:\n- type: individual\n  text: The DAN is intended for use only by individuals who have an Account (such individuals, “Registered Users”).\n- type: business\n  text: if you are accepting these Terms on behalf of a company or other legal entity, that legal entity.\nrestricted_uses:\n- summary: No fraudulent or illegal\
  \ use\n  text: use the DAN or the Site in connection with any fraudulent or illegal conduct, transaction, or business\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: you must be authorized by a Data Provider, a Data Recipient, or directly by Akoya and register for an account\nminimum_age:\n  value: '18'\n  text: at least 18 years of age (or the minimum age in your jurisdiction for entering into a binding contract)\n"
source_yaml_url: https://artifacts.apis.io/akoya/eligibility/akoya-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Akoya's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Open Banking
- Open Finance
- Aggregator
- Data Access Network
- Tokenized
- Consumer-Permissioned
- FDX
- Account Aggregation
- United States
- Data Aggregation
---
