# Using preprocessed data
## TF-IDF
### Number of clusters = 5

**SVD**
![[kmeans_tfidf_svd.PNG]]
**Elbow**
![[kmeans_tfidf_elbow.PNG]]
**Silhouette Plot**
![[kmeans_tfidf_5clusters_silhouette.png]]

**Inter cluster distance**
![[kmeans_tfidf_5clusters_interdistance.png]]

**Intra cluster distance:**
Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5723.0 
Average Diameter Distance: 1984.8232931760856 
Centroid Diameter Distance: 464325.3520435619 

Intra cluster distances for topic **3**: 
Complete Diameter Distance: 5701.0 
Average Diameter Distance: 2343.49103021331 
Centroid Diameter Distance: 420402.24528022745 

Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5653.0 
Average Diameter Distance: 1572.6359756028046 
Centroid Diameter Distance: 447455.40909009404 

Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5673.0 
Average Diameter Distance: 1652.8534858326484 
Centroid Diameter Distance: 473674.47245919163 

Intra cluster distances for topic **4**: 
Complete Diameter Distance: 4474.0 
Average Diameter Distance: 1332.241412803532
Centroid Diameter Distance: 326101.34265072644

**Calinski-Harabasz**
Calinski-Harabasz score (higher is better): 30.410959402231644

**Davies-Bouldin**
Davies-Bouldin score (closer to 0 is better): 8.335909228672278

**Topic diversity**
{0: 0.0, 1: 0.0, 2: 0.0, 3: 0.0, 4: 1.0}

**Topic coherence**
c_npmi: 0.09289920211661833 
c_uci: 0.23044912854658609 
c_umass: -2.5502118881328673 

c_npmi for each topic: [0.06198455423269983, 0.15869880565300673, 0.20722712057890272, 0.029217872218573, 0.0073676578999093386] 

c_uci for each topic: [0.06198455423269983, 0.15869880565300673, 0.20722712057890272, 0.029217872218573, 0.0073676578999093386] 

c_umass for each topic: [0.06198455423269983, 0.15869880565300673, 0.20722712057890272, 0.029217872218573, 0.0073676578999093386]

## Embeddings
#### BERT
**Number of clusters = 4**

**SVD**
![[kmeans_emb_svd.PNG]]
**Elbow**
![[kmeans_emb_elbow.PNG]]
**Silouette plot**
![[kmeans_emb_4clusters_silhouette.PNG]]

**Inter Cluster Distance**
![[kmeans_emb_4clusters_interdistance.PNG]]

**Intra Cluster Distance**
Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5721.0 
Average Diameter Distance: 2135.848491611799 
Centroid Diameter Distance: 170947.61551483165

Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5722.0 
Average Diameter Distance: 1897.8180887161454 
Centroid Diameter Distance: 155202.57231333488

Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5718.0 
Average Diameter Distance: 1768.532963775268 
Centroid Diameter Distance: 156026.17071131745

Intra cluster distances for topic **3**: 
Complete Diameter Distance: 5693.0 
Average Diameter Distance: 2062.4152687673773 
Centroid Diameter Distance: 179457.3126802542

**Calinski-Harabasz**
Calinski-Harabasz score (higher is better): 7134.6722484857355

**Davies-Bouldin**
Davies-Bouldin score (closer to 0 is better): 0.8690557887974575

**Topic Diversity**
{0: 0.0, 1: 0.0, 2: 0.0, 3: 1.0}

**Coherence**
c_npmi: 0.10362356628091014 
c_uci: 0.061487066151353756 
c_umass: -3.068764135867488

c_npmi for each topic: [0.060519132261228153, 0.28597152717843094, 0.008598852505174821, 0.05940475317880666] 

c_uci for each topic: [0.060519132261228153, 0.28597152717843094, 0.008598852505174821, 0.05940475317880666] 

c_umass for each topic: [0.060519132261228153, 0.28597152717843094, 0.008598852505174821, 0.05940475317880666]

---

#### XLNET
**SVD**
![[kmeans_xlnet_svd.png]]
**Elbow**
![[kmeans_xlnet_elbow.PNG]]
**Silhouette**
![[kmeans_xlnet_3clusters_silhouette.PNG]]

**Inter Cluster Distance**
![[kmeans_xlnet_3cluster_interdistance.PNG]]

