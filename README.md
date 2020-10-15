# Mobile App: Directing customers to subscription and identify most important drivers
Design a predictive model identifying users likely to subcribe or not allowing to focus marketing ressources to increase conversion

# Problem Statement

The project uses activity log from users testing a mobile app.
Mobile App often offers a freemium service to attract users and expects to convert to premium paid versions offering higher value services.
How to determine which users will switch and subscribe ?
Marketing can benefit significantly from being able to identify those who will most likely NOT switch from those that will. Indeed, this allows to focus marketing efforts on the users most likely NOT to convert as the others will anyhow. This allows to optimize the customer acquisition effort and reduce marketing / promotion expenses. It also allows to generate a ROI on the predictive tool through increased subscription.

# Business Case

Release of an App with a fremium version having some premium features unlocked.
Upon App installation, the user is offered a 24h trial with the full version.
Behavioral data (usage log) is collected when the App is used and the objective is to use this log to determine the users most likely NOT to convert.
- which are the key decision drivers?
- what is the accuracy of such a predictive model?

# Behavioral data (usage log)

The log is composed of screens visited by the user, whether he tried premium features, the minigame available on the app, whether he liked or not the app, etc...
The log provides the first 24hrs of the app covering the free trial.
Additional information in the dataset is:
- the user subscribed or not
This is the label for our predictive model. 0 = not engaged, 1 = engaged (subscribed)

# Steps
- Data exploration
- Data pre-processing
- Train the model
- Anayze and interpret results
- Evaluate predictive performance of the model
- Use information generated by the model to identify potential improvement areas for the App

# Results
The model is able to predict subscription with 76% accuracy.
The model allows to flag users who will most likely NOT subscribe, offering Marketing to target them with special offers and discounts and increase the subscription ratio.
The model allows to identify the most important variables to either positively or negatively influence the conversion.

