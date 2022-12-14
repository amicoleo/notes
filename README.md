# SETUP

Run locally
```
bundle exec jekyll serve
```

Open CMS GUI available at `https://localhost:4000/admin/`

# USAGE
- Add images in 'assets' folder and link them like this `{% include picture name="NAMEIMAGE.png" %}`


## Social Image
- On the post.html layout, set *generateSocialImage = true* 
- Reloadl the page
- Tweak size and padding as needed
- On Chrome, inspect element, right click on the body element, and press "capture node screenshot"
- Save it on assets/nameSocialImage.png
- Write the image name in the blog post header, on the *socialImage* tag
- Remember to set *generateSocialImage = false* 
