 *1. 3D Chromain interaction*

    1. 3DIV: https://www.kobic.kr/3div/hic
          
    2. http://epigenomegateway.wustl.edu/
      简介：WashU EpiGenome Browser，该数据库由圣路易斯华盛顿大学医学院的王艇教授小组（http://wang.wustl.edu/）创建维护。王艇教授的研究主要是通过干湿实验结合研究表观遗传调控机制，paper十分高产，此外还构建了UCSC Cancer Genomics Browser，绝对是大神级人物。相比于UCSCBrowser，WashU EpiGenome Browser在浏览表观遗传修饰数据中表现的更加专业，界面更加友好，容易上手学习，同时配色方案远优于UCSC；同时可以加载ENCDOE、RoadMap和用户自定义文件，实现数据的快速浏览比对
    
 *2. Enhancer databases*

       1. EnhancerAtlas: http://www.enhanceratlas.org/
       简介：Currently, the updated database contains 13,494,603 enhancers for 586 tissue/cell types. 
       
       2 EnhancerDB
       简介：该数据库包含了在41个组织/细胞系中共识别的116278个增强子，也包含了在VISTA和FANTOM5中增强子的数据（VISTA是由人和小鼠中经过实验验证的增强子组成的数据库，FANTOM5是通过双向转录RNA的测定，利用基因表达的cap分析来定义增强子的一个项目）。目前，数据库还包含了41个正常组织和细胞系中的490个TF，1726个miRNA，23334个基因和11381519个SNP。总共识别了131054581对TF-增强子，17059对增强子-miRNA和318993对增强子-基因的调控关系。此外，在41个组织/细胞系中发现了4039558对TF-miRNA和1059695对TF-基因的调控关系（数据源和流程详见于下图）。
       
 *3. Transcription factor databases*
 
       1. Jaspar
       2. HOCOMOCO
       3. Factorbook
       4. Animal TFDB3.0
       5. PlantTFDB (植物)
       
 *4. Ensemble plants (批量下载)
 
    rsync -av rsync://ftp.ensemblgenomes.org/all/pub/plants/current/fasta/*/pep/*pep.all.fa.gz ./
    rsync://ftp.ensembl.org/ensembl/pub/current_embl/
    rsync://ftp.ensemblgenomes.org/all/pub/protists/current/
    rsync://ftp.ensemblgenomes.org/all/pub/plants/current/
    rsync://ftp.ensemblgenomes.org/all/pub/fungi/current/
    rsync://ftp.ensemblgenomes.org/all/pub/metazoa/current/

*5. 拟南芥蛋白组、转录组
http://athena.proteomics.wzw.tum.de:5002/master_arabidopsisshiny/
