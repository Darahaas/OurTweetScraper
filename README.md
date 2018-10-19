# OurTweetScraper
Running several scrapy commands in parallel to yeild many tweets at a time. Better option to yeild most tweets in less time with appropriate fields, without the use of Twitter API.

*** INSTRUCTIONS ***

1. Run 'runme.sh' shell script with your favourite hashtags as the parameters.

2. Two files, namely, 'GenTweets.sh' and 'commands.sh' are generated.

3. Run the 'GenTweets.sh' shell script directly to generate the tweets.

4. Else, pick the commands of required combinations from 'commands.sh' and run them seperately. Compare 'GenTweets.sh' and 'commands.sh' to understand the difference.

NOTE1: n hashtags would generate 2^n commands which are either concatenated with '&' in 'GenCommands.sh' or written one in each line in 'commands.sh'
If you'd run 'GenCommands.sh' make sure that you limit the number of hashtags to not more than 5. It's a rough number, but it may vary with the different configurations.

NOTE2: To know the prerequisites and also more about the project which we've tweaked to yeild more number of tweets, read another README.txt inside TweetScraper dir.

*** MORE DOCUMENTATION WOULD BE PROVIDED AFTER FEW MORE UPDATES. KINDLY CO-OPERATE AND REACH US ON 15311A0572@sreenidhi.edu.in ***
