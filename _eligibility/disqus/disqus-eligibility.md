---
api_specs:
- filename: disqus-categories-api-openapi.yml
  format: yaml
  label: Disqus Categories API
  slug: disqus-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-categories-api-openapi.yml
- filename: disqus-forums-api-openapi.yml
  format: yaml
  label: Disqus Forums API
  slug: disqus-forums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-forums-api-openapi.yml
- filename: disqus-posts-api-openapi.yml
  format: yaml
  label: Disqus Posts API
  slug: disqus-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-posts-api-openapi.yml
- filename: disqus-threads-api-openapi.yml
  format: yaml
  label: Disqus Threads API
  slug: disqus-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-threads-api-openapi.yml
- filename: disqus-users-api-openapi.yml
  format: yaml
  label: Disqus Users API
  slug: disqus-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disqus/openapi/disqus-users-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: THE SERVICE IS CONTROLLED AND OPERATED FROM ITS FACILITIES IN THE U.S.A. THE DISQUS ENTITIES MAKE NO REPRESENTATIONS THAT THE SERVICE IS APPROPRIATE OR AVAILABLE FOR US IN OTHER LOCATIONS.
  entity_types:
  - text: You may only access and use the Service if you agree to be bound by these Terms, are over the age of 18
    type: individual
  - text: If you are accepting these Terms and using the Service on behalf of a company, organization, government or other legal entity, you represent and warrant that you are authorized to do so.
    type: business
  - text: If you are a federal, state, or local government entity in the United States using the Services in your official capacity and legally unable to accept the controlling law, jurisdiction or venue clauses above, then those clauses do not apply to you.
    type: government
  minimum_age:
    text: are over the age of 18
    value: '18'
  restricted_uses:
  - summary: Hate speech, bullying, violence, and other prohibited content
    text: Disqus prohibits bullying and hate speech and requires our users to respect each other
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
name: Disqus
provenance_date: '2026-11-09'
provider_name: Disqus
provider_slug: disqus
slug: disqus-eligibility
source_date: '2026-11-09'
source_filename: disqus-eligibility.yml
source_heading: Eligibility
source_page: https://help.disqus.com/en/articles/1717102-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Disqus\naid: disqus\nurl: https://help.disqus.com/en/articles/1717102-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: THE SERVICE IS CONTROLLED AND OPERATED FROM ITS FACILITIES IN THE U.S.A. THE DISQUS ENTITIES MAKE NO REPRESENTATIONS\n    THAT THE SERVICE IS APPROPRIATE OR AVAILABLE FOR US IN OTHER LOCATIONS.\nentity_types:\n- type: individual\n  text: You may only access and use the Service if you agree to be bound by these Terms, are over the age of 18\n- type: business\n  text: If you are accepting these Terms and using the Service on behalf of a company, organization,\
  \ government\n    or other legal entity, you represent and warrant that you are authorized to do so.\n- type: government\n  text: If you are a federal, state, or local government entity in the United States using the Services in your\n    official capacity and legally unable to accept the controlling law, jurisdiction or venue clauses above, then\n    those clauses do not apply to you.\nrestricted_uses:\n- summary: Hate speech, bullying, violence, and other prohibited content\n  text: Disqus prohibits bullying and hate speech and requires our users to respect each other\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/disqus/eligibility/disqus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Disqus's own page on 2026-11-09.
synthetic: false
tags:
- Comments
- Community
- Discussions
- Publishing
- Audience Engagement
- Social
---
