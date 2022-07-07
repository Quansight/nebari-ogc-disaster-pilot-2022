# OGC Disaster Pilot 2022: Cloud processing of spatial data using Nebari

Cloud processing of spatial data has incredible promise for rapid, scalable insights and geographic awareness, particularly in emergency and disaster situations. The only problem: it's still very difficult to deploy, tricky to limit cost, and complicated to interchange different cloud platforms. 

The Open Geospatial Consortium (OGC) and Quansight, building upon the Disaster Pilot initiatives is running a virtual workshop on July 7-8, 2022 to show how Nebari can be used to automate the cloud deployment and maintainance of a spatial data science platform on the cloud of your choice.

## Getting started:

### Register

1. If you don't have a GitHub profile, please create one. 
   - See the [GitHub docs](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) for more details.
2. Register via this [OGC Google Form](https://forms.gle/9dVzraCVKPvr6bPGA) before July 7th.
3. Register yourself on [this OGC Gitter channel](https://gitter.im/ogc-developer/qhub-nebari).


### Logging into a Quansight pre-configured QHub instance

1. Login to QHub for the first time at [esip-ogc.nebari.dev](https://esip-ogc.nebari.dev/]).
   - For more details on how to login, please see the [QHub Getting Started docs](https://docs.qhub.dev/en/latest/source/user_guide/getting_started.html).

2. If you missed the registration deadline, please reach out to @iameskild on the [Gitter channel](https://gitter.im/ogc-developer/qhub-nebari) for access.


### Deploying your own QHub instance

If you plan to deploy your own QHub instance in the cloud, you will need to have set up:

1. an account for cloud services (with admin-level permissions) from either [Amazon Web Services (AWS)](https://portal.aws.amazon.com/billing/signup) or [Google Cloud Platform (GCP)](https://console.cloud.google.com/); and
2. a DNS registry account from, e.g., [CloudFlare](https://dash.cloudflare.com/sign-up). Other DNS registries (e.g., [Hover](http://www.hover.com/), [GoDaddy](https://www.godaddy.com), etc.) are supported but may lack some auto-provision features built for CloudFlare.

## Outline:

1. [Introduction - What is Nebari and why should I use it?](./01_introduction.ipynb)
2. Exploration of the features and tools available in Nebari:
   1. [Nebari 101](./02a_nebari_101.ipynb)
   2. [Using Dask on Nebari](./02b_using_dask_on_nebari.ipynb)
3. Example Spatial Workflows
   1. [Bathymetric Explorer](./03a_bathymetric_explorer.ipynb)
   2. [Visualizing Gridded Data (WaveWatch)](./03b_visualize_wavewatch.ipynb)
   3. [Exploring the National Water Model](./03c_exploring_national_water_model.ipynb)
   4. [Analyzing Landsat 8 Collection 2 Level 2 Data](./03d_analyzing_landsat-8-c2-l2.ipynb)
4. Useful Cloud Tools
   1. [Running and scheduling batch workflows with KBatch](./04a_submit_batch_job.ipynb)
   2. [Creating and sharing an interactive application](https://www.nebari.dev/tutorials/creating-cds-dashboard)
   3. [Creating and using catalogs with Intake](./04c_data_catalogs_with_intake.ipynb)
5. [Deploy your own Nebari](./05_deploy_nebari.ipynb)
   1. Configuration & Installation
   2. Estimating the cost of your deployment
   3. Managing your users
6. BYOD - Bring Your Own Data (Examples Provided)
7. Show & Tell

## Schedule:

*Note: All times in EDT*

- July 7th 
  - 10:00am-12:00pm Using Nebari for Spatial Workflows (Sections 0-3)
  - 12:30pm-02:30pm Useful Cloud Tools (Sections 4)
  - 02:45pm-04:30pm Install & Manage Nebari (Section 5)
- July 8th
  - 10:00am-12:00pm BYOD/Independant Work (see help section)
  - 01:00pm-03:00pm Show & Tell + Q&A

## Getting Help During the Sprint.

Use the Gitter channel: [`ogc-developer/qhub-nebari`](https://gitter.im/ogc-developer/qhub-nebari).
