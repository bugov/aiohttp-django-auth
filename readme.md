# aiohttp-django-auth

Quick and dirty way to integrate aiohttp app with django app.

Works with Python >= 3.5, Django >= 2.0.

## Installation

**coming soon**

```
pip install aiohttp-django-auth
```

## Example

```
from aiohttp_django_auth import get_request_user


async def hello(request):
    user = get_request_user(request)
    return web.Response(body=user.username)
```

## See

Git https://github.com/bugov/aiohttp-django-auth

## Copyright and License

Copyright (C) 2018, Georgy Bazhukov.

This program is free software, you can redistribute it and/or modify it
under the terms of the Artistic License version 2.0.


