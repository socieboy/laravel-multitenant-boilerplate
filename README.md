# Multitenancy Boilerplace

#### Jetstream + Inertia

Create your first tenant
```
php artisan migrate
php artisan passport:keys
php artisan tinker
$tenant1 = Tenant::create(['id' => 'tenant']);
$tenant1->domains()->create(['domain' => 'tenant.{you-application}.test']);
```
