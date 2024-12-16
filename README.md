# React Router Dom Wildcard Route Issue

This repository demonstrates a bug encountered while using nested routes and wildcard routes in React Router Dom v6.  The wildcard route (`*`) doesn't behave as expected; it intercepts all routes, even those explicitly defined.  The solution provided correctly prioritizes specific routes over the wildcard route.