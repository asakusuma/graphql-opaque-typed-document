# graphql-opaque-typed-document

Opaque version of [@graphql-typed-document-node/core](https://github.com/dotansimha/graphql-typed-document-node)

By opaque, we mean that the variable and result types are stashed on the document type as [private types](https://github.com/asakusuma/graphql-opaque-typed-document/blob/main/index.ts#L8-L9), without exposing a bogus field that doesn't actually exist (i.e. [`__apiType`](https://github.com/dotansimha/graphql-typed-document-node/blob/master/packages/core/src/index.ts#L9))