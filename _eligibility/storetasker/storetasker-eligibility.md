---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (c) are not a citizen or resident of a geographic area in which access to or use of the Storetasker Service is prohibited or otherwise barred by applicable law, rule, decree, regulation, treaty, or administrative act.
  entity_types:
  - text: Storetasker offers the Storetasker Service for your business purposes only and not for personal, household, or consumer use.
    type: business
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your jurisdiction in order to register for an account to use the Storetasker Service
    value: '18'
  restricted_uses:
  - summary: Business use only
    text: Storetasker offers the Storetasker Service for your business purposes only and not for personal, household, or consumer use.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: When you register for an Account and from time to time thereafter, your Account may be subject to verification, including, but not limited to, validation against third-party databases or the verification of one or more official government or legal documents that confirm your identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Storetasker
provenance_date: '2026-11-10'
provider_name: Storetasker
provider_slug: storetasker
slug: storetasker-eligibility
source_date: '2026-11-10'
source_filename: storetasker-eligibility.yml
source_heading: Eligibility
source_page: https://www.storetasker.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Storetasker\naid: storetasker\nurl: https://www.storetasker.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: (c) are not a citizen or resident of a geographic area in which access to or use of the Storetasker Service\n    is prohibited or otherwise barred by applicable law, rule, decree, regulation, treaty, or administrative act.\nentity_types:\n- type: business\n  text: Storetasker offers the Storetasker Service for your business purposes only and not for personal, household,\n    or consumer use.\nrestricted_uses:\n- summary: Business use\
  \ only\n  text: Storetasker offers the Storetasker Service for your business purposes only and not for personal, household,\n    or consumer use.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: When you register for an Account and from time to time thereafter, your Account may be subject to verification,\n    including, but not limited to, validation against third-party databases or the verification of one or more official\n    government or legal documents that confirm your identity\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority in your jurisdiction in order to register for an\n    account to use the Storetasker Service\n"
source_yaml_url: https://artifacts.apis.io/storetasker/eligibility/storetasker-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Storetasker's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Shopify
- E-Commerce
- Freelance
- Developers
- Direct to Consumer
---
