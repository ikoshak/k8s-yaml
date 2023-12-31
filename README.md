| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| app.yaml | Create pod deployment of nginx with name 'ngx_app', label 'app: nginx', 'run:nginx' | create pod nginx | [app.yaml](/yaml/app.yaml) |
| app-livenessProbe.yaml | Create pod deployment of nginx with livenessprobe and set resource limits for nginx application | pod  with livenessProbe | [app-livenessProbe.yaml](/yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | Create pod deployment of nginx with readinessprobe and livenessprobe and set resource limits for nginx application | pod  with livenessProbe and readinessprob | [app-readinessProbe.yaml](/yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | Create pod deployment of nginx with livenessprobe, set resource quotas for nginx application and add volummeMounts with volume name 'data' | pod with volumeMounts | [app-volumeMounts.yaml](/yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | Create cronjob which will run every 5 minute bash echo message 'hello world', container have to be alpine | cretate cronjob | [app-cronjob.yaml](/yaml/app-cronjob.yaml) |
| app-job.yaml | Create job which will copy data from google cloud storage to mount path '/data/input' | create Job | [app-job.yaml](/yaml/app-job.yaml) |
| app-multicontainer.yaml | Create mupticontainer deployment where first container is nginx, second is debian, nginx container have volumeMount 'html' with path '/usr/share/nginx/html', debian have vilumeMount 'html' with path 'html', and running bash command which write date and time in /html/index.html | create multicontainer | [app-multicontainer.yaml](/yaml/app-multicontainer.yaml) |
| app-resources.yaml | Create pod deployment of nginx with readinessprobe and livenessprobe and set resource limits for nginx application | create resources | [app-resources.yaml](/yaml/app-resources.yaml) |
| app-secret-env.yaml | Create pod deployment of couchdb with environment variables 'SECRET_USERNAME' and 'SECRET_PASSWORD' | create secret-env | [app-secret-env.yaml](/yaml/app-secret-env.yaml) |
