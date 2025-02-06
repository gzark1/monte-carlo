# Monte Carlo Dice Game Analysis

This project explores optimal decision-making in a dice-based game using Monte Carlo simulations and probability theory. The goal is to determine the best strategy for maximizing earnings by deciding when to stop rolling and keep a value. The exact game rules are explained in the `Overview` chapter of the Notebook.

We analyze different approaches:

* Probability threshold approach
* Dice number threshold approach
* Total expected earnings calculations (Monte Carlo vs. probability formula)
* The correlation between dice sides / total tries and the optimal threshold

## How to Open the Notebook

1. Create a Virtual Environment

```
python -m venv venv
```
2. Activate the Virtual Environment

    * Windows (Command Prompt):

    ```
    venv\Scripts\activate
    ```
    * Mac/Linux:

    ```
    source venv/bin/activate
    ```

3. Install Required Dependencies

```
pip install -r requirements.txt
```
4. Run Jupyter Notebook

```
jupyter notebook monte_carlo_dice_game.ipynb
```

This will open the notebook in your browser, where you can explore the analysis interactively.