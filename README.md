# hse_hw3_chromhmm

# Коллаб с выполненными командами и доп заданием
https://colab.research.google.com/drive/1Cu9KvToZGRtDCHP1Q-YWKJQBV6YQlIbE?usp=sharing

# Гистоновые метки и файлы

| Гистоновая метка | файл | Ссылка |
| :---: | :---: | :---: |
| H2AFZ | wgEncodeBroadHistoneHmecH2azAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH2azAlnRep1.bam |
| H3K27ac | wgEncodeBroadHistoneHmecH3k27acStdAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k27acStdAlnRep1.bam |
| H3K27me3 | wgEncodeBroadHistoneHmecH3k27me3StdAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k27me3StdAlnRep1.bam |
| H3K36me3 | wgEncodeBroadHistoneHmecH3k36me3StdAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k36me3StdAlnRep1.bam |
| H3K4me1 | wgEncodeBroadHistoneHmecH3k4me1StdAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k4me1StdAlnRep1.bam |
| H3K4me2 | wgEncodeBroadHistoneHmecH3k4me2StdAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k4me2StdAlnRep1.bam |
| H3K4me3 | wgEncodeBroadHistoneHmecH3k4me3StdAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k4me3StdAlnRep1.bam |
| H3K79me2 | wgEncodeBroadHistoneHmecH3k79me2AlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k79me2AlnRep1.bam |
| H3K9ac | wgEncodeBroadHistoneHmecH3k9acStdAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k9acStdAlnRep1.bam |
| H3K9me3 | wgEncodeBroadHistoneHmecH3k09me3AlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecH3k09me3AlnRep1.bam |
| Control | wgEncodeBroadHistoneHmecControlStdAlnRep1.bam | http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHmecControlStdAlnRep1.bam |

# Картинки из CromHMM
| Emissions | Overlap | |
| :---: | :---: | :---: |
| ![emissions_10](https://user-images.githubusercontent.com/65420132/160288345-52c7507a-cafa-473e-87f6-1f28c758f61e.png) | ![HMEC_10_overlap](https://user-images.githubusercontent.com/65420132/160288414-e111bada-a349-4ad8-857d-1b29bd621b2f.png)
 | ![transitions_10](https://user-images.githubusercontent.com/65420132/160290869-08cf1daa-008c-491b-99b0-24a293aa0edc.png) | 


# Картинки из геномного браузера
![image](https://user-images.githubusercontent.com/65420132/160291117-7fcd2d83-258c-4fa6-b4ce-bb7bd80cbd02.png)
![image](https://user-images.githubusercontent.com/65420132/160291125-1b93e5e4-96a0-4ac7-a44b-e1fc0b01bb61.png)
![image](https://user-images.githubusercontent.com/65420132/160291132-1bc8607f-ed79-46fe-9f40-cb0653b77877.png)
  
# Анализ результатов
| Состояние | Название | Гистоновые метки | Расположение в геноме |
| :---: | :---: | :---: | :---: |
| 1 | Insulator | H3K4me2, H2AFZ, H3K4me3, H3K9ac, H3K27ac, H3K79me2 | CpGIslands, Exon, Tss, Tss2kb |
| 2 | Week promoter | H3K4me1, H3K4me2, H2AFZ, H3K4me3, H3K9ac |CpGIslands, Exon, Tss, Tss2kb |
| 3 | Week transckribet | H3K4me1 | TES |
| 4 | Promoter | H3K4me1, H3K4me2, H3K27ac | Laminb1lads |
| 5 | Transkriptional_transation | H3K4me1, H3K4me2, H3K79me2 | Gene, Tes |
| 6 | Transkriptional_elongation| H3K79me2 | Gene |
| 7 | Active_promoter | Cлабопредставлены: H3K36me3 | Gene, Tes |
| 8 | Strong_enhancer | Cлабопредставлены: H3K9me3 | Laminb1lads |
| 9 | Week_enhancer |  | Высокое содержание в геноме |
| 10 | Inactive_promoter | Cлабопредставлены: H3K27me3 | Laminb1lads |


# Результаты доп задания(Выполнение см коллаб)
![image](https://user-images.githubusercontent.com/65420132/160290827-5250be81-8e02-4481-9dcd-e8f122560c3b.png)

