```bio-meta
{
    "name": "Zifan Wang",
    "title": "Zifan Wang | Curriculum Vitae",
    "description": "Zifan Wang&#8217;s curriculum vitae.",
    "domain": "zifan_wang.bio",
    "date-created": "2020-04-13",
    "repo": "https://github.com/SailColubrid",
    "tilecolor": "#222222"
}
```

# Sail (Zifan) Wang<span aria-hidden="true"> </span><span lang="zh-CN">王梓帆</span><span aria-hidden="true"></span>

<figure class="gl-page-background gl-float-right gl-image-box" style="text-align: center;"><img src="/assets/images/hero-image.jpeg" alt="A photo of Zifan Wang" width="160" height="160" style="max-width: 160px;" /></figure>

I’m a first-year Ph.D. student in Electrical and Computer Enigneering, Carnegie Mellon University. I am co-advised by Prof. [Anupam Datta](http://www.andrew.cmu.edu/user/danupam/) and Prof. [Matt Fredrikson](http://www.cs.cmu.edu/~mfredrik/) in the [**Accountable System Lab**](https://fairlyaccountable.org). My current concentration is the development of interpretations for deep neural networks. Before joining CMU, I received my B.S. in Electronic Science and Technology from Beijing Institute of Technology.


## Contact
E-mail: `zifan.wang@sv.cmu.edu`

Cubic: `CIC-2205@Cylab, CMU, 15213`


```bio-remove
Below we use a simple mechanism to mitigate email address reaping.
Change the encoding for your own email address.
```

<!--[bio][protect]
<script type="application/javascript">
window.setTimeout(function ()
{
var addr = [108,117,111,106,105,64,99,115,46,119,97,115,104,105,110,103,116,111,110,46,101,100,117];
addr = String.fromCharCode.apply(String, addr);
var eml = document.getElementById('_eml');
eml.innerHTML = '<a href="mailto:' + addr + '">' + addr + '</a>';
eml.removeAttribute('class');
}, 600);
</script>
[bio]-->

## Teaching Assitance
* 2019 Spring 18-661 Introduction to Machine Learning for Engineers
* 2020 Fall 18-739 Fairness and Security in Deep Learning


## Publications

```blog-bib

@comment
{
The output is guaranteed to be labeled.
You can use #bibitem_PKC_DLOSS18 to refer to "PKC:DLOSS18".

To support more information links (e.g., allow "slides" or "pdf" links),
see "builder/marked.0.3.6/bibtex-service.js" line 85.
}

[CVPR2020 Workshop]
@misc{wang2020interpreting,
    title={Interpreting Interpretations: Organizing Attribution Methods by Criteria},
    author={Zifan Wang and Piotr Mardziel and Anupam Datta and Matt Fredrikson},
    year={2020},
    eprint={2002.07985},
    archivePrefix={arXiv},
    primaryClass={cs.AI}
}

Motivated by distinct, though related, criteria, a growing number of attribution methods have been developed tointerprete deep learning. While each relies on the interpretability of the concept of "importance" and our ability to visualize patterns, explanations produced by the methods often differ. As a result, input attribution for vision models fail to provide any level of human understanding of model behaviour. In this work we expand the foundationsof human-understandable concepts with which attributionscan be interpreted beyond "importance" and its visualization; we incorporate the logical concepts of necessity andsufficiency, and the concept of proportionality. We definemetrics to represent these concepts as quantitative aspectsof an attribution. This allows us to compare attributionsproduced by different methods and interpret them in novelways: to what extent does this attribution (or this method)represent the necessity or sufficiency of the highlighted inputs, and to what extent is it proportional? We evaluate our measures on a collection of methods explaining convolutional neural networks (CNN) for image classification. We conclude that some attribution methods are more appropriate for interpretation in terms of necessity while others are in terms of sufficiency, while no method is always the most appropriate in terms of both.


[CVPR2020 Workshop]
@misc{wang2019scorecam,
    title={Score-CAM: Score-Weighted Visual Explanations for Convolutional Neural Networks},
    author={Haofan Wang and Zifan Wang and Mengnan Du and Fan Yang and Zijian Zhang and Sirui Ding and Piotr Mardziel and Xia Hu},
    year={2019},
    eprint={1910.01279},
    archivePrefix={arXiv},
    primaryClass={cs.CV}
}

Recently, increasing attention has been drawn to the internal mechanisms of convolutional neural networks, and the reason why the network makes specific decisions. In this paper, we develop a novel post-hoc visual explanation method called Score-CAM based on class activation mapping. Unlike previous class activation mapping based approaches, Score-CAM gets rid of the dependence on gradients by obtaining the weight of each activation map through its forward passing score on target class, the final result is obtained by a linear combination of weights and activation maps. We demonstrate that Score-CAM achieves better visual performance and fairness for interpreting the decision making process. Our approach outperforms previous methods on both recognition and localization tasks, it also passes the sanity check. We also indicate its application as debugging tools. Official code has been released.

```



## Acknowledgement

This website is developed under Mr. Ji Luo's [Published Project](http://iiis.tsinghua.edu.cn/en/).
