# Sentiment Analysis on 515K Hotel Reviews

Team member:
- Xin Qu xinq2@illinois.edu, responsible for data processing (stemming, tokenization, removing stop words), classifier evaluations,
sentiment analysis. 
- Biruo Zhao biruoz2@illinois.edu, responsible for paper presentation and degbug. 

## About the data

The original dataset is available [515K-hotel-reviews](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe),
also available [Hotel_Reviews.csv](https://drive.google.com/file/d/1U2ktXTsFn0GRaan1_LpyYGIH-9EYS-4c/view?usp=sharing). 

## Prerequistes

1. At least **python 2.6**. **Jupyter** notebook is uesd for this project. Information about [Jupyter notebook](https://jupyter.org/). 

2. Install useful library:

    2.1 **sklearn**
    
        <pip install -U scikit-learn>
    
    2.2 **nltk**
    
        < pip install -U nltk>
    
    2.3 **pandas** and **numpy**
    
    2.4 **folium** for geographical display
    
        <conda install -c conda-forge folium >
    
    2.5 **matplotlib** for data visualization
    
        <python -m pip install -U matplotlib>
    
## How to run

1. Download **data** file. 

    1.1 Download the original dataset [Hotel_Reviews](https://drive.google.com/file/d/1U2ktXTsFn0GRaan1_LpyYGIH-9EYS-4c/view?usp=sharing) to a local folder. 
    
    1.2 Download "stop_words.txt" in **data** folder in the same folder.
    
    (1.3 and 1.4 are **Optional**-these two optional large files are generated in "data_process.ipynb")
    
    1.3 Download "Filling_nans" pickle file from [Filling_nans](https://drive.google.com/file/d/1w-Mkkqi0js0v_f0JnPI1mWQByadL75xN/view?usp=sharing). 
    
    1.4 Download "text_df" pickle file from [text_df](https://drive.google.com/file/d/1UkbWJI5VYrLBxkclNnUuBSDMNZemIswC/view?usp=sharing).
    
2. Download the 5 **.ipynb** files and save them in the same folder as all the data files stay in step 1. 

3. Run **.ipynb** file as the follwong order: run **"data_process.ipynb"** first, then **"aspect_analysis_data_prcocess.ipynb"**, 
thirdly **"aspect_analysis.ipynb"**, the last **"reviewer_score.ipynb"**. Open each .ipynb in Jupyter notebook, click run all 
cells. It may take **long** time (sevral hours) to run "data_process.ipynb". 
Additional information: if skip running "data_process.ipynb", must download **"Filling_nans"** in **step 1.3**. 

## Test case presentation
Since it takes long time to run all the four mentioned .ipynb files, **test_case.ipynb** provides the three applications discussed in project report (available under **/paper presentation/Project Report.pdf** with less time consuming. Need to 
download all the files in **data** folder first. Open **test_case.ipynb**, click run all. 

## Paper work

All paper work could be found under **/paper presentation**, including project proposal, technology review proposal and project 
report. See **project report** for details. 

