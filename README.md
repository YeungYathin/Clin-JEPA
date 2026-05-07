                                                                                                                                                                                                      
# Clin-JEPA: A Multi-Phase Co-Training Framework for Joint-Embedding Predictive Pretraining on EHR Patient Trajectories
                                                                                                                                                                                    
Code repository for the paper *Clin-JEPA: A Multi-Phase Co-Training Framework for Joint-Embedding Predictive Pretraining on EHR Patient Trajectories*                                                              
(under review at NeurIPS 2026).                                                                                                                                                                     
                                                                                                                                                                                    
## Status
                                                                                                                                                                                    
The code release is in active preparation. The repository will be populated                                                                                                                         
with the following components shortly:
                                                                                                                                                                                    
- Encoder (Qwen3-8B + LoRA) and 92M-parameter latent trajectory predictor                                                                                                                           
- Multi-phase co-training pipeline (curriculum: warmup, co-training, alignment, hard sync, finalize)
- Evaluation scripts: rollout drift, latent geometry (UMAP), downstream probes                                                                                                                      
- Configuration files for all reported experiments                                                                                                                                                  
                                                                                                                                                                                    
## Data                                                                                                                                                                                             
                                                                                                                                                                                    
Experiments use MIMIC-IV (Johnson et al., 2023), accessed via PhysioNet under                                                                                                                       
credentialed access. Raw data is not redistributed in this repository.
                                                                                                                                                                                    
## License                                                      
                                                                                                                                                                                    
Code: MIT (upon release).                                       
