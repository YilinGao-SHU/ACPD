# Towards All-Category License Plate Recognition: A Large Dataset and Baseline
License plate detection and recognition(LPDR) is widely used in intelligent transportation systems. Although there are typically multiple categories of license plates for various vehicles, most existing research cannot be applied to multi-category plates due to the scarcity of large-scale multi-category plate datasets and the fact that existing methods are not optimised for multi-category plate scenarios. In this paper, we propose a large-scale All-Category LDPR dataset(AKPD) for vehicles in mainland China, which also contains annotations of license plate categories. At the same time, an multi-category license plate recognition framework named GroupPlate is proposed as our dataset's baseline, which includes group module and implicit supervision module, making full use of the implicit and explicit information of license plate to recognize the multi-category license plates. Experiments demonstrate that the dataset we proposed can ease the problem of models trained on a single category license plate dataset failing to recognize multi-category license plates. Extensive results show that GroupPlate achieves the comparable performance on single-category license plate dataset CCPD and outperforms significantly on top of our GroupPlate's baseline on our all-category license plates dataset. Ablation experiments demonstrate the effectiveness of group module and implicit supervision module in our GroupPlate.
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="https://github.com/YilinGao-SHU/AKPD/blob/main/img/AKCPD.png" width = "100%" alt=""/>
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">
       Fig. 1. Examples of our dataset. 
  	</div>
</center>

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="https://github.com/YilinGao-SHU/AKPD/blob/main/img/Pipeline.png" width = "100%" alt=""/>
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">
       Fig. 1. Pipeline of GroupPlate. 
  	</div>
</center>
