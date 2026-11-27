---
api_specs:
- filename: hasura-asyncapi.yml
  format: yaml
  label: Hasura GraphQL API
  slug: hasura-graphql-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/hasura/asyncapi/hasura-asyncapi.yml
- filename: hasura-healthz-api-openapi.yml
  format: yaml
  label: Hasura Healthz API
  slug: hasura-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-healthz-api-openapi.yml
- filename: hasura-metadata-api-openapi.yml
  format: yaml
  label: Hasura Metadata API
  slug: hasura-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-metadata-api-openapi.yml
- filename: hasura-query-api-openapi.yml
  format: yaml
  label: Hasura Query API
  slug: hasura-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-query-api-openapi.yml
- filename: hasura-source-health-api-openapi.yml
  format: yaml
  label: Hasura Source Health API
  slug: hasura-source-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-source-health-api-openapi.yml
- filename: hasura-v1alpha1-api-openapi.yml
  format: yaml
  label: Hasura V1alpha1 API
  slug: hasura-v1alpha1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-v1alpha1-api-openapi.yml
- filename: hasura-v1beta1-api-openapi.yml
  format: yaml
  label: Hasura V1beta1 API
  slug: hasura-v1beta1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-v1beta1-api-openapi.yml
- filename: hasura-version-api-openapi.yml
  format: yaml
  label: Hasura Version API
  slug: hasura-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-version-api-openapi.yml
- filename: hasura-graph-ql-api-openapi.yml
  format: yaml
  label: Hasura Graph QL API
  slug: hasura-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasura/openapi/hasura-graph-ql-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    source: https://hasura.io/legal/website-terms-of-use
    text: You must only use the Websites ... in compliance with U.S. export laws or regulations, or in violation of any applicable local laws or regulations.
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES TO THESE TERMS AND CONDITIONS
    type: business
  minimum_age:
    text: REPRESENT THAT YOU ARE AT LEAST 18 (EIGHTEEN) YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: Use the Hasura Cloud Platform/Services for any illegal purpose or in a manner that it violates any law or rights of any other person.
  - source: https://hasura.io/legal/website-terms-of-use
    summary: Export law compliance
    text: You may not access, download, use, or export the information, software, products or services contained on this website in violation of U.S. export laws or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to create an Account, you will be required to provide us with your e-mail address, GitHub Id and/or Google Id, and/or such other information as Hasura may require for the purpose of user registration, identification, and account verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hasura
provenance_date: '2026-11-09'
provider_name: Hasura
provider_slug: hasura
slug: hasura-eligibility
source_date: '2026-11-09'
source_filename: hasura-eligibility.yml
source_heading: Eligibility
source_page: https://hasura.io/legal/hasura-cloud-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hasura\naid: hasura\nurl: https://hasura.io/legal/hasura-cloud-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://hasura.io/legal/hasura-cloud-terms-of-service\n  - https://hasura.io/legal/website-terms-of-use\ncountries:\n  served: []\n  excluded: []\n  text: You must only use the Websites ... in compliance with U.S. export laws or regulations, or in violation of\n    any applicable local laws or regulations.\n  source: https://hasura.io/legal/website-terms-of-use\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY,\
  \ YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY AND ITS AFFILIATES TO THESE TERMS AND CONDITIONS\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: Use the Hasura Cloud Platform/Services for any illegal purpose or in a manner that it violates any law or\n    rights of any other person.\n- summary: Export law compliance\n  text: You may not access, download, use, or export the information, software, products or services contained on\n    this website in violation of U.S. export laws or regulations\n  source: https://hasura.io/legal/website-terms-of-use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to create an Account, you will be required to provide us with your e-mail address, GitHub Id and/or\n    Google Id, and/or such other information as Hasura may require for the purpose of user registration, identification,\n    and account verification.\nminimum_age:\n  value: '18'\n  text: REPRESENT THAT YOU ARE AT LEAST\
  \ 18 (EIGHTEEN) YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/hasura/eligibility/hasura-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Hasura's own page on 2026-11-09.
synthetic: false
tags:
- Data Access
- GraphQL
- Real-Time
---
