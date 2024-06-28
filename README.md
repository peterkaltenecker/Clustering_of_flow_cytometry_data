# K-means clustering of flow cytometry data
Flow cytometry is a very powerful technology to study single cells, from several types of biological samples, in solution. It is particularly convenient to examine the proportion of different immune cell types in blood.
Conventionally, these cell types are distinguished by the presence of distinct markers, which are used to categorize individual cells into certain groupings. 
This classification system relies on decades of extensive laboratory research, however, unsupervised machine learning techniques, such as clustering, might reveal new insights in this field and help to finetune categorization.<br>
<br>
In this example separated human B cells (from peripheral blood) were studied and the cell surface markers CD27 and IgD were used for classification. Based on these markers we differentiate 4 major groups of immune cells in our everyday laboratory practice: double negatives, double positives, CD27<sup>+</sup>IgD<sup>-</sup> and CD27<sup>-</sup>IgD<sup>+</sup>. The results of K-means clustering will be compared to the manual selection of these groups, however, the latter is not presented here yet.
