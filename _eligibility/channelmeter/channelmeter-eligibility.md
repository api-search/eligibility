---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Acceptable use policy limits on User Content
    text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content (i) that violates any third-party right
  - summary: Export restrictions
    text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Company, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: ChannelMeter
provenance_date: '2026-11-09'
provider_name: ChannelMeter
provider_slug: channelmeter
slug: channelmeter-eligibility
source_date: '2026-11-09'
source_filename: channelmeter-eligibility.yml
source_heading: Eligibility
source_page: https://channelmeter.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChannelMeter\naid: channelmeter\nurl: https://channelmeter.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: YOU ARE ACCEPTING THESE TERMS (ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT)\nrestricted_uses:\n- summary: Acceptable use policy limits on User Content\n  text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content (i)\n    that violates any third-party right\n- summary: Export restrictions\n  text: You agree not to export, reexport, or transfer, directly or indirectly,\
  \ any U.S. technical data acquired\n    from Company, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/channelmeter/eligibility/channelmeter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ChannelMeter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Creator Economy
- Creator Management
- Payments
- Payouts
- Analytics
- Influencer Marketing
- Fintech
---
