# Youtube Data Analysis

# Introduction

Youtube uses a variety of metrics to determine the most popular videos, including shares, likes, comments, views, and so on. The project delves deeply into these metrics and their various correlations.

# Data Context

This dataset contains information on the daily trending YouTube videos stretching over a couple of months. Up to 200 trending videos per day for the US, GB and CA areas (the USA, Great Britain and Canada respectively) are drilled down to find out the trends and metrics using which videos are trending on Youtube.

# Data Content

The data for each region is in a different file. The video's title, channel title, publish time, tags, number of views, number of likes, number of dislikes, description, and number of comments are included in the dataset. The region is used as a partition key to differentiate between the files and to retrieve the categories.

# Tech Stack

S3
Athena
Glue
Lambda
QuickSight
Cloudwatch
IAM
