## Constructor: updates\_differenceSlice  

### Attributes:

| Name     |    Type       | Required |
|----------|:-------------:|---------:|
|new\_messages|Array of [Message](../types/Message.md) | Required|
|new\_encrypted\_messages|Array of [EncryptedMessage](../types/EncryptedMessage.md) | Required|
|other\_updates|Array of [Update](../types/Update.md) | Required|
|chats|Array of [Chat](../types/Chat.md) | Required|
|users|Array of [User](../types/User.md) | Required|
|intermediate\_state|[updates\_State](../types/updates\_State.md) | Required|


### Type: [updates\_Difference](../types/updates\_Difference.md)

### Example:


```
$updates_differenceSlice = ['new_messages' => [Message], 'new_encrypted_messages' => [EncryptedMessage], 'other_updates' => [Update], 'chats' => [Chat], 'users' => [User], 'intermediate_state' => updates_State, ];
```