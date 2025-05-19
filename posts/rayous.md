%== title: About Rayous
%== subtitle: The component based js ui framework
%== tags: coding, rayous, typescript
%== image: https://media2.dev.to/dynamic/image/width=1000,height=420,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2F8xv0thjynosb4g4gj3rb.png
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
