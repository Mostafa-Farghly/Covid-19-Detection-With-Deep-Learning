# Covid-19-Detection-With-Deep-Learning
### Results of AlexNet, Resnet50, and Resnet101 CNN in Detecting Covid-19 Using CT and X-ray Images.
# Datasets Used
<table>
  <tr>
      <th><center>Number</center></th>
    <th><center>Dataset's link</center></th>
      <th><center>Modality</center></th>
      <th><center>Data Size (Number of Images)</center></th>
  </tr>
    
  <tr>
      <td><center>1</center></td>
    <td><center>https://github.com/UCSD-AI4H/COVID-CT</center></td>
    <td><center>CT</center></td>
    <td><center>746</center></td>
  </tr>
  
  <tr>
      <td><center>2</center></td>
    <td><center>https://github.com/RunwenHu/COVID-19</center></td>
    <td><center>CT</center></td>
    <td><center>802</center></td>
  </tr>
  
  <tr>
      <td><center>3</center></td>
    <td><center>https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset</center></td>
    <td><center>CT</center></td>
    <td><center>2481</center></td>
  </tr>
  
  <tr>
      <td><center>4</center></td>
    <td><center>https://www.dropbox.com/s/7rjw6oet4za01op/CovidDataset-20200427T133042Z-001.zip?dl=0</center></td>
    <td><center>X-ray</center></td>
    <td><center>284</center></td>
  </tr>
  
</table>

# Highlights
### Accuracies of Customized AlexNet vs ResNet 101 (When Trained By Dataset 2)
<table style="width:100%">    
    <tr>
        <th></th>
        <th><center>Customized AlexNet</center></th>
        <th><center>ResNet 101</center></th>
    </tr>
    <tr>
        <th><center>Validation Accuracy</center></th>
        <td><center>98.86%</center></td>
        <td><center>97.55%</center></td>
    </tr>
    <tr>
        <th><center>Test Accuracy (tested by 10% of dataset 2)</center></th>
        <td><center>90.01%</center></td>
        <td><center>91.21%</center></td>
    </tr>
    <tr>
        <th><center>Test by dataset 1 (the whole dataset)</center></th>
        <td><center>92.76%</center></td>
        <td><center>89.54%</center></td>
    </tr>
    <tr>
        <th><center>Test by dataset 2 (the whole dataset)</center></th>
        <td><center>97.63%</center></td>
        <td><center>95.64%</center></td>
    </tr>
    <tr>
        <th><center>Test by dataset 3 (the whole dataset)</center></th>
        <td><center>44.58%</center></td>
        <td><center>49.01%</center></td>
    </tr>
</table>

### Accuracies of Customized AlexNet vs ResNet 101 (When Trained By Dataset 3)
<table style="width:100%">    
    <tr>
        <th></th>
        <th><center>Customized AlexNet</center></th>
        <th><center>ResNet 101</center></th>
    </tr>
    <tr>
        <th><center>Validation Accuracy</center></th>
        <td><center>95.07%</center></td>
        <td><center>96.92%</center></td>
    </tr>
    <tr>
        <th><center>Test Accuracy (tested by 10% of dataset 3)</center></th>
        <td><center>93.95%</center></td>
        <td><center>91.94%</center></td>
    </tr>
    <tr>
        <th><center>Test by dataset 1 (the whole dataset)</center></th>
        <td><center>55.63%</center></td>
        <td><center>58.45%</center></td>
    </tr>
    <tr>
        <th><center>Test by dataset 2 (the whole dataset)</center></th>
        <td><center>61.85%</center></td>
        <td><center>65.59%</center></td>
    </tr>
    <tr>
        <th><center>Test by dataset 3 (the whole dataset)</center></th>
        <td><center>98.51%</center></td>
        <td><center>95.32%</center></td>
    </tr>
</table>
