ML - Flow Tutorial https://www.youtube.com/watch?v=GlvgqliaQaA&t=1s

This is used for experiment tracking 

We have various process such as:
    1) Pre-Processing
    2) Feature Engineernig 
    3) Model Training
    4) Parameter Tuning

And within each of these we have different Techniques or methods and we dont know which one is the correct or the best one , so for that we need to note all the methods and the results and for that we need to keep track of the experiments and for that we use ML-Flow

DVC VS ML-Ops:
    Use DVC for data versioning + pipeline stages.
    Use MLflow for tracking metrics, parameters, and registering models.

|   **Component**          | **MLflow**                                      | **DVC**                                        |
|------------------------|-------------------------------------------------|------------------------------------------------|
| **Experiment Tracking** | ✅ Parameters, metrics, artifacts, UI            | ⚠️ Not primary; can track manually             |
| **Model Versioning**   | ✅ With built-in model registry                  | ✅ Uses Git + remote storage                   |
| **Data Versioning**    | ⚠️ Minimal (log artifacts only)                  | ✅ Core feature                                |
| **Pipeline Management**| 🟡 Limited (with MLflow Projects)                | ✅ Strong DAG-based pipeline support           |
| **Storage Backend**    | File system, S3, GCS, etc.                       | Any cloud remote + Git                         |
| **Integration with Git**| ❌ Not tightly coupled (Works independent)      | ✅ Strong Git integration                      |


