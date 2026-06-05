# Alation (alation)

Alation is a data intelligence platform that helps organizations harness the power of their data by providing a centralized platform for data cataloging, governance, and collaboration. By enabling users to easily search, understand, and trust their data, Alation empowers organizations to make data-driven decisions with confidence. Through advanced analytics and AI capabilities, Alation helps organizations uncover insights, improve data quality, and drive innovation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/alation/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Data Catalog
- Data Governance
- Data Intelligence
- Data Lineage
- Data Quality
- Business Glossary
- Metadata Management
- AI

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Alation Data Catalog API

REST API for managing data sources, schemas, tables, columns, and custom field values in the Alation data catalog. Supports metadata retrieval and batch updates for catalog objects.

- **Human URL:** [https://developer.alation.com](https://developer.alation.com)
- **Base URL:** `https://your-instance.alation.com/integration/v2`

#### Tags

- Data Catalog
- Metadata
- Data Sources
- Schemas
- Tables
- Columns

#### Properties

- [Documentation](https://developer.alation.com)
- [OpenAPI](openapi/alation-data-catalog-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/alation-alation-data-catalog-data-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-data-catalog-schema-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-data-catalog-table-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-data-catalog-column-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-data-catalog-custom-field-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/alation-alation-data-catalog-data-source-structure.json)
- [JSON Structure](json-structure/alation-alation-data-catalog-schema-structure.json)
- [JSON Structure](json-structure/alation-alation-data-catalog-table-structure.json)
- [JSON Structure](json-structure/alation-alation-data-catalog-column-structure.json)
- [JSON Structure](json-structure/alation-alation-data-catalog-custom-field-value-structure.json)
- [Example](examples/alation-alation-data-catalog-data-source-example.json)
- [Example](examples/alation-alation-data-catalog-schema-example.json)
- [Example](examples/alation-alation-data-catalog-table-example.json)
- [Example](examples/alation-alation-data-catalog-column-example.json)
- [Example](examples/alation-alation-data-catalog-custom-field-value-example.json)

### Alation Lineage API

REST API for managing data lineage and dataflow objects in Alation. Supports creating, retrieving, updating, and deleting lineage paths between catalog objects.

- **Human URL:** [https://developer.alation.com/dev/reference/lineage-overview](https://developer.alation.com/dev/reference/lineage-overview)
- **Base URL:** `https://your-instance.alation.com/api/v1`

#### Tags

- Data Lineage
- Dataflow
- Metadata

#### Properties

- [Documentation](https://developer.alation.com)
- [OpenAPI](openapi/alation-lineage-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/alation-alation-lineage-dataflow-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-lineage-lineage-graph-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/alation-alation-lineage-dataflow-structure.json)
- [JSON Structure](json-structure/alation-alation-lineage-lineage-graph-structure.json)
- [Example](examples/alation-alation-lineage-dataflow-example.json)
- [Example](examples/alation-alation-lineage-lineage-graph-example.json)

### Alation Governance API

REST API for data governance workflows in Alation, including business glossary management, governance policy enforcement, and data quality rules and scoring.

- **Human URL:** [https://developer.alation.com](https://developer.alation.com)
- **Base URL:** `https://your-instance.alation.com/integration/v2`

#### Tags

- Data Governance
- Business Glossary
- Data Quality
- Policies

#### Properties

- [Documentation](https://developer.alation.com)
- [OpenAPI](openapi/alation-governance-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/alation-alation-governance-glossary-term-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-governance-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-governance-data-quality-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-governance-data-quality-score-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/alation-alation-governance-glossary-term-structure.json)
- [JSON Structure](json-structure/alation-alation-governance-policy-structure.json)
- [JSON Structure](json-structure/alation-alation-governance-data-quality-rule-structure.json)
- [JSON Structure](json-structure/alation-alation-governance-data-quality-score-structure.json)
- [Example](examples/alation-alation-governance-glossary-term-example.json)
- [Example](examples/alation-alation-governance-policy-example.json)
- [Example](examples/alation-alation-governance-data-quality-rule-example.json)
- [Example](examples/alation-alation-governance-data-quality-score-example.json)

### Alation Search API

REST API for searching and discovering catalog assets in Alation. Supports full-text search, AI-powered aggregated context retrieval, and article browsing.

- **Human URL:** [https://developer.alation.com](https://developer.alation.com)
- **Base URL:** `https://your-instance.alation.com/integration/v2`

#### Tags

- Search
- Data Discovery
- AI
- Catalog

#### Properties

- [Documentation](https://developer.alation.com)
- [OpenAPI](openapi/alation-search-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/alation-alation-search-search-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-search-search-results-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-search-context-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/alation-alation-search-article-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/alation-alation-search-search-result-structure.json)
- [JSON Structure](json-structure/alation-alation-search-search-results-structure.json)
- [JSON Structure](json-structure/alation-alation-search-context-request-structure.json)
- [JSON Structure](json-structure/alation-alation-search-article-structure.json)
- [Example](examples/alation-alation-search-search-result-example.json)
- [Example](examples/alation-alation-search-search-results-example.json)
- [Example](examples/alation-alation-search-context-request-example.json)
- [Example](examples/alation-alation-search-article-example.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/alation)
- [Website](https://alation.com)
- [Documentation](https://developer.alation.com)
- [Getting Started](https://developer.alation.com/dev/docs/about-the-alation-apis)
- [GitHub Organization](https://github.com/Alation)
- [Spectral Rules](rules/alation-spectral-rules.yml)
- [Vocabulary](vocabulary/alation-vocabulary.yaml)
- [JSON-LD](json-ld/alation-alation-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.alation.com/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
