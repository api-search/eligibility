---
api_specs:
- filename: chembl-activities-api-openapi.yml
  format: yaml
  label: ChEMBL Activities API
  slug: chembl-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-activities-api-openapi.yml
- filename: chembl-assays-api-openapi.yml
  format: yaml
  label: ChEMBL Assays API
  slug: chembl-assays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-assays-api-openapi.yml
- filename: chembl-drugs-api-openapi.yml
  format: yaml
  label: ChEMBL Drugs API
  slug: chembl-drugs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-drugs-api-openapi.yml
- filename: chembl-efo-disease-terms-api-openapi.yml
  format: yaml
  label: ChEMBL EFO disease terms API
  slug: chembl-efo-disease-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-efo-disease-terms-api-openapi.yml
- filename: chembl-hpo-api-openapi.yml
  format: yaml
  label: ChEMBL HPO API
  slug: chembl-hpo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-hpo-api-openapi.yml
- filename: chembl-intact-api-openapi.yml
  format: yaml
  label: ChEMBL Intact API
  slug: chembl-intact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-intact-api-openapi.yml
- filename: chembl-molecules-api-openapi.yml
  format: yaml
  label: ChEMBL Molecules API
  slug: chembl-molecules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-molecules-api-openapi.yml
- filename: chembl-proteins-api-openapi.yml
  format: yaml
  label: ChEMBL Proteins API
  slug: chembl-proteins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-proteins-api-openapi.yml
- filename: chembl-pubchem-bioassay-sids-api-openapi.yml
  format: yaml
  label: ChEMBL PubChem Bioassay Sids API
  slug: chembl-pubchem-bioassay-sids-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-pubchem-bioassay-sids-api-openapi.yml
- filename: chembl-pubchem-biossays-api-openapi.yml
  format: yaml
  label: ChEMBL PubChem Biossays API
  slug: chembl-pubchem-biossays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-pubchem-biossays-api-openapi.yml
- filename: chembl-pubchem-compounds-api-openapi.yml
  format: yaml
  label: ChEMBL PubChem Compounds API
  slug: chembl-pubchem-compounds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-pubchem-compounds-api-openapi.yml
- filename: chembl-pubchem-substances-api-openapi.yml
  format: yaml
  label: ChEMBL PubChem Substances API
  slug: chembl-pubchem-substances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-pubchem-substances-api-openapi.yml
- filename: chembl-targets-api-openapi.yml
  format: yaml
  label: ChEMBL Targets API
  slug: chembl-targets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chembl/openapi/chembl-targets-api-openapi.yml
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
  - summary: Unlawful or infringing uploads
    text: 'The user responsible for the uploading of any content shall ensure: (i) that they have all required licences, authorisations, permissions and consents for open access dissemination'
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
name: ChEMBL
provenance_date: '2026-11-09'
provider_name: ChEMBL
provider_slug: chembl
slug: chembl-eligibility
source_date: '2026-11-09'
source_filename: chembl-eligibility.yml
source_heading: Eligibility
source_page: https://www.ebi.ac.uk/about/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChEMBL\naid: chembl\nurl: https://www.ebi.ac.uk/about/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing uploads\n  text: 'The user responsible for the uploading of any content shall ensure: (i) that they have all required licences,\n    authorisations, permissions and consents for open access dissemination'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chembl/eligibility/chembl-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from ChEMBL's own page on 2026-11-09.
synthetic: false
tags:
- Drug Discovery
- Bioactivity
- Molecules
- Cheminformatics
- Life Sciences
- Bioinformatics
- Pharmacology
- EMBL-EBI
---
