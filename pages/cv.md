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
<div id='switch_language_btn' class="form-switcher form-switcher-lg form-switcher-sm-phone">
      <input type="checkbox" name="switcher-lg" id="switcher-lg">
      <label class="switcher" for="switcher-lg"></label>
</div>
<div id='language_div_en'>
    <div class='co-md-12' style='text-align:center;' name='basic information en'>
        <h3>Basic Information</h3>
        <table style='margin:auto;width:80%;' border="0" cellpadding="0" cellspacing="0">
            <tr style='margin:auto;'>
                <td>Email<br/> cs_liangdong@qq.com</td>
                <td>Tel<br/> +86-17774010899</td>
                <td>Skills<br/> Deep Learning, Machine Learning</td>
                <td>Framework<br/> Tensorflow, Keras</td>
            </tr>
        </table>
    </div>
    <div class='col-md-12' name='education information en'>
        <h3 style='text-align:center;'>Education</h3> 
        <div name='work experience bytedance' style="width:80%;margin:auto">
            <ul>
                <li>2017.09---2020.03 Master, Computer Science and Technology, Zhejiang University, Hangzhou, China</li>
                <li>2013.09---2017.07 Bachlor, Software Engineering, Northwestern Polytechnical University, Xi'an, China</li>
            </ul>
        </div> 
    </div>
    <div class='col-md-12' name='Publication en'>
        <h3 style='text-align:center;'>Publications</h3>
        <div name='work experience bytedance' style="width:80%;margin:auto">
            <ul>
                <li>
                <b>Liang D</b>, Lin L, Chen X, et al. Multi-Stream Scale-Insensitive Convolutional and Recurrent Neural Networks for Liver Tumor Detection in Dynamic Ct Images[C]//2019 IEEE International Conference on Image Processing (ICIP). IEEE, 2019: 794-798.<a href="">Paper</a>, <a href="">Code</a></li>
                <li>Chen X, Lin L, <b>Liang D</b>, et al. A Dual-Attention Dilated Residual Network for Liver Lesion Classification and Localization on CT Images[C]//2019 IEEE International Conference on Image Processing (ICIP). IEEE, 2019: 235-239.<a href="">Paper</a>, <a href="">Code</a></li>
                <li><b>Liang D</b>, Lin L, Hu H, et al. Combining convolutional and recurrent neural networks for classification of focal liver lesions in multi-phase CT images[C]//International Conference on Medical Image Computing and Computer-Assisted Intervention. Springer, Cham, 2018: 666-675.<a href="">Paper</a>, <a href="">Code</a></li>
                <li><b>Liang D</b>, Lin L, Hu H, et al. Residual convolutional neural networks with global and local pathways for classification of focal liver lesions[C]//Pacific Rim International Conference on Artificial Intelligence. Springer, Cham, 2018: 617-628.<a href="">Paper</a>, <a href="">Code</a></li>
            </ul>
        </div>
    </div>
    <div class='col-md-12' name='Work Experience en'>
        <h3 style='text-align:center;'>Work Experience</h3>
        <div name='work experience bytedance' style="width:80%;margin:auto">
            <h4>AI Lab, ByteDance Inc. 2019.05---2019.08</h4>
            <p>I was an intern during this time. I was focusing on the similar video retrieval.</p>
            <ul>
                <li>Developed Unsupervised Teacher-Student Model for large-scale video retrieval. And archieveed the new state-of-the-art in FIVR dataset. The mAP of three tasks is 50.94%, 49.83, 43.18. QPS(single P4) increased by 2 times (150->300).</li>
                <li>Developed Frame-level Retrieval Pipeline based on hash binarized code. It is suitable for long-video retrieval scenarios, which can keep the key information of video.</li>
                <li>Compared different retrieval engines. such as HNSW, IVF-HNSW, Link && Code</li>
                <li>Related work was accepted by ICCV workshop 2019. <a href="">Paper</a>,<a href="">Code</a></li>
            </ul>
        </div>
    </div>
    <div class='col-md-12' name='Awards en'>
        <h3 style='text-align:center;'>Awards</h3>
        <div name='work experience bytedance' style="width:80%;margin:auto">
            <ul>
                <li>Tianzhou Chen Scholarship, 2018.05, 2019.05, ZJU</li>
                <li>Chiang Chun Scholarship, 2017.11, 2018.11, ZJU</li>
                <li>MICCAI 2018 Student Travel Award</li>
                <li>National Scholarship, 2014.11, 2015.11, 2016.11</li>
                <li>Baogang Scholarship 2016.12</li>
                <li>Second-class scholarship of the Ministry of Industry and Information Technology, 2017.05</li>
                <li>Outstanding graduates, NPU</li>
            </ul>
        </div>
    </div>
</div>
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
                <li>陈天洲奖学金, 2018.05, 2019.05, ZJU</li>
                <li>蒋震奖学金, 2017.11, 2018.11, ZJU</li>
                <li>MICCAI 2018 Student Travel Award</li>
                <li>国家奖学金, 2014.11, 2015.11, 2016.11</li>
                <li>宝钢奖学金, 2016.12</li>
                <li>工信部创新二等奖学金, 2017.05</li>
                <li>西北工业大学优秀毕业生</li>
            </ul>
        </div>
    </div>
</div>
<p style='text-align:right'>Last Updated: 09/09/2019</p>
 
