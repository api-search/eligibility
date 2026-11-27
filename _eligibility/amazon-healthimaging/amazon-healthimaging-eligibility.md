---
api_specs:
- filename: amazon-healthimaging-datastore-api-openapi.yml
  format: yaml
  label: Amazon HealthImaging Datastore API
  slug: amazon-healthimaging-datastore-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-healthimaging/openapi/amazon-healthimaging-datastore-api-openapi.yml
- filename: amazon-healthimaging-tags-api-openapi.yml
  format: yaml
  label: Amazon HealthImaging Tags API
  slug: amazon-healthimaging-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-healthimaging/openapi/amazon-healthimaging-tags-api-openapi.yml
- filename: amazon-healthimaging-get-dicom-import-job-api-openapi.yml
  format: yaml
  label: Amazon HealthImaging Get DICOM Import Job API
  slug: amazon-healthimaging-get-dicom-import-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-healthimaging/openapi/amazon-healthimaging-get-dicom-import-job-api-openapi.yml
- filename: amazon-healthimaging-list-dicom-import-jobs-api-openapi.yml
  format: yaml
  label: Amazon HealthImaging List DICOM Import Jobs API
  slug: amazon-healthimaging-list-dicom-import-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-healthimaging/openapi/amazon-healthimaging-list-dicom-import-jobs-api-openapi.yml
- filename: amazon-healthimaging-start-dicom-import-job-api-openapi.yml
  format: yaml
  label: Amazon HealthImaging Start DICOM Import Job API
  slug: amazon-healthimaging-start-dicom-import-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-healthimaging/openapi/amazon-healthimaging-start-dicom-import-job-api-openapi.yml
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
  - summary: Spend limits not for regulated content
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems, any regulated content (such as protected health information), government data, or any content of government entities.
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
name: Amazon HealthImaging
provenance_date: '2026-11-09'
provider_name: Amazon HealthImaging
provider_slug: amazon-healthimaging
slug: amazon-healthimaging-eligibility
source_date: '2026-11-09'
source_filename: amazon-healthimaging-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon HealthImaging\naid: amazon-healthimaging\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spend limits not for regulated content\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems, any regulated content (such as protected health information),\n    government data, or any content of government entities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-healthimaging/eligibility/amazon-healthimaging-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon HealthImaging's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Healthcare
- HIPAA
- Machine Learning
- Medical Imaging
- DICOM
---
