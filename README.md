# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React applications: creating an infinite loop within a `useEffect` hook.

## Description
The `bug.js` file contains a component that attempts to increment a state variable (`count`) within its `useEffect` hook without any condition to stop it, leading to an infinite re-render cycle.

## Solution
The solution (`bugSolution.js`) demonstrates how to avoid this issue by adding a condition or using a different approach. 
