# RxJS

## Notes
- Observable: collection of future values or events
- Observer: collection of callbacks that knows how to listen to values
- Subscription: represents the execution of an Observable, (unsubscribe())
- Operators: functions that are dealing with the values comming from the observale
- Subject: equivalent to an EventEmitter, and the only way of multicasting a value or event to multiple Observers.
- Schedulers: centralized dispatchers to control concurrency, allowing us to coordinate when computation happens