**Intra Cluster Distance**
Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5723.0 
Average Diameter Distance: 2113.332355332929 
Centroid Diameter Distance: 428867.0056295372

Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5718.0 
Average Diameter Distance: 1781.078942214936 
Centroid Diameter Distance: 422339.02670965565

Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5688.0 
Average Diameter Distance: 1973.9886016451235 
Centroid Diameter Distance: 433353.8035664494

**Calinski-Harabasz**
Calinski-Harabasz score (higher is better): 50329.99653815486

**Davies-Bouldin**
Davies-Bouldin score (closer to 0 is better): 0.2843959043089151

**Topic diversity**
{0: 0.0, 1: 0.0, 2: 1.0}

**Topic coherence**
c_npmi: 0.06849318992370977 
c_uci: -0.1825337020496051 
c_umass: -2.696087440728117

c_npmi for each topic: [0.060846510686940344, 0.027158612103146625, 0.11747444698104231] 

c_uci for each topic: [0.060846510686940344, 0.027158612103146625, 0.11747444698104231] 

c_umass for each topic: [0.060846510686940344, 0.027158612103146625, 0.11747444698104231]

#### AlBERT
**SVD**
![[kmeans_albert_svd.PNG]]
**Elbow**
![[kmeans_albert_elbow.PNG]]
**Silhouette**
![[kmeans_albert_3clusters_silhouette.PNG]]
**Inter Cluster Distance**
![[kmeans_albert_3clusters_interdistance.PNG]]

**Intra Cluster Distance**
Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5723.0 
Average Diameter Distance: 2120.000362714931 
Centroid Diameter Distance: 189409.83385954014

Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5718.0 
Average Diameter Distance: 1780.0462588490639 
Centroid Diameter Distance: 176931.4487517692

Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5688.0 
Average Diameter Distance: 1995.7058441558443 
Centroid Diameter Distance: 197819.71625844575

**Calinski-Harabasz**
Calinski-Harabasz score (higher is better): 119544.31959988055

**Davies-Bouldin**
Davies-Bouldin score (closer to 0 is better): 0.19690454821622705

**Topic diversity**
{0: 1.0, 1: 1.0, 2: 1.0}

**Topic Coherence**
c_npmi: 0.06849318992370977 
c_uci: -0.1825337020496051 
c_umass: -2.696087440728117

c_npmi for each topic: [0.060846510686940344, 0.027158612103146625, 0.11747444698104231] 

c_uci for each topic: [0.060846510686940344, 0.027158612103146625, 0.11747444698104231] 

c_umass for each topic: [0.060846510686940344, 0.027158612103146625, 0.11747444698104231]
### DeCLUTR
#### Number of clusters=5

**SVD**
![[kmeans_declutr_svd.png]]
**Elbow**
![[kmeans_declutr_elbow.PNG]]

**Silhouette**
![[kmeans_declutr_5clusters_silhouette.PNG]]

**Inter Cluster Distance**
![[kmeans_declutr_5clusters_interdistance.PNG]]

**Intra Cluster Distance**
Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5714.0 
Average Diameter Distance: 1919.894922953082 
Centroid Diameter Distance: 156081.71170512636

Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5722.0 
Average Diameter Distance: 1908.940963195838 
Centroid Diameter Distance: 165503.17684623293

Intra cluster distances for topic **4**: 
Complete Diameter Distance: 5719.0 
Average Diameter Distance: 2054.996487130958 
Centroid Diameter Distance: 158801.16115844765

Intra cluster distances for topic **3**: 
Complete Diameter Distance: 5682.0 
Average Diameter Distance: 1608.7331895299576 
Centroid Diameter Distance: 151729.74735013014

Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5142.0 
Average Diameter Distance: 2116.12 
Centroid Diameter Distance: 158573.75453143552

**Calinski-Harabasz**
Calinski-Harabasz score (higher is better): 142.84165380459942

**Davies-Bouldin**
Davies-Bouldin score (closer to 0 is better): 3.981131202254636

**Topic diversity**
{0: 0.0, 1: 0.0, 2: 1.0, 3: 0.0, 4: 0.0}

**Coherence**
c_npmi: 0.10609732857940199 
c_uci: -0.05851240528707815 
c_umass: -2.8800381293891126

