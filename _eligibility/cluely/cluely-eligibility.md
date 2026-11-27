---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: use the Services from an embargoed nation or any other country/region that becomes an embargoed nation
  entity_types:
  - text: If you are accessing or using the Services on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  - text: The following applies to consumer users of the Services, inclusive of the Free and Pro plans
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed countries
    text: use the Services from an embargoed nation or any other country/region that becomes an embargoed nation
  - summary: Unlawful or infringing content
    text: use the Services to post or send infringing, obscene, threatening, libelous, or otherwise unlawful material
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
name: Cluely
provenance_date: '2026-11-09'
provider_name: Cluely
provider_slug: cluely
slug: cluely-eligibility
source_date: '2026-11-09'
source_filename: cluely-eligibility.yml
source_heading: Eligibility
source_page: https://cluely.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cluely\naid: cluely\nurl: https://cluely.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: use the Services from an embargoed nation or any other country/region that becomes an embargoed nation\nentity_types:\n- type: business\n  text: If you are accessing or using the Services on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company\n- type: individual\n  text: The following applies to consumer users of the Services, inclusive of the Free and Pro plans\nrestricted_uses:\n- summary: Embargoed countries\n  text:\
  \ use the Services from an embargoed nation or any other country/region that becomes an embargoed nation\n- summary: Unlawful or infringing content\n  text: use the Services to post or send infringing, obscene, threatening, libelous, or otherwise unlawful material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cluely/eligibility/cluely-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Cluely's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Meeting Assistant
- Productivity
- Transcription
- Speech Recognition
- Sales
- Real-Time
- Command Line Interface
---
