# Architectural Specification: Text Cubes Matrix Protocol

This document defines the mathematical, spatial, and logical parameters of the Text Cubes modular testing environment. It serves as the baseline technical reference for programming Computer Vision (CV) tracking models and robotic manipulation paths.

---

## 1. Spatial Geometry & Coordinate System

The Text Cubes environment operates on a strict, rigid rectangular grid. Every individual physical unit is an identical isotropic cube designed to prevent spatial entropy.

* **Dimensional Precision:** All physical modules adhere to a uniform X=Y=Z ratio.
* **Orientation Anchor:** The 6th surface of each module features an asymmetrical, high-contrast proprietary glyph (the creator logo). This surface serves as:
  1. The absolute spatial orientation vector (0,0,0) for external cameras.
  2. The standardized physical contact zone for vacuum or mechanical robotic grippers.
* **Surface Modularity:** The remaining 5 surfaces contain deep, high-contrast geometric indentations (semi-circular grooved channels) that form the core stroke database.

---

## 2. Typographic Disruption & Generative Logic

Text Cubes intentionally shifts typography from historical continuous-line characters to an uncompressed, quantized matrix. This method introduces a set of new conventions that optimize machine readability while expanding visual perspective.

### Overriding Traditional Linguistic Standards:
1. **Directional Invariance:** Text layers are fully bi-directional. The system natively supports classic horizontal flows, strict top-to-bottom vertical typography, and inverted/rotated layouts.
2. **Deterministic Hyphenation:** Traditional word-break structures are abandoned. Line transitions and text splits occur strictly when the physical matrix boundary is reached. The continuity of meaning is preserved via structural adjacency, not typographic symbols.
3. **Optimized Tokenization:** Complex alphabetic glyphs are reduced to their minimal non-redundant geometric components. Instead of memorizing thousands of independent font contours, AI agents only need to evaluate the presence and intersection of 5 primitive stroke topologies per cell.

---

## 3. Computer Vision & CV-Agent Training Protocol

Standard OCR algorithms fail when encountering Text Cubes because they expect curved baselines and predictable kerning. To train a vision agent or build a real-time Digital Twin using external cameras, the following pipeline must be implemented:

```text
[Raw Video Stream] 
       │
       ▼
[Edge Node Filtering] ──> High-Contrast Thresholding (Binarization)
       │
       ▼
[Grid Segmentation]   ──> Detect Rectangular Boundaries & Scale Baseline
       │
       ▼
[Anchor Verification] ──> Locate 6th-Side Glyphs for Rotational Alignment
       │
       ▼
[Primitive Mapping]   ──> Classify Stroke Types Across the 5-Primitive Database
       │
       ▼
[Text Synthesis]      ──> Decouple Matrix Layout into Pure Algorithmic Text
```

### Calibration Rules for Camera Arrays:
* **The Inversion Principle:** The vision model must process both positive and negative (inverted) spaces with equal weight. For example, solid black strokes on a white polymer substrate and white channels on an dark acrylic block share identical topological meaning.
* **Segmentation Over Correction:** The agent must never attempt to "correct" the text back into traditional typographic fonts. It must register the layout as a native rectangular dataset, evaluating the structural intersections without filtering out intentional line breaks or vertical rotations.
