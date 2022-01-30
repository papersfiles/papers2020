# A Machine Learning-Based Approach For IdentifyingGod Components and Unstable Dependencies



#### How to read the features

The adaptation consists in calculating the maximum (max), minimum (min),
mean, median, first quartile (q1), second quartile (q2), standard deviation (std)
and sum, e.g., if a component A has 10 classes, the LOC metric was adapted
in the following way: LOC sum represents the sum of line code of all classes in
the component; LOC max represents the highest number of lines of code in a
class inside the component; LOC min, LOC q1, LOC q2,


### Important Files

features-gc.csv       => Selected features of God Components

features-ud.csv       => Selected features of Unstable Dependency

ud_full.csv           => Full Unstable Dependency Dataset

qualitas.csv          => Version of software from Qualitas Corpus

githubandappache.csv  => Version of software from Apache and github
