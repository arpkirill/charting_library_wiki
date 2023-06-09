## :warning: WARNING :warning:

### Our documentation has moved to a [new site](https://www.tradingview.com/charting-library-docs/)

You can find the corresponding page here: [IDelegate](https://www.tradingview.com/charting-library-docs/latest/api/interfaces/Broker.IDelegate)

---

<br/>
<br/>

Delegate is an object that is used in the [Account Manager](Account-Manager) to notify about events happening with orders, positions and other information displayed in the tables.

### subscribe(object, member)

1. `object` is an owner of `member`, and can be null for a function
1. `member` is a method of object

Subscribes `object::member` to the event.

### unsubscribe(object, member)

Unsubscribes `object::member` from the event.

Use the same object and `member` that you used in the `subscribe` function to unsubscribe from the event.
