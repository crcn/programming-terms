A curated list of generic terms used in programming. 

## Class names

### Object

> Some *thing*

**Classes**: `Entity`, `Symbol`, `Actor`, `Item`, `Artifact`

### Mediator

> An object which transfers a message between a sender & a receiver

**Classes**: `Notifier`, `Dispatcher`, `Bus`, `EventBus`, `MessageBus`, `Conductor`, `Router`, `Invoker`, `Scheduler`, `MessageBroker`
<br /> **Emit Methods**: `notify`, `emit`, `dispatch`, `execute`, `send`
<br /> **Listen Methods**: `on`, `addReceiver`, `addListener`

### Event

> An object which contains a payload emitted from another object

**Classes**: `Message`, `Event`, `Envelop`, `Action`, `Command`
<br /> **Type Properties**: `type`, `name`, `action`
<br /> **Payload Properties**: `data`, `body`, `payload`, `message`

### Observable

> An object which can be listened to for events

**Classes**: `Observable`, `EventEmitter`, `EventDispatcher`, `Notifiable`
<br /> **Listen Methods**: `observe`, `addListener`, `addEventListener`, `on`
<br /> **Unlisten Methods**: `off`, `removeListener`, `removeEventListener`

### Observer

> An object which can receive messages from another object (observable, mediator)

**Classes**: `Observer`, `EventListener`, `MessageListener`, `Listener`, `EventHandler`, `MessageHandler`, `Consumer`, `Receiver`

### Route

**Classes**: `Route`, `Chan`, `Channel`

### Collections

> A group of one or more items

**Classes**: `Collection`, `Group`, `Vector`, `[TYPE]s` (`Items`, `Images`), `Container`, `Array`

### Other Structures

**Classes**: `Node`, `Tree`

### Others

> Other uncategorized names

**Classes**: `Model`, `ValueObject`, `ActiveRecord`, `Record`, `Controller`, `Manager`, `Actor`, `DataTransferObject`, `DisplayObject`, `Service`, `Facade`, `Adapter`, `Source`, `Client`, `Type`, `Container`, `Store`, `Root`, `Base`, `Abstract`, `Registry`, `Injector`, `Builder`, `Link`

## Function names

### transform

`transform`, `map`, `coerce`, `alter`, `convert`, `mutate`, `morph`

### initialize

`initialize`, `bootstrap`, `init`, `construct`, `configure`, `start`

### find

`query`, `search`
