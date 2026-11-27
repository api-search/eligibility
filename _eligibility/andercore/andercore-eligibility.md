---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For purposes hereof, transactions with businesses are no different than transactions with legal entities or special funds under public law.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law obstacles
    text: Andercore shall be released from an obligation stemming from and occurring in connection with the agreement if and insofar Andercore is or will be temporarily or permanently hindered from fulfilling such obligations due to the provisions of German, European or US export laws
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
name: Andercore
provenance_date: '2026-11-09'
provider_name: Andercore
provider_slug: andercore
slug: andercore-eligibility
source_date: '2026-11-09'
source_filename: andercore-eligibility.yml
source_heading: Eligibility
source_page: https://www.andercore.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Andercore\naid: andercore\nurl: https://www.andercore.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: For purposes hereof, transactions with businesses are no different than transactions with legal entities\n    or special funds under public law.\nrestricted_uses:\n- summary: Export law obstacles\n  text: Andercore shall be released from an obligation stemming from and occurring in connection with the agreement\n    if and insofar Andercore is or will be temporarily or permanently hindered from fulfilling such obligations\n\
  \    due to the provisions of German, European or US export laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/andercore/eligibility/andercore-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Andercore's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Industrial Trade
- Supply Chain
- Fintech
- Europe
---
