# Dream Vacation App

## Setting Up CI CD With Git Actions

<img width="1440" height="819" alt="Screenshot 2025-08-05 at 4 56 43 AM" src="https://github.com/user-attachments/assets/c1ca8bfe-880a-4f39-beaa-28934c9e05b2" />



<img width="1440" height="819" alt="Screenshot 2025-08-05 at 4 57 17 AM" src="https://github.com/user-attachments/assets/b6c2c7e8-26bb-451e-abb4-a5d2b5885850" />

- GitHub runs this workflow automatically by using your saved secrets to log in securely to dockerhub.


## Step 1: Build the app
<img width="1440" height="900" alt="Screenshot 2025-07-19 at 8 57 05 AM" src="https://github.com/user-attachments/assets/3ce0defd-b470-4bf5-90c7-437172ba292e" />

- docker-compose builds all three images.
- Runs frontend, backend, and database containers.

## Step 2: Access your app 
<img width="800" height="500" alt="Screenshot 2025-07-19 at 8 57 47 AM" src="https://github.com/user-attachments/assets/0f5f9161-4605-4483-b839-14b41ce2d0e1" />

- Open http://localhost:3000 (React frontend)
- Backend API runs at http://localhost:3001

## Step 3: Make images publicly available on Docker Hub
<img width="1440" height="900" alt="Screenshot 2025-07-19 at 8 52 25 AM" src="https://github.com/user-attachments/assets/83d81059-aa2a-4330-8978-df956df75951" />

<img width="1440" height="822" alt="Screenshot 2025-07-19 at 5 25 04 AM" src="https://github.com/user-attachments/assets/f1034571-a1fd-48ef-b206-657b18e404d4" />


- The images are now publicly available on Docker Hub
