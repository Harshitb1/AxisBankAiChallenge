# AxisBankAiChallenge
<b>This Repository contains code for verification of signature</b>

<br/>Tensorflow is used and details of folder is as follows -
<br/>* axis_bank.ipynb file contains model 
<br/>* forged and real folders contain dataset for this project in form of real and forged images respectively
<br/>* training folder will save the trained images

<br/>Images are stored in the format : <b>XXXZZZ_YYY</b>
<br/>XXX denotes id of the person who has signed on the document(ex -001)
<br/>ZZZ denotes the id of the person to whom the sign belongs in actual(ex- 001)
<br/>YYY deontes the n'th no.of attempt

<br/>Now if <b>XXX == ZZZ </b>then image is <b>genuine</b> otherwise the signature is forged


