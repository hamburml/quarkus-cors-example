# start nodejs-localhost_3001
# start quarkus_8080
# open localhost:3001 which sends POST request to localhost:8080
# set custom header which forces preflight/options request
# should fail because POST method is not allowed in quarkus application.properties (only get and delete)
