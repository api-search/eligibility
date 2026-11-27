---
api_specs:
- filename: html2img-com-api-openapi.json
  format: json
  label: HTML to Image API API
  slug: html-to-image-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/html2img-com/openapi/_original/html2img-com-api-openapi.json
claim_count: 2
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
  - summary: Illegal, hateful or criminal content
    text: Generating images from content that is illegal, illicit, or promotes hate, violence, or any criminal activity.
  - summary: Adult content
    text: Taking screenshots of websites or materials that contain adult content, pornography, or similar materials.
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
name: html2img-com
provenance_date: '2026-11-09'
provider_name: html2img-com
provider_slug: html2img-com
slug: html2img-com-eligibility
source_date: '2026-11-09'
source_filename: html2img-com-eligibility.yml
source_heading: Eligibility
source_page: https://html2img.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: html2img-com\naid: html2img-com\nurl: https://html2img.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal, hateful or criminal content\n  text: Generating images from content that is illegal, illicit, or promotes hate, violence, or any criminal activity.\n- summary: Adult content\n  text: Taking screenshots of websites or materials that contain adult content, pornography, or similar materials.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/html2img-com/eligibility/html2img-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from html2img-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Screenshots
- PDF
- Rendering
- Headless Chrome
---
