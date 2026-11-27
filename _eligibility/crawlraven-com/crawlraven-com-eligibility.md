---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to use CrawlRaven.
    value: '16'
  restricted_uses:
  - summary: MCP client cannot change Google services or administration
    text: This permission does not let the client change Google services, sites, targets, opportunities, derived events, billing, or administration, and MCP cannot permanently delete annotations.
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
name: CrawlRaven
provenance_date: '2026-11-09'
provider_name: CrawlRaven
provider_slug: crawlraven-com
slug: crawlraven-com-eligibility
source_date: '2026-11-09'
source_filename: crawlraven-com-eligibility.yml
source_heading: Eligibility
source_page: https://crawlraven.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CrawlRaven\naid: crawlraven-com\nurl: https://crawlraven.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: MCP client cannot change Google services or administration\n  text: This permission does not let the client change Google services, sites, targets, opportunities, derived events,\n    billing, or administration, and MCP cannot permanently delete annotations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use\
  \ CrawlRaven.\n"
source_yaml_url: https://artifacts.apis.io/crawlraven-com/eligibility/crawlraven-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from CrawlRaven's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- Search Console
- Google Analytics
- Technical SEO Audit
- Analytics
- MCP
- Marketing
---
