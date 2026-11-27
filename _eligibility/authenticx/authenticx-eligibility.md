---
api_specs:
- filename: authenticx-agent-api-openapi.yml
  format: yaml
  label: Authenticx Agent API
  slug: authenticx-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-agent-api-openapi.yml
- filename: authenticx-conversations-api-openapi.yml
  format: yaml
  label: Authenticx Conversations API
  slug: authenticx-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-conversations-api-openapi.yml
- filename: authenticx-evaluations-api-openapi.yml
  format: yaml
  label: Authenticx Evaluations API
  slug: authenticx-evaluations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-evaluations-api-openapi.yml
- filename: authenticx-hierarchy-api-openapi.yml
  format: yaml
  label: Authenticx Hierarchy API
  slug: authenticx-hierarchy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-hierarchy-api-openapi.yml
- filename: authenticx-interactions-api-openapi.yml
  format: yaml
  label: Authenticx Interactions API
  slug: authenticx-interactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-interactions-api-openapi.yml
- filename: authenticx-media-api-openapi.yml
  format: yaml
  label: Authenticx Media API
  slug: authenticx-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-media-api-openapi.yml
- filename: authenticx-metadata-api-openapi.yml
  format: yaml
  label: Authenticx Metadata API
  slug: authenticx-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-metadata-api-openapi.yml
- filename: authenticx-modelresults-api-openapi.yml
  format: yaml
  label: Authenticx Model Results API
  slug: authenticx-modelresults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-modelresults-api-openapi.yml
- filename: authenticx-receipts-api-openapi.yml
  format: yaml
  label: Authenticx Receipts API
  slug: authenticx-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-receipts-api-openapi.yml
- filename: authenticx-roles-api-openapi.yml
  format: yaml
  label: Authenticx Roles API
  slug: authenticx-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-roles-api-openapi.yml
- filename: authenticx-scim-resourcetypes-api-openapi.yml
  format: yaml
  label: Authenticx (Scim) ResourceTypes API
  slug: authenticx-scim-resourcetypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-scim-resourcetypes-api-openapi.yml
- filename: authenticx-scim-schemas-api-openapi.yml
  format: yaml
  label: Authenticx (Scim) Schemas API
  slug: authenticx-scim-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-scim-schemas-api-openapi.yml
- filename: authenticx-scim-serviceproviderconfig-api-openapi.yml
  format: yaml
  label: Authenticx (Scim) ServiceProviderConfig API
  slug: authenticx-scim-serviceproviderconfig-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-scim-serviceproviderconfig-api-openapi.yml
- filename: authenticx-scim-users-api-openapi.yml
  format: yaml
  label: Authenticx (Scim) Users API
  slug: authenticx-scim-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-scim-users-api-openapi.yml
- filename: authenticx-textmedia-api-openapi.yml
  format: yaml
  label: Authenticx Text Media API
  slug: authenticx-textmedia-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-textmedia-api-openapi.yml
- filename: authenticx-user-api-openapi.yml
  format: yaml
  label: Authenticx User API
  slug: authenticx-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-user-api-openapi.yml
- filename: authenticx-userhierarchy-api-openapi.yml
  format: yaml
  label: Authenticx User Hierarchy API
  slug: authenticx-userhierarchy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-userhierarchy-api-openapi.yml
- filename: authenticx-workflows-api-openapi.yml
  format: yaml
  label: Authenticx Workflows API
  slug: authenticx-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-workflows-api-openapi.yml
- filename: authenticx-scim-groups-api-openapi.yml
  format: yaml
  label: Authenticx (Scim) Groups API
  slug: authenticx-scim-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authenticx/openapi/authenticx-scim-groups-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No HIPAA data without BAA/DUA
    text: Customer agrees not to upload to the Software Service any HIPAA Data unless Customer has entered into Business Associate Agreement (BAA) or Data Usage Agreement (DUA) with Authenticx.
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
name: Authenticx
provenance_date: '2026-11-09'
provider_name: Authenticx
provider_slug: authenticx
slug: authenticx-eligibility
source_date: '2026-11-09'
source_filename: authenticx-eligibility.yml
source_heading: Eligibility
source_page: https://authenticx.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Authenticx\naid: authenticx\nurl: https://authenticx.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No HIPAA data without BAA/DUA\n  text: Customer agrees not to upload to the Software Service any HIPAA Data unless Customer has entered into Business\n    Associate Agreement (BAA) or Data Usage Agreement (DUA) with Authenticx.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/authenticx/eligibility/authenticx-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Authenticx's own page on 2026-11-09.
synthetic: false
tags:
- Conversation Intelligence
- Healthcare
- Speech Analytics
- Contact Center
- Customer Experience
- Quality Assurance
- Pharmacovigilance
- Patient Experience
- Transcription
- Life Sciences
- SCIM
- OAuth
- Authentication
---
