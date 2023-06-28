# Metagenomics

[中文版](https://github.com/flowhub-team/CNV/blob/main/README_cn.md)

Metagenomics research is a study method that involves analyzing the collective genome of microbial communities in environmental samples to understand their structure, functionality, and interactions. The typical steps involved in metagenomics research include sample collection, DNA or RNA extraction, high-throughput sequencing, data analysis, and interpretation.

Metagenomics research has widespread applications in various fields. In environmental science, it can be used to study microbial diversity and functionality in ecosystems, as well as their responses to environmental changes. In agriculture, metagenomics research can be employed to improve microbial management strategies for soil health and crop growth. In medical research, it can help uncover the relationship between the human gut microbiota and health, disease, and treatment responses.

Metagenomics research provides a comprehensive approach to understanding microbial communities, facilitating a deeper understanding of microbial diversity, functionality, and ecological roles. This, in turn, supports applications in environmental conservation, agriculture, and medicine.

Here are the main steps and key concepts of metagenomics research：

1. Sample Collection: Collecting samples from the desired environment, such as soil, water, animal intestines, etc. The selection and collection methods of the samples can influence the results of subsequent metagenomic analyses.

2. DNA or RNA Extraction: Extracting the microbial genomic DNA or transcribed RNA from the collected samples. The extraction method should be capable of obtaining high-quality and high-concentration nucleic acids.

3. High-throughput Sequencing: Sequencing the extracted DNA or RNA, typically using next-generation sequencing technologies such as Illumina or PacBio. This process generates a vast amount of sequence data, including gene sequences from various microorganisms.

4. Data Analysis: Performing bioinformatics analysis on the generated sequence data. This includes steps such as sequence quality control, removal of host DNA, sequence assembly, gene annotation, and functional analysis. These analytical methods can be used to determine the composition, diversity, functionality, and metabolic pathways of the microbial community.
    
   1. 16S rRNA analysis tools:
      1. QIIME (Quantitative Insights Into Microbial Ecology): QIIME is an open-source tool used for analyzing microbial community 16S rRNA sequencing data. It provides functionalities for data processing, quality control, OTU (Operational Taxonomic Unit) clustering, species annotation, and diversity analysis.[QIIME  website](https://qiime2.org/)
      2. Mothur is an open-source software for microbial community analysis, which includes functions for processing 16S rRNA sequences, performing clustering analysis, species annotation, and diversity assessment. It provides a comprehensive set of tools for studying and characterizing microbial communities.[Mothur website](https://www.mothur.org/)
      3. DADA2: DADA2 is a software package specifically designed for high-resolution analysis of 16S rRNA variants. It allows for denoising, removing chimeras, variant analysis, and species annotation of sequence data. DADA2 enables the identification of individual sequence variants, providing a more precise and accurate representation of microbial community composition.[DADA2 website](https://benjjneb.github.io/dada2/)
      4. UPARSE: UPARSE is a tool for processing 16S rRNA data, which includes functionalities such as quality filtering, chimera removal, OTU clustering, and species annotation. It is widely used for analyzing microbial community sequencing data, particularly for amplicon-based studies. UPARSE provides a comprehensive pipeline for generating operational taxonomic units (OTUs) and assigning taxonomic identities to sequences.[UPARSE website](https://drive5.com/uparse/)
   2. Functional annotation and metabolic pathway analysis tools.
      1. MG-RAST: MG-RAST is an online platform for metagenomic analysis that provides functionalities such as sequence annotation, classification, functional annotation, and includes a wide range of data analysis tools.[MG-RAST website](https://www.mg-rast.org/)
      2. KEGG: Kyoto Encyclopedia of Genes and Genomes is an abbreviation that represents a comprehensive database providing gene functional annotation, metabolic pathway analysis, and systems biology information.[KEGG website](https://www.genome.jp/kegg/)
      3. IMG/M: Integrated Microbial Genomes & Microbiomes is an abbreviation for an online platform dedicated to metagenomics research. It offers functionalities such as gene annotation, diversity analysis, comparative genomics, and more. IMG/M provides a comprehensive resource for studying and analyzing microbial genomes and microbiomes.[IMG/M website](https://img.jgi.doe.gov/m/)
      4. PICRUSt: Phylogenetic Investigation of Communities by Reconstruction of Unobserved States is an abbreviation for a tool used to predict the functional composition of microbial communities based on 16S rRNA data. PICRUSt utilizes evolutionary relationships to infer the functional capabilities of microorganisms in a given community, providing insights into the potential functional profiles of the microbiome.[PICRUSt website](https://picrust.github.io/picrust/)
   3. Genome Assembly and Gene Prediction Tools:
      1. MetaSPAdes: MetaSPAdes is a tool specifically designed for assembling metagenomic sequencing data. It can handle complex microbial community data, making it particularly suitable for mixed samples. MetaSPAdes employs an iterative algorithm that combines de Bruijn graph assembly with read mapping, helping to overcome challenges posed by diverse genomes and varying abundances in metagenomic datasets.[MetaSPAdes website](https://cab.spbu.ru/software/spades/)
      2. MEGAHIT: MEGAHIT is a fast and efficient genome assembly tool, specifically designed for handling large-scale metagenomic data. It utilizes a succinct de Bruijn graph algorithm to assemble fragmented reads into longer contigs. MEGAHIT is known for its ability to handle complex microbial communities and large datasets, making it a valuable tool in metagenomics research.[GitHub](https://github.com/voutcn/megahit)
      3. IDBA-UD: IDBA-UD is an assembly tool specifically designed for de novo assembly of unknown data, making it suitable for metagenomic sequencing data. It employs a de Bruijn graph algorithm and a stepwise iterative approach to handle complex and diverse microbial communities. IDBA-UD is known for its ability to assemble contigs from short reads, enabling the reconstruction of genomes without relying on reference sequences.[IDBA-UD website](https://i.cs.hku.hk/~alse/hkubrg/projects/idba_ud/)
      4. Prodigal: Prodigal is an open-source tool used for gene prediction. It is capable of identifying open reading frames (ORFs) from genomic or metagenomic data. Prodigal employs an efficient algorithm to predict protein-coding genes and provides annotations such as start and stop codons, gene length, and protein translations. It is widely used for gene annotation and functional analysis in genomics and metagenomics studies.[GitHub](https://github.com/hyattpd/Prodigal)
   4. Macrobiome Diversity Analysis Tools:
      1. QIIME (Quantitative Insights Into Microbial Ecology): QIIME is an open-source tool used for analyzing microbial community 16S rRNA sequencing data. It provides functionalities for data processing, quality control, OTU (Operational Taxonomic Unit) clustering, species annotation, and diversity analysis. QIIME allows for comprehensive exploration and interpretation of microbial diversity within and between samples.[QIIME website](https://qiime2.org/)
      2. Mothur: Mothur is an open-source software designed for microbial community analysis, which includes features for processing 16S rRNA sequences, performing clustering analysis, species annotation, and diversity assessment. It offers a comprehensive suite of tools for studying and characterizing microbial communities, allowing for in-depth exploration of their diversity, composition, and structure.[mothur website](https://www.mothur.org/)
      3. RDP (Ribosomal Database Project): RDP is an abbreviation for the Ribosomal Database Project. It provides microbial classification and diversity analysis based on 16S rRNA data. RDP offers a comprehensive and curated database of ribosomal RNA sequences along with analysis tools for taxonomic assignment, phylogenetic analysis, and ecological diversity assessment. It is widely used in microbial ecology and metagenomics studies for characterizing and understanding microbial communities.[RDP website](https://rdp.cme.msu.edu/)
      4. Vegan: Vegan is a package implemented in R language used for ecological data analysis and diversity assessment. It provides a wide range of functions and statistical tools for analyzing community ecology, including species diversity, community composition, ordination methods, and ecological similarity measures. Vegan is widely used in ecological research to explore and interpret patterns and processes in biodiversity and community dynamics.[Vegan website](https://cran.r-project.org/web/packages/vegan/index.html)
   5. Network Analysis Tools:
      1. Cytoscape: Cytoscape is a popular open-source software platform for visualizing and analyzing complex networks. It provides a user-friendly interface and a wide range of plugins for network visualization, layout algorithms, data integration, and network analysis.[Cytoscape website](https://cytoscape.org/)
      2. CoNet: CoNet is a software tool used for analyzing co-occurrence and interaction relationships in microbial community data. It enables the identification of potential microbial associations and interactions by employing statistical methods and network analysis techniques. CoNet allows researchers to explore and uncover complex microbial relationships and their ecological implications in microbial communities.[CoNet website](https://sourceforge.net/projects/consensusnetwork/)
      3. SparCC: SparCC is a statistical method used to infer microbial co-occurrence networks based on correlation analysis. It utilizes a sparse correlation approach to estimate correlations between microbial taxa in a community. SparCC helps uncover potential co-occurrence patterns and interactions among microorganisms, providing insights into the structure and dynamics of microbial ecosystems.[SparCC website](https://bitbucket.org/yonatanf/sparcc/)
      4. MEGAN (MetaGenome Analyzer): MEGAN is an abbreviation for MetaGenome Analyzer. It is a software tool used for taxonomic classification and annotation of metagenomic data. MEGAN allows for the construction of microbial taxonomic trees and analysis of community structures based on sequence similarity and taxonomic information. It provides a comprehensive platform for exploring the taxonomic composition and functional potential of microbial communities in metagenomic datasets.[MEGAN website](https://megan.informatik.uni-tuebingen.de/)

5. Biological interpretation: Biological interpretation involves comparing and interpreting data analysis results with known genomic and metabolic pathway databases. This process helps in understanding the functional features, environmental adaptability, and interaction networks of microbial communities. By mapping the obtained data onto reference databases, researchers can gain insights into the potential functions, metabolic capabilities, and ecological roles of microorganisms within a given community. This step is crucial for connecting the analyzed data to existing biological knowledge and advancing our understanding of microbial systems.
   1. Gene Function Annotation Tools:
      1. BLAST (Basic Local Alignment Search Tool): BLAST is a widely used tool for sequence similarity searching. It compares a query sequence against a database of known sequences to identify homologous sequences and infer functional annotations based on sequence similarity.[BLAST website](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
      2. InterProScan: InterProScan is a tool that integrates multiple protein signature databases, such as Pfam, PROSITE, and InterPro, to predict protein domains, motifs, and functional annotations based on sequence analysis.[InterProScan website](https://www.ebi.ac.uk/interpro/interproscan.html)
      3. HMMER: HMMER is a tool based on hidden Markov models (HMMs) used to search for sequence similarity between a query sequence and protein family or domain models. It employs profile HMMs to identify conserved domains, motifs, and functional regions within protein sequences. HMMER is widely used for protein sequence analysis, homology searching, and functional annotation in genomics and proteomics research.[HMMER website](http://hmmer.org/)
      4. KAAS (KEGG Automatic Annotation Server): KAAS is a web-based tool that utilizes the KEGG Orthology (KO) identifiers to annotate gene sequences and assign them to KEGG functional pathways and modules. It performs automatic annotation by comparing input sequences against the KEGG GENES database and assigns them with KEGG orthologs and corresponding functional annotations. KAAS is a valuable resource for functional annotation and pathway analysis, providing insights into the biological functions and metabolic pathways associated with a set of genes or genomes.[KAAS website](https://www.genome.jp/tools/kaas/)
   2. Metabolic Pathway Analysis Tools:
      1. KEGG (Kyoto Encyclopedia of Genes and Genomes): KEGG is a comprehensive database that provides information on biological pathways, including metabolic pathways. It offers a collection of annotated pathway maps and associated genes, enzymes, and compounds. Researchers can use KEGG to explore and analyze metabolic pathways, visualize pathway diagrams, and study the functional roles of genes in specific pathways.[KEGG website](https://www.genome.jp/kegg/)
      2. MetaCyc: MetaCyc is a comprehensive database that contains a wide range of metabolic pathway information. It serves as a valuable resource for metabolic annotation and analysis of macrogenomic data. MetaCyc provides curated and experimentally validated metabolic pathways, enzyme reactions, and metabolites across various organisms. Researchers can utilize MetaCyc to annotate metabolic pathways in macrogenomic datasets, analyze metabolic network connectivity, and investigate the functional capabilities of microbial communities. The database offers a wealth of information to facilitate the understanding of metabolic processes and their regulation in diverse biological systems.[MetaCyc website](https://metacyc.org/)
      3. Metagenome Analyzer (MEGAN): MEGAN is a software tool specifically designed for annotating and analyzing sequences from metagenomic data and mapping them to known metabolic pathways. It allows researchers to assign taxonomic and functional annotations to sequences using various databases, including NCBI, UniProt, and KEGG. MEGAN employs advanced algorithms to classify sequences based on their similarity to reference sequences and provides visualizations, such as interactive heatmaps and phylogenetic trees, to explore the taxonomic and functional composition of metagenomic samples. Additionally, MEGAN supports pathway analysis and allows users to identify enriched metabolic pathways in their metagenomic datasets. The tool aids in the interpretation of metagenomic data and provides insights into the metabolic potential of microbial communities.[MEGAN website](https://megan.informatik.uni-tuebingen.de/)

### Metagenomics Standard Workflow Tutorial

#### How to use FlowHub to quickly complete data analysis
+ Step1：Click flow link，Enter FLOWHUB standard subscribe page，click "subscribe" to subscribe to the flow.
  ![step1](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step1.png)
+ Step2：If you do not log in to the platform in advance, the subscription will not be successful, and you will enter the login interface of the FLOWHUB platform. If you already have an account, you can log in to the platform directly with the account password. If you do not have an account, click "sign up" to complete the registration according to the instructions.

   <img src="https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step2.png" width="400" alt="step2" />

+ Step3：Login to the platform, enter the FLOWHUB standard pipeline subscription interface again, click "subscribe" once more, proceed with the subscription, and click "Sure" to complete the subscription.
  ![step3](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step3.png)

+ Step4：After completing the subscription, enter the Community-Subscribe Manage interface, add the corresponding standard process to the platform project, follow the instructions, and click "Sure" to create a new project.
  ![step4](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step4.png)
+ Step5：Complete the new project creation according to the instructions.
  ![step5](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step5.png)
+ Step6：After completing the creation of the new project, follow the instructions to add a flow again and enter the newly created project.
  ![step6](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step6.png)
+ Step7：After successful addition, click on "PROJECT" in the upper right corner to display the project list and quickly access the project where the flow is located.
  ![step7](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step7.png)
+ Step8：Upon entering the project, upload the data file that needs to be processed in the "Files" section. Then, navigate to the job and click on "Create Job" to create a task.
  ![step8](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step8.png)
+ Step9：Click on "Choose Flow" and follow the instructions to select the flow. Then, click on "Next Step" to proceed with the selection of input files.
  ![step9](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step9.png)
+ Step10：
1. Specify the root directory for all output files of the task in the "Output folder" field.
2. In the "Input File" section, select the input file based on the endpoint name.
3. In the "Output File" section, rename the output file that needs to be labeled.
   ![step10-1](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step10-1.png)
4. Check the tools used within the job and make personalized parameter adjustments, such as CPU/GPU settings. If executing the standardization process, no changes are needed.
   ![step10-2](https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/tutoral-step10-2.png)
+ Step11：Once the settings are completed, follow the instructions to submit the job and wait for the computation results. For detailed instructions, please refer to the tutorial.``[https://doc.flowhub.com.cn/en/](https://doc.flowhub.com.cn/en/)。


### Introduction to Fowhub Platform

FlowHub is an innovative cloud-based workflow platform that offers users comprehensive and powerful functionalities. It serves not only as a reliable data management platform but also as a flexible tool development platform, efficient workflow construction platform, intelligent task scheduling platform, and intuitive data visualization platform.

As a data management platform, FlowHub provides robust data storage and processing capabilities, allowing users to securely store and manage various types of data. Through an intuitive interface and user-friendly tools, users can easily perform operations such as data manipulation, import/export, and comprehensive data management.

As a tool development platform, FlowHub offers a rich set of development tools and interfaces, enabling users to customize and extend the platform's functionalities. Users can utilize their preferred programming languages and technologies to develop and integrate various tools, plugins, and extensions to meet their specific needs.

Workflow construction is one of the core features of FlowHub. It provides a visual and intuitive graphical interface that allows users to design and build workflows in a visual manner. Through simple drag-and-drop operations, users can connect different tasks and operations to create complete workflows. This graphical approach not only enhances work efficiency but also reduces the probability of errors.

Task scheduling is another important feature of FlowHub, as it intelligently manages and schedules task execution. Users can set task priorities, dependencies, and scheduling rules, and FlowHub will automatically arrange task execution order and timing based on these settings to ensure the smooth progression of the workflow.

In addition, FlowHub provides powerful data visualization capabilities. Users can transform complex data into understandable and analyzable forms through intuitive charts, graphs, and reports. This enables users to better understand the data, discover potential patterns and trends, and make informed decisions based on the data.

In summary, FlowHub is a feature-rich, user-friendly, and powerful workflow cloud platform that provides comprehensive data management, tool development, workflow construction, task scheduling, and data visualization capabilities. It helps users efficiently handle and analyze data, enhance work efficiency, and improve decision-making abilities.

### To contact us, please use the following contact information:

email: flowhub_team@flowhub.com.cn

Phone: (+86)17399981010

Wechat:

<img src="https://github.com/flowhub-team/WholeGenomeSequencing/blob/main/asset/wechat.jpg" width="250" alt="add my wechat">
