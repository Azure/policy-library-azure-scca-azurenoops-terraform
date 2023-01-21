# Microsoft Azure SCCA Mission Enclaves using the Azure NoOps Accelerator for Terraform
This library, provides prescriptive Terraform policies that can be used to establish secure Terraform configuration for Microsoft Azure. The policies that are contained in this library are based on the [Secure Cloud Computing Architecture (SCCA) Functional Requirements Document (FRD)](https://rmf.org/wp-content/uploads/2018/05/SCCA_FRD_v2-9.pdf). Terraform Cloud/Enterprise users can use the policies in this library to establish a foundational level of security for the services that they are adopting in Microsoft Azure.

The SCCA has four components:

- [Boundary Cloud Access Point (BCAP)](#BCAP-Controls)
- [Virtual Datacenter Security Stack (VDSS)](#VDSS-Controls)
- [Virtual Datacenter Managed Services (VDMS)](#VDMS-Controls)
- [Trusted Cloud Credential Manager (TCCM)](#TCCM-Controls)

> **NOTE:**
>
> This Policy Library is not an exhaustive list of all of possible security configurations and architecture that is available in Microsoft Azure. If you have questions, comments, or have identified ways for us to improve this library, please create [a new GitHub issue](https://github.com/Azure/policy-library-azure-scca-azurenoops-terraform/issues/new/choose).
>
> Alternatively, We welcome any contributions that improve the quality of this library! To learn more about contributing and suggesting changes to this library, refer to the [contributing guide](https://github.com/Azure/policy-library-azure-scca-azurenoops-terraform/blob/main/CONTRIBUTING.md).

---

## Policies included

---

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
