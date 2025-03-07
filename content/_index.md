---
title: My Site
toc: false
---

{{% details title="hidden" closed="true" %}}
```
this is a unformatted code block
```

```yaml
this is a formatted code block
```
{{% /details %}}

{{% details title="filetree" closed="true" %}}
  {{< filetree/container >}}
    {{< filetree/folder name="dir1" >}}
      {{< filetree/file name="file1" >}}
      {{< filetree/file name="file2" >}}
    {{< /filetree/folder >}}
  {{< /filetree/container >}}
{{% /details %}}
