---
api_specs:
- filename: moonbounce-batch-processing-api-openapi.yml
  format: yaml
  label: Moonbounce Batch Processing API
  slug: moonbounce-batch-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moonbounce/openapi/moonbounce-batch-processing-api-openapi.yml
- filename: moonbounce-create-jobs-api-openapi.yml
  format: yaml
  label: Moonbounce Create Jobs API
  slug: moonbounce-create-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moonbounce/openapi/moonbounce-create-jobs-api-openapi.yml
- filename: moonbounce-get-jobs-api-openapi.yml
  format: yaml
  label: Moonbounce Get Jobs API
  slug: moonbounce-get-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moonbounce/openapi/moonbounce-get-jobs-api-openapi.yml
- filename: moonbounce-labels-api-openapi.yml
  format: yaml
  label: Moonbounce Labels API
  slug: moonbounce-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moonbounce/openapi/moonbounce-labels-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Website
    type: individual
  - text: If you’re agreeing to these ToU on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these ToU on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 16 years of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the Website
    value: '16'
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
name: Moonbounce
provenance_date: '2026-11-10'
provider_name: Moonbounce
provider_slug: moonbounce
slug: moonbounce-eligibility
source_date: '2026-11-10'
source_filename: moonbounce-eligibility.yml
source_heading: Eligibility
source_page: https://www.moonbounce.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moonbounce\naid: moonbounce\nurl: https://www.moonbounce.ai/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Website\n- type: business\n  text: If you’re agreeing to these ToU on behalf of an organization or entity, you represent and warrant that you\n    are authorized to agree to these ToU on that organization’s or entity’s behalf\nrestricted_uses:\n\
  - summary: Unlawful or harmful use\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 16 years\n    of age; if you are a child under 16 years of age, please do not attempt to register for or otherwise use the\n    Website\n"
source_yaml_url: https://artifacts.apis.io/moonbounce/eligibility/moonbounce-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Moonbounce's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Content Moderation
- Trust and Safety
- AI Governance
- Policy Enforcement
- Content Evaluation
---
