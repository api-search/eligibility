---
claim_count: 2
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
  - summary: Acceptable-use restrictions
    text: 'Do not use the Content or the service to: violate law; infringe third-party rights; misrepresent Beyond Wine or any claim''s confidence/verification status; or build a competing or substitute database or product in breach of License §4.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To call the API you must register, obtain an API key, and accept these Terms and the License.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beyond Wine
provenance_date: '2026-11-09'
provider_name: Beyond Wine
provider_slug: beyond-wine
slug: beyond-wine-eligibility
source_date: '2026-11-09'
source_filename: beyond-wine-eligibility.yml
source_heading: Eligibility
source_page: https://beyond.wine/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beyond Wine\naid: beyond-wine\nurl: https://beyond.wine/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable-use restrictions\n  text: 'Do not use the Content or the service to: violate law; infringe third-party rights; misrepresent Beyond\n    Wine or any claim''s confidence/verification status; or build a competing or substitute database or product\n    in breach of License §4.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To call the API you must register, obtain an API key, and accept\
  \ these Terms and the License.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beyond-wine/eligibility/beyond-wine-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Beyond Wine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beverages
- Non-Alcoholic
- Specialty Drinks
- Knowledge Base
---
