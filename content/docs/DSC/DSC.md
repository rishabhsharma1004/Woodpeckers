# **DSC**

Management platform provided by the Microsoft, also known as a PowerShell feature. DSC provides a set of PowerShell language extensions. The main idea is to provide a method for maintaining consistent configuration across computers or devices. Using central DSC server, projects can store OS configuration, configuration resources and use them several times across builds. Mainly used for setting up virtualized environments, deployments and management of systems.


Woodpeckers team is supplying a complete solution for the business partners who would like to enhance their DSC practice. 
The offer consists of:
- HTTP DSC Pull Server for Configurations and LCM agent registration. Pull Server also has the capability to store agents' reports, which can be used in further processing.
- DSC Resources space, hosted as an SMB file share for storing custom modules and items.

Each business partner may count on a dedicated space with the above components.



## **Environments**

- **DSC Test** (dsctest.emea.roche.com:*Dedicated port*)

    - Configuration: (dsctestconfiguration.emea.roche.com:*Dedicated port*)
    - Reporting: (dsctestreporting.emea.roche.com:*Dedicated port*)
    - Resources: (dsctestresources.emea.roche.com\\*Dedicated file share*)

- **DSC Production** (dscprod.emea.roche.com:*Dedicated port*)

    - Configuration: (dscprodconfiguration.emea.roche.com:*Dedicated port*)
    - Reporting: (dscprodreporting.emea.roche.com:*Dedicated port*)
    - Resources: (dscprodresources.emea.roche.com\\*Dedicated file share*)


## **Reach out to us for support**

- [Service Request](https://roche.service-now.com/rose?id=nr_sc_cat_item&sys_id=efcfc1d2ebfb23046a4e0dffab887e72)

- [Raise an Issue](https://roche.service-now.com/rose?id=nr_sc_cat_item&sys_id=2aeff74b4f7b5704c93809de0310c72b)
