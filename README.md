# Locate-Anything-Demo
This project evaluates NVIDIA’s LocateAnything-3B, a vision-language grounding model that locates objects in images using natural-language prompts. It was tested on street, office, grocery store, and clothing store scenes with different levels of visual complexity.

# Experiments
The evaluation included:
- Multi-category object detection
- Dense-scene detection
- Broad and refined phrase grounding
- Image cropping and prompt refinement
- Bounding-box visualization
  
Workflow
- Load the model and test image
- Enter a natural-language prompt
- Run inference
- Extract the predicted bounding boxes
- Display the results as visual annotations
  
Key Findings
Performance was affected by scene complexity, object size, prompt wording, image cropping, and GPU-memory limits. More specific prompts and focused image regions generally improved detection in crowded scenes.
