#  Understanding Data Flow in SwiftUI

A [RW tutorial](https://www.raywenderlich.com/11781349-understanding-data-flow-in-swiftui)

## Property Wrappers in SwiftUI

```
@State
@Binding
@StateObject
@ObservedObject
@EnvironmentObject
@Environment
```


|    `wrapper`         | `type`      | `example / note`    |
|----------------------|-------------|---------------------|
| `@State`             | `value`     |  |
| `@Binding`           |             |  |
| `@StateObject`       | `reference` |  |
| `@ObservedObject`    | `reference` | `class MovieStore: ObservableObject`<br/> |
| `@EnvironmentObject` | `reference` | `class UserStore: ObservableObject,`<br/>`with at least one @Published variable;`<br/>`supplied to an ancestor object,`<br/>` visible by descenants` |
| `@Environment`       |             |  |



![alt](./FaveFlicks/Assets.xcassets/SwiftUI-property-wrappers.imageset/SwiftUI-property-wrappers.png)

