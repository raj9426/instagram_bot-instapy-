# instagram_bot using " instapy "
But it's not working, can you guys fix it...??

it's showing this error:-

Traceback (most recent call last):
  File "c:/Users/shakthi raj/Desktop/insta follower python/insta_follower.py", line 16, in <module>        
    session.like_by_tags(['spacex','tesla','isro','mylyfmyrulz'], amount=10)
  File "C:\Users\shakthi raj\AppData\Local\Programs\Python\Python38-32\lib\site-packages\instapy\instapy.py", line 1957, in like_by_tags
    inappropriate, user_name, is_video, reason, scope = check_link(
  File "C:\Users\shakthi raj\AppData\Local\Programs\Python\Python38-32\lib\site-packages\instapy\like_util.py", line 633, in check_link
    media = post_page[0]["shortcode_media"]
KeyError: 0
