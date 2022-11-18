![Gini logo](Gini_logo_blue.svg)

# Android Skills Challenge

We ask you to write an app that uses our Gini Bank SDK to extract payment information from German invoices.

In the [Resources](#resources) section, we listed links to our documentation, source code, and our example app. You are invited to use all of those resources to integrate the Gini Bank SDK into your app.

Please use the simplest integration option, which is called Screen API. This allows you to configure the SDK and launch it by starting an activity for result.

You don't have to utilise all features of the SDK. Use only the basic feature, which is taking a picture of a single page and retrieving the payment information.

You can take pictures of the test invoices by displaying them on your screen. You don’t need to print them out.

The app should store the extracted payment information and allow the user to view all their previous results. A basic UI example could be a list, where each item represents one invoice and by tapping on an item users can see all the extracted payment information.

The invoice’s image is not available so you don’t need to save the image. You only need to save the extracted payment information.

We are interested in seeing how you approach integrating our SDK into an app. We have no specific UI requirements.

Please don’t spend more than four hours on this.

You can either send us your project in a zip via email or send us a link to your repository. If you use GitHub and don't want to make your repository public then please invite the following two GitHub handles to view your repository: `zladzeyka` and `a-szotyori`.

Good luck solving this challenge!

# Requirements

* Use Gini Bank SDK’s Screen API to take pictures of German invoices and retrieve payment information.
* Save the payment information for each invoice. You can use a timestamp as an identifier for the invoice.
* Show a list of all invoices (without a picture).
* When selecting an invoice then show the saved payment information.

# Resources
* Guide: https://developer.gini.net/gini-mobile-android/bank-sdk/sdk 
* Source code: https://github.com/gini/gini-mobile-android/tree/main/bank-sdk 
* Example app: https://github.com/gini/gini-mobile-android/tree/main/bank-sdk/screen-api-example-app 
* Test invoices: located in this repository called `test_image.png` and `test_pdf.pdf`
* Credentials: will be sent via email
* Email for questions: team-mobile@gini.net
