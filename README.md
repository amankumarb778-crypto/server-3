🌍 State Statistics Management REST API

A RESTful API built using Node.js, Express.js, and CORS for managing and analyzing state statistics data such as population, literacy rate, and GDP.

This API supports:

Retrieve all states

Retrieve state by ID

Get state with highest GDP

Create new state records

Full state updates

Population updates

Literacy updates

GDP updates

Partial updates

Delete GDP field

Delete states with low literacy

Delete state by ID

🔗 Project Links

📂 GitHub Repository
https://github.com/amankumarb778-crypto/server-3.git

🚀 Live Deployment (Render)
https://server-3-4954.onrender.com

📘 Postman API Documentation
https://documenter.getpostman.com/view/50839281/2sBXcKCduZ

🚀 Tech Stack

Node.js

Express.js

CORS

ES Modules (import/export)

🌍 Base URL

Local

http://localhost:3000

Production

https://server-3-4954.onrender.com
📌 API Endpoints
1️⃣ Get All States
GET /states

Example:

https://server-3-4954.onrender.com/states
2️⃣ Get State by ID
GET /states/:id

Example:

https://server-3-4954.onrender.com/states/3
3️⃣ Get State with Highest GDP
GET /states/highest-gdp

Example:

https://server-3-4954.onrender.com/states/highest-gdp
4️⃣ Create New State
POST /states

Creates a new state record.

5️⃣ Update Full State
PUT /states

Updates full state data.

6️⃣ Update State Data
PUT /states

Updates state information.

7️⃣ Update State Population
PUT /states/:id/population

Example:

https://server-3-4954.onrender.com/states/1/population
8️⃣ Update State Literacy
PATCH /states/:id/literacy

Example:

https://server-3-4954.onrender.com/states/1/literacy
9️⃣ Update State GDP
PATCH /states/:id/gdp

Example:

https://server-3-4954.onrender.com/states/1/gdp
🔟 Partial Update State
PATCH /states/:id

Example:

https://server-3-4954.onrender.com/states/1
1️⃣1️⃣ Delete State GDP
DELETE /states/:id/gdp

Example:

https://server-3-4954.onrender.com/states/1/gdp
1️⃣2️⃣ Delete States with Low Literacy
DELETE /states/low-literacy/:percentage

Example:

https://server-3-4954.onrender.com/states/low-literacy/40

Deletes states with literacy below the given percentage.

1️⃣3️⃣ Delete State by ID
DELETE /states/:id

Example:

https://server-3-4954.onrender.com/states/12
📦 State Data Structure

Example state object:

{
  "id": 1,
  "stateName": "Maharashtra",
  "population": 124000000,
  "literacy": 89,
  "gdp": 400
}
🛠 Installation (Local Setup)

Clone the repository

git clone https://github.com/amankumarb778-crypto/server-3.git

Install dependencies

npm install

Run the server

node server.js

Server runs at

http://localhost:3000
