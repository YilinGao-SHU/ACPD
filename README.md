# GroupPlate: Towards All-Category License Plate Recognition
License plate detection and recognition (LPDR) is widely used in intelligent transportation systems. Although there are typically multiple categories of license plates for various vehicles, most existing research cannot be applied to multi-category plates due to the fact that existing methods are not optimised for multi-category plate scenarios and the scarcity of large-scale multi-category plate datasets. In this paper, we propose a multi-category license plate recognition framework named GroupPlate, which includes Group Module and Indirect Supervision Module, making full use of the implicit and explicit information of license plate to recognize the multi-category license plates. At the same time, we propose a large-scale All-Category license Plate detection and recognition Dataset (ACPD) for vehicles in mainland China, which also contains annotations of license plate categories. Experiments shows that GroupPlate achieves the comparable performance to the existing methods on single-category license plate dataset and outperforms significantly on top of our baseline on our all-category license plates dataset. Ablation experiments demonstrate the effectiveness of Group Module and Indirect Supervision Module in our GroupPlate. Extensive results show that the dataset we proposed can ease the problem of models trained on a single category license plate dataset failing to recognize multi-category license plates.
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="https://github.com/YilinGao-SHU/ACPD/blob/main/img/AKCPD.png" width = "100%" alt=""/>
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
    src="https://github.com/YilinGao-SHU/ACPD/blob/main/img/Pipeline.png" width = "100%" alt=""/>
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">
       Fig. 1. Pipeline of GroupPlate. 
  	</div>
</center>
