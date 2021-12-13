# SurrealDB Licensing

SurrealDB is an end-to-end cloud native database for web, mobile, serverless, jamstack, backend, and traditional applications.

Source code for SurrealDB is variously licensed under a number of different licenses. A copy of each license can be found in [each repository](https://github.com/surrealdb).

- Libraries and SDKs, each located in its own distinct repository, are released under either the [Apache License 2.0](https://github.com/surrealdb/license/blob/main/APL.txt) or [MIT License](https://github.com/surrealdb/license/blob/main/MIT.txt).
- Certain core database components, each located in its own distinct repository, are released under the [Apache License 2.0](https://github.com/surrealdb/license/blob/main/APL.txt).
- Core database code for SurrealDB, located [here](https://github.com/surrealdb/surrealdb), is released under the [Business Source License 1.1](https://github.com/surrealdb/surrealdb/blob/main/LICENSE).

The code licensed under the Business Source License is free to use and the source code is freely available, but users may not provide SurrealDB as a managed service, or a database-as-a-service (DBaaS), without an agreement with SurrealDB Ltd. The Business Source License is not certified as an open-source license, but most of the Open Source Initiative (OSI) criteria are met - allowing it to be used in production without limits.

## How open is the Business Source License?

We have decided to adopt an extremely permissive version of the Business Source License (BSL). SurrealDB users can use and scale SurrealDB to any number of nodes. They can use SurrealDB or embed it in their applications (whether they ship those applications to customers or run them as a service). They can even run it as a service internally, to their employees, contractors, and subsidiary companies. The only thing that SurrealDB users will not be able to do is offer a commercial version of SurrealDB as a service without buying a license.

We are committed to further the open-source ideal, and consequently this restriction has a rolling time limit: four years after each release, the license converts to the standard [Apache License 2.0](https://github.com/surrealdb/license/blob/main/APL.txt). By adopting a time restriction we intend to simultaneously create a competitive database-as-a-service (DBaaS) while also providing a guarantee that the core product will become pure open source.

## How does the Business Source License work?

We are not alone in adopting a license with a time-limited restriction, and along with several other companies we have decided to use MariaDB's Business Source License (BSL) 1.1 which has the provisions we want (and it has already been endorsed by OSI founder Bruce Perens). 

The BSL is a parameterized license, so our use of it is not exactly the same as MariaDB's. The key difference is in the *Additional Use Grant* - SurrealDB's *Additional Use Grant* allows you to use SurrealDB with as many nodes as you want as long as you are not offering it as a commercial DBaaS. Our BSL protects SurrealDB's current code from being used as a DBaaS without an enterprise license for a period of four years. After 4 years this restriction lapses and the code becomes open source, per our current [Apache License 2.0](https://github.com/surrealdb/license/blob/main/APL.txt), and is free to use for any purpose.

We are applying this license to the core edition of SurrealDB, which is consequently no longer *Open Source* (according to OSI's Open Source Definition), although the complete source code is still freely available, and any commercial usage is allowed with the one exception of building a DBaaS. We believe that this is the best way to balance the needs of the business with our commitment to Open Source. Our BSL license still permits the vast majority of users to use, redistribute, and modify SurrealDB freely, and will become no-strings-attached Open Source after four years.

We continue to be committed to building a powerful core product that is open source and consider that this compromise is closest to the spirit of open source, while still protecting our business. Of course, four years after each release, our commitment to Open Source will be demonstrated.

## Do I need to purchase a SurrealDB license for development use?

No! SurrealDB is free to use for all development and pre-production use.

## Do I need to purchase a SurrealDB license for production scenarios?

No! SurrealDB is free to use for production use.