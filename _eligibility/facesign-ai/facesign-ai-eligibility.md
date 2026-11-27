---
api_specs:
- filename: facesign-ai-avatars-api-openapi.yml
  format: yaml
  label: FaceSign Avatars API
  slug: facesign-ai-avatars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facesign-ai/openapi/facesign-ai-avatars-api-openapi.yml
- filename: facesign-ai-langs-api-openapi.yml
  format: yaml
  label: FaceSign Langs API
  slug: facesign-ai-langs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facesign-ai/openapi/facesign-ai-langs-api-openapi.yml
- filename: facesign-ai-sessions-api-openapi.yml
  format: yaml
  label: FaceSign Sessions API
  slug: facesign-ai-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/facesign-ai/openapi/facesign-ai-sessions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization, you represent that you have the authority to bind that organization, and "Customer" refers to that organization.
    type: business
  - text: If you are an individual completing a verification session at the request of one of our Customers (an "End User"), your verification relationship is with that Customer.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Verification without notice and consent
    text: Verify any individual without the notice and consent required by applicable law and these Terms.
  - summary: Surveillance outside consented sessions
    text: Conduct surveillance, tracking, or monitoring outside of a discrete, consented verification session.
  - summary: Sole basis for significant decisions
    text: use Verification Results as the sole basis for decisions with legal or similarly significant effects on individuals without meaningful human review.
  - summary: Minors without consent
    text: Verify individuals under the age of majority in their jurisdiction without verifiable parental or guardian consent where required by law.
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
name: FaceSign
provenance_date: '2026-11-09'
provider_name: FaceSign
provider_slug: facesign-ai
slug: facesign-ai-eligibility
source_date: '2026-11-09'
source_filename: facesign-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.facesign.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FaceSign\naid: facesign-ai\nurl: https://www.facesign.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you have the authority to\n    bind that organization, and \"Customer\" refers to that organization.\n- type: individual\n  text: If you are an individual completing a verification session at the request of one of our Customers (an \"End\n    User\"), your verification relationship is with that Customer.\nrestricted_uses:\n- summary: Verification\
  \ without notice and consent\n  text: Verify any individual without the notice and consent required by applicable law and these Terms.\n- summary: Surveillance outside consented sessions\n  text: Conduct surveillance, tracking, or monitoring outside of a discrete, consented verification session.\n- summary: Sole basis for significant decisions\n  text: use Verification Results as the sole basis for decisions with legal or similarly significant effects on\n    individuals without meaningful human review.\n- summary: Minors without consent\n  text: Verify individuals under the age of majority in their jurisdiction without verifiable parental or guardian\n    consent where required by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/facesign-ai/eligibility/facesign-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from FaceSign's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Identity Verification
- Deepfake Detection
- Liveness Detection
- Biometrics
---
