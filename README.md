### **Google AI Runtime: Fast or Slow? Let's Predict! 🚀**

Ever wondered how fast an AI model will run before you even deploy it? That's the super cool challenge we tackled in this project! We're talking about predicting the runtime of AI models (represented as graphs!) on Google's Tensor Processing Units (TPUs). It's like trying to guess how fast a new car will go just by looking at its blueprints and engine settings. Pretty neat, right?

#### **Our Mission: Speed Up AI! 💨**

The big goal here is to help optimize AI models by finding the best configurations that make them run super fast. This means diving deep into how compilers transform these AI "graphs" for peak performance.

#### **The Data: TpuGraphs! 📊**

We used a special dataset called `TpuGraphs`. It's packed with info about XLA HLO graphs and how they perform on TPUs. This dataset has two main flavors:
*   **`layout` collections:** For these, we're all about ranking! We want to see how well our predictions match the actual runtime rankings.
*   **`tile` collection:** Here, it's about minimizing "slowdown." The closer to 1, the better!

#### **Our Secret Sauce (aka Tech Stack) 🛠️**

*   **Python:** Our go-to language for all things data.
*   **Pandas & NumPy:** For crunching those numbers and wrangling data.
*   **TensorFlow:** The powerhouse for building and running AI models.
*   **Jupyter Notebook:** Where all the magic happens, from exploration to prediction.

#### **Want to Predict the Future of AI? 🔮**

1.  **Clone the repo:**
    ```bash
    git clone https://github.com/jackren0000/Google---Fast-or-Slow-Predict-AI-Model-Runtime.git
    ```
2.  **Install the libraries:**
    ```bash
    pip install pandas numpy tensorflow jupyter
    ```
3.  **Run the notebook:**
    ```bash
    jupyter notebook googleairuntimecomp.ipynb
    ```