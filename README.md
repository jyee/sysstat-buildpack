# Heroku sysstat buildpack

This Heroku buildpack will install the libsensors4 and sysstat packages in your dyno.

Using the Heroku CLI tool:

```
heroku buildpacks:add https://github.com/jyee/sysstat-buildpack.git
```

p.s. - I built this as a step towards building an updated [Heroku Datadog buildpack](https://github.com/Datadog/heroku-buildpack-datadog)
