---
api_specs:
- filename: proofdraw-account-api-openapi.yml
  format: yaml
  label: ProofDraw Account API
  slug: proofdraw-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-account-api-openapi.yml
- filename: proofdraw-auth-api-openapi.yml
  format: yaml
  label: ProofDraw Auth API
  slug: proofdraw-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-auth-api-openapi.yml
- filename: proofdraw-draws-api-openapi.yml
  format: yaml
  label: ProofDraw Draws API
  slug: proofdraw-draws-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-draws-api-openapi.yml
- filename: proofdraw-system-api-openapi.yml
  format: yaml
  label: ProofDraw System API
  slug: proofdraw-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-system-api-openapi.yml
- filename: proofdraw-verification-api-openapi.yml
  format: yaml
  label: ProofDraw Verification API
  slug: proofdraw-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/proofdraw/openapi/proofdraw-verification-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms, and "you" refers to both you and the organization.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old and competent to enter into a binding contract under the laws of your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Unlawful draws
    text: 'You may not use the Service to: Conduct any lottery, contest, sweepstakes, drawing, or promotion that violates applicable law'
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
name: ProofDraw
provenance_date: '2026-11-10'
provider_name: ProofDraw
provider_slug: proofdraw
slug: proofdraw-eligibility
source_date: '2026-11-10'
source_filename: proofdraw-eligibility.yml
source_heading: Eligibility
source_page: https://proofdraw.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ProofDraw\naid: proofdraw\nurl: https://proofdraw.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms, and \"you\" refers to both you and the organization.\nrestricted_uses:\n- summary: Unlawful draws\n  text: 'You may not use the Service to: Conduct any lottery, contest, sweepstakes, drawing, or promotion that violates\n    applicable law'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old and competent to enter into a binding contract under the laws\n    of your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/proofdraw/eligibility/proofdraw-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ProofDraw's own page on 2026-11-10.
synthetic: false
tags:
- Randomness
- Provably Fair
- Drand
- Verifiable Randomness
- Cryptography
- raffle
- Giveaways
- Sweepstakes
- Lottery
- Verification
- Webhook
- REST API
---
