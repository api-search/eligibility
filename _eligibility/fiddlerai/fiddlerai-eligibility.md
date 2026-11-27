---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Fiddler makes no representations that the Site and Services are appropriate or available for use in other locations.
  entity_types:
  - text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FIDDLER
    type: individual
  - text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED ON THE WEBSITE.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FIDDLER
    value: legal age
  restricted_uses:
  - summary: Export and embargo restrictions
    text: Fiddler Properties may not be exported or re-exported (a) into any United States embargoed countries, or (b) to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be required to register for an account (“ Account ”) and provide certain information about yourself as prompted by the account registration form
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: fiddler.ai
provenance_date: '2026-11-09'
provider_name: fiddler.ai
provider_slug: fiddlerai
slug: fiddlerai-eligibility
source_date: '2026-11-09'
source_filename: fiddlerai-eligibility.yml
source_heading: Eligibility
source_page: https://www.fiddler.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fiddler.ai\naid: fiddlerai\nurl: https://www.fiddler.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Fiddler makes no representations that the Site and Services are appropriate or available for use in other\n    locations.\nentity_types:\n- type: individual\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FIDDLER\n- type: business\n  text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU\n    REGISTERED ON THE WEBSITE.\nrestricted_uses:\n- summary: Export and embargo restrictions\n  text: Fiddler\
  \ Properties may not be exported or re-exported (a) into any United States embargoed countries, or\n    (b) to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be required to register for an account (“ Account ”) and provide certain information about yourself\n    as prompted by the account registration form\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH FIDDLER\n"
source_yaml_url: https://artifacts.apis.io/fiddlerai/eligibility/fiddlerai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from fiddler.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Observability
- Machine Learning
- LLM
- Model Monitoring
- Guardrails
- MLOps
- AI Governance
- Explainability
- Agent Observability
- AI Security
---
