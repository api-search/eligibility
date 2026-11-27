---
api_specs:
- filename: impossible-cloud-distributors-api-openapi.yml
  format: yaml
  label: Impossible Cloud Distributors API
  slug: impossible-cloud-distributors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/impossible-cloud/openapi/impossible-cloud-distributors-api-openapi.yml
- filename: impossible-cloud-integrations-api-openapi.yml
  format: yaml
  label: Impossible Cloud Integrations API
  slug: impossible-cloud-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/impossible-cloud/openapi/impossible-cloud-integrations-api-openapi.yml
- filename: impossible-cloud-partners-api-openapi.yml
  format: yaml
  label: Impossible Cloud Partners API
  slug: impossible-cloud-partners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/impossible-cloud/openapi/impossible-cloud-partners-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Storage Services may not be used in any country subject to embargoes, sanctions, or trade restrictions.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated data
    text: Customer shall not use the Storage Services to store data subject to special regulatory or contractual handling requirements exceeding those set out in this Agreement and the Data Processing Agreement (e.g., cardholder data under PCI DSS, protected health information under HIPAA), unless the parties have entered into a separate written agreement covering such data.
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
name: Impossible Cloud
provenance_date: '2026-11-09'
provider_name: Impossible Cloud
provider_slug: impossible-cloud
slug: impossible-cloud-eligibility
source_date: '2026-11-09'
source_filename: impossible-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://www.impossiblecloud.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Impossible Cloud\naid: impossible-cloud\nurl: https://www.impossiblecloud.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Storage Services may not be used in any country subject to embargoes, sanctions, or trade restrictions.\nentity_types: []\nrestricted_uses:\n- summary: Regulated data\n  text: Customer shall not use the Storage Services to store data subject to special regulatory or contractual handling\n    requirements exceeding those set out in this Agreement and the Data Processing Agreement (e.g., cardholder data\n    under PCI DSS, protected health\
  \ information under HIPAA), unless the parties have entered into a separate written\n    agreement covering such data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/impossible-cloud/eligibility/impossible-cloud-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Impossible Cloud's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Object Storage
- S3
- Storage
- Infrastructure
- GPU
- AI Infrastructure
- Data Sovereignty
- Europe
- GDPR
- Partner API
---
