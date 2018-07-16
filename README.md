protected-route
 ============================
 A Route component that redirects unauthenticated users.

 # Example
 ```js
 import ProtectedRoute from "react-router-protected-route";

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