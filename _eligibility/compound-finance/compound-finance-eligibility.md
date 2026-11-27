---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Interface is not offered to, and is not intended for use by, persons in any jurisdiction where such offer or use would be unlawful or would require the Foundation to obtain any license, registration, or authorization.
  entity_types:
  - text: you are at least 18 years of age (or the age of legal majority in your jurisdiction, if higher) and have full legal capacity to enter into these Terms
    type: individual
  - text: you are acting for business or professional purposes and not as a consumer, and, where you access any market-specific feature, you are a legal entity acting for business or institutional purposes
    type: business
  minimum_age:
    text: you are at least 18 years of age (or the age of legal majority in your jurisdiction, if higher)
    value: '18'
  restricted_uses:
  - summary: USDC market business use only
    text: By using any Market Feature you represent and warrant, on a continuing basis, that you are a legal entity acting for business or institutional purposes and not a consumer
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: The Foundation does not verify, and assumes no obligation to verify, the status, purpose or eligibility of any user
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Compound Finance
provenance_date: '2026-11-09'
provider_name: Compound Finance
provider_slug: compound-finance
slug: compound-finance-eligibility
source_date: '2026-11-09'
source_filename: compound-finance-eligibility.yml
source_heading: Eligibility
source_page: https://www.compound.xyz/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Compound Finance\naid: compound-finance\nurl: https://www.compound.xyz/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Interface is not offered to, and is not intended for use by, persons in any jurisdiction where such\n    offer or use would be unlawful or would require the Foundation to obtain any license, registration, or authorization.\nentity_types:\n- type: individual\n  text: you are at least 18 years of age (or the age of legal majority in your jurisdiction, if higher) and have\n    full legal capacity to enter into these Terms\n- type:\
  \ business\n  text: you are acting for business or professional purposes and not as a consumer, and, where you access any market-specific\n    feature, you are a legal entity acting for business or institutional purposes\nrestricted_uses:\n- summary: USDC market business use only\n  text: By using any Market Feature you represent and warrant, on a continuing basis, that you are a legal entity\n    acting for business or institutional purposes and not a consumer\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: The Foundation does not verify, and assumes no obligation to verify, the status, purpose or eligibility\n    of any user\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age (or the age of legal majority in your jurisdiction, if higher)\n"
source_yaml_url: https://artifacts.apis.io/compound-finance/eligibility/compound-finance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Compound Finance's own page on 2026-11-09.
synthetic: false
tags:
- DeFi
- Finance
- Lending
- Cryptocurrency
- Blockchain
---
