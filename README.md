# Free_To_Game_Project
**About the Dataset:**  

The dataset contains a total of 10 columns, described as follows:  

- **`title`**: The name of the game.  
- **`thumbnail`**: The URL of the game's thumbnail image.  
- **`short_description`**: A brief description of the game.  
- **`game_url`**: The URL of the game's main page.  
- **`genre`**: The genre of the game (e.g., MMORPG, Shooter, Action RPG, etc.).  
- **`platform`**: The platform on which the game is available (e.g., PC (Windows)).  
- **`publisher`**: The publisher of the game.  
- **`developer`**: The developer of the game.  
- **`release_date`**: The release date of the game.  
- **`freetogame_profile_url`**: The URL to the game's profile on FreeToGame.

## Project Steps:
**Data Loading:**  

In this section, the dataset will be loaded into Python using either the **`pandas`** library or the **`open`** function. Each row in the dataset represents information about a single game.  

1. **Loading Data into a DataFrame:**  
   - If the **`open`** function is used, ensure that the loaded data is converted into a **`pandas DataFrame`** for easier manipulation and analysis.  

2. **Data Summary and Missing Data:**  
   - Display a summary of the dataset to understand its structure (e.g., column data types, number of rows).  
   - Check for any missing data in the dataset and handle them appropriately.  

3. **Analyzing Game Trends by Platform:**  
   - Explore the distribution and trends of games released for different platforms (e.g., PC, mobile).  

4. **Analyzing Trends in Game Genres:**  
   - Study how game genres have evolved over time.  
   - Analyze these trends separately and also based on **`publisher`** and **`developer`**.  

5. **Finding Frequent Words in `short_description`:**  
   - Identify the most common words in the **`short_description`** column.  
   - Perform this analysis for the entire dataset as well as separately for each game genre.  

To access the data available on game profiles I used web scraping methods. 
