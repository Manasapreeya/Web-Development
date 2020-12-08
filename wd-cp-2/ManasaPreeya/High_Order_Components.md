# High order components

## What are High Order Components :question:
Components are the primary unit of code reuse in React. A higher-order component or  **HOC** is an advanced technique in React for reusing component logic.
They are a pattern that emerge from React’s compositional nature. A pattern where a function takes a component as an argument and return a new component.

## Where are they Used :question:
- Whereas a component transforms props into UI, a higher-order component transforms a component into another component.
- HOCs are common in third-party React libraries, such as Redux’s connect and Relay’s createFragmentContainer.

## Why should we Use HOC :question:
- To share common functionalities bw components
- We get to reuse the functionality and not duplicate it over and over.
If 10 diff components needed the exact same functionality, we'd be writing the exact code over and over again (duplicate them) and not reuse them.
- So, there is a need to share a coomon functionality between components without repeating code. HOC is used here.

## Working of HOC :computer:

|HOC doesn’t modify the input component, nor does it use inheritance to copy its behavior.|It composes the original component by wrapping it in a container component.|The wrapped component receives all the props of the container, along with a new prop & data|It uses them to render its output.|
|---------|---------|----------|----------|


### Contributed by 
Manasa preeya S

:email:  manasapreeya01@gmail.com

:wave: GitHub: Manasapreeya
Instagram: @manasa___1
