# Sentiment Analysis on 515K Hotel Reviews

Team member:
- Xin Qu xinq2@illinois.edu, responsible for data processing (stemming, tokenization, removing stop words), classifier evaluations,
sentiment analysis. 
- Biruo Zhao biruoz2@illinois.edu, responsible for paper presentation and degbug. 

## About the data

The original dataset is available [515K-hotel-reviews](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe),
also available under **/data/Hotel_Reviews.csv**. 

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

1. Download all the files in **data** folder to a local folder. 
2. Download the 5 **.ipynb** files and save them in the same folder as all the data files stay in step 1. 
3. Run **.ipynb** file as the follwong order: run **"data_process.ipynb"** first, then **"aspect_analysis_data_prcocess.ipynb"**, 
thirdly **"aspect_analysis.ipynb"**, the last **"reviewer_score.ipynb"**. Open each .ipynb in Jupyter notebook, click run all 
cells. It may take **long** time (sevral hours) to run "data_process.ipynb". 
4. Since it takes long time to run all the cells, **test_case.ipynb** provides the three applications discussed in project 
report (available under **/paper presentation/Project Report.pdf** with less time consuming. 

## Paper work

All paper work could be found under **/paper presentation**, including project proposal, technology review proposal and project 
report. See **project report** for details. 

