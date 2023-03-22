# MooMu
Mood Based Music Recommendation System

MooMu is a machine learning-based project that predicts a user's mood based on multiple behavioral attributes. The attributes include the time spent on various apps, the number of times a smartphone is lifted, location data, content browsed, and data from voice assistants.

This project uses the data collected from these attributes to build a model that predicts the user's mood. The predicted mood can then be used to recommend music via push notifications or provide shopping recommendations.

For example, if the user is predicted to be in a happy mood, MooMu could recommend upbeat music or suggest products that are associated with happy moods, such as bright colors and positive affirmations. MooMu can also help delivery apps like Uber Eats and DoorDash to make more money by recommending mouth-watering delicacies based on the user's mood, which can encourage them to make an order.

Overall, MooMu can help businesses to provide personalized recommendations based on the user's mood, which can enhance the user experience and increase revenue. Additionally, it can help individuals to better understand their moods and behaviors and make informed decisions about their daily lives.

PROJECT:
In this project of three students, three different models were created for three different datasets - one to predict mood based on gyroscope readings, another to predict mood based on voice, and the one that I worked on to predict mood based on Google search history. To achieve this, I found a dataset that had a sentiment attached to each data of browsing history.

To process the data, I used Convolutional Neural Networks (CNN) to predict the sentiment of the browsing history and SVC using Word2Vec. CNN is a deep learning model that is commonly used for image classification tasks, but it can also be used for text classification tasks.

After processing the data with CNN, the accuracy attained by the model was 89%.

After obtaining the emotions from all three models, a scale was created to combine these three emotions to predict a final emotion. The final emotion can be used to predict a suitable song for the user.

This approach can be particularly useful in creating personalized music playlists for individuals based on their mood. For example, if the user is feeling happy, the algorithm could suggest songs with upbeat tempos and positive lyrics. On the other hand, if the user is feeling sad, the algorithm could suggest songs with slower tempos and melancholic lyrics.

