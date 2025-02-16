# Visitor-prediction

<figure>
    <img 
    src="./img/banner.png" 
    alt='HdM X Stuttgart University'
    >
</figure>

**Project description:**

For the project in "Selected Topics in AI" we decided to make a visitor forecast for the BWI Library (Library of the Institute of Business Administration) at the University of Stuttgart.


In the BWI library the number of visitors is recorded daily (Monday - Friday). This is done in the form of "visitor statistics". In the visitor statistics the visitors are recorded in eight different time periods: `09:30`, `10:45`, `13:45`, `16:15`, `17:45`, `18:00`, `18:30` and `18:45`. Due to the library's opening hours (Mon. - Thurs. 09:00-19:00; Fri. 09:00 - 17:00), the last three time periods are not recorded on Fridays.


**Data:** Visitor statistics of the BWI library, which are available in analog form. Since the data is collected by hand on paper, the data has to be digitized for the first time. This is done by manually filling out a pre-generated Excel spreadsheet (see `data/dataset_creator.ipynb`).

**Goal:** The goal of this project and the AI model is to predict the number of visitors for the next day.

**Method:** To achieve the goal, an LSTM model is trained and tuned.

<figure>
    <img 
    src="./img/workflow.png" 
    width="700px"
    alt='Visitor Prediction Project Workflow'
    >
</figure>
<p>Source: own creation (Patryk Gadziomski)</p>