c_npmi for each topic: [0.06028950781310395, 0.2858221281144686, 0.03030514335088248, 0.09366385615525828, 0.06040600746329667] 

c_uci for each topic: [0.06028950781310395, 0.2858221281144686, 0.03030514335088248, 0.09366385615525828, 0.06040600746329667] 

c_umass for each topic: [0.06028950781310395, 0.2858221281144686, 0.03030514335088248, 0.09366385615525828, 0.06040600746329667]

# Using original data
## TF-IDF
### Number of clusters = 6
**SVD**
![[tfidf_original_data_svd.PNG]]
**Elbow**
![[tfidf_original_data_elbow.PNG]]
**Silhouette**
![[tfidf_original_data_silhouette.PNG]]
**Inter Clusters Distance**
![[tfidf_original_data_inter_distance.PNG]]
**Intra Clusters Distance**
Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5723.0 
Average Diameter Distance: 2018.1166179147654 
Centroid Diameter Distance: 776439.4800090049

Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5701.0 
Average Diameter Distance: 2341.0821198766353 
Centroid Diameter Distance: 713556.3108644387

Intra cluster distances for topic **5**: 
Complete Diameter Distance: 5645.0 
Average Diameter Distance: 1579.6279934673096 
Centroid Diameter Distance: 743488.2370905668

Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5653.0 
Average Diameter Distance: 1635.7541727065645 
Centroid Diameter Distance: 772625.3441932797

Intra cluster distances for topic **4**: 
Complete Diameter Distance: 5668.0 
Average Diameter Distance: 1701.4972373938251 
Centroid Diameter Distance: 794524.0300398096

Intra cluster distances for topic **3**: 
Complete Diameter Distance: 4528.0 
Average Diameter Distance: 1285.9446162118563 
Centroid Diameter Distance: 533062.7412761761

**Calinski-Harabasz**
Calinski-Harabasz score (higher is better): 13.63431241859787

**Davies-Bouldin**
Davies-Bouldin score (closer to 0 is better): 12.084333063569565

**Topic Diversity**
{0: 1.0, 1: 1.0, 2: 1.0, 3: 1.0, 4: 1.0, 5: 1.0}

**Topic Coherence**
c_npmi: 0.1321753716600249 
c_uci: 0.5469488687106242 
c_umass: -2.575587379779541

c_npmi for each topic: [0.061078846725978346, 0.15774107871020876, 0.20648369213355686, 0.13680177245198913, 0.1287478068595059, 0.10219903307891048] 

c_uci for each topic: [0.061078846725978346, 0.15774107871020876, 0.20648369213355686, 0.13680177245198913, 0.1287478068595059, 0.10219903307891048]

c_umass for each topic: [0.061078846725978346, 0.15774107871020876, 0.20648369213355686, 0.13680177245198913, 0.1287478068595059, 0.10219903307891048]
## Embeddings
### BERT
#### 4 Clusters
**SVD**
![[BERT_original_data_svd.png]]
**Elbow**
![[BERT_original_data_elbow.png]]
**Silhouette**
![[BERT_original_data_silhouette.png]]
**Inter Cluster Distance**
![[BERT_original_data_inter_distance.png]]
**Intra Cluster Distance**
Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5721.0 
Average Diameter Distance: 2140.733313152106 
Centroid Diameter Distance: 290256.78949038044

Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5722.0 
Average Diameter Distance: 1902.352837552787 
Centroid Diameter Distance: 280706.90020092647

Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5718.0 
Average Diameter Distance: 1769.4230305950373 
Centroid Diameter Distance: 280061.157191193

Intra cluster distances for topic **3**: 
Complete Diameter Distance: 5693.0 
Average Diameter Distance: 2068.1554022988507 
Centroid Diameter Distance: 297849.54373821465

**Calinski Harabasz**
Calinski-Harabasz score (higher is better): 39630.32101837557

**Davies Buoldin**
Davies-Bouldin score (closer to 0 is better): 0.3845689578784088

**Topic diversity**
{0: 1.0, 1: 1.0, 2: 1.0, 3: 1.0}

**Topic coherence**
c_npmi: 0.10362356628091017 
c_uci: 0.061487066151353784 
c_umass: -3.068764135867488

c_npmi for each topic: [0.060519132261228174, 0.285971527178431, 0.008598852505174814, 0.059404753178806655] 

