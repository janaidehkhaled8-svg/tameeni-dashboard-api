# Render Deployment Configuration
# Backend API for Tameeni Dashboard

## Environment Variables
- PORT: 3000 (or any available port)
- NODE_ENV: production

## Build Command
npm install

## Start Command
npm start

## Database
- SQLite database file: tameeni_data.db
- Auto-created on first run
- Stores all form submissions and analytics

## API Endpoints
- POST /api/step1 - Collect step 1 data
- POST /api/step2 - Collect step 2 data  
- POST /api/step3 - Collect step 3 data
- POST /api/step4 - Collect step 4 data
- POST /api/final - Collect final data
- GET /api/submissions - Get all submissions
- GET /api/stats - Get quick statistics

## Health Check
- Root endpoint (/) shows API status
- Returns JSON responses for all API calls