---
layout: about
title: About
permalink: /
subtitle: Ph.D. Candidate at <a href='http://iiis.tsinghua.edu.cn/en/'>IIIS, Tsinghua University</a>. | lixt21@mails.tsinghua.edu.cn

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>IIIS, Tsinghua University</p>
    <p>Beijing, China</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder
---

I am Xintong Li, a Ph.D. candidate at the [Institute for Interdisciplinary Information Sciences (IIIS)](http://iiis.tsinghua.edu.cn/en/), Tsinghua University, advised by professor [Mingyu Gao](https://people.iiis.tsinghua.edu.cn/~gaomy/). I received my Bachelor's degree in Computer Science from Peking University, where I was advised by professor [Guangyu Sun](https://ceca.pku.edu.cn/en/people_/faculty_/guangyu_sun/).

My primary research interest lies in hardware-software co-optimization for irregular computation patterns, particularly those involving sparsity and dynamism. My work encompasses accelerating sparse computation kernels (like SpMSpM), designing solutions for Near-Data Processing (NDP) / Processing-in-Memory (PIM) hardware, and optimizing Large Language Model (LLM) inference services, with a special focus on leveraging sparsity and addressing complex load-balancing challenges.

### Research Highlights

My main projects focus on building efficient accelerator and memory systems for sparse computations.

- **[ISCA 2025] HYTE: Flexible Tiling for Sparse Accelerators via Hybrid Static-Dynamic Approaches**
  - We define a complete design space for sparse tiling and analyze the impact of various sparsity features. Our method uses a static offline scheduler to find a near-optimal initial tiling plan and employs a dynamic runtime to efficiently manage metadata and adjust tile shapes, boosting cache utilization. HYTE achieves a 3.9–7.4x performance improvement over state-of-the-art sparse accelerators.

- **[MICRO 2025] SeaCache: Efficient and Adaptive Caching for Sparse Accelerators**
  - To handle the variable access patterns in sparse workloads, we propose a two-level address mapping scheme to reduce cache line waste. SeaCache also features a low-cost prefetcher that uses one matrix's access patterns to predict another's and explores optimal cache allocation between data, metadata, and prefetched content.

### Experience

- **ByteDance, AML Heterogeneous Computing Group** (Apr 2025 – Present)
  - Research Intern. My work involves deploying LLM inference services on novel hardware like AiMx (an in-memory computing chip) and evaluating the performance of emerging technologies (PIM, RRAM) for LLM applications. I also contributed to the design and optimization of **AutoNDP**, a system for automatic mapping and scheduling of LLM inference on near-data processing platforms.

<!-- ### Honors and Awards

- Tsinghua University First-Class Scholarship, *2025*
- National Scholarship, *2020*
- "Sanhao" (Merit) Student, *2019, 2020*
- Silver Medal, National Olympiad in Informatics (NOI), *2015* -->



<!-- ---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. aatestAddress. Contacts. Motto. Etc.

profile:
  align: right
  image: 
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Tsinghua University</p>
    <p>Beijing, China</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I'm xintong Li

<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. --> -->
