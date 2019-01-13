# Language-Model
This language model is built in Keras using an LSTM with the Adam optimiser, and can generate models with multiple diversity levels.

Its purpose is to provide insight into the common discussion points in reports written by carers after home visits.

It is based on IBM's Deep Learning Language Model (https://github.com/IBM/deep-learning-language-model).


## Sample output:
"...et, from the kitchen, filled it with water and left close to the bedroom. on this visit mrs X didn't open the bowels, two care workers using hoist assisted mrs X with transfer from commode to the bed, dressed pad and assisted with transfer to the w..."

This sample highlights some of the common discussion points, which were consistent with other samples:
- bowels
- mobility
- dressing
- eating and drinking

## Future planned work:
Run model with different dataset sizes to assess impact on accuracy.
