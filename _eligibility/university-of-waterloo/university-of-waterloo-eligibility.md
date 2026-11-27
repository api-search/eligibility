---
api_specs:
- filename: university-of-waterloo-academicorganizations-api-openapi.yml
  format: yaml
  label: University of Waterloo AcademicOrganizations API
  slug: university-of-waterloo-academicorganizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-academicorganizations-api-openapi.yml
- filename: university-of-waterloo-account-api-openapi.yml
  format: yaml
  label: University of Waterloo Account API
  slug: university-of-waterloo-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-account-api-openapi.yml
- filename: university-of-waterloo-classschedules-api-openapi.yml
  format: yaml
  label: University of Waterloo ClassSchedules API
  slug: university-of-waterloo-classschedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-classschedules-api-openapi.yml
- filename: university-of-waterloo-courses-api-openapi.yml
  format: yaml
  label: University of Waterloo Courses API
  slug: university-of-waterloo-courses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-courses-api-openapi.yml
- filename: university-of-waterloo-examschedules-api-openapi.yml
  format: yaml
  label: University of Waterloo ExamSchedules API
  slug: university-of-waterloo-examschedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-examschedules-api-openapi.yml
- filename: university-of-waterloo-foodservices-api-openapi.yml
  format: yaml
  label: University of Waterloo FoodServices API
  slug: university-of-waterloo-foodservices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-foodservices-api-openapi.yml
- filename: university-of-waterloo-holidaydates-api-openapi.yml
  format: yaml
  label: University of Waterloo HolidayDates API
  slug: university-of-waterloo-holidaydates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-holidaydates-api-openapi.yml
- filename: university-of-waterloo-importantdates-api-openapi.yml
  format: yaml
  label: University of Waterloo ImportantDates API
  slug: university-of-waterloo-importantdates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-importantdates-api-openapi.yml
- filename: university-of-waterloo-locations-api-openapi.yml
  format: yaml
  label: University of Waterloo Locations API
  slug: university-of-waterloo-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-locations-api-openapi.yml
- filename: university-of-waterloo-subjects-api-openapi.yml
  format: yaml
  label: University of Waterloo Subjects API
  slug: university-of-waterloo-subjects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-subjects-api-openapi.yml
- filename: university-of-waterloo-terms-api-openapi.yml
  format: yaml
  label: University of Waterloo Terms API
  slug: university-of-waterloo-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-terms-api-openapi.yml
- filename: university-of-waterloo-wcms-api-openapi.yml
  format: yaml
  label: University of Waterloo Wcms API
  slug: university-of-waterloo-wcms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-waterloo/openapi/university-of-waterloo-wcms-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: represent that you are of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: Unlawful or objectionable content
    text: Applications may not be associated with nor contain any content that is unlawful, tortious, defamatory, obscene, invasive of the privacy of another person, threatening, harassing, abusive, hateful, racist or otherwise objectionable or inappropriate, as determined by UW in UW's sole discretion.
  - source: https://uwaterloo.atlassian.net/wiki/spaces/UWAPI/pages/34019781061/Acceptable+Use+Policy+SourceAPI
    summary: Governed by UW Policy 46
    text: this access and the usage of the data available in this API is governed by University of Waterloo Policy 46 - Information Management.
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
name: University of Waterloo
provenance_date: '2026-11-10'
provider_name: University of Waterloo
provider_slug: university-of-waterloo
slug: university-of-waterloo-eligibility
source_date: '2026-11-10'
source_filename: university-of-waterloo-eligibility.yml
source_heading: Eligibility
source_page: https://uwaterloo.atlassian.net/wiki/spaces/UWAPI/pages/34019780998/Terms+of+Service+SourceAPI
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: University of Waterloo\naid: university-of-waterloo\nurl: https://uwaterloo.atlassian.net/wiki/spaces/UWAPI/pages/34019780998/Terms+of+Service+SourceAPI\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://uwaterloo.atlassian.net/wiki/spaces/UWAPI/pages/34019780998/Terms+of+Service+SourceAPI\n  - https://uwaterloo.atlassian.net/wiki/spaces/UWAPI/pages/34019781061/Acceptable+Use+Policy+SourceAPI\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: Applications may not be associated with nor contain any content that is\
  \ unlawful, tortious, defamatory,\n    obscene, invasive of the privacy of another person, threatening, harassing, abusive, hateful, racist or otherwise\n    objectionable or inappropriate, as determined by UW in UW's sole discretion.\n- summary: Governed by UW Policy 46\n  text: this access and the usage of the data available in this API is governed by University of Waterloo Policy\n    46 - Information Management.\n  source: https://uwaterloo.atlassian.net/wiki/spaces/UWAPI/pages/34019781061/Acceptable+Use+Policy+SourceAPI\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: represent that you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/university-of-waterloo/eligibility/university-of-waterloo-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from University of Waterloo's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Higher Education
- University
- Open Data
- Canada
- Ontario
- Research
- Research Data
- Course Catalog
- Identity Federation
- Research Repository
- Campus Life
---
