---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Fundable.com or any affiliated services may not be used by persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Multi-level marketing, home-based business services, adult content
    text: These include Multi Level Marketers, Home Based Business Services, and just about anything that has to do with pornography or adult entertainment.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Only users who are manually approved will be able to launch a campaign on the site. All startups are thoroughly vetted prior to launching a campaign
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fundable
provenance_date: '2026-11-09'
provider_name: Fundable
provider_slug: fundable
slug: fundable-eligibility
source_date: '2026-11-09'
source_filename: fundable-eligibility.yml
source_heading: Eligibility
source_page: https://www.fundable.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fundable\naid: fundable\nurl: https://www.fundable.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Multi-level marketing, home-based business services, adult content\n  text: These include Multi Level Marketers, Home Based Business Services, and just about anything that has to do\n    with pornography or adult entertainment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Only users who are manually approved will be able to launch a campaign on the site. All startups are thoroughly\n\
  \    vetted prior to launching a campaign\nminimum_age:\n  value: '18'\n  text: Fundable.com or any affiliated services may not be used by persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/fundable/eligibility/fundable-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Fundable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fundraising
- Startups
- Crowdfunding
- Investor
- Fintech
- Software-as-a-Service
---
