# Generative Adversarial Networks for Synthetic Node Expansion in MOF Material Graphs

## Overview
This project explores the use of **Generative Adversarial Networks (GANs)** for generating synthetic nodes within **MOFGalaxyNet**, a material graph representation for Metal-Organic Frameworks (MOFs). By leveraging deep learning techniques, we aim to expand MOF material networks by introducing synthetic nodes that correspond to novel MOFs with predicted properties and structures.

## Key Features
- **MOFGalaxyNet-Based Graph Representation**: The framework models MOFs as a structured graph where nodes represent existing MOFs, and edges denote similarities or relationships between them.
- **GAN-Powered Synthetic Node Generation**: A GAN-based model generates new nodes representing novel MOFs within the material graph.
- **Graph Expansion and Property Prediction**: The synthetic nodes are integrated into MOFGalaxyNet, allowing for property prediction and structural analysis.
- **Visualization and Evaluation**: Tools to assess and visualize the expanded MOFGalaxyNet with newly generated MOFs.

## Installation
To use this repository, install the required dependencies:

```bash
pip install torch networkx numpy matplotlib
```

## Usage
Run the main script to train the GAN and generate synthetic nodes:

```bash
python generate_synthetic_nodes.py
```

## Example Output
- Visualization of the expanded MOFGalaxyNet with synthetic MOFs.
- Feature representation of generated MOF nodes.

## Future Work
- Enhancing GAN architecture for more accurate MOF property prediction.
- Implementing edge prediction to establish relationships between generated and existing MOFs.
- Extending the approach to real-world MOF datasets for validation.

## Contributions
We welcome contributions! Feel free to submit issues and pull requests.

## License
This project is open-source and available under the MIT License.


