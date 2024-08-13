# awesome-vlm-inference-strategies
A curated list of inference strategies and algorithms that boost Vision Language Model (VLM) performance.

Paper suggestions, including self-promotion, are more than welcome.

# Papers

[Scaffolding Coordinates to Promote Vision-Language Coordination in Large Multi-Modal Models](https://arxiv.org/abs/2402.12058)

Proposes Scaffold prompting that scaffolds coordinates to promote vision-language coordination. Specifically, Scaffold overlays a dot matrix within the image as visual information anchors and leverages multi-dimensional coordinates as textual positional references. Extensive experiments on a wide range of challenging vision-language tasks demonstrate the superiority of Scaffold over GPT-4V with the textual CoT prompting.


[Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models](https://arxiv.org/abs/2406.09403)

Introduces Sketchpad, a framework that gives multimodal LMs a visual sketchpad and tools to draw on the sketchpad. The LM conducts planning and reasoning according to the visual artifacts it has drawn. Sketchpad enables LMs to draw with lines, boxes, marks, etc., which is closer to human sketching and better facilitates reasoning. Sketchpad can also use specialist vision models during the sketching process (e.g., draw bounding boxes with object detection models, draw masks with segmentation models), to further enhance visual perception and reasoning. GPT-4o with Sketchpad sets a new state of the art on all tasks


[Contrastive Region Guidance: Improving Grounding in Vision-Language Models without Training](https://arxiv.org/abs/2403.02325)

Introduces Contrastive Region Guidance (CRG), a training-free guidance method that enables open-source VLMs to respond to visual prompts. CRG contrasts model outputs produced with and without visual prompts, factoring out biases revealed by the model when answering without the information required to produce a correct answer (i.e., the model's prior). CRG achieves substantial improvements in a wide variety of VL tasks: When region annotations are provided, CRG increases absolute accuracy by up to 11.1% on ViP-Bench, a collection of six diverse region-based tasks such as recognition, math, and object relationship reasoning. 
