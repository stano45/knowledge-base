**GraphQL** is an open-source data query and manipulation language for APIs, and a runtime for fulfilling queries with existing data.

It provides an approach to developing web APIs and has been compared and contrasted with [[REST]] and other web service architectures. It allows clients to define the structure of the data required, and the same structure of the data is returned from the server, therefore preventing excessively large amounts of data from being returned. 

But this has implications for how effective web caching of query results can be. The flexibility and richness of the query language also adds complexity that may not be worthwhile for simple APIs.

In larger Full-Stack applications, there is usually a GraphQL server handling requests, and the [[Frontend]] formulates its requests in the GraphQL syntax.