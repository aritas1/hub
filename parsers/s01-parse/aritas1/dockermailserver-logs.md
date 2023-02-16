# docker-mailserver

This is a log splitting parser for the combined log output of the mailserver/docker-mailserver container.

## requirements

When using this parser, you need to specify the program as `docker-mailserver`.

e.G. via `acquis.yaml`: 

```yaml
labels:
 program: docker-mailserver
```
