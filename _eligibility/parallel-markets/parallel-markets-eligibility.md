---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Website is not directed at, or intended for distribution to or use by, any person or entity who is a citizen or resident of or located in any jurisdiction where such distribution, publication, availability or use would be contrary to applicable law or regulation
  entity_types:
  - text: You are using the Website, Content and Services on your own behalf, on behalf of your organization or entity, or as an authorized agent, designee, or representative of another party.
    type: individual
  minimum_age:
    text: You are at least 18 years old, are of the age of majority in the jurisdiction in which you live or are otherwise able to enter contracts as an adult
    value: '18'
  restricted_uses:
  - summary: Securities-law compliance
    text: Use the Services in a way that violates the securities laws and regulations in the United States, or in the jurisdiction in which you are operating
  - summary: Recipients limited to compliance use
    text: If you are a recipient of information from our services, your use of our Services is strictly limited to compliance with regulatory or other legal obligations.
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
name: Parallel Markets
provenance_date: '2026-11-10'
provider_name: Parallel Markets
provider_slug: parallel-markets
slug: parallel-markets-eligibility
source_date: '2026-11-10'
source_filename: parallel-markets-eligibility.yml
source_heading: Eligibility
source_page: https://parallelmarkets.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parallel Markets\naid: parallel-markets\nurl: https://parallelmarkets.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Website is not directed at, or intended for distribution to or use by, any person or entity who is\n    a citizen or resident of or located in any jurisdiction where such distribution, publication, availability or\n    use would be contrary to applicable law or regulation\nentity_types:\n- type: individual\n  text: You are using the Website, Content and Services on your own behalf, on behalf of your organization or entity,\n    or as an authorized\
  \ agent, designee, or representative of another party.\nrestricted_uses:\n- summary: Securities-law compliance\n  text: Use the Services in a way that violates the securities laws and regulations in the United States, or in\n    the jurisdiction in which you are operating\n- summary: Recipients limited to compliance use\n  text: If you are a recipient of information from our services, your use of our Services is strictly limited to\n    compliance with regulatory or other legal obligations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old, are of the age of majority in the jurisdiction in which you live or are otherwise\n    able to enter contracts as an adult\n"
source_yaml_url: https://artifacts.apis.io/parallel-markets/eligibility/parallel-markets-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Parallel Markets's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity
- Identity Verification
- KYC
- AML
- Accreditation
- Compliance
- Financial Services
- Onboarding
- Investor Verification
- Webhook
---
