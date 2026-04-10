## 1.Docker image
### Download image
link:`https://pan.baidu.com/s/1tRIVY8Z5GLRkdId6MSm2uQ?pwd=g52f` 

### Docker load and run

```
docker load -i ampliconcn.tar
docker run -d -p 8501:8501 --name ampliconcn --restart unless-stopped ampliconcn:latest
```

### Local search
link:`localhost:8501`


## 2.Download Files Description

### Genome Metadata
- **archaea_genome_info.zip**  
  Genome metadata for archaeal organisms, including taxonomy, assembly accession, genome size, and related genome information.

- **bacteria_genome_info.zip**  
  Genome metadata for bacterial organisms, including taxonomy, assembly accession, genome size, and related genome information.

- **fungi_genome_info.zip**  
  Genome metadata for fungal organisms, including taxonomy, assembly accession, genome size, and related genome information.


### rRNA Copy Number Summary
- **Genus_copy_summary.zip**  
  Summarizes rRNA gene copy numbers calculated from bacterial, archaeal, and fungal genomes at the genus level.

- **Species_copy_summary.zip**  
  Summarizes rRNA gene copy numbers calculated from bacterial, archaeal, and fungal genomes at the species level.


### Taxonomy Mapping Files
- **taxid_taxa_archaea.zip**  
  Mapping table between NCBI TaxID and archaeal taxonomy lineage.

- **taxid_taxa_bacteria.zip**  
  Mapping table between NCBI TaxID and bacterial taxonomy lineage.

- **taxid_taxa_fungi.zip**  
  Mapping table between NCBI TaxID and fungal taxonomy lineage.
