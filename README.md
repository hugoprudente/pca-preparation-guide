# Prometheus Certified Associate (PCA)

![PCA Training Badge](images/Training_Badge_Prometheus_V2-2-300x300.png)


The objective of this repository is help you for taking the Prometheus Certified Associate (PCA) exam using online resources, especially using resources from Prometheus Official Documentation.

The references were selected for the Beta exam, and there are exclusive information for API objects and annotations. For more information, please see CNCF Curriculum.

Please, feel free to place a pull request whether something is not up-to-date, should be added or contains wrong information/reference.

# Exam

### Exam Cost: $250


# PCA Curriculum

The Prometheus Certified Associate (PCA) exam demonstrates an engineers foundational knowledge of observability and skills using Prometheus, the open source systems monitoring and alerting toolkit.


## Observability Concepts - 18%
* Metrics

  [Metrics Types](https://prometheus.io/docs/concepts/metric_types/)
  
  [Jobs and Instances](https://prometheus.io/docs/concepts/jobs_instances/)
  
* Understand logs and events

  [Query Log](https://prometheus.io/docs/guides/query-log/)

  [Logs and Metrics and Graphs, Oh My!](https://grafana.com/blog/2016/01/05/logs-and-metrics-and-graphs-oh-my/)

  [Pull doesn't scale - or does it?](https://prometheus.io/blog/2016/07/23/pull-does-not-scale-or-does-it/#prometheus-is-not-an-event-based-system)
  
* Trancing and Spans

  [Tracing vs Span by Logit](https://logit.io/blog/post/traces-vs-spans/)

  [Prometheus Tracing itself](https://prometheus.io/docs/prometheus/latest/configuration/configuration/#tracing_config)

  [A beginners guide to distributed tracing by Grafana](https://grafana.com/blog/2021/01/25/a-beginners-guide-to-distributed-tracing-and-how-it-can-increase-an-applications-performance/)

* Push vs Pull

  [Pull vs Push FAQ](https://prometheus.io/docs/introduction/faq/#why-do-you-pull-rather-than-push)

  [Pull doesn't scale - or does it?](https://prometheus.io/blog/2016/07/23/pull-does-not-scale-or-does-it/)

  [Pushgateway](https://prometheus.io/docs/instrumenting/pushing/)
  
* Service Discovery

  [Http Service Discovery](https://prometheus.io/docs/prometheus/latest/http_sd/#writing-http-service-discovery)
  
  [File based Service Discovery](https://prometheus.io/docs/guides/file-sd/#use-file-based-service-discovery-to-discover-scrape-targets)
  
* Basics of SLOs, SLAs, and SLIs

  SLO - [SRE Book](https://sre.google/sre-book/service-level-objectives/)
  
  SLI & SLA - [Fundamentals 2021](https://cloud.google.com/blog/products/devops-sre/sre-fundamentals-sli-vs-slo-vs-sla)  

## Prometheus Fundamentals - 20%

* System Architecture

  [Overview](https://prometheus.io/docs/introduction/overview/)

* Configuration and Scraping

  [Configuration](https://prometheus.io/docs/prometheus/latest/configuration/configuration/#scrape_config)

* Understanding Prometheus Limitations

  [LTS Limitations](https://prometheus.io/docs/introduction/release-cycle/#limitations-of-lts-support)

  [Storage Limitation](https://prometheus.io/docs/prometheus/latest/storage/#limitations)

* Data Model and Labels

  [Data Model](https://prometheus.io/docs/concepts/data_model/)

  [Best Practices Naming and Labels](https://prometheus.io/docs/practices/naming/)

* Exposition Format

  [Exposition Format](https://prometheus.io/docs/instrumenting/exposition_formats/#exposition-formats)


## PromQL - 28%

* Selecting Data

  [Basic Query](https://prometheus.io/docs/prometheus/latest/querying/basics/)

* Rates and Derivates

  [Functions](https://prometheus.io/docs/prometheus/latest/querying/functions/)

* Aggregating over time

  [Operators](https://prometheus.io/docs/prometheus/latest/querying/operators/#aggregation-operators)

* Aggregation over dimensions

  [Operators](https://prometheus.io/docs/prometheus/latest/querying/operators/#aggregation-operators)

* Binary Operators

  [Binary Operators](https://prometheus.io/docs/prometheus/latest/querying/operators/#binary-operators)

* Histograms

  [Best Practices Histograms and Summaries](https://prometheus.io/docs/practices/histograms/)

* Timestamp Metrics

  [Timestamp()](https://prometheus.io/docs/prometheus/latest/querying/functions/#timestamp)

  [Timestamp Instrumentation](https://prometheus.io/docs/practices/instrumentation/#timestamps-not-time-since)


## Instrumentation and Exporters - 16%
* Client Libraries
* Instrumentation
* Exporters
* Structuring and naming metrics


## Alerting & Dashboarding - 18%
* Dashboarding basics
* Configuring Alerting rules
* Understand and Use Alertmanager
* Alerting basics (when, what, and why)


# PCA Preparation Courses

* [Descomplicando o Prometheus (Portuguese)](https://www.linuxtips.io/products/descomplicando-o-prometheus)
* [PromQL Cheat Sheet](https://promlabs.com/promql-cheat-sheet/)
* [Introduction to Prometheus - free](https://training.promlabs.com/training/introduction-to-prometheus)
* [Prometheus Up and Running - paid](https://www.oreilly.com/library/view/prometheus-up/9781492034131/)

