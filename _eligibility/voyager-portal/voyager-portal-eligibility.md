---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal use only
    text: Voyager will provide Customer with access to the Service during the Term (as defined below) solely for Customer’s internal use for the number of Authorized Users set forth in the applicable P.O..
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
name: Voyager Portal
provenance_date: '2026-11-10'
provider_name: Voyager Portal
provider_slug: voyager-portal
slug: voyager-portal-eligibility
source_date: '2026-11-10'
source_filename: voyager-portal-eligibility.yml
source_heading: Eligibility
source_page: https://www.voyagerportal.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voyager Portal\naid: voyager-portal\nurl: https://www.voyagerportal.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Internal use only\n  text: Voyager will provide Customer with access to the Service during the Term (as defined below) solely for Customer’s\n    internal use for the number of Authorized Users set forth in the applicable P.O..\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/voyager-portal/eligibility/voyager-portal-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Voyager Portal's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Maritime
- Shipping
- Logistics
- Demurrage
- Laytime
- Voyages
- Workflows
- Bulk Commodities
---
