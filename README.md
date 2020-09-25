# Multitenancy Boilerplace
```

php artisan migrate
$tenant1 = Tenant::create(['id' => 'tenant']);
$tenant1->domains()->create(['domain' => 'tenant.project.test']);
```
