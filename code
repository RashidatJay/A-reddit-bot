import config
#i created a config file where i entered my secret reddit key and client id so as to avoid having to display it.
reddit=praw.Reddit(
	client_id=config.client_id,
	client_secret=config.client_secret,
	user_agent='<terminal:com.Rjaybot:v0.0.1(by u/bluntblucher>)'
	)
print(reddit.read_only)
for submissions in reddit.subreddit('esports').hot(limit=10):
	print(submissions.title)
