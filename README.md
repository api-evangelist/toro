# Toro

The Toro Company is a leading worldwide provider of innovative solutions for the outdoor environment, including turf and landscape maintenance, snow and ice management, underground utility construction, rental and specialty construction, and irrigation and outdoor lighting solutions. Founded in 1914, Toro offers smart connected products and software platforms for golf courses, landscape contractors, and sports turf managers.

**Website:** [https://www.thetorocompany.com/](https://www.thetorocompany.com/)
**Smart Connected Products:** [https://www.thetorocompany.com/smart-connected-products](https://www.thetorocompany.com/smart-connected-products)

---

## APIs

### Toro Horizon360

All-in-one business management software for landscape contractors covering customer management, job scheduling, crew dispatch, invoicing, equipment tracking, and payment processing.

- **Documentation:** [https://horizon360.toro.com/](https://horizon360.toro.com/)
- **OpenAPI Spec:** [openapi/toro-horizon360-openapi.yml](openapi/toro-horizon360-openapi.yml)

### Toro IntelliDash

Irrigation and fleet management platform for golf course superintendents. Integrates with Lynx Central Control, myTurf Pro, Turf Guard sensors, and IntelliDash Alliance partners to provide real-time agronomic and operational data.

- **Documentation:** [https://www.toro.com/en/product/IntelliDash](https://www.toro.com/en/product/IntelliDash)
- **OpenAPI Spec:** [openapi/toro-intellidash-openapi.yml](openapi/toro-intellidash-openapi.yml)

### Toro myTurf

Web-based equipment management solution for golf courses and sports fields providing fleet tracking, maintenance scheduling, work orders, and parts management.

- **Documentation:** [https://www.toro.com/en/professional-contractor](https://www.toro.com/en/professional-contractor)

---

## Artifacts

### OpenAPI Specifications

| File | API | Description |
|---|---|---|
| [toro-horizon360-openapi.yml](openapi/toro-horizon360-openapi.yml) | Horizon360 | Landscape business management |
| [toro-intellidash-openapi.yml](openapi/toro-intellidash-openapi.yml) | IntelliDash | Golf irrigation and fleet management |

### Naftiko Capabilities

**Workflow Capabilities:**

| File | Description |
|---|---|
| [capabilities/landscape-operations.yaml](capabilities/landscape-operations.yaml) | End-to-end landscape contractor operations (12 tools) |
| [capabilities/golf-course-management.yaml](capabilities/golf-course-management.yaml) | Golf course irrigation and fleet management (12 tools) |

**Shared Per-API Definitions:**

| File | API |
|---|---|
| [capabilities/shared/horizon360.yaml](capabilities/shared/horizon360.yaml) | Toro Horizon360 |
| [capabilities/shared/intellidash.yaml](capabilities/shared/intellidash.yaml) | Toro IntelliDash |

### JSON Schemas

| File | Resource |
|---|---|
| [json-schema/toro-customer-schema.json](json-schema/toro-customer-schema.json) | Customer |
| [json-schema/toro-job-schema.json](json-schema/toro-job-schema.json) | Job |

### JSON Structure

| File | Resource |
|---|---|
| [json-structure/toro-customer-structure.json](json-structure/toro-customer-structure.json) | Customer |

### JSON-LD Context

| File | Description |
|---|---|
| [json-ld/toro-context.jsonld](json-ld/toro-context.jsonld) | Linked data context mapping Toro resources to schema.org |

### Examples

| File | Operation |
|---|---|
| [examples/toro-list-customers-example.json](examples/toro-list-customers-example.json) | List Customers |
| [examples/toro-get-irrigation-status-example.json](examples/toro-get-irrigation-status-example.json) | Get Irrigation Status |

### Spectral Rules

| File | Description |
|---|---|
| [rules/toro-spectral-rules.yml](rules/toro-spectral-rules.yml) | API design rules for Toro OpenAPI specifications |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/toro-vocabulary.yml](vocabulary/toro-vocabulary.yml) | Domain vocabulary for Toro landscape and irrigation management |

---

## Tags

`Landscaping` `Irrigation` `Golf` `Equipment` `Smart Connected Products` `Fleet Management` `Turf Management`
