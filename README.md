# ClusteredCF-MovieRec

This project implements **Collaborative Filtering combined with clustering methods** to improve movie recommendation accuracy and efficiency. The goal is to achieve **lower RMSE and MAE values** while **reducing computation time** compared to traditional collaborative filtering approaches.

The methodology is inspired by the research paper:

*Mark O’Connor & Jon Herlocker, 1999 – “Clustering Users for Collaborative Filtering”* (included in this repository as `Reference-Paper.pdf`).

## Dataset

We use the **MovieLens 25M Dataset**:

- Contains 25 million ratings across thousands of movies.  
- Provides a large-scale testbed for collaborative filtering and clustering methods.  
- Dataset link: [MovieLens 25M](https://grouplens.org/datasets/movielens/25m/)

## Clustering Algorithms Implemented

- **K-Means**  
- **Agglomerative Clustering**  
- **MiniBatch K-Means**

These methods replace older clustering approaches (hMetis, kMetis, Average Link, ROCK) while maintaining efficiency and scalability.

## Project Structure

````
ClusteredCF-MovieRec/
├── ClusteredCF-MovieRec.ipynb   # Main Jupyter notebook with code and experiments
├── data/                        # MovieLens dataset files (if included or downloaded)
├── Reference-Paper.pdf          # Research paper used as reference
├── Project-Report.pdf           # Detailed report of this project
├── requirements.txt             # Python dependencies
└── README.md
````


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ClusteredCF-MovieRec.git
   cd ClusteredCF-MovieRec


2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in **Jupyter** or **VS Code**:

   ```bash
   jupyter notebook ClusteredCF-MovieRec.ipynb
   ```
4. Run the notebook cells to reproduce results:

   * Load dataset
   * Apply clustering + collaborative filtering
   * Evaluate RMSE, MAE, and computation time

## PDFs Included

* **Reference-Paper.pdf** – Original research paper by Mark O’Connor & Jon Herlocker (1999).
* **Project-Report.pdf** – Detailed report explaining methodology, experiments, and results.

## Results

* Compare collaborative filtering **with vs. without clustering**.
* Analyze effects of different clustering algorithms on **accuracy and runtime**.
* The notebook reports RMSE, MAE, and execution time for each algorithm.

## Contributions

Contributions are welcome! You can:

* Report issues or bugs
* Suggest improvements
* Add new clustering or recommendation techniques

## License

This project is open-source and available under the **MIT License**.

---

Made with ❤️ to explore efficient movie recommendation techniques.
