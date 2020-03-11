## Kollectin platform introduction ##
Kollectin is your platform for fashion. Available both as both iOS and Android app, Kollectin houses virtual boutiques created by social media Style Stars, allowing you to experience fashion through their lenses, while giving you the chance to share your own looks, and create your own personal boutique from exclusive products.

## Job requirement ##
As an Android Developer in the Taipei office, your job is to take care of the entire Android development lifecycle, create, maintain, optimize, and publish all content to the Android platform, deliver a quality product and to ensure a pleasant user journey.

#### The simple following task is to test if the candidate has a solid understanding of how to structure a reliable and optimized application: ####

Please create a one screen application based on our current platform design. Here is a screen/media of how the final result looks:

![screen](https://github.com/Kollectin-Taiwan/KOLLECTIN_INTERVIEW_ANDROID/blob/master/android_interview_demo.gif "preview screen")

### To access Graphic materials ###
please visit figma (please sign up to see design in detail)
https://www.figma.com/file/UgIaxDGI4rTC44YrVQwK8g/For-Interview

### To access API ###
Please load only 10 items at the beginning when the screen launched, load more items (10 at a time) as user scroll to the end of the page.

Domain：https://interview-api.kollectin.com/apidocs/index.html

Parameters：
 1. sort：sort method, you can always set it to "pop".
 2. limit：number of items per page.
 3. pageNo：the page number you want to get.

**for example to get first page and 10 items per page:**
```
> curl -X GET "https://interview-api.kollectin.com/api/social/posts?sort=pop&limit=10&pageNo=1" -H "accept: application/json"
```

### Please create a new git and upload your entire Android/iOS project and share us the link for evaluation, Thank you! ###


