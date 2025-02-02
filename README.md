# SecurityMalware
Malware detection for security in computing

An ensemble classifier for malware detection

Classifiers used:

Decision tree

Random forest

Adaboost

Gradient boosting

Gaussian Naive Bayes

Linear Regression

Normalised featrue list:
1. feature Characteristics (0.208634)
2. feature DllCharacteristics (0.137150)
3. feature Machine (0.079703)
4. feature VersionInformationSize (0.079365)
5. feature MajorSubsystemVersion (0.072201)
6. feature Subsystem (0.066693)
7. feature SizeOfOptionalHeader (0.047118)
8. feature ResourcesMinEntropy (0.044212)
9. feature SectionsMaxEntropy (0.036656)
10. feature SectionsMinEntropy (0.032514)
11. feature ImageBase (0.020871)
12. feature SizeOfStackCommit (0.020711)

Training stats:

Adaboost : 0.9852951829047446 

GradientBoosting : 0.9888446215139443 

LinearRegression : 0.5277241761085258 

GNB : 0.6985512495472654 

RandomForest : 0.9946034045635639 

DecisionTree : 0.9910539659543643 

False positive rate : 0.088913 %

False negative rate : 0.191177 %

To run: python malware_test.py legitimatefile.exe

python malware_test.py malware.exe

References:
https://docs.microsoft.com/en-us/windows/desktop/api/winnt/ns-winnt-_image_optional_header
https://en.wikibooks.org/wiki/X86_Disassembly/Windows_Executable_Files
https://pdfs.semanticscholar.org/d1fd/840c5a626e0004d2ca01847d6a97557c402a.pdf
