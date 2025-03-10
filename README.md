
![img](https://github.com/ekovegeance/inertia-boilerplate/blob/main/inertia-boilerplate.png)
## Getting Started

First, run the development server:

```bash
git clone https://github.com/ekovegeance/inertia-boilerplate && cd inertia-boilerplate
composer install && npm install
```
```bash
php artisan serve && npm run dev
```

Configure your local environment
```bash
cp .env.local .env
```
```bash
php artisan key:generate
```
Migrate database
```bash
php artisan migrate --seed
```

Open [http://localhost:8000](http://localhost:8000) with your browser to see the result.
Use [Style Guide](https://ekovegeance.github.io/styleguide/coding/laravel) for Consistent Development 

## Tech Stack

- [Laravel](https://laravel.com/docs/11.x) - learn about Laravel
- [Eloquent ORM](https://laravel.com/docs/11.x/eloquent) - MySQL
- [Auth Laravel Breeze](https://laravel.com/docs/11.x/starter-kits#laravel-breeze) - Inertia React
- [Dependencies/ third party library](https://github.com/ekovegeance/laravel-templates/blob/main/package.json)

With shadcn/ui [Beautifully designed components that you can copy and paste into your apps. Accessible. Customizable. Open Source.](https://ui.shadcn.com/) 
Generate UI [v0](https://v0.dev/https://v0.dev/)


