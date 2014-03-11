# Event

Super hyper simple event dispatcher implementation.

## Usage

Instantiate the event dispatcher

    var dispatcher = new event.Dispatcher();
    
Attach an event

    dispatcher.attach('eventName', function(event){
      alert(event.name);
    });
    
Dispatch an event

    dispatcher.dispatch({name: 'eventName'});
    
## License

Licensed under MIT license.
