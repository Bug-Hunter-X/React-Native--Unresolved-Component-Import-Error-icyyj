# React Native Unresolved Component Import

This repository demonstrates a common React Native error: failing to import a component correctly.

## The Problem

The `BuggyComponent.js` file attempts to render the `MyComponent` component without importing it. This leads to a runtime error indicating that `MyComponent` is not defined.

## The Solution

`FixedComponent.js` shows the corrected version.  The `MyComponent` is imported correctly using:

`import MyComponent from './MyComponent';`

Remember to make sure the path to your component is correct and that the component has been properly installed using npm or yarn.