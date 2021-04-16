---
title: "Delete a Task from Project"
type: docs
url: /delete-a-task-from-project/
weight: 30
---

## **Introduction**
This example allows you to delete a project task with all references to it and rebuilds tasks tree, using Aspose.Tasks Cloud. Aspose.Tasks Cloud is a REST API which can be used with any language: .NET, Java, PHP, Ruby, Rails, Python, jQuery and many more.
## **API Information**

|**API**|**Type**|**Description**|**Resource Link**|
| :- | :- | :- | :- |
|/tasks/{name}/tasks/{taskUid}|DELETE|Deletes a project task with all references to it and rebuilds tasks tree|[DeleteTask](https://apireference.aspose.cloud/tasks/#/TasksTask/DeleteTask)|
### **cURL Example**
{{< tabs tabTotal="2" tabID="1" tabName1="Request" tabName2="Response" >}}

{{< tab tabNum="1" >}}

```java

curl -X DELETE "https://api.aspose.cloud/v3.0/tasks/Project2016.mpp/tasks/4" -H "accept: application/json" -H "x-aspose-client: Containerize.Swagger"

```

{{< /tab >}}

{{< tab tabNum="2" >}}

```java

{
  "Code": "200",
  "Status": "OK"
}

```

{{< /tab >}}

{{< /tabs >}}
## **SDKs**
The Aspose.Tasks Cloud SDKs can be downloaded from the following page: [Available SDKs](/tasks/available-sdks/)
### **SDK Examples**
{{< tabs tabTotal="5" tabID="4" tabName1="C#" tabName2="PHP" tabName3="Python" tabName4="Node.js" tabName5="Go" >}}

{{< tab tabNum="1" >}}

{{< gist "aspose-cloud" "923dc267b52f915c12ea7272b2db6152" "Examples-DeleteTask.cs" >}}

{{< /tab >}}


{{< tab tabNum="2" >}}

{{< gist "aspose-cloud" "fccd709b575ee217d7c150a67339fcbc" "Example-deleteTask.php" >}}

{{< /tab >}}


{{< tab tabNum="3" >}}

{{< gist "aspose-cloud" "89a5b1c8d4e51289b5a5eac016584c4e" >}}

{{< /tab >}}

{{< tab tabNum="4" >}}

{{< gist "aspose-cloud" "f25ce3e18e830c4795cd0ee66f7cc2ce" >}}

{{< /tab >}}

{{< tab tabNum="5" >}}

{{< gist "aspose-cloud" "07b528dc09cd57c1da0fb9affb1417f7" "Examples-DeleteTask.go" >}}

{{< /tab >}}

{{< /tabs >}}
