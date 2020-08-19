# Stanford-Dogs-
This repository compares seven state of the art pre-trained, deep learning models, on the Stanford Dogs Dataset. The dataset is challenging due to various reasons. It is a huge dataset as it has around 22,000 annotated images of dogs belonging to 120 species. Secondly, it is a fine-grained dataset. So, there is little inter-class variation and large intraclass variation.<br>
I have used following pre-trained models to train on this dataset:
<ol>
  <li>MobileNetV2</li>
<li>DenseNet121</li>
<li>EfficientNetB7</li>
<li>EfficientNetB7; weights: NosiyStudent</li>
<li>InceptionResNetV2</li>
<li>ResNet50</li>
 </ol>
 
 <h2> Results </h2>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Architecture</th>
    <th class="tg-0pky">Best Vadilation Accuracy</th>
    <th class="tg-0pky">Training time in minutes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow">MobileNetV2</td>
    <td class="tg-c3ow">78.44</td>
    <td class="tg-c3ow">104</td>
  </tr>
  <tr>
    <td class="tg-c3ow">DenseNet121</td>
    <td class="tg-c3ow">81.76</td>
    <td class="tg-c3ow">58</td>
  </tr>
  <tr>
    <td class="tg-c3ow">EfficientNetB7</td>
    <td class="tg-c3ow">90.62</td>
    <td class="tg-c3ow">74</td>
  </tr>
  <tr>
    <td class="tg-c3ow">Noisy-student</td>
    <td class="tg-c3ow">88.542</td>
    <td class="tg-c3ow">78</td>
  </tr>
  <tr>
    <td class="tg-c3ow">InceptionResNetV2</td>
    <td class="tg-c3ow">86.46</td>
    <td class="tg-c3ow">46</td>
  </tr>
  <tr>
    <td class="tg-c3ow">ResNet50</td>
    <td class="tg-c3ow">87.5</td>
    <td class="tg-c3ow">31</td>
  </tr>
  <tr>
    <td class="tg-c3ow">ResNet50 + c</td>
    <td class="tg-c3ow">80.208</td>
    <td class="tg-c3ow">30</td>
  </tr>
</tbody>
</table>
