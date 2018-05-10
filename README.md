# netscrub

Note: Work in progress

This is a command-line tool written in Java 
that collects network data using the command-line component of
WireShark, called TShark. 

Once the data is collected, it is fed into a feature extractor,
which extracts certain features from the data. For example, some 
valuable features might be source_ip and destination_ip. 
Thus, these types of features will be extracted. 

Once the features are extracted, they are passed on to the 
ML Predictor.

The ML Predictor is itself an independent project that will form
predictions based on this raw data. 

  
