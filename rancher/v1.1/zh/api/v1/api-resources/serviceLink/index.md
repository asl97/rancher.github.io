---
title: API
layout: rancher-api-v1-default-v1.1
version: v1.1
lang: zh
apiVersion: v1
---

## serviceLink



### Resource Fields

#### Writeable Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
name | string | Optional | - | - | 
serviceId | [service]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/{{page.apiVersion}}/api-resources/service/) | Yes | - | - | The unique identifier of the associated service


#### Read Only Fields

Field | Type   | Notes
---|---|---
uuid | string  | The universally unique identifier for the serviceLink. This will always be unique across Rancher installations.


<br>
