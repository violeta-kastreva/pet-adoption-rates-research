Pet Adoption Data Analysis
This project provides an in-depth analysis of pet adoption data, specifically focusing on cats and dogs. It utilizes data extracted from Petfinder.com API, which is a vast database of adoptable pets in the North America region.

The project uses Python and several data science libraries including pandas, seaborn, matplotlib, and nltk.

Project Structure
The project is divided into several sections, each focusing on a different aspect of the data:

Data Extraction: In this initial stage, data from Petfinder API is extracted, forming the raw dataset for this project.

Data Cleaning: After the extraction, the data undergoes cleaning processes, where unnecessary columns are removed and missing values are handled.

Basic Analysis: This section provides a basic analysis of the data, providing an understanding of the different variables in the dataset.

Adoptability Analysis: This section focuses on the time each pet stays on the site before being adopted. The adoptability is then analyzed based on the pet's age, breed, size, and gender.

Sentiment Analysis of Descriptions: The pet descriptions are analyzed to understand the sentiment of the language used. The sentiment score is then used to categorize the descriptions as positive, negative, or neutral.

Comparative Analysis of Cats and Dogs: This section provides a comparison between cats and dogs in terms of adoptability and sentiment scores.

Results
The project provides several interesting findings such as:

Younger pets are more likely to be adopted quickly compared to older ones.
Size of the pet has an influence on the adoption speed.
The breed of the pet does not significantly impact the speed of adoption.
The sentiment score of the description does not significantly affect the speed of adoption.
Please refer to the Jupyter notebook for detailed analysis and visualizations.

How to Run
Clone the repository.
Install the necessary Python packages. You can do this by running pip install -r requirements.txt in your terminal.
Open the Jupyter notebook.
