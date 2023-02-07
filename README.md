## Micronaut 3.8.3 Documentation

- [User Guide](https://docs.micronaut.io/3.8.3/guide/index.html)
- [API Reference](https://docs.micronaut.io/3.8.3/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/3.8.3/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/index.html)
---

## Handler

[AWS Lambda Handler](https://docs.aws.amazon.com/lambda/latest/dg/java-handler.html)

Handler: io.micronaut.function.aws.proxy.MicronautLambdaHandler


## Requisites

- [AWS Account](https://aws.amazon.com/free/)
- [CDK CLI](https://docs.aws.amazon.com/cdk/v2/guide/cli.html)
- [AWS CLI](https://aws.amazon.com/cli/)

## How to deploy

### Generate the deployable artifact

```
./gradlew :app:shadowJar
./gradlew test
```

### Deploy

The `infra/cdk.json` file tells the CDK Toolkit how to execute your app.

`cd infra`
`cdk synth` - emits the synthesized CloudFormation template
`cdk deploy` - deploy this stack to your default AWS account/region
`cd ..`

Other useful commands:

`cdk diff` - compare deployed stack with current state
`cdk docs`- open CDK documentation

### Cleanup

```
cd infra
cdk destroy
cd ..
```


- [Shadow Gradle Plugin](https://plugins.gradle.org/plugin/com.github.johnrengelman.shadow)
## Feature netflix-hystrix documentation

- [Micronaut Netflix Hystrix documentation](https://docs.micronaut.io/latest/guide/index.html#netflixHystrix)


## Feature graphql documentation

- [Micronaut GraphQL documentation](https://micronaut-projects.github.io/micronaut-graphql/latest/guide/index.html)


## Feature tracing-opentelemetry-http documentation

- [Micronaut OpenTelemetry HTTP documentation](http://localhost/micronaut-tracing/guide/index.html#opentelemetry)


## Feature amazon-api-gateway documentation

- [Micronaut Amazon API Gateway REST API documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#amazonApiGateway)

- [https://docs.aws.amazon.com/apigateway/](https://docs.aws.amazon.com/apigateway/)


## Feature lombok documentation

- [Micronaut Project Lombok documentation](https://docs.micronaut.io/latest/guide/index.html#lombok)

- [https://projectlombok.org/features/all](https://projectlombok.org/features/all)


## Feature rss documentation

- [Micronaut RSS Feed documentation](https://micronaut-projects.github.io/micronaut-rss/latest/guide/index.html#whatsNew)


## Feature management documentation

- [Micronaut Management documentation](https://docs.micronaut.io/latest/guide/index.html#management)


## Feature multi-tenancy documentation

- [Micronaut Multitenancy documentation](https://docs.micronaut.io/latest/guide/index.html#multitenancy)


## Feature aws-secrets-manager documentation

- [Micronaut AWS Secrets Manager documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/#distributedconfigurationsecretsmanager)

- [https://aws.amazon.com/secrets-manager/](https://aws.amazon.com/secrets-manager/)


## Feature elasticsearch documentation

- [Micronaut Elasticsearch Driver documentation](https://micronaut-projects.github.io/micronaut-elasticsearch/latest/guide/index.html)


## Feature tracing-opentelemetry-zipkin documentation

- [Micronaut OpenTelemetry Zipkin documentation](https://micronaut-projects.github.io/micronaut-tracing/latest/guide/#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature netflix-ribbon documentation

- [Micronaut Netflix Ribbon LoadBalancer documentation](https://docs.micronaut.io/latest/guide/index.html#netflixRibbon)


## Feature email-amazon-ses documentation

- [Micronaut SES Email documentation](https://micronaut-projects.github.io/micronaut-email/latest/guide/index.html#ses)

- [https://aws.amazon.com/ses/](https://aws.amazon.com/ses/)


## Feature reactor documentation

- [Micronaut Reactor documentation](https://micronaut-projects.github.io/micronaut-reactor/snapshot/guide/index.html)


## Feature openapi documentation

- [Micronaut OpenAPI Support documentation](https://micronaut-projects.github.io/micronaut-openapi/latest/guide/index.html)

- [https://www.openapis.org](https://www.openapis.org)


## Feature serialization-bson documentation

- [Micronaut Serialization BSON documentation](https://micronaut-projects.github.io/micronaut-serialization/latest/guide/)


## Feature aws-parameter-store documentation

- [Micronaut AWS Parameter Store Distributed Configuration documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#parametersStore)

- [https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)


## Feature aws-lambda documentation

- [Micronaut AWS Lambda Function documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#lambda)


## Feature cache-hazelcast documentation

- [Micronaut Hazelcast Cache documentation](https://micronaut-projects.github.io/micronaut-cache/latest/guide/index.html#hazelcast)

- [https://hazelcast.org/](https://hazelcast.org/)


## Feature aws-v2-sdk documentation

- [Micronaut AWS SDK 2.x documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/)

- [https://docs.aws.amazon.com/sdk-for-java/v2/developer-guide/welcome.html](https://docs.aws.amazon.com/sdk-for-java/v2/developer-guide/welcome.html)


## Feature problem-json documentation

- [Micronaut Problem JSON documentation](https://micronaut-projects.github.io/micronaut-problem-json/latest/guide/index.html)


## Feature security documentation

- [Micronaut Security documentation](https://micronaut-projects.github.io/micronaut-security/latest/guide/index.html)


## Feature tracing-opentelemetry-exporter-zipkin documentation

- [Micronaut OpenTelemetry Exporter Zipkin documentation](http://localhost/micronaut-tracing/guide/index.html#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature testcontainers documentation

- [https://www.testcontainers.org/](https://www.testcontainers.org/)


## Feature discovery-consul documentation

- [Micronaut Consul Service Discovery documentation](https://docs.micronaut.io/latest/guide/index.html#serviceDiscoveryConsul)

- [https://www.consul.io](https://www.consul.io)


## Feature security-oauth2 documentation

- [Micronaut Security OAuth 2.0 documentation](https://micronaut-projects.github.io/micronaut-security/latest/guide/index.html#oauth)


## Feature security-session documentation

- [Micronaut Security Session documentation](https://micronaut-projects.github.io/micronaut-security/latest/guide/index.html#session)


## Feature security-jwt documentation

- [Micronaut Security JWT documentation](https://micronaut-projects.github.io/micronaut-security/latest/guide/index.html)


## Feature dynamodb documentation

- [Micronaut Amazon DynamoDB documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/#dynamodb)

- [https://aws.amazon.com/dynamodb/](https://aws.amazon.com/dynamodb/)


## Feature tracing-opentelemetry-xray documentation

- [Micronaut OpenTelemetry XRay Tracing documentation](https://micronaut-projects.github.io/micronaut-tracing/latest/guide/#opentelemetry)

- [https://docs.aws.amazon.com/xray/latest/devguide/aws-xray.html](https://docs.aws.amazon.com/xray/latest/devguide/aws-xray.html)


## Feature localstack documentation

- [https://www.testcontainers.org/modules/localstack/](https://www.testcontainers.org/modules/localstack/)


## Feature email-sendgrid documentation

- [Micronaut Sendgrid Email documentation](https://micronaut-projects.github.io/micronaut-email/latest/guide/index.html#sendgrid)

- [https://docs.sendgrid.com/for-developers](https://docs.sendgrid.com/for-developers)


## Feature tracing-opentelemetry-annotations documentation

- [Micronaut OpenTelemetry Annotations documentation](https://micronaut-projects.github.io/micronaut-tracing/latest/guide/#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature tracing-opentelemetry-exporter-otlp documentation

- [Micronaut OpenTelemetry Exporter OTLP documentation](http://localhost/micronaut-tracing/guide/index.html#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature tracing-opentelemetry-exporter-logging documentation

- [Micronaut OpenTelemetry Exporter Logging documentation](http://localhost/micronaut-tracing/guide/index.html#opentelemetry)

- [https://opentelemetry.io](https://opentelemetry.io)


## Feature flyway documentation

- [Micronaut Flyway Database Migration documentation](https://micronaut-projects.github.io/micronaut-flyway/latest/guide/index.html)

- [https://flywaydb.org/](https://flywaydb.org/)


## Feature camunda-zeebe documentation

- [https://github.com/camunda-community-hub/micronaut-zeebe-client](https://github.com/camunda-community-hub/micronaut-zeebe-client)


## Feature kubernetes-reactor-client documentation

- [Micronaut Kubernetes Reactor Client documentation](https://micronaut-projects.github.io/micronaut-kubernetes/latest/guide/#kubernetes-client)

- [https://github.com/kubernetes-client/java/wiki](https://github.com/kubernetes-client/java/wiki)


## Feature aws-cdk documentation

- [https://docs.aws.amazon.com/cdk/v2/guide/home.html](https://docs.aws.amazon.com/cdk/v2/guide/home.html)


## Feature http-client documentation

- [Micronaut HTTP Client documentation](https://docs.micronaut.io/latest/guide/index.html#httpClient)


## Feature views-handlebars documentation

- [Micronaut Handlebars Views documentation](https://micronaut-projects.github.io/micronaut-views/latest/guide/index.html#handlebars)

- [https://jknack.github.io/handlebars.java/](https://jknack.github.io/handlebars.java/)


