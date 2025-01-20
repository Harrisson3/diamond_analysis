import pandas as pd
url = "https://raw.githubusercontent.com/Harrisson3/diamond_analysis/refs/heads/main/diamonds.csv"
diamonds_df = pd.read_csv(url)
diamonds_df.head(7)
