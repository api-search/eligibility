---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old and provide a valid email address.
    type: individual
  - text: If you use the Service on behalf of an organisation, you confirm you are authorised to accept these Terms for it.
    type: business
  minimum_age:
    text: You must be at least 16 years old and provide a valid email address.
    value: '16'
  restricted_uses:
  - summary: Form data collection
    text: Forms must not collect passwords, one-time codes, payment card numbers or other credentials, and we reject such fields.
  - summary: Template content
    text: Templates must not contain personal data, credentials, malware, or material you don't own or have permission to share.
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
name: ArtifactDeploy
provenance_date: '2026-11-09'
provider_name: ArtifactDeploy
provider_slug: artifactdeploy-com
slug: artifactdeploy-com-eligibility
source_date: '2026-11-09'
source_filename: artifactdeploy-com-eligibility.yml
source_heading: Eligibility
source_page: https://artifactdeploy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ArtifactDeploy\naid: artifactdeploy-com\nurl: https://artifactdeploy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old and provide a valid email address.\n- type: business\n  text: If you use the Service on behalf of an organisation, you confirm you are authorised to accept these Terms\n    for it.\nrestricted_uses:\n- summary: Form data collection\n  text: Forms must not collect passwords, one-time codes, payment card numbers or other credentials, and we reject\n    such fields.\n- summary:\
  \ Template content\n  text: Templates must not contain personal data, credentials, malware, or material you don't own or have permission\n    to share.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and provide a valid email address.\n"
source_yaml_url: https://artifacts.apis.io/artifactdeploy-com/eligibility/artifactdeploy-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ArtifactDeploy's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- No-Code
- Deployment
- Templates
- Collaboration
---
