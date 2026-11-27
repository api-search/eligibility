---
api_specs:
- filename: belindoc-com-openapi-generated.yml
  format: yaml
  label: Belin Doc API
  slug: belindoc-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/belindoc-com/openapi/_ae-authored/belindoc-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating an account or using any part of the Service, you confirm that you are at least 13 years of age and have the legal capacity to enter into this agreement.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: you confirm that you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful uploads
    text: Upload documents containing illegal, harmful, threatening, abusive, harassing, defamatory, obscene, or otherwise unlawful content
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
name: Belin Doc
provenance_date: '2026-11-09'
provider_name: Belin Doc
provider_slug: belindoc-com
slug: belindoc-com-eligibility
source_date: '2026-11-09'
source_filename: belindoc-com-eligibility.yml
source_heading: Eligibility
source_page: https://belindoc.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Belin Doc\naid: belindoc-com\nurl: https://belindoc.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By creating an account or using any part of the Service, you confirm that you are at least 13 years of age\n    and have the legal capacity to enter into this agreement.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: Unlawful or harmful uploads\n  text: Upload documents containing\
  \ illegal, harmful, threatening, abusive, harassing, defamatory, obscene, or otherwise\n    unlawful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you confirm that you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/belindoc-com/eligibility/belindoc-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Belin Doc's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Document Translation
- Free
- PDF
- Multilingual
---
