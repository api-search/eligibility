---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: An Investor can be a person with full active legal capacity, who is a citizen or permanent resident of the Member State of the European Union (EU) or the European Economic Area (EEA)
  entity_types:
  - text: An Investor can be a person with full active legal capacity, who is a citizen or permanent resident of the Member State of the European Union (EU) or the European Economic Area (EEA)
    type: individual
  - text: The Invoice Seller can be a legal person entered in the register of a Member State of the EU or the EEA.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal transactions
    text: not use Investly for illegal transactions or operations, incl. fraud, money laundering and terrorism financing;
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: The Portal can only be accessed and used by a person who has been registered by the Portal Manager as a User
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Investly
provenance_date: '2026-11-09'
provider_name: Investly
provider_slug: investly
slug: investly-eligibility
source_date: '2026-11-09'
source_filename: investly-eligibility.yml
source_heading: Eligibility
source_page: https://www.investly.co/v6/%C3%BCldtingimused-en-0
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Investly\naid: investly\nurl: https://www.investly.co/v6/%C3%BCldtingimused-en-0\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: An Investor can be a person with full active legal capacity, who is a citizen or permanent resident of the\n    Member State of the European Union (EU) or the European Economic Area (EEA)\nentity_types:\n- type: individual\n  text: An Investor can be a person with full active legal capacity, who is a citizen or permanent resident of the\n    Member State of the European Union (EU) or the European Economic Area (EEA)\n- type: business\n\
  \  text: The Invoice Seller can be a legal person entered in the register of a Member State of the EU or the EEA.\nrestricted_uses:\n- summary: Illegal transactions\n  text: not use Investly for illegal transactions or operations, incl. fraud, money laundering and terrorism financing;\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: The Portal can only be accessed and used by a person who has been registered by the Portal Manager as a\n    User\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/investly/eligibility/investly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Investly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Invoice Finance
- Invoice Discounting
- Lending
- Working Capital
- SME Finance
- Marketplace
- Estonia
- United Kingdom
---
