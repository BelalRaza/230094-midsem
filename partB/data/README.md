# Dataset Information

The datasets used in this project are dynamically loaded through scikit-learn's built-in dataset generators. No manual downloading of CSV or raw text files is required.

## make_circles
*   **Used in:** `task_2_1.ipynb`, `task_2_2.ipynb`, `task_2_3.ipynb`, `task_3_1.ipynb`
*   **Source:** `sklearn.datasets.make_circles`
*   **Description:** A classic toy dataset generating a large circle containing a smaller circle in 2D space. It is specifically chosen because it is inseparable by standard linear classifiers but perfectly separable by the degree-2 polynomial mappings discussed in the reproduced paper.
*   **Obtaining:** The notebook cells automatically generate the dataset via the Python API.

## make_moons
*   **Used in:** `task_3_2.ipynb`
*   **Source:** `sklearn.datasets.make_moons`
*   **Description:** Generates two interleaving half circles (S-curve topology). This dataset is specifically selected to illustrate the structural failure mode (Task 3.2) of a strict degree-2 explicit polynomial mapping, as the topological complexity heavily exceeds simple conic geometries.
*   **Obtaining:** Programmatically generated at runtime by the notebooks.
