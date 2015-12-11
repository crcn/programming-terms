This is a compiled list of terms to help you with naming things for you application. 

## OO terms

Object-oriented terms. 

#### Object

> A representation of something

Entity, Symbol

#### Mediator

> An object which transfers a message between a sender & a receiver

**Classes**: Notifier, Dispatcher, Bus, EventBus, MessageBus, Conductor, Router 
<br /> **Emit Methods**: notify, emit, dispatch, execute, send
<br /> **Listen Methods**: on, addReceiver, addListener

#### Event

> An object which contains a payload emitted from another object

**Classes**: Message, Event, Envelop, Action
<br /> **Type Properties**: type, name, action
<br /> **Payload Properties**: data, body, payload, message

#### Observable

> An object which can be listened to for events

**Classes**: Observable, EventEmitter, EventDispatcher, Notifiable
<br /> **Listen Methods**: observe, addListener, addEventListener, on
<br /> **Unlisten Methods**: off, removeListener, removeEventListener

#### Observer

> An object which can receive messages from another object (observable, mediator)

**Classes**: Observer, EventListener, MessageListener

#### Others

> Other uncategorized names

Nouns: Model, ValueObject, Controller, Manager, Actor, DataTransferObject, DisplayObject, Service, Facade, Adapter

## Functional Terms


