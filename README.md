This repo contains the code that is used to create my resume site [jonbloomer.com.au](http://jonbloomer.com.au).  I used Facebook's excellent boilerplate [Create React App](https://github.com/facebookincubator/create-react-app) and enhanced it with the extra tools that I needed.

The whole application is based around this file `/src/resume.json` which is structured using the schema from [jsonresume.org](https://jsonresume.org/schema/). In `src/components/App.js` I think import this json object and assign each section to a data variable which is then passed in as a prop to the corresponding section component such as `src/components/About.js`.


