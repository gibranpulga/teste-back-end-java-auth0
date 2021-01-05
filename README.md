Test for Back-end Java Auth0 Developer

Hi ! 
We designed this test to better understand how you approach problems solving, and how you like to code. We try to get as close as possible to our reality, using technologies that we use and that tutorials can easily be found on the internet.
If you are unable or don't want to do one of the requirements, no problem. We will not disqualify you for that. In that case you can comment on it and tell why you skipped. 
We hope you enjoy it!

Below are the tasks. 
Some of the tasks are considered as bonuses, if you do not have time or prefer not to do, you can comment on how you would do or how the technical architecture would be:

- Create a simple users API. You must allow at least sign-up, login and logout. Use Spring BOOT; 
- Add social login using Auth0 - https://auth0.com (only Google is already good);
- Add functionality of sending activation link;
- Add MFA functionality (https://auth0.com/docs/mfa);
- DB can be chosen free at will (suggestion h2, postgres or mongo);
- Add swagger, as we won't have a front-end, we should be able to make all the flow through the swagger. Tip: document all fields;
- Do not forget the unit tests;
- Deliver the repository link in private mode (gitlab preference) with readme.MD with instructions on how to run locally and technical summary.

- Bonus: add these functions: list users, delete users, login and log out;
- Bonus: create dockerfile and docker-compose.yaml to deploy locally as a docker container;
- Bonus: create CI / CD gitlab file with 3 stages: compile, tests (if you have unit + integration, 1 stage for each) and dockerize (generate docker container);
- Bonus: deploy to a cloud provider (AWS preference, can be on EC2, or Azure or Heroku).
