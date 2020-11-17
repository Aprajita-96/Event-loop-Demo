# Event-loop-Demo


How the dom uses a event queue to render the DOM.


- Dom is not repainted everytime the DOM update is made , the DOM repaint events are stored in the event queue of the browser and then when the function is completly executed we see the DOM getting repainted because the thread looks into the queue after getting free from the function exection.


- Hence we use the SetTimeOut function. what this does?

the settimeout takes the function itself inside the queue and queues it up for future execution.
