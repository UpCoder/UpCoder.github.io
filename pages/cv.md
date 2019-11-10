---
layout: page
title: CV
permalink: /cv/
feature-img: "assets/img/pexels/circuit.jpeg"
tags: [CV, Archive]
---

<script>
    $('').ready(function(){
        let is_check = false;
        $('#switcher-lg').click(function(){
            if(is_check){
                $('#language_div_en').hide();
                $('#language_div_cn').show();
                is_check = false;
                console.log(is_check);
            }else{
                $('#language_div_en').show();
                $('#language_div_cn').hide();
                is_check = true;
                console.log(is_check);
            }
        });
    })
</script>
<div id='language_div_cn'>
    <div class='co-md-12' style='text-align:center;' name='basic information en'>
        <h3>基本信息</h3>
        <table style='margin:auto;width:80%;' border="0" cellpadding="0" cellspacing="0">
            <tr style='margin:auto;'>
                <td>邮箱<br/> cs_liangdong@qq.com</td>
                <td>电话<br/> +86-17774010899</td>
                <td>技能<br/> Deep Learning, Machine Learning</td>
                <td>框架<br/> Tensorflow, Keras</td>
            </tr>
        </table>
    </div>
    <div class='col-md-12' name='education information cn'>
        <h3 style='text-align:center;'>教育经历</h3> 
        <div name='work experience bytedance' style="width:80%;margin:auto">
            <ul>
                <li>2017.09---2020.03 硕士, 计算机科学与技术专业, 浙江大学, 杭州, 中国</li>
                <li>2013.09---2017.07 学士, 软件工程专业, 西北工业大学, 西安, 中国</li>
            </ul>
        </div> 
    </div>
    <div class='col-md-12' name='Publication cn'>
        <h3 style='text-align:center;'>发表文献</h3>
        <div name='work experience bytedance' style="width:80%;margin:auto">
            <ul>
                <li><b>Liang, Dong</b>, et al. Unsupervised Teacher-Student Model for Large-Scale Video Retrieval." Proceedings of the IEEE International Conference on Computer Vision Workshops. 2019.<a href="http://openaccess.thecvf.com/content_ICCVW_2019/html/ViRaL/Liang_Unsupervised_Teacher-Student_Model_for_Large-Scale_Video_Retrieval_ICCVW_2019_paper.html">Paper</a>,<a href="https://github.com/UpCoder/UTSModel">Code</a></li>
                <li>
                <b>Liang D</b>, Lin L, Chen X, et al. Multi-Stream Scale-Insensitive Convolutional and Recurrent Neural Networks for Liver Tumor Detection in Dynamic Ct Images[C]//2019 IEEE International Conference on Image Processing (ICIP). IEEE, 2019: 794-798.<a href="">Paper</a>, <a href="">Code</a></li>
                <li>Chen X, Lin L, <b>Liang D</b>, et al. A Dual-Attention Dilated Residual Network for Liver Lesion Classification and Localization on CT Images[C]//2019 IEEE International Conference on Image Processing (ICIP). IEEE, 2019: 235-239.<a href="">Paper</a>, <a href="">Code</a></li>
                <li><b>Liang D</b>, Lin L, Hu H, et al. Combining convolutional and recurrent neural networks for classification of focal liver lesions in multi-phase CT images[C]//International Conference on Medical Image Computing and Computer-Assisted Intervention. Springer, Cham, 2018: 666-675.<a href="">Paper</a>, <a href="">Code</a></li>
                <li><b>Liang D</b>, Lin L, Hu H, et al. Residual convolutional neural networks with global and local pathways for classification of focal liver lesions[C]//Pacific Rim International Conference on Artificial Intelligence. Springer, Cham, 2018: 617-628.<a href="">Paper</a>, <a href="">Code</a></li>
            </ul>
        </div>
    </div>
    <div class='col-md-12' name='Work Experience cn'>
        <h3 style='text-align:center;'>工作经验</h3>
        <div name='work experience bytedance' style="width:80%;margin:auto">
            <h4>AI Lab, ByteDance Inc. 2019.05---2019.08</h4>
            <p>我是负责相似视频检索研发的实习生。</p>
            <ul>
                <li>开发了无监督的Teacher-Student模型，来优化大规模相似视频检索。并且达到的state-of-the-art在FIVR数据集上，在三个任务上的mAP分别达到 50.94%, 49.83, 43.18. QPS(单卡P4) 提升两倍 (150->300).</li>
                <li>基于hash的二值化特征，开发了帧级别的检索流程。它适合长视频检索的场景，可以保持视频的关键信息。</li>
                <li>对比了不同检索引擎的性能。例如 HNSW, IVF-HNSW, Link && Code</li>
                <li>相关工作已经发表至ICCV 2019 Workshop <a href="">Paper</a>,<a href="">Code</a></li>
            </ul>
        </div>
    </div>
    <div class='col-md-12' name='Awards cn'>
        <h3 style='text-align:center;'>荣誉</h3>
        <div name='work experience bytedance' style="width:80%;margin:auto">
            <ul>
                <li>【浙江大学】三好学生，2019.12</li>
                <li>【浙江大学】优秀研究生，2018.12 && 2019.12</li>
                <li>【浙江大学】陈天洲奖学金, 2018.05 && 2019.05</li>
                <li>【浙江大学】蒋震奖学金, 2017.11 && 2018.11</li>
                <li>【MICCAI】MICCAI 2018 Student Travel Award</li>
                <li>【西北工业大学】优秀毕业生，2017.06</li>
                <li>【西北工业大学】工信部创新二等奖学金, 2017.05</li>
                <li>【西北工业大学】国家奖学金, 2014.11 && 2015.11 && 2016.11</li>
                <li>【西北工业大学】宝钢奖学金, 2016.12</li>
            </ul>
        </div>
    </div>
</div>
<p style='text-align:right'>Last Updated: 10/11/2019</p>
 
