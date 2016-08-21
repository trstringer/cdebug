# cdebug

*Conditional debugging in code... a nice, terse solution*

This is just a wrapper around `debugger`.

## Installation

```
npm install cdebug
```

## Usage

```javascript
let myVar = 1;
// conditional breakpoint
cdebug(myVar === 1); // breakpoint hit

myVar = 2;
cdebug(myVar === 1); // breakpoint not hit
```
