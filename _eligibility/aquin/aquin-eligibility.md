---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Aquin on behalf of a company, you represent that you are authorized to accept these Terms on their behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harmful, illegal or deceptive content
    text: You may not use Aquin to inspect, train, edit, or deploy models intended to generate harmful, illegal, abusive, or deceptive content
  - source: https://www.aquin.app/acceptable-use-policy
    summary: Harmful model use
    text: Inspect, train, edit, simulate, or deploy models intended to generate or facilitate harmful, illegal, abusive, harassing, hateful, or deceptive content
  - source: https://www.aquin.app/acceptable-use-policy
    summary: Fraud, malware, surveillance, weapons
    text: Develop, test, or improve systems for fraud, malware, unauthorized surveillance, weapons, or other activities that pose serious risk of harm
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
name: Aquin
provenance_date: '2026-11-09'
provider_name: Aquin
provider_slug: aquin
slug: aquin-eligibility
source_date: '2026-11-09'
source_filename: aquin-eligibility.yml
source_heading: Eligibility
source_page: https://www.aquin.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aquin\naid: aquin\nurl: https://www.aquin.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.aquin.app/acceptable-use-policy\n  - https://www.aquin.app/terms\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Aquin on behalf of a company, you represent that you are authorized to accept these Terms on\n    their behalf.\nrestricted_uses:\n- summary: Harmful, illegal or deceptive content\n  text: You may not use Aquin to inspect, train, edit, or deploy models intended to generate harmful, illegal, abusive,\n    or deceptive content\n- summary:\
  \ Harmful model use\n  text: Inspect, train, edit, simulate, or deploy models intended to generate or facilitate harmful, illegal, abusive,\n    harassing, hateful, or deceptive content\n  source: https://www.aquin.app/acceptable-use-policy\n- summary: Fraud, malware, surveillance, weapons\n  text: Develop, test, or improve systems for fraud, malware, unauthorized surveillance, weapons, or other activities\n    that pose serious risk of harm\n  source: https://www.aquin.app/acceptable-use-policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aquin/eligibility/aquin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Aquin's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Foundation Models
- Open Source
- Research
---
