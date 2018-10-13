[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FNirBerko%2Fprotected-route.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FNirBerko%2Fprotected-route?ref=badge_shield)

protected-route
 ============================
 A Route component that redirects unauthenticated users.

 # Example
 ```js
 import ProtectedRoute from "protected-route";

 <Switch>
     <ProtectedRoute
         isAllowed
         redirectToPath="/login"
         path="/"
         component={Dashboard}
     />
     <Route
         path="/login"
         render={Login}
     />
 </Switch>
 ```

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FNirBerko%2Fprotected-route.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FNirBerko%2Fprotected-route?ref=badge_large)