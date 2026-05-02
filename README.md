# LogRocket (logrocket)
LogRocket is a session replay and monitoring platform that helps development teams understand user behavior and diagnose issues in web and mobile applications. Their developer platform provides REST, GraphQL, and data export APIs alongside JavaScript and React Native SDKs for capturing session recordings, tracking errors, and integrating monitoring data into custom workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/logrocket/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Session Replay, Error Monitoring, Analytics, Observability, Frontend Monitoring

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-04-28

## APIs

### LogRocket REST API
The LogRocket REST API provides programmatic access to LogRocket session replay and monitoring data. It enables developers to manage user identification by sending demographic and engagement data via PUT requests to contextualize user behavior. The API also supports retrieving session highlights and exported session data. All endpoints require an API access key available from the LogRocket dashboard under Settings.

**Human URL:** [https://docs.logrocket.com/reference](https://docs.logrocket.com/reference)


#### Tags:

 - Session Replay, Error Monitoring, User Identification, Analytics, Observability

#### Properties

- [Documentation](https://docs.logrocket.com/reference)
- [OpenAPI](openapi/logrocket-rest-api-openapi.yml)

### LogRocket GraphQL API
The LogRocket GraphQL API allows developers to query session replay and analytics data using GraphQL. It provides a flexible query interface for retrieving session information, user activity, error details, and performance metrics. Developers can use this API to build custom dashboards, integrate session data into internal tools, and perform advanced filtering and aggregation of LogRocket monitoring data.

**Human URL:** [https://docs.logrocket.com/reference/graphql-1](https://docs.logrocket.com/reference/graphql-1)


#### Tags:

 - Session Replay, GraphQL, Analytics, Querying, Observability

#### Properties

- [Documentation](https://docs.logrocket.com/reference/graphql-1)
- [OpenAPI](openapi/logrocket-graphql-api-openapi.yml)

### LogRocket JavaScript SDK
The LogRocket JavaScript SDK enables session replay and error monitoring for web applications. Once initialized with LogRocket.init(), it automatically records user sessions including DOM changes, network requests, console logs, and JavaScript errors. The SDK provides methods for user identification, session URL retrieval, and custom event tracking. It can be installed via npm or script tag and integrates with popular frameworks like React, Angular, and Vue.

**Human URL:** [https://docs.logrocket.com/reference/getting-started-with-sdks](https://docs.logrocket.com/reference/getting-started-with-sdks)


#### Tags:

 - Session Replay, JavaScript, SDK, Browser, Frontend Monitoring

#### Properties

- [Documentation](https://docs.logrocket.com/reference/getting-started-with-sdks)

### LogRocket React Native SDK
The LogRocket React Native SDK brings session replay and error monitoring to React Native mobile applications. It captures wireframes of UI elements, network requests, and application errors to help developers reproduce and diagnose issues on mobile devices. The SDK provides initialization, user identification, and session URL access methods similar to the browser SDK, adapted for the React Native environment.

**Human URL:** [https://docs.logrocket.com/reference/configure-reactnative-sdk](https://docs.logrocket.com/reference/configure-reactnative-sdk)


#### Tags:

 - Session Replay, React Native, SDK, Mobile, Mobile Monitoring

#### Properties

- [Documentation](https://docs.logrocket.com/reference/configure-reactnative-sdk)

### LogRocket Data Export API
The LogRocket Data Export API enables automated export of session data into file storage buckets for external analysis. When a session completes, LogRocket creates a JSON Lines file containing the session data which can be retrieved programmatically. This API is useful for teams that need to integrate LogRocket session data into their data warehouses, build custom analytics pipelines, or perform long-term retention and analysis of user behavior data.

**Human URL:** [https://docs.logrocket.com/docs/data-export](https://docs.logrocket.com/docs/data-export)


#### Tags:

 - Data Export, Analytics, Session Data, Storage, ETL

#### Properties

- [Documentation](https://docs.logrocket.com/docs/data-export)

### LogRocket User Identification API
The LogRocket User Identification API allows developers to send user demographic, financial, and engagement data from any backend system to LogRocket. Using PUT requests to the organizations and apps endpoint, developers can attach user attributes such as subscription type, revenue data, and product interest to session recordings. This enables teams to contextualize user behavior, filter sessions by user attributes, and break down business metrics within the LogRocket dashboard.

**Human URL:** [https://docs.logrocket.com/docs/user-identification-api](https://docs.logrocket.com/docs/user-identification-api)


#### Tags:

 - User Management, Identification, User Data, Analytics

#### Properties

- [Documentation](https://docs.logrocket.com/docs/user-identification-api)

### LogRocket Galileo Highlights API
The LogRocket Galileo Highlights API provides programmatic access to AI-generated session summaries and highlights. Galileo AI watches user sessions and automatically identifies and aggregates problematic interactions, errors, and notable user behaviors. Developers can use this API to retrieve session highlights via POST requests, enabling integration of AI-powered session insights into custom workflows, alerting systems, and internal dashboards.

**Human URL:** [https://docs.logrocket.com/docs/session-highlights-api](https://docs.logrocket.com/docs/session-highlights-api)


#### Tags:

 - Session Replay, AI, Highlights, Summarization, Observability

#### Properties

- [Documentation](https://docs.logrocket.com/docs/session-highlights-api)
- [AsyncAPI](asyncapi/logrocket-highlights-webhook-asyncapi.yml)

## Common Properties

- [Portal](https://docs.logrocket.com/reference)
- [Documentation](https://docs.logrocket.com/)
- [Website](https://logrocket.com/)
- [PrivacyPolicy](https://logrocket.com/privacy)
- [TermsOfService](https://logrocket.com/terms)
- [Blog](https://blog.logrocket.com/)
- [Login](https://app.logrocket.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
