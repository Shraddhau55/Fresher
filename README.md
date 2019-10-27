# Fresher


Contents :

model-export_icn_core_ml-applegoogle5-2019-10-27T11_07_37.327Z_model.mlmodel : model created using GCP's AutoML. Precision : 97%

AppleSeb.mlmodel : model created using Apple MLKit. Precision : 81%

iOS app : Folder contains XCode code to develop iOS app incorporating the above built models.

Output : Folder contains screenshots of the Fresher app at work.


INSPIRATION

The primary purpose of the Fresher is to detect how fresh a fruit or vegetable is and to do this, the user only has to rely on their smartphone. Often there is a need to find and buy fresh fruits. Users who are not familiar with finding fresh fruits by themselves have a hard time shopping and end up buying stale produces. Such an app will help such customer base in buying fresh veggies on the go!

Apart from serving individuals, the app can also be accumulated in serving as an inventory management tool for warehouses which store vegetables and fruits on larger scale. Often it is seen that warehouses depend on human labour to sort the fruits and vegetable stocks. The machines are not at all reliable here. And reliance on human labour leads to more time and is prone to error at the same time. Hence, with the help of a camera and our "FRESHER" technology we can solve this problem easily.

WHAT DID WE LEARN

When we initially started to plan the approach for this project, we only knew that we have to use an object detection model which should work smoothly wish phone camera and as well as with CCTV cameras. We explored many tools and services to achieve the same. Ranging from Tensorflow, Apple ML Kit, Azure and Google Cloud. We started slow, but we knew from the beginning what tools are we going to use.

Being a team of just two members, we already had a lot on our plates, in the same time we never lost our faith in each other. We helped each other out, wherever the need be. Our understanding and teamwork helped both of us bring the best out of each other.

Whilst exploring various services offered by Google Cloud, we came to know about the advancement happening in each domain and how being a part of such an event is helping us shape ourselves for the future.

** HOW DID WE BUILD**

_ Building the dataset _ We started with collecting images of apple. We referred to Kaggle for it. To build a dataset with rotten apples, was a trick for us. When internet couldn't help us, we went back to San Francisco to our friends place to collect pictures of rotten and damaged apples. Later, With more than 500 images our dataset of fresh and stale apple was created.

_ Building the model _

After trying our hands on Google Vision and Apple MLKit, we started to explore AutoML. With review from the Google team and mentors at the venue, we went forward with AutoML. After a session of research and understanding how it works, we were able to wrap our hands around this technology and started the training process with the dataset we had created. We built and rebuilt the whole model more than 10 times to achieve perfection.

_ App for the project _

Now, the model was ready. We wanted a souce device to use it. Looking at a user persona, we decided to use this model in a mobile app. With our previous little experience in iOS app development and Google Cloud offering to use the model in Apple MLKit, we made a basic app which uses our "Fresher" model. The app is deployed on iOS smartphones right now and currently we are working on android.

** Challenges we faced **

We faced many challenges, these were, Wrapping our head around AutoML. Trying AutoML for the first time, we had issues developing it's model. Due to some reasons, our models used to take more than 5 hours to train around 60 images. We lost a lot of our time due to the same. With help of team Google and our research, we managed to carb down this issue by choosing more efficient dataset. After spending a good amount of time on building and training model, we did not have much time and man-power to develop a proper mobile app. But we did a fine job making a basic app for the same. One of our biggest challenges was to bring our prediction rate from 81% to 99%. We did this by playing around with our datasets. We even travelled miles to take photos to make our dataset perfect for such a less amount of pictures.

At the end, we are happy that we did train our model to detect freshness of apple in 5 stages.

Best apple

Good apple

Okay apple

Bad apple &

Worst apple.

A BIG CHEER TO OUR TEAM!
