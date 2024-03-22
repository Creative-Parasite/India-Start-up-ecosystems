# 🗺️ India-Start-up-ecosystems
India's startup ecosystem has experienced a remarkable surge in funding in recent years, propelling it to become one of the most vibrant and dynamic in the world. This overview will provide insights into the funding landscape, highlighting the growth and potential of India's startup ecosystem.

 ### Features
 **1. Company brand** - The name of the company.
 
 **2. Sector** - The industry in which the company is in.
 
 **3. Headquarter** - Where the office is suited.
 
 **4. Founded** - The year in which the company was founded.
 
 **5. About company** - The purpose of the company.
 
 **6. Investors** - The investors interested in the startup companies.
 
 **7. Amount** - The amount of funds received by each startup.
 
 **8. Founder** - The owner of the company.
 
 **9. Series** - Refers to the stage in which startups are funded.
 
 **10. Year** - Refers to the year of amount funded.
 
## 🚗 Roadmap 
- Retrieve data from external sources
  
  -**Prerequistes**
  
  In order to run this project you need:
  
  . VS CODE
  
  . Python
   
    - **Clone repository:**
      clone this repository to your desired folder
      ```
      cd my-folder
      git clone https://github.com/Creative-Parasite/India-Start-up-ecosystems.git
      ```
    - **Project directory:** 
       ```
       cd my-project
      ```

    - **Create a virtual environment:**
        ```
        python -m venv env
        ```

  - **Activate the virtual environment:**
    ```
        env/Scripts/activate
    ```
  - **Import necessary libraries :**
    
     `import pandas as pd` , `import numpy as np`
- **EDA analysis** 
- **Data cleaning** 
- **Hypothesis testing** 
- **Business analysis**

## Usage
-To run the project do paste the clone to your VS CODE

- Use functions in the `notebook`
  
  **example:**
  
  def concat_dataframes(data1,data2, data3, data4):
    result = pd.concat([df1, df2, df3,df4], axis=0)
    return result
  
## 🔄 Optimization 
-- Refactor this function with your dataset index for optimal performance of the function.

-**Run the function once:**

def swap_row_cells(df, row_index, col1_index, col2_index):

    """
    Swaps the values in the given columns and row of a data array.
    Parameters:
    df (list): A 2D list representing the data array.
    row_index (int): The index of the first column.
    col1_index (int): The index of the second column.
    col2_index (int): The index of the row where the values are swapped.
    Returns:
    list: The modified data array with swapped values.
    """
    
    df.loc[row_index, [col1_index,col2_index]] = df.loc[row_index,[col2_index,col1_index]].values
    return df
    
## 🗳️ Contributions
Contributions are always welcome!

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Conclusion 🔥
Feel the fire, burn with rage. For india, funding is the fuel that thrives innovation, growth and evolution.

## 🤜 Acknowledgements

I would like to appreciate and thank my team members for making this project a success.

## Feedback

If you have any feedback, please reach out at kamurin@zohomail.com 

## 🦹‍♀️ Author
[@Creative-Parasite](https://github.com/Creative-Parasite)

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/evalyne-kamuri/)

