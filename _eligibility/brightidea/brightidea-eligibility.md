---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Subscriber represents that it is not a citizen of an embargoed country or prohibited end user under applicable U.S. export and anti-terrorism laws, regulations and lists.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competitor access
    text: access or use the Services if Subscriber is a direct competitor of Brightidea
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
name: Brightidea
provenance_date: '2026-11-09'
provider_name: Brightidea
provider_slug: brightidea
slug: brightidea-eligibility
source_date: '2026-11-09'
source_filename: brightidea-eligibility.yml
source_heading: Eligibility
source_page: https://www.brightidea.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brightidea\naid: brightidea\nurl: https://www.brightidea.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Subscriber represents that it is not a citizen of an embargoed country or prohibited end user under applicable\n    U.S. export and anti-terrorism laws, regulations and lists.\nentity_types: []\nrestricted_uses:\n- summary: No competitor access\n  text: access or use the Services if Subscriber is a direct competitor of Brightidea\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brightidea/eligibility/brightidea-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Brightidea's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Innovation
- Software
- Collaboration
- Enterprise
---
