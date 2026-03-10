This restaurant reservation system is a web-based platform with two key dashboards for users and restaurants. Customers can:
- Search for restaurants
- Filter based on preferences
- Reserve tables
- Edit and cancel reservations

Restaurant owner can:
- Add Restaurant and Edit Restaurant
- View table bookings

The system ensures transparency and user convenience, offering modification and deletion capabilities for reservations.

### Backend Setup
Create a `.env` file with the following contents:
```bash
MONGO_URI=<your mongo url>
JWT_SECRET=<your secret>
email=<your email>
password=<your password>
CLIENT_ID=<Your ClientId of OAuth>
CLIENT_SECRET=<Your Client Secret of OAuth>
SESSION_SECRET=<Your session secret>
port=<port>
BACKEND_URL=http://localhost:port
FRONTEND_URL=http://localhost:frontend port
```

In VSCode terminal:
```bash
cd Backend
npm install
# To run Backend
npm run dev
```

### Frontend Setup
Create a `.env` file with the following contents:
```bash
REACT_APP_API_URL=http://localhost:backendport
REACT_APP_WS_URL=ws://localhost:backendport
```

In VSCode terminal:
```bash
cd Frontend
npm install
# To run Frontend
npm start
```
