#README

#################################################################
#								#
# Multi-Source Social Feedback of Online News Feeds		#
# Nuno Moniz and Luís Torgo					#
# 								#
# The data set is made available under a CC-BY license		#
#								#
#################################################################

##################
# REFERENCE
# 
# Nuno Moniz and Luís Torgo (2018), “Multi-Source Social Feedback of Online News Feeds”,
# CoRR, abs/1801.07055
#
# @Article{Moniz2018,
#   title = {Multi-Source Social Feedback of Online News Feeds},
#   author = {Nuno Moniz and Lu\’is Torgo},
#   year = {2018},
#   ee = {https://arxiv.org/abs/1801.07055},
#   volume = {abs/1801.07055},
#   journal = {CoRR},
# }
# 
##################


This is a large data set of news items and their respective social feedback on multiple platforms: Facebook, Google+ and LinkedIn.
The collected data relates to a period of 8 months, between November 2015 and July 2016, accounting for about 100,000 news items on four different topics: economy, microsoft, obama and palestine.
This data set is tailored for evaluative comparisons in predictive analytics tasks, although allowing for tasks in other research areas such as topic detection and tracking, sentiment analysis in short text, first story detection or news recommendation. 

##################
#
# VARIABLES OF NEWS DATA
#
# IDLink (numeric): Unique identifier of news items
# Title (string): Title of the news item according to the official media sources
# Headline (string): Headline of the news item according to the official media sources
# Source (string): Original news outlet that published the news item
# Topic (string): Query topic used to obtain the items in the official media sources
# PublishDate (timestamp): Date and time of the news items' publication
# SentimentTitle (numeric): Sentiment score of the text in the news items' title
# SentimentHeadline (numeric): Sentiment score of the text in the news items' headline
# Facebook (numeric): Final value of the news items' popularity according to the social media source Facebook
# GooglePlus (numeric): Final value of the news items' popularity according to the social media source Google+
# LinkedIn (numeric): Final value of the news items' popularity according to the social media source LinkedIn
#
##################

