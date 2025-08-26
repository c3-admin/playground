# Yahlox Playground

**Playground** is a testing ground for experimenting with my custom libraries, prototypes, and integration setups. This repository is not intended for production use — it serves as a sandbox to validate features, run quick experiments, and test ideas before they’re applied in real projects.

## Installation
### Clone the repository
``` bash
git clone https://github.com/yahlox/playground.git
cd playground
```

### Download and Install dependencies
``` bash
composer install
npm install
npm run build 
```

### Copy .env.example to .env
``` bash
cp .env.example .env
```

#### Generate Larave Key
``` bash
php artisan key:generate
```

### Migrate database with initial seed (SQLITE)
``` bash
php artisan migrate --seed
```

