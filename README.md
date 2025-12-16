# DL4OpticalEngineering
Curated academic resources on deep learning for optical system design and assembly.

## Deep Learning for Optical Engineering
This repository accompanies the topical review
“Deep Learning across Optical System Workflow: A Comprehensive Review from Design to Assembly”.
It provides a curated list of references and links to publicly available resources relevant to deep learning for optical system design and assembly.
## Notes on links and updates
Links are provided when a public resource is available. This repository is intended as a living academic resource and will be updated periodically as new works appear. If you notice missing or outdated links, please open an issue or submit a pull request.

# Method summaries
## Starting Point Generation (SPG)
Starting Point Generation methods aim to assist optical designers by learning mappings from system specifications to initial optical design structures or prescriptions. These approaches are primarily used to accelerate early stage optical design, where the selection of a suitable starting point strongly influences convergence and final performance. Existing SPG methods cover spherical, aspheric, and freeform optical surfaces, and typically rely on supervised learning using reference designs optimized with commercial optical design software. More recent works incorporate unsupervised or hybrid learning strategies based on differentiable ray tracing and optics aware loss functions, reducing the reliance on labeled datasets. Applications of SPG networks include freeform imaging systems, microscope objectives, illumination optics, and compact off axis imaging configurations.
## End to End co design (E2E)
End to End co design methods jointly optimize optical elements and computational processing within a single learning framework. These approaches embed differentiable imaging models into neural network training loops, enabling gradients to propagate from image based or task driven objectives back to optical parameters. Learnable optical variables include lens curvatures, thicknesses, aspheric coefficients, diffractive phase profiles, and metasurface patterns. Forward models commonly rely on differentiable point spread function computation, wave optics simulation, or rendering based image synthesis. E2E methods are widely applied in computational imaging tasks such as depth sensing, extended depth of field imaging, hyperspectral imaging, super resolution, and task specific vision problems, where optical and algorithmic components are optimized together to meet system level performance goals.
## Optical Active Alignment (OAA)
Optical Active Alignment methods focus on bridging simulation and hardware realization by learning to infer fabrication or alignment errors from optical measurements acquired during assembly. These methods use neural networks to map measured features, such as wavefront error coefficients, point spread function images, or beam patterns, to misalignment states or correction commands. Depending on the feature modality, multilayer perceptrons or convolutional neural networks are commonly employed. OAA approaches are applied to a wide range of systems, including telescopes, camera lenses, micro optics, and multi element imaging assemblies, enabling faster and more accurate alignment compared to traditional iterative procedures. By integrating learning based prediction with physical alignment processes, OAA methods support improved manufacturing efficiency and robustness.

