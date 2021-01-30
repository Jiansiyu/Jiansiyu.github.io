---
layout: splash
permalink: /
hidden: true
# header:
#   overlay_color: "#5e616c"
#   overlay_image: home/img_mountains_wide.jpg
#   actions:
#     - label: "<i class='fas fa-download'></i> Install now"
#       url: "/docs/quick-start-guide/"
# excerpt: >
#   A flexible two-column Jekyll theme. Perfect for building personal sites, blogs, and portfolios.<br />
#   <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.20.2">Latest release v4.20.2</a></small>
feature_row:
  - image_path: home/parity_500x300.png
    alt: "research"
    title: "Research"
    excerpt: "My research is mainly focus on the Lead(Pb) Radius Experiment(PRex). Beside that I am also working on the SBS GEM tracker.."
    url: "/Research/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  
  - image_path: home/RG-Machine-Blog_0.png
    alt: "MachineLearning"
    title: "Machine Learning"
    excerpt: "My notes about machine learning project and some other topics. Machine Learing! Machine Learing!"
    url: "/machinelearing/"
    btn_class: "btn--primary"
    btn_label: "Learn more"

  - image_path: home/learning_500x300.jpg
    alt: "Notes"
    title: "Learning Notes"
    excerpt: "MY notes about Machine Learning, Docker, SQL, bash, Linux system, and also some other interesting topics"
    url: "/year-archive/"
    btn_class: "btn--primary"
    btn_label: "Learn more"

imagesslideshow:
  # - slide_image: home/unsplash-image-1_1500x500.png
  #   alt: "100% free"
  #   title: "100% free"
  #   excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
  #   url: "/docs/license/"
  #   btn_class: "btn--primary"
  #   btn_label: "Learn more"

  - slide_image: home/uva_long.jpg
    alt: "100% free"
    title: "100% free"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  

leetcode_feature_row:
  - icon_image: "leetcode/download.png"
    user: "大胖喵的leetcode"
    chaturl: "https://docs.google.com/spreadsheets/d/e/2PACX-1vTXt-UsTz6zxIl1C0frYfkBU9S56_29nnRFUDorv0gZ0WLZ3wHzUGoNIoPZdxewxaKDXGeBwLJgADj1/pubchart?oid=198820844&amp;format=interactive"
    statisticurl: "https://docs.google.com/spreadsheets/d/e/2PACX-1vTXt-UsTz6zxIl1C0frYfkBU9S56_29nnRFUDorv0gZ0WLZ3wHzUGoNIoPZdxewxaKDXGeBwLJgADj1/pubchart?oid=1193338765&amp;format=interactive"

  # - icon_image: "leetcode/download.png"
  #   user: "小喵咪的leetcode"
  #   chaturl: "https://docs.google.com/spreadsheets/d/e/2PACX-1vQnsjFK7I1KcqCEx7R7RRRwhYgYBTVywoSTbs8DMxvN9VdPo7evRQfABZnCNGQjQyQQZCdPKl_cscdX/pubchart?oid=198820844&amp;format=interactive"
  #   statisticurl: "https://docs.google.com/spreadsheets/d/e/2PACX-1vQnsjFK7I1KcqCEx7R7RRRwhYgYBTVywoSTbs8DMxvN9VdPo7evRQfABZnCNGQjQyQQZCdPKl_cscdX/pubchart?oid=1969946663&amp;format=interactive"

---
{% include imageslideshow.html %}

---
{% include feature_row %}

---
{% include leetcodeProgress.html %}

---

{% include footer.html %}
