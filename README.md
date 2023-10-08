# Kurīmu クリーム
![two-parts-v1](https://github.com/alexanmv/try1.github.io/assets/56640707/46531437-4246-4217-a932-07d81712711b)

# About the Database

クリーム


Kurīmu (meaning "cream" in Japanese) is a pangenome data collection for public access. Kurīmu is a highly curated pangenome collection that provides consistent and validated information needed to document published reports for a wide variety of pangenomes at various taxonomic levels. This information was obtained from hundreds of research papers published in peer reviewed scientific journals and incorporated into a database for consistency and reproducibility of the reported and/or adapted results.


# Information Provided

The Kurīmu data collection offers a variety of organized and ready to use information for hundreds of pangenomes, corresponding to over 20,000 individual genome sequences. This collection can serve as an entry point for any pangenome property by taxon, pangenome size, NCBI taxonomy identifier, and citations in the literature. In Kurīmu, information has been harvested for pangenomes at all taxonomic levels. Fields are shown as follows:

-Pangenome: The official scientific name of the taxon; please note that in some cases there are phenotypic (polyphyletic) groups, such as photosynthetic prokaryotes

-Unique_ID: A unique identifier for the organism constructed with MD5

-NCBI_txid: The Taxonomy identifier provided by the NCBI database linking to other data resources

-Effective: The ‘true’ number of genomes used for the calculation of pangenome parameters

-Level: The taxonomic level that this organism belongs to

-Pan: The pangenome size of the entry

-Core: The number of core genes of the entry

-Peripheral: The number of peripheral genes of the entry

-Unique: The number of unique genes of the entry

-Core_pan: The percentage of the pangenome belonging to the core set (an index of coherence: the higher, the tighter the pangenome)

-Shell_eff: The ratio of unique genes per genome (an index of ‘uniqueness’/dispersion: the lower, the tighter the pangenome)

-Reference: First author surname and year of publication for the published report

-DOI: digital object identifier for the corresponding publication

-Gene_cluster: signifies whether the pangenome partitioning refers to traditional protein family clusters (C, red in figure above) or the more recent adoption of the term for gene-level variation (G, green in figure above)

The boolean fields DS1-DS4 correspond to subsets (see Table 3, original publication), in lieu of Data Supplements: DS1 for all pangenomes; DS2 for gene-level pangenomes and missing values for family clusters; DS3 when C+P+U=T (see Box 2, original publication); DS4 for duplicate entries with variable counts for pangenome sets.


# List with the pangenome analysis methods and hyperlinks
|[AGAPE](https://github.com/yeastgenome/AGAPE),|
|                                              |
|                                              |  
[BPGA](https://sourceforge.net/projects/bpgatool/),

[Bloom FT](https://github.com/GuillaumeHolley/BloomFilterTrie),

[BGDMdocker](https://github.com/cgwyx/debian_prokka_panx_antismash_biodocker/),

[CAMBer](http://bioputer.mimuw.edu.pl/camber/),

[EDGAR](https://www.uni-giessen.de/de/fbz/fb08/Inst/bioinformatik/software/EDGAR),

[eCAMBer](http://bioputer.mimuw.edu.pl/ecamber/),

[EUPAN](https://cgm.sjtu.edu.cn/eupan/index.html),

[get_phylomarkers](https://github.com/vinuesa/get_phylomarkers),

[get_homologues](https://github.com/eead-csic-compbio/get_homologues),

[Hierarchicalsets](https://cran.r-project.org/web/packages/hierarchicalSets/index.html),

[Harvest](https://github.com/marbl/harvest),

[ITEP](https://hood-price.isbscience.org/),

[KinFin](https://github.com/DRL/kinfin),

[MCL](http://micans.org/mcl/),

[Mugsy-A](https://mugsy.sourceforge.net/),

MetaRef †,

[micropan](https://cran.r-project.org/web/packages/micropan/index.html),

[MSPminer](https://www.enterome.com/downloads/),

[NGSPanPipe](https://github.com/Biomedinformatics/NGSPanPipe),

PanCGH †,

[progMauve](https://darlinglab.org/mauve/mauve.html),

Panseq †,

[PGAT](http://tools.uwgenomics.org/pgat/),

[PanOCT](https://sourceforge.net/projects/panoct/),

[PGAP](https://sourceforge.net/projects/pgap/),

[PanCake](https://bitbucket.org/CorinnaErnst/pancake/wiki/Home),

[PanFunPro](https://zenodo.org/record/7583),

Pannotator †,

PanGP †,

PanTetris †,

[PanFP](https://github.com/srjun/PanFP),

[Prokka](http://www.vicbioinformatics.com/software.prokka.shtml),

[PanCoreGen](https://sourceforge.net/projects/pancoregen1/),

[PGAdb-builder](http://wgmlstdb.imst.nsysu.edu.tw/),

[PanTools](https://github.com/sheikhizadeh/pantools),

[panX](https://pangenome.org/),

[Phandango](https://github.com/jameshadfield/phandango),

PanWeb †,

[PanViz](https://github.com/thomasp85/PanViz),

[Panaconda](https://github.com/aswarren/pangenome_graphs),

[PanGeT](https://github.com/PanGeTv1/PanGeT),

[PanACEA](https://github.com/JCVenterInstitute/PanACEA/),

[PanGeneHome](https://pangenehome.lmge.uca.fr/),

[Piggy](https://github.com/harry-thorpe/piggy),

[PanVC](https://gitlab.com/dvalenzu/PanVC),

[PGAP-X](https://pgapx.zhaopage.com/),

[Roary](http://sanger-pathogens.github.io/Roary/),

[RPAN](http://cgm.sjtu.edu.cn/3kricedb/),

SOP (pg) †,

[SplitMEM](https://sourceforge.net/projects/splitmem/),

[seqana](https://www.uni-ulm.de/en/in/institute-of-theoretical-computer-science/research/seqana.html),

[Scoary](https://github.com/AdmiralenOla/Scoary),

[seq-seq-pan](https://gitlab.com/rki_bioinformatics/seq-seq-pan),

‘VarDetPGI’.

# How to access

Hit the [link](http://pangenome.s3-website-us-east-1.amazonaws.com/pangenome.html) to start browsing Kurīmu.
