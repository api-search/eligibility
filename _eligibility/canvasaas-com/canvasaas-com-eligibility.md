---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Platform on behalf of an organisation, company, or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  - text: An Account Owner may be an individual entrepreneur, a startup founder, a business consultant, an investor, or a representative acting on behalf of an organisation.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to create an account and use the Platform as an Account Owner.
    value: '18'
  restricted_uses:
  - summary: Fraudulent analyses
    text: create fake data or fabricated analyses intended to mislead investors, partners, or other stakeholders.
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
name: CanvasaaS
provenance_date: '2026-11-09'
provider_name: CanvasaaS
provider_slug: canvasaas-com
slug: canvasaas-com-eligibility
source_date: '2026-11-09'
source_filename: canvasaas-com-eligibility.yml
source_heading: Eligibility
source_page: https://canvasaas.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CanvasaaS\naid: canvasaas-com\nurl: https://canvasaas.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Platform on behalf of an organisation, company, or other legal entity, you represent\n    and warrant that you have the authority to bind that entity to these Terms.\n- type: individual\n  text: An Account Owner may be an individual entrepreneur, a startup founder, a business consultant, an investor,\n    or a representative acting on behalf of an organisation.\nrestricted_uses:\n- summary: Fraudulent analyses\n\
  \  text: create fake data or fabricated analyses intended to mislead investors, partners, or other stakeholders.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to create an account and use the Platform as an Account Owner.\n"
source_yaml_url: https://artifacts.apis.io/canvasaas-com/eligibility/canvasaas-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CanvasaaS's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Strategic Planning
- BusinessTools
- Presentation Decks
- Canvas
---
