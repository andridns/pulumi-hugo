---
title: Static Website on Azure
meta_desc: The Static Website blueprint makes it easy to deploy a static website on Azure with Pulumi, Azure Blob Storage, and Azure CDN.
layout: template
cloud:
    name: Microsoft Azure
    slug: azure
---

{{% chooser language "typescript,python,go,csharp,yaml" / %}}

{{% choosable language typescript %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-azure-typescript
```

{{% /choosable %}}

{{% choosable language python %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-azure-python
```

{{% /choosable %}}

{{% choosable language go %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-azure-go
```

{{% /choosable %}}

{{% choosable language csharp %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-azure-csharp
```

{{% /choosable %}}

{{% choosable language yaml %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-azure-yaml
```

{{% /choosable %}}
