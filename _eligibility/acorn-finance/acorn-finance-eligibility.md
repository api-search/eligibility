---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: 'IF YOU ARE LOCATED IN THE U . S . : THIS AGREEMENT CONTAINS CERTAI N DISCLAIMERS REGARDING WARRANTIES AND LIABILITY'
  entity_types:
  - text: You will only use your User Account for personal, non-commercial purposes.
    type: individual
  minimum_age:
    text: You are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Credit report access under false pretenses
    text: You are not permitted to use our Services to obtain any consumer credit report, score, or other consumer credit information under false pretenses or in violation of any applicable law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You have a valid Canadian social insurance number or U.S. Social Security Number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Acorn Finance
provenance_date: '2026-11-09'
provider_name: Acorn Finance
provider_slug: acorn-finance
slug: acorn-finance-eligibility
source_date: '2026-11-09'
source_filename: acorn-finance-eligibility.yml
source_heading: Eligibility
source_page: https://www.acornfinance.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acorn Finance\naid: acorn-finance\nurl: https://www.acornfinance.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: 'IF YOU ARE LOCATED IN THE U . S . : THIS AGREEMENT CONTAINS CERTAI N DISCLAIMERS REGARDING WARRANTIES AND\n    LIABILITY'\nentity_types:\n- type: individual\n  text: You will only use your User Account for personal, non-commercial purposes.\nrestricted_uses:\n- summary: Credit report access under false pretenses\n  text: You are not permitted to use our Services to obtain any consumer credit report, score, or other consumer\n\
  \    credit information under false pretenses or in violation of any applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You have a valid Canadian social insurance number or U.S. Social Security Number.\nminimum_age:\n  value: '18'\n  text: You are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/acorn-finance/eligibility/acorn-finance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Acorn Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Lending
- Loans
- Home Improvement
- Embedded Finance
- Point-of-Sale
- Consumer Finance
- Fintech
- Webhook
---
