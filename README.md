**Data Science and Openshift on the MOC**
--------------------------------------------------

Pull request accepted by RedHat into [main repo](https://github.com/AICoE/prometheus-anomaly-detector)  on 06/11/2020. 

**Metors**
----------

-   Michael Clifford, RedHat Inc.
-   Anand Sanmukhani, RedHat Inc.

**Team**
--------

- Yousif Khaireddin  		ykh@bu.edu
- Zhuofa (Marco) Chen   	zfchen@bu.edu
- Krishna Palle 		pallekc@bu.edu
- Fangya Xu			fangya@bu.edu
- Nihar Dwivedi		ndwivedi@bu.edu
- Ojasvi Jhamb		ojhamb@bu.edu

**Project Report and Final Video**
------------------------------------------

Click [here](https://github.com/BU-CLOUD-S20/Data-Science-and-Openshift-on-the-MOC/blob/master/Data%20Science%20and%20Openshift%20on%20the%20MOC_projectReport.pdf) for a comprehensive Project Report

Our GitHub repo containing our Prometheus Anomaly Detector can be found [here](https://github.com/pallekc91/prometheus-anomaly-detector)

The Final presentation video for our project can be found [here](https://youtu.be/dZmbSw0eiUg).

The slides for this presentation can be found [here](https://docs.google.com/presentation/d/1Ej-usqv6imtO18ZMMK_EqyoTBqt8eALq3WUn8Z00VRw/edit?usp=sharing).


**Goals**
---------

-   Understanding the current ML models (SARIMA and Prophet) and workings of [Prometheus Anomaly Detection
    (PAD)](https://github.com/AICoE/prometheus-anomaly-detector), an
    existing open-source project developed by the AI team at RedHat to
    analyze time-series data generated by cloud infrastructure
   
-   Developing and deploying a new ML model (LSTM) onto [DataHub](http://opendatahub.io/), a blueprint for building an AI application as a service platform on the OpenShift Container Platform.
 
-   Testing the workings of DataHub on the MOC and reporting any problems for future ramifications.


**Users/Personas**
------------------

-   The open-source community

-   MOC users that want to analyze time-series data generated by cloud
    infrastructure and send alerts for potential anomalies

-   Site Reliability Engineers that would like to monitor the health of
    their applications

**Scope and Features**
----------------------

-   Ensuring the deployment and functionality of DataHub on the MOC

-   Extension of the current Prometheus Anomaly Detection tool with a
    new model(s)

-   Exploring/reporting any issues and bugs we encounter along with the
    project for future ramifications

**Solution Concept**
--------------------

-   Installing OpenShift client and datahub on our locally for familiarization

-   Developing and testing PAD ML algorithms on JupiterHub

-   Testing the current models on JupyterHub

-   Building a simple LSTM model on JupyterHub

-   Experimenting with different architectures, optimizers, and layers in our model

-   Automating the tuning of our model

-   Comparing our model’s performance with that of the current deployment

-   Deploying our models onto the DataHub 

**Acceptance Criteria**
-----------------------

Developing at least one new ML model (LSTM) and having it monitor any metric while running on DataHub.

**Release Planning**
--------------------

1.  Project familiarization (02/05)

    1.  [MassOpenCloud (MOC)](https://massopen.cloud/opencloud-testbed/)

    2.  [OpenShift](http://learn.openshift.com/playgrounds/)

    3.  [Kubernetes](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

    4.  [OpenDataHub](http://opendatahub.io/)

    5.  [Prometheus Anomaly Detection
        (PAD)](https://github.com/AICoE/prometheus-anomaly-detector)

2.  Deploy DataHub onto MOC (03/01)

3.  Set up Data Hub on Openshift (03/15)

4.  Extend Prometheus with a new model(s) using Jupyter notebooks
    (04/15)

5.  Test the models on Prometheus using data provided by the mentor
    (05/01)

6.  Migrate built ML Algorithms and models onto DataHub (05/05)

**Links to Presentations / Class Lecture**
------------------------------------------

- [Sprint 1](https://docs.google.com/presentation/d/1e0QByoGbPIJOFgC1vTweVz-FojE6N5Hi5WudWHgsejo/edit?usp=sharing)
- [Sprint 2](https://docs.google.com/presentation/d/1dPSQh8Krn7tUywDNkpLJDfgINSiGLM3xvb2xzg5roNw/edit?usp=sharing)
- [Sprint 3](https://docs.google.com/presentation/d/1OzxMYc6w3MnnibcYa0E3kfOTpYQVMb-EOxH3OYkl-BI/edit?usp=sharing)
- [Sprint 4](https://docs.google.com/presentation/d/1QcR6yhtNkXyETeQn8KxbGmt9kHp_lsPEb5QBR0uTFgo/edit?usp=sharing)
- [MapReduce Talk](https://docs.google.com/presentation/d/1tAceg0GshV3ne7VhNXuVF9yplu7TTYOk8pgo5Ifo5ks/edit?usp=sharing)
- [Sprint 5](https://docs.google.com/presentation/d/179BS_06cfb-J9pX4MJTynOyuEnAQmtR92DuI7FiiFJU/edit?ts=5e9f4187#slide=id.g83e550b1fe_0_344)
