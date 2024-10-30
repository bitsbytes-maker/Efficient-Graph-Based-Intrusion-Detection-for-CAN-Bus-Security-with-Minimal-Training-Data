### Dataset and Dependencies

- **Dataset**: The dataset used for this project can be found [here](https://ocslab.hksecurity.net/Datasets/car-hacking-dataset).
- **Library**: All classification methods are implemented using the `scikit-learn` library. You can find more information and install instructions [here](https://scikit-learn.org/stable/).

### Data Preparation

To simplify the process, we have stored all CAN IDs in `allIDwithattackfree_can_fd.txt`, along with labels that specify whether each data point is from an attack or an attack-free instance in `allLabelwithattackfree_can_fd.txt`. These files are used as inputs for the analysis. You can make your input file accordingly.

### Output Storage

The output from each method is saved in `classifier_all_can_fd.csv`. You can make your output file accordingly.

### Instructions for Use

- **File Names**: When working with different versions or subsets of the car hacking dataset, **please update the filenames in the code** to match your desired input files. Ensure that any new or modified file paths are specified in the code.
- **Output File**: You may also adjust the name or location of the output file `classifier_all_can_fd.csv` to your preference. Modify the filename within the code to save the output as desired.
- **Dependencies**: All classification methods rely on the `scikit-learn` library. Ensure `scikit-learn` is installed to execute the code.
