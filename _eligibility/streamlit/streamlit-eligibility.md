---
api_specs:
- filename: streamlit-apps-api-openapi.yml
  format: yaml
  label: Streamlit Apps API
  slug: streamlit-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamlit/openapi/streamlit-apps-api-openapi.yml
- filename: streamlit-secrets-api-openapi.yml
  format: yaml
  label: Streamlit Secrets API
  slug: streamlit-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamlit/openapi/streamlit-secrets-api-openapi.yml
- filename: streamlit-workspaces-api-openapi.yml
  format: yaml
  label: Streamlit Workspaces API
  slug: streamlit-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamlit/openapi/streamlit-workspaces-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Streamlit Services is subject to export control or sanctions laws of the United States or any other applicable jurisdiction; no country list is stated.
  entity_types:
  - text: You must be 18 or older to use the Streamlit.io services, such as the forum and the Community Cloud
    type: individual
  minimum_age:
    text: You must be 18 or older to use the Streamlit.io services, such as the forum and the Community Cloud
    value: '18'
  restricted_uses:
  - summary: No sensitive data on Community Cloud
    text: You shall not, and shall not permit others to, make available to or otherwise process with the Community Cloud any Community Cloud Content or other content that is subject to heightened legal or regulatory data protection requirements or standards, including, but not limited to, financial information, health information, biometric information, and any other sensitive personal information.
  - summary: Personal non-commercial use only for PII apps
    text: you may only use the Community Cloud for personal and non-commercial purposes, such as evaluation, educational, or household use, and you may not access or use the Community Cloud for the benefit of, or otherwise in connection with, a business or commercial purpose.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Snowflake reserves the right to change its account registration requirements and procedures from time-to-time, and will have sole discretion in deciding whether or not to approve your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Streamlit
provenance_date: '2026-11-10'
provider_name: Streamlit
provider_slug: streamlit
slug: streamlit-eligibility
source_date: '2026-11-10'
source_filename: streamlit-eligibility.yml
source_heading: Eligibility
source_page: https://streamlit.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Streamlit\naid: streamlit\nurl: https://streamlit.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Streamlit Services is subject to export control or sanctions laws of the United States or any\n    other applicable jurisdiction; no country list is stated.\nentity_types:\n- type: individual\n  text: You must be 18 or older to use the Streamlit.io services, such as the forum and the Community Cloud\nrestricted_uses:\n- summary: No sensitive data on Community Cloud\n  text: You shall not, and shall not permit others to, make available to or otherwise process\
  \ with the Community\n    Cloud any Community Cloud Content or other content that is subject to heightened legal or regulatory data protection\n    requirements or standards, including, but not limited to, financial information, health information, biometric\n    information, and any other sensitive personal information.\n- summary: Personal non-commercial use only for PII apps\n  text: you may only use the Community Cloud for personal and non-commercial purposes, such as evaluation, educational,\n    or household use, and you may not access or use the Community Cloud for the benefit of, or otherwise in connection\n    with, a business or commercial purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Snowflake reserves the right to change its account registration requirements and procedures from time-to-time,\n    and will have sole discretion in deciding whether or not to approve your account.\nminimum_age:\n  value: '18'\n  text: You must be 18 or older\
  \ to use the Streamlit.io services, such as the forum and the Community Cloud\n"
source_yaml_url: https://artifacts.apis.io/streamlit/eligibility/streamlit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Streamlit's own page on 2026-11-10.
synthetic: false
tags:
- Data Science
- Machine Learning
- Open Source
- Python
- Web Applications
---
