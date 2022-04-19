# KGdatasets

<div>
<h2>Public datasets for graph embedding</h2>
<h3>Available datasets</h3>
<table>
<caption><b>Datasets' table</b></caption>
    <tr>
        <td><b>Number</b></td>
        <td align="center"><b>Dataset</b></td>
        <td align="center"><b>Description</b></td>
    </tr>
    <tr>
        <td align="center">1</td>
        <td><a href="https://github.com/bi-graph/KGdatasets/blob/master/datasets/cn15k.zip">CN15K (ConceptNet 15k)</a></td>
        <td>It is a subset of <a href="https://conceptnet.io/">ConceptNet</a>, a semantic network, designed to help computers understand the meanings of words that people use. Numeric values on triples represent uncertainty.</td>
    </tr>
    <tr>
        <td align="center">2</td>
        <td><a href="https://github.com/bi-graph/KGdatasets/blob/master/datasets/fb15k.zip">FB15k (Freebase 15K)</a></td>
        <td>The FB15k dataset contains knowledge base relation triples and textual mentions of Freebase entity pairs. It has a total of 592,213 triplets with 14,951 entities and 1,345 relationships. FB15K-237 is a variant of the original dataset where inverse relations are removed, since it was found that a large number of test triplets could be obtained by inverting triplets in the training set.</td>
    </tr>
    <tr>
        <td align="center">3</td>
        <td><a href="https://github.com/bi-graph/KGdatasets/blob/master/datasets/fb15k-237.zip">FB15k-237</a> </td>
        <td>FB15k-237 is a link prediction dataset created from FB15k. While FB15k consists of 1,345 relations, 14,951 entities, and 592,213 triples, many triples are inverses that cause leakage from the training to testing and validation splits. FB15k-237 was created by Toutanova and Chen (2015) to ensure that the testing and evaluation datasets do not have inverse relation test leakage. In summary, FB15k-237 dataset contains 310,079 triples with 14,505 entities and 237 relation types.</td>
    </tr>
    <tr>
        <td align="center">4</td>
        <td><a href="">FB13</a> </td>
        <td>FB13 is a subset of Freebase</td>
    </tr>
    <tr>
        <td align="center">5</td>
        <td><a href="https://github.com/bi-graph/KGdatasets/blob/master/datasets/nl27k.zip">NL27K</a> </td>
        <td>NL27K is a typical UKG dataset extracted from NELL (Never Ending Language Learning). The triples in NL27K dataset are high quality (confidence scores >= 0.95) which rarely has noises or uncertain data.</td>
    </tr>
    <tr>
        <td align="center">6</td>
        <td><a href="https://github.com/bi-graph/KGdatasets/blob/master/datasets/onet20k.zip">O*NET20K</a> </td>
        <td>It is a  subset  of <a href="https://www.onetonline.org/">O*NET</a> , a dataset that includes job descriptions, skills
    and labeled, binary relations between such concepts. Each triple is labeled with a numeric value that 
    indicates the importance of that link.</td>
    </tr>
    <tr>
        <td align="center">7</td>
        <td><a href="https://github.com/bi-graph/KGdatasets/blob/master/datasets/ppi5k.zip">PPI5K (protein-protein interactions)</a></td>
        <td>It is a subset of the protein-protein interactions (PPI) knowledge graph. Numeric values represent the confidence of the link based on existing scientific literature evidence.</td>
    </tr>
    <tr>
        <td align="center">8</td>
        <td><a href="">WN18 (WordNet18)</a></td>
        <td>The WN18 dataset has 18 relations scraped from WordNet for roughly 41,000 synsets, resulting in 141,442 triplets. It was found out that a large number of the test triplets can be found in the training set with another relation or the inverse relation. Therefore, a new version of the dataset WN18RR has been proposed to address this issue.</td>
    </tr>
    <tr>
        <td align="center">9</td>
        <td><a href="https://github.com/bi-graph/KGdatasets/blob/master/datasets/wn18RR.zip">WN18RR</a></td>
        <td>WN18RR is a link prediction dataset created from WN18, which is a subset of WordNet. WN18 consists of 18 relations and 40,943 entities. However, many text triples are obtained by inverting triples from the training set. Thus the WN18RR dataset is created to ensure that the evaluation dataset does not have inverse relation test leakage. In summary, WN18RR dataset contains 93,003 triples with 40,943 entities and 11 relation types.</td>
    </tr>
    <tr>
        <td align="center">10</td>
        <td><a href="wordnet11.zip">WordNet11 (WN11)</a></td>
        <td>A lexical database for English</td>
    </tr>
    <tr>
        <td align="center">11</td>
        <td><a href="https://github.com/bi-graph/KGdatasets/blob/master/datasets/YAGO3-10.zip">YAGO3-10 (Yet Another Great Ontology 3-10)</a></td>
        <td>YAGO3-10 is benchmark dataset for knowledge base completion. It is a subset of YAGO3 (which itself is an extension of YAGO) that contains entities associated with at least ten different relations. In total, YAGO3-10 has 123,182 entities and 37 relations, and most of the triples describe attributes of persons such as citizenship, gender, and profession.</td>
    </tr>
</table>
</div>