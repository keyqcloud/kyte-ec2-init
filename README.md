# OPcache

Recommended settings to change or enable

```
zend_extension=opcache
opcache.enable=1
opcache.memory_consumption=128
opcache.interned_strings_buffer=8
opcache.max_accelerated_files=4000
opcache.revalidate_freq=60
opcache.huge_code_pages=1
```

See details:
https://www.php.net/manual/en/opcache.installation.php#opcache.installation.recommended