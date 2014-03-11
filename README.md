# Event
=====

Super hyper simple event dispatcher implementation.

## Usage

Instantiate the event dispatcher

    var dispatcher = new EventDispatcher();
    
Attach an event

    dispatcher.attach('eventName', function(event){
      alert(event.name);
    });
    
Dispatch an event

    dispatcher.dispatc({name: 'eventName'});
    
## License

Licensed under MIT license.
