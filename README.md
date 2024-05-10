# PGD_KG_Schema
A knowledge graph model of performance-based generative design of sustainable buildings
# 1. Overview
This is the official repository of the paper *A knowledge-informed optimization framework for performance-based generative design of sustainable buildings* (https://doi.org/10.1016/j.apenergy.2024.123318). The repository provides the knowledge graph model of performance-based generative design of sustainable buildings (PGD-KG Schema).  

> Wu, Z., Wang, Z., Cheng, J. C., & Kwok, H. H. (2024). A knowledge-informed optimization framework for performance-based generative design of sustainable buildings. Applied Energy, 367, 123318.

The models are OWL files in Turtle syntax. You can view and edit them in OWL-supported tools such as Protégé.  
`schema_only_PGD_KG_model.owl` is the PGD-KG model with fundamental classes and properties. You can reuse the classes and properties to build your own models.  
`case1068_PGD_KG_model.owl` and `case6725_PGD_KG_model.owl` are two example models with enriched individuals in a design project.  
# 2. Graphs of the model
<div align="center">
  <img src="/image/overall_schema.png" height="80%" width="80%"><br>
  Fig. 1. PGD-KG Schema: Overall.<br>
  <br>
  <br>
  <br>
  <br>
  <img src="/image/building_domain.png" height="45%" width="45%"><br>
  Fig. 2. Building domain.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/site_building.png" height="70%" width="70%"><br>
  Fig. 3. Site and building.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/space.png" height="70%" width="70%"><br>
  Fig. 4. Space.  
  <br>
  <br>
  <br>
  <br>
   <img src="/image/building_surface.png" height="70%" width="70%"><br>
  Fig. 5. Building surface.<br>
  <br>
  <br>
   <img src="/image/fenestration_surface.png" height="70%" width="70%"><br>
  Fig. 6. Fenestration surface.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/shading.png" height="70%" width="70%"><br>
  Fig. 7. Shading surface.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/weather.png" height="70%" width="70%"><br>
  Fig. 8. Weather.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/airwall.png" height="50%" width="50%"><br>
  Fig. 9. Air wall.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/equipment.png" height="70%" width="70%"><br>
  Fig. 10. Electrical equipment.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/lighting.png" height="70%" width="70%"><br>
  Fig. 11. Lighting equipment.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/occupancy.png" height="70%" width="70%"><br>
  Fig. 12. Occupancy.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/HVAC.png" height="70%" width="70%"><br>
  Fig. 13. HVAC.<br>
  <br>
  <br>
  <br>
  <br>
   <img src="/image/compliance_checking.png" height="55%" width="55%"><br>
  Fig. 14. Compliance checking. 
</div>


## 3. Feedback
Any feedback or questions are welcome. Please feel free to contact [George Wu](mailto:zwubz@connect.ust.hk).

## 4. Citation  
If you use the ontology model and codes, please cite our paper as follows:  
```
@article{wu2023ontology,  
  title={An ontology-based framework for automatic building energy modeling with thermal zoning},  
  author={Wu, Zhaoji and Cheng, Jack CP and Wang, Zhe and Kwok, Helen HL},  
  journal={Energy and Buildings},  
  pages={113267},  
  year={2023},  
  publisher={Elsevier}  
}
```
