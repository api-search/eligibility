---
api_specs:
- filename: google-search-console-sitemaps-api-openapi.yml
  format: yaml
  label: Google Search Console Sitemaps API
  slug: google-search-console-sitemaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-search-console/openapi/google-search-console-sitemaps-api-openapi.yml
- filename: google-search-console-sites-api-openapi.yml
  format: yaml
  label: Google Search Console Sites API
  slug: google-search-console-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-search-console/openapi/google-search-console-sites-api-openapi.yml
- filename: google-search-console-searchanalytics-api-openapi.yml
  format: yaml
  label: Google Search Console Search Console Searchanalytics API
  slug: google-search-console-searchanalytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-search-console/openapi/google-search-console-searchanalytics-api-openapi.yml
- filename: google-search-console-urlinspection-api-openapi.yml
  format: yaml
  label: Google Search Console URL Inspection API
  slug: google-search-console-urlinspection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-search-console/openapi/google-search-console-urlinspection-api-openapi.yml
- filename: google-search-console-urltestingtools-api-openapi.yml
  format: yaml
  label: Google Search Console URL Testing Tools API
  slug: google-search-console-urltestingtools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-search-console/openapi/google-search-console-urltestingtools-api-openapi.yml
claim_count: 11
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the APIs if you are a person barred from using or receiving the APIs under the applicable laws of the United States or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  - text: If you are accepting the Terms on behalf of a United States federal government entity, then the following applies instead of the paragraph above
    type: government
  - source: https://policies.google.com/terms
    text: Many organizations , such as businesses, non-profits, and schools, take advantage of our services .
    type: business
  - source: https://policies.google.com/terms
    text: If you’re under the age required to manage your own Google Account , you must have your parent or legal guardian’s permission to use a Google Account.
    type: individual
  minimum_age:
    text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding contract with Google
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: ITAR-controlled data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations
  - summary: HIPAA protected health information
    text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
  - summary: Unlawful gambling or disruptive commercial messages
    text: Promote or facilitate unlawful online gambling or disruptive commercial messages or advertisements.
  - source: https://policies.google.com/terms
    summary: Legal compliance
    text: comply with applicable laws, including export control, sanctions, and human trafficking laws
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
name: Google Search Console
provenance_date: '2026-11-09'
provider_name: Google Search Console
provider_slug: google-search-console
slug: google-search-console-eligibility
source_date: '2026-11-09'
source_filename: google-search-console-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Search Console\naid: google-search-console\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://developers.google.com/terms\n  - https://policies.google.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the APIs if you are a person barred from using or receiving the APIs under the applicable\n    laws of the United States or other countries including the country in which you are resident or from which you\n    use the APIs.\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant\
  \ that you have authority to bind\n    that entity to the Terms\n- type: government\n  text: If you are accepting the Terms on behalf of a United States federal government entity, then the following\n    applies instead of the paragraph above\n- type: business\n  text: Many organizations , such as businesses, non-profits, and schools, take advantage of our services .\n  source: https://policies.google.com/terms\n- type: individual\n  text: If you’re under the age required to manage your own Google Account , you must have your parent or legal\n    guardian’s permission to use a Google Account.\n  source: https://policies.google.com/terms\nrestricted_uses:\n- summary: High-risk activities\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: ITAR-controlled data\n  text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations\n- summary:\
  \ HIPAA protected health information\n  text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information\n    to Google unless you have received prior written consent to such use from Google.\n- summary: Unlawful gambling or disruptive commercial messages\n  text: Promote or facilitate unlawful online gambling or disruptive commercial messages or advertisements.\n- summary: Legal compliance\n  text: comply with applicable laws, including export control, sanctions, and human trafficking laws\n  source: https://policies.google.com/terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may not use the APIs and may not accept the Terms if (a) you are not of legal age to form a binding\n    contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-search-console/eligibility/google-search-console-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 11 quoted statements, read from Google Search Console's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Google
- Indexing
- Search
- Search Analytics
- SEO
- Sitemap
- URL Inspection
- Webmaster Tools
---
