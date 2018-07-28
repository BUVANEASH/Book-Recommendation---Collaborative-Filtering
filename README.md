# Book-Recommendation---Collaborative-Filtering
Book Recommendation System using SVD and KNN for User/Item based collaborative filtering

## Running the Book Recommendation

The program recommends books for a particular User based CF using singular-value decomposition (SVD) algorithm `--SVD` and recommends books related to a particular book based on CF using k-Nearest Neighbors algorithm `--KNN`

### Example

For recommendations for a particular user (by default SVD latent factor is set to 50). The output prints the books already rated by the user and then the recommendations

```
python main.py --SVD
```

For recommendations for a particular Item (by default K-Neighbors is set to 10). The output prints the Top K recommended books.

 ```
 python main.py --KNN
 ```
 
 If no arguements were passed, the top 10 books with mean highest ratings and top 10 books with the high ratings count.
 
 ```
 python main.py
 ```
 
 ## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
