# Laravel DebugBox

A small **developer overlay** for Laravel + Inertia (Vue).  
Shows useful info (current route, page props, entity data, etc.) in a fixed box on your app’s pages — like Laravel Debugbar, but inside the frontend.

## Installation

```bash
composer require vendor/laravel-debug-box --dev
```

## Usage

- After install, reload your app.  
- The DebugBox will appear in the bottom-right corner.  
- Enable/disable via `.env`:

```env
DEBUG_BOX_ENABLED=true
```

## Notes

- Intended for **local / non-production** environments.  
- Still experimental — features and design may change.
