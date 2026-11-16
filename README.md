# Private outbound connectivity for Azure Database for MySQL flexible server (preview)

Private outbound connectivity lets an Azure Database for MySQL flexible server instance connect privately to resources in a virtual network that you choose. Use it for data-in replication from a MySQL source server that isn't reachable from the internet, such as a server on an Azure virtual machine, in an on-premises datacenter, or in another cloud.

This repository contains the preview documentation for the feature.

> [!IMPORTANT]
> Private outbound connectivity is in preview. To use it, contact your Microsoft account team to enable it for your subscription. Previews are provided without a service-level agreement and aren't recommended for production workloads. For more information, see [Supplemental Terms of Use for Microsoft Azure Previews](https://azure.microsoft.com/support/legal/preview-supplemental-terms/).

## Documentation

The documentation is a single article, [Private outbound connectivity for Azure Database for MySQL flexible server (preview)](concepts-networking-private-outbound-connectivity.md). It has two parts:

| Part | What it covers |
| --- | --- |
| [About private outbound connectivity](concepts-networking-private-outbound-connectivity.md#about-private-outbound-connectivity) | How the feature works, use cases, requirements, and supported features and limitations. |
| [Configure private outbound connectivity in the Azure portal](concepts-networking-private-outbound-connectivity.md#configure-private-outbound-connectivity-in-the-azure-portal) | Setup for [a new server](concepts-networking-private-outbound-connectivity.md#for-a-new-server) or [an existing server](concepts-networking-private-outbound-connectivity.md#for-an-existing-server), and [data-in replication](concepts-networking-private-outbound-connectivity.md#set-up-data-in-replication) over the connection. |

## Repository layout

```text
README.md
concepts-networking-private-outbound-connectivity.md
media/
└── concepts-networking-private-outbound-connectivity/
```

Images are in a `media` subfolder named after the article, the same convention that Microsoft Learn uses for Azure Database for MySQL articles.

## Feedback

To share feedback about the preview or this article, contact your Microsoft account team.
