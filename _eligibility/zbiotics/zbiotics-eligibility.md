---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Automated scraping and bulk account creation
    text: use software or automated agents or scripts to produce multiple accounts on the Site, or to generate automated searches, requests, or queries to (or to strip, scrape, or mine data from) the Site
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
name: ZBiotics
provenance_date: '2026-11-10'
provider_name: ZBiotics
provider_slug: zbiotics
slug: zbiotics-eligibility
source_date: '2026-11-10'
source_filename: zbiotics-eligibility.yml
source_heading: Eligibility
source_page: https://zbiotics.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZBiotics\naid: zbiotics\nurl: https://zbiotics.com/pages/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT\nrestricted_uses:\n- summary: Automated scraping and bulk account creation\n  text: use software or automated agents or scripts to produce multiple accounts on the Site, or to generate automated\n    searches, requests, or queries to (or to strip, scrape, or mine data from) the Site\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/zbiotics/eligibility/zbiotics-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ZBiotics's own page on 2026-11-10.
synthetic: false
tags:
- Biotechnology
- Probiotics
- Consumer Health
- Direct to Consumer
- E-Commerce
- Agentic Commerce
- MCP
- Universal Commerce Protocol
- Shopify
- Company
---
