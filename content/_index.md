---
title: My Site
toc: false
---

{{% details title="filetree" closed="true" %}}
  {{< filetree/container >}}
    {{< filetree/folder name="dir1" >}}
      {{< filetree/file name="file1" >}}
      {{< filetree/file name="file2" >}}
    {{< /filetree/folder >}}
  {{< /filetree/container >}}
{{% /details %}}

{{< filetree/container >}}
  {{< filetree/folder name="dir1" >}}
    {{< filetree/file name="file1" >}}
    {{< filetree/file name="file2" >}}
  {{< /filetree/folder >}}
{{< /filetree/container >}}
