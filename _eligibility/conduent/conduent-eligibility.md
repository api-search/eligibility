---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Conduent makes no representation that Materials, Software, products or services on this Site are available outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Government restricted rights
    text: 'U.S. Government Restricted Rights: The Software available on this Site and accompanying documentation that is downloaded from this Server for or on behalf of the United States of America, its agencies and/or instrumentalities are provided with Restricted Rights.'
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
name: Conduent
provenance_date: '2026-11-09'
provider_name: Conduent
provider_slug: conduent
slug: conduent-eligibility
source_date: '2026-11-09'
source_filename: conduent-eligibility.yml
source_heading: Eligibility
source_page: https://www.conduent.com/website-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conduent\naid: conduent\nurl: https://www.conduent.com/website-terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Conduent makes no representation that Materials, Software, products or services on this Site are available\n    outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Government restricted rights\n  text: 'U.S. Government Restricted Rights: The Software available on this Site and accompanying documentation that\n    is downloaded from this Server for or on behalf of the United States of America, its agencies and/or instrumentalities\n\
  \    are provided with Restricted Rights.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/conduent/eligibility/conduent-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Conduent's own page on 2026-11-09.
synthetic: false
tags:
- Business Process Services
- Technology
- Government
- Healthcare
- Transportation
- Financial Services
- Customer Experience
- Learning
- Webhook
---
