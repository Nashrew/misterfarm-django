# misterfarm-django
This is a Django app primarily used to learn some Django itself as well as some Terraform

I have not worked on it in a week or so, when last I was working on it I had purchased a domain and began running into certificate issues that I still need to work through when I revisit the project.

I also need to add some actual models and endpoints so the app can actually do something - I had created an app that actually does something when first learning django, but when starting over with the intent of making something 'production ready' (still not quite there) and moving to a new environment I ended up focusing so much on terraform that I haven't added those endpoints back to this version of the app yet.
  - The intent is to just have a couple of endpoints to create a crop and retrieve harvests, with a separate batch job running elsewhere to harvest the crops
  - I got carried away with the terraform pieces and need to implement the actual functionality soon, but a different Java project has my attention for the moment

I am certainly open to making additions or adjustments as part of an interview process if requested.

(Credit where it's due, this article helped me tremendously when it came to implementing and learning about different aspects of Terraform and even some aspects of AWS - https://testdriven.io/blog/deploying-django-to-ecs-with-terraform/)
