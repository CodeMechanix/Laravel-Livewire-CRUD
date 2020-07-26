## Laravel Livewire

Livewire is a full-stack framework for Laravel that makes building dynamic interfaces simple, without leaving the comfort of Laravel.

###  Install Livewire
> composer require livewire/livewire

### What’s the benefit of using Livewire components?

- When we create Vue components we always created dedicated REST endpoints to get/create/delete/update resources. But with Livewire it’s not needed, every Livewire component automatically creates its own REST endpoints and handles them behind the scenes.
- We created separate methods, event handlers both on frontend and backend.
- Unit testing becomes super easy. Because everything is in PHP and component properties, methods are publicly accessible, unit testing of components does not require any additional testing tools.

### Conclusion

Livewire is not a total replacement for frontend libraries or frameworks. Because of its unique reactive nature, every binding, method call or event handling is a round-trip to the backend. If you want to have full control over how frontend and backend behave separately or if your frontend component does not rely on data exchange with backend, creating pure Vue components would be a better option than using Livewire. But if you want to create a frontend component which actively needs to communicate with backend, Livewire makes it super easy to archive.
    
Learning Reference: 
- Different Websites
