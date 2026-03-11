using AI to analyse multiple types biological data to find therapuetic targets
of neurodevelopment disorders affected by chromatin- regulators defects.

Chromatin regulators: turn genes on and off, writers, erasers, and readers of 
histone marks; SWI/SNF complex members

Chromatinopathies: mutation in chromatin regulators, causes intellectual 
disability, autism, epilepsy. examples:

1) Coffin- siris syndrome = Presents itself in facial malformations, short
nailess fingers and eye abnormalities. Autosomal dominant affecting 12 genes.
ARID genes in cell cycle control

2) Kabuki syndrome = distinctive facial features, growth delays, varying degrees 
of intellectual disability, skeletal abnormalities and short stature. KMT2D is a
lysine specific methyltransferase and activates enhancers. KDM6A encodes a 
histone demethylase that promotes gene expression.

3) CHARGE syndrome: Caused by random CHD7 gene mutation (used in embryonic 
growth), symptoms include: Coloboma, Heart defects, Atresia choanae, 
Retarded growth, Genital abnormalities, and Ear abnormalities. 


Mini project: Multi-omic signature analysis of a chromatinopathy using public 
data

RNA-seq → Differential Expression → Significant Genes
                  ↓
        Overlay with chromatin data
                  ↓
     Feature table (genes + chromatin signals)
                  ↓
        Machine learning (Random Forest)
                  ↓
          Rank important pathways
