### Client Engineering: LLMs Test Exercises

#### Exercise 1 - Text Cleaning

Process the provided text samples by:
- Remove URLs from the text: "Join here https://xyz.com/a/b to attend the session!"
- Remove alphanumeric words from the text: "Hello Mike745 how you doin?"
- Remove words starting with '#' character: "The journey is illuminated by the convergence of strategic insights and pragmatic execution #technology #artificialintelligence #datascience"
- Splits alphanumeric words into digits and text: "There will be 5adults and 2kids."

#### Exercise 2 - Summarization 
Use the text.csv file from the /data folder and summarize 3 of the stories using a model/technique of your choice

#### Exercise 3 - Performance
Compare the summarized output of the article from /data and calculate the precision (BLEU score or alternative implementation) taken into consideration the reference summary (summary-1-flan-ul2--article1) and the candidate summary (summary-2-flan-ul2--article1)

#### Exercise 4 - Classification
Use the provided Pytorch model from the /model folder and classify 10 texts from the given data.

**NOTE**:
- You can provide your input within a Jupyter notebook containing the cells' output. Don't forget to be creative as much as you want in the provided time.
- Please don't fork this repo.
