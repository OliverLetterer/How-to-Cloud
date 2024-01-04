# Cloud Manifest

## Motivation

Most services consist of a single application. Therefore, deploying an entire operating system, with process separation, permissions and address spaces is a lot of overhead, which can be reduced. How often do you need ls or sudo while running your application.

If there's one application, there is no one to attack.

## How to

1. Download OS<sup>v</sup>

```
curl https://raw.githubusercontent.com/cloudius-systems/capstan/master/scripts/download | bash
```

2. Get struck by a x86 warning.

```
OSv only supports 64-bit x86. Exiting.
```
