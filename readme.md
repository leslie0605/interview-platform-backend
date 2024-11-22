# Project README

This project consists of two components: a frontend and a backend. Both need to be set up and run separately. Follow the instructions below to get the system running.

---

## Frontend

To run the frontend, you need to:

1. Install [Node.js](https://nodejs.org/) and npm.
2. Navigate to the frontend directory in your terminal.
3. Run the following commands:
   ```bash
   npm install
   npm start
   ```

---

## Backend

TO RUN LOCALLY:
To start the backend:

1. conda activate 4347
2. pip install -r requirements.txt
3. python manage.py migrate
4. python manage.py runserver: will run on localhost:8000

RUN IN DOCKER(recommand):
run ./docker_run.sh

Please rerun ./docker_run.sh after code modification.

To connect to apis and AWS service:
create .env in root, should be like:
`
OPENAI_API_KEY=your-openai-api-key

    AWS_ACCESS_KEY_ID=your-aws-access-key

    AWS_SECRET_ACCESS_KEY=your-aws-secret-access-key

    AWS_STORAGE_BUCKET_NAME=your-aws-s3-bucket-name

    AWS_REGION_NAME=your-aws-region-name(ap-xxx-xx)
    `
