---
title: "Efficient Management of Containers for Software Defined Vehicles"
authors:
- admin
- Rania khalsi
- Marouane Kessentini
- Foyzul Hassan


date: "2024-05-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Software Engineering and Methodology"
publication_short: ""

abstract: "Containerization technology, such as Docker, is gaining in popularity in newly established software-defined vehicle architectures (SDVA). However, executing those containers can quickly become computationally expensive in constrained environments, given the limited CPU, memory, and energy resources in the Electric Control Units (ECU) of SDVA. Consequently, the efficient management of these containers is crucial for enabling the on-demand usage of the applications in the vehicle based on the available resources while considering several constraints and priorities, including failure tolerance, security, safety, and comfort.
In this paper, we propose a dynamic software container management approach for constrained environments such as embedded devices/ECUs in SDVA within smart cars. To address the conflicting objectives and constraints within the vehicle, we design a novel search-based approach based on multi-objective optimization. This approach facilitates the allocation, movement, or suspension of containers between ECUs in the cluster. Collaborating with our industry partner, Ford Motor Company, we evaluate our approach using different real-world software-defined scenarios. These scenarios involve using heterogeneous clusters of ECU devices in vehicles based on real-world software containers and use-case studies from the automotive industry. The experimental results demonstrate that our scheduler outperforms existing scheduling algorithms, including the default Docker scheduler -Spread- commonly used in automotive applications. Our proposed scheduler exhibits superior performance in terms of energy and resource cost efficiency. Specifically, it achieves a 35% reduction in energy consumption in power-saving mode compared to the scheduler employed by Ford Motor Company. Additionally, our scheduler effectively distributes workload among the ECUs in the cluster, minimizing resource usage, and dynamically adjusts to the real-time requirements and constraints of the car environment. This work will serve as a fundamental building block in the automotive industry to efficiently manage software containers in smart vehicles considering constraints and priorities in the real world."


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
# url: ""
url_pdf: https://dl.acm.org/doi/pdf/10.1145/3672461
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: 'https://sites.google.com/view/containerscheduling/'
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


