---
layout: default
title: About FIVR-200k-PVCD
---

To evaluating the performances of PVCD systems on more complicated spatial and temporal situations, we add annotation of the segment pairs for DSVR subset of FIVR-200k to construct the new partial video copy detection benchmark, called FIVR-200k-PVCD. Original FIVR-200k is a Fine-grained instance video retrieval dataset consisting of 225,960 videos and 100 queries, including three retrieval tasks namely Duplicate Scene Video Retrieval (DSVR), Complementary Scene Video Retrieval (CSVR) and Incident Scene Video Retrieval (ISVR). Here we only focus on the annotations DSVR videos.

## Newly Added Segment-level Annotations
 Overall FIVR-200k-PVCD contains 10870 annotated copy segment pairs involving 5935 different video pairs. Many partial copy segments are more challenging with abundant temporal and spatial editing. 

## News 
 [2021-08-03] **The FIVR-200k-PVCD annotations have been released!**

 [2021-08-09] **The full paper is availible now!**

## Links
* [Results][results] 
* [FIVR-200k-PVCD][anno]
* [FIVR-200k][video]
* [Evaluation codes][code]

[anno]: https://pvcd-vsal.github.io/vsal//downloads/
[video]: http://ndd.iti.gr/fivr/
[code]: https://pvcd-vsal.github.io/vsal//codes/
[results]: https://pvcd-vsal.github.io/vsal//results/

<!-- [anno]: http://127.0.0.1:4000//downloads/
[video]: http://ndd.iti.gr/fivr/
[code]: http://127.0.0.1:4000//codes/
[results]: http://127.0.0.1:4000//results/ -->

## Citation
If you use FIVR-200K-PVCD dataset in your research, please cite the following paper[[arXiv]][[pdf]]:
```
Zhen Han, Xiangteng He, Mingqian Tang and Yiliang Lv. 2021. 
Video Similarity and Alignment Learning on Partial Video Copy Detection.
In Proceedings of the 29th ACM International Conference on Multimedia (MM ’21), 
October 20–24, 2021, Virtual Event, China. ACM, New York, NY, USA, 9 pages. 
https://doi.org/10.1145/3474085.3475549
```
[arXiv]: https://arxiv.org/abs/2108.01817
[pdf]: https://arxiv.org/pdf/2108.01817