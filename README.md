# React Router v6 Catch-all Route Bug

This repository demonstrates a bug in React Router v6 related to catch-all routes (`/*`) and their interaction with nested routes.  In some scenarios, the catch-all route unexpectedly overrides more specific routes, leading to incorrect rendering.  The issue is particularly noticeable when dealing with nested route structures.

## Bug Description

The bug is described in `App.js`.  The catch-all route `/` should only match when no other routes match. However, in some cases it incorrectly matches even when a more specific route exists leading to unexpected behavior. 

## Solution

A solution is provided in `AppSolution.js` that fixes the issue.