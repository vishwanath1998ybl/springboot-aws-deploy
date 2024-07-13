# springboot-aws-deploy
springboot-aws-deployThis is a sample microservice to deploy it on AWS ECS.

To build automated AWS CodePipeline and deploy microservice to AWS ECS, follow tutorial as shown in video :

Video Link :https://youtu.be/ARGmrYFfv44

Health Check command for AWS Task definition :

CMD-SHELL,curl -f http://localhost:8080/actuator/health || exit 1
Prerequisite :

AWS acconunt.
Git and docker installed on the machine.
Docker should be started before building docker image.
And your favourite code editor

