protected-route
 ============================
 A Route component that redirects unauthenticated users.

[![NPM](https://img.shields.io/npm/v/protected-route.svg)](https://www.npmjs.com/package/Mezrmouse)
[![MIT License][license-image]][license-url]
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FNirBerko%2Fprotected-route.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FNirBerko%2Fprotected-route?ref=badge_shield)

 ## Example
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

protected-route is freely distributable under the terms of the [MIT license](https://github.com/moment/moment/blob/develop/LICENSE).

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FNirBerko%2Fprotected-route.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FNirBerko%2Fprotected-route?ref=badge_large)

[license-image]: http://img.shields.io/badge/license-MIT-blue.svg?style=flat
[license-url]: LICENSE

[travis-url]: https://travis-ci.org/NirBerko/protected-route
[travis-image]: https://travis-ci.org/NirBerko/protected-route.svg?branch=master
