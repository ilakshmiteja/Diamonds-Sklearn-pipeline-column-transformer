# Diamonds-Sklearn-pipeline-column-transformer
Implementing Sci-kit learn Pipeline and Column transformer on Diamonds dataset

When we need to apply different preprocessing techniques across the independent variables, we go for column transformer. However, column transformer perform transform operations paralelly. This causes in inefficient transformation of the columns. Hence, we go for sklearn piepline where transformation happens serially. To achieve our desired transformations, we combine column transforamtion and pipeline techniques.
