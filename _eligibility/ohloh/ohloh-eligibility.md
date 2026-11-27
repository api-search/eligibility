---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this API Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No academic research
    text: and not for academic research. If you want to use the API Feature in support of academic research, please see the Academic Use License.
  - summary: Commercial distribution needs contact
    text: If you want to distribute or allow access to Applications for commercial purposes to end-users outside of your organization or company, please contact Open Hub Support at info@openhub.net.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must have a registered account on Open Hub to be issued an API key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ohloh
provenance_date: '2026-11-10'
provider_name: Ohloh
provider_slug: ohloh
slug: ohloh-eligibility
source_date: '2026-11-10'
source_filename: ohloh-eligibility.yml
source_heading: Eligibility
source_page: https://community.blackduck.com/s/article/Black-Duck-Open-Hub-API-Use-Agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ohloh\naid: ohloh\nurl: https://community.blackduck.com/s/article/Black-Duck-Open-Hub-API-Use-Agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this API Agreement on behalf of a company or other legal entity, you represent\n    that you have the authority to bind such entity\nrestricted_uses:\n- summary: No academic research\n  text: and not for academic research. If you want to use the API Feature in support of academic research, please\n    see the Academic Use License.\n- summary: Commercial distribution\
  \ needs contact\n  text: If you want to distribute or allow access to Applications for commercial purposes to end-users outside of\n    your organization or company, please contact Open Hub Support at info@openhub.net.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must have a registered account on Open Hub to be issued an API key.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ohloh/eligibility/ohloh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Ohloh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Open Source
- Open Source Directory
- Code Analytics
- Software Composition
- DEVELOPER DATA
- Project
- Contributors
- Black Duck
---
