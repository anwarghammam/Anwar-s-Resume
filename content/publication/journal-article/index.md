---
title: "Dynamic Software Containers Workload Balancing via Many-Objective Search"
authors:
- admin
- Thiago Ferreira
- Wajdi Aljedaani
- Marouane Kessentini


date: "2022-12-31T00:00:00Z"
doi: "10.1109/TSC.2023.3237755"

# Schedule page publish date (NOT publication's date).
publishDate: "2023/2/17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE TRANSACTIONS ON SERVICES COMPUTING"
publication_short: ""

abstract: "Software containers are becoming the new state of the art in the industry as they are extensively used to deploy systems. Indeed, the use of containers enables better modularity, reusability, and portability compared to other technologies. As the complexity of software systems is dramatically increasing, it is critical to enable optimal usage of the needed resources to execute them such as memory and CPU. Thus, different scheduling strategies are proposed to select the most suitable nodes to execute a set of containers. For instance, the default strategy in the Docker Swarm kit scheduling framework is based on an equal distribution of the containers between nodes independent of their sizes and consumed resources. However, balancing the containers’ workload is a complex problem due to the conflicting objectives of minimizing the number of selected nodes, minimizing the number of containers per node, the number of changes compared to the original schedule, and the coupling between containers allocated to different nodes. To deal with those conflicting scheduling objectives, we propose a scheduler based on a many-objective optimization approach for scheduling the execution of containers between multiple nodes. The proposed approach aims at finding the best allocation for containers in nodes that leads to efficient utilization of resources. To evaluate our approach, we compared the performance of multiple many and multi-objective techniques based on NSGA-II, NSGA-III, and IBEA algorithms using 48 Docker-related systems and the results show that NSGA-III outperforms the other algorithms in quality attributes as well as in CPU, Memory and Network usage."


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
# url: ""
url_pdf: https://www.researchgate.net/profile/Wajdi-Aljedaani-2/publication/368619937_Dynamic_Software_Containers_Workload_Balancing_Via_Many-Objective_Search/links/6411b12f66f8522c38a87abf/Dynamic-Software-Containers-Workload-Balancing-Via-Many-Objective-Search.pdf
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: 'https://anwarghammam.github.io/ContainersSchedulingWebSite/'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false



# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


