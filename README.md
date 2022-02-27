# whistl - The Community Accessibility Bulletin

[GitHub Repository](https://github.com/namanmodani/whistl) | [Figma Prototype](https://www.figma.com/file/39obHkouG3yu8uLHtSNXsC/whistl?node-id=0%3A1)

## Inspiration

Roughly [15% of UCLA students reported having some type of disability](https://sairo.ucla.edu/file/4317cf06-d7d3-4464-95f6-dde3786e7820). We wanted to create an app that empowered differently-abled people to thrive and navigate UCLA with ease.

Sure, UCLA has the [best college campus in the nation](https://www.niche.com/colleges/search/best-college-campuses/). But it isn't perfect. Every now and then, we come across out-of-order elevators, damaged pavements, incorrectly-placed stop signs, poor lighting, lack of crossing mechanisms, and other issues that affect the ability of differently-abled persons to navigate campus.

So, creating a platform that allows members of the UCLA community to draw attention to these issues is one step towards making UCLA a more inclusive community.

## What it does

whistl is UCLA's Community Accessibility Bulletin. Essentially, whistl is a notice board for the UCLA community with a focus on accessibility-related issues on campus. Users hop on to the app and can primarily:

* report problems they see/experience around campus
* view recent incident reports by other users
* upvote issues that matter to them,

thus creating awareness and pushing for faster resolutions to these issues.

## How we built it

Our system can be accessed on virtually all devices, with 3 broad platforms:

* A mobile-responsive web app
* A WebView app for iOS
* A WebView app for Android

Firstly, we drew out sketches of our apps and subsequently put together prototypes in Figma. We then developed a mobile-responsive web app on the React framework, utilizing HTML, CSS, and JavaScript for the front-end. Additionally, we utilized ChakraUI and jQuery to give our app a better look and feel. We also utilized the Google Maps API to visualize report locations.

For our backend, we utilized BaaS Google Firebase, since this provided us with convenient authentication, databases, hosting, and analytics all in one place.

Finally, we created optimized WebView apps natively for both Android (Java) and iOS (Swift).

## Challenges we ran into

Two most significant challenges we encountered were:

* Efficiently using the Maps API to indicate locations intuitively. We spent a lot of time working around this.
* We also moderate difficulties making our app look great on all devices and screen sizes.

## Accomplishments we're proud of

* At the initial stage, we were able to put together a fully-functional prototype.
* Despite having a newbie team, we were able to work with moderately large tech stacks.
* We pulled off an ambitious and complex concept within 12 hours.

## What we learned

We definitely gained technical experience through this hackathon, but more importantly, it was rewarding in other ways. We learned how important it is to be accepting of each others' views and suggestions. All members of our team had different levels of experience in various fields of tech, and we learned to work to the strengths and weaknesses of each member. In fact, one of our members submitted a pull request for the first time today!

Often, our ideas conflicted, but we managed to work it out. The intense time pressure also taught us to manage our work and spread the load evenly. All in all, this was an incredible experience where we all grew academically and personally.

## What's next for whistl

After identifying the vital problem of making a community more accessible and taking a step in the right direction by implementing our web application, we believe that our journey doesn’t stop here.

We aim to add images and videos of the issues people report through our application.

Furthermore, we would like to focus on migrating to a React Native application, supporting different operating systems natively. This step would increase the performance of our application.

Moreover, we would improve our notification system, to provide more useful information to our community and better connect with local personnel.

Last but not least, we would like to build a moderation system to regulate potential abuse.
