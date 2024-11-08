
## to initialize go module

go mod init user-microservice

## to install go dependency


go get github.com/joho/godotenv

go get github.com/mongodb/mongo-go-driver

go get github.com/gin-gonic/gin


## create account in mongodb atlas

### to run go application

go run main.go

## For Mongodb connection

Define the Variables:

export MONGO_USERNAME=<your_username>

export MONGO_PASSWORD=<your_password>

construct the "export MONGO_URI="mongodb+srv://$MONGO_USERNAME:$MONGO_PASSWORD@cluster0.azhly.mongodb.net/userdb?retryWrites=true&w=majority" and add in .env file