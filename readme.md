<h1> Running on local Machine (Preferred) </h1>
install requirements using 
pip install -r requirements.txt
<h2>To evaluate the code</h2>
<ol>
  <li> change to code directory </li>
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
  download cleaned_application.csv
  <li>run label_final.ipynb</li>
  set onlinedataset to True
  download max_label.csv
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
