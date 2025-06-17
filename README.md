# Harris Detector and SIFT Matcher

This repository contains a project focused on analyzing, implementing, and testing two distinct methods for image feature extraction and matching: the Harris Detector with Normalized Cross-Correlation (NCC) and the Scale-Invariant Feature Transform (SIFT) Matcher. The initial objective is to evaluate these methods in general scenarios to determine their comparative performance. Subsequently, the superior method will be applied to locate specific regions within a satellite image.

## Repository Content

1. **`Image_feature_extraction_and_matching.pdf`**  
   A detailed report is provided, encompassing an analysis of each method, their respective implementations, and the resulting matches. The report also includes a comparative analysis between the methods, along with additional insights.

2. **`harris2.py`**  
   A Python script implementing the Harris Corner Detector.

3. **`TestHarrisCorners.ipynb`**  
   A Jupyter Notebook for testing corner extraction using the Harris Corner Detector.
   
4. **`TestHarrisMatches.ipynb`**  
   A Jupyter Notebook for testing the matching of similar features (Harris corners) between two images.

5. **`SIFT_matcher.ipynb`**  
   A Jupyter Notebook containing the implementation of the SIFT Matcher and tests for matching similar features between two images.

## Suggested Workflow

For a better understanding, it is recommended to first read the **report** to get an overview of the project and then proceed to explore and run the **code**.
