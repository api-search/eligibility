---
api_specs:
- filename: bespoke-labs-nimble-api-openapi.yml
  format: yaml
  label: Bespoke Labs Nimble API
  slug: bespoke-labs-nimble-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bespoke-labs/openapi/bespoke-labs-nimble-api-openapi.yml
- filename: bespoke-labs-viewer-api-openapi.yml
  format: yaml
  label: Bespoke Labs Viewer API
  slug: bespoke-labs-viewer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bespoke-labs/openapi/bespoke-labs-viewer-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 13 years of age
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable;
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
name: Bespoke Labs
provenance_date: '2026-11-09'
provider_name: Bespoke Labs
provider_slug: bespoke-labs
slug: bespoke-labs-eligibility
source_date: '2026-11-09'
source_filename: bespoke-labs-eligibility.yml
source_heading: Eligibility
source_page: https://bespokelabs.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bespoke Labs\naid: bespoke-labs\nurl: https://bespokelabs.ai/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\n\
  restricted_uses:\n- summary: Unlawful or harmful use\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/bespoke-labs/eligibility/bespoke-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bespoke Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- LLM
- Synthetic Data
- Data Curation
- Fact Checking
- Hallucination Detection
- AI Agents
- Evaluation
---
