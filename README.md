# ProdNet 💻🦾
is a neural network framework designed to discover efficient matrix multiplication algorithms using machine learning, specifically through tensor decomposition techniques.

<img width="487" height="455" alt="image" src="https://github.com/user-attachments/assets/c3213613-8aa8-4b33-9272-18e88aa15abe" />
<img width="487" height="455" alt="image" src="https://github.com/user-attachments/assets/d5d0fa46-7e52-4213-a9f4-28dc80dc070c" />


# Research Objectives 🎯
The main objective of ProdNet is to automatically discover multiplication algorithms for a given matrix size under a fixed number of scalar multiplications. The aim is to reduce the number of required multiplications compared to traditional methods, thereby lowering computational complexity.
Importantly, the approach is designed to operate efficiently without requiring high-performance or supercomputing resources.

# Libraries 📚
- **Numpy:** used for data generation.
- **Pytorch:** used for data loading, model construction, and training
- **os:** used for handling file paths for saving models
- **Matplotlib:** used for visualization and plotting results.

# Results and Analysis 📋
- **Evaluation Metrics:** The quality of the discovered multiplication algorithm is assessed using Mean Squared Error (MSE) and regularization terms.
  In theory, a perfect solution would yield an MSE of exactly zero. However, due to numerical approximation limits in computer calculations, the MSE typically reaches extremely small values (on the order of 1e-15), which indicates a highly accurate solution.
- **Results:** The discovered algorithms for 2by2 and 3by3 matrices size are presented in the 5th ISPR international conference.  The link will be provided soon.

# Contributing 🤝
Contributions are welcome! You can experiment with the model and explore new matrix multiplication algorithms by adjusting a few key parameters:
- **Matrix Size (size):**  Modify the size variable to define the dimensions of the square matrices used in the experiment.
- **Number of Multiplications (mul):** Set the mul variable to control the number of scalar multiplications allowed in the discovered algorithm.
 
⚠️ Make sure that this number is strictly less than the number required by the standard matrix multiplication algorithm:
                                 (rows of matrix A)×(columns of matrix A)×(columns of matrix B)
- **Non-Square Matrices (Optional)**
You can extend the implementation to handle non-square matrices by:
  - Adjusting the data generation process
  - Modifying the model’s input and output dimensions accordingly

Feel free to open issues, suggest improvements, or submit pull requests to enhance the project 🚀

# Contact ✉️
• **Email:** wissambadia4@gmail.com

• **LinkedIn:** [Badia Ouissam Lakas](linkedin.com/in/badia-ouissam-lakas-a66a28214)   



