# ehour2-i18n
Language files for eHour2.

There is a separate file for each supported language with ehour-i18n.properties being the default English text.

To add a new translation:
1. Clone this repository obviously.
2. Copy the ehour-i18.properties file and add a suffix indicating for the language you're adding. For example, to add Hungarian the filename would be ehour-i18_hu.properties.
3. Create a pull request including the changes you did.
4. After review your changes will be included in the next deployment to eHour's staging environment.

Tips for adding a translation:
1. Try to keep approx. the translation the same length (character wise) as the original English text. The UI is designed with the English text in mind.
2. The translations have variables which are substituted during runtime. Variables are written as {0}, {1}, etc. For instance, Approved on {1} by {0}. will transform to Approved on 11 November by John Doe.
3. Split long lines with a \. For example, have a look at user.profile.intime.body

Happy translating and thanks for your work!
