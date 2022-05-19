# Graphql 17 graphql-tools/utils incompatibility

```
> pnpm i

> import { parse, GraphQLError, isNonNullType, Kind, valueFromAST, print, isObjectType, isListType, isSpecifiedDirective, astFromValue, isSpecifiedScalarType, isIntrospectionType, isInterfaceType, isUnionType, isInputObjectType, isEnumType, isScalarType, GraphQLDeprecatedDirective, specifiedRules, concatAST, validate, versionInfo, buildClientSchema, visit, TokenKind, Source, isTypeSystemDefinitionNode, getNamedType, GraphQLString, GraphQLNonNull, GraphQLList, GraphQLID, GraphQLBoolean, GraphQLFloat, GraphQLInt, GraphQLObjectType, GraphQLInterfaceType, GraphQLInputObjectType, GraphQLDirective, GraphQLUnionType, GraphQLEnumType, GraphQLScalarType, isNamedType, getNullableType, isLeafType, GraphQLSchema, isDirective, isCompositeType, doTypesOverlap, getOperationAST, getDirectiveValues, GraphQLSkipDirective, GraphQLIncludeDirective, typeFromAST, isAbstractType, getOperationRootType, TypeNameMetaFieldDef, buildASTSchema } from 'graphql';
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    ^^^^^^^^^^^^^^^^^^^^
SyntaxError: The requested module 'graphql' does not provide an export named 'getOperationRootType'
    at ModuleJob._instantiate (node:internal/modules/esm/module_job:128:21)
    at async ModuleJob.run (node:internal/modules/esm/module_job:194:5)
    at async Promise.all (index 0)
    at async ESMLoader.import (node:internal/modules/esm/loader:385:24)
    at async loadESM (node:internal/process/esm_loader:88:5)
    at async handleMainPromise (node:internal/modules/run_main:61:12)
```
