%== title: About Rayous
%== subtitle: The component based js ui framework
%== tags: coding, rayous, typescript
# Rayous
Rayous is a component based ui framework that works by utilizing javascript classes instead of jsx.

Here is a simple example:

```typescript
import { Component, Container, Text } from "rayous";

export default class extends Component {
  build(){
    return new Container({
      children: [
        new Text("Hey!!")
      ]
    });
  }
} 
```
