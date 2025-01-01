# React Router Catch-All Route Conflict

This repository demonstrates a common issue in React Router v6 where a catch-all route (`/*`) interferes with other defined routes.  The problem arises when the catch-all route unintentionally intercepts requests meant for other, more specific routes.

The solution involves carefully ordering routes and potentially using more precise path matching to ensure that catch-all routes only handle URLs that aren't matched by other routes.