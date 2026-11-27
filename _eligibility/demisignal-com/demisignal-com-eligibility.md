---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Paid plans are monthly or annual subscriptions processed by Paddle, our payment provider and merchant of record.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive use
    text: 'You agree not to use the Service: In any way that violates any applicable national or international law or regulation.'
  - summary: Monitoring only domains owned or authorized
    text: Continuous monitoring and scheduled re-scanning are intended for domains that you own or are otherwise authorized to assess.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Access to paid monitoring begins when your payment is approved.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DemiSignal
provenance_date: '2026-11-09'
provider_name: DemiSignal
provider_slug: demisignal-com
slug: demisignal-com-eligibility
source_date: '2026-11-09'
source_filename: demisignal-com-eligibility.yml
source_heading: Eligibility
source_page: https://demisignal.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DemiSignal\naid: demisignal-com\nurl: https://demisignal.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Paid plans are monthly or annual subscriptions processed by Paddle, our payment provider and merchant of\n    record.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: 'You agree not to use the Service: In any way that violates any applicable national or international law\n    or regulation.'\n- summary: Monitoring only domains owned or authorized\n  text: Continuous monitoring and scheduled re-scanning\
  \ are intended for domains that you own or are otherwise authorized\n    to assess.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Access to paid monitoring begins when your payment is approved.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/demisignal-com/eligibility/demisignal-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from DemiSignal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Authentication
- DMARC
- SPF
- DKIM
- Email Security
- DNS
- Domain Monitoring
- MCP
---
