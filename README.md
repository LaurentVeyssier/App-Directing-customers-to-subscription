# Mobile App: Directing customers to subscription and identify most important drivers
Design a predictive model identifying users likely to subcribe or not allowing to focus marketing ressources to increase conversion

# Problem Statement

Most mobile or digital App proposes a freemium service to attract users and expects to convert to premium paid versions offering higher value services.

How to determine which users will switch and subscribe ?

Marketing can benefit a lot from being able to identify the users who will most likely NOT switch from those that will. Indeed, this allows to focus marketing efforts on the users most likely NOT to convert as the others will anyhow. This allows to optimize the customer acquisition effort and reduce marketing / promotion expenses. It also allows to generate a ROI on the predictive tool through increased subscription.

# Business Case

Context: Release of an App with a fremium version having some premium features unlocked.
Upon installation, the user is offered a 24h trial with the full version unlocked.
Behavioral data (usage log) is collected when the App is used and the objective is to use this log to determine if the users will convert or not.
- what are the key variables to influence the choice?
- what is the accuracy of such a predictive model?

# Behavioral data (usage log)

The project uses activity log from users testing a mobile app.
The log is composed of screens visited by the user, whether he tried premium features or the minigame available on the app, whether he gave a feedback or not regarding the app, etc...
The log provides the first 24hrs of the app during the free trial.
Additional information in the dataset is:
- the user subscribed or not and when the subcription occured
This 'enrolled' variable is the label for our predictive model. 0 = not engaged, 1 = engaged (subscribed)

# Steps in the Notebook
- Data exploration
- Data pre-processing
- Train the model
- Anayze and interpret results
- Evaluate predictive performance of the model
- Use information generated by the model to identify potential improvement areas for the App

# Results

The model is able to predict subscription with 76% accuracy.
The model allows to flag users who will most likely NOT subscribe, allowing Marketing to target them immediately with special offers or discounts and increase the subscription ratio.
The model allows to identify the most important variables which either positively or negatively influence the conversion.
This can provides opportunities to revisit some functionalities causing users to decide not to subscribe

