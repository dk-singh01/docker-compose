# Manual installation

- Install Nodejs locally
- Clone this repo
- Install dependencies
- Start Database locally (docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres)
- change the .env file and update your DB credentials
- npx prisma migrate
- npx prisma generate
- npm run build
- npm run start


## Docker Installation
- Install docker 
- Start postgres 
  - docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
- Build the image -'docker build -t user-project'
- Start the image - 'docker run -p 3000:3000 user-project'

## Docker Compose installation steps
- Install docker, compose
- Run 'docker-compose up'