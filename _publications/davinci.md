---
title: "DaVinci Sketch: A Versatile Sketch for Efficient and Comprehensive Set Measurements"
collection: publications
category: conferences
header:
    teaser: "JJN.png"
permalink: /publication/davinci
excerpt: 'This paper is about fixing template issue #693.'
date: 2025-01-01
venue: 'ICDE'
paperurl: 'https://yangtonghome.github.io/uploads/DaVinci_icde_final.pdf'
citation: 'Yanshu Wang*, Jianan Ji*, Chao-Hsuan Liu, Hengyang Zhou, Tong Yang'

---
Set measurements are fundamental in numerous areas including network measurement, database queries, and data mining. These measurements are typically executed on multisets. Existing algorithms optimize a specific set measurement task, leading to sophisticated but narrowly focused solutions. This specialization often results in inefficiencies when multiple set measurement tasks are required simultaneously, consuming excessive computational and storage resources. This paper introduces DaVinci Sketch, a versatile sketch designed to efficiently handle various set measurement tasks using a single unified data structure. DaVinci Sketch employs a novel approach by utilizing a dedicated structure to store frequent elements, thereby reducing collisions among flows that have the most significant impact on results. Remarkably, DaVinci Sketch can simultaneously perform up to nine different measurement tasks with a single data structure and a unified operation, whereas other approaches typically support fewer tasks. The experimental results demonstrate that DaVinci Sketch achieves high accuracy across 9 measurement tasks. Furthermore, in multi-task scenarios, DaVinci Sketch significantly reduces the memory usage (by more than 59%) and achieves high throughput (more than 23 times faster than other methods).