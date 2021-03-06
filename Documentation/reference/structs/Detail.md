**STRUCT**

# `Detail`

```swift
public struct Detail: Decodable, Equatable
```

## Properties
### `id`

```swift
public let id: Int
```

> The comment's id

### `version`

```swift
public let version: Int
```

> The comment's version

### `text`

```swift
public let text: String
```

> The comment content

### `author`

```swift
public let author: User
```

> The author of the comment

### `createdAt`

```swift
public let createdAt: Int
```

> Date comment created as number of mili seconds since the unix epoch

### `updatedAt`

```swift
public let updatedAt: Int
```

> Date comment updated as number of mili seconds since the unix epoch

### `comments`

```swift
public let comments: [Detail]
```

> Replys to the comment

### `properties`

```swift
public let properties: InnerProperties
```

> Properties associated with the comment

### `tasks`

```swift
public let tasks: [Task]
```

> Tasks associated with the comment
