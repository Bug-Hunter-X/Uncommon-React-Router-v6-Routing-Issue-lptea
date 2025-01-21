# Uncommon React Router v6 Bug

This repository demonstrates a subtle bug in React Router v6.  A seemingly correct route definition leads to unexpected routing issues.  The solution involves carefully examining route nesting and potential conflicts.

## Bug Description

The bug is present in `bug.js`.  The `/contact` route, when added, interferes with other routes, resulting in incorrect page rendering or errors such as `NoRouteMatch`.  The error is not immediately apparent from inspecting the route configuration.

## Solution

The solution is provided in `bugSolution.js`.  The problem and its solution are explained in detail in the comments.