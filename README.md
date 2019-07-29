Cool, we have a nice yaml setup. Now in the terminal we execute
docker compose up
to fire up with the correct image etc. Now the actual jenkins should be available.

To check for your password that you will need for the first time check first which container id is associated with your newly ran container.

```
docker-compose exec jenkins bash
```

```
cat /var/jenkins_home/secrets/initialAdminPassword
```
