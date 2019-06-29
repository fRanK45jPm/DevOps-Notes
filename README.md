## Welcome to JohnPM DevOps Page, I write anything that can be helpful in coming days, weeks, months or years.

You can use the [editor on GitHub](https://github.com/johnpm45/DevOps-Notes/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.


**Docker Command CheatSheets**


```
//// Download image and run an application in the container.
docker run --rm mcr.microsoft.com/dotnet/core/samples

//// Download image and run a sime web application on the container, after the container is started navigate to http://localhost:8000
docker run -it --rm -p 8000:80 --name aspnetcore_sample mcr.microsoft.com/dotnet/core/samples:aspnetapp 
 
//// Run command from on container using the tag  
docker run --rm -it {image}:{tag}
 
//// Run command from the container using the latest tag  
docker run --rm -it {image}`
```



### >> Azure DevOps - Docker / AKS

* [Visual Studio Setup](https://github.com/johnpm45/DevOps-Notes/wiki/Visual-Studio-Setup)

* [Docker Setup](https://github.com/johnpm45/DevOps-Notes/wiki/a.-Setup-Docker-and-Automate-Deployment-Windows)

* [Public Docker Registry](https://github.com/johnpm45/DevOps-Notes/wiki/b.-Uploading-Images-to-public-docker-registry)

* [Orchestrating Deployment](https://github.com/johnpm45/DevOps-Notes/wiki/c.-Orchestrating-docker-deployment-using-Azure-Kubernetes-Service)

* [Uploading Image to Azure Container Registry](https://github.com/johnpm45/DevOps-Notes/wiki/d.-Uploading-image-to-Azure-container-registry)

### >> Azure ARM

### >> Team City

### >> Octopus Deploy

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/johnpm45/DevOps-Notes/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
