# Awesome List Updates on Apr 18, 2023

13 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome V](/content/vlang/awesome-v/README.md)

### Command-line

*   [vzcc (⭐27)](https://github.com/malisipi/vzcc) - A CLI cross-compiling tool based on Zig CC for V.

## [2. Awesome React](/content/enaqx/awesome-react/README.md)

### React Tutorials

*   [Design patterns and Component patterns for building powerful Web Apps](https://www.patterns.dev/)

### React Testing

*   [cypress (⭐47k)](https://github.com/cypress-io/cypress) - Fast, easy and reliable testing for anything that runs in a browser

### React Awesome Components

*   [react-insta-stories (⭐1.4k)](https://github.com/mohitk05/react-insta-stories) - A React component for Instagram like stories

## [3. Awesome Neovim](/content/rockerBOO/awesome-neovim/README.md)

### Color / Diagnostics

*   [Mr-LLLLL/interestingwords.nvim (⭐47)](https://github.com/Mr-LLLLL/interestingwords.nvim) - Highlight multiple word same time and navigate word under cursor with scrolling smoothly, display search count in virualtext.

### Colorscheme Creation / Diagnostics

*   [echasnovski/mini.nvim#mini.colors (⭐6.8k)](https://github.com/echasnovski/mini.nvim/blob/main/readmes/mini-colors.md) - Module of `mini.nvim` to tweak and save any color scheme. Also can animate transition and convert between some color spaces.

### Utility / Diagnostics

*   [hbac.nvim (⭐210)](https://github.com/axkirillov/hbac.nvim) - Automatically close buffers you are not working on.

## [4. Awesome Developer First](/content/agamm/awesome-developer-first/README.md)

### Authentication & Identity

*   [Clerk](https://clerk.com/) - Authentication and user management platform for React, React Native, and Next.js.

## [5. Awesome Spark](/content/awesome-spark/awesome-spark/README.md)

### Packages / Middleware

*   [Apache Kyuubi (⭐2.1k)](https://github.com/apache/kyuubi) <img src="https://img.shields.io/github/last-commit/apache/kyuubi.svg"> - A distributed multi-tenant JDBC server for large-scale data processing and analytics, built on top of Apache Spark.

### Resources / Docker Images

*   [apache/spark](https://hub.docker.com/r/apache/spark) - Apache Spark Official Docker images.

## [6. Awesome Orgs](/content/beansource/awesome-orgs/README.md)

### Other

*   [Axo](https://github.com/axodotdev) - Collection of open source Rust libraries and tools.

## [7. Awesome Crystal](/content/veelenga/awesome-crystal/README.md)

### HTML Builders

*   [blueprint (⭐54)](https://github.com/gunbolt/blueprint) - Write reusable and testable HTML templates in plain Crystal

## [8. Awesome Integration](/content/stn1slv/awesome-integration/README.md)

### Integration Patterns / Microservice API Patterns

*   Foundation
    *   [Frontend Integration](https://microservice-api-patterns.org/patterns/foundation/FrontendIntegration) - How can client-side end-user interfaces that are physically separated from server-side business logic and data storage be populated and updated with computing results, result sets from searches in data sources, and detailed information about data entities? How can application frontends invoke activities in a backend or upload data to it?
    *   [Backend Integration](https://microservice-api-patterns.org/patterns/foundation/BackendIntegration) - How can distributed applications and their parts, which have been built independently and are deployed separately, exchange data and trigger mutual activity while preserving system-internal conceptual integrity without introducing undesired coupling?
    *   [Public API](https://microservice-api-patterns.org/patterns/foundation/PublicAPI) - How can an API be made available to an unlimited and/or unknown number of API clients outside the organization that are globally, nationally, and/or regionally distributed?
    *   [Community API](https://microservice-api-patterns.org/patterns/foundation/CommunityAPI) - How can the visibility of and the access to an API be restricted to a closed user group that does not work for a single organizational unit but for multiple legal entities (such as companies, nonprofit/nongovernment organizations, and governments)?
    *   [Solution-Internal API](https://microservice-api-patterns.org/patterns/foundation/SolutionInternalAPI) - How can access to and usage of an API be limited to an application, for instance, components in the same or another logical layer and/or physical tier?
    *   [API Description](https://microservice-api-patterns.org/patterns/foundation/APIDescription) - Which knowledge should be shared between an API provider and its clients? How should this knowledge be documented?
*   Responsibility
    *   Endpoint Roles
        *   [Processing Resource](https://microservice-api-patterns.org/patterns/responsibility/endpointRoles/ProcessingResource) - How can an API provider allow its clients to trigger an action in it?
        *   [Information Holder Resource](https://microservice-api-patterns.org/patterns/responsibility/endpointRoles/InformationHolderResource) - How can domain data be exposed in an API, but its implementation still be hidden? How can an API expose data entities so that API clients can access and/or modify these entities concurrently without compromising data integrity and quality?
    *   Operation Responsibilities
        *   [State Creation Operation](https://microservice-api-patterns.org/patterns/responsibility/operationResponsibilities/StateCreationOperation) - How can an API provider allow its clients to report that something has happened that the provider needs to know about, for instance, to trigger instant or later processing?
        *   [Retrieval Operation](https://microservice-api-patterns.org/patterns/responsibility/operationResponsibilities/RetrievalOperation) - How can information available from a remote party (the API provider, that is) be retrieved to satisfy an information need of an end user or to allow further client-side processing?
        *   [State Transition Operation](https://microservice-api-patterns.org/patterns/responsibility/operationResponsibilities/StateTransitionOperation) - How can a client initiate a processing action that causes the provider-side application state to change? How can API clients and API providers share the responsibilities required to execute and control business processes and their activities?
        *   [Computation Function](https://microservice-api-patterns.org/patterns/responsibility/operationResponsibilities/ComputationFunction) - How can a client invoke side-effect-free remote processing on the provider side to have a result calculated from its input?
    *   Information Holder Types
        *   [Operational Data Holder](https://microservice-api-patterns.org/patterns/responsibility/informationHolderEndpointTypes/OperationalDataHolder) - How can an API support clients that want to create, read, update, and/or delete instances of domain entities that represent operational data: data that is rather short-lived, changes often during daily business operations, and has many outgoing relations?
        *   [Master Data Holder](https://microservice-api-patterns.org/patterns/responsibility/informationHolderEndpointTypes/MasterDataHolder) - How can I design an API that provides access to master data that lives for a long time, does not change frequently, and will be referenced from many clients?
        *   [Reference Data Holder](https://microservice-api-patterns.org/patterns/responsibility/informationHolderEndpointTypes/ReferenceDataHolder) - How should data that is referenced in many places, lives long, and is immutable for clients be treated in API endpoints? How can such reference data be used in requests to and responses from Processing Resources or Information Holder Resources?
        *   [Link Lookup Resource](https://microservice-api-patterns.org/patterns/responsibility/informationHolderEndpointTypes/LinkLookupResource) - How can message representations refer to other, possibly many and frequently changing, API endpoints and operations without binding the message recipient to the actual addresses of these endpoints?
        *   [Data Transfer Resource](https://microservice-api-patterns.org/patterns/responsibility/informationHolderEndpointTypes/DataTransferResource) - How can two or more communication participants exchange data without knowing each other, without being available at the same time, and even if the data has already been sent before its recipients became known?
*   Structure
    *   Representation Elements
        *   [Atomic Parameter](https://microservice-api-patterns.org/patterns/structure/representationElements/AtomicParameter) - How can simple, unstructured data (such as a number, a string, a Boolean value, or a block of binary data) be exchanged between API client and API provider?
        *   [Atomic Parameter List](https://microservice-api-patterns.org/patterns/structure/representationElements/AtomicParameterList) - How can multiple related Atomic Parameters be combined in a representation element so that each of them stays simple, but their relatedness becomes explicit in the API Description and the runtime message exchanges?
        *   [Parameter Tree](https://microservice-api-patterns.org/patterns/structure/representationElements/ParameterTree) - How can containment relationships be expressed when defining complex representation elements and exchanging such related elements at runtime?
        *   [Parameter Forest](https://microservice-api-patterns.org/patterns/structure/representationElements/ParameterForest) - How can multiple Parameter Trees be exposed as request or response payload of an API operation?
    *   Element Stereotypes
        *   [Data Element](https://microservice-api-patterns.org/patterns/structure/elementStereotypes/DataElement) - How can domain/application-level information be exchanged between API clients and API providers without exposing provider-internal data definitions in the API? How can API client and API provider be decoupled from a data management point of view?
        *   [Metadata Element](https://microservice-api-patterns.org/patterns/structure/elementStereotypes/MetadataElement) - How can messages be enriched with additional information so that receivers can interpret the message content correctly, without having to hardcode assumptions about the data semantics?
        *   [Id Element](https://microservice-api-patterns.org/patterns/structure/elementStereotypes/IdElement) - How can API elements be distinguished from each other at design time and at runtime? When applying domain-driven design, how can elements of the Published Language be identified?
        *   [Link Element](https://microservice-api-patterns.org/patterns/structure/elementStereotypes/LinkElement) - How can API endpoints and operations be referenced in request and response message payloads so that they can be called remotely?
    *   Special Purpose Representations
        *   [API Key](https://microservice-api-patterns.org/patterns/structure/specialPurposeRepresentations/APIKey) - How can an API provider identify and authenticate clients and their requests?
        *   [Error Report](https://microservice-api-patterns.org/patterns/structure/specialPurposeRepresentations/ErrorReport) - How can an API provider inform its clients about communication and processing faults? How can this information be made independent of the underlying communication technologies and platforms (for example, protocol-level headers representing status codes)?
        *   [Context Representation](https://microservice-api-patterns.org/patterns/structure/specialPurposeRepresentations/ContextRepresentation) - How can API consumers and providers exchange context information without relying on any particular remoting protocols? How can identity information and quality properties in a request be made visible to related subsequent ones in conversations?
*   Quality
    *   Reference Management
        *   [Embedded Entity](https://microservice-api-patterns.org/patterns/quality/referenceManagement/EmbeddedEntity) - How can one avoid sending multiple messages when their receivers require insights about multiple related information elements?
        *   [Linked Information Holder](https://microservice-api-patterns.org/patterns/quality/referenceManagement/LinkedInformationHolder) - How can messages be kept small even when an API deals with multiple information elements that reference each other?

    *   Data Transfer Parsimony
        *   [Pagination](https://microservice-api-patterns.org/patterns/quality/dataTransferParsimony/Pagination) - How can messages be kept small even when an API deals with multiple information elements that reference each other?
        *   [Wish List](https://microservice-api-patterns.org/patterns/quality/dataTransferParsimony/WishList) - How can an API client inform the API provider at runtime about the data it is interested in?
        *   [Wish Template](https://microservice-api-patterns.org/patterns/quality/dataTransferParsimony/WishTemplate) - How can an API client inform the API provider about nested data that it is interested in? How can such preferences be expressed flexibly and dynamically?
        *   [Conditional Request](https://microservice-api-patterns.org/patterns/quality/dataTransferParsimony/ConditionalRequest) - How can unnecessary server-side processing and bandwidth usage be avoided when frequently invoking API operations that return rarely changing data?
        *   [Request Bundle](https://microservice-api-patterns.org/patterns/quality/dataTransferParsimony/RequestBundle) - How can the number of requests and responses be reduced to increase communication efficiency?

    *   Quality Management and Governance
        *   [Pricing Plan](https://microservice-api-patterns.org/patterns/quality/qualityManagementAndGovernance/PricingPlan) - How can the API provider meter API service consumption and charge for it?
        *   [Rate Limit](https://microservice-api-patterns.org/patterns/quality/qualityManagementAndGovernance/RateLimit) - How can the API provider prevent API clients from excessive API usage?
        *   [Service Level Agreement](https://microservice-api-patterns.org/patterns/quality/qualityManagementAndGovernance/ServiceLevelAgreement) - How can an API client learn about the specific quality-of-service characteristics of an API and its endpoint operations? How can these characteristics, and the consequences of not meeting them, be defined and communicated in a measurable way?
*   Evolution
    *   [Version Identifier](https://microservice-api-patterns.org/patterns/evolution/VersionIdentifier) - How can an API provider indicate its current capabilities as well as the existence of possibly incompatible changes to clients in order to prevent malfunctioning of clients due to undiscovered interpretation errors?
    *   [Semantic Versioning](https://microservice-api-patterns.org/patterns/evolution/SemanticVersioning) - How can stakeholders compare API versions to detect immediately whether they are compatible?
    *   [Two In Production](https://microservice-api-patterns.org/patterns/evolution/TwoInProduction) - How can a provider gradually update an API without breaking existing clients but also without having to maintain a large number of API versions in production?
    *   [Aggressive Obsolescence](https://microservice-api-patterns.org/patterns/evolution/AggressiveObsolescence) - How can API providers reduce the effort for maintaining an entire API or its parts (such as endpoints, operations, or message representations) with guaranteed service quality levels?
    *   [Experimental Preview](https://microservice-api-patterns.org/patterns/evolution/ExperimentalPreview) - How can providers make the introduction of a new API, or new API version, less risky for their clients and obtain early adopter feedback without having to freeze the API design prematurely?
    *   [Limited Lifetime Guarantee](https://microservice-api-patterns.org/patterns/evolution/LimitedLifetimeGuarantee) - How can a provider let clients know for how long they can rely on the published version of an API?
    *   [Eternal Lifetime Guarantee](https://microservice-api-patterns.org/patterns/evolution/EternalLifetimeGuarantee) - How can a provider support clients that are unable or unwilling to migrate to newer API versions at all?

## [9. Awesome Mac](/content/jaywcjlove/awesome-mac/README.md)

### Reading and Writing Tools / Others

*   [Zotero](https://www.zotero.org/) - Free tool to collect, organize, annotate, cite, and share research. [![OSS](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software")](https://github.com/zotero/zotero/) ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")

### Utilities / General Tools

*   [lo-rain](https://lo.cafe/lo-rain) - Create a customizable rain over your desktop and apps, with splash over the dock.

### Utilities / Window Management

*   [Rectangle-app (⭐27k)](https://github.com/rxhanson/Rectangle) - Rectangle is a window management app based on Spectacle, written in Swift: Move and resize windows on macOS with keyboard shortcuts and snap areas. [![Open-Source Software](https://jaywcjlove.github.io/sb/ico/min-oss.svg "Open Source Software") ![Freeware](https://jaywcjlove.github.io/sb/ico/min-free.svg "Freeware")](https://github.com/rxhanson/Rectangle)
*   [Sidebar](http://sidebarapp.net/) - The modern Dock replacement for your Mac.

## [10. Awesome Transit](/content/CUTR-at-USF/awesome-transit/README.md)

### GTFS Merge Tools / Rust

*   [Transitfeed merge function (⭐682)](https://github.com/google/transitfeed/wiki/Merge) - A Python library with a function to merge two different GTFS feeds.

## [11. Free for Dev](/content/ripienaar/free-for-dev/README.md)

### Design Inspiration

*   [LovelyLanding.net](https://www.lovelylanding.net/) - \[Landing Page Designs] Frequently updated landing page screenshots. Includes Desktop, Tablet, and Mobile screenshots.

## [12. Awesome Geojson](/content/tmcw/awesome-geojson/README.md)

### conversion

*   [topojson for Python (⭐188)](https://github.com/mattijn/topojson): Topojson is a library that is capable of creating a topojson encoded format of merely any spatial object in Python.
*   [geomet (⭐171)](https://github.com/geomet/geomet): Pure Python conversion library for common geospatial data formats

## [13. Awesome Flame](/content/flame-engine/awesome-flame/README.md)

### App Releases / Casual

*   BBB - Birds, Beasts, Baddies - [Android](https://play.google.com/store/apps/details?id=com.coconutisland.balloons) - Four furry and feathery friends jump for joy. Avoid enemies, collect mushrooms, jump as high as you can. By [Coconut Island Apps](https://coconutisland.xyz/)

---

- Prev: [Apr 19, 2023](/content/2023/04/19/README.md)
- Next: [Apr 17, 2023](/content/2023/04/17/README.md)