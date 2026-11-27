---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Embargoed Countries are excluded from use of the Services; governing-law list names the United States, European Union, United Kingdom, Republic of Ireland, Canada, Australia, New Zealand, and others by region.
  minimum_age:
    text: You declare that You have the legal capacity to enter into the Subscription Agreement (including any minimum legal age requirements that may be applicable).
    value: null
  restricted_uses:
  - summary: Consumer or competitor access
    text: If You are a consumer, a direct competitor of ours, or intend to use the Services for monitoring or benchmarking purposes or any competitive analysis, You are prohibited from accessing the Services.
  - summary: Embargoed and restricted parties
    text: Using the Services in or for the benefit of, export or re-export (a) into any Embargoed Countries; b) to anyone on the Restricted Party Lists.
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
name: Docket Alarm
provenance_date: '2026-11-09'
provider_name: Docket Alarm
provider_slug: docket-alarm
slug: docket-alarm-eligibility
source_date: '2026-11-09'
source_filename: docket-alarm-eligibility.yml
source_heading: Eligibility
source_page: https://www.docketalarm.com/TermsOfService
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docket Alarm\naid: docket-alarm\nurl: https://www.docketalarm.com/TermsOfService\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Embargoed Countries are excluded from use of the Services; governing-law list names the United States, European\n    Union, United Kingdom, Republic of Ireland, Canada, Australia, New Zealand, and others by region.\nentity_types: []\nrestricted_uses:\n- summary: Consumer or competitor access\n  text: If You are a consumer, a direct competitor of ours, or intend to use the Services for monitoring or benchmarking\n    purposes or any competitive analysis,\
  \ You are prohibited from accessing the Services.\n- summary: Embargoed and restricted parties\n  text: Using the Services in or for the benefit of, export or re-export (a) into any Embargoed Countries; b) to\n    anyone on the Restricted Party Lists.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You declare that You have the legal capacity to enter into the Subscription Agreement (including any minimum\n    legal age requirements that may be applicable).\n"
source_yaml_url: https://artifacts.apis.io/docket-alarm/eligibility/docket-alarm-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Docket Alarm's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Litigation
- Data
---
