# KBase Developer Documentation

* [KBase SDK Documentation](/kb_sdk_docs/)

## Core Service Docs

* Workspace: [release](https://kbase.us/services/ws/docs/), [develop](https://kbase.us/services/ws/docs/)
  * [Release KIDL spec](https://kbase.us/services/ws/docs/Workspace.html), [Develop KIDL spec](https://ci.kbase.us/services/ws/docs/Workspace.html)
* [Narrative UI](https://github.com/kbase/narrative/blob/develop/README.md)
* KBase UI (non-narrative UI): [release](https://narrative.kbase.us/_book/index.html), [develop](https://ci.kbase.us/_book/index.html)
* Relation Engine: [API](https://github.com/kbase/relation_engine_api), [Specifications](https://github.com/kbase/relation_engine_spec)
* Search Engine: [API](https://github.com/kbase/search_api_deluxe), [Indexer](https://github.com/kbase/index_runner_deluxe), [Config](https://github.com/kbase/search_config)
* [Auth server](https://github.com/kbase/auth2/blob/master/README.md)
* [File Caching Service](https://github.com/kbase/CachingService)
* [ID mapping API](https://github.com/jgi-kbase/IDMappingService)
* [Assembly homology API](https://github.com/jgi-kbase/AssemblyHomologyService)
* Service Wizard: [KIDL spec](https://github.com/kbase/service_wizard/blob/master/ServiceWizard.spec)
* Catalog: [KIDL spec](https://github.com/kbase/catalog/blob/master/catalog.spec)

### Relation Engine and Search codebases

* The Relation Engine (using ArangoDB) can be found here: [https://github.com/kbase/relation_engine](https://github.com/kbase/relation_engine)
* The Search API (using Elasticsearch) is found here: [github.com/kbase/search_api2/](github.com/kbase/search_api2/)
* The Index Runner (which listens to Kafka events and imports data into Elasticsearch and ArangoDB) can be found here: [https://github.com/kbase/index_runner](https://github.com/kbase/index_runner)

## User help

* [Using KBase](http://kbase.us/new-to-kbase/)
* [User help board](http://kbase.us/help-board/)
