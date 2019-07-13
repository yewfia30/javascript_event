# javascript_event
how to use original event in Javascript

## Overview
- Use dispatchEvent

- Prepare one object, anything is good  
Using Link object in this sample

- Add your own event listener to this link  
This part will be done by User

- Fire your own event  
This part will be done by Supplier

## Description
- init method
  - Set up a listener for your own event at initialization
  - If it is myevent1, the alert shows fired 1
  - If it is myevent2, the alert shows fired 2

- func1 and func2 method
  - make event object and specify event type
  - and fire event by dispatchEvent

## Annotation
Actually, I will handle it when the event comes from dll or somthing like that.  
If the button on the screen is pressed instead,  
Fire myevent1 when the func1 button is pressed  
Fire myevent2 when the func2 button is pressed
