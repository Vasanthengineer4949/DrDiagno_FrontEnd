# Dr.Diagno
#### Dr.Diagno is an Artificial Intelligence based app which predicts the diseases or other health conditions based on the provided symptoms.

##### [Pesentartion about this app (Link to the PPT).](https://docs.google.com/presentation/d/1stXATFaBDL85zV4q5UVasmyiyTkJOv-LszQV9CKdIP8/edit?usp=sharing)
##### [Live demo app! (link)](https://dr-diagno.vercel.app/)
##### [Demo video! (link)](https://www.youtube.com/watch?v=sPlcFLZ2Hq8)
---
### How Dr.Diagno works:
1. Initially,the user is prompted to create an account. This helps in keeping track of the user's past predictions and some other vital information.
2. The next page requests for the information which the app requires to carry out the diagnostic, which are Sympotoms, temperature and the number of days the user has been experiencing the symptoms.
3. The data given by the user is transfered to the backend(django) which contains the MachineLearning models that predict and return the most possible diseases to the app.
4. The app then generates a graph that depicts the results processsed by the MachineLearning models.
5. After the prediction phase, details like the disease description and the appropriate precautions are loaded onto the home screen, so that the user can get a few more insights about his condition.

---

### Tech Stack
* Front-End: React, Chart.js, Material UI
* Back-End: Django Rest Framework, JSON Web Token(JWT)
* Database: PostGreSQL
* AI: Catboost Algorithm from Catboost package

---
## How to run this app:
Clone this repository
### `git clone https://github.com/GanapathyPT/Dr.Diagno_Frontend.git`

change the directory
### `cd Dr.Diagno_Frontend`

Install the requirements
### `yarn`




In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.



### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

