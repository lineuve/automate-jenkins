# automate-jenkins

```sh
git clone https://github.com/dihogoteixeira/automate-jenkins.git
cd automate-jenkins
```

Change value in variable `dockerhub_user` on `setup-and-run.sh` local file

```yaml
.
├── Dockerfile
├── README.md
├── config
│   ├── authentication.properties
│   ├── credentials.properties
│   ├── globals.properties
│   ├── initial-jobs.properties
│   └── tools.properties
├── groovy
│   ├── credentials.groovy
│   ├── globalconfig.groovy
│   ├── helpers.groovy
│   ├── initialjobs.groovy
│   ├── java.groovy
│   ├── maven.groovy
│   ├── scriptSecurity.groovy
│   └── securityOwnDB.groovy
├── plugins.txt
└── setup-and-run.sh
```

Just run local `setup-and-run.sh` script:

```sh
sh setup-and-run.sh
```

url: http://localhost:8080

```yaml
user1: jenkins
user2: hudson
passwd: Br@s1l2021
```

Instaled plugins in `plugins.txt`

```yaml
workflow-api:2.26
jira:2.5
ssh-agent:1.15
dashboard-view:2.9.11
pipeline-model-extensions:1.2.7
git-server:1.7
blueocean-rest-impl:1.4.2
timestamper:1.8.9
blueocean-config:1.4.2
external-monitor-job:1.7
cobertura:1.12
workflow-support:2.18
build-name-setter:1.6.9
gitlab-hook:1.4.2
saferestart:0.3
build-pipeline-plugin:1.5.8
jenkins-design-language:1.4.2
jdk-tool:1.1
active-directory:2.6
resource-disposer:0.8
ansible:1.0
blueocean-git-pipeline:1.4.2
parameterized-trigger:2.35.2
handy-uri-templates-2-api:2.1.6-1.0
blueocean-dashboard:1.4.2
ldap:1.20
subversion:2.10.5
config-file-provider:2.18
gradle:1.28
sse-gateway:1.15
publish-over-ssh:1.19.1
blueocean-pipeline-scm-api:1.4.2
pam-auth:1.3
jquery:1.12.4-0
docker-commons:1.11
docker-workflow:1.15.1
blueocean-rest:1.4.2
apache-httpcomponents-client-4-api:4.5.3-2.1
command-launcher:1.2
antisamy-markup-formatter:1.5
workflow-cps-global-lib:2.9
artifactdeployer:1.2
webhook-step:1.3
github:1.29.0
workflow-job:2.17
jackson2-api:2.8.11.1
token-macro:2.4
ruby-runtime:0.12
pipeline-stage-tags-metadata:1.2.7
ant:1.8
gitlab-plugin:1.5.5
git-client:2.7.1
gitlab-merge-request-jenkins:2.0.0
windows-slaves:1.3.1
workflow-step-api:2.14
email-ext:2.62
checkstyle:3.50
nodejs:1.2.5
pipeline-stage-view:2.10
branch-api:2.0.18
mailer:1.21
blueocean:1.4.2
momentjs:1.1.1
conditional-buildstep:1.3.6
scm-api:2.2.6
cloudbees-bitbucket-branch-source:2.2.10
blueocean-i18n:1.4.2
blueocean-personalization:1.4.2
script-security:1.43
pipeline-rest-api:2.10
blueocean-events:1.4.2
javadoc:1.4
handlebars:1.1.1
envinject-api:1.5
build-timeout:1.19
embeddable-build-status:1.9
ssh-slaves:1.26
display-url-api:2.2.0
workflow-scm-step:2.6
authentication-tokens:1.3
jenkins-multijob-plugin:1.29
credentials-binding:1.16
workflow-basic-steps:2.6
mercurial:2.3
blueocean-pipeline-api-impl:1.4.2
github-api:1.90
pipeline-graph-analysis:1.6
bouncycastle-api:2.16.2
jquery-detached:1.2.1
blueocean-autofavorite:1.2.2
copyartifact:1.39.1
analysis-core:1.95
variant:1.1
ssh-credentials:1.13
workflow-cps:2.45
pipeline-model-declarative-agent:1.1.1
workflow-multibranch:2.17
envinject:2.1.5
git:3.8.0
structs:1.14
pipeline-utility-steps:2.0.2
blueocean-core-js:1.4.2
blueocean-github-pipeline:1.4.2
favorite:2.3.1
pipeline-model-api:1.2.7
blueocean-display-url:2.2.0
sonar-quality-gates:1.3.0
rebuild:1.28
matrix-auth:2.2
blueocean-pipeline-editor:1.4.2
matrix-project:1.12
toolenv:1.1
publish-over:0.21
pipeline-github-lib:1.0
workflow-aggregator:2.5
blueocean-jwt:1.4.2
ws-cleanup:0.34
credentials:2.1.16
blueocean-web:1.4.2
pipeline-build-step:2.7
pipeline-milestone-step:1.3.1
plain-credentials:1.4
maven-plugin:3.1.2
blueocean-bitbucket-pipeline:1.4.2
pubsub-light:1.12
blueocean-jira:1.4.2
durable-task:1.22
jsch:0.1.54.2
htmlpublisher:1.15
pipeline-stage-step:2.3
mapdb-api:1.0.9.0
ssh:2.5
ace-editor:1.1
github-branch-source:2.3.3
cloudbees-folder:6.4
role-strategy:2.7.0
run-condition:1.0
junit:1.24
pipeline-model-definition:1.2.7
workflow-durable-task-step:2.19
pipeline-input-step:2.8
built-on-column:1.1
blueocean-commons:1.4.2
thinBackup:1.9
kubernetes:1.5
```