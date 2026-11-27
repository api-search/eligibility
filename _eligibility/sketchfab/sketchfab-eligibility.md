---
api_specs:
- filename: sketchfab-download-api-openapi.yml
  format: yaml
  label: Sketchfab Download API
  slug: sketchfab-download-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-download-api-openapi.yml
- filename: sketchfab-bookmarks-api-openapi.yml
  format: yaml
  label: Sketchfab Bookmarks API
  slug: sketchfab-bookmarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-bookmarks-api-openapi.yml
- filename: sketchfab-categories-api-openapi.yml
  format: yaml
  label: Sketchfab Categories API
  slug: sketchfab-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-categories-api-openapi.yml
- filename: sketchfab-collections-api-openapi.yml
  format: yaml
  label: Sketchfab Collections API
  slug: sketchfab-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-collections-api-openapi.yml
- filename: sketchfab-comments-api-openapi.yml
  format: yaml
  label: Sketchfab Comments API
  slug: sketchfab-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-comments-api-openapi.yml
- filename: sketchfab-likes-api-openapi.yml
  format: yaml
  label: Sketchfab Likes API
  slug: sketchfab-likes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-likes-api-openapi.yml
- filename: sketchfab-models-api-openapi.yml
  format: yaml
  label: Sketchfab Models API
  slug: sketchfab-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-models-api-openapi.yml
- filename: sketchfab-orgs-api-openapi.yml
  format: yaml
  label: Sketchfab Orgs API
  slug: sketchfab-orgs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-orgs-api-openapi.yml
- filename: sketchfab-search-api-openapi.yml
  format: yaml
  label: Sketchfab Search API
  slug: sketchfab-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-search-api-openapi.yml
- filename: sketchfab-tags-api-openapi.yml
  format: yaml
  label: Sketchfab Tags API
  slug: sketchfab-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-tags-api-openapi.yml
- filename: sketchfab-users-api-openapi.yml
  format: yaml
  label: Sketchfab Users API
  slug: sketchfab-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-users-api-openapi.yml
- filename: sketchfab-o-embed-api-openapi.yml
  format: yaml
  label: Sketchfab o Embed API
  slug: sketchfab-o-embed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-o-embed-api-openapi.yml
- filename: sketchfab-oauth-api-openapi.yml
  format: yaml
  label: Sketchfab O Auth API
  slug: sketchfab-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sketchfab/openapi/sketchfab-oauth-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are primarily operated by Sketchfab from its offices in the United States and France. Access to the Services from jurisdictions where such access is illegal is prohibited.
  entity_types:
  - source: https://sketchfab.com/developers/terms
    text: If you are agreeing to be bound by this Agreement on behalf of your employer or other entity, you represent and warrant that you have full legal authority
    type: business
  minimum_age:
    text: THE SERVICES ARE NOT INTENDED FOR CHILDREN UNDER 18, and persons under the age of 18 are prohibited from registering with or using the Services.
    value: '18'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: Transmit any material or content that is pornographic, dehumanizing, threatening, harassing, libelous, hate-oriented, harmful, defamatory, racist, xenophobic, or illegal;
  - summary: Export law compliance
    text: In no event will you use the Services or User Content in violation of US or EU export laws.
  - source: https://sketchfab.com/developers/terms
    summary: Lawful, permitted purposes only
    text: You agree to use the API and write applications only for purposes that are permitted by (a) this Agreement
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information applicable to a purchase may be required prior to our acceptance of any order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sketchfab
provenance_date: '2026-11-10'
provider_name: Sketchfab
provider_slug: sketchfab
slug: sketchfab-eligibility
source_date: '2026-11-10'
source_filename: sketchfab-eligibility.yml
source_heading: Eligibility
source_page: https://sketchfab.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sketchfab\naid: sketchfab\nurl: https://sketchfab.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://sketchfab.com/developers/terms\n  - https://sketchfab.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: The Services are primarily operated by Sketchfab from its offices in the United States and France. Access\n    to the Services from jurisdictions where such access is illegal is prohibited.\nentity_types:\n- type: business\n  text: If you are agreeing to be bound by this Agreement on behalf of your employer or other entity, you represent\n    and warrant that you have full legal authority\n\
  \  source: https://sketchfab.com/developers/terms\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: Transmit any material or content that is pornographic, dehumanizing, threatening, harassing, libelous, hate-oriented,\n    harmful, defamatory, racist, xenophobic, or illegal;\n- summary: Export law compliance\n  text: In no event will you use the Services or User Content in violation of US or EU export laws.\n- summary: Lawful, permitted purposes only\n  text: You agree to use the API and write applications only for purposes that are permitted by (a) this Agreement\n  source: https://sketchfab.com/developers/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information applicable to a purchase may be required prior to our acceptance of any order.\nminimum_age:\n  value: '18'\n  text: THE SERVICES ARE NOT INTENDED FOR CHILDREN UNDER 18, and persons under the age of 18 are prohibited from\n    registering with or using the\
  \ Services.\n"
source_yaml_url: https://artifacts.apis.io/sketchfab/eligibility/sketchfab-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Sketchfab's own page on 2026-11-10.
synthetic: false
tags:
- 3D
- Models
- Marketplace
- Viewer
- WebGL
- glTF
- Augmented Reality
- Virtual Reality
- Creative
- Epic Games
---