c_uci for each topic: [0.060519132261228174, 0.285971527178431, 0.008598852505174814, 0.059404753178806655] 

c_umass for each topic: [0.060519132261228174, 0.285971527178431, 0.008598852505174814, 0.059404753178806655]

### DeCLUTR
**SVD**
![[kmeans_original_dataset_declutr_svd.PNG]]
**Elbow**
![[kmeans_original_dataset_declutr_elbow.PNG]]
**Silhouette**
![[kmeans_original_data_declutr_silhouette.PNG]]
**Inter Clusters Distance**
![[kmeans_original_data_declutr_inter_distance.PNG]]
**Intra Clusters Distance**
Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5714.0 
Average Diameter Distance: 1919.894922953082 
Centroid Diameter Distance: 156081.71170512636

Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5722.0 
Average Diameter Distance: 1908.940963195838
Centroid Diameter Distance: 165503.17684623293

Intra cluster distances for topic **4**: 
Complete Diameter Distance: 5719.0 
Average Diameter Distance: 2054.996487130958 
Centroid Diameter Distance: 158801.16115844765

Intra cluster distances for topic **3**:
Complete Diameter Distance: 5682.0 
Average Diameter Distance
: 1608.7331895299576 
Centroid Diameter Distance: 151729.74735013014

Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5142.0
Average Diameter Distance: 2116.12 
Centroid Diameter Distance: 158573.75453143552

**Calinski-Harabasz**
Calinski-Harabasz score (higher is better): 142.84165380459942

**Davies-Bouldin**
Davies-Bouldin score (closer to 0 is better): 3.981131202254636

**Topic Diversity**
{0: 1.0, 1: 1.0, 2: 1.0, 3: 1.0, 4: 1.0}

**Topic Coherence**
c_npmi: 0.10609732857940199 
c_uci: -0.05851240528707815 
c_umass: -2.8800381293891126

c_npmi for each topic: [0.06028950781310395, 0.2858221281144686, 0.03030514335088248, 0.09366385615525828, 0.06040600746329667] 

c_uci for each topic: [0.06028950781310395, 0.2858221281144686, 0.03030514335088248, 0.09366385615525828, 0.06040600746329667] 

c_umass for each topic: [0.06028950781310395, 0.2858221281144686, 0.03030514335088248, 0.09366385615525828, 0.06040600746329667]

### XLNet
**SVD**
![[kmeans_original_data_xlnet_svd.PNG]]
**Elbow**
![[kmeans_original_data_xlnet_elbow.PNG]]
**Silhouette**
![[kmeans_original_data_xlnet_silhouette.PNG]]
**Inter Clusters Distance**
![[kmeans_original_data_xlnet_inter_distance.PNG]]

**Intra Clusters Distance**
Intra cluster distances for topic **0**: 
Complete Diameter Distance: 5721.0 
Average Diameter Distance: 2140.733313152106 
Centroid Diameter Distance: 290256.78949038044

Intra cluster distances for topic **2**: 
Complete Diameter Distance: 5722.0 
Average Diameter Distance: 1902.352837552787 
Centroid Diameter Distance: 280706.90020092647

Intra cluster distances for topic **1**: 
Complete Diameter Distance: 5718.0 
Average Diameter Distance: 1769.4230305950373
Centroid Diameter Distance: 280061.157191193

Intra cluster distances for topic **3**:
Complete Diameter Distance: 5693.0 
Average Diameter Distance: 2068.1554022988507 
Centroid Diameter Distance: 297849.54373821465

**Calinski-Harabasz**
Calinski-Harabasz score (higher is better): 39630.32101837557

**Davies-Bouldin**
Davies-Bouldin score (closer to 0 is better): 0.3845689578784088

**Topic Diversity**
{0: 1.0, 1: 1.0, 2: 1.0, 3: 1.0}

**Topic Coherence**
c_npmi: 0.10362356628091017 
c_uci: 0.061487066151353784 
c_umass: -3.068764135867488

c_npmi for each topic: [0.060519132261228174, 0.285971527178431, 0.008598852505174814, 0.059404753178806655] 

c_uci for each topic: [0.060519132261228174, 0.285971527178431, 0.008598852505174814, 0.059404753178806655] 

c_umass for each topic: [0.060519132261228174, 0.285971527178431, 0.008598852505174814, 0.059404753178806655]