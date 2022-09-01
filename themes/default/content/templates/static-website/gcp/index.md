---
title: Static Website on Google Cloud
meta_desc: The Static Website blueprint makes it easy to deploy a static website on Google Cloud with Pulumi, Google Cloud Storage, and Google Cloud CDN.
layout: template
cloud:
    name: Google Cloud Platform
    slug: gcp
---

{{% chooser language "typescript,python,go,csharp,yaml" / %}}

{{% choosable language typescript %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-gcp-typescript
```

{{% /choosable %}}

{{% choosable language python %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-gcp-python
```

{{% /choosable %}}

{{% choosable language go %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-gcp-go
```

{{% /choosable %}}

{{% choosable language csharp %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-gcp-csharp
```

{{% /choosable %}}

{{% choosable language yaml %}}

```bash
$ mkdir my-site && cd my-site
$ pulumi new static-website-gcp-yaml
```

{{% /choosable %}}
