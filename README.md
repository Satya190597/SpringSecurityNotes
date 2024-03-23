# SpringSecurityNotes

## Key components of Spring Security.
- Authentication
  - AuthenticationManager
  - AuthenticationProvider
  - UserDetailsService
  - PasswordEncoder
- Authorization
  - GrantedAuthority
  - Authentication
  - SecurityContextHolder
- Filters
  - FilterChainProxy
  - SecurityFilters
- Additional Components
  - SecurityContext
  - Remember-Me Functionality
## AuthenticationManager
This interface is the central component responsible for user authentication. It delegates the task to one or more AuthenticationProvider.
- Flow
  - The AuthenticationManager acts as a gatekeeper, ensuring only authorized users can access protected resources in your application.
  - It receives an Authentication object containing the user's credentials (typically username and password) as input.
  - It delegates the authentication task to one or more AuthenticationProviders configured within the AuthenticationManager.

## Resources

| Name | Link |
|----------|------|
| Java Brains - How Spring Security Authentication works | https://www.youtube.com/watch?v=caCJAJC41Rk |
