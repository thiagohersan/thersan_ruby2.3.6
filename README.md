YAML definition for creating a multi-architecture manifest (amd64/x86_64 and armhf/arm32v7) for the ruby:2.3.6 docker image.

Using [manifest-tool](https://github.com/estesp/manifest-tool) to create the manifest and upload to Docker Hub:

```
manifest-tool --username=my_name --password=my_password push from-spec thersan_ruby2.3.6.yaml
```
