# Unexpected Type Error in React Native

This repository demonstrates a common error in React Native applications: the "Unexpected type" error when dealing with component props. This error occurs when a component receives a prop of an unexpected type, leading to runtime issues.

## Problem

The provided `MyComponent` expects a `number` prop called `count`. However, the parent component passes a string instead, resulting in an `Unexpected type` error.

## Solution

The solution involves ensuring that the prop passed to `MyComponent` is of the expected type. This can be achieved through type checking before passing the prop or by converting the prop's type before usage.