---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website and Service are only intended for individuals aged eighteen (18) years or older.
    type: individual
  - text: If you are entering into this Agreement on behalf of your employer or other legal entity, you represent and warrant that you have full authority to act on behalf of the employer or other legal entity
    type: business
  minimum_age:
    text: individuals aged eighteen (18) years or older
    value: '18'
  restricted_uses:
  - summary: Not for PII or Sensitive Data
    text: the Services are not designed for processing of personally identifying information (PII) or Sensitive Data as part of User Content
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
name: Groundcover
provenance_date: '2026-11-09'
provider_name: Groundcover
provider_slug: groundcover
slug: groundcover-eligibility
source_date: '2026-11-09'
source_filename: groundcover-eligibility.yml
source_heading: Eligibility
source_page: https://www.groundcover.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Groundcover\naid: groundcover\nurl: https://www.groundcover.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website and Service are only intended for individuals aged eighteen (18) years or older.\n- type: business\n  text: If you are entering into this Agreement on behalf of your employer or other legal entity, you represent\n    and warrant that you have full authority to act on behalf of the employer or other legal entity\nrestricted_uses:\n- summary: Not for PII or Sensitive Data\n  text: the Services are not\
  \ designed for processing of personally identifying information (PII) or Sensitive Data\n    as part of User Content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: individuals aged eighteen (18) years or older\n"
source_yaml_url: https://artifacts.apis.io/groundcover/eligibility/groundcover-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Groundcover's own page on 2026-11-09.
synthetic: false
tags:
- AIOps
- Observability
- Kubernetes
- eBPF
- Monitoring
- Logs
- Traces
- Metrics
- OpenTelemetry
- MCP
---
