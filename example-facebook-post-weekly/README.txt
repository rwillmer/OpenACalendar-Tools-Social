You need to set 3 variables inside the code:

1. MY_API_URL 	
- where do you get your calendar data?

2. MY_SITE_MSG  
- what do you want at the top of the message?

3. MY_GROUP_NAME 
- What's the name of the group on Facebook (needed to find the group-id)

and one environment variable:

4. FACEBOOK_ACCESS_TOKEN
- This is what grants you access for your code to post on your behalf.
- The quick'n'dirty way is to login at Facebook, and then in the same
  browser, go to https://developers.facebook.com/tools/explorer and create
  short-term token there by clicking 'get access token'.

  For this code, you need the 'user_groups' from the standard tab to get the
  group-id, and the 'publish-actions' from the extended to be able to post.

  By default, the token only lasts an hour, but there is a way to extend it 
  to 60 days. Will see if I can programmatically recreate it.

