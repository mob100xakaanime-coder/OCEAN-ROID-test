OCEAN ROID - RENDER DEPLOY

Upload the CONTENTS of this folder to the ROOT of your GitHub repository.
Do NOT upload the outer folder itself.

GitHub root must show:
  package.json
  render.yaml
  backend/
  frontend/

Render settings:
  Service: Web Service
  Root Directory: blank
  Build Command: npm install
  Start Command: npm start
  Environment Variables: none required for this starter

Open:
  /          customer store
  /admin.html management dashboard

Initial admin login:
  email: admin@oceanroid.local
  password: admin12345

This starter stores data in backend/data JSON files. For production, move auth/data to a hosted database such as Supabase.
