# AI Royalties
An IP framework to compensate artists and IP-holders for AI-generated content

### Abstract
This article investigates how AI-generated content can disrupt central revenue streams of the creative industries, in particular the collection of dividends from intellectual property (IP) rights. It reviews the IP and copyright questions related to the input and output of generative AI systems. A systematic method is proposed to assess whether AI-generated outputs, especially images, violate previous copyrights, using a CLIP metric between images against historical
copyright rulings. An examination (economic and technical feasibility) of previously proposed compensation frameworks reveals their financial implications for creatives and IP holders. Lastly, we propose a novel IP framework for compensation of artists and IP holders based on their published ``licensed AIs'' as a new medium and asset from which to collect AI royalties.


### Copyright Infringement Metric
Any metric to measure whether or not a new image constitutes sufficient transformation for fair use or violates previous copyrights must: 
* Identify identical images beyond formats, aspect ratios, or indistinguishable pixel alterations
* Identify transformed images of a same work or subject 
* Identify different images referencing identical subjects 
* Integrate the subjective elements of precedent jury's decisions and court rulings

Because they combine technical dimensions with subjective social aspects, the metric most go beyond pure visual analysis of the images.
We propose an AI metric combining pixel processing of images with contextual language. One such metric that has recently come to prominence is CLIP. [CLIP models](https://arxiv.org/pdf/2103.00020.pdf)<sup>1</sup> are a family of image understanding models that were made freely available by different research organizations such as OpenAI, Stability.AI, and others. 
Because CLIP models are trained to recognize the similarity between an image and a caption, they combine elements of language and visual intelligence of image that could be repurposed to assess the level of transformation an original image has undergone, and interpret it in light of precedent copyright rulings.

### Dataset of Images in United States Fair Use Rulings
We assessed previous copyright rulings in the U.S., constituting a list of over cases opposing an original work to a derivative one, and whether the transformation was considered fair use or copyright violation.

To find the rulings, we searched the [U.S. Copyright Office Fair Use Index Database](https://www.copyright.gov/fair-use/fair-index.html)<sup>2</sup> -- specifically selecting categories "photograph", "painting/drawing/graphic", and "film/audiovisual" while deselecting "parody/satire".
