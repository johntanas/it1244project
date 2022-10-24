<h1> Running on local Machine (Preferred) </h1>
pip install -r requirements.txt
<h2>To evaluate the code</h2>
<ol>
  <li>run dataclean.ipynb</li>
  <li>run label_final.ipynb</li>
  <li>run model_score.ipynb</li>
  <li>run model_nn.ipynb</li>
  <li>run datavisual.ipynb</li>
</ol>
<h1> Running on google colab </h1>
<ol>
  <li>run dataclean.ipynb</li>
  set onlinedataset to True (third code block)
  <li>run label_final.ipynb</li>
  set onlinedataset to True
  <li>run model_score.ipynb</li>
  <ul>
  <li>upload max_label.csv onto content</li>
  <li>upload cleaned_application.csv onto content</li>
  </ul>
  <li>run model_nn.ipynb</li>
  <ul>
  <li>upload max_label.csv onto content</li>
  <li>upload cleaned_application.csv onto content</li>
  </ul>
  <li>run datavisual.ipynb</li>
  <ul>
  <li>upload all the score csv onto content</li>
  </ul>
</ol>
<h2> To reproduce results </h2>
 <ul> 
 <li>Set n_repeats to 5 in model_score and model_nn ( time-consuming warning)</li>
 <li> Or set basedir to ../content/nrepeats5 </li>
 </ul>
