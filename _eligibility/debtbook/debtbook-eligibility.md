---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: The Site is intended for users who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site.
    value: '18'
  restricted_uses:
  - summary: Regulated data uses
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: DebtBook
provenance_date: '2026-11-09'
provider_name: DebtBook
provider_slug: debtbook
slug: debtbook-eligibility
source_date: '2026-11-09'
source_filename: debtbook-eligibility.yml
source_heading: Eligibility
source_page: https://monetaryhq.com/terms-of-use/?from=debtbook
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DebtBook\naid: debtbook\nurl: https://monetaryhq.com/terms-of-use/?from=debtbook\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old.\nrestricted_uses:\n- summary: Regulated data uses\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance\
  \ Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: GLBA\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/debtbook/eligibility/debtbook-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from DebtBook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Treasury Management
- Government
- Public Finance
- Debt Management
- Cash Management
- Accounting
- Lease Accounting
- Investment Management
- Non-Profit
- Higher Education
- Healthcare
- Software-as-a-Service
---
