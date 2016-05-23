### PluggableWeb

### The Problem
- Large, monolith products are hard to keep maintained, tested, and deployed in a sane manner
- Trying to update a codebase by either migrating to a new framework or update to a breaking version of a framework is hard to do incrementally. Especially if the original application was built entirely with a new framework.
 

### The Solution
- Build a pluggable architecture that will allow for independent testing and deploying.
- The architecture will be framework agnostic and will provide hooks to bootstrap any framework and do cross communication
