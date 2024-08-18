# `kubectl-ai` yaml prompt

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| --- | --- | --- | --- |
| app.yaml | Create deploymet application app-demo with port 8080 | | [app.yaml](yaml/app.yaml) |
| app-livenessProbe.yaml | Create deploymet application app-demo and add livenessProbe | | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | Create deploymet application app-demo and add readinessProbe | | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | Create deploymet application app-demo,open port 8080, add volume data and mount it | | [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | Create cronjob every 5 minutes print Hello World | | [app-cronjob.yaml](yaml/app-cronjob.yaml) |
| app-job.yaml | Create job append  date time timestamp to file on mounted volume | | [app-job.yaml](yaml/app-job.yaml) |
| app-multicontainer.yaml | Create multiconteiner app with containers nginx and debian | | [app-multicontainer.yaml](yaml/app-multicontainer.yaml) |
| app-resources.yaml | Create app with limit resources | | [app-resources.yaml](yaml/app-resources.yaml) |
| app-secret-env.yaml | Create app with secret | | [app-secret-env.yaml](yaml/app-secret-env.yaml) |

