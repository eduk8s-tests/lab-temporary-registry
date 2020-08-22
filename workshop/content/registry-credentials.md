The credentials for your temporary image registry are:

```
REGISTRY_HOST="{{ registry_host }}"
REGISTRY_USERNAME="{{ registry_username }}"
REGISTRY_PASSWORD="{{ registry_password }}"
```

To login to the registry using ``docker``, run:

```
docker login -u {{ registry_username }} -p {{ registry_password }} {{ registry_host }}
```

The image registry will be available for a period of 24 hours.

If you no longer require the image registry and wish to delete it sooner,
then click on [this link]({{ ENV_RESTART_URL }}) link.
