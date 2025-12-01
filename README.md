INSTRUCTIONS   

1. Clone  repository --> git clone https://github.com/philoholy/salvationcentral-backend.git
2. Navigate to the project --> cd salvationcentral-backend
3. Install dependencies --> npm install
4. Set up PostgreSQL database (create database named 'salvationcentral')
5. Create a .env file in the root
   --> DATABASE_URL=postgresql://username:password@localhost:5432/salvationcentral // of course, you must decide your own username and password
   --> JWT_SECRET=unassigned_as_of_right_now_tba
   --> PORT=5000
   
6. Start server --> npm run dev
7. Backend now available at http://localhost:5000
