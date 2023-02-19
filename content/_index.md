+++
title = "Dotfair"
[data]
thumbnail = "images/dotfair.png"
featureImage = "images/dotfair.png"
shareImage = "images/dotfair.png"
baseChartOn = 3
colors = ["#627c62", "#11819b", "#ef7f1a", "#4e1154"]
columnTitles = ["Section", "Status", "Author"]
description = "Dotfair is a tool that helps you to deploy your infrastructure in a more sustainable way."
+++
{{< block "grid-2" >}}
{{< column >}}

# Are you ready for **greener deployments**?

Dotfair is a tool that **helps you to deploy your infrastructure in a more sustainable way**. It is a command line tool that **uses the Terraform state and plan** to generate a report that shows you **the environmental impact of your deployment**.

**Want to try it out?** You can **run it with Docker**:
  
```bash
docker run -it --rm -v <terraform_folder>:/app/terraform \
ghcr.io/dotfair-opensource/dotfair:latest ./dotfair run
```


{{< tip "warning" >}}
**Warning:** This is a work in progress. The project is not yet ready for production use.

At the moment, dotfair works only with AWS instances. To know more about what is planned, check the [roadmap](roadmap/).
{{< /tip >}}

{{< button "https://github.com/dotfair-opensource/dotfair" "See on GitHub" "mb-1" >}}
{{< button "https://calendly.com/mariusjoffre/30min" "Book a demo"  "mb-1" >}}
{{< /column >}}

{{< column >}}
![diy](images/demo.gif)
{{< /column >}}
{{< /block >}}