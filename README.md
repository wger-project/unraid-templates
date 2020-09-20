# TO ADD

## REDIS CACHE

```python
CACHES = {
    'default': {
        'BACKEND': os.environ.get("DJANGO_CACHE_BACKEND"),
        'LOCATION': os.environ.get("DJANGO_CACHE_LOCATION"),
        'TIMEOUT': os.environ.get("DJANGO_CACHE_TIMEOUT"),
        'OPTIONS': {
            'CLIENT_CLASS': os.environ.get("DJANGO_CACHE_CLIENT_CLASS"),
        }
    }
}
```