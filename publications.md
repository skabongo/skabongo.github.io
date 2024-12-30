---
layout: page
title: "Publications"
tagline : ""
use_math: true
lang: zh
---
{% include JB/setup %}

{% assign posts_collate = site.categories.projects %}
{% include JB/posts_collate %}

<link rel="stylesheet" href="/glyphicons/css/glyphicons.css">

<table style="width:100%">
<col width="20%">
<col width="10">
<col >

<!-- <tr height="50">
<td style="padding-left: 1px;
    padding-bottom: 3px;
    vertical-align: bottom;">
    <strong style="font-size: 25px;">2017</strong></td>
</tr> -->

<!-- <tr style="border-bottom:1pt solid #eee" >
<td markdown="1">
![videovec](images/main/videovec.jpg){:class="img-shadow"}
</td>
<td></td>
<td markdown="1">
<div><a href="/archive/research/videovec/"><b>Video Vectorization via Tetrahedral Remeshing</b></a></div>
<div><b>Chuan Wang</b>, Jie Zhu, Yanwen Guo, Wenping Wang</div>
<div><i>IEEE Transactions on Image Processing, 2017</i></div>
<div><i>"converting a raster video into its vectorized version, with perservation of the video features"</i></div>

|| <em class="icon-home"></em> || [project page](/archive/research/videovec/) || <em class="icon-file"></em> || [paper](/archive/research/videovec/paper.pdf) || <em class="icon-film"></em> || [video demo](https://youtu.be/KmPdjB8f4ww) ||

</td> 
</tr> -->

<tr height="50">
<td style="padding-left: 1px;
    padding-bottom: 3px;
    vertical-align: bottom;">
    <strong style="font-size: 25px;">2021</strong></td>
</tr>

<tr style="border-bottom:1pt solid #eee" >
<td markdown="1">
<!-- ![spiden](images/papers/icadl2021.png =100x20){:class="img-shadow"} -->
<img src="images/papers/icadl2021.png" width="200" height="200" />
</td>
<td></td>
<td markdown="1">
<div><b>Automated Mining of Leaderboards for Empirical AI Research</b></div>
<div>
With the rapid growth of research publications, empowering scientists to keep oversight over the scientific progress is of paramount importance. In this regard, the Leaderboards facet of information organization provides an overview on the state-of-the-art by aggregating empirical results from various studies addressing the same research challenge. Crowdsourcing efforts like PapersWithCode among others are devoted to the construction of Leaderboards predominantly for various subdomains in Artificial Intelligence. Leaderboards provide machine-readable scholarly knowledge that has proven to be directly useful for scientists to keep track of research progress. The construction of Leaderboards could be greatly expedited with automated text mining.
This study presents a comprehensive approach for generating Leaderboards for knowledge-graph-based scholarly information organization. Specifically, we investigate the problem of automated Leaderboard construction using state-of-the-art transformer models, viz. Bert, SciBert, and XLNet. Our analysis reveals an optimal approach that significantly outperforms existing baselines for the task with evaluation scores above 90% in F1. This, in turn, offers new state-of-the-art results for Leaderboard extraction. As a result, a vast share of empirical AI research can be organized in the next-generation digital libraries as knowledge graphs.
</div>
<div><i>Accepted as a full paper at ICADL 2021</i></div>

|| <em class="icon-home"/> || [paper](https://arxiv.org/pdf/2109.13089.pdf) || <em class="icon-github"/> || [source code](https://github.com/Kabongosalomon/task-dataset-metric-nli-extraction) ||

</td> 
</tr>

<tr style="border-bottom:1pt solid #eee" >
<td markdown="1">
<img src="images/papers/listra.png" width="200" height="200" />
</td>
<td></td>
<td markdown="1">
<div><b>LiSTra Automatic Speech Translation: English to Lingala case study</b></div>
<div>
In recent years there have been great interests in addressing the low resourcefulness of African languages and providing baseline models for different Natural Language Processing tasks. Several initiatives on the continent use the Bible as a data source to provide proof of concept for some NLP tasks. In this work, we present the Lingala Speech Translation (LiSTra) dataset, release a full pipeline for the construction of such dataset in other languages, and report baselines using both the traditional cascade approach (Automatic Speech Recognition -> Machine Translation) and a revolutionary transformer-based End-2-End architecture with customized interactive attention that allows information sharing between the recognition decoder and the translation decoder.
</div>
<div><i>Accepted as a Poster and selected for spotlight talk at The 5th Black in AI Workshop (co-located with NeurIPS 2021)</i></div>

|| <em class="icon-home"/> || [paper](/archive/posterBiai2021.pdf) || <em class="icon-github"/> || [source code](https://github.com/dsfsi/2020-AMMI-salomon) ||

</td> 
</tr>

<tr height="50">
<td style="padding-left: 1px;
    padding-bottom: 3px;
    vertical-align: bottom;">
    <strong style="font-size: 25px;">2020</strong></td>
</tr>

<tr style="border-bottom:1pt solid #eee" >
<td markdown="1">
<img src="images/papers/masakhane_paper_1.png" width="200" height="200" />

</td>
<td></td>
<td markdown="1">
<div><b>MASAKHANE - MACHINE TRANSLATION FOR AFRICA</b></div>
<div>
Africa has over 2000 languages. Despite this, African languages account for a small portion of available resources and publications in Natural Language Processing (NLP). This is due to multiple factors, including: a lack of focus from government and funding, discoverability, a lack of community, sheer language complexity, difficulty in reproducing papers and no benchmarks to compare techniques. In this paper, we discuss our methodology for building the community and spurring research from the African continent, as well as outline the success of the community in terms of addressing the identified problems affecting African NLP.</div>
<div><i>Accepted for the AfricaNLP Workshop, ICLR 2020</i></div>

|| <em class="icon-home"/> || [paper](https://arxiv.org/pdf/2003.11529.pdf) || <em class="icon-github"/> || [source code](https://github.com/masakhane-io/masakhane.git) ||

</td> 
</tr>

<tr height="50">
<td style="padding-left: 1px;
    padding-bottom: 3px;
    vertical-align: bottom;">
    <strong style="font-size: 25px;">2020</strong></td>
</tr>

<tr style="border-bottom:1pt solid #eee" >
<td markdown="1">
<img src="images/papers/aims_sa_msc.jpg" width="200" height="200" />

</td>
<td></td>
<td markdown="1">
<div><b>An empirical investigation into the properties of standard word embeddings</b></div>
<div>
The embedding of word sequences into continuous vector spaces has been one of the most important developments in Natural Language Processing in the recent past. Such embeddings have found application in areas such as Automatic Speech Recognition, Machine Translation, Sentiment Analysis and many more. This essay reviews the various mechanisms that have been proposed for the calculation of word embeddings, investigates popular toolkits and embedding matrices that are available in the public domain, and experiments with one or more selected implementations to better understand their characteristics.</i></div>

|| <em class="icon-home"/> || [paper](https://library.nexteinstein.org/thesis/an-empirical-investigation-into-the-properties-of-standard-word-embeddings/) || <em class="icon-github"/> || [source code](https://github.com/Kabongosalomon/Word-Embedding-Investigation) ||

</td> 
</tr>

<!-- <tr height="50">
<td style="padding-left: 1px;
    padding-bottom: 3px;
    vertical-align: bottom;">
    <strong style="font-size: 25px;">2015</strong></td>
</tr> -->

<!-- <tr style="border-bottom:1pt solid #eee" >
<td markdown="1">
![thesis](images/main/hkulogo2.jpg){:class="img-shadow"}
</td>
<td></td>
<td markdown="1">
<div><b>Ph.D Thesis: Video Object Co-Segmentation and Video Vectorization</b></div>
<div><b>Chuan Wang</b></div>
<div><i>The University of Hong Kong, January 2015.</i></div>
<div><i>"a detailed version of the works in video object co-segmentation and video vectorization"</i></div>

|| <em class="icon-file"></em> || thesis || <!--[thesis](/archive/research/thesis.pdf)-->

<!-- </td> 
</tr> -->

<!-- <tr height="50">
<td style="padding-left: 1px;
    padding-bottom: 3px;
    vertical-align: bottom;">
    <strong style="font-size: 25px;">2014</strong></td>
</tr> -->

<!-- <tr style="border-bottom:1pt solid #eee" >
<td markdown="1">
![videocoseg](images/main/videocoseg.jpg){:class="img-shadow"}
</td>
<td></td>
<td markdown="1">
<div><a href="/archive/research/videocoseg/"><b>Video Object Co-segmentation via Subspace Clustering and Quadratic Pseudo-Boolean Optimization in an MRF Framework</b></a></div>
<div><b>Chuan Wang</b>, Yanwen Guo, Jie Zhu, Linbo Wang, Wenping Wang</div>
<div><i>IEEE Transactions on Multimedia, 2014.</i></div>
<div><i>"common-foreground co-segmentation system for a group of videos"</i></div>

|| <em class="icon-home"/> || [project page](/archive/research/videocoseg/) || <em class="icon-file"/> || [paper](/archive/research/videocoseg/paper.pdf) || <em class="icon-film"/> || [video demo](https://youtu.be/vbeN6JMkuGk) ||

</td> 
</tr> -->

</table>

<style type="text/css">
td {
    border: 0.5px;
    vertical-align: center;
    text-align: left;
}
</style>
