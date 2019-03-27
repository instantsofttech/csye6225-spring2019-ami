# Trigger CircleCI Build Using API

Doc: https://circleci.com/docs/2.0/api-job-trigger/

```
curl -u TOKEN \
     -d build_parameters[CIRCLE_JOB]=build \
     https://circleci.com/api/v1.1/project/github/punith101/csye6225-spring2019-ami/tree/master
```
