# DNA_Analysis
Course project to read fastq DNA file data, which contains  and output a simplified fasta file: 
- Invalid DNA Record = Record it in RecordFormatException and don't write a Fasta Record
- Valid DNA Record that is not low quality = Write a Fasta Record
- Keeps reading records till the end of the fastq File

A new fasta file is created with only valid, high quality DNA records.
