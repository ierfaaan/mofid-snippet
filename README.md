# Mofid Snippet

The essential collection of React Snippets.

## Features

Only what you need and nothing more. **No Redux. No React Native.**

Simply, simple React snippets.

These snippets were selected carefully from my own day-to-day React use. Not
everything in React is included here. This is a hand selected set of snippets
that work the way that you would expect, not just a copy of the documentation.

## Snippets

| Snippet     | Renders                                                   |
| ----------- | --------------------------------------------------------- |
| `fc`        | Function Component                                        |
| `fcc`       | Function Component With Children Props                    |
| `fcd`       | Function Component With export Default                    |
| `fccd`      | Function Component With Children Props and export Default |
| `clg`       | log                                                       |
| `stater`    | React.useState                                            |
| `effectr  ` | React.useEffect                                           |
| `callbackr` | React.useCallback                                         |
| `memor`     | React.useMemo                                             |
| `state`     | useState                                                  |
| `effect`    | useEffect                                                 |
| `callback`  | useCallback                                               |
| `memo`      | useMemo                                                   |
| `get`       | get Request                                               |
| `post`      | post Request                                              |
| `delete`    | delete Request                                            |
| `put`       | put Request                                               |
| `patch`     | patch Request                                             |

## Full Expansions

### fc - Function Component

```typescript
interface |Props {

}

const |: FunctionComponent<|Props> = () => {
    return (  );
}

export default |;
```

### fcc - Function Component With Children Props

```typescript
import React,{FunctionComponent,PropsWithChildren} from 'react'

interface postPropsType extends PropsWithChildren {
    |
}

export const post: FunctionComponent<postPropsType> = () => {
    return ( <div>post</div> );
}

```

### fcd - Function Component With export Default

```typescript
import React,{FunctionComponent} from 'react'

interface postPropsType {
    |
}

const post: FunctionComponent<postPropsType> = () => {
    return ( <div>post</div> );
}

export default post
```

### fccd - Function Component With Children Props and export Default

```typescript
import React, { FunctionComponent, PropsWithChildren } from "react";

interface postPropsType extends PropsWithChildren {}

const post: FunctionComponent<postPropsType> = () => {
  return <div>post</div>;
};

export default post;
```

### clg - log

```typescript
console.log(|)
```

### stater - useState hook from React

```typescript
const [, set] = React.useState();
```

### effectr - useEffect hook from React

```typescript
React.useEffect(() => {}, []);
```

### callbackr - callback hook from React

```typescript
const | = React.useCallback(()=>{

},[])
```

### memor - useMemo hook from React

```typescript
const | = React.useMemo(()=>{

},[])
```

### state - useState hook

```typescript
const [, set] = useState();
```

### effect - useEffect hook

```typescript
useEffect(() => {}, []);
```

### callback - useCallback hook

```typescript
const | = useCallback(()=>{

},[])
```

### memo - useMemo hook

```typescript
const | = useMemo(()=>{

},[])
```

### get - create get Request with axios-query package

```typescript
import {AQHookTypeHelper, AQMethodTypeHelper, CreateApi} from "axiosQuery"

export type UseGET|Type = AQHookTypeHelper<{
method: AQMethodTypeHelper<"GET">
}>

export const useGET| = CreateApi<UseGET|Type>({
endPoint: () => ``,
name: () => [],
method: "GET",
})
```

### post - create post Request with axios-query package

```typescript
import { AQHookTypeHelper, AQMethodTypeHelper, CreateApi } from "axiosQuery";

export type UsePOSTType = AQHookTypeHelper<{
  method: AQMethodTypeHelper<"POST">,
}>;

export const usePOST =
  CreateApi <
  UsePOSTType >
  {
    endPoint: () => ``,
    name: () => [],
    method: "POST",
  };
```

### delete - create delete Request with axios-query package

```typescript
import {AQHookTypeHelper, AQMethodTypeHelper, CreateApi} from "axiosQuery"

export type UseDELETE|Type = AQHookTypeHelper<{
method: AQMethodTypeHelper<"DELETE">
}>

export const useDELETE| = CreateApi<UseDELETE|Type>({
endPoint: () => ``,
name: () => [],
method: "DELETE",
})
```

### put - create put Request with axios-query package

```typescript
import { AQHookTypeHelper, AQMethodTypeHelper, CreateApi } from "axiosQuery";

export type UsePUTType = AQHookTypeHelper<{
  method: AQMethodTypeHelper<"PUT">,
}>;

export const usePUT =
  CreateApi <
  UsePUTType >
  {
    endPoint: () => ``,
    name: () => [],
    method: "PUT",
  };
```

### patch - create patch Request with axios-query package

```typescript
import { AQHookTypeHelper, AQMethodTypeHelper, CreateApi } from "axiosQuery";

export type UsePATCHType = AQHookTypeHelper<{
  method: AQMethodTypeHelper<"PATCH">,
}>;

export const usePATCH =
  CreateApi <
  UsePATCHType >
  {
    endPoint: () => ``,
    name: () => [],
    method: "PATCH",
  };
```

## Thank You! ❤️

While I wrote the initial version of this extension, many people (too many to name) have helped make it what it is today. From providing TypeScript definitions to keeping up with changing API and best practices. If you are enjoying this extension, you have the great React community to thank.